SPDX-License-Identifier: Community-Spec-1.0

# CdxPropertyEntry

## Summary

A property name with an associated value.

## Description

Each CdxPropertyEntry contains a name-value pair which maps the name to its
associated value.

Unlike key-value stores, properties in CdxPropertiesExtension support duplicate
names, each potentially having different values.

This class can be used to implement CycloneDX compatible properties.

## Metadata

- name: CdxPropertyEntry
- Instantiability: Concrete

## Properties

- cdxPropName
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- cdxPropValue
  - type: xsd:string
  - maxCount: 1

## Summary @ja

関連付けられた値を持つプロパティ名を表すクラス

## Description @ja

各 `CdxPropertyEntry` は、名前とその関連値をマッピングするname-valueのペアを含む。

key-valueストアとは異なり、`CdxPropertiesExtension` のプロパティは重複する名前をサポートし、それぞれが異なる値を持つ可能性がある。

このクラスは、CycloneDX互換のプロパティを実装するために使用することが可能である。