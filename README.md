# 冬奥会问答数据集——WinterOlympics-QA

WinterOlympics-QA公开数据集包含训练集（train_set.json）与测试集（test_set.json）两部分，语言为中文。

训练集包含14701条问答对数据，格式为：

```bash
{"question":"1924年在法国夏蒙尼冬奥会上决出的第一个项目是什么？","answer":"男子500米速度滑冰"}
```

测试集包含1733条无答案的问题数据，格式为：

```bash
{"question":"《中国冬奥会史》是哪位作家的作品？"}
```

训练集问句类型包括Which、Who、Where、How、When、Why、Whether等主观/客观问句，分布如下：
| 问题种类 | 数量 | 
| ------ | ----------- |
| how | 5,411 |
| which | 5,785 |
| when | 2,232 |
| where | 515 |
| whether | 147 |
| who | 457 |
| why | 155 |

问题答案来自[维基百科](https://zh.wikipedia.org/)、[百度知道](https://zhidao.baidu.com/)等公开网页，本数据集不保证问题与答案的准确性与时效性。
