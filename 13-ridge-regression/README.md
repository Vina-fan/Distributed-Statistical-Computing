# 实例分析：利用MapReduce计算岭回归模型系数


## 准备知识

* Ridge Regression
* R
* Mapreduce







参照岭回归系数的计算公式，比较好的解决方案是先利用并行计算出维度较高、计算量较大的矩阵和，在最后汇总时再考虑λ引起的收缩并计算出β。

	#! /usr/bin/env Rscript


	#! /usr/bin/env Rscript

### 汇总部分
（感谢中央财经大学刘利恒提供素材和案例。）