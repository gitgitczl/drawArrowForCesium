# drawArrowForCesium
之前的态势标会插件（此插件地址：https://adventurexph.github.io/drawForCesium/）兼容不了cesium1.50之上，在修改态势标会箭头时会出错，导致没法修改；再后来某大神推出了兼容1.5x版本的插件（此插件地址：https://github.com/leation/DrawHelperForCesium1.5.X），但是该插件再绘制钳击箭头的时候有时会出现bug

军事标绘箭头插件，兼容cesium1.5之上版本，无bug；

操作逻辑：
绘制攻击箭头时 右键结束绘制；
若要编辑箭头，则在绘制或加载完成后点击箭头，会出现控制点，点击控制点即可移动箭头，移动完成后再点击箭头面之外的地方，即可完成编辑；
原理：
主要利用了plotUtil和algorithm这两个js来计算出面的坐标；

注意：
下载可通过火狐打开，用谷歌会报错，或者通过服务器打开；
相关csdn地址：https://blog.csdn.net/caozl1132/article/details/89679716
