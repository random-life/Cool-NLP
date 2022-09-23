**数据名称：**翻译语料 (translation2019zh)

**数据规格**: 1.1G, 520万个中英文平行语料

**数据描述**：中英文平行语料520万对。每一个对，包含一个英文和对应的中文。中文或英文，多数情况是一句带标点符号的完整的话。对于一个平行的中英文对，中文平均有36个字，英文平均有19个单词(单词如“she”)。

**数据集划分**：数据去重并分成三个部分。训练集：516万；验证集：3.9万；测试集，数万，不提供下载。

**内容结构**：

```json
{"english": <english>, "chinese": <chinese>}

其中，english是英文句子，chinese是中文句子，中英文一一对应。
```

**示例**：

`{"english": "In Italy, there is no real public pressure for a new, fairer tax system.", "chinese": "在意大利，公众不会真的向政府施压，要求实行新的、更公平的税收制度。"}`

**数据来源**：github：[nlp_chinese_corpus](https://github.com/brightmart/nlp_chinese_corpus)

