---
layout: post
title:  "分析生产管线自动化 Data Analytic Pipeline Automation"
date:   2023-09-13 09:33:30
author: Zizhun Guo
category: Projects
categories: jekyll update
visible: 1
porject: 1
---

###### 目录
- [目录](#目录)
- [为什么要自动化 Why Go Auto](#为什么要自动化-why-go-auto)
- [需求场景 Request Scenarios](#需求场景-request-scenarios)
- [精益法 Lean Development](#精益法-lean-development)
- [流程脚本化](#流程脚本化)


###### 为什么要自动化 Why Go Auto

希腊神话中有一位王子叫西西弗斯，狡诈机智，因钻漏洞和不守约定而被冥王黑帝斯惩罚，每日推大石到陡峭的山峰，但在大石将要抵达山顶时从手中滑脱滚落，无止境地劳作。这个故事告诉我们三件事情：1. 事情在没成功之前都有失败的可能； 2. 希望破灭最为痛苦； 3. 重复是抹杀灵魂的一种方式。困难的事情不可怕，可怕的是相同的事情变得重复化。

###### 需求场景 Request Scenarios

在平日的大数据分析挖掘工作中，相信很多从业者可能都会有这么一个感触，如果需求方一直不停地提出相同的需求，为了满足他们，工作不仅会变得饱和，而且会变得重复，因为大部分需求出发点是相似和固定的，变化的仅仅是约束条件，比如时间范围，分组对象。这部分工作则完全可以由T+1的形式，通过ETL数仓表的形式落地，也可以在BI dashboard通过前端渲染在web页面里，供业务方实时查阅。但那些介于中间形态的产品，比如一个刚刚提出的想法，一个粗略的需求，一个即插即用的统计报告，则很难落地为需要数仓人员正式落盘的排期任务，这种原始阶段“灵活”的提数需求满足，则会成为分析人员占用大量时间的工作内容。

###### 精益法 Lean Development

实际上问题的本质是，如何提高价值提交能力？我们已经迭代出了产品（已有查询统计代码），且用户满意（历史的统计结果有效性经过使用人员验证），和少量迭代需求（逻辑改动地方少）。不存在需要强调进度的连续性和可提高性，在这个情况下，采用Lean Development（精益法）的概念更为有效。精益法讲究精度和效率，简单讲叫“有的放矢，反应迅速”。在分析挖掘场景里，意味着需求的快速可实现，和实现结果高成功率。自动化完美满足这两个条件。


###### 流程脚本化

脚本化的目的是在于，所有人工的中间操作都由一条条脚本命令替代，这是工程师需要达到的能力，因为所有内容都是数据，存储在电脑内存和硬盘中，代码就是数字信息的搬运工，而信息只是通过一个又一个方法输入返回地重复，所以需要将操作流程原子化。

---
Copyright @ 2021 Zizhun Guo. All Rights Reserved.

