SPDX-License-Identifier: Community-Spec-1.0

# File

## Summary

Refers to any object that stores content on a computer.

## Description

Refers to any object that stores content on a computer.
The type of content can optionally be provided in the contentType property.

The fileKind property can be set to `directory` to indicate the file represents
a directory and all content stored in that directory.

## Metadata

- name: File
- SubclassOf: /Software/SoftwareArtifact

## Properties

- /Core/contentType
  - type: /Core/MediaType
  - minCount: 0
  - maxCount: 1
- fileKind
  - type: FileKindType
  - minCount: 0
  - maxCount: 1

## External properties restrictions

- /Core/Element/name
  - minCount: 1

## Summary  @zh-Hans

指计算机上存储内容的任意对象。

## Description  @zh-Hans

指计算机上存储内容的任意对象。

内容的类型可以通过可选地contentType 属性提供。

fileKind 属性可以设置为directory ，用以表示文件代表的目录和该目录中的所有内容。
