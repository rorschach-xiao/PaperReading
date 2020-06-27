论文名称：《DCNAS: Densely Connected Neural Architecture Search for Semantic Image Segmentation》

论文地址：https://arxiv.org/pdf/2003.11883v1.pdf

神经网络架构搜索（NAS）已经在密集图像预测的自动网络架构设计上展现了很大的潜力，然而现有的NAS算法常在限制的搜索空间上妥协，并在代理任务(proxy task)进行搜索以保证可实现的计算需求。为了保证网络架构尽可能广并避免目标任务和代理任务之间的差距，本文提出了密度连接NAS框架，直接通过目标数据集上多尺度的视觉信息的表达来搜索最优的网络结构。特别地，通过可学习的权重连接细胞，本文提出了密度连接搜索空间来代替大量主流的网络结构设计。此外，通过融合path-level和channel-level的采样策略，本文设计了一个融合模块来减少主要搜索空间上的内存消耗。本文提出的DCNAS在多个公开的数据集如Cityscapes,Pascal VOC2012上都达到了sota的表现。

- #### 本文的主要贡献：

1. 本文设计了首个完整的密度连接的搜索空间，允许探索多种现有的网络设计，并能覆盖随机的模型结构模式。
2. 本文实现了首个proxyless的搜索范式，从编码在DCNAS的模型中搜索到最适合大分割数据集的模型。
3. 在Cityscapes,Pascal VOC2012,Pascal Context和ADE20K数据集上达到了sota效果。

