
# 项目描述

这个项目是kaggle竞赛中的一个恶毒评论分类问题，旨在对于网络评论区的恶意评论进行区分和鉴别。


链接：https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/overview

# 数据集

该项目的数据集是来自与kaggle端，并且分为train和test两个数据集，train作为训练集，test作为需要预测的测试集。

# 项目环境

在该项目中我使用的是**Anaconda**所搭建的环境，并且在使用了一下几种库:

**keras**,**sklearn**,

**matplotlib.pyplot**,

**pandas**,**numpy**

# 项目流程

1. 数据导入 
2. 数据如处理
  1. 词袋模型
      1. tf-idf
  2. 词向量模型
      1. 分词
      2. 去停词
3. 训练模型
4. 模型评估
