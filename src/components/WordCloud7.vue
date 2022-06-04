<template>
    <div id="wordCloud7" class="chart-container"
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
    name: "WordCloud7",
    mounted() {
        var dom=document.getElementById('wordCloud7')
        var chart_9fc13ad2cc854b5cb9bf64c2efe98a3d = echarts.init(dom);
        var option_9fc13ad2cc854b5cb9bf64c2efe98a3d = {
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
                            "name": "\u6e38\u620f",
                            "value": 9573,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(139,7,106)"
                                // }
                            }
                        },
                        {
                            "name": "\u5c31\u662f",
                            "value": 5596,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(33,160,130)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e00\u4e2a",
                            "value": 5370,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(84,33,14)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e0d\u662f",
                            "value": 4834,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(30,97,100)"
                                }
                            // }
                        },
                        {
                            "name": "\u756a\u8304",
                            "value": 4660,
                            "textStyle": {
                           //     "normal": {
                                    "color": "rgb(89,62,102)"
                                // }
                            }
                        },
                        {
                            "name": "\u771f\u7684",
                            "value": 4366,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(131,144,3)"
                                // }
                            }
                        },
                        {
                            "name": "\u6ca1\u6709",
                            "value": 3940,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(115,7,92)"
                                // }
                            }
                        },
                        {
                            "name": "\u73b0\u5728",
                            "value": 3907,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(12,131,105)"
                                // }
                            }
                        },
                        {
                            "name": "\u89c6\u9891",
                            "value": 3604,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(154,3,122)"
                                // }
                            }
                        },
                        {
                            "name": "\u53ef\u4ee5",
                            "value": 3377,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(59,22,120)"
                                }
                            // }
                        },
                        {
                            "name": "\u65f6\u5019",
                            "value": 3241,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(83,9,94)"
                                // }
                            }
                        },
                        {
                            "name": "\u73a9\u5bb6",
                            "value": 3128,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(140,7,100)"
                                // }
                            }
                        },
                        {
                            "name": "\u8fd8\u662f",
                            "value": 2739,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(131,81,93)"
                                // }
                            }
                        },
                        {
                            "name": "\u600e\u4e48",
                            "value": 2409,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(35,43,61)"
                                // }
                            }
                        },
                        {
                            "name": "\u6536\u83b7",
                            "value": 2400,
                            "textStyle": {
                            //    "normal": {
                                    "color": "rgb(74,33,60)"
                                // }
                            }
                        },
                        {
                            "name": "\u77e5\u9053",
                            "value": 2187,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(87,65,76)"
                                // }
                            }
                        },
                        {
                            "name": "\u6211\u4eec",
                            "value": 1961,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(94,94,21)"
                                }
                            // }
                        },
                        {
                            "name": "\u4f46\u662f",
                            "value": 1935,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(4,98,72)"
                                // }
                            }
                        },
                        {
                            "name": "\u559c\u6b22",
                            "value": 1902,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(108,74,89)"
                                // }
                            }
                        },
                        {
                            "name": "\u5df2\u7ecf",
                            "value": 1817,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(25,5,150)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e16\u754c",
                            "value": 1807,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(33,147,22)"
                                }
                            // }
                        },
                        {
                            "name": "\u8fd9\u4e48",
                            "value": 1802,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(37,14,147)"
                                // }
                            }
                        },
                        {
                            "name": "\u597d\u73a9",
                            "value": 1787,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(137,32,42)"
                                }
                            // }
                        },
                        {
                            "name": "\u5f00\u59cb",
                            "value": 1778,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(76,137,77)"
                                // }
                            }
                        },
                        {
                            "name": "\u611f\u89c9",
                            "value": 1724,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(70,117,85)"
                                }
                            // }
                        },
                        {
                            "name": "\u8fd8\u6709",
                            "value": 1722,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(40,57,19)"
                                }
                            // }
                        },
                        {
                            "name": "\u56e0\u4e3a",
                            "value": 1693,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(95,60,144)"
                                // }
                            }
                        },
                        {
                            "name": "\u89c9\u5f97",
                            "value": 1603,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(118,76,128)"
                                }
                            // }
                        },
                        {
                            "name": "\u90a3\u4e2a",
                            "value": 1594,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(143,26,149)"
                                // }
                            }
                        },
                        {
                            "name": "\u817e\u8baf",
                            "value": 1528,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(109,86,40)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e2d\u56fd",
                            "value": 1526,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(26,137,158)"
                                // }
                            }
                        },
                        {
                            "name": "\u7b2c\u4e00",
                            "value": 1520,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(33,116,95)"
                                // }
                            }
                        },
                        {
                            "name": "\u786e\u5b9e",
                            "value": 1519,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(14,97,110)"
                                // }
                            }
                        },
                        {
                            "name": "\u5f53\u65f6",
                            "value": 1508,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(22,17,119)"
                                // }
                            }
                        },
                        {
                            "name": "\u6240\u4ee5",
                            "value": 1458,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(149,43,65)"
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
        chart_9fc13ad2cc854b5cb9bf64c2efe98a3d.setOption(option_9fc13ad2cc854b5cb9bf64c2efe98a3d);
    }
}
</script>

<style scoped>

</style>
