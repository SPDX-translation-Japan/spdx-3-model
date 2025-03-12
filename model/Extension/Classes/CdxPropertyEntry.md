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

## Summary @zh-Hans

一个属性名称及其关联的值。

## Description @zh-Hans

每个`CdxPropertyEntry`都包含一个名值对，将名称映射到其关联的值。

与键值存储不同，`CdxPropertiesExtension`中的属性支持重名，每个属性可以具有不同的值。

此类可用于实现与CycloneDX兼容的属性。