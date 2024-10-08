---
title: C++简介
date: 2024-10-07 09:24:05
tags:
  - C++
---
# 简介

名称`C++`来自C语言中的递增运算符`++`，该运算符将变量加1。名称`C++`表明，它是C的扩充版本。

`C++`融合了3种不同的编程方式：C语言代表的过程性语言、`C++`在C语言基础上添加的类代表的面向对象语言、`C++`模板支撑的泛型编程。

在`C++`中，类是一种规范，它描述了这种新型数据格式，对象是根据这种规范构造的特定数据结构。通常，类规定了可使用哪些数据来表示对象，以及可以对这些数据执行哪些操作。

OOP是一个管理大型项目的工具，而泛型编程提供了执行常见任务（如对数据排序或合并链表）的工具。

## 版本

`ISO/IEC 14882:1998`标准常被称为 `C++98`。

`ISO/IEC 14882:2011`标准被称为`C++11`。

## C++运行步骤

*   编写源代码
*   编译器
*   目标代码
*   链接程序（启动代码+库代码）
*   可执行代码

最初，Stroustrup实现`C++`时，使用了一个`C++`到C的编译器程序，而不是开发直接的`C++`到目标代码的编译器。 前者叫做`cfront`（表示C前端，C front end），它将C++源代码翻译成C源代码，然后使用一个标准C编译器对其进行编译。

随着`C++`的日渐普及，越来越多的实现转向创建`C++`编译器，直接将`C++`源代码生成目标代码。

