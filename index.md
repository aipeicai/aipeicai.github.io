<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Awesome-pyecharts</title>
            <script type="text/javascript" src="https://assets.pyecharts.org/assets/echarts.min.js"></script>

    
</head>
<body>
        <style>
        .tab {
            overflow: hidden;
            border: 1px solid #ccc;
            background-color: #f1f1f1;
        }

        .tab button {
            background-color: inherit;
            float: left;
            border: none;
            outline: none;
            cursor: pointer;
            padding: 12px 16px;
            transition: 0.3s;
        }

        .tab button:hover {
            background-color: #ddd;
        }

        .tab button.active {
            background-color: #ccc;
        }

        .chart-container {
            display: none;
            padding: 6px 12px;
            border-top: none;
        }
    </style>
    <div class="tab">
            <button class="tablinks" onclick="showChart(event, '68d5db670e7d4bd1a1666f9bdeb4daf2')">工时在项目类型上分布</button>
            <button class="tablinks" onclick="showChart(event, '1eaea5fe485c40acac13e4fb07942221')">工时在职位上分布</button>
            <button class="tablinks" onclick="showChart(event, '0e4e014a351c4b2893d1f7a1037a88ff')">各组工时分布</button>
            <button class="tablinks" onclick="showChart(event, '3126d1c14eba457196243d55bcc67af3')">工时在项目分布Top5</button>
    </div>

    <div class="box">
                <div id="68d5db670e7d4bd1a1666f9bdeb4daf2" class="chart-container" style="width:900px; height:500px;"></div>
    <script>
        var chart_68d5db670e7d4bd1a1666f9bdeb4daf2 = echarts.init(
            document.getElementById('68d5db670e7d4bd1a1666f9bdeb4daf2'), 'white', {renderer: 'canvas'});
        var option_68d5db670e7d4bd1a1666f9bdeb4daf2 = {
    "baseOption": {
        "series": [
            {
                "type": "pie",
                "clockwise": true,
                "data": [
                    {
                        "name": "Acquisition",
                        "value": 178
                    },
                    {
                        "name": "daily",
                        "value": 59.5
                    },
                    {
                        "name": "Developing",
                        "value": 1026.5
                    },
                    {
                        "name": "internal order to AQ",
                        "value": 30
                    },
                    {
                        "name": "internal order to AV",
                        "value": 131
                    },
                    {
                        "name": "management",
                        "value": 1515.25
                    },
                    {
                        "name": "other",
                        "value": 54.25
                    },
                    {
                        "name": "project",
                        "value": 42.5
                    },
                    {
                        "name": "Supporting",
                        "value": 3
                    },
                    {
                        "name": "RLS",
                        "value": 17
                    },
                    {
                        "name": "Car Access",
                        "value": 37
                    },
                    {
                        "name": "Adjustment",
                        "value": 3820
                    }
                ],
                "radius": "65%",
                "center": [
                    "50%",
                    "50%"
                ],
                "label": {
                    "show": true,
                    "position": "top",
                    "margin": 8,
                    "formatter": "{b}: {d}%"
                },
                "rippleEffect": {
                    "show": true,
                    "brushType": "stroke",
                    "scale": 2.5,
                    "period": 4
                }
            }
        ],
        "timeline": {
            "axisType": "category",
            "orient": "horizontal",
            "autoPlay": true,
            "controlPosition": "left",
            "loop": true,
            "rewind": false,
            "show": true,
            "inverse": false,
            "playInterval": 3000,
            "bottom": "-5px",
            "data": [
                "6\u6708",
                "7\u6708"
            ]
        }
    },
    "options": [
        {
            "legend": [
                {
                    "data": [
                        "Acquisition",
                        "daily",
                        "Developing",
                        "internal order to AQ",
                        "internal order to AV",
                        "management",
                        "other",
                        "Supporting",
                        "Steering",
                        "RLS",
                        "Car Access",
                        "Adjustment",
                        "HMI"
                    ],
                    "selected": {},
                    "show": true,
                    "left": "1%",
                    "top": "15%",
                    "orient": "vertical",
                    "padding": 5,
                    "itemGap": 10,
                    "itemWidth": 25,
                    "itemHeight": 14
                }
            ],
            "series": [
                {
                    "type": "pie",
                    "clockwise": true,
                    "data": [
                        {
                            "name": "Acquisition",
                            "value": 188.5
                        },
                        {
                            "name": "daily",
                            "value": 59
                        },
                        {
                            "name": "Developing",
                            "value": 804
                        },
                        {
                            "name": "internal order to AQ",
                            "value": 40
                        },
                        {
                            "name": "internal order to AV",
                            "value": 75
                        },
                        {
                            "name": "management",
                            "value": 304.75
                        },
                        {
                            "name": "other",
                            "value": 101
                        },
                        {
                            "name": "Supporting",
                            "value": 27
                        },
                        {
                            "name": "Steering",
                            "value": 6
                        },
                        {
                            "name": "RLS",
                            "value": 38
                        },
                        {
                            "name": "Car Access",
                            "value": 4445.25
                        },
                        {
                            "name": "Adjustment",
                            "value": 1402
                        },
                        {
                            "name": "HMI",
                            "value": 22
                        }
                    ],
                    "radius": "65%",
                    "center": [
                        "50%",
                        "50%"
                    ],
                    "label": {
                        "show": true,
                        "position": "top",
                        "margin": 8,
                        "formatter": "{b}: {d}%"
                    },
                    "rippleEffect": {
                        "show": true,
                        "brushType": "stroke",
                        "scale": 2.5,
                        "period": 4
                    }
                }
            ],
            "title": [
                {
                    "text": "2022-\u5de5\u65f6\u5728\u9879\u76ee\u7c7b\u578b\u4e0a\u5206\u5e03",
                    "top": "5%",
                    "padding": 5,
                    "itemGap": 10
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
                "borderWidth": 0,
                "padding": 5
            },
            "color": [
                "#c23531",
                "#2f4554",
                "#61a0a8",
                "#d48265",
                "#749f83",
                "#ca8622",
                "#bda29a",
                "#6e7074",
                "#546570",
                "#c4ccd3",
                "#f05b72",
                "#ef5b9c",
                "#f47920",
                "#905a3d",
                "#fab27b",
                "#2a5caa",
                "#444693",
                "#726930",
                "#b2d235",
                "#6d8346",
                "#ac6767",
                "#1d953f",
                "#6950a1",
                "#918597"
            ]
        },
        {
            "legend": [
                {
                    "data": [
                        "Acquisition",
                        "daily",
                        "Developing",
                        "internal order to AQ",
                        "internal order to AV",
                        "management",
                        "other",
                        "project",
                        "Supporting",
                        "RLS",
                        "Car Access",
                        "Adjustment"
                    ],
                    "selected": {},
                    "show": true,
                    "left": "1%",
                    "top": "15%",
                    "orient": "vertical",
                    "padding": 5,
                    "itemGap": 10,
                    "itemWidth": 25,
                    "itemHeight": 14
                }
            ],
            "series": [
                {
                    "type": "pie",
                    "clockwise": true,
                    "data": [
                        {
                            "name": "Acquisition",
                            "value": 178
                        },
                        {
                            "name": "daily",
                            "value": 59.5
                        },
                        {
                            "name": "Developing",
                            "value": 1026.5
                        },
                        {
                            "name": "internal order to AQ",
                            "value": 30
                        },
                        {
                            "name": "internal order to AV",
                            "value": 131
                        },
                        {
                            "name": "management",
                            "value": 1515.25
                        },
                        {
                            "name": "other",
                            "value": 54.25
                        },
                        {
                            "name": "project",
                            "value": 42.5
                        },
                        {
                            "name": "Supporting",
                            "value": 3
                        },
                        {
                            "name": "RLS",
                            "value": 17
                        },
                        {
                            "name": "Car Access",
                            "value": 37
                        },
                        {
                            "name": "Adjustment",
                            "value": 3820
                        }
                    ],
                    "radius": "65%",
                    "center": [
                        "50%",
                        "50%"
                    ],
                    "label": {
                        "show": true,
                        "position": "top",
                        "margin": 8,
                        "formatter": "{b}: {d}%"
                    },
                    "rippleEffect": {
                        "show": true,
                        "brushType": "stroke",
                        "scale": 2.5,
                        "period": 4
                    }
                }
            ],
            "title": [
                {
                    "text": "2022-\u5de5\u65f6\u5728\u9879\u76ee\u7c7b\u578b\u4e0a\u5206\u5e03",
                    "top": "5%",
                    "padding": 5,
                    "itemGap": 10
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
                "borderWidth": 0,
                "padding": 5
            },
            "color": [
                "#c23531",
                "#2f4554",
                "#61a0a8",
                "#d48265",
                "#749f83",
                "#ca8622",
                "#bda29a",
                "#6e7074",
                "#546570",
                "#c4ccd3",
                "#f05b72",
                "#ef5b9c",
                "#f47920",
                "#905a3d",
                "#fab27b",
                "#2a5caa",
                "#444693",
                "#726930",
                "#b2d235",
                "#6d8346",
                "#ac6767",
                "#1d953f",
                "#6950a1",
                "#918597"
            ]
        }
    ]
};
        chart_68d5db670e7d4bd1a1666f9bdeb4daf2.setOption(option_68d5db670e7d4bd1a1666f9bdeb4daf2);
    </script>
                <div id="1eaea5fe485c40acac13e4fb07942221" class="chart-container" style="width:900px; height:500px;"></div>
    <script>
        var chart_1eaea5fe485c40acac13e4fb07942221 = echarts.init(
            document.getElementById('1eaea5fe485c40acac13e4fb07942221'), 'white', {renderer: 'canvas'});
        var option_1eaea5fe485c40acac13e4fb07942221 = {
    "baseOption": {
        "series": [
            {
                "type": "pie",
                "clockwise": true,
                "data": [
                    {
                        "name": "MECH",
                        "value": 745
                    },
                    {
                        "name": "ASSISTANT",
                        "value": 170
                    },
                    {
                        "name": "HW",
                        "value": 170
                    },
                    {
                        "name": "SW",
                        "value": 4183
                    },
                    {
                        "name": "SYS",
                        "value": 2024.5
                    },
                    {
                        "name": "TPL",
                        "value": 903
                    }
                ],
                "radius": "65%",
                "center": [
                    "50%",
                    "50%"
                ],
                "label": {
                    "show": true,
                    "position": "top",
                    "margin": 8,
                    "formatter": "{b}: {d}%"
                },
                "rippleEffect": {
                    "show": true,
                    "brushType": "stroke",
                    "scale": 2.5,
                    "period": 4
                }
            }
        ],
        "timeline": {
            "axisType": "category",
            "orient": "horizontal",
            "autoPlay": true,
            "controlPosition": "left",
            "loop": true,
            "rewind": false,
            "show": true,
            "inverse": false,
            "playInterval": 3000,
            "bottom": "-5px",
            "data": [
                "6\u6708",
                "7\u6708"
            ]
        }
    },
    "options": [
        {
            "legend": [
                {
                    "data": [
                        "MECH",
                        "ASSISTANT",
                        "HW",
                        "SW",
                        "SYS",
                        "TPL"
                    ],
                    "selected": {},
                    "show": true,
                    "left": "1%",
                    "top": "15%",
                    "orient": "vertical",
                    "padding": 5,
                    "itemGap": 10,
                    "itemWidth": 25,
                    "itemHeight": 14
                }
            ],
            "series": [
                {
                    "type": "pie",
                    "clockwise": true,
                    "data": [
                        {
                            "name": "MECH",
                            "value": 727
                        },
                        {
                            "name": "ASSISTANT",
                            "value": 178.5
                        },
                        {
                            "name": "HW",
                            "value": 179.5
                        },
                        {
                            "name": "SW",
                            "value": 3786.75
                        },
                        {
                            "name": "SYS",
                            "value": 1659.25
                        },
                        {
                            "name": "TPL",
                            "value": 898
                        }
                    ],
                    "radius": "65%",
                    "center": [
                        "50%",
                        "50%"
                    ],
                    "label": {
                        "show": true,
                        "position": "top",
                        "margin": 8,
                        "formatter": "{b}: {d}%"
                    },
                    "rippleEffect": {
                        "show": true,
                        "brushType": "stroke",
                        "scale": 2.5,
                        "period": 4
                    }
                }
            ],
            "title": [
                {
                    "text": "2022-\u5de5\u65f6\u5728\u804c\u4f4d\u4e0a\u5206\u5e03",
                    "top": "5%",
                    "padding": 5,
                    "itemGap": 10
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
                "borderWidth": 0,
                "padding": 5
            },
            "color": [
                "#c23531",
                "#2f4554",
                "#61a0a8",
                "#d48265",
                "#749f83",
                "#ca8622",
                "#bda29a",
                "#6e7074",
                "#546570",
                "#c4ccd3",
                "#f05b72",
                "#ef5b9c",
                "#f47920",
                "#905a3d",
                "#fab27b",
                "#2a5caa",
                "#444693",
                "#726930",
                "#b2d235",
                "#6d8346",
                "#ac6767",
                "#1d953f",
                "#6950a1",
                "#918597"
            ]
        },
        {
            "legend": [
                {
                    "data": [
                        "MECH",
                        "ASSISTANT",
                        "HW",
                        "SW",
                        "SYS",
                        "TPL"
                    ],
                    "selected": {},
                    "show": true,
                    "left": "1%",
                    "top": "15%",
                    "orient": "vertical",
                    "padding": 5,
                    "itemGap": 10,
                    "itemWidth": 25,
                    "itemHeight": 14
                }
            ],
            "series": [
                {
                    "type": "pie",
                    "clockwise": true,
                    "data": [
                        {
                            "name": "MECH",
                            "value": 745
                        },
                        {
                            "name": "ASSISTANT",
                            "value": 170
                        },
                        {
                            "name": "HW",
                            "value": 170
                        },
                        {
                            "name": "SW",
                            "value": 4183
                        },
                        {
                            "name": "SYS",
                            "value": 2024.5
                        },
                        {
                            "name": "TPL",
                            "value": 903
                        }
                    ],
                    "radius": "65%",
                    "center": [
                        "50%",
                        "50%"
                    ],
                    "label": {
                        "show": true,
                        "position": "top",
                        "margin": 8,
                        "formatter": "{b}: {d}%"
                    },
                    "rippleEffect": {
                        "show": true,
                        "brushType": "stroke",
                        "scale": 2.5,
                        "period": 4
                    }
                }
            ],
            "title": [
                {
                    "text": "2022-\u5de5\u65f6\u5728\u804c\u4f4d\u4e0a\u5206\u5e03",
                    "top": "5%",
                    "padding": 5,
                    "itemGap": 10
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
                "borderWidth": 0,
                "padding": 5
            },
            "color": [
                "#c23531",
                "#2f4554",
                "#61a0a8",
                "#d48265",
                "#749f83",
                "#ca8622",
                "#bda29a",
                "#6e7074",
                "#546570",
                "#c4ccd3",
                "#f05b72",
                "#ef5b9c",
                "#f47920",
                "#905a3d",
                "#fab27b",
                "#2a5caa",
                "#444693",
                "#726930",
                "#b2d235",
                "#6d8346",
                "#ac6767",
                "#1d953f",
                "#6950a1",
                "#918597"
            ]
        }
    ]
};
        chart_1eaea5fe485c40acac13e4fb07942221.setOption(option_1eaea5fe485c40acac13e4fb07942221);
    </script>
                <div id="0e4e014a351c4b2893d1f7a1037a88ff" class="chart-container" style="width:900px; height:500px;"></div>
    <script>
        var chart_0e4e014a351c4b2893d1f7a1037a88ff = echarts.init(
            document.getElementById('0e4e014a351c4b2893d1f7a1037a88ff'), 'white', {renderer: 'canvas'});
        var option_0e4e014a351c4b2893d1f7a1037a88ff = {
    "baseOption": {
        "series": [
            {
                "type": "bar",
                "name": "Other",
                "legendHoverLink": true,
                "data": [
                    0,
                    170,
                    180.5,
                    723.5,
                    10,
                    454,
                    630.5,
                    300,
                    588.5
                ],
                "showBackground": false,
                "stack": "stack1",
                "barMinHeight": 0,
                "barCategoryGap": "20%",
                "barGap": "30%",
                "large": false,
                "largeThreshold": 400,
                "seriesLayoutBy": "column",
                "datasetIndex": 0,
                "clip": true,
                "zlevel": 0,
                "z": 2,
                "label": {
                    "show": false,
                    "position": "top",
                    "margin": 8
                }
            },
            {
                "type": "bar",
                "name": "Electronics",
                "legendHoverLink": true,
                "data": [
                    170,
                    0,
                    552.5,
                    1301,
                    662.5,
                    662,
                    686.5,
                    777.5,
                    326.5
                ],
                "showBackground": false,
                "stack": "stack1",
                "barMinHeight": 0,
                "barCategoryGap": "20%",
                "barGap": "30%",
                "large": false,
                "largeThreshold": 400,
                "seriesLayoutBy": "column",
                "datasetIndex": 0,
                "clip": true,
                "zlevel": 0,
                "z": 2,
                "label": {
                    "show": false,
                    "position": "top",
                    "margin": 8
                }
            },
            {
                "type": "bar",
                "name": "Switch",
                "legendHoverLink": true,
                "data": [
                    0,
                    0,
                    0,
                    0,
                    0,
                    0,
                    0,
                    0,
                    0
                ],
                "showBackground": false,
                "stack": "stack1",
                "barMinHeight": 0,
                "barCategoryGap": "20%",
                "barGap": "30%",
                "large": false,
                "largeThreshold": 400,
                "seriesLayoutBy": "column",
                "datasetIndex": 0,
                "clip": true,
                "zlevel": 0,
                "z": 2,
                "label": {
                    "show": false,
                    "position": "top",
                    "margin": 8
                }
            },
            {
                "type": "bar",
                "name": "Mechantronics",
                "legendHoverLink": true,
                "data": [
                    0,
                    0,
                    0,
                    0,
                    0,
                    0,
                    0,
                    0,
                    0
                ],
                "showBackground": false,
                "stack": "stack1",
                "barMinHeight": 0,
                "barCategoryGap": "20%",
                "barGap": "30%",
                "large": false,
                "largeThreshold": 400,
                "seriesLayoutBy": "column",
                "datasetIndex": 0,
                "clip": true,
                "zlevel": 0,
                "z": 2,
                "label": {
                    "show": false,
                    "position": "top",
                    "margin": 8
                }
            }
        ],
        "timeline": {
            "axisType": "category",
            "orient": "horizontal",
            "autoPlay": true,
            "controlPosition": "left",
            "loop": true,
            "rewind": false,
            "show": true,
            "inverse": false,
            "playInterval": 3000,
            "bottom": "-5px",
            "data": [
                "6\u6708",
                "7\u6708"
            ]
        },
        "xAxis": [
            {
                "show": true,
                "scale": false,
                "nameLocation": "end",
                "nameGap": 15,
                "gridIndex": 0,
                "inverse": false,
                "offset": 0,
                "splitNumber": 5,
                "minInterval": 0,
                "splitLine": {
                    "show": false,
                    "lineStyle": {
                        "show": true,
                        "width": 1,
                        "opacity": 1,
                        "curveness": 0,
                        "type": "solid"
                    }
                },
                "data": [
                    "AEV",
                    "AEV1",
                    "AEV2",
                    "AEV3",
                    "AEV4",
                    "AEV6.1",
                    "AEV6.2",
                    "AEV6.3",
                    "AEV8.1"
                ]
            }
        ],
        "yAxis": [
            {
                "type": "value",
                "show": true,
                "scale": false,
                "nameLocation": "end",
                "nameGap": 15,
                "gridIndex": 0,
                "axisLabel": {
                    "show": true,
                    "position": "top",
                    "margin": 8,
                    "formatter": "{value} h"
                },
                "inverse": false,
                "offset": 0,
                "splitNumber": 5,
                "minInterval": 0,
                "splitLine": {
                    "show": false,
                    "lineStyle": {
                        "show": true,
                        "width": 1,
                        "opacity": 1,
                        "curveness": 0,
                        "type": "solid"
                    }
                }
            }
        ]
    },
    "options": [
        {
            "legend": [
                {
                    "data": [
                        "Other",
                        "Electronics",
                        "Switch",
                        "Mechantronics"
                    ],
                    "selected": {
                        "Other": true,
                        "Electronics": true,
                        "Switch": true,
                        "Mechantronics": true
                    },
                    "show": true,
                    "top": "5%",
                    "padding": 5,
                    "itemGap": 10,
                    "itemWidth": 25,
                    "itemHeight": 14
                }
            ],
            "series": [
                {
                    "type": "bar",
                    "name": "Other",
                    "legendHoverLink": true,
                    "data": [
                        0,
                        178.5,
                        10,
                        458.75,
                        13.5,
                        60.5,
                        310.5,
                        34.5,
                        523
                    ],
                    "showBackground": false,
                    "stack": "stack1",
                    "barMinHeight": 0,
                    "barCategoryGap": "20%",
                    "barGap": "30%",
                    "large": false,
                    "largeThreshold": 400,
                    "seriesLayoutBy": "column",
                    "datasetIndex": 0,
                    "clip": true,
                    "zlevel": 0,
                    "z": 2,
                    "label": {
                        "show": false,
                        "position": "top",
                        "margin": 8
                    }
                },
                {
                    "type": "bar",
                    "name": "Electronics",
                    "legendHoverLink": true,
                    "data": [
                        181.5,
                        0,
                        706.5,
                        1200.5,
                        943.5,
                        719.5,
                        804.5,
                        900.25,
                        383.5
                    ],
                    "showBackground": false,
                    "stack": "stack1",
                    "barMinHeight": 0,
                    "barCategoryGap": "20%",
                    "barGap": "30%",
                    "large": false,
                    "largeThreshold": 400,
                    "seriesLayoutBy": "column",
                    "datasetIndex": 0,
                    "clip": true,
                    "zlevel": 0,
                    "z": 2,
                    "label": {
                        "show": false,
                        "position": "top",
                        "margin": 8
                    }
                },
                {
                    "type": "bar",
                    "name": "Switch",
                    "legendHoverLink": true,
                    "data": [
                        0,
                        0,
                        0,
                        0,
                        0,
                        0,
                        0,
                        0,
                        0
                    ],
                    "showBackground": false,
                    "stack": "stack1",
                    "barMinHeight": 0,
                    "barCategoryGap": "20%",
                    "barGap": "30%",
                    "large": false,
                    "largeThreshold": 400,
                    "seriesLayoutBy": "column",
                    "datasetIndex": 0,
                    "clip": true,
                    "zlevel": 0,
                    "z": 2,
                    "label": {
                        "show": false,
                        "position": "top",
                        "margin": 8
                    }
                },
                {
                    "type": "bar",
                    "name": "Mechantronics",
                    "legendHoverLink": true,
                    "data": [
                        0,
                        0,
                        0,
                        0,
                        0,
                        0,
                        0,
                        0,
                        0
                    ],
                    "showBackground": false,
                    "stack": "stack1",
                    "barMinHeight": 0,
                    "barCategoryGap": "20%",
                    "barGap": "30%",
                    "large": false,
                    "largeThreshold": 400,
                    "seriesLayoutBy": "column",
                    "datasetIndex": 0,
                    "clip": true,
                    "zlevel": 0,
                    "z": 2,
                    "label": {
                        "show": false,
                        "position": "top",
                        "margin": 8
                    }
                }
            ],
            "xAxis": [
                {
                    "show": true,
                    "scale": false,
                    "nameLocation": "end",
                    "nameGap": 15,
                    "gridIndex": 0,
                    "inverse": false,
                    "offset": 0,
                    "splitNumber": 5,
                    "minInterval": 0,
                    "splitLine": {
                        "show": false,
                        "lineStyle": {
                            "show": true,
                            "width": 1,
                            "opacity": 1,
                            "curveness": 0,
                            "type": "solid"
                        }
                    },
                    "data": [
                        "AEV",
                        "AEV1",
                        "AEV2",
                        "AEV3",
                        "AEV4",
                        "AEV6.1",
                        "AEV6.2",
                        "AEV6.3",
                        "AEV8.1"
                    ]
                }
            ],
            "yAxis": [
        {
                    "type": "value",
                    "show": true,
                    "scale": false,
                    "nameLocation": "end",
                    "nameGap": 15,
                    "gridIndex": 0,
                    "axisLabel": {
                        "show": true,
                        "position": "top",
                        "margin": 8,
                        "formatter": "{value} h"
                    },
                    "inverse": false,
                    "offset": 0,
                    "splitNumber": 5,
                    "minInterval": 0,
                    "splitLine": {
                        "show": false,
                        "lineStyle": {
                            "show": true,
                            "width": 1,
                            "opacity": 1,
                            "curveness": 0,
                            "type": "solid"
                        }
                    }
                }
            ],
            "title": [
                {
                    "text": "2022-\u5404\u7ec4\u5de5\u65f6\u5206\u5e03",
                    "top": "5%",
                    "padding": 5,
                    "itemGap": 10
                }
            ],
            "tooltip": {
                "show": true,
                "trigger": "axis",
                "triggerOn": "mousemove|click",
                "axisPointer": {
                    "type": "shadow"
                },
                "showContent": true,
                "alwaysShowContent": false,
                "showDelay": 0,
                "hideDelay": 100,
                "textStyle": {
                    "fontSize": 14
                },
                "borderWidth": 0,
                "padding": 5
            },
            "color": [
                "#c23531",
                "#2f4554",
                "#61a0a8",
                "#d48265",
                "#749f83",
                "#ca8622",
                "#bda29a",
                "#6e7074",
                "#546570",
                "#c4ccd3",
                "#f05b72",
                "#ef5b9c",
                "#f47920",
                "#905a3d",
                "#fab27b",
                "#2a5caa",
                "#444693",
                "#726930",
                "#b2d235",
                "#6d8346",
                "#ac6767",
                "#1d953f",
                "#6950a1",
                "#918597"
            ]
        },
        {
            "legend": [
                {
                    "data": [
                        "Other",
                        "Electronics",
                        "Switch",
                        "Mechantronics"
                    ],
                    "selected": {
                        "Other": true,
                        "Electronics": true,
                        "Switch": true,
                        "Mechantronics": true
                    },
                    "show": true,
                    "top": "5%",
                    "padding": 5,
                    "itemGap": 10,
                    "itemWidth": 25,
                    "itemHeight": 14
                }
            ],
            "series": [
                {
                    "type": "bar",
                    "name": "Other",
                    "legendHoverLink": true,
                    "data": [
                        0,
                        170,
                        180.5,
                        723.5,
                        10,
                        454,
                        630.5,
                        300,
                        588.5
                    ],
                    "showBackground": false,
                    "stack": "stack1",
                    "barMinHeight": 0,
                    "barCategoryGap": "20%",
                    "barGap": "30%",
                    "large": false,
                    "largeThreshold": 400,
                    "seriesLayoutBy": "column",
                    "datasetIndex": 0,
                    "clip": true,
                    "zlevel": 0,
                    "z": 2,
                    "label": {
                        "show": false,
                        "position": "top",
                        "margin": 8
                    }
                },
                {
                    "type": "bar",
                    "name": "Electronics",
                    "legendHoverLink": true,
                    "data": [
                        170,
                        0,
                        552.5,
                        1301,
                        662.5,
                        662,
                        686.5,
                        777.5,
                        326.5
                    ],
                    "showBackground": false,
                    "stack": "stack1",
                    "barMinHeight": 0,
                    "barCategoryGap": "20%",
                    "barGap": "30%",
                    "large": false,
                    "largeThreshold": 400,
                    "seriesLayoutBy": "column",
                    "datasetIndex": 0,
                    "clip": true,
                    "zlevel": 0,
                    "z": 2,
                    "label": {
                        "show": false,
                        "position": "top",
                        "margin": 8
                    }
                },
                {
                    "type": "bar",
                    "name": "Switch",
                    "legendHoverLink": true,
                    "data": [
                        0,
                        0,
                        0,
                        0,
                        0,
                        0,
                        0,
                        0,
                        0
                    ],
                    "showBackground": false,
                    "stack": "stack1",
                    "barMinHeight": 0,
                    "barCategoryGap": "20%",
                    "barGap": "30%",
                    "large": false,
                    "largeThreshold": 400,
                    "seriesLayoutBy": "column",
                    "datasetIndex": 0,
                    "clip": true,
                    "zlevel": 0,
                    "z": 2,
                    "label": {
                        "show": false,
                        "position": "top",
                        "margin": 8
                    }
                },
                {
                    "type": "bar",
                    "name": "Mechantronics",
                    "legendHoverLink": true,
                    "data": [
                        0,
                        0,
                        0,
                        0,
                        0,
                        0,
                        0,
                        0,
                        0
                    ],
                    "showBackground": false,
                    "stack": "stack1",
                    "barMinHeight": 0,
                    "barCategoryGap": "20%",
                    "barGap": "30%",
                    "large": false,
                    "largeThreshold": 400,
                    "seriesLayoutBy": "column",
                    "datasetIndex": 0,
                    "clip": true,
                    "zlevel": 0,
                    "z": 2,
                    "label": {
                        "show": false,
                        "position": "top",
                        "margin": 8
                    }
                }
            ],
            "xAxis": [
                {
                    "show": true,
                    "scale": false,
                    "nameLocation": "end",
                    "nameGap": 15,
                    "gridIndex": 0,
                    "inverse": false,
                    "offset": 0,
                    "splitNumber": 5,
                    "minInterval": 0,
                    "splitLine": {
                        "show": false,
                        "lineStyle": {
                            "show": true,
                            "width": 1,
                            "opacity": 1,
                            "curveness": 0,
                            "type": "solid"
                        }
                    },
                    "data": [
                        "AEV",
                        "AEV1",
                        "AEV2",
                        "AEV3",
                        "AEV4",
                        "AEV6.1",
                        "AEV6.2",
                        "AEV6.3",
                        "AEV8.1"
                    ]
                }
            ],
            "yAxis": [
                {
                    "type": "value",
                    "show": true,
                    "scale": false,
                    "nameLocation": "end",
                    "nameGap": 15,
                    "gridIndex": 0,
                    "axisLabel": {
                        "show": true,
                        "position": "top",
                        "margin": 8,
                        "formatter": "{value} h"
                    },
                    "inverse": false,
                    "offset": 0,
                    "splitNumber": 5,
                    "minInterval": 0,
                    "splitLine": {
                        "show": false,
                        "lineStyle": {
                            "show": true,
                            "width": 1,
                            "opacity": 1,
                            "curveness": 0,
                            "type": "solid"
                        }
                    }
                }
            ],
            "title": [
                {
                    "text": "2022-\u5404\u7ec4\u5de5\u65f6\u5206\u5e03",
                    "top": "5%",
                    "padding": 5,
                    "itemGap": 10
                }
            ],
            "tooltip": {
                "show": true,
                "trigger": "axis",
                "triggerOn": "mousemove|click",
                "axisPointer": {
                    "type": "shadow"
                },
                "showContent": true,
                "alwaysShowContent": false,
                "showDelay": 0,
                "hideDelay": 100,
                "textStyle": {
                    "fontSize": 14
                },
                "borderWidth": 0,
                "padding": 5
            },
            "color": [
                "#c23531",
                "#2f4554",
                "#61a0a8",
                "#d48265",
                "#749f83",
                "#ca8622",
                "#bda29a",
                "#6e7074",
                "#546570",
                "#c4ccd3",
                "#f05b72",
                "#ef5b9c",
                "#f47920",
                "#905a3d",
                "#fab27b",
                "#2a5caa",
                "#444693",
                "#726930",
                "#b2d235",
                "#6d8346",
                "#ac6767",
                "#1d953f",
                "#6950a1",
                "#918597"
            ]
        }
    ]
};
        chart_0e4e014a351c4b2893d1f7a1037a88ff.setOption(option_0e4e014a351c4b2893d1f7a1037a88ff);
    </script>
                <div id="3126d1c14eba457196243d55bcc67af3" class="chart-container" style="width:900px; height:500px;"></div>
    <script>
        var chart_3126d1c14eba457196243d55bcc67af3 = echarts.init(
            document.getElementById('3126d1c14eba457196243d55bcc67af3'), 'white', {renderer: 'canvas'});
        var option_3126d1c14eba457196243d55bcc67af3 = {
    "baseOption": {
        "series": [
            {
                "type": "bar",
                "name": "Other",
                "legendHoverLink": true,
                "data": [
                    174.5,
                    121,
                    110.5,
                    310,
                    120
                ],
                "showBackground": false,
                "stack": "stack1",
                "barMinHeight": 0,
                "barCategoryGap": "20%",
                "barGap": "30%",
                "large": false,
                "largeThreshold": 400,
                "seriesLayoutBy": "column",
                "datasetIndex": 0,
                "clip": true,
                "zlevel": 0,
                "z": 2,
                "label": {
                    "show": false,
                    "position": "top",
                    "margin": 8
                }
            },
            {
                "type": "bar",
                "name": "Electronics",
                "legendHoverLink": true,
                "data": [
                    341.5,
                    385,
                    246.5,
                    0,
                    150.5
                ],
                "showBackground": false,
                "stack": "stack1",
                "barMinHeight": 0,
                "barCategoryGap": "20%",
                "barGap": "30%",
                "large": false,
                "largeThreshold": 400,
                "seriesLayoutBy": "column",
                "datasetIndex": 0,
                "clip": true,
                "zlevel": 0,
                "z": 2,
                "label": {
                    "show": false,
                    "position": "top",
                    "margin": 8
                }
            },
            {
                "type": "bar",
                "name": "Switch",
                "legendHoverLink": true,
                "data": [
                    0,
                    21,
                    38,
                    8,
                    61
                ],
                "showBackground": false,
                "stack": "stack1",
                "barMinHeight": 0,
                "barCategoryGap": "20%",
                "barGap": "30%",
                "large": false,
                "largeThreshold": 400,
                "seriesLayoutBy": "column",
                "datasetIndex": 0,
                "clip": true,
                "zlevel": 0,
                "z": 2,
                "label": {
                    "show": false,
                    "position": "top",
                    "margin": 8
                }
            },
            {
                "type": "bar",
                "name": "Mechantronics",
                "legendHoverLink": true,
                "data": [
                    16,
                    0,
                    0,
                    66,
                    42.5
                ],
                "showBackground": false,
                "stack": "stack1",
                "barMinHeight": 0,
                "barCategoryGap": "20%",
                "barGap": "30%",
                "large": false,
                "largeThreshold": 400,
                "seriesLayoutBy": "column",
                "datasetIndex": 0,
                "clip": true,
                "zlevel": 0,
                "z": 2,
                "label": {
                    "show": false,
                    "position": "top",
                    "margin": 8
                }
            }
        ],
        "timeline": {
            "axisType": "category",
            "orient": "horizontal",
            "autoPlay": true,
            "controlPosition": "left",
            "loop": true,
            "rewind": false,
            "show": true,
            "inverse": false,
            "playInterval": 3000,
            "top": "460px",
            "bottom": "-5px",
            "data": [
                "6\u6708",
                "7\u6708"
            ]
        },
        "xAxis": [
            {
                "show": true,
                "scale": false,
                "nameLocation": "end",
                "nameGap": 15,
                "gridIndex": 0,
                "axisLabel": {
                    "show": true,
                    "position": "top",
                    "rotate": -15,
                    "margin": 8
                },
                "inverse": false,
                "offset": 0,
                "splitNumber": 5,
                "minInterval": 0,
                "splitLine": {
                    "show": false,
                    "lineStyle": {
                        "show": true,
                        "width": 1,
                        "opacity": 1,
                        "curveness": 0,
                        "type": "solid"
                    }
                },
                "data": [
                    [
                        "P08248.03",
                        "NIO Force BLE-UWB"
                    ],
                    [
                        "P08513.02",
                        "GWM ES11 KBCM&FOB"
                    ],
                    [
                        "P08223.02",
                        "Ford CX743 PEPS+"
                    ],
                    [
                        "P08437",
                        "NIO Pegasus DCU"
                    ],
                    [
                        "P08558.02",
                        "Yutong Light Bus PEPS+"
                    ]
                ]
            }
        ],
        "yAxis": [
            {
                "type": "value",
                "show": true,
                "scale": false,
                "nameLocation": "end",
                "nameGap": 15,
                "gridIndex": 0,
                "axisLabel": {
                    "show": true,
                    "position": "top",
                    "margin": 8,
                    "formatter": "{value} h"
                },
                "inverse": false,
                "offset": 0,
                "splitNumber": 5,
                "minInterval": 0,
                "splitLine": {
                    "show": false,
                    "lineStyle": {
                        "show": true,
                        "width": 1,
                        "opacity": 1,
                        "curveness": 0,
                        "type": "solid"
                    }
                }
            }
        ]
    },
    "options": [
        {
            "legend": [
                {
                    "data": [
                        "Other",
                        "Electronics",
                        "Switch",
                        "Mechantronics"
                    ],
                    "selected": {
                        "Other": true,
                        "Electronics": true,
                        "Switch": true,
                        "Mechantronics": true
                    },
                    "show": true,
                    "top": "5%",
                    "padding": 5,
                    "itemGap": 10,
                    "itemWidth": 25,
                    "itemHeight": 14
                }
            ],
            "series": [
                {
                    "type": "bar",
                    "name": "Other",
                    "legendHoverLink": true,
                    "data": [
                        102,
                        191,
                        182.5,
                        0,
                        22.5
                    ],
                    "showBackground": false,
                    "stack": "stack1",
                    "barMinHeight": 0,
                    "barCategoryGap": "20%",
                    "barGap": "30%",
                    "large": false,
                    "largeThreshold": 400,
                    "seriesLayoutBy": "column",
                    "datasetIndex": 0,
                    "clip": true,
                    "zlevel": 0,
                    "z": 2,
                    "label": {
                        "show": false,
                        "position": "top",
                        "margin": 8
                    }
                },
                {
                    "type": "bar",
                    "name": "Electronics",
                    "legendHoverLink": true,
                    "data": [
                        527.5,
                        276,
                        275.5,
                        397.5,
                        397.0
                    ],
                    "showBackground": false,
                    "stack": "stack1",
                    "barMinHeight": 0,
                    "barCategoryGap": "20%",
                    "barGap": "30%",
                    "large": false,
                    "largeThreshold": 400,
                    "seriesLayoutBy": "column",
                    "datasetIndex": 0,
                    "clip": true,
                    "zlevel": 0,
                    "z": 2,
                    "label": {
                        "show": false,
                        "position": "top",
                        "margin": 8
                    }
                },
                {
                    "type": "bar",
                    "name": "Switch",
                    "legendHoverLink": true,
                    "data": [
                        38,
                        0,
                        43,
                        72,
                        0
                    ],
                    "showBackground": false,
                    "stack": "stack1",
                    "barMinHeight": 0,
                    "barCategoryGap": "20%",
                    "barGap": "30%",
                    "large": false,
                    "largeThreshold": 400,
                    "seriesLayoutBy": "column",
                    "datasetIndex": 0,
                    "clip": true,
                    "zlevel": 0,
                    "z": 2,
                    "label": {
                        "show": false,
                        "position": "top",
                        "margin": 8
                    }
                },
                {
                    "type": "bar",
                    "name": "Mechantronics",
                    "legendHoverLink": true,
                    "data": [
                        10,
                        80,
                        2,
                        0,
                        24
                    ],
                    "showBackground": false,
                    "stack": "stack1",
                    "barMinHeight": 0,
                    "barCategoryGap": "20%",
                    "barGap": "30%",
                    "large": false,
                    "largeThreshold": 400,
                    "seriesLayoutBy": "column",
                    "datasetIndex": 0,
                    "clip": true,
                    "zlevel": 0,
                    "z": 2,
                    "label": {
                        "show": false,
                        "position": "top",
                        "margin": 8
                    }
                }
            ],
            "xAxis": [
                {
                    "show": true,
                    "scale": false,
                    "nameLocation": "end",
                    "nameGap": 15,
                    "gridIndex": 0,
                    "axisLabel": {
                        "show": true,
                        "position": "top",
                        "rotate": -15,
                        "margin": 8
                    },
                    "inverse": false,
                    "offset": 0,
                    "splitNumber": 5,
                    "minInterval": 0,
                    "splitLine": {
                        "show": false,
                        "lineStyle": {
                            "show": true,
                            "width": 1,
                            "opacity": 1,
                            "curveness": 0,
                            "type": "solid"
                        }
                    },
                    "data": [
                        [
                            "P08513.02",
                            "GWM ES11 KBCM&FOB"
                        ],
                        [
                            "P08248.03",
                            "NIO Force BLE-UWB"
                        ],
                        [
                            "P08223.02",
                            "Ford CX743 PEPS+"
                        ],
                        [
                            "P08558.02",
                            "Yutong Light Bus PEPS+"
                        ],
                        [
                            "P08254.02",
                            "GWM P03 BLE RSSI"
                        ]
                    ]
                }
            ],
            "yAxis": [
                {
                    "type": "value",
                    "show": true,
                    "scale": false,
                    "nameLocation": "end",
                    "nameGap": 15,
                    "gridIndex": 0,
                    "axisLabel": {
                        "show": true,
                        "position": "top",
                        "margin": 8,
                        "formatter": "{value} h"
                    },
                    "inverse": false,
                    "offset": 0,
                    "splitNumber": 5,
                    "minInterval": 0,
                    "splitLine": {
                        "show": false,
                        "lineStyle": {
                            "show": true,
                            "width": 1,
                            "opacity": 1,
                            "curveness": 0,
                            "type": "solid"
                        }
                    }
                }
            ],
            "title": [
                {
                    "text": "2022-\u5de5\u65f6\u5728\u9879\u76ee\u5206\u5e03Top5",
                    "top": "5%",
                    "padding": 5,
                    "itemGap": 10
                }
            ],
            "tooltip": {
                "show": true,
                "trigger": "axis",
                "triggerOn": "mousemove|click",
                "axisPointer": {
                    "type": "shadow"
                },
                "showContent": true,
                "alwaysShowContent": false,
                "showDelay": 0,
                "hideDelay": 100,
                "textStyle": {
                    "fontSize": 14
                },
                "borderWidth": 0,
                "padding": 5
            },
            "color": [
                "#c23531",
                "#2f4554",
                "#61a0a8",
                "#d48265",
                "#749f83",
                "#ca8622",
                "#bda29a",
                "#6e7074",
                "#546570",
                "#c4ccd3",
                "#f05b72",
                "#ef5b9c",
                "#f47920",
                "#905a3d",
                "#fab27b",
                "#2a5caa",
                "#444693",
                "#726930",
                "#b2d235",
                "#6d8346",
                "#ac6767",
                "#1d953f",
                "#6950a1",
                "#918597"
            ]
        },
        {
            "legend": [
                {
                    "data": [
                        "Other",
                        "Electronics",
                        "Switch",
                        "Mechantronics"
                    ],
                    "selected": {
                        "Other": true,
                        "Electronics": true,
                        "Switch": true,
                        "Mechantronics": true
                    },
                    "show": true,
                    "top": "5%",
                    "padding": 5,
                    "itemGap": 10,
                    "itemWidth": 25,
                    "itemHeight": 14
                }
            ],
            "series": [
                {
                    "type": "bar",
                    "name": "Other",
                    "legendHoverLink": true,
                    "data": [
                        174.5,
                        121,
                        110.5,
                        310,
                        120
                    ],
                    "showBackground": false,
                    "stack": "stack1",
                    "barMinHeight": 0,
                    "barCategoryGap": "20%",
                    "barGap": "30%",
                    "large": false,
                    "largeThreshold": 400,
                    "seriesLayoutBy": "column",
                    "datasetIndex": 0,
                    "clip": true,
                    "zlevel": 0,
                    "z": 2,
                    "label": {
                        "show": false,
                        "position": "top",
                        "margin": 8
                    }
                },
                {
                    "type": "bar",
                    "name": "Electronics",
                    "legendHoverLink": true,
                    "data": [
                        341.5,
                        385,
                        246.5,
                        0,
                        150.5
                    ],
                    "showBackground": false,
                    "stack": "stack1",
                    "barMinHeight": 0,
                    "barCategoryGap": "20%",
                    "barGap": "30%",
                    "large": false,
                    "largeThreshold": 400,
                    "seriesLayoutBy": "column",
                    "datasetIndex": 0,
                    "clip": true,
                    "zlevel": 0,
                    "z": 2,
                    "label": {
                        "show": false,
                        "position": "top",
                        "margin": 8
                    }
                },
                {
                    "type": "bar",
                    "name": "Switch",
                    "legendHoverLink": true,
                    "data": [
                        0,
                        21,
                        38,
                        8,
                        61
                    ],
                    "showBackground": false,
                    "stack": "stack1",
                    "barMinHeight": 0,
                    "barCategoryGap": "20%",
                    "barGap": "30%",
                    "large": false,
                    "largeThreshold": 400,
                    "seriesLayoutBy": "column",
                    "datasetIndex": 0,
                    "clip": true,
                    "zlevel": 0,
                    "z": 2,
                    "label": {
                        "show": false,
                        "position": "top",
                        "margin": 8
                    }
                },
                {
                    "type": "bar",
                    "name": "Mechantronics",
                    "legendHoverLink": true,
                    "data": [
                        16,
                        0,
                        0,
                        66,
                        42.5
                    ],
                    "showBackground": false,
                    "stack": "stack1",
                    "barMinHeight": 0,
                    "barCategoryGap": "20%",
                    "barGap": "30%",
                    "large": false,
                    "largeThreshold": 400,
                    "seriesLayoutBy": "column",
                    "datasetIndex": 0,
                    "clip": true,
                    "zlevel": 0,
                    "z": 2,
                    "label": {
                        "show": false,
                        "position": "top",
                        "margin": 8
                    }
                }
            ],
            "xAxis": [
                {
                    "show": true,
                    "scale": false,
                    "nameLocation": "end",
                    "nameGap": 15,
                    "gridIndex": 0,
                    "axisLabel": {
                        "show": true,
                        "position": "top",
                        "rotate": -15,
                        "margin": 8
                    },
                    "inverse": false,
                    "offset": 0,
                    "splitNumber": 5,
                    "minInterval": 0,
                    "splitLine": {
                        "show": false,
                        "lineStyle": {
                            "show": true,
                            "width": 1,
                            "opacity": 1,
                            "curveness": 0,
                            "type": "solid"
                        }
                    },
                    "data": [
                        [
                            "P08248.03",
                            "NIO Force BLE-UWB"
                        ],
                        [
                            "P08513.02",
                            "GWM ES11 KBCM&FOB"
                        ],
                        [
                            "P08223.02",
                            "Ford CX743 PEPS+"
                        ],
                        [
                            "P08437",
                            "NIO Pegasus DCU"
                        ],
                        [
                            "P08558.02",
                            "Yutong Light Bus PEPS+"
                        ]
                    ]
                }
            ],
            "yAxis": [
                {
                    "type": "value",
                    "show": true,
                    "scale": false,
                    "nameLocation": "end",
                    "nameGap": 15,
                    "gridIndex": 0,
                    "axisLabel": {
                        "show": true,
                        "position": "top",
                        "margin": 8,
                        "formatter": "{value} h"
                    },
                    "inverse": false,
                    "offset": 0,
                    "splitNumber": 5,
                    "minInterval": 0,
                    "splitLine": {
                        "show": false,
                        "lineStyle": {
                            "show": true,
                            "width": 1,
                            "opacity": 1,
                            "curveness": 0,
                            "type": "solid"
                        }
                    }
                }
            ],
            "title": [
                {
                    "text": "2022-\u5de5\u65f6\u5728\u9879\u76ee\u5206\u5e03Top5",
                    "top": "5%",
                    "padding": 5,
                    "itemGap": 10
                }
            ],
            "tooltip": {
                "show": true,
                "trigger": "axis",
                "triggerOn": "mousemove|click",
                "axisPointer": {
                    "type": "shadow"
                },
                "showContent": true,
                "alwaysShowContent": false,
                "showDelay": 0,
                "hideDelay": 100,
                "textStyle": {
                    "fontSize": 14
                },
                "borderWidth": 0,
                "padding": 5
            },
            "color": [
                "#c23531",
                "#2f4554",
                "#61a0a8",
                "#d48265",
                "#749f83",
                "#ca8622",
                "#bda29a",
                "#6e7074",
                "#546570",
                "#c4ccd3",
                "#f05b72",
                "#ef5b9c",
                "#f47920",
                "#905a3d",
                "#fab27b",
                "#2a5caa",
                "#444693",
                "#726930",
                "#b2d235",
                "#6d8346",
                "#ac6767",
                "#1d953f",
                "#6950a1",
                "#918597"
            ]
        }
    ]
};
        chart_3126d1c14eba457196243d55bcc67af3.setOption(option_3126d1c14eba457196243d55bcc67af3);
    </script>
    </div>

    <script>
    </script>
    <script>
        (function() {
            containers = document.getElementsByClassName("chart-container");
            if(containers.length > 0) {
                containers[0].style.display = "block";
            }
        })()

        function showChart(evt, chartID) {
            let containers = document.getElementsByClassName("chart-container");
            for (let i = 0; i < containers.length; i++) {
                containers[i].style.display = "none";
            }

            let tablinks = document.getElementsByClassName("tablinks");
            for (let i = 0; i < tablinks.length; i++) {
                tablinks[i].className = "tablinks";
            }

            document.getElementById(chartID).style.display = "block";
            evt.currentTarget.className += " active";
        }
    </script>
</body>
</html>

