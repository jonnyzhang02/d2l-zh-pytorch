<!--
 * @Author       : JonnyZhang 71881972+jonnyzhang02@users.noreply.github.com
 * @LastEditTime : 2023-07-24 11:31
 * @FilePath     : \d2l-zh-pytorch\README.md
 * 
 * coded by ZhangYang@BUPT, my email is zhangynag0207@bupt.edu.cn
-->
# Dive into Deep Learning

## [chapter_preliminaries](./chapter_preliminaries/linear-algebra.ipynb)

## [chapter_linear-networks-线性回归](./chapter_linear-networks/.md)

7.19 完成

## [chapter_multilayer-perceptrons-感知机](./chapter_multilayer-perceptrons/.md/)

- [感知机](./chapter_multilayer-perceptrons/.md#%E6%84%9F%E7%9F%A5%E6%9C%BA)
    - [多层感知机从零开始实现](./chapter_multilayer-perceptrons/.md#%E5%A4%9A%E5%B1%82%E6%84%9F%E7%9F%A5%E6%9C%BA%E4%BB%8E%E9%9B%B6%E5%BC%80%E5%A7%8B%E5%AE%9E%E7%8E%B0)
    - [多层感知机简洁实现](./chapter_multilayer-perceptrons/.md#%E5%A4%9A%E5%B1%82%E6%84%9F%E7%9F%A5%E6%9C%BA%E7%AE%80%E6%B4%81%E5%AE%9E%E7%8E%B0)
    - [模型选择](./chapter_multilayer-perceptrons/.md#%E6%A8%A1%E5%9E%8B%E9%80%89%E6%8B%A9)
        - [K折交叉验证](./chapter_multilayer-perceptrons/.md#k%E6%8A%98%E4%BA%A4%E5%8F%89%E9%AA%8C%E8%AF%81)
    - [欠拟合和过拟合](./chapter_multilayer-perceptrons/.md#%E6%AC%A0%E6%8B%9F%E5%90%88%E5%92%8C%E8%BF%87%E6%8B%9F%E5%90%88)
    - [正则化方法](./chapter_multilayer-perceptrons/.md#%E6%AD%A3%E5%88%99%E5%8C%96%E6%96%B9%E6%B3%95)
        - [权重衰退](./chapter_multilayer-perceptrons/.md#%E6%9D%83%E9%87%8D%E8%A1%B0%E9%80%80)
            - [L1正则化](./chapter_multilayer-perceptrons/.md#l1%E6%AD%A3%E5%88%99%E5%8C%96)
            - [L2正则化](./chapter_multilayer-perceptrons/.md#l2%E6%AD%A3%E5%88%99%E5%8C%96)
        - [丢弃法](./chapter_multilayer-perceptrons/.md#%E4%B8%A2%E5%BC%83%E6%B3%95)
    - [数值稳定性和模型初始化](./chapter_multilayer-perceptrons/.md#%E6%95%B0%E5%80%BC%E7%A8%B3%E5%AE%9A%E6%80%A7%E5%92%8C%E6%A8%A1%E5%9E%8B%E5%88%9D%E5%A7%8B%E5%8C%96)
        - [数值稳定性](./chapter_multilayer-perceptrons/.md#%E6%95%B0%E5%80%BC%E7%A8%B3%E5%AE%9A%E6%80%A7)
        - [模型初始化和激活函数提高数值稳定性](./chapter_multilayer-perceptrons/.md#%E6%A8%A1%E5%9E%8B%E5%88%9D%E5%A7%8B%E5%8C%96%E5%92%8C%E6%BF%80%E6%B4%BB%E5%87%BD%E6%95%B0%E6%8F%90%E9%AB%98%E6%95%B0%E5%80%BC%E7%A8%B3%E5%AE%9A%E6%80%A7)
            - [权重初始化](./chapter_multilayer-perceptrons/.md#%E6%9D%83%E9%87%8D%E5%88%9D%E5%A7%8B%E5%8C%96)
            - [激活函数](./chapter_multilayer-perceptrons/.md#%E6%BF%80%E6%B4%BB%E5%87%BD%E6%95%B0)
    - [Kaggle房价预测](./chapter_multilayer-perceptrons/.md#kaggle%E6%88%BF%E4%BB%B7%E9%A2%84%E6%B5%8B)

7.23 完成

## [chapter_deep-learning-computation-深度学习计算](./chapter_deep-learning-computation/.md)

- [深度学习计算](./chapter_deep-learning-computation/.md#%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E8%AE%A1%E7%AE%97)
    - [模型构造](./chapter_deep-learning-computation/.md#%E6%A8%A1%E5%9E%8B%E6%9E%84%E9%80%A0)
    - [参数管理](./chapter_deep-learning-computation/.md#%E5%8F%82%E6%95%B0%E7%AE%A1%E7%90%86)
    - [自定义层](./chapter_deep-learning-computation/.md#%E8%87%AA%E5%AE%9A%E4%B9%89%E5%B1%82)
    - [读写文件](./chapter_deep-learning-computation/.md#%E8%AF%BB%E5%86%99%E6%96%87%E4%BB%B6)
    - [使用和购买GPU](./chapter_deep-learning-computation/.md#%E4%BD%BF%E7%94%A8%E5%92%8C%E8%B4%AD%E4%B9%B0gpu)

7.23 完成

## [chapter_convolutional-neural-networks-卷积神经网络](./chapter_convolutional-neural-networks/.md)  

- [卷积神经网络](./chapter_convolutional-neural-networks/.md#%E5%8D%B7%E7%A7%AF%E7%A5%9E%E7%BB%8F%E7%BD%91%E7%BB%9C)
    - [从全连接神经网络到卷积神经网络](./chapter_convolutional-neural-networks/.md#%E4%BB%8E%E5%85%A8%E8%BF%9E%E6%8E%A5%E7%A5%9E%E7%BB%8F%E7%BD%91%E7%BB%9C%E5%88%B0%E5%8D%B7%E7%A7%AF%E7%A5%9E%E7%BB%8F%E7%BD%91%E7%BB%9C)
        - [四维的全连接层](./chapter_convolutional-neural-networks/.md#%E5%9B%9B%E7%BB%B4%E7%9A%84%E5%85%A8%E8%BF%9E%E6%8E%A5%E5%B1%82)
        - [关于平移不变性](./chapter_convolutional-neural-networks/.md#%E5%85%B3%E4%BA%8E%E5%B9%B3%E7%A7%BB%E4%B8%8D%E5%8F%98%E6%80%A7)
        - [局部性](./chapter_convolutional-neural-networks/.md#%E5%B1%80%E9%83%A8%E6%80%A7)
    - [卷积层](./chapter_convolutional-neural-networks/.md#%E5%8D%B7%E7%A7%AF%E5%B1%82)
        - [卷积层代码](./chapter_convolutional-neural-networks/.md#%E5%8D%B7%E7%A7%AF%E5%B1%82%E4%BB%A3%E7%A0%81)
    - [卷积层的填充和步幅](./chapter_convolutional-neural-networks/.md#%E5%8D%B7%E7%A7%AF%E5%B1%82%E7%9A%84%E5%A1%AB%E5%85%85%E5%92%8C%E6%AD%A5%E5%B9%85)
        - [填充（padding）](./chapter_convolutional-neural-networks/.md#%E5%A1%AB%E5%85%85padding)
        - [步幅（stride）](./chapter_convolutional-neural-networks/.md#%E6%AD%A5%E5%B9%85stride)
        - [padding代码](./chapter_convolutional-neural-networks/.md#padding%E4%BB%A3%E7%A0%81)
    - [多个输入和输出通道](./chapter_convolutional-neural-networks/.md#%E5%A4%9A%E4%B8%AA%E8%BE%93%E5%85%A5%E5%92%8C%E8%BE%93%E5%87%BA%E9%80%9A%E9%81%93)
        - [多个输入通道](./chapter_convolutional-neural-networks/.md#%E5%A4%9A%E4%B8%AA%E8%BE%93%E5%85%A5%E9%80%9A%E9%81%93)
        - [多个输出通道](./chapter_convolutional-neural-networks/.md#%E5%A4%9A%E4%B8%AA%E8%BE%93%E5%87%BA%E9%80%9A%E9%81%93)
        - [*1卷积核](./chapter_convolutional-neural-networks/.md#1%E5%8D%B7%E7%A7%AF%E6%A0%B8)
        - [总结](./chapter_convolutional-neural-networks/.md#%E6%80%BB%E7%BB%93)
        - [多通道代码](./chapter_convolutional-neural-networks/.md#%E5%A4%9A%E9%80%9A%E9%81%93%E4%BB%A3%E7%A0%81)
    - [池化层](./chapter_convolutional-neural-networks/.md#%E6%B1%A0%E5%8C%96%E5%B1%82)
        - [二维最大池化](./chapter_convolutional-neural-networks/.md#%E4%BA%8C%E7%BB%B4%E6%9C%80%E5%A4%A7%E6%B1%A0%E5%8C%96)
        - [平均池化](./chapter_convolutional-neural-networks/.md#%E5%B9%B3%E5%9D%87%E6%B1%A0%E5%8C%96)
        - [pooling代码](./chapter_convolutional-neural-networks/.md#pooling%E4%BB%A3%E7%A0%81)
    - [LeNet](./chapter_convolutional-neural-networks/.md#lenet)
        - [LeNet代码](./chapter_convolutional-neural-networks/.md#lenet%E4%BB%A3%E7%A0%81)





