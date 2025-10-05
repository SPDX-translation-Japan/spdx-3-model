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

## Summary @ja

脆弱性が悪用される確率を示す、0から1の範囲のスコア。

## Description @ja

現在の確率スコアを 0 から 1（すなわち 0〜100%）の範囲で示し、公開後30日以内に実際の環境で悪用される可能性を推定する。
定義は [EPSS Data](https://www.first.org/epss/data_stats) における「epss」に従う。
