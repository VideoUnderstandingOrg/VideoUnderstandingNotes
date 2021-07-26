

https://github.com/yjxiong/temporal-segment-networks



主要思想：将视频分成K段，从每段中随机抽取一帧，然后将得到的K帧图像输入到CNN中进行分类。

实现：

- 只有RGB图像

- two-stream模型，RGB+光流



![image-20210720172639814](#TSN# Temporal Segment Networks Towards Good Practices for Deep Action Recognition-1608.00859.assets/image-20210720172639814.png)

