<template>
    <div id="wordCloud10" class="chart-container"
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
    name: "WordCloud10",
    mounted() {
        var dom=document.getElementById('wordCloud10')
        var chart_4c980fcb25764686aff8de19162e4261 = echarts.init(dom);
        var option_4c980fcb25764686aff8de19162e4261 = {
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
                            "name": "\u5bb3\u6015",
                            "value": 4806,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(145,56,118)"
                                // }
                            }
                        },
                        {
                            "name": "\u89c6\u9891",
                            "value": 2337,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(31,27,28)"
                                // }
                            }
                        },
                        {
                            "name": "\u53ef\u7231",
                            "value": 2315,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(139,75,47)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e00\u4e2a",
                            "value": 2177,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(36,51,27)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e0d\u662f",
                            "value": 1949,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(74,10,80)"
                                // }
                            }
                        },
                        {
                            "name": "\u559c\u6b22",
                            "value": 1692,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(102,59,84)"
                                // }
                            }
                        },
                        {
                            "name": "\u771f\u7684",
                            "value": 1653,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(97,49,46)"
                                // }
                            }
                        },
                        {
                            "name": "\u6ca1\u6709",
                            "value": 1631,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(159,100,32)"
                                // }
                            }
                        },
                        {
                            "name": "\u5c31\u662f",
                            "value": 1584,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(36,112,122)"
                                }
                            // }
                        },
                        {
                            "name": "\u8001\u5a46",
                            "value": 1415,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(50,155,22)"
                                // }
                            }
                        },
                        {
                            "name": "\u53ef\u4ee5",
                            "value": 1403,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(7,98,142)"
                                // }
                            }
                        },
                        {
                            "name": "\u5feb\u4e50",
                            "value": 1393,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(138,82,1)"
                                // }
                            }
                        },
                        {
                            "name": "\u600e\u4e48",
                            "value": 1372,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(50,0,96)"
                                // }
                            }
                        },
                        {
                            "name": "\u8fd9\u4e48",
                            "value": 1295,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(77,30,24)"
                                // }
                            }
                        },
                        {
                            "name": "\u7316\u72c2",
                            "value": 1236,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(99,50,10)"
                                // }
                            }
                        },
                        {
                            "name": "\u597d\u770b",
                            "value": 1227,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(96,22,55)"
                                }
                            // }
                        },
                        {
                            "name": "\u65e0\u9650",
                            "value": 1188,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(22,109,74)"
                                // }
                            }
                        },
                        {
                            "name": "\u611f\u89c9",
                            "value": 1111,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(40,65,135)"
                                // }
                            }
                        },
                        {
                            "name": "\u6210\u529f",
                            "value": 1093,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(114,130,155)"
                                // }
                            }
                        },
                        {
                            "name": "\u8fd8\u662f",
                            "value": 1054,
                            "textStyle": {
                                //"normal": {
                                    "color": "rgb(122,83,111)"
                                // }
                            }
                        },
                        {
                            "name": "\u554a\u554a\u554a",
                            "value": 1003,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(65,19,28)"
                                // }
                            }
                        },
                        {
                            "name": "\u7cfb\u5217",
                            "value": 957,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(47,122,67)"
                                // }
                            }
                        },
                        {
                            "name": "\u77e5\u9053",
                            "value": 936,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(157,54,118)"
                                }
                            // }
                        },
                        {
                            "name": "\u751f\u65e5",
                            "value": 916,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(84,157,1)"
                                // }
                            }
                        },
                        {
                            "name": "\u6211\u4eec",
                            "value": 906,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(133,98,13)"
                                // }
                            }
                        },
                        {
                            "name": "\u545c\u545c",
                            "value": 902,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(1,140,154)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e0d\u8981",
                            "value": 854,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(93,45,7)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e3a\u4ec0\u4e48",
                            "value": 841,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(8,155,15)"
                                // }
                            }
                        },
                        {
                            "name": "\u65f6\u5019",
                            "value": 832,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(2,74,97)"
                                // }
                            }
                        },
                        {
                            "name": "\u8df3\u821e",
                            "value": 818,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(11,53,114)"
                                // }
                            }
                        },
                        {
                            "name": "\u5206\u949f",
                            "value": 785,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(53,105,99)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e00\u6837",
                            "value": 781,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(81,61,130)"
                            //    }
                            }
                        },
                        {
                            "name": "\u751f\u65e5\u5feb\u4e50",
                            "value": 777,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(13,105,114)"
                                // }
                            }
                        },
                        {
                            "name": "\u5144\u5f1f",
                            "value": 777,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(65,139,106)"
                                // }
                            }
                        },
                        {
                            "name": "\u5df2\u7ecf",
                            "value": 770,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(106,132,12)"
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
        chart_4c980fcb25764686aff8de19162e4261.setOption(option_4c980fcb25764686aff8de19162e4261);
    }
}
</script>

<style scoped>

</style>
