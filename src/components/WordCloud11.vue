<template>
    <div id="wordCloud11" class="chart-container"
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
    name: "WordCloud11",
    mounted() {
        var dom=document.getElementById('wordCloud11')
        var chart_b43a0e45848c4fd58a9ed7016785b18b = echarts.init(dom);
        var option_b43a0e45848c4fd58a9ed7016785b18b = {
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
                            "name": "\u559c\u6b22",
                            "value": 898,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(39,126,118)"
                                // }
                            }
                        },
                        {
                            "name": "\u89c6\u9891",
                            "value": 647,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(119,6,136)"
                                // }
                            }
                        },
                        {
                            "name": "\u5144\u5f1f",
                            "value": 607,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(119,127,99)"
                                // }
                            }
                        },
                        {
                            "name": "\u539a\u793c",
                            "value": 595,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(113,30,56)"
                                // }
                            }
                        },
                        {
                            "name": "\u8fd9\u4e48",
                            "value": 586,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(143,23,65)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e0d\u662f",
                            "value": 573,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(84,35,88)"
                                // }
                            }
                        },
                        {
                            "name": "\u592a\u4f1a",
                            "value": 564,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(54,109,61)"
                                // }
                            }
                        },
                        {
                            "name": "\u597d\u770b",
                            "value": 563,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(33,137,1)"
                                // }
                            }
                        },
                        {
                            "name": "\u600e\u4e48",
                            "value": 559,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(132,132,106)"
                                // }
                            }
                        },
                        {
                            "name": "\u6ca1\u6709",
                            "value": 534,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(85,55,119)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e00\u4e2a",
                            "value": 519,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(31,120,9)"
                                // }
                            }
                        },
                        {
                            "name": "\u771f\u7684",
                            "value": 516,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(120,93,143)"
                                // }
                            }
                        },
                        {
                            "name": "\u7535\u89c6",
                            "value": 491,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(52,7,53)"
                                // }
                            }
                        },
                        {
                            "name": "\u88e4\u5b50",
                            "value": 461,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(114,138,39)"
                                // }
                            }
                        },
                        {
                            "name": "\u8863\u670d",
                            "value": 458,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(24,116,56)"
                                // }
                            }
                        },
                        {
                            "name": "\u53ef\u4ee5",
                            "value": 436,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(55,104,3)"
                                // }
                            }
                        },
                        {
                            "name": "\u5c31\u662f",
                            "value": 427,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(32,49,145)"
                                // }
                            }
                        },
                        {
                            "name": "\u8eab\u6750",
                            "value": 396,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(2,155,137)"
                                // }
                            }
                        },
                        {
                            "name": "\u89c2\u770b",
                            "value": 395,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(152,102,55)"
                                // }
                            }
                        },
                        {
                            "name": "\u6211\u4eec",
                            "value": 394,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(33,76,52)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e3a\u4ec0\u4e48",
                            "value": 387,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(13,96,109)"
                                // }
                            }
                        },
                        {
                            "name": "\u8001\u5a46",
                            "value": 379,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(84,95,151)"
                                // }
                            }
                        },
                        {
                            "name": "\u8fd8\u662f",
                            "value": 370,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(52,114,42)"
                                // }
                            }
                        },
                        {
                            "name": "\u5fc3\u5fc3",
                            "value": 350,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(51,21,89)"
                                // }
                            }
                        },
                        {
                            "name": "\u5065\u8eab",
                            "value": 349,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(139,7,54)"
                                // }
                            }
                        },
                        {
                            "name": "\u5f39\u5e55",
                            "value": 349,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(61,119,156)"
                                // }
                            }
                        },
                        {
                            "name": "\u7cfb\u5217",
                            "value": 343,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(34,85,104)"
                                // }
                            }
                        },
                        {
                            "name": "\u6e38\u620f",
                            "value": 335,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(97,38,76)"
                                // }
                            }
                        },
                        {
                            "name": "\u79bb\u8c31",
                            "value": 325,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(74,82,54)"
                                // }
                            }
                        },
                        {
                            "name": "\u77e5\u9053",
                            "value": 321,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(37,93,67)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e00\u4e0b",
                            "value": 312,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(139,72,72)"
                                // }
                            }
                        },
                        {
                            "name": "\u611f\u89c9",
                            "value": 306,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(140,124,131)"
                                // }
                            }
                        },
                        {
                            "name": "\u8138\u7ea2",
                            "value": 288,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(138,57,84)"
                                // }
                            }
                        },
                        {
                            "name": "\u773c\u775b",
                            "value": 287,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(153,66,97)"
                                // }
                            }
                        },
                        {
                            "name": "\u8df3\u821e",
                            "value": 281,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(49,59,47)"
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
        chart_b43a0e45848c4fd58a9ed7016785b18b.setOption(option_b43a0e45848c4fd58a9ed7016785b18b);
    }
}
</script>

<style scoped>

</style>
