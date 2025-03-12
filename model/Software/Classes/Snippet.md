SPDX-License-Identifier: Community-Spec-1.0

# Snippet

## Summary

Describes a certain part of a file.

## Description

A Snippet describes a certain part of a file and can be used when the file is
known to have some content that has been included from another original source.

Snippets are useful for denoting when part of a file may have been originally
created under another license or copied from a place with a known
vulnerability.

## Metadata

- name: Snippet
- SubclassOf: /Software/SoftwareArtifact

## Properties

- byteRange
  - type: /Core/PositiveIntegerRange
  - minCount: 0
  - maxCount: 1
- lineRange
  - type: /Core/PositiveIntegerRange
  - minCount: 0
  - maxCount: 1
- snippetFromFile
  - type: File
  - minCount: 1
  - maxCount: 1

## Summary @zh-Hans

代码片段用于描述文件的某一部分。

## Description @zh-Hans

代码片段(`Snippet`)用于描述文件的某一部分,可以用于当文件中包含来自另一个原始来源的内容的场景。

代码片段有助于标明文件的某部分可最初可能是在另一个许可下创建的，或者从已知存在漏洞的地方复制而来。
