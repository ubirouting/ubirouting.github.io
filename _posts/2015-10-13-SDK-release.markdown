---
layout: post
title:  "识途发布室内定位SDK v0.1"
date:   2015-10-13 17:33:33 +0800
categories: ubirouting
description: "今天我们宣布在iOS和Android平台上全面发布各种引擎的SDK，包括：地磁SDK、Wi-Fi SDK"
author: "LiKe"
---

    System.out.println("hello, ubirouting SDK.");

    mLocationManager = ShituLocationManager.newManager(this, parameters);
    mLocationManager.setOnNatureListener(this);


今天我们宣布在iOS和Android平台上全面发布各种引擎的SDK，包括：地磁SDK、Wi-Fi SDK。这是北京识途科技有限公司继不久前发布*识途 Creator*采集和定位工具以来的又一重大成果。这些成果是我们长期坚持脚踏实地的研究的最好报答。

今天发布的SDK是我们的核心产品“识途云”构架中的一部分。

地磁SDK和Wi-Fi SDK可以将用户APP实时收到的室内环境数据（地磁或者Wi-Fi）传送给“识途云”的定位服务器，利用我们特有的室内定位算法分析出用户的具体位置，再该位置结果返回给APP，从而让APP实现精确的室内定位功能。

矢量地图SDK的功能有：

- 地图：提供2D地图的展示和缩放、平移、旋转等地图操作；
- 线路规划：支持步行路径检索；
- 覆盖物：提供多种地图覆盖物（自定义标注、几何图形、文字绘制、地形图图层等），满足开发者的各种需求；
- 定位：采用多种定位模式，使用定位SDK获取位置信息，使用地图SDK中的位置图层进行位置展示；

安卓SDK支持4.0以上版本；iOS SDK支持8.0以上版本。用户可以在[识途开发者平台](open.ubirouting.com)免费下载这些SDK，并获取开发者文档。识途官方QQ （3314478190）提供技术咨询。
