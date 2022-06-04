<template>
    <div id="wordCloud6" class="chart-container"
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
    name: "WordCloud6",
    mounted() {
        var dom=document.getElementById('wordCloud6')
        var chart_2e94d67803ce4714be985b93bc20ce03 = echarts.init(dom);
        var option_2e94d67803ce4714be985b93bc20ce03 = {
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
                            "name": "\u624b\u673a",
                            "value": 5020,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(158,140,7)"
                                // }
                            }
                        },
                        {
                            "name": "\u6ca1\u6709",
                            "value": 4420,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(98,157,105)"
                                // }
                            }
                        },
                        {
                            "name": "\u53ef\u4ee5",
                            "value": 4325,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(56,78,83)"
                                // }
                            }
                        },
                        {
                            "name": "\u82f9\u679c",
                            "value": 4325,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(159,109,14)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e0d\u662f",
                            "value": 4285,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(33,102,104)"
                                // }
                            }
                        },
                        {
                            "name": "\u5c31\u662f",
                            "value": 3977,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(14,128,99)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e00\u4e2a",
                            "value": 3609,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(59,43,61)"
                                // }
                            }
                        },
                        {
                            "name": "\u5c0f\u7c73",
                            "value": 3547,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(152,119,20)"
                                // }
                            }
                        },
                        {
                            "name": "\u771f\u7684",
                            "value": 3283,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(78,114,84)"
                                // }
                            }
                        },
                        {
                            "name": "\u8fd8\u662f",
                            "value": 3219,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(153,49,87)"
                                }
                            // }
                        },
                        {
                            "name": "\u89c6\u9891",
                            "value": 2804,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(58,24,141)"
                                // }
                            }
                        },
                        {
                            "name": "\u600e\u4e48",
                            "value": 2696,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(49,56,45)"
                                // }
                            }
                        },
                        {
                            "name": "\u611f\u89c9",
                            "value": 2564,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(130,127,48)"
                                }
                            // }
                        },
                        {
                            "name": "\u8fd9\u4e48",
                            "value": 2204,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(94,20,53)"
                                }
                            // }
                        },
                        {
                            "name": "\u6e38\u620f",
                            "value": 2121,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(87,1,149)"
                                // }
                            }
                        },
                        {
                            "name": "\u73b0\u5728",
                            "value": 2060,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(156,23,35)"
                                // }
                            }
                        },
                        {
                            "name": "\u534e\u4e3a",
                            "value": 2047,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(7,52,152)"
                                }
                            // }
                        },
                        {
                            "name": "\u77e5\u9053",
                            "value": 1793,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(98,76,110)"
                                // }
                            }
                        },
                        {
                            "name": "\u65f6\u5019",
                            "value": 1762,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(58,52,157)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e00\u6837",
                            "value": 1743,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(61,74,63)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e09\u661f",
                            "value": 1740,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(126,73,118)"
                                // }
                            }
                        },
                        {
                            "name": "\u5c4f\u5e55",
                            "value": 1720,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(29,153,133)"
                                // }
                            }
                        },
                        {
                            "name": "\u5367\u69fd",
                            "value": 1703,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(87,96,76)"
                                // }
                            }
                        },
                        {
                            "name": "\u5df2\u7ecf",
                            "value": 1660,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(7,159,114)"
                                // }
                            }
                        },
                        {
                            "name": "\u559c\u6b22",
                            "value": 1616,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(52,70,51)"
                                // }
                            }
                        },
                        {
                            "name": "\u89c9\u5f97",
                            "value": 1596,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(96,147,131)"
                                // }
                            }
                        },
                        {
                            "name": "\u597d\u770b",
                            "value": 1579,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(115,151,14)"
                                // }
                            }
                        },
                        {
                            "name": "\u4f46\u662f",
                            "value": 1498,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(9,137,90)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e0d\u9519",
                            "value": 1491,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(20,139,46)"
                                // }
                            }
                        },
                        {
                            "name": "\u51fa\u6765",
                            "value": 1465,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(33,31,19)"
                                }
                            // }
                        },
                        {
                            "name": "\u4ef7\u683c",
                            "value": 1443,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(159,148,76)"
                                }
                            // }
                        },
                        {
                            "name": "\u4e00\u4e0b",
                            "value": 1419,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(31,59,47)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e3a\u4ec0\u4e48",
                            "value": 1415,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(72,75,138)"
                                // }
                            }
                        },
                        {
                            "name": "\u6709\u70b9",
                            "value": 1396,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(30,8,4)"
                                }
                            // }
                        },
                        {
                            "name": "\u76f4\u63a5",
                            "value": 1389,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(74,47,72)"
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
        chart_2e94d67803ce4714be985b93bc20ce03.setOption(option_2e94d67803ce4714be985b93bc20ce03);
    }
}
</script>

<style scoped>

</style>
