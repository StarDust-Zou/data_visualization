<template>
    <div id="wordCloud1" class="chart-container"
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
    name: "WordCloud1",
    mounted() {
        var dom=document.getElementById('wordCloud1')
        var chart_7c3c7406761b44dda996e668b9952741 = echarts.init(dom);
        var option_7c3c7406761b44dda996e668b9952741 = {
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
                            "name": "\u554a\u554a\u554a",
                            "value": 6195,
                            "textStyle": {

                                    "color": "rgb(157,15,78)"

                            }
                        },
                        {
                            "name": "\u771f\u7684",
                            "value": 4176,
                            "textStyle": {

                                    "color": "rgb(31,92,48)"

                            }
                        },
                        {
                            "name": "\u5c31\u662f",
                            "value": 3850,
                            "textStyle": {

                                    "color": "rgb(80,48,115)"

                            }
                        },
                        {
                            "name": "\u4e0d\u662f",
                            "value": 3330,
                            "textStyle": {

                                    "color": "rgb(64,61,131)"

                            }
                        },
                        {
                            "name": "\u4e00\u4e2a",
                            "value": 3093,
                            "textStyle": {

                                    "color": "rgb(7,90,35)"

                            }
                        },
                        {
                            "name": "\u6ca1\u6709",
                            "value": 2853,
                            "textStyle": {

                                    "color": "rgb(21,32,61)"

                            }
                        },
                        {
                            "name": "\u89c9\u5f97",
                            "value": 2513,
                            "textStyle": {

                                    "color": "rgb(20,65,40)"

                            }
                        },
                        {
                            "name": "\u53ef\u4ee5",
                            "value": 2207,
                            "textStyle": {

                                    "color": "rgb(129,108,81)"

                            }
                        },
                        {
                            "name": "\u611f\u89c9",
                            "value": 1941,
                            "textStyle": {

                                    "color": "rgb(105,34,136)"

                            }
                        },
                        {
                            "name": "\u559c\u6b22",
                            "value": 1916,
                            "textStyle": {
                                    "color": "rgb(72,108,138)"

                            }
                        },
                        {
                            "name": "\u52a8\u753b",
                            "value": 1881,
                            "textStyle": {

                                    "color": "rgb(138,44,123)"

                            }
                        },
                        {
                            "name": "\u5267\u60c5",
                            "value": 1752,
                            "textStyle": {

                                    "color": "rgb(71,107,1)"

                            }
                        },
                        {
                            "name": "\u8fd8\u662f",
                            "value": 1671,
                            "textStyle": {

                                    "color": "rgb(96,109,142)"

                            }
                        },
                        {
                            "name": "\u7b2c\u4e00",
                            "value": 1670,
                            "textStyle": {

                                    "color": "rgb(26,155,15)"

                            }
                        },
                        {
                            "name": "\u56e0\u4e3a",
                            "value": 1620,
                            "textStyle": {

                                    "color": "rgb(129,62,47)"

                            }
                        },
                        {
                            "name": "\u8f9b\u82e6",
                            "value": 1614,
                            "textStyle": {

                                    "color": "rgb(132,79,158)"
                                }

                        },
                        {
                            "name": "\u65f6\u5019",
                            "value": 1608,
                            "textStyle": {

                                    "color": "rgb(9,76,45)"

                            }
                        },
                        {
                            "name": "\u6211\u4eec",
                            "value": 1591,
                            "textStyle": {

                                    "color": "rgb(59,56,85)"

                            }
                        },
                        {
                            "name": "\u53ef\u80fd",
                            "value": 1525,
                            "textStyle": {

                                    "color": "rgb(34,30,147)"
                                }

                        },
                        {
                            "name": "\u4f46\u662f",
                            "value": 1516,
                            "textStyle": {

                                    "color": "rgb(17,25,93)"

                            }
                        },
                        {
                            "name": "\u77e5\u9053",
                            "value": 1454,
                            "textStyle": {

                                    "color": "rgb(46,10,103)"

                            }
                        },
                        {
                            "name": "\u9a6c\u514b",
                            "value": 1440,
                            "textStyle": {

                                    "color": "rgb(46,49,112)"

                            }
                        },
                        {
                            "name": "\u7535\u5f71",
                            "value": 1398,
                            "textStyle": {

                                    "color": "rgb(133,135,39)"

                            }
                        },
                        {
                            "name": "\u51f9\u51f8",
                            "value": 1357,
                            "textStyle": {

                                    "color": "rgb(148,115,31)"

                            }
                        },
                        {
                            "name": "\u4e16\u754c",
                            "value": 1353,
                            "textStyle": {

                                    "color": "rgb(67,124,35)"

                            }
                        },
                        {
                            "name": "\u73b0\u5728",
                            "value": 1316,
                            "textStyle": {

                                    "color": "rgb(84,11,132)"

                            }
                        },
                        {
                            "name": "\u770b\u5230",
                            "value": 1260,
                            "textStyle": {

                                    "color": "rgb(140,12,113)"

                            }
                        },
                        {
                            "name": "\u8fd9\u4e48",
                            "value": 1234,
                            "textStyle": {

                                    "color": "rgb(42,25,82)"

                            }
                        },
                        {
                            "name": "\u51fa\u6765",
                            "value": 1215,
                            "textStyle": {

                                    "color": "rgb(139,21,0)"

                            }
                        },
                        {
                            "name": "\u4e2a\u4eba",
                            "value": 1207,
                            "textStyle": {

                                    "color": "rgb(58,129,45)"

                            }
                        },
                        {
                            "name": "\u4ed6\u4eec",
                            "value": 1204,
                            "textStyle": {

                                    "color": "rgb(80,89,11)"

                            }
                        },
                        {
                            "name": "\u600e\u4e48",
                            "value": 1185,
                            "textStyle": {

                                    "color": "rgb(81,146,160)"

                            }
                        },
                        {
                            "name": "\u6240\u4ee5",
                            "value": 1180,
                            "textStyle": {

                                    "color": "rgb(23,5,129)"

                            }
                        },
                        {
                            "name": "\u90a3\u4e2a",
                            "value": 1168,
                            "textStyle": {

                                    "color": "rgb(78,74,124)"

                            }
                        },
                        {
                            "name": "\u8fd8\u6709",
                            "value": 1168,
                            "textStyle": {

                                    "color": "rgb(54,1,39)"

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
                // "show": true,
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
        chart_7c3c7406761b44dda996e668b9952741.setOption(option_7c3c7406761b44dda996e668b9952741);
    }
}
</script>

<style scoped>

</style>
