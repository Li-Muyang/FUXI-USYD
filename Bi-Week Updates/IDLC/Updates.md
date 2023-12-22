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

7.14 meeting

上周问题：

1. 刘老师分享时间确定(八月初)
2. 分享内容, 标签噪声+半监督
3. Cora数据集简化(不成功)
4. 继续寻找新的图结构数据集
5. cross-domain evaluation调研(https://openaccess.thecvf.com/content/CVPR2021/papers/Deng_Are_Labels_Always_Necessary_for_Classifier_Accuracy_Evaluation_CVPR_2021_paper.pdf)

7.28 meeting
上周问题：
1. 继续寻找新的图结构数据集(wiki-CS)
2. 多模态数据集标签噪声(proposal)

总结：
1. wiki-CS标注成本估计
2. 多模态数据集标注成本估计
3. 继续寻找新的图结构数据集

10.20 meeting
上周问题：
1. CLIP工作总结调研

总结：
1. CLIP confidence的evaluation(验证实验)
2. InstanT专利问题咨询刘老师
3. 继续camera-ready以及现有工作

12.08 meeting
上周问题：
1. 继续ICML coreset实验

总结：
1. 寻找研究方向与业务问题的共同来确定新工作

12.22 meeting
上周问题：
1. NeurIPS参会

