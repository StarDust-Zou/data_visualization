<template>
    <div id="myChart3" style="border: 0px solid gray;position: absolute;left: 810px;top:0;"
         :style="{width: width + 'px', height: height + 'px'}" >
        <div></div>
    </div>
</template>

<script>
import echarts from '@/static/echarts'

export default {
    beforeCreate() {
        this.$nextTick(()=>{
            document.body.setAttribute('style', 'background:#000')
        })
    },
    data(){
        return{
            width:700,
            height:750,
        }
    },
    mounted() {
        var chartDom = document.getElementById('myChart3');
        var myChart = echarts.init(chartDom);
        var option;

        option = {
            // backgroundColor: "#000",
            title: {
                text: "",
                subtext: "",
                left:'center',
                textStyle: {
                    color: "#fff",
                    fontSize: "22",
                },
                subtextStyle: {
                    color: "#90979c",
                    fontSize: "16",
                },
            },
            tooltip: {
                trigger: "axis",
                axisPointer: {
                    type: "shadow",
                },
                backgroundColor: "rgba(255,255,255,0.1)", //设置背景颜色
                textStyle: {
                    color: "white" //设置文字颜色
                },
                borderColor: "rgba(255,255,255,0.1)", //设置边框颜色
            },
            grid: {
                borderWidth: 0,
                top: 80,
                bottom: 70,
                textStyle: {
                    color: "#fff",
                },
            },
            legend: [{
                orient : 'horizontal',
                data: ["该时间段使用b站用户数", "该时间段up主投稿视频数"],
                right: 10,
                top: 24,
                textStyle: {
                    color: "#fff",
                },
                itemWidth: 12,
                itemHeight: 10,
                //itemGap: 35
            },
                {
                    orient : 'horizontal',
                    data: ["用户使用b站时间段趋势", "up主投稿视频时间段趋势"],
                    right: 10,
                    top: 42,
                    textStyle: {
                        color: "#fff",
                    },
                    itemWidth: 12,
                    itemHeight: 10,
                    //itemGap: 35
                }
            ],
            xAxis: {
                position: "center",
                data: ["0:00-7:00", "7:00-10:00", "10:00-13:00", "13:00-16:00", "16:00-19:00", "19:00-22:00", "22:00-0:00"],
            },
            yAxis: [
                {
                    type: "value",
                    max: 100,
                    inverse: true,
                },
                {
                    type: "value",
                    max: 500,
                },
            ],
            dataZoom: [
                {
                    show: true,
                    height: 12,
                    xAxisIndex: [0],
                    bottom: "8%",
                    start: 0,
                    end: 100,
                    handleIcon:
                        "path://M306.1,413c0,2.2-1.8,4-4,4h-59.8c-2.2,0-4-1.8-4-4V200.8c0-2.2,1.8-4,4-4h59.8c2.2,0,4,1.8,4,4V413z",
                    handleSize: "110%",
                    handleStyle: {
                        color: "#d3dee5",
                    },
                    textStyle: {
                        color: "#fff",
                    },
                    borderColor: "#90979c",
                },
                {
                    type: "inside",
                    show: true,
                    height: 15,
                    start: 1,
                    end: 35,
                },
            ],
            series: [
                {
                    name:"该时间段使用b站用户数",
                    type: "bar",
                    yAxisIndex: 0, //对应左y轴
                    barGap: "-100%",
                    barMaxWidth: 35,
                    itemStyle: {
                        normal: {
                            barBorderRadius: 5,
                            color: new echarts.graphic.LinearGradient(0, 0, 0, 1, [
                                { offset: 0, color: "#f83710" },
                                { offset: 1, color: "#cd4e35" },
                            ]),
                        },
                    },
                    data: [17, 13, 33, 19, 17, 55, 59],
                },
                {
                    name:"该时间段up主投稿视频数",
                    type: "bar",
                    yAxisIndex: 1, //对应右y轴
                    barMaxWidth: 35,
                    itemStyle: {
                        normal: {
                            barBorderRadius: 5,
                            color: new echarts.graphic.LinearGradient(0, 0, 0, 1, [
                                { offset: 0, color: "#14c8d4" },
                                { offset: 1, color: "#43eec6" },
                            ]),
                        },
                    },
                    data: [11, 11, 188, 53, 339, 193, 32],
                },
                {
                    name: "用户使用b站时间段趋势",
                    type: "line",
                    symbolSize: 10,
                    symbol: "circle",
                    itemStyle: {
                        normal: {
                            color: "rgba(252,230,48,1)",
                            barBorderRadius: 0,
                            label: {
                                show: false, //折线图中的曲线数据不显示
                                position: "top",
                                formatter: function (p) {
                                    return p.value > 0 ? p.value : "";
                                },
                            },
                        },
                    },
                    data: [
                        17, 13, 33, 19, 17, 55, 59
                    ],
                },
                {
                    name: "up主投稿视频时间段趋势",
                    type: "line",
                    symbolSize: 10,
                    symbol: "circle",
                    yAxisIndex: 1,
                    itemStyle: {
                        normal: {
                            color: "white",
                            barBorderRadius: 0,
                            label: {
                                show: false,
                                position: "top",
                                formatter: function (p) {
                                    return p.value > 0 ? p.value : "";
                                },
                            },
                        },
                    },
                    data: [
                        11, 11, 188, 53, 339, 193, 32
                    ],

                },
            ],
        };
        var app = {
            currentIndex: -1,
        };
        setInterval(function () {
            var dataLen = option.series[0].data.length;

            // 取消之前高亮的图形
            myChart.dispatchAction({
                type: "downplay",
                seriesIndex: 0,
                dataIndex: app.currentIndex,
            });
            app.currentIndex = (app.currentIndex + 1) % dataLen;
            //console.log(app.currentIndex);
            // 高亮当前图形
            myChart.dispatchAction({
                type: "highlight",
                seriesIndex: 0,
                dataIndex: app.currentIndex,
            });
            // 显示 tooltip
            myChart.dispatchAction({
                type: "showTip",
                seriesIndex: 0,
                dataIndex: app.currentIndex,
            });
        }, 1000);

        option && myChart.setOption(option);

    }
}
</script>

<style scoped>

</style>
