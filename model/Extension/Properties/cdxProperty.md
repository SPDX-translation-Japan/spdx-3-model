SPDX-License-Identifier: Community-Spec-1.0

# cdxProperty

## Summary

Provides a map of a property names to a values.

## Description

This field provides a mapping of a name to a value.

This is intended to be compatible with the CycloneDX property `properties`.

Unlike key-value stores, properties in CdxPropertiesExtension support duplicate
names, each potentially having different values.

## Metadata

- name: cdxProperty
- Nature: ObjectProperty
- Range: CdxPropertyEntry

## Summary @ja

プロパティ名から値へのマップを提供するプロパティ

## Description @ja

`cdxProperty` は、名前と値のマッピングを提供する。

CycloneDXのプロパティ`properties`との互換性を意図している。

key-valueストアとは異なり、`CdxPropertiesExtension` のプロパティは重複する名前をサポートし、それぞれが異なる値を持つ可能性がある。