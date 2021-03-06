# 交流流量预测应用方案收集(欢迎补充、持续更新...)

* 基于时间图卷积网络(T-GCN)交通流预测（A Temporal Graph Convolutional Network for Trafﬁc Prediction
） 2019IEEE
> * 一种基于神经网络的交通预测方法，该模型结合了图卷积网络(GCN)和门控递归单元(GRU)。GCN用于学习复杂的拓扑结构来捕获空间依赖关系，GRU用于学习交通数据的动态变化来捕获时间依赖关系。
> * [论文下载链接](https://arxiv.org/abs/1811.05320?context=stat.ML)
> * [实现链接tf](https://github.com/lehaifeng/T-GCN)

* 基于时空图卷积网络(STGCN)交通流预测(Spatio-TemporalGraphConvolutionalNetworks: ADeepLearningFramework forTrafﬁcForecasting) 2018IJCAI
> * 一种新的深度学习结构，时空图卷积网络,由多个时空卷积块组成，时空卷积块由图卷积层和卷积序列学习层组合而成,对时空依赖关系进行建模
> * [论文下载链接](https://arxiv.org/abs/1709.04875v4)
> * [实现链接tf](https://github.com/VeritasYin/STGCN_IJCAI-18)

* 基于注意力机制的时空图卷积网络(ASTGCN)交通流预测(AttentionBasedSpatial-TemporalGraphConvolutionalNetworks forTrafﬁcFlowForecasting) 2019AAAI
> * ASTGCN主要由三个独立部分组成，分别对交通流的三个时间特性进行建模，即邻近、每日和每周的依赖关系。其中每个独立部分又包含两部分:1)时空注意力机制，有效地捕捉交通数据中的动态时空关联; 2)时空卷积，即同时使用图卷积来捕捉空间模式和常用的标准卷积来描述时间特征。对三个分量的输出进行加权融合，生成最终预测结果
> * [论文下载链接](https://github.com/Davidham3/ASTGCN/blob/master/papers)
> * [实现链接tf](https://github.com/guoshnBJTU/ASTGCN)
> * [实现链接pytorch](https://github.com/jianpingbadao/ASTGCN-PyTorch)

* 基于时空动态网络(STDN)的交通流预测(RevisitingSpatial-TemporalSimilarity:ADeepLearningFramework forTrafﬁcPrediction) 2019AAAI
> * 为解决区域间的空间依赖是动态的，时间依赖虽说有天和周的模式，但因为有动态时间平移，它不是严格周期的。为了解决这两个问题，本文提出基于时空神经网络的，使用局部 CNN 和 LSTM 分别处理时空信息。一个门控局部 CNN 使用区域间的动态相似性对空间依赖建模。一个周期平移的注意力机制用来学习长期周期依赖。通过注意力机制对长期周期信息和时间平移建模
> * [论文下载链接](http://export.arxiv.org/abs/1803.01254)
> * [实现链接tf](https://github.com/tangxianfeng/STDN)

* 基于时空多任务学习框架(MDL)的区域交通流量预测与流向预测(Flow Prediction in Spatio-Temporal Networks Based on Multitask Deep Learning)  2019TKDE
> * 设计了一个深度神经网络来预测顶点流量（命名为 NODENET），另一个深度神经网络预测边流量（命名为 EDGENET）。通过将他们的隐藏状态拼接来连接这两个深度神经网络，并一同训练。此外，这两类流量的相关性通过损失函数中的正则项来建模。基于深度学习的模型可以处理复杂性和尺度等问题，同时多任务框架增强了每类流量的预测性能
> * [论文下载链接](https://ieeexplore.ieee.org/document/8606218)
> * 暂无实现

* 
> * 基于扩散卷积循环神经网络(DCRNN)的交通流预测(DIFFUSION CONVOLUTIONAL RECURRENT NEURAL NETWORK: DATA-DRIVEN TRAFFIC FORECASTING
) 2018ICLR
> * 将交通流建模为有向图上的扩散过程，并引入扩散卷积递归神经网络（DCRNN）,DCRNN使用图上的双向随机游走捕获空间依赖性，以及使用具有调度采样的编码器 - 解码器架构的时间依赖性
> * [论文下载链接](https://arxiv.org/abs/1707.01926)
> * [实现链接tf](https://github.com/liyaguang/DCRNN)
> * [实现链接pytorch](https://github.com/chnsh/DCRNN_PyTorch)

* 基于Conv-LSTM交通流预测(Short-term traffic flow prediction with Conv-LSTM)
> * 利用ConvLSTM模块对相邻区域的短时交通流数据进行处理，提取时空特征;利用双向LSTM对预测点历史交通数据进行处理，提取交通流数据的周期特征。提出了一种无需数据预处理和数据特征提取的端到端深度学习短时交通流预测体系结构。最后，集中时空特征和周期特征对交通流进行预测
> * [论文下载链接](https://ieeexplore.ieee.org/document/8171119)
