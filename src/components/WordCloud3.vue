<template>
    <div id="wordCloud3" class="chart-container"
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
    name: "WordCloud3",
    mounted() {
        var dom=document.getElementById('wordCloud3')
        var chart_257c2a568edc4bb9be09f58f0d199530 = echarts.init(dom);
        var option_257c2a568edc4bb9be09f58f0d199530 = {
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
                            "name": "\u51b0\u51b0",
                            "value": 5009,
                            "textStyle": {

                                    "color": "rgb(75,112,69)"

                            }
                        },
                        {
                            "name": "\u4e00\u4e2a",
                            "value": 2059,
                            "textStyle": {

                                    "color": "rgb(82,89,83)"

                            }
                        },
                        {
                            "name": "\u53ef\u4ee5",
                            "value": 1818,
                            "textStyle": {

                                    "color": "rgb(0,4,103)"

                            }
                        },
                        {
                            "name": "\u89c6\u9891",
                            "value": 1585,
                            "textStyle": {

                                    "color": "rgb(143,140,41)"

                            }
                        },
                        {
                            "name": "\u7cfb\u5217",
                            "value": 1509,
                            "textStyle": {

                                    "color": "rgb(51,157,119)"

                            }
                        },
                        {
                            "name": "\u5c31\u662f",
                            "value": 1340,
                            "textStyle": {

                                    "color": "rgb(24,90,143)"

                            }
                        },
                        {
                            "name": "\u4e0d\u662f",
                            "value": 1240,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(73,120,129)"
                                // }
                            }
                        },
                        {
                            "name": "\u8fd8\u662f",
                            "value": 1214,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(3,29,36)"
                                // }
                            }
                        },
                        {
                            "name": "\u6ca1\u6709",
                            "value": 1068,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(20,110,68)"
                                // }
                            }
                        },
                        {
                            "name": "\u600e\u4e48",
                            "value": 977,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(27,95,30)"
                                // }
                            }
                        },
                        {
                            "name": "\u559c\u6b22",
                            "value": 913,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(91,109,96)"
                                // }
                            }
                        },
                        {
                            "name": "\u771f\u7684",
                            "value": 913,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(100,104,49)"
                                // }
                            }
                        },
                        {
                            "name": "\u6211\u4eec",
                            "value": 836,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(19,157,23)"
                                // }
                            }
                        },
                        {
                            "name": "\u5211\u90e8",
                            "value": 832,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(160,142,87)"
                                // }
                            }
                        },
                        {
                            "name": "\u65f6\u5019",
                            "value": 814,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(36,87,39)"
                                // }
                            }
                        },
                        {
                            "name": "\u8fd9\u4e48",
                            "value": 787,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(51,62,59)"
                                // }
                            }
                        },
                        {
                            "name": "\u5feb\u4e50",
                            "value": 777,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(46,86,113)"
                                }
                            // }
                        },
                        {
                            "name": "\u5bb6\u4f19",
                            "value": 758,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(13,42,69)"
                                // }
                            }
                        },
                        {
                            "name": "\u624b\u5de5",
                            "value": 743,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(1,135,74)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e00\u4e0b",
                            "value": 733,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(82,104,157)"
                                // }
                            }
                        },
                        {
                            "name": "\u597d\u5bb6\u4f19",
                            "value": 727,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(96,89,118)"
                                // }
                            }
                        },
                        {
                            "name": "\u6709\u7528",
                            "value": 726,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(137,147,110)"
                                // }
                            }
                        },
                        {
                            "name": "\u554a\u554a\u554a",
                            "value": 722,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(83,117,59)"
                                // }
                            }
                        },
                        {
                            "name": "\u5c1a\u4e66",
                            "value": 702,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(104,4,3)"
                                // }
                            }
                        },
                        {
                            "name": "\u5211\u5177",
                            "value": 683,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(154,48,64)"
                                // }
                            }
                        },
                        {
                            "name": "\u611f\u89c9",
                            "value": 664,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(52,146,26)"
                                // }
                            }
                        },
                        {
                            "name": "\u90a3\u4e48",
                            "value": 646,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(138,65,154)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e1c\u897f",
                            "value": 634,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(4,99,110)"
                                // }
                            }
                        },
                        {
                            "name": "\u77e5\u9053",
                            "value": 626,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(153,26,72)"
                                // }
                            }
                        },
                        {
                            "name": "\u76f4\u63a5",
                            "value": 620,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(48,74,131)"
                                // }
                            }
                        },
                        {
                            "name": "\u89c9\u5f97",
                            "value": 609,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(19,78,132)"
                                // }
                            }
                        },
                        {
                            "name": "\u5f00\u59cb",
                            "value": 593,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(125,137,74)"
                                // }
                            }
                        },
                        {
                            "name": "\u5df2\u7ecf",
                            "value": 584,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(136,59,30)"
                                // }
                            }
                        },
                        {
                            "name": "\u8fd9\u6837",
                            "value": 575,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(140,159,118)"
                                // }
                            }
                        },
                        {
                            "name": "\u5927\u5bb6",
                            "value": 573,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(101,105,38)"
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
        chart_257c2a568edc4bb9be09f58f0d199530.setOption(option_257c2a568edc4bb9be09f58f0d199530);
    }
}
</script>

<style scoped>

</style>
