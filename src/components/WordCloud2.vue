<template>
    <div id="wordCloud2" class="chart-container"
         style="border: 0px solid white;position: absolute;left: 400px;margin-top: 285px"
         :style="{width: 490 + 'px', height: 490 + 'px'}">
    </div>
</template>

<script>
import * as echarts from 'echarts';
import 'echarts-wordcloud';
import macarons from '@/static/macarons';
import Vue from '@/static/vue'

export default {
    name: "WordCloud2",
    mounted() {
        var dom=document.getElementById('wordCloud2')
        var chart_db44377482fa4b64966ba0d655436233 = echarts.init(dom);
        var option_db44377482fa4b64966ba0d655436233 = {
            "animation": true,
            "animationThreshold": 2000,
            "animationDuration": 1000,
            "animationEasing": "cubicOut",
            "animationDelay": 0,
            "animationDurationUpdate": 300,
            "animationEasingUpdate": "cubicOut",
            "animationDelayUpdate": 0,
            "series": [
                {
                    "type": "wordCloud",
                    "name": "\u8bcd\u9891",
                    "shape": "diamond",
                    "rotationRange": [
                        0,
                        0
                    ],
                    "rotationStep": 45,
                    "girdSize": 20,
                    "sizeRange": [
                        15,
                        108
                    ],
                    "data": [
                        {
                            "name": "\u597d\u597d",
                            "value": 14653,
                            "textStyle": {

                                    "color": "rgb(24,121,2)"

                            }
                        },
                        {
                            "name": "\u53ef\u7231",
                            "value": 6711,
                            "textStyle": {

                                    "color": "rgb(152,24,76)"

                            }
                        },
                        {
                            "name": "\u8001\u516c",
                            "value": 6389,
                            "textStyle": {

                                    "color": "rgb(0,57,29)"

                            }
                        },
                        {
                            "name": "\u5411\u665a",
                            "value": 3270,
                            "textStyle": {

                                    "color": "rgb(103,1,106)"

                            }
                        },
                        {
                            "name": "\u4e00\u4e2a",
                            "value": 2772,
                            "textStyle": {

                                    "color": "rgb(68,126,45)"

                            }
                        },
                        {
                            "name": "\u8d1d\u62c9",
                            "value": 2495,
                            "textStyle": {

                                    "color": "rgb(134,51,56)"

                            }
                        },
                        {
                            "name": "\u6536\u5230",
                            "value": 2319,
                            "textStyle": {

                                    "color": "rgb(91,106,146)"

                            }
                        },
                        {
                            "name": "\u559c\u6b22",
                            "value": 2044,
                            "textStyle": {

                                    "color": "rgb(86,80,75)"

                            }
                        },
                        {
                            "name": "\u963f\u8428",
                            "value": 1787,
                            "textStyle": {

                                    "color": "rgb(156,32,137)"

                            }
                        },
                        {
                            "name": "\u4e0d\u662f",
                            "value": 1747,
                            "textStyle": {

                                    "color": "rgb(138,122,124)"

                            }
                        },
                        {
                            "name": "\u6ca1\u6709",
                            "value": 1675,
                            "textStyle": {

                                    "color": "rgb(67,41,63)"

                            }
                        },
                        {
                            "name": "\u597d\u542c",
                            "value": 1619,
                            "textStyle": {

                                    "color": "rgb(30,52,32)"

                            }
                        },
                        {
                            "name": "\u5fc3\u5fc3",
                            "value": 1530,
                            "textStyle": {

                                    "color": "rgb(75,122,118)"

                            }
                        },
                        {
                            "name": "\u600e\u4e48",
                            "value": 1468,
                            "textStyle": {

                                    "color": "rgb(12,52,74)"

                            }
                        },
                        {
                            "name": "\u771f\u7684",
                            "value": 1411,
                            "textStyle": {

                                    "color": "rgb(121,11,126)"

                            }
                        },
                        {
                            "name": "\u53ef\u4ee5",
                            "value": 1312,
                            "textStyle": {

                                    "color": "rgb(4,92,148)"

                            }
                        },
                        {
                            "name": "\u5c31\u662f",
                            "value": 1312,
                            "textStyle": {

                                    "color": "rgb(14,56,86)"

                            }
                        },
                        {
                            "name": "\u6211\u4eec",
                            "value": 1310,
                            "textStyle": {

                                    "color": "rgb(111,135,88)"

                            }
                        },
                        {
                            "name": "\u76f4\u64ad",
                            "value": 1304,
                            "textStyle": {

                                    "color": "rgb(20,84,160)"

                            }
                        },
                        {
                            "name": "\u725b\u86d9",
                            "value": 1300,
                            "textStyle": {

                                    "color": "rgb(103,132,157)"

                            }
                        },
                        {
                            "name": "\u5927\u5934",
                            "value": 1113,
                            "textStyle": {

                                    "color": "rgb(64,81,40)"

                            }
                        },
                        {
                            "name": "\u77e5\u9053",
                            "value": 1080,
                            "textStyle": {

                                    "color": "rgb(35,140,16)"

                            }
                        },
                        {
                            "name": "\u65f6\u5019",
                            "value": 1055,
                            "textStyle": {

                                    "color": "rgb(115,87,2)"

                            }
                        },
                        {
                            "name": "\u5988\u5988",
                            "value": 1051,
                            "textStyle": {

                                    "color": "rgb(29,45,42)"

                            }
                        },
                        {
                            "name": "\u5c0f\u59d0",
                            "value": 1044,
                            "textStyle": {

                                    "color": "rgb(39,79,81)"

                            }
                        },
                        {
                            "name": "\u751c\u751c",
                            "value": 943,
                            "textStyle": {

                                    "color": "rgb(51,23,63)"

                            }
                        },
                        {
                            "name": "\u4e00\u4e0b",
                            "value": 931,
                            "textStyle": {

                                    "color": "rgb(9,33,155)"

                            }
                        },
                        {
                            "name": "\u8fd8\u662f",
                            "value": 927,
                            "textStyle": {

                                    "color": "rgb(94,103,67)"

                            }
                        },
                        {
                            "name": "\u89c6\u9891",
                            "value": 927,
                            "textStyle": {

                                    "color": "rgb(21,12,22)"

                            }
                        },
                        {
                            "name": "\u8fd9\u4e48",
                            "value": 915,
                            "textStyle": {

                                    "color": "rgb(80,89,33)"

                            }
                        },
                        {
                            "name": "\u4eca\u5929",
                            "value": 913,
                            "textStyle": {

                                    "color": "rgb(102,106,69)"

                            }
                        },
                        {
                            "name": "\u5feb\u4e50",
                            "value": 912,
                            "textStyle": {

                                    "color": "rgb(69,136,0)"

                            }
                        },
                        {
                            "name": "\u5df2\u7ecf",
                            "value": 861,
                            "textStyle": {

                                    "color": "rgb(91,29,6)"

                            }
                        },
                        {
                            "name": "\u554a\u554a\u554a",
                            "value": 857,
                            "textStyle": {

                                    "color": "rgb(91,14,44)"

                            }
                        },
                        {
                            "name": "\u611f\u89c9",
                            "value": 856,
                            "textStyle": {

                                    "color": "rgb(99,154,151)"

                            }
                        }
                    ],
                    "drawOutOfBound": false,
                    "textStyle": {
                        "normal": {
                            "fontFamily": "cursive"
                        },
                        "emphasis": {}
                    }
                }
            ],
            "legend": [
                {
                    "data": [],
                    "selected": {},
                    "show": true,
                    "padding": 5,
                    "itemGap": 10,
                    "itemWidth": 25,
                    "itemHeight": 14
                }
            ],
            "tooltip": {
                "show": true,
                "trigger": "item",
                "triggerOn": "mousemove|click",
                "axisPointer": {
                    "type": "line"
                },
                "showContent": true,
                "alwaysShowContent": false,
                "showDelay": 0,
                "hideDelay": 100,
                "textStyle": {
                    "fontSize": 14
                },
                "backgroundColor": "red",
                "borderColor": "yellow",
                "borderWidth": 0,
                "padding": 5
            },
            "title": [
                {
                    // "text": "\u8bc4\u8bba\u4e91\u56fe",
                    "padding": 5,
                    "itemGap": 10
                }
            ],
            "toolbox": {
                "show": false,
                "orient": "vertical",
                "itemSize": 15,
                "itemGap": 10,
                "left": "80%",
                "feature": {
                    "saveAsImage": {
                        "type": "png",
                        "backgroundColor": "auto",
                        "connectedBackgroundColor": "#fff",
                        "show": true,
                        "title": "\u4fdd\u5b58\u4e3a\u56fe\u7247",
                        "pixelRatio": 1
                    },
                    "restore": {
                        "show": true,
                        "title": "\u8fd8\u539f"
                    },
                    "dataView": {
                        "show": true,
                        "title": "\u6570\u636e\u89c6\u56fe",
                        "readOnly": false,
                        "lang": [
                            "\u6570\u636e\u89c6\u56fe",
                            "\u5173\u95ed",
                            "\u5237\u65b0"
                        ],
                        "backgroundColor": "#fff",
                        "textareaColor": "#fff",
                        "textareaBorderColor": "#333",
                        "textColor": "#000",
                        "buttonColor": "#c23531",
                        "buttonTextColor": "#fff"
                    },
                    "dataZoom": {
                        "show": true,
                        "title": {
                            "zoom": "\u533a\u57df\u7f29\u653e",
                            "back": "\u533a\u57df\u7f29\u653e\u8fd8\u539f"
                        },
                        "icon": {},
                        "xAxisIndex": false,
                        "yAxisIndex": false,
                        "filterMode": "filter"
                    },
                    "magicType": {
                        "show": true,
                        "type": [
                            "line",
                            "bar",
                            "stack",
                            "tiled"
                        ],
                        "title": {
                            "line": "\u5207\u6362\u4e3a\u6298\u7ebf\u56fe",
                            "bar": "\u5207\u6362\u4e3a\u67f1\u72b6\u56fe",
                            "stack": "\u5207\u6362\u4e3a\u5806\u53e0",
                            "tiled": "\u5207\u6362\u4e3a\u5e73\u94fa"
                        },
                        "icon": {}
                    },
                    "brush": {
                        "icon": {},
                        "title": {
                            "rect": "\u77e9\u5f62\u9009\u62e9",
                            "polygon": "\u5708\u9009",
                            "lineX": "\u6a2a\u5411\u9009\u62e9",
                            "lineY": "\u7eb5\u5411\u9009\u62e9",
                            "keep": "\u4fdd\u6301\u9009\u62e9",
                            "clear": "\u6e05\u9664\u9009\u62e9"
                        }
                    }
                }
            }
        };
        chart_db44377482fa4b64966ba0d655436233.setOption(option_db44377482fa4b64966ba0d655436233);
    }
}
</script>

<style scoped>

</style>
