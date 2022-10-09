# [PlantPre](https://github.com/scut-bds/PlantPre)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-red.svg)](#python)  [![GitHub stars](https://img.shields.io/github/stars/scut-bds/PlantPre)](https://github.com/scut-bds/PlantPre/stargazers) [![GitHub license](https://img.shields.io/github/license/scut-bds/PlantPre)](https://github.com/scut-bds/PlantPre/blob/main/LICENSE) ![GitHub repo size](https://img.shields.io/github/repo-size/scut-bds/PlantPre) [![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black) ![GitHub last commit](https://img.shields.io/github/last-commit/scut-bds/PlantPre)     

README: [English](https://github.com/scut-bds/PlantPre/blob/main/README.md) | [中文](https://github.com/scut-bds/PlantPre/blob/main/README-zh.md)      

**使用可穿戴足底评估老年人跌倒风险的数据集**        




## 简介
跌倒是老年人受伤死亡的主要原因。日常生活中的跌倒风险评估可以防止老年人跌倒。基于可穿戴设备建立评估老年人跌倒风险的数据集已成为一个热门的研究课题，相关数据处理方法（如特征工程/深度学习）取得了良好的性能。然而，这些数据集不能用于日常生活空间，因为它们的数据采集设备穿戴不舒适或过于昂贵。因此，基于这些数据集的相关数据处理方法不能应用于日常生活中的真实场景，其实用能力有限。为了使日常跌倒风险评估成为可能，我们提出了一种新的方法来构建48名老年人的连续足底压力数据集，以及每个老年人的跌倒风险标签（他们的伯格量表分数）。我们的数据集是通过适合日常生活空间的足底压力监测鞋收集的。此外，我们将Conv LSTM算法应用于我们的数据集，分类结果达到92%，这证明它是一个适合于生物医学关系提取的数据集。我们的数据集有助于老年人的平衡评估和健康监测。我们鼓励其他研究人员在我们的数据集上测试他们自己的坠落风险评估方法。
