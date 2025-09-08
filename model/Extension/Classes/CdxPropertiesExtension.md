SPDX-License-Identifier: Community-Spec-1.0

# CdxPropertiesExtension

## Summary

A type of extension consisting of a list of name value pairs.

## Description

This extension provides a more structured extension using a name-value
approach.

Unlike key-value stores, properties in CdxPropertiesExtension support duplicate names, each
potentially having different values.

This is intended to be compatible with the CycloneDX property `properties`.

## Metadata

- name: CdxPropertiesExtension
- SubclassOf: Extension
- Instantiability: Concrete

## Properties

- cdxProperty
  - type: CdxPropertyEntry
  - minCount: 1

## Summary @ja

名前と値のペアのリストで構成される拡張子の種類を表すクラス

## Description @ja

`CdxPropertiesExtension` は、名前と値のアプローチを用いたより構造化された拡張機能を提供する。

key-valueストアとは異なり、 `CdxPropertiesExtension` のプロパティは重複する名前をサポートし、それぞれが異なる値を持つ可能性がある。

これはCycloneDXのプロパティ`properties`との互換性を意図したものである。