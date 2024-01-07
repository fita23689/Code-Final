# 编程基础期末报告
## 项目简介
本文选取AIDS Clinical Trials Group Study 175 数据集，数据集的链接为[艾滋病临床试验小组研究 175 - UCI 机器学习存储库](https://archive.ics.uci.edu/dataset/890/aids+clinical+trials+group+study+175)，该数据集包含有关被诊断患有 AIDS 的患者的医疗保健统计数据和分类信息。该数据集最初发表于1996年。预测任务是预测每个患者是否在特定时间窗口内死亡，本文使用其探究影响患者是否在特定时间窗口内死亡的重要因素,并完成预测任务。

### 影响因素探索
使用Logit回归进行影响因素的探索，结果表示time、offtrt、cd420、race、cd820、age、strat_1、symptom、drugs、karnof、strat_2、hemo、cd40和gender

### 预测及模型比较