SPDX-License-Identifier: Community-Spec-1.0

# modelExplainability

## Summary

Describes methods that can be used to explain the results from the AI model.

## Description

A free-form text that lists the different explainability mechanisms and how
they can be used to explain the results from the AI model.

The mechanisms can be model-agnostic methods, such as
[SHapley Additive exPlanations (SHAP)](https://shap.readthedocs.io/) and
[Local Interpretable Model-agnostic Explanations (LIME)](https://github.com/marcotcr/lime),
and model-specific methods that applied to a limited category of models.

## Metadata

- name: modelExplainability
- Nature: DataProperty
- Range: xsd:string

## Summary @zh-Hans

描述用于解释AI模型结果的方法。

## Description @zh-Hans

列出不同可解释性机制及其如何用于解释AI模型结果的自由格式文本。

这些机制可以是与模型无关的方法，如[SHAP](https://shap.readthedocs.io/)和[LIME](https://github.com/marcotcr/lime)，也可以是只适用于有限类别模型的特定于模型的方法。

## Summary @ja

AIモデルの結果を説明するために使用できる手法を記述する。

## Description @ja

AIモデルの結果を説明するために利用できるさまざまな説明可能性メカニズムと、それらがどのように結果を説明するのに役立つかを列挙する自由形式のテキストである。

これらのメカニズムには、モデル非依存の手法（たとえば
[SHapley Additive exPlanations (SHAP)](https://shap.readthedocs.io/) や
[Local Interpretable Model-agnostic Explanations (LIME)](https://github.com/marcotcr/lime)
）と、特定の種類のモデルにのみ適用されるモデル依存の手法が含まれる。
