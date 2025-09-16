SPDX-License-Identifier: Community-Spec-1.0

# metricDecisionThreshold

## Summary

Captures the threshold that was used for computation of a metric described in
the metric field.

## Description

Each metric might be computed based on a decision threshold.

For instance, precision or recall is typically computed by checking if the
probability of the outcome is larger than 0.5.

Each decision threshold should match with a metric field defined in the AI
package.

## Metadata

- name: metricDecisionThreshold
- Nature: ObjectProperty
- Range: /Core/DictionaryEntry

## Summary @zh-Hans

记录用于计算`metric`字段中所述指标的阈值。

## Description @zh-Hans

指标可以基于决策阈值计算。

例如，精确度或召回率通常通过检查结果的概率是否大于0.5来计算。

每个决策阈值应与AI包中定义的 `metric` 字段相匹配。

## Summary @ja

metricフィールドで記述された指標を計算する際に用いられた閾値を記録する。

## Description @ja

各metricは、ある意思決定の閾値に基づいて計算される場合がある。

たとえば、精度（precision）や再現率（recall）は、結果の確率が0.5を超えているかどうかを確認することで計算されるのが一般的である。

各意思決定の閾値は、AIパッケージ内で定義されたmetricフィールドと対応していなければならない。

