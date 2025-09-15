SPDX-License-Identifier: Community-Spec-1.0

# ExternalRef

## Summary

A reference to a resource outside the scope of SPDX-3.0 content related to an Element.

## Description

An External Reference points to a general resource outside the scope of the SPDX-3.0 content
that provides additional context, characteristics or related information about an Element.

## Metadata

- name: ExternalRef
- SubclassOf: none
- Instantiability: Concrete

## Properties

- externalRefType
  - type: ExternalRefType
  - maxCount: 1
- locator
  - type: xsd:string
- contentType
  - type: MediaType
  - maxCount: 1
- comment
  - type: xsd:string
  - maxCount: 1

## Summary @ja

SPDX-3.0 コンテンツのスコープ外にあるリソースへの参照。

## Description @ja

ExternalRef は、SPDX-3.0 コンテンツのスコープ外にあるリソースを指し、Element に関連する追加の文脈や特性、情報を提供する。
