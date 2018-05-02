# 实时行为识别系统

编程语言：Python3

主要用到的工具包或库：OpenCV, Keras, TensorFlow, PyQt等。


## 数据集

本来数据集拟采用的是谷歌最新的AVA行为识别数据集。后来仔细看了AVA数据集的情况，发现该数据集不适合。

因此我们采取自建数据集。自建数据集使用的程序是[dataset maker](https://github.com/TianzhongSong/Dataset-maker-for-action-recognition)。


### UI界面构建

初步界面布局 [uiTest.py](https://github.com/TianzhongSong/Real-time-action-recognition-system/blob/master/ui/uiTest.py)

![](https://github.com/TianzhongSong/Action-Recognition-Research/blob/master/files/pose.gif)

### Todo

1.尝试将人体分割加入

2.尝试其他模型，不局限于普通CNN、3DCNN

3.采集更多数据，在允许条件下公开数据

4.进一步优化
