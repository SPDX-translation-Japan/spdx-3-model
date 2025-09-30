SPDX-License-Identifier: Community-Spec-1.0

# VulnAssessmentRelationship

## Summary

Abstract ancestor class for all vulnerability assessments

## Description

VulnAssessmentRelationship is the ancestor class common to all vulnerability
assessment relationships. It factors out the common properties shared by them.

## Metadata

- name: VulnAssessmentRelationship
- SubclassOf: /Core/Relationship
- Instantiability: Abstract

## Properties

- assessedElement
  - type: /Software/SoftwareArtifact
  - minCount: 0
  - maxCount: 1
- publishedTime
  - type: /Core/DateTime
  - minCount: 0
  - maxCount: 1
- /Core/suppliedBy
  - type: /Core/Agent
  - minCount: 0
  - maxCount: 1
- modifiedTime
  - type: /Core/DateTime
  - minCount: 0
  - maxCount: 1
- withdrawnTime
  - type: /Core/DateTime
  - minCount: 0
  - maxCount: 1

## Summary @zh-Hans

所有漏洞评估的抽象祖先类。

## Description @zh-Hans

`VulnAssessmentRelationship`是所有漏洞评估关系的祖先类，提取它们共享的公共属性。

## Summary @ja

すべての脆弱性アセスメントの抽象的な祖先クラス

## Description @ja

VulnAssessmentRelationship は、すべての脆弱性アセスメント関係に共通する祖先クラスである。
このクラスは、それらに共通するプロパティを抽出して定義している。

