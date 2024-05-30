# Summer Class
## 第一周  (2024.6.03 - 2024.6.09)
### 超分
#### 积分梯度与盲超分语义
积分梯度常用于神经网络解释性工作，数学推导较为简单。
##### Brief introduction of Integral Gradient  
- Axiomatic Attribution for Deep Networks (概览,可不看)
- https://zhuanlan.zhihu.com/p/468782348/ (可只看这个网站)
##### Attribution analysis on Blind Super-Resolution   
- SeD: Semantic-Aware Discriminator for Image Super-Resolution
##### Semantic Blind Super-Resolution   
- Finding Discriminative Filters for Specific Degradations in Blind Super-Resolution
### 图像分类
- 2012年：AlexNet 深度卷积神经网络的ImageNet分类
- 2014年：VGG 超深度卷积网络用于大规模图像识别
### 对比学习
- InstDist: 
    - Unsupervised Feature Learning via Non-Parametric Instance Discrimination (CVPR 2018) 
    - 利用 memory bank 来存储图像经神经网络编码后的特征。
- InvaSpread: 
    - Unsupervised Embedding Learning via Invariant and Spreading Instance Feature (CVPR 2019)
    - 没有使用额外的数据结构去存储大量的样本信息；正负样本都来自于同一个 minibatch；使用同一个编码器进行端到端的学习。

- CPC: 
    - Representation Learning with Constrastive Predictive Coding (2019)
    - 可以应用于音频、图片、强化学习；将输入当成序列，利用前面的输入通过 RNN 或 LSTM 等网络输出来进行预测。

##  第二周  (2024.6.10 - 2024.6.16)
### 超分
#### 跨领域整合的图像修复方法
##### LUTs and Image Restoration
- Toward DNN of LUTs: Learning Efficient Image Restoration with Multiple Look-Up Tables
##### Mamba and Image Restoration
- MambaIR: A Simple Baseline for Image Restoration with State-Space Model
### 图像分类
- 2014年：GoogLeNet更深卷积
### 对比学习

##  第三周 (2024.6.17 - 2024.6.23)
### 超分
#### 无监督计算机视觉
#### #Unsupervised Super resolution
- Bayesian Image Super-Resolution With Deep Modeling of Image Statistics
##### Unsupervised Deraining
- Unsupervised Deraining: Where Asymmetric Contrastive Learning Meets Self-Similarity
### 图像分类
- 2015年：Batch Normalization 批处理规范化：通过减少内部协变量偏移来加速深度网络训练
- 2015年：ResNet 深度残差学习用于图像识别

### 对比学习


## 第四周 (2024.6.24 - 2024.6.30 )
### 超分
#### 傅里叶特征
傅里叶特征是简单傅里叶变换的工程改进，此部分论文数学内容与主题关联较小，可在一定程度上忽略。
##### Brief introduction of Spectral Bias
- On the Spectral Bias of Neural Networks (概览,可不看)
##### Brief introduction of Fourier Features
- Fourier Features Let Networks Learn High Frequency Functions in Low Dimensional Domains (概览,可不看)
##### Fourier feature for continue super resolution
- Local Texture Estimator for Implicit Representation Function

### 图像分类
- 2016年：Xception深度学习与深度可分卷积
- 2017年：MobileNet用于移动视觉应用的高效卷积神经网络

### 对比学习


