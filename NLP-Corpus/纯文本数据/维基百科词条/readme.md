**数据名称：**维基百科json版(wiki2019zh)

**数据规格**:1.6G左右，104万个词条

**数据描述**：100万个结构良好的中文词条。

**数据集划分**：

**内容结构**：

```
{"id":<id>,"url":<url>,"title":<title>,"text":<text>} 其中，title是词条的标题，text是正文；通过"\n\n"换行。
```

**示例**：

```
{"id": "53", "url": "https://zh.wikipedia.org/wiki?curid=53", "title": "经济学", "text": "经济学\n\n经济学是一门对产品和服务的生产、分配以及消费进行研究的社会科学。西方语言中的“经济学”一词源于古希腊的。\n\n经济学注重的是研究经济行为者在一个经济体系下的行为，以及他们彼此之间的互动。在现代，经济学的教材通常将这门领域的研究分为总体经济学和个体经济学。微观经济学检视一个社会里基本层次的行为，包括个体的行为者（例如个人、公司、买家或卖家）以及与市场的互动。而宏观经济学则分析整个经济体和其议题，包括失业、通货膨胀、经济成长、财政和货币政策等。..."}
```

**数据来源**：github：[nlp_chinese_corpus](https://github.com/brightmart/nlp_chinese_corpus)

