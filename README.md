# 野火HAL库开发学习笔记

## 说明

**本库仅供学习交流使用**

- 编译器： ARM v5.06
- C编译版本: C99
- 固件库版本: V3.5.0
- MDK version: 538A
- 芯片包: Keil.STM32F1xx_DFP.2.4.1
- **芯片型号**: STM32F103ZET6
- **参考视频**: 【【野火】STM32 HAL库开发实战指南 教学视频 手把手教学STM32全系列 零基础入门CubeMX+HAL库，基于野火全系列STM32开发板】 https://www.bilibili.com/video/BV18X4y1M763/?share_source=copy_web&vd_source=0db47c15b9f51dbaa4548ec2dc55dea4

## 内核差异介绍

**Cotex 内核指令的差异**

![Cotex 内核指令差异](https://raw.githubusercontent.com/See-YouL/MarkdownPhotos/main/%E6%88%AA%E5%B1%8F2024-01-07%2009.04.51.png)

- 指令集, 浮点运算, 数字信号处理
- 是否有cache, TCM
- 性能的差异
- 功耗

## 
