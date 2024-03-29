---
title: PSDK API 概览
date: 2023-05-24
---



> **说明：**

GDU 为支持开发者开发出可挂载在GDU 无人机上的负载设备，提供了开发工具包Payload SDK（即PSDK）以及开发配件FlyPort转接环，方便开发者利用GDU 无人机上如电源、通讯链路及状态信息等**资源**，开发出可挂载在GDU 无人机上的负载设备。开发者能够根据行业的应用需求，基于PSDK提供的功能接口，结合具体的结构设计、硬件设计、软件逻辑实现和算法优化，开发出如**自动巡检系统**、**红外相机**、**测绘相机**、**多光谱相机**、**喊话器**、**探照灯**等满足不同细分领域的负载设备。

## 主要特性

- 使用C 语言开发
- 支持主流的嵌入式系统，如Linux 和RTOS
- 模块化的设计思路，易于跨平台移植