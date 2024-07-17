# UI框架实战

## 简介

按理来说，个人开发应该直接找个轮椅用，去大厂大螺丝，应该有现成的用。但这个项目是手搓，最基本的那种，用来熟悉一下框架大概需要实现些什么，也是拖UI的底层基础。

UI框架主要实现UILayer作为基类，分别实现Panel（面板）和Window（窗口、弹窗）层，配套搭配对应的PanelController和WindowController实现逻辑和显示的分离。

通过UIFrame对外部暴露统一开启关闭界面等接口，在显示上合理的划分好节点，做好层级遮挡。

对于Window实现队列和栈进行弹出的管理，Panel则不用。

支持界面的传参（Properties类），搭配动画组件和事件系统，形成完整健全的UI框架。

## 链接

详细文档：https://gongqihua.github.io/

演示Demo在Demo文件夹下：传送门