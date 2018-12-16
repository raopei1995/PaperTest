# Dataset

# FPN
**paper:**[Feature Pyramid Networks for Object Detection](https://arxiv.org/abs/1612.03144)`CVPR2017`

## Abstract
特征金字塔是识别系统中用于检测不同尺度目标的基本组件。最近的深度学习目标检测器已经避免了金字塔表示，部分原因是它们是计算和内存密集型的。在本文中，利用深度卷积网络内在的多尺度、金字塔分级来构造具有很少额外成本的特征金字塔。开发了一种具有横向连接的自顶向下架构(A top-down architecture with lateral connections)，用于在所有尺度上构建高级语义特征映射。这种称为特征金字塔网络（FPN）的架构在应用中作为通用特征提取器表现出了显著的改进。在一个基本的Faster R-CNN系统中使用FPN，该方法可以在COCO检测基准数据集上取得最先进的单模型结果，结果超过了所有现有的单模型输入，包括COCO 2016挑战赛的获奖者。此外，该方法可以在GPU上以6FPS运行，因此是多尺度目标检测的实用和准确的解决方案。

我们在做目标检测和超分辨率重建等问题的时候，我们一般是对同一个尺寸的图片进行网络训练。我们希望我们的网络能够适应更多尺寸的图片，我们传统的做法使用图像金字塔，但是这种做法从侧面提升了计算的复杂度，我们希望可以改善这个问题，所以本文就提出了一种在特征图金字塔的方法，我们称这种网络结构叫做FPN。

## Contribution
- list one
- list two
## Result

![network]ima/7CQPBNNA29GGIFV2B2J0.png
