## Cifar10图像分类任务 ##

- CIFAR-10数据集包含10小类，60,000个32*32的彩色图像。有50,000个训练图像和10,000个测试图像。
- CIFAR-100数据集包含100个小类，每小类包含600个图像，其中有500个训练图像和100个测试图像。100类被分组为20个大类。每个图像带有1个小类的"fine"标签和1个大类的"coarse"标签。

### Cifar10图像数据解析

### Cifar数据打包和数据读取

- tf.train.string_input_producer



### TensorFlow训练框架搭建

- Data
- Net
- Loss
- Summary
- Session

### TensorFlow挑战Cifar10编程案例

- 训练代码
- 测试代码
- Tensorboard调试
- 模型优化

#### 如何优化Cifar图像分类任务

- 更多的数据增强策略，比如mixup
- 更好的主干网络结构，比如SENet
- 更好的标签策略，比如Soft-label策略
- 更好的Loss设计，比如采用分类+回归smooth-l1 loss
- 不同的优化器、参数初始化方法等
