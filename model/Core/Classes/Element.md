SPDX-License-Identifier: Community-Spec-1.0

# Element

## Summary

Base domain class from which all other SPDX-3.0 domain classes derive.

## Description

An Element is a representation of a fundamental concept either directly inherent
to the Bill of Materials (BOM) domain or indirectly related to the BOM domain
and necessary for contextually characterizing BOM concepts and relationships.
Within SPDX-3.0 structure this is the base class acting as a consistent,
unifying, and interoperable foundation for all explicit
and inter-relatable content objects.

## Metadata

- name: Element
- SubclassOf: none
- Instantiability: Abstract

## Properties

- spdxId
  - type: xsd:anyURI
  - minCount: 1
  - maxCount: 1
- name
  - type: xsd:string
  - maxCount: 1
- summary
  - type: xsd:string
  - maxCount: 1
- description
  - type: xsd:string
  - maxCount: 1
- comment
  - type: xsd:string
  - maxCount: 1
- creationInfo
  - type: CreationInfo
  - minCount: 1
  - maxCount: 1
- verifiedUsing
  - type: IntegrityMethod
- externalRef
  - type: ExternalRef
  - minCount: 0
- externalIdentifier
  - type: ExternalIdentifier
  - minCount: 0
- extension
  - type: /Extension/Extension
  - minCount: 0

## Summary @ja

すべての他の SPDX-3.0 ドメインクラスが派生する基底ドメインクラス。

## Description @ja

Element は BOM ドメインに直接固有または間接的に関連し、BOM の概念や関係を文脈的に特徴づけるために必要となる基本概念の表現である。SPDX-3.0 の構造において、Element はすべての明示的かつ相互関連可能なコンテンツオブジェクトの一貫性のある、統一的で相互運用可能な基盤となる。
