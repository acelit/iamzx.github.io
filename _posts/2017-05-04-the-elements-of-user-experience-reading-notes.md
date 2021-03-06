---
layout: post
title: "【005】《用户体验要素》读书笔记"
comments: true
description: "《用户体验要素》读书笔记"
keywords: ""
---
>在看《用户体验要素》这本书时，明显感觉到很吃力，作者从“**道**”的高度概括了**用户体验五要素**，并围绕这五个要素进行了逐一论述。本人由于缺乏一定的项目实践积累，不能完全体会本书的精髓，只希望“**以术论道**”，和大家分享个人愚见。

全书核心——一图以蔽之：

![用户体验五层次](http://img.blog.csdn.net/20170504140701541?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

用户体验五要素似乎翻译成【用户体验五层次】更贴切一些，任何复杂的设计都可以通过分层来解决，这也是软件设计的一项技能。本书将用户体验设计从抽象到具体分为**战略层、范围层、结构层、框架层和表现层**。

其中，两端的层次最好理解，战略层要求我们思考“**为什么**要开发这个产品”的问题，对企业必然是能获取商业利益，对用户必然是满足个人需求，从内到外的结合才能更好满足双方的需求。表现层离用户最近，我们作为用户时视觉上最能够直接感知产品的那部分，譬如图片、图标、颜色、背景等，这部分也通常被人狭隘地理解为用户体验。

再来谈一下功能性产品和信息性产品的区别：

 - **功能型产品：产品具备某种功能，以完成某项任务，重解决方法。**

 - **信息型产品：产品具有某些内容，以满足用户情感，重精神需求。**

通常这五个层次是自下而上即`战略层->范围层->结构层->框架层->表现层`来进行建设的，下面结合【滴滴出行】来理解这五个层次的具体含义。

----
#### 战略层：需要同时满足企业商业目标和用户需求
企业的商业目标既可能是短期的有可能是长期的，既可以用利润来衡量也可以用品牌形象、用户粘度等指标来衡量。

用户需求可能是用户自己提出来的需求，有时候还需要我们来分析用户真正的需求、进一步挖掘用户需求。

同一个产品，我们首先要区分用户维度，细分用户群体——即确定我们的目标用户，从而满足目标用户，因为我们很难提供一种方案来同时满足两种用户的需求。

战略是决定一切产品命运的前提，我们该如何做好战略层面的规划呢？
首先，要分析市场行情，其次要分析用户心理，通过用户模型划分用户群体，进而确定产品定位。

以滴滴为例，经济的发展促进私家车保有量提高，传统出租车市场无法很好满足人们快速出行的要求，互联网思维在各行各业的应用，使乘客能够快速接受互联网约车的出行方式。一二线城市中初入职场还没能力购车的上班族、大学生、短程游客都成为滴滴的目标用户。

----
#### 范围层：确定产品特性和功能
战略层解决的是“为什么”的问题，而范围层者解决“是什么”的问题。为了要解决战略层提出的内外两种需求，产品需要哪些功能？我们通常会为产品提出很多功能，但是各功能之间必须确定优先级，哪些是必须的、核心的，哪些是可有可无的，哪些是以后可以再拓展的？

滴滴出行的基本功能包括：快车、专车、出租车、顺风车、代驾、自驾租车、试驾等。

核心功能：

|  功能  |  时间 |  特点 |
|--|--|--|
|专车|2014.8|中高端商务约车|
|快车|2015.5|优惠出行|
|顺风车|2015.6|共享出行|
|代驾|2015.7|“起步价+公里费”|
|租车|2016.8|全程上门取送车|


----------

#### 结构层：确定产品的业务逻辑
结构层是产品设计中从从抽象到具体的过渡层，也就是通过与用户进行交互来实现产品功能，满足用户需求。结构层注重对业务逻辑的理解，要让用户通过点击按钮到达某个页面，以及明确各个页面的层次关系。这有点像写论文的时候要先确定论文整体目录，最常见的组织方式是**树状结构**，当然还有**矩阵结构、自然结构、线性结构**等。

 - 树状结构
![树状结构](http://img.blog.csdn.net/20170504163242364?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

 - 矩阵结构
![矩阵结构](http://img.blog.csdn.net/20170504163353963?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

 - 自然结构

![自然结构](http://img.blog.csdn.net/20170504163455880?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

- 线性结构

![线性结构](http://img.blog.csdn.net/20170504163522568?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

不同的组织结构可以遵循不同的的组织原则，但一定要直观、让用户容易理解、操作方便。非常喜欢de Saint-Exupery的一句话：
>你知道你的设计达到完美，不是因为你没有什么可以加上去，而是当你不能再除去些东西的时候。

滴滴出行的结构图如下：
![滴滴出行结构图](http://img.blog.csdn.net/20170504173052243?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)


----------
#### 框架层：确定图片、按钮在页面的位置

#### 表现层：与视觉有关的元素，图片、图标、按钮、背景、分割线、颜色、材质、肌理、形状、圆角、投影等

这两部分基本上由UI设计师完成，涉及到布局、配色、排版等设计风格，对设计师的内功修为提出了很高的要求。


----------


### 总结

>用户体验层次之间并不是相互独立的，下一层的决策会影响上一层的设计，而上一层也可以反过来对下一层产生互锁影响。

 - 下层对上层的影响：

![单层影响](http://img.blog.csdn.net/20170504175522434?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

 

 - 上下层相互影响：

![多层影响](http://img.blog.csdn.net/20170504175547981?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

>鉴于各层之间会相互影响，在整个产品设计过程中，任何一个层面中的工作都不能在其下层的工作完成之前结束。

![各层顺序](http://img.blog.csdn.net/20170504180223205?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYWNlbGl0/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

本书的结尾以马拉松来比作用户体验开发，诚然，要想做出用户体验非常好的产品绝非易事，在迭代开发的过程中不断审视产品的不足，时刻把握每个层次可能出现的问题，反馈，修改，再反馈，再修改......
