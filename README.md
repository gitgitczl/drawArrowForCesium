# drawArrowForCesium
之前的态势标会插件（此插件地址：https://adventurexph.github.io/drawForCesium/）
兼容不了cesium1.50之上，在修改态势标会箭头时会出错，导致没法修改；
再后来某大神推出了兼容1.5x版本的插件（此插件地址：https://github.com/leation/DrawHelperForCesium1.5.X），
但是该插件再绘制钳击箭头的时候有时会出现bug
后抽时间重写了此军事标绘箭头插件，兼容cesium1.5之上版本，无bug，后续会完善绘制的种类；
操作逻辑：
绘制攻击箭头时 右键结束绘制；
若要编辑箭头，则在绘制或加载完成后点击箭头，会出现控制点，点击控制点即可移动箭头，移动完成后再点击箭头面之外的地方，即可完成编辑；
原理：
主要利用了plotUtil和algorithm这两个js来计算出面的坐标；

注意：通过web容器打开，例如iis发布、vscode live server启动、hbuilder启动。
下面是本人新写的军标效果（共有十种），相比较上个基于plotUtil和algorithm写的军标：
1、实现了更多种标绘的兼容
2、实现类的统一管理
3、更友好的绘制
###
![Image](https://github.com/gitgitczl/drawArrowForCesium/blob/master/img/2.jpg)
更多效果可关注本人csdn https://blog.csdn.net/caozl1132 或者 关注本人qq 951973194

