# 强化学习：模拟特卡罗方法与时间差分方法
- 构建一个简单的环境，有nS个状态，0，1，...，nS-1；其中nS-1是终止状态。 该环境下一共两个动作：0向左运动，1向右运动，每个动作都有概率p0不动，p1的概率会往反方向运动, 1-p0-p1概率正常运动。

|0 | 1 | 2 | ... | 9 |
|--|--|----|-----|---|
|←·→|←·→|←·→|←·→|终点|

- 实现上述问题的模拟特卡罗方法和3种时间差分方法（SARSA, Q-learning, Double Q-learning）
- 提交作业请发PR，可以参考tracholar，子目录名字请用自己的名字，谢谢