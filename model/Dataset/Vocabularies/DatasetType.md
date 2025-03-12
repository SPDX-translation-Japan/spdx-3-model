SPDX-License-Identifier: Community-Spec-1.0

# DatasetType

## Summary

Enumeration of dataset types.

## Description

Describes the different structures of data within a given dataset. A dataset
can have multiple types of data, or even a single type of data but still match
multiple types, for example sensor data could also be timeseries or labeled
image data could also be considered categorical.

## Metadata

- name: DatasetType

## Entries

- audio: data is audio based, such as a collection of music from the 80s.
- categorical: data that is classified into a discrete number of categories, such as the eye color of a population of people.
- graph: data is in the form of a graph where entries are somehow related to each other through edges, such a social network of friends.
- image: data is a collection of images such as pictures of animals.
- noAssertion: data type is not known.
- numeric: data consists only of numeric entries.
- other: data is of a type not included in this list.
- sensor: data is recorded from a physical sensor, such as a thermometer reading or biometric device.
- structured: data is stored in tabular format or retrieved from a relational database.
- syntactic: data describes the syntax or semantics of a language or text, such as a parse tree used for natural language processing.
- text: data consists of unstructured text, such as a book, Wikipedia article (without images), or transcript.
- timeseries: data is recorded in an ordered sequence of timestamped entries, such as the price of a stock over the course of a day.
- timestamp: data is recorded with a timestamp for each entry, but not necessarily ordered or at specific intervals, such as when a taxi ride starts and ends.
- video: data is video based, such as a collection of movie clips featuring Tom Hanks.

## Summary @zh-Hans

数据集类型的枚举。

## Description @zh-Hans

描述给定数据集中的不同数据结构。一个数据集可以包含多种类型的数据，或者即使是单一类型的数据，但仍可以匹配多种类型。例如，传感器数据也可以是时间序列数据，或者带有标签的图像数据也可以被认为是分类数据。

## Entries @zh-Hans

- audio: 数据基于音频，比如 80 年代的音乐集合。
- categorical: 数据被分类到离散数量的类别中，比如人群的眼睛颜色。
- graph: 数据以图的形式呈现，其中条目通过边相互关联，比如朋友的社交网络。
- image: 数据是一组图像，比如动物的图片。
- noAssertion: 数据类型未知。
- numeric: 数据仅由数值条目组成。
- other: 数据类型不在本列表中。
- sensor: 数据来自物理传感器的记录，比如温度计读数或生物识别设备。
- structured: 数据以表格格式存储或从关系数据库中检索。
- syntactic: 数据描述语言或文本的语法或语义，比如用于自然语言处理的解析树。
- text: 数据由非结构化文本组成，比如书籍、维基百科文章（不含图片）或转录稿。
- timeseries: 数据以有序的时间戳条目序列记录，比如一天内股票价格的变化。
- timestamp: 每个数据条目都记录了时间戳，但不一定是有序的或在特定的时间间隔内，比如出租车行程的开始和结束时间。
- video: 数据基于视频，比如汤姆·汉克斯主演的电影片段集合。
