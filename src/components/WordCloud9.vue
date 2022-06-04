<template>
    <div id="wordCloud9" class="chart-container"
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
    name: "WordCloud9",
    mounted() {
        var dom=document.getElementById('wordCloud9')
        var chart_579e445cb6524196bf6655c12d013919 = echarts.init(dom);
        var option_579e445cb6524196bf6655c12d013919 = {
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
                            "name": "\u5c31\u662f",
                            "value": 6750,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(153,78,20)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e09\u591a",
                            "value": 6638,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(103,1,41)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e0d\u662f",
                            "value": 6282,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(14,105,27)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e00\u4e2a",
                            "value": 5960,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(62,91,122)"
                                // }
                            }
                        },
                        {
                            "name": "\u771f\u7684",
                            "value": 5349,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(31,18,60)"
                                }
                            // }
                        },
                        {
                            "name": "\u6ca1\u6709",
                            "value": 4683,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(88,27,122)"
                                // }
                            }
                        },
                        {
                            "name": "\u6210\u624d",
                            "value": 4130,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(75,141,120)"
                                }
                            // }
                        },
                        {
                            "name": "\u6728\u9c7c",
                            "value": 4086,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(125,89,36)"
                                // }
                            }
                        },
                        {
                            "name": "\u65f6\u5019",
                            "value": 3824,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(131,146,100)"
                                // }
                            }
                        },
                        {
                            "name": "\u554a\u554a\u554a",
                            "value": 3484,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(149,154,71)"
                                // }
                            }
                        },
                        {
                            "name": "\u6797\u51b2",
                            "value": 3132,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(135,68,132)"
                                // }
                            }
                        },
                        {
                            "name": "\u73b0\u5728",
                            "value": 2989,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(0,80,7)"
                                }
                            // }
                        },
                        {
                            "name": "\u77e5\u9053",
                            "value": 2941,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(74,131,73)"
                                }
                            // }
                        },
                        {
                            "name": "\u600e\u4e48",
                            "value": 2926,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(51,62,21)"
                                // }
                            }
                        },
                        {
                            "name": "\u559c\u6b22",
                            "value": 2881,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(1,16,49)"
                                // }
                            }
                        },
                        {
                            "name": "\u8fd9\u4e48",
                            "value": 2868,
                            "textStyle": {
                                //"normal": {
                                    "color": "rgb(6,145,103)"
                                // }
                            }
                        },
                        {
                            "name": "\u6c34\u6d52",
                            "value": 2774,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(56,35,37)"
                                }
                            // }
                        },
                        {
                            "name": "\u53ef\u4ee5",
                            "value": 2733,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(23,78,23)"
                                // }
                            }
                        },
                        {
                            "name": "\u8fd8\u662f",
                            "value": 2727,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(148,96,102)"
                                // }
                            }
                        },
                        {
                            "name": "\u73ed\u957f",
                            "value": 2505,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(102,101,73)"
                                // }
                            }
                        },
                        {
                            "name": "\u56e0\u4e3a",
                            "value": 2334,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(7,65,89)"
                                // }
                            }
                        },
                        {
                            "name": "\u8fd9\u91cc",
                            "value": 2324,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(86,137,30)"
                                }
                            // }
                        },
                        {
                            "name": "\u89c9\u5f97",
                            "value": 2278,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(42,102,153)"
                                // }
                            }
                        },
                        {
                            "name": "\u56e2\u957f",
                            "value": 2252,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(131,9,117)"
                                // }
                            }
                        },
                        {
                            "name": "\u6b66\u677e",
                            "value": 2218,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(44,102,99)"
                                // }
                            }
                        },
                        {
                            "name": "\u6211\u4eec",
                            "value": 2199,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(20,86,103)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e2a\u4eba",
                            "value": 2193,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(28,46,25)"
                                }
                            // }
                        },
                        {
                            "name": "\u8fd9\u6837",
                            "value": 2193,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(64,32,82)"
                                // }
                            }
                        },
                        {
                            "name": "\u545c\u545c",
                            "value": 2090,
                            "textStyle": {
                                //"normal": {
                                    "color": "rgb(123,124,78)"
                                // }
                            }
                        },
                        {
                            "name": "\u5df2\u7ecf",
                            "value": 2010,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(70,20,100)"
                                // }
                            }
                        },
                        {
                            "name": "\u4ed6\u4eec",
                            "value": 1896,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(54,140,10)"
                                }
                            // }
                        },
                        {
                            "name": "\u66f4\u65b0",
                            "value": 1894,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(45,72,26)"
                                // }
                            }
                        },
                        {
                            "name": "\u5176\u5b9e",
                            "value": 1830,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(58,43,142)"
                                }
                            // }
                        },
                        {
                            "name": "\u4e00\u6837",
                            "value": 1821,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(159,71,14)"
                                // }
                            }
                        },
                        {
                            "name": "\u4f46\u662f",
                            "value": 1807,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(118,73,10)"
                                }
                            // }
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
        chart_579e445cb6524196bf6655c12d013919.setOption(option_579e445cb6524196bf6655c12d013919);
    }
}
</script>

<style scoped>

</style>
