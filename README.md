该项目通过从零实现K-Means聚类算法，对2024年6月大曼彻斯特地区的Airbnb房源数据进行全面分析。项目旨在探究房源的地理分布、价格分层和房型差异，进而为市场定位和定价策略提供数据支持。

项目亮点:

自研聚类算法

完全手写K-Means算法，实现了欧氏距离计算、随机质心初始化、迭代更新与收敛判断，未依赖外部机器学习库。

多维数据分析

构建了三种聚类模型：

模型1：基于纬度和经度揭示地理分布。
模型2：引入价格维度，区分经济型与高端房源。
模型3：结合房型信息，识别不同住宿类型的空间分布。

数据预处理与可视化

对原始数据进行清洗、特征工程和异常值处理，确保聚类输入数据质量。
利用可视化图表（如散点图、箱线图等）直观展示各模型聚类结果及市场细分信息。
