空间卷积网络分支：输入为单张图像，归一化为**224x224**，卷积网络为图像分类网络。

时间卷积网络分支：堆叠L帧连续帧构建2L输入维（光流堆叠），归一化为**224x224x2L**。

光流是在训练前预先计算的，采用opencv中计算稠密光流的方法，保存为两张JPEG图像。【需要很多存储空间】



![image-20210726103329100](#Two-Stream Networks# Two-Stream Convolutional Networks for Action Recognition in Videos-1406.2199.assets/image-20210726103329100.png)



![image-20210726105429747](#Two-Stream Networks# Two-Stream Convolutional Networks for Action Recognition in Videos-1406.2199.assets/image-20210726105429747.png)