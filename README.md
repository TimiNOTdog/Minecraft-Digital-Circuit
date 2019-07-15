# Minecraft-Digital-Circuit

本项目利用Minecraft游戏中的简单逻辑元件构建出复杂的组合和时序逻辑“电路”，不需要考虑现实中的晶体管电路所涉及到的电气特性和器件工艺等问题，通过一种直观的三维可视化方式展示一个较为纯粹的可计算模型。

![Image text](https://github.com/Alpha21016/Minecraft-Digital-Circuit/blob/master/images/adder.jpg)

在saves目录下包含三个存档

用于教学的存档Digital-Circuit-Basic，里面搭建了常用的从简单到复杂的数字电路结构，该存档适用于Minecraft-1.12版本及以上，我自己用的是1.12.2。
这个存档的元件和模块列表说明在“docs/教学存档单元和模块列表.xlsx”

我以前的大型作品Alpha21016分为两个存档，一个是最终版演示存档，一个是加减乘除计算器演示存档。
之所以分开是因为最终版的存档里为了让CPU的电路简化，四则运算计算器已经被我废弃了，所以我把很久以前刚建完四则运算计算器时的存档单独列出来。
最终版里包含CPU，特殊函数计算器，显示屏，时钟等电路结构。
这两个存档必须在1.4.7版本打开才能顺利运行，因为这个游戏版本过于古老，如果网上寻找不到可以到知乎上私信我。
如果是自行在别处下载的1.4.7游戏程序，需要额外安装能够加载更多区块的插件，因为游戏中超出视野之外的电路是不会运行的。
尽量保证加载范围能覆盖至少256x256的范围，这需要较强的CPU性能，单核性能较强的双核及以上酷睿处理器最为合适。
这个作品并没有全部完成，但是CPU已经具有完整的流水线结构。
在游戏中建造十万门以上的大规模数字电路，后期的维护和调试成本过高，因为时间和精力的原因没有将全部的指令集完成。
我使用了一个很有用的工具，叫MCEdit，可以方便快捷地编辑游戏存档中的三维结构，使得电路搭建比纯手搭节约了很多时间，下载这个工具可以去MCEdit Unified官网。
关于介绍的文档目前没有写完，日后会继续完善。



