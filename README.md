# Question-Answer-Datasets

### 本项目用于记录在项目期间用到的数据集，主要为中文

#### 问答任务

#### 文本相似度匹配任务

#### 文本分类任务



# 文本匹配

| ID   | 标题                                                         | 更新日期       | 数据集提供者                                  | 许可                                                   | 说明                                                         | 关键字                                                       | 类别                       | 论文地址                                                     | 备注 |
| ---- | ------------------------------------------------------------ | -------------- | --------------------------------------------- | ------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------- | ------------------------------------------------------------ | ---- |
|      |                                                              |                |                                               |                                                        |                                                              |                                                              |                            |                                                              |      |
| 1    | [LCQMC](https://github.com/ares5221/Question-Answer-Datasets/tree/master/LCQMC) | 2018/6/6       | 哈工大(深圳)智能计算研究中心                  | Creative Commons Attribution 4.0 International License | <font size=2> 该数据集共包含来自多个领域的260068个中文问句对，相同询问意图的句子对标记为1，否则为0；并预先将其切分为了训练集：238766对，验证集：8802对，测试集：12500对 </font> | 大规模问句匹配；意图匹配                                     | 短文本匹配；问句匹配       | [论文](https://www.aclweb.org/anthology/C18-1166)            |      |
| 2    | [The BQ Corpus](https://github.com/ares5221/Question-Answer-Datasets/tree/master/BQ_corpus) | 2018/9/4       | 哈工大(深圳)智能计算研究中心；微众银行        |                                                        | <font size=2> 该数据集共有120000个句子对，来自银行一年中的咨询服务日志；句子对包含不同的意图，标记正负样本比例为1:1 </font> | 银行服务问句；意图匹配                                       | 短文本匹配；问句一致性检测 | [论文](https://www.aclweb.org/anthology/D18-1536/)           |      |
| 3    | [AFQMC 蚂蚁金融语义相似度](https://dc.cloud.alipay.com/index?click_from=MAIL&_bdType=acafbbbiahdahhadhiih#/topic/intro?id=3) | 2018/4/25      | 蚂蚁金服                                      |                                                        | <font size=2>提供10万对的标注数据（分批次更新，已更新完毕），作为训练数据，包括同义对和不同义对<font> | 金融问句                                                     | 短文本匹配；问句匹配       |                                                              |      |
| 4    | [第三届拍拍贷“魔镜杯”大赛](https://ai.ppdai.com/mirror/goToMirrorDetail?mirrorId=1) | 2018/6/10      | 拍拍贷智慧金融研究院                          |                                                        | <font size=2> train.csv文件包含3列，分别是标签（label，表示问题1和问题2是否表示相同的意思，1表示相同，0表示不同），问题1的编号（q1）和问题2的编号（q2）。本文件中出现的所有问题编号均在question.csv中出现过 </font> | 金融产品                                                     | 短文本匹配；问句匹配       |                                                              |      |
| 5    | [CAIL2019相似案例匹配大赛](https://github.com/china-ai-law-challenge/CAIL2019/tree/master/scm) | 2019/6         | 清华大学；中国裁判文书网                      |                                                        | <font size=2> 对于每份数据，用三元组(A,B,C)来代表该组数据，其中A,B,C均对应某一篇文书。文书数据A与B的相似度总是大于A与B的相似度的，即sim(A,B)>sim(A,C) </font> | 法律文书；相似案例                                           | 长文本匹配                 |                                                              |      |
| 6    | [CCKS 2018 微众银行智能客服问句匹配大赛](https://biendata.com/competition/CCKS2018_3/data/) | 2018/4/5       | 哈工大(深圳)智能计算研究中心；微众银行        |                                                        | <font size=2>                                                              </font> | 银行服务问句；意图匹配                                       | 短文本匹配；问句匹配       |                                                              |      |
| 7    | [ChineseTextualInference](https://github.com/liuhuanyong/ChineseTextualInference) | 2018/12/15     | 刘焕勇，中国科学院软件研究所                  |                                                        | <font size=2> 中文文本推断项目,包括88万文本蕴含中文文本蕴含数据集的翻译与构建,基于深度学习的文本蕴含判定模型构建 </font> | 中文NLI                                                      | 中文文本推断；文本蕴含     |                                                              |      |
| 8    | [NLPCC-DBQA](https://biendata.com/ccf_tcci2018/datasets/tcci_tag/11) | 2016/2017/2018 | NLPCC                                         |                                                        | <font size=2> 给定问题-答案，以及该答案是否是该问题的答案之一的标记，1表示是，0表示不是 </font> | DBQA                                                         | 问答匹配                   |                                                              |      |
| 9    | [“技术需求”与“技术成果”项目之间关联度计算模型](https://www.datafountain.cn/competitions/359) | 201/8/32       | CCF                                           |                                                        | <font size=2> 给定文本形式的技术需求和技术成果，以及需求与成果的关联度标签；其中技术需求与技术成果之间的关联度分为四个层级： 强相关、较强相关、弱相关、无相关 </font> | 长文本；需求与成果匹配                                       | 长文本匹配                 |                                                              |      |
| 10   | [CNSD / CLUE-CMNLI](https://github.com/zengjunjun/CNSD)      | 2019/12        | ZengJunjun                                    |                                                        | <font size=2> 中文自然语言推理数据集，本数据及通过翻译加部分人工修正的方法，从英文原数据集生成，可以一定程度缓解中文自然语言推理和语义相似度计算数据集不够的问题 </font> | 中文NLI                                                      | 中文自然语言推断           | [论文](https://6a75-junzeng-uxxxm-1300734931.tcb.qcloud.la/CNSD.pdf?sign=401485f4d6f256393a264e68464ca4ae&t=1578114336) |      |
| 11   | [cMedQA v1.0](https://github.com/zhangsheng93/cMedQA)        | 2017/4/5       | 寻药寻医网 和国防科技大学 信息系统及管理 学院 |                                                        | <font size=2> 该数据集来源为寻医寻药网站中的提问和回答， 数据集做过匿名处理，提供的是包含 训练集中有50,000个问题，94,134个答案，平均每个问题、答案字符数分别为为120、212个； 验证集有2,000个问题，有3774个答案，问题和答案的平均字符数分别为117和212个； 测试集有2,000个问题，有3835个答案，问题和答案的平均字符数分别为119和211个； 数据集总量有54,000个问题，101,743个答案，平均每个问题和答案的字符数分别为119、212个； </font> | 医疗问答匹配                                                 | 问答匹配                   | [论文](https://www.mdpi.com/2076-3417/7/8/767)               |      |
| 12   | [cMedQA2](https://github.com/zhangsheng93/cMedQA2)           | 2018/11/8      | 寻药寻医网 和国防科技大学 信息系统及管理 学院 |                                                        | <font size=2> 该数据集来源为寻医寻药网站中的提问和回答， 数据集做过匿名处理，提供的是包含 训练集中有100,000个问题，188,490个答案，平均每个问题、答案字符数分别为为48、101个； 验证集有4,000个问题，有7527个答案，问题和答案的平均字符数分别为49和101个； 测试集有4,000个问题，有7552个答案，问题和答案的平均字符数分别为49和100个； 数据集总量有108,000个问题，203,569个答案，平均每个问题和答案的字符数分别为49、101个； </font> | 医疗问答匹配                                                 | 问答匹配                   | [论文](https://www.mdpi.com/2076-3417/7/8/767)               |      |
| 13   | [ChineseSTS](https://github.com/IAdmireu/ChineseSTS)         | 2017/9/21      | 唐善成, 白云悦, 马付玉.  西安科技大学         |                                                        | <font size=2> 该数据集提供了12747对中文相似数据集，在数据集后 作者给出了他们相似度的打分，语料由短句构成。 </font> | 短句相似度 匹配                                              | 相似度匹配                 |                                                              |      |
| 14   | [中国健康信息处理会议 举办的医疗问题相似度 衡量竞赛数据集](https://biendata.com/competition/chip2018/) | 2018           | CHIP 2018-第四届中国健康信息处理会议（CHIP）  |                                                        | <font size=2> 本次评测任务的主要目标是针对中文的真实患者健康咨询语料，进行问句意图匹配。 给定两个语句，要求判定两者意图是否相同或者相近。 所有语料来自互联网上患者真实的问题，并经过了筛选和人工的意图匹配标注。 数据集经过脱敏处理，问题由数字标示 训练集包含20000条左右标注好的数据（经过脱敏处理，包含标点符号），  测试集包含10000条左右无label的数据（经过脱敏处理，包含标点> 符号）。 </font> | 医疗问题相似度 匹配                                          | 相似度匹配                 |                                                              |      |
| 15   | [COS960: A Chinese Word Similarity Dataset of 960 Word Pairs](https://github.com/thunlp/COS960) | 2019/6/6       | 清华大学                                      |                                                        | <font size=2> 该数据集中包含了960对单词， 并且每对单词都被15个母语者用相似度分数来衡量 这960个词对根据标签被分成三组， 包含480对名词，240对动词和240对形容词。 </font> | 单词之间的相似度                                             | 同义词                     | [论文](https://arxiv.org/abs/1906.00247)                     |      |
| 16   | OPPO手机搜索排序query-title语义匹配数据集。(https://pan.baidu.com/s/1Hg2Hubsn3GEuu4gubbHCzw  密码7p3n) | 2018/11/6      | OPPO                                          |                                                        | <font size=2> 该数据集来自于OPPO手机搜索排序优化实时搜索场景, 该场景就是在用户不断输入过程中，实时返回查询结果。 该数据集在此基础上做了相应的简化， 提供了一个query-title语义匹配，即ctr预测的问题。 </font> | 问题标题匹配， ctr预测                                       | 相似度匹配                 |                                                              |      |
| 17   | [网页搜索结果评价(SogouE)](https://www.sogou.com/labs/resource/e.php) | 2012年         | 搜狗                                          | 搜狗实验室数据使用许可协议                             | <font size=2> 该数据集包含了查询词，相关URL以及查询类别的搜索数据，格式如下 数据格式说明：查询词]\t相关的URL\t查询类别 其中URL保证存在于对应的互联网语料库； 查询类别中“1”表示导航类查询；“2”表示信息类查询 </font> | [Automatic Search Engine Performance Evaluation with Click-through Data Analysis](https://www.sogou.com/labs/paper/Automatic_Search_Engine_Performance_Evaluation_with_Click-through_Data_Analysis.pdf) | 查询类型匹配预测           |                                                              |      |

# 多轮对话

| ID   | 标题                                                         | 更新日期 | 数据集提供者                 | 许可                                                   | 说明                                                         | 关键字                   | 类别                 | 论文地址                                          | 备注 |
| ---- | ------------------------------------------------------------ | -------- | ---------------------------- | ------------------------------------------------------ | ------------------------------------------------------------ | ------------------------ | -------------------- | ------------------------------------------------- | ---- |
|      |                                                              |          |                              |                                                        |                                                              |                          |                      |                                                   |      |
| 1    | [LCQMC](https://github.com/ares5221/Question-Answer-Datasets/tree/master/LCQMC) | 2018/6/6 | 哈工大(深圳)智能计算研究中心 | Creative Commons Attribution 4.0 International License | <font size=2> 该数据集共包含来自多个领域的260068个中文问句对，相同询问意图的句子对标记为1，否则为0；并预先将其切分为了训练集：238766对，验证集：8802对，测试集：12500对 </font> | 大规模问句匹配；意图匹配 | 短文本匹配；问句匹配 | [论文](https://www.aclweb.org/anthology/C18-1166) |      |
| 2    | 对话 青松                                                    |          |                              |                                                        |                                                              |                          |                      |                                                   |      |
|      |                                                              |          |                              |                                                        |                                                              |                          |                      |                                                   |      |
|      |                                                              |          |                              |                                                        |                                                              |                          |                      |                                                   |      |
|      |                                                              |          |                              |                                                        |                                                              |                          |                      |                                                   |      |
|      |                                                              |          |                              |                                                        |                                                              |                          |                      |                                                   |      |
|      |                                                              |          |                              |                                                        |                                                              |                          |                      |                                                   |      |
|      |                                                              |          |                              |                                                        |                                                              |                          |                      |                                                   |      |
|      |                                                              |          |                              |                                                        |                                                              |                          |                      |                                                   |      |
|      |                                                              |          |                              |                                                        |                                                              |                          |                      |                                                   |      |
|      |                                                              |          |                              |                                                        |                                                              |                          |                      |                                                   |      |
|      |                                                              |          |                              |                                                        |                                                              |                          |                      |                                                   |      |
|      |                                                              |          |                              |                                                        |                                                              |                          |                      |                                                   |      |
|      |                                                              |          |                              |                                                        |                                                              |                          |                      |                                                   |      |
|      |                                                              |          |                              |                                                        |                                                              |                          |                      |                                                   |      |
|      |                                                              |          |                              |                                                        |                                                              |                          |                      |                                                   |      |
|      |                                                              |          |                              |                                                        |                                                              |                          |                      |                                                   |      |