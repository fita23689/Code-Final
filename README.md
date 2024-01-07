# 编程基础期末报告
## 项目简介
本项目选取AIDS Clinical Trials Group Study 175 数据集，数据集的链接为[艾滋病临床试验小组研究 175 - UCI 机器学习存储库](https://archive.ics.uci.edu/dataset/890/aids+clinical+trials+group+study+175)，该数据集包含有关被诊断患有 AIDS 的患者的医疗保健统计数据和分类信息。该数据集最初发表于1996年。任务是预测每个患者是否在特定时间窗口内死亡，本项目使用其探究影响患者是否在特定时间窗口内死亡的重要因素,并完成预测任务。

### 影响因素探索
使用Logit回归进行影响因素的探索，结果表示time、offtrt、cd420、race、cd820、age、strat_1、symptom、drugs、karnof、strat_2、hemo、cd40和gender等因素通过T检验，对患者是否在特定时间窗口内死亡有显著影响，详情见文章。

### 预测及模型比较
在预测任务阶段，主要使用DNN进行预测，兼于传统机器学习包括Logit回归、决策树、支持向量机、朴素贝叶斯以及K近邻等模型进行对比，结果见文章。

## 复现说明

### 运行环境
Colab：https://colab.research.google.com/

除了引入数据集所需要的包ucimlrepo，其他包都是Colab自带

### 复现说明
ipynb中已有相关注释，随机种子也统一设定为42，直接从头运行到最后即可
