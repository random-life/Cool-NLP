# 词库介绍
面向中文处理的12类、百万规模的语义常用词典，包括34万抽象语义库、34万反义语义库、43万同义语义库等，可支持句子扩展、转写、事件抽象与泛化等多种应用场景。

# 数据来源
Github：[liuhuanyong/ChineseSemanticKB](https://github.com/liuhuanyong/ChineseSemanticKB)

# 词典样例

| 词库类型 | 词库规模 | 词库举例 | 词库应用 |
| :--- | :---: | :---: | :---: |
| 抽象关系库 | 346,048 | 座椅,抽象,家具 | 事件抽象与泛化，人民币贬值到货币贬值，再到美元贬值，可支持查询扩展、推荐等任务 |
| 反义关系库 | 34,380 | 开心@苦恼 | 可用于句子改写，开心改苦恼，支持数据增强，句子生成 |
| 同义关系库 | 424,826 | 开心@高兴| 可用于查询扩展、数据增强，也可结合抽象关系库完成推荐等任务 |
| 简称关系库 | 136,081 | 北京大学@北大| 可用于句子标准化、句子改写、实体消歧等任务 |
| 程度副词 | 222 | 极其,2.0 | 可用于情感强度计算，带情感色彩的句子生成 |
| 否定词 | 586 | 不,无,没有 | 可用于情感计算等任务 |
| 节日时间词 | 54 | 春节、五四节 | 可用于时间词识别等任务 |
| 量比词 | 7 | 占比、环比、同比 | 可用于金融领域指标类数据提取任务 |
| 数量介词 | 24| 大约、达到、超过 |可用于金融事件抽象或主干化的搭配词处理任务  |
| 停用词 | 3,861 | ？、的、着 | 常规的文本特征提取等任务 |
| 修饰副词 | 222 | 所、有所 | 可结合程度副词完成情感强度计算等任务 |
| 情态词 |　77 | 肯定、应该、大概 | 可用于句子主观性计算、舆情与可信度计算 |