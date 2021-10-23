# sodic2021_qa
- 2021全球开放数据应用创新大赛法律咨询问答第2名方案
- 比赛官网：https://www.sodic.com.cn/competitions/900022
### 简介

使用追一科技开源的T5-base进行生成式建模，具体方案见[答辩PPT](【2021SODiC】法律咨询智能问答-TCCI-答辩路演PPT.pdf)

### 融合方式-投票

首先从多个预测答案中抽取出第一条作为预测答案，其余作为标准答案；

然后计算出预测答案和所有标准答案的分值，累加起来作为该预测答案的得分；

最后选取得分最高的作为最终答案。

这种模型融合方式适用于阅读理解、摘要等复杂任务
