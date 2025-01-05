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

## Summary @zh-Hans

提供属性名称与值的映射。

## Description @zh-Hans

此字段提供名称与值的映射。

目的是与CycloneDX属性`properties`兼容。

与键值存储不同，`CdxPropertiesExtension`中的属性支持重名，每个属性可以具有不同的值。
