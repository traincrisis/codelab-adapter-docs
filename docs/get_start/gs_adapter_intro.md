# Codelab Adapter 概览

<!--补充魔杖视频的链接 -->
大家可能会好奇，[魔杖一挥](https://adapter.codelab.club/user_guide/gallery/#_17)是怎么将所有灯都关闭的，又是怎么做到将手抬起，[窗帘就顺应而升](https://adapter.codelab.club/user_guide/gallery/#_20)的? 其实这些神奇的场景都是在Adapter的帮助下完成的。

<!-- 介绍一个例子像大家介绍清楚利用Adapter操作的过程-->
Adapter使用 **扩展** 将两个事物连接起来，在魔杖亮灯的场景中，Adapter将魔杖和灯连接起来，我们在创作平台中利用Adapter提供的扩展对魔杖和灯进行编程，之后用魔杖画出相应的手势，灯就亮起来了。

## Adapter的核心组件

Adapter的扩展分为 **插件** 和 **节点** ，有小伙伴会问到：“为什么都是扩展，还要区分为不同的两个东西啊？”

这主要是因为插件和节点所需要的依赖不同，相比于插件，节点需要的依赖会更多也更复杂，比如说用手势控制窗帘升降用到的扩展就是节点。

如果想进一步了解请看[插件和节点的区别](https://adapter.codelab.club/dev_guide/Adapter-Node/)

在简单介绍Adatper的具体组件后，我们进入安装环节。