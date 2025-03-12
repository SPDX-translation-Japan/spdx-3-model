SPDX-License-Identifier: Community-Spec-1.0

# SoftwareArtifact

## Summary

A distinct article or unit related to Software.

## Description

A software artifact is a distinct article or unit related to software
such as a package, a file, or a snippet.

## Metadata

- name: SoftwareArtifact
- SubclassOf: /Core/Artifact
- Instantiability: Abstract

## Properties

- primaryPurpose
  - type: SoftwarePurpose
  - minCount: 0
  - maxCount: 1
- additionalPurpose
  - type: SoftwarePurpose
  - minCount: 0
- copyrightText
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- attributionText
  - type: xsd:string
  - minCount: 0
- contentIdentifier
  - type: ContentIdentifier
  - minCount: 0

## Summary @zh-Hans

是与软件相关的一个独立条目或单元。

## Description @zh-Hans

软件工件(`SoftwareArtifact`)是与软件相关的一个独立条目或单元。

比如，一个软件包、文件或一个代码片段。
