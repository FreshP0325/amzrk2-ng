---
title: '计算机专业基础笔记'
date: 2019-01-07T11:05:30+08:00
tags:
  - ds
  - os
  - algorithm
description: '计算机专业基础笔记。'
---

计算机专业基础相关笔记。

<!--more-->

## 算法与数据结构

### 常用排序算法

![时间复杂度与稳定性](/images/2019/basic-note/20201022110804.webp)

## 操作系统

### 进程与线程

线程是进程中执行运算的最小单位，是系统独立调度资源的基本单位，线程自己不拥有系统资源，但可与同属一个进程的其它线程共享该进程所拥有的全部资源。一个线程可以创建和撤消另一个线程，同一进程中的多个线程之间可以并发执行。

一个线程只能属于一个进程，而一个进程可以有多个线程；资源分配给进程，同一进程的所有线程共享该进程的所有资源；线程作为调度和分配的基本单位，进程作为拥有资源的基本单位。
