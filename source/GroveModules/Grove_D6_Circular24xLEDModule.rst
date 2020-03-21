.. _Grove_D6_Circular24xLEDModule:

============================
环形LED阵列模块(x24颗)
============================

我们先来看看使用环形LED阵列模块实现的有趣效果

.. image:: ../_static/images/GroveModules/Grove_D6_Circular24xLEDModule/CircularLEDModule_0.gif
    :align: center 

如何实现这个效果的程序源码，后面的章节中会给出，并分析实现的思路。
实现这个有趣效果的主角是，环形LED阵列模块(x24颗)。这个模块由24颗亮度可单独调节的LED及其控制接口电路单元组成，且24颗
LED呈环形排列，相当于手表上小时刻度的每隔半小时一颗。准确地说，每隔15度一颗LED，24颗LED正好排布在一个圆上。

.. image:: ../_static/images/GroveModules/Grove_D6_Circular24xLEDModule/CircularLEDModule_1.jpg
    :align: center 


环形LED阵列模块的技术参数
=====================

==========  ==========
LED颜色      绿、红、蓝三色间隔排列
LED规格      2.0x0.8mm
LED总数      24颗
亮度分级      8级
亮度调节      PWM方式
刷新时间      小于1ms/次
电气接口      Grove
接口逻辑      3.3V/5V
供电电压      3～5V
供电电流      100%亮度时最大35mA
外型尺寸      外径45mm,内方孔22x22mm,圆角半径2.54mm
重量         5g
==========  ==========


环形LED阵列模块的用法
=============

环形LED阵列模块的电气接口采用一对4线(2mm间距)的Grove接口，4个引脚的名称和功能如下：

========  ========  ========
1         Gnd       电源地线
2         Vdd       电源正极
3         SDin      串行数据输入
4         SKin      与串行数据同步的时钟信号输入
========  ========  ========




