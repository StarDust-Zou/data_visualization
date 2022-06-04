<template>
    <div id="wordCloud8" class="chart-container"
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
    name: "WordCloud8",
    mounted() {
        var dom=document.getElementById('wordCloud8')
        var chart_b6ebb6399f53430a8dfba7b3dc0b644e = echarts.init(dom);
        var option_b6ebb6399f53430a8dfba7b3dc0b644e = {
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
                            "name": "\u8001\u5e08",
                            "value": 12571,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(117,10,4)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e00\u4e2a",
                            "value": 5253,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(48,158,35)"
                                // }
                            }
                        },
                        {
                            "name": "\u5c31\u662f",
                            "value": 4763,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(137,48,74)"
                                // }
                            }
                        },
                        {
                            "name": "\u53ef\u4ee5",
                            "value": 4369,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(55,87,138)"
                                // }
                            }
                        },
                        {
                            "name": "\u6ca1\u6709",
                            "value": 4287,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(46,27,117)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e0d\u662f",
                            "value": 4225,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(78,89,106)"
                                // }
                            }
                        },
                        {
                            "name": "\u600e\u4e48",
                            "value": 3515,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(78,122,33)"
                                // }
                            }
                        },
                        {
                            "name": "\u8c22\u8c22",
                            "value": 3503,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(33,76,59)"
                                // }
                            }
                        },
                        {
                            "name": "\u65f6\u5019",
                            "value": 3136,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(141,5,117)"
                                // }
                            }
                        },
                        {
                            "name": "\u771f\u7684",
                            "value": 2821,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(41,18,126)"
                                // }
                            }
                        },
                        {
                            "name": "\u73b0\u5728",
                            "value": 2729,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(52,43,110)"
                                // }
                            }
                        },
                        {
                            "name": "\u89c6\u9891",
                            "value": 2650,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(146,34,109)"
                                // }
                            }
                        },
                        {
                            "name": "\u77e5\u9053",
                            "value": 2380,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(11,88,108)"
                                // }
                            }
                        },
                        {
                            "name": "\u4f46\u662f",
                            "value": 2322,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(57,147,48)"
                                // }
                            }
                        },
                        {
                            "name": "\u8fd8\u662f",
                            "value": 2311,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(48,2,62)"
                                }
                            // }
                        },
                        {
                            "name": "\u6211\u4eec",
                            "value": 2296,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(157,117,21)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e00\u76f4",
                            "value": 2160,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(160,93,87)"
                                // }
                            }
                        },
                        {
                            "name": "\u56e0\u4e3a",
                            "value": 2143,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(50,42,82)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e00\u4e0b",
                            "value": 2049,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(76,20,107)"
                                // }
                            }
                        },
                        {
                            "name": "\u611f\u89c9",
                            "value": 2041,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(9,140,60)"
                                // }
                            }
                        },
                        {
                            "name": "\u7136\u540e",
                            "value": 1968,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(145,27,126)"
                                // }
                            }
                        },
                        {
                            "name": "\u5982\u679c",
                            "value": 1937,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(38,148,49)"
                                // }
                            }
                        },
                        {
                            "name": "\u95ee\u9898",
                            "value": 1805,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(85,23,92)"
                                // }
                            }
                        },
                        {
                            "name": "\u6240\u4ee5",
                            "value": 1758,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(92,42,28)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e0d\u80fd",
                            "value": 1690,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(156,87,84)"
                                }
                            // }
                        },
                        {
                            "name": "\u5df2\u7ecf",
                            "value": 1685,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(22,126,15)"
                                // }
                            }
                        },
                        {
                            "name": "\u89c9\u5f97",
                            "value": 1684,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(130,18,41)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e2a\u4eba",
                            "value": 1571,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(159,155,130)"
                                // }
                            }
                        },
                        {
                            "name": "\u53ef\u80fd",
                            "value": 1553,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(122,131,63)"
                                // }
                            }
                        },
                        {
                            "name": "\u5927\u54ed",
                            "value": 1510,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(115,41,113)"
                                // }
                            }
                        },
                        {
                            "name": "\u670b\u53cb",
                            "value": 1487,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(112,143,22)"
                                // }
                            }
                        },
                        {
                            "name": "\u5e94\u8be5",
                            "value": 1421,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(113,2,84)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e0d\u4f1a",
                            "value": 1419,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(157,143,90)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e0d\u8981",
                            "value": 1417,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(62,38,49)"
                                // }
                            }
                        },
                        {
                            "name": "\u5bb6\u4f19",
                            "value": 1400,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(22,88,119)"
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
        chart_b6ebb6399f53430a8dfba7b3dc0b644e.setOption(option_b6ebb6399f53430a8dfba7b3dc0b644e);
    }
}
</script>

<style scoped>

</style>
