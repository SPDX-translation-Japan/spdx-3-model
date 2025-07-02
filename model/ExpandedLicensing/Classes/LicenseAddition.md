SPDX-License-Identifier: Community-Spec-1.0

# LicenseAddition

## Summary

Abstract class for additional text intended to be added to a License, but
which is not itself a standalone License.

## Description

A LicenseAddition represents text which is intended to be added to a License
as additional text, but which is not itself intended to be a standalone
License.

It may be an exception which is listed on the
[SPDX License Exceptions](https://spdx.org/licenses/exceptions-index.html)
(ListedLicenseException), or may be any other additional text (as an exception
or otherwise) which is defined by an SPDX data creator (CustomLicenseAddition).

## Metadata

- name: LicenseAddition
- SubclassOf: /Core/Element
- Instantiability: Abstract

## Properties

- additionText
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- isDeprecatedAdditionId
  - type: xsd:boolean
  - minCount: 0
  - maxCount: 1
- licenseXml
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- obsoletedBy
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- seeAlso
  - type: xsd:anyURI
- standardAdditionTemplate
  - type: xsd:string
  - minCount: 0
  - maxCount: 1

## Summary @zh-Hans

用于添加到许可证（`License`）中但其本身并非独立的许可证的附加文本的抽象类。

## Description @zh-Hans

许可证附加内容（`LicenseAddition`）表示要将一段文本作为附加文本添加到许可证（`License`）中，但其本身并不旨在成为一个独立的许可证。

它可能是列在[SPDX License Exceptions](https://spdx.org/licenses/exceptions-index.html)中一个例外情况（`(ListedLicenseException`），或也可能是由SPDX数据创建者定义（`CustomLicenseAddition`）的任何其他附加文本（作为例外情况，或者其他情况）。
