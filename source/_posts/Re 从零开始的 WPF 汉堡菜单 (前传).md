---
title: Re 从零开始的 WPF 汉堡菜单 (前传)
date: 2022-03-15 09:34:06
tags: [•ᴗ•, SoftWare, C#, WPF]
categories: 
  - 技术
  - C#
excerpt: 服务员，上汉堡菜单!
index_img: /img/index/Re 从零开始的 WPF 汉堡菜单 (前传).webp
---

**(本文为项目 Ona Pix 的部分开发记录，项目基于 WPF .Net5 框架，开源地址: https://github.com/SpaceTimee/Ona-Pix)**

作为一个未来想要成为 Pixiv 第三方客户端的 "大项目"，给 Ona Pix 添加一个设置窗口当然是必不可少的，要想做设置窗口，我第一个想到的就是 Hamberger Menu，汉堡菜单，一个我从爆伯的 UWP 教程中学到的名词

![BV1is41197MU](/img/illustration/BV1is41197MU.webp)

左侧一栏目录，右侧显示内容，肥肠地不辍。我重新看了一遍视频，原来爆伯使用的是一个叫做 SplitView 的控件，那太好了，作为一名资深 CV 党，只需要把代码 Copy 下来，再微改几下，应该就能轻松秒杀了，我心里暗自窃喜，没想到这么轻松就搞定了，完全没难度嘛 ~

虽然但是，然而然而，我的直觉却告诉我，这一切并没有这么简单。其实当我看到 SplitView 这个名字的时候，我心里就凉了半截，以前好像没在工具栏里看到过这个控件啊？该不会是 WinUI 特有的控件吧，但我转念一想，人家 Hyperlink 不也不在工具栏里吗，不照样能在 Label 里使用，我如是安慰自己，抱着试一试的心态，输入 SplitView

> Error: 未找到类型“SplitView”。请确保不缺少程序集引用并且已生成所有引用的程序集

好吧，这下是真的彻底寄了，WPF 果然还是没有 SplitView 控件。目前我能想到的，还有2个办法，第一个，在 WPF 中引入 UWP 控件；第二个，自己从零开始手写一个汉堡菜单。两个想法都挺不错，反正做项目的目的也是为了学习新技术，不如两个方案都试一下，我想先试试第二个。

**[To Be Continued •ᴗ•]**