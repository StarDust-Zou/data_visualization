<template>
    <div id="wordCloud5" class="chart-container"
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
    name: "WordCloud5",
    mounted() {
        var dom=document.getElementById('wordCloud5')
        var chart_b28274ff7aea4a5f9a49e5e36ed4dbd1 = echarts.init(dom);
        var option_b28274ff7aea4a5f9a49e5e36ed4dbd1 = {
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
                            "name": "\u771f\u7684",
                            "value": 3470,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(11,145,118)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e00\u4e2a",
                            "value": 2528,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(72,157,82)"
                                // }
                            }
                        },
                        {
                            "name": "\u5c31\u662f",
                            "value": 2486,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(17,69,154)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e0d\u662f",
                            "value": 2326,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(3,53,88)"
                                // }
                            }
                        },
                        {
                            "name": "\u6ca1\u6709",
                            "value": 2007,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(117,93,28)"
                                // }
                            }
                        },
                        {
                            "name": "\u52a8\u753b",
                            "value": 1965,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(57,153,133)"
                                // }
                            }
                        },
                        {
                            "name": "\u559c\u6b22",
                            "value": 1600,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(60,100,80)"
                                // }
                            }
                        },
                        {
                            "name": "\u597d\u770b",
                            "value": 1543,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(143,66,90)"
                                // }
                            }
                        },
                        {
                            "name": "\u89c6\u9891",
                            "value": 1522,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(121,53,135)"
                                // }
                            }
                        },
                        {
                            "name": "\u5df2\u7ecf",
                            "value": 1496,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(65,31,37)"
                                // }
                            }
                        },
                        {
                            "name": "\u53ef\u4ee5",
                            "value": 1471,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(26,78,5)"
                                // }
                            }
                        },
                        {
                            "name": "\u554a\u554a\u554a",
                            "value": 1457,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(130,148,153)"
                                // }
                            }
                        },
                        {
                            "name": "\u73b0\u5728",
                            "value": 1428,
                            "textStyle": {
                                // "normal": {
                                "color": "rgb(71,120,65)"
                                // }
                            }
                        },
                        {
                            "name": "\u8fd8\u662f",
                            "value": 1399,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(7,128,43)"
                                // }
                            }
                        },
                        {
                            "name": "\u4e16\u754c",
                            "value": 1386,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(84,35,76)"
                                // }
                            }
                        },
                        {
                            "name": "\u611f\u89c9",
                            "value": 1314,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(36,101,101)"
                                // }
                            }
                        },
                        {
                            "name": "\u6e38\u620f",
                            "value": 1287,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(106,13,57)"
                                // }
                            }
                        },
                        {
                            "name": "\u600e\u4e48",
                            "value": 1224,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(119,2,74)"
                                // }
                            }
                        },
                        {
                            "name": "\u5267\u60c5",
                            "value": 1216,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(109,131,27)"
                                // }
                            }
                        },
                        {
                            "name": "\u65f6\u5019",
                            "value": 1214,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(26,108,153)"
                                // }
                            }
                        },
                        {
                            "name": "\u77e5\u9053",
                            "value": 1200,
                            "textStyle": {
                                // "normal": {
                                "color": "rgb(87,79,56)"
                                //        }
                            }
                        },
                        {
                            "name": "\u4f46\u662f",
                            "value": 1139,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(31,111,31)"
                                // }
                            }
                        },
                        {
                            "name": "\u7b2c\u4e00",
                            "value": 1089,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(75,35,145)"
                                // }
                            }
                        },
                        {
                            "name": "\u8fd9\u4e48",
                            "value": 1086,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(37,1,105)"
                                // }
                            }
                        },
                        {
                            "name": "\u89c9\u5f97",
                            "value": 1040,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(18,119,45)"
                                // }
                            }
                        },
                        {
                            "name": "\u56e0\u4e3a",
                            "value": 1019,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(25,103,19)"
                                // }
                            }
                        },
                        {
                            "name": "\u770b\u5230",
                            "value": 1018,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(127,120,93)"
                                // }
                            }
                        },
                        {
                            "name": "\u6700\u540e",
                            "value": 987,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(67,38,143)"
                                // }
                            }
                        },
                        {
                            "name": "\u6211\u4eec",
                            "value": 984,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(61,160,48)"
                                // }
                            }
                        },
                        {
                            "name": "\u545c\u545c",
                            "value": 979,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(98,60,13)"
                                // }
                            }
                        },
                        {
                            "name": "\u8d77\u7acb",
                            "value": 971,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(110,134,92)"
                          //      }
                            }
                        },
                        {
                            "name": "\u5168\u4f53",
                            "value": 959,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(51,8,151)"
                                // }
                            }
                        },
                        {
                            "name": "\u8fd8\u6709",
                            "value": 887,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(0,21,7)"
                                // }
                            }
                        },
                        {
                            "name": "\u4f5c\u54c1",
                            "value": 878,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(155,47,97)"
                                // }
                            }
                        },
                        {
                            "name": "\u5f00\u59cb",
                            "value": 859,
                            "textStyle": {
                                // "normal": {
                                    "color": "rgb(108,48,125)"
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
        chart_b28274ff7aea4a5f9a49e5e36ed4dbd1.setOption(option_b28274ff7aea4a5f9a49e5e36ed4dbd1);
    }
}
</script>

<style scoped>

</style>
