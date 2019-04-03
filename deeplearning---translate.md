深度学习允许由多层计算组成的计算模型去学习以数据为代表的多个抽象水平。深度学习通过后向传播算法去探索发现大型数据集的复杂的结构，从而表明一个机器应该如何改变它的内部参数（内部参数通常被用于从之前层的表达式来计算每一层的表达式）***（相当于内部参数+上一层的输出影响这一层的表示法）***

深度卷积网络--------处理图像，声音，演讲和音频

循环网络---------顺序数据     文章和演讲

Machine Learning  includes deep learning.

特征学习是一种给机器灌入原始数据，然后机器自动发现需要进行检测和分类的表达式。

deep learning是特征学习。将原始数据通过简单但非线性的模型转变为更高层次，更加抽象的表达。不断的转变。

deep learning 核心通用的学习过程从数据中学到各层的特征

## Supervise d   learning

supervised learning利用已知类别的样本（关键是**训练数据有标签**），设置目标函数（例实际输出与期望输出距离最小），通过调整内部参数，来让目标函数达到最优。

主要有两类:

1.回归（连续）：已知样本点找一条最优曲线

![1554191659451](C:\Users\22986\AppData\Roaming\Typora\typora-user-images\1554191659451.png)

2：分类（离散型）：

![1554191703093](C:\Users\22986\AppData\Roaming\Typora\typora-user-images\1554191703093.png)

### 梯度下降：

![1554195087611](C:\Users\22986\AppData\Roaming\Typora\typora-user-images\1554195087611.png)

![1554194973258](C:\Users\22986\AppData\Roaming\Typora\typora-user-images\1554194973258.png)

其中α为步长，理解时以二维图像理解较为简单。权值减去步长与梯度的积。然后带入loss函数中。得到loss的最优值。

另一种理解：![1554195984763](C:\Users\22986\AppData\Roaming\Typora\typora-user-images\1554195984763.png)就是权值。BGD（求和）和SGD（随机求一个样本）的公式都是展开的![1554195881549](C:\Users\22986\AppData\Roaming\Typora\typora-user-images\1554195881549.png)

![1554195900109](C:\Users\22986\AppData\Roaming\Typora\typora-user-images\1554195900109.png)