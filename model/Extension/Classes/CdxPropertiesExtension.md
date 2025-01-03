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

## Summary  @zh-Hans

一种扩展类型，由名值对的列表组成。

## Description  @zh-Hans

此扩展采用名值方法，提供了更结构化的扩展。

与键值存储不同，`CdxPropertiesExtension`中的属性支持重名，每个属性可以具有不同的值。

目的是与CycloneDX属性`properties`兼容。
