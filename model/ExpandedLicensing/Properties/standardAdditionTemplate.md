SPDX-License-Identifier: Community-Spec-1.0

# standardAdditionTemplate

## Summary

Identifies the full text of a LicenseAddition, in SPDX templating format.

## Description

A standardAdditionTemplate contains a license addition template which describes
sections of the LicenseAddition text which can be varied.

See the Legacy Text Template format section of the
[SPDX License List Matching Guidelines](../../../annexes/license-matching-guidelines-and-templates.md)
for format information.

It is recommended to use [licenseXml](./licenseXml.md) instead, as it can
capture all the text and metadata associated with a license.

## Metadata

- name: standardAdditionTemplate
- Nature: DataProperty
- Range: xsd:string

## Summary @zh-Hans

以SPDX模板格式，标识许可证附加内容（`LicenseAddition`）的全文。

## Description @zh-Hans

标准附加内容模版（`standardAdditionTemplate`）包含许可证附加内容的模版，该模板描述了许可证附加内容（`LicenseAddition`）文本中可以更改的部分。

请参阅[SPDX许可证列表匹配指南](../../../annexes/license-matching-guidelines-and-templates.md) 的“旧版文本模板格式”这个部分，以获取格式信息。

建议使用[licenseXml](./licenseXml.md)作为替代，因为可以获取与许可证关联的所有文本和元数据。
