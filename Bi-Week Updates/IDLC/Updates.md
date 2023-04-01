3.17 Meetings

上周总结：

1. 新添加了两个baseline（coteaching NIPS 2018, BARE WACV 2023）

2. 通过我们模型所correct的标签比例，仍小于early-stop所得的label的clean标签比例

本周总结：

1. 新添加了一个baseline（PLC ICLR 2021）

2. 将label correction方法从单次的correction改成iterative的correction，目前效果优于early-stop所得的label的clean标签比例

3. 目前在30% 的 noise rate的情况下，效果略弱于PLC

本周问题：

1. label noise learning workshop/competition - 数据问题

2. 刘老师分享（topic 在 trustworthy/data centric）

3.31 Meetings

上周总结：

1. 经刘老师建议，把setting改到semi-supervised learning下
2. 在USB library (https://github.com/microsoft/Semi-supervised-learning)尝试实现我们的方法
3. 熟悉半监督的setting和现有的工作


本周
1. 完成了文章intro部分的写作
2. 在USB library下实现了我们的方法, 正在收集结果

本周问题：

1. 找一下图结构数据的不同形式并且展示
2. 提前多久和刘老师确定talk的时长
3. 希望刘老师从标签噪声生成的角度谈一下这个问题 （哪些误差是随机造成，哪些是固定误差）
