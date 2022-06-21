单变量线性回归Linear Regression with One Variable
表达方式为:，因为只含有一个特征/输入变量，因此这样的问题叫作单变量线性回归问题。 
代价函数Cost Function（平方误差函数）
使它最小，学习参数theta
梯度下降
来求解代价函数的最小值
思路：开始随机theta，计算cost，再寻找下一个能让cost变小的theta，直到得到局部最小值

alpha：学习率。太小：很慢到达全局最优点；太大：越过最低点难以收敛
theta[0]和[1]和同步更新
