<template>
    <div id="wordCloud4" class="chart-container"
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
    name: "WordCloud4",
    mounted() {
        var dom=document.getElementById('wordCloud4')
        var chart_bdf8178a67254f89b9500e64800445e7 = echarts.init(dom);
        var option_bdf8178a67254f89b9500e64800445e7 = {
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
                            "name": "\u5927\u5e86",
                            "value": 6124,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(105,50,133)"
                                // }
                            }
                        },
                        {
                            "name": "\u732b\u773c",
                            "value": 5430,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(112,130,146)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e00\u4e2a",
                            "value": 3412,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(125,75,36)"
                                // }
                            }
                        },
                        {
                            "name": "\u5927\u59e8",
                            "value": 3372,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(106,35,98)"
                                // }
                            }
                        },
                        {
                            "name": "\u89c6\u9891",
                            "value": 3365,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(33,63,159)"
                                // }
                            }
                        },
                        {
                            "name": "\u7ef5\u7f8a",
                            "value": 3040,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(95,112,33)"
                                // }
                            }
                        },
                        {
                            "name": "\u6b7b\u56e0",
                            "value": 2820,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(52,89,20)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e0d\u662f",
                            "value": 1900,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(60,71,63)"
                                // }
                            }
                        },
                        {
                            "name": "\u670b\u53cb",
                            "value": 1887,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(154,159,150)"
                                // }
                            }
                        },
                        {
                            "name": "\u6211\u4eec",
                            "value": 1885,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(84,92,124)"
                                // }
                            }
                        },
                        {
                            "name": "\u6ca1\u6709",
                            "value": 1822,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(159,35,15)"
                                // }
                            }
                        },
                        {
                            "name": "\u4eca\u5929",
                            "value": 1805,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(141,139,81)"
                                // }
                            }
                        },
                        {
                            "name": "\u4efb\u52a1",
                            "value": 1670,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(39,28,38)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e0d\u65ad",
                            "value": 1629,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(68,5,36)"
                                // }
                            }
                        },
                        {
                            "name": "\u53ef\u4ee5",
                            "value": 1627,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(19,33,131)"
                                // }
                            }
                        },
                        {
                            "name": "\u600e\u4e48",
                            "value": 1605,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(76,152,147)"
                                // }
                            }
                        },
                        {
                            "name": "\u5c31\u662f",
                            "value": 1514,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(78,83,143)"
                                // }
                            }
                        },
                        {
                            "name": "\u7cfb\u5217",
                            "value": 1510,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(45,84,54)"
                                // }
                            }
                        },
                        {
                            "name": "\u8d76\u6d77",
                            "value": 1474,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(82,133,23)"
                                // }
                            }
                        },
                        {
                            "name": "\u559c\u6b22",
                            "value": 1455,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(155,45,91)"
                                // }
                            }
                        },
                        {
                            "name": "\u8fd9\u4e48",
                            "value": 1446,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(72,50,17)"
                                // }
                            }
                        },
                        {
                            "name": "\u771f\u7684",
                            "value": 1422,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(104,92,25)"
                                // }
                            }
                        },
                        {
                            "name": "\u6bcf\u65e5",
                            "value": 1373,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(16,41,83)"
                                // }
                            }
                        },
                        {
                            "name": "\u5927\u5bb6",
                            "value": 1339,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(6,76,78)"
                                // }
                            }
                        },
                        {
                            "name": "\u4f5c\u4e1a",
                            "value": 1284,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(101,50,113)"
                                // }
                            }
                        },
                        {
                            "name": "\u5feb\u4e50",
                            "value": 1223,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(127,103,14)"
                                // }
                            }
                        },
                        {
                            "name": "\u77e5\u9053",
                            "value": 1209,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(83,102,97)"
                                // }
                            }
                        },
                        {
                            "name": "\u65f6\u5019",
                            "value": 1136,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(36,21,33)"
                                // }
                            }
                        },
                        {
                            "name": "\u8fd9\u91cc",
                            "value": 1131,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(85,129,122)"
                                // }
                            }
                        },
                        {
                            "name": "\u554a\u554a\u554a",
                            "value": 1104,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(42,72,118)"
                                // }
                            }
                        },
                        {
                            "name": "\u51fa\u6765",
                            "value": 1066,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(82,126,146)"
                                // }
                            }
                        },
                        {
                            "name": "\u5199\u4f5c",
                            "value": 1049,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(37,151,42)"
                                // }
                            }
                        },
                        {
                            "name": "\u5f00\u59cb",
                            "value": 1039,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(74,50,60)"
                                // }
                            }
                        },
                        {
                            "name": "\u73b0\u5728",
                            "value": 990,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(101,7,88)"
                                // }
                            }
                        },
                        {
                            "name": "\u5df2\u7ecf",
                            "value": 988,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(65,33,40)"
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
        chart_bdf8178a67254f89b9500e64800445e7.setOption(option_bdf8178a67254f89b9500e64800445e7);
    }
}
</script>

<style scoped>

</style>
