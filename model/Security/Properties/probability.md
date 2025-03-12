SPDX-License-Identifier: Community-Spec-1.0

# probability

## Summary

A probability score between 0 and 1 of a vulnerability being exploited.

## Description

The probability score between 0 and 1 (0 and 100%) estimating the likelihood of
exploitation in the wild in the next 30 days (following score publication).
The definition follows "epss" in
[EPSS Data](https://www.first.org/epss/data_stats).

## Metadata

- name: probability
- Nature: DataProperty
- Range: xsd:decimal

## Summary @zh-Hans

漏洞被利用的概率分数，范围为0到1。

## Description @zh-Hans

预估未来30天（发布评分后）漏洞在实际环境中被利用的概率分数，范围为0到1（0%到100%）。此定义参照[EPSS数据](https://www.first.org/epss/data_stats)中的“epss”定义。
