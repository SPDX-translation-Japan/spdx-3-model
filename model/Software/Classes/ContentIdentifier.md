SPDX-License-Identifier: Community-Spec-1.0

# ContentIdentifier

## Summary

A canonical, unique, immutable identifier

## Description

A ContentIdentifier is a canonical, unique, immutable identifier of the content
of a software artifact, such as a package, a file, or a snippet.

It can be used for verifying its identity and integrity.

## Metadata

- name: ContentIdentifier
- SubclassOf: /Core/IntegrityMethod
- Instantiability: Concrete

## Properties

- contentIdentifierType
  - type: ContentIdentifierType
  - minCount: 1
  - maxCount: 1
- contentIdentifierValue
  - type: xsd:anyURI
  - minCount: 1
  - maxCount: 1
## Summary @zh-Hans

一个规范的、唯一的、不可变的标识符。

## Description @zh-Hans

内容标识符(`ContentIdentifier`) 是软件工件内容的一个规范的、唯一的、不可变的标识符，例如一个软件包，一个文件或一个代码片段。

它可用于验证其身份和完整性。

