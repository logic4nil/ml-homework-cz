###已完成部分:
* 实现gbdt计算残差，叶子节点的值，f值的更新

###遇到的问题：
* 最初设置正负样本的值为（0，1），这样计算得到的预测概率值都是>0.5的
* 这是因为在将预测值转换为概率时，使用的是sigmoid函数，sigmoid函数在取0时值为0.5
* 这是因为计算得到的f值是对标签值的拟合，改为正负样本值为（-1，1）解决

###TODO
* k折交叉
* AUC
* xgboost
* 迭代版本

