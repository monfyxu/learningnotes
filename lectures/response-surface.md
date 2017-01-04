# Response Surface 二次响应面

2015/6/10

处理成对概念中一者对另一者的效应，如：父子、母子、来访者咨询师
基于双方互评的差异，用其进行预测

### 建立回归模型
Z= b0 + b1X + b2Y + b3X2 + b4XY + b5Y2 + e

### 斜率、曲率
**固定点**（最值点or鞍点）当X=Y=Z  --> 分析斜率

**主轴：**在经过固定点的所有切面中，曲率最大的是第一主轴，最小的（负值）是第二主轴

**目标线：**X = Y（一致线）, X = -Y（相反线）

分析目标线的斜率（一次项系数）和曲率（二次项系数）

### 适用前提
匹配变量概念相同，测量尺度相同
回归分析的所有前提

### 步骤
1. 中心化（减去度量中心）
3. 回归分析：逐步回归，先放一次项，再放高次项 （ΔR方要显著/高次项至少要有一个显著）

