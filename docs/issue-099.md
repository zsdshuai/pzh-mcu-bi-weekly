# 痞子衡嵌入式半月刊： 第 99 期

![](https://raw.githubusercontent.com/JayHeng/pzh-mcu-bi-weekly/master/pics/pzh_mcu_bi_weekly.PNG)

这里分享嵌入式领域有用有趣的项目/工具以及一些热点新闻，农历年分二十四节气，希望在每个交节之日准时发布一期。

本期刊是开源项目（GitHub: [JayHeng/pzh-mcu-bi-weekly](https://github.com/JayHeng/pzh-mcu-bi-weekly)），欢迎提交 issue，投稿或推荐你知道的嵌入式那些事儿。

**上期回顾** ：[《痞子衡嵌入式半月刊： 第 98 期》](https://www.cnblogs.com/henjay724/p/18162722)

## 唠两句

历史上的今天：1908年5月1日，中国工人阶级第一次纪念“五一国际劳动节”。

本期共收录 4 个项目、1 个工具，希望对你有帮助！

## 项目类

### <font color="red">1、Terathon-Math-Library - 用于2D/3D/4D矢量及矩阵的C++数学库</font>

这是一个用于2D/3D/4D矢量，矩阵，四元数和几何代数的 C++ 数学库。作者主要是做游戏引擎和计算机图形开发，大家有需要做一些稍复杂图形绘制可以试试这个库，作者尤其在文档方面花了很多心思。  

 * 项目地址：https://github.com/EricLengyel/Terathon-Math-Library

### <font color="red">2、Wheelbot - 一辆对称的反作用轮独轮车</font>

Wheelbot 是一辆对称的反作用轮独轮车，可以从任何初始位置跳上车轮。车轮机器人具有非完整和欠驱动的动力学特性，以及两个耦合的不稳定自由度，为非线性和数据驱动控制研究提供了一个具有挑战性的平台。项目文档介绍了 Wheelbot 的机械和电气设计，其估计和控制算法，以及初步的实验，以证明在平衡时自立和抗干扰。  

 * 项目地址：https://github.com/AndReGeist/wheelbot-v2.5

 ![](https://raw.githubusercontent.com/JayHeng/pzh-mcu-bi-weekly/master/pics/issue-099/Wheelbot.PNG)

 ### <font color="red">3、Intelligent Cooling Plate - 一个基于MCU的智能冷却板设计</font>

这是一个 Microchip 推出的智能冷却板(cold plate)参考设计，主控基于 PIC16F17146，可以冷却其金属表面和上面的任何东西。该系统由单个20针8位微控制器(MCU)控制，具有温度测量、电流监测、用户界面控制和安全功能。由于其广泛的核心独立外设(cip)阵列，MCU可以单独处理此任务。

 * 项目地址：https://github.com/microchip-pic-avr-examples/pic16f17146-cold-plate-mplab-mcc

 ![](https://raw.githubusercontent.com/JayHeng/pzh-mcu-bi-weekly/master/pics/issue-099/IntelligentCoolingPlate.PNG)

  ### <font color="red">4、studio_mic - 一个简单易于构建的电容麦克风</font>

这是一个高质量的麦克风项目，麦克风构建使用克隆RK12/CK12胶囊，U87麦克风和定制前置放大器板。该板非常简单，但高性能 - 它在单个封装中使用双 FET 输入运放来转换胶囊的阻抗并提供差分信号，而偏置则由六角施密特触发逆变器电荷泵提供。由于电路的简单性和所选运放的性能、充足的动态范围和无信号失真，几乎没有自噪声。  

 * 项目地址：https://github.com/Spirit532/studio_mic

 ![](https://raw.githubusercontent.com/JayHeng/pzh-mcu-bi-weekly/master/pics/issue-099/studio_mic.PNG)

 ## 工具类

 ### <font color="red">1、Quick Connect Studio - 基于云的瑞萨嵌入式系统设计平台</font>

Quick-Connect Studio 是一个基于云的在线设计平台，用户能够以图形方式构建硬件和软件，以快速验证原型并加速产品开发。 借助快速连接工作室，工程师可以直观地将设备和子系统块拖放到云上以构建其解决方案。 该平台自动生成、编译和构建软件，以实现无代码开发。 用户可以在云中构建完整的解决方案，并在不到 10 分钟的时间内快速部署到硬件。

 * 软件地址：https://www.renesas.cn/cn/zh/software-tool/quick-connect-studio

Quick Connect Studio 目前支持所有瑞萨RA MCU板以及多种瑞萨无线模块和传感器。不仅如此，其还纳入了艾迈斯欧司朗（ams OSRAM）、TDK和Arducam等合作伙伴的产品，进一步扩大了所支持的应用与设计范围。Quick Connect Studio现已能够帮助用户借助瑞萨MCU和分立板卡构建超过350个系统。

 ![](https://raw.githubusercontent.com/JayHeng/pzh-mcu-bi-weekly/master/pics/issue-099/QuickConnectStudio.PNG)

### 欢迎订阅

文章会同时发布到我的 [博客园主页](https://www.cnblogs.com/henjay724/)、[CSDN主页](https://blog.csdn.net/henjay724)、[知乎主页](https://www.zhihu.com/people/henjay724)、[微信公众号](http://weixin.sogou.com/weixin?type=1&query=痞子衡嵌入式) 平台上。

微信搜索"__痞子衡嵌入式__"或者扫描下面二维码，就可以在手机上第一时间看了哦。

![](https://raw.githubusercontent.com/JayHeng/pzhmcu-picture/master/wechat/pzhMcu_qrcode_258x258.jpg)

