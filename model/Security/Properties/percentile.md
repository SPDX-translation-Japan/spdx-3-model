SPDX-License-Identifier: Community-Spec-1.0

# percentile

## Summary

The percentile of the current probability score.

## Description

The percentile between 0 and 1 (0 and 100%) of the current probability score,
the proportion of all scored vulnerabilities with the same or a lower
probability score. The definition follows "percentile" in
[EPSS Data](https://www.first.org/epss/data_stats).

## Metadata

- name: percentile
- Nature: DataProperty
- Range: xsd:decimal

## Summary @zh-Hans

当前概率分数的百分位数。

## Description @zh-Hans

当前概率分数的百分位数，范围为0到1（0到100%），表示所有得分漏洞中具有相同或更低概率得分的比例。此定义参照[EPSS数据](https://www.first.org/epss/data_stats)中的“percentile”定义。

## Summary @ja

現在の確率スコアのパーセンタイルを示す。

## Description @ja

現在の確率スコアにおけるパーセンタイル（0から1の範囲、すなわち0〜100%）を示す。
これは、同じまたはそれ以下の確率スコアを持つすべての脆弱性の割合を表す。
定義は [EPSS Data](https://www.first.org/epss/data_stats) における「percentile」に従う。
