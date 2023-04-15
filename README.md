# Deep-Learning-Wide-Residual-Networks
This is the first assignment of the course named *Deep Learning* in scope of the PhD studies.

It has been observed that swallow neural networks need exponentially more parameters to achieve comparable performance to the deep networks. This is the rationale behind the creation of the deep residual networks, to make them as thin and long as possible. However, a study introduces the concept of [Wide Residual Networks](https://arxiv.org/abs/1605.07146) (a.k.a WRS), which claim to have better performance on some tasks compared to classic ResNets, with similar capacity (number of parameters) but with less training time required.

The goal of the asssignment is to reproduce some of the experiments conducted in the paper, to use the [MixUp](https://arxiv.org/abs/1710.09412) data augmentation technique and study the effect of the Drop Out on the performance of the WRS. To perform all of those tasks, we use the [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) dataset.
