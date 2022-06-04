<template>
    <div id="wordCloud12" class="chart-container"
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
    name: "WordCloud12",
    mounted() {
        var dom=document.getElementById('wordCloud12')
        var chart_b587227c7ccf443ba4ba853a9907c4d9 = echarts.init(dom);
        var option_b587227c7ccf443ba4ba853a9907c4d9 = {
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
                            "name": "\u57fa\u4f6c",
                            "value": 25532,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(51,138,110)"
                                // }
                            }
                        },
                        {
                            "name": "\u767d\u9f20",
                            "value": 6925,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(17,9,134)"
                                // }
                            }
                        },
                        {
                            "name": "\u72ee\u5b50",
                            "value": 3342,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(146,101,49)"
                                // }
                            }
                        },
                        {
                            "name": "\u9b3c\u755c",
                            "value": 2890,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(91,111,73)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e00\u4e2a",
                            "value": 2416,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(44,113,149)"
                                // }
                            }
                        },
                        {
                            "name": "\u89c6\u9891",
                            "value": 2155,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(32,141,135)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e0d\u662f",
                            "value": 1655,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(134,48,110)"
                                // }
                            }
                        },
                        {
                            "name": "\u6211\u4eec",
                            "value": 1514,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(101,100,82)"
                                // }
                            }
                        },
                        {
                            "name": "\u5c31\u662f",
                            "value": 1419,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(69,30,64)"
                                // }
                            }
                        },
                        {
                            "name": "\u5c40\u957f",
                            "value": 1326,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(79,135,18)"
                                // }
                            }
                        },
                        {
                            "name": "\u5927\u7237",
                            "value": 1316,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(99,97,73)"
                                // }
                            }
                        },
                        {
                            "name": "\u6ca1\u6709",
                            "value": 1266,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(114,107,94)"
                                // }
                            }
                        },
                        {
                            "name": "\u6e38\u620f",
                            "value": 1220,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(80,61,27)"
                                // }
                            }
                        },
                        {
                            "name": "\u8def\u4eba",
                            "value": 1213,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(128,77,17)"
                                // }
                            }
                        },
                        {
                            "name": "\u73b0\u5728",
                            "value": 1175,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(78,107,104)"
                                // }
                            }
                        },
                        {
                            "name": "\u771f\u7684",
                            "value": 1123,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(138,105,148)"
                                // }
                            }
                        },
                        {
                            "name": "\u65f6\u5019",
                            "value": 1121,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(105,28,39)"
                                // }
                            }
                        },
                        {
                            "name": "\u90a3\u4e2a",
                            "value": 1114,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(108,88,131)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e0d\u8981",
                            "value": 1057,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(115,61,130)"
                                // }
                            }
                        },
                        {
                            "name": "\u53ef\u4ee5",
                            "value": 1019,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(105,24,100)"
                                // }
                            }
                        },
                        {
                            "name": "\u770b\u5230",
                            "value": 1000,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(15,99,44)"
                                // }
                            }
                        },
                        {
                            "name": "\u77e5\u9053",
                            "value": 988,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(83,3,119)"
                                // }
                            }
                        },
                        {
                            "name": "\u8fd8\u662f",
                            "value": 947,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(7,130,132)"
                                // }
                            }
                        },
                        {
                            "name": "\u5df2\u7ecf",
                            "value": 894,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(6,91,147)"
                                // }
                            }
                        },
                        {
                            "name": "\u600e\u4e48",
                            "value": 844,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(15,90,26)"
                                // }
                            }
                        },
                        {
                            "name": "\u5f39\u5e55",
                            "value": 834,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(123,67,62)"
                                // }
                            }
                        },
                        {
                            "name": "\u60c5\u4fa3",
                            "value": 831,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(46,74,46)"
                                // }
                            }
                        },
                        {
                            "name": "\u6c42\u751f",
                            "value": 804,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(90,81,51)"
                                // }
                            }
                        },
                        {
                            "name": "\u80a5\u7682",
                            "value": 753,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(26,152,157)"
                                // }
                            }
                        },
                        {
                            "name": "\u7ed3\u5c40",
                            "value": 751,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(145,45,56)"
                                // }
                            }
                        },
                        {
                            "name": "\u559c\u6b22",
                            "value": 723,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(83,33,7)"
                                // }
                            }
                        },
                        {
                            "name": "\u71c3\u70e7",
                            "value": 695,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(122,100,79)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e4b\u8def",
                            "value": 687,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(91,81,58)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e00\u6b21",
                            "value": 669,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(129,130,138)"
                                // }
                            }
                        },
                        {
                            "name": "\u6807\u51c6",
                            "value": 669,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(41,146,80)"
                                // }
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
        chart_b587227c7ccf443ba4ba853a9907c4d9.setOption(option_b587227c7ccf443ba4ba853a9907c4d9);
    }
}
</script>

<style scoped>

</style>
