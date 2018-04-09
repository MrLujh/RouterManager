# ☆☆☆ “RouteManager” ☆☆☆

## 支持pod导入
* pod 'RouteManager'

![Mou icon](https://github.com/MrLujh/RouteManager/blob/master/resource/21432543.gif)

## 架构怎么进化

*架构进化体现在哪些方面，作为一个技术团队我们要如何把架构进化落地？这个问题因项目而异，因团队而异，因方向而异。本文只介绍手机天猫在发展过程中，与解耦相关的进化历程。

* 升级开发模式

     * 开发模式的概念有点大，本文就只讨论和解耦这件事相关的：团队合作方式和工程组织形式。下文单独一节聊这个事，此处不赘述。
 
* 各维度解耦

     * 工程大了以后，要分拆，不管是组件化还是插件化，还是什么，解耦是第一步，而且是各个维度的解耦。
 
* 升级开发模式

     * 模式演进的过程中，解耦的过程中，就会衍生出很多的工具。在进化过程里我们也会去思考，哪些工作是需要工具化的，主动去开发工具。一个完善的工具集，会极大提升团队的生产力，可以说是最有价值的部分。
 
 ## 解耦思路
 
 主要解决依赖耦合和工程耦合。
 
 工欲善其事，必先利其器。这句话每个人都在说，却不是每个人都能做到。一个具有工具文化的团队会在质量，效率各个方面都会有很大优势。
 
 在这个膨胀过程里，我把耦合分成三类：

* 界面耦合，就是用户操作流程里，从首页-到搜索-到详情-再进店，这些界面的跳转是硬编码的
* 依赖耦合，顾名思义，两个模块之间的有依赖，就是耦合
* 工程耦合，每个模块有自己的生命周期和运行时，每个模块在生产环境里又需要依赖主工程的运行时

## Contents
* Getting Started
    * [Features【Support what kinds of controls to refresh】](#Support_what_kinds_of_controls_to_refresh)
    * [Installation【How to use MJRefresh】](#How_to_use_MJRefresh)
    * [Who's using【More than hundreds of Apps are using MJRefresh】](#More_than_hundreds_of_Apps_are_using_MJRefresh)
    * [Classes【The Class Structure Chart of MJRefresh】](#The_Class_Structure_Chart_of_MJRefresh)
