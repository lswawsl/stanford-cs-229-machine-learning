<a name="jI6U4"></a>
# 单变量线性回归Linear Regression with One Variable
表达方式为:![image.png](https://cdn.nlark.com/yuque/0/2022/png/25360752/1655197684682-671e0407-c910-492c-a853-06182b4fe0d9.png#clientId=u06a867c8-8106-4&from=paste&height=23&id=u45b139cf&margin=%5Bobject%20Object%5D&name=image.png&originHeight=23&originWidth=110&originalType=binary&ratio=1&size=5003&status=done&style=none&taskId=uf41772e5-cf6c-41e7-afdd-eef96d555f4&width=110)，因为只含有一个特征/输入变量，因此这样的问题叫作单变量线性回归问题。 
<a name="tibPG"></a>
## 代价函数Cost Function（平方误差函数）
![image.png](https://cdn.nlark.com/yuque/0/2022/png/25360752/1655198927445-88d1a49b-8421-46c3-b7d5-d83610b0c456.png#clientId=u06a867c8-8106-4&from=paste&height=39&id=u415bae35&margin=%5Bobject%20Object%5D&name=image.png&originHeight=39&originWidth=280&originalType=binary&ratio=1&size=8288&status=done&style=none&taskId=u5d8b2f6d-88c9-4200-b3b9-657bc6f1662&width=280)使它最小，学习参数theta
<a name="wPVg1"></a>
## 梯度下降
来求解代价函数的最小值<br />思路：开始随机theta，计算cost，再寻找下一个能让cost变小的theta，直到得到局部最小值<br />![image.png](https://cdn.nlark.com/yuque/0/2022/png/25360752/1655207756329-6199cde1-4568-4b95-9793-d8ca7ebf296b.png#clientId=u06a867c8-8106-4&from=paste&height=127&id=u86a16155&margin=%5Bobject%20Object%5D&name=image.png&originHeight=127&originWidth=503&originalType=binary&ratio=1&size=24629&status=done&style=none&taskId=ud099a776-9a3c-4064-9878-25628577e3a&width=503)<br />alpha：学习率。太小：很慢到达全局最优点；太大：越过最低点难以收敛<br />theta[0]和[1]和同步更新

<a name="a100F"></a>
# 多变量线性回归
![image.png](https://cdn.nlark.com/yuque/0/2022/png/25360752/1655213125039-313d7d89-eba8-4d87-8615-23e11cbcf0e5.png#clientId=u22da2a13-cfae-4&from=paste&height=36&id=ue53c0733&margin=%5Bobject%20Object%5D&name=image.png&originHeight=36&originWidth=110&originalType=binary&ratio=1&size=5378&status=done&style=none&taskId=u0123b988-6668-4d41-9034-f3d3bd3cdf3&width=110)


