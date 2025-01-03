SPDX-License-Identifier: Community-Spec-1.0

# standardLicenseTemplate

## Summary

Identifies the full text of a License, in SPDX templating format.

## Description

A standardLicenseTemplate contains a license template which describes sections
of the License text which can be varied.

See the Legacy Text Template format section of the
[SPDX License List Matching Guidelines](../../../annexes/license-matching-guidelines-and-templates.md)
for format information.

It is recommended to use [licenseXml](./licenseXml.md) instead, as it can
capture all the text and metadata associated with a license.

## Metadata

- name: standardLicenseTemplate
- Nature: DataProperty
- Range: xsd:string

## Summary @zh-Hans

以SPDX模板格式标识许可证（`License`）的全文。

## Description @zh-Hans

标准许可证模版（`standardLicenseTemplate`）包含描述许可证（`License`）文本可以更改的部分的许可证模版。

请参阅[SPDX许可证列表匹配指南](../../../ annexes/license-matching-guidelines-and-templates..md)，以获得格式信息。

建议改用[licenseXml](./licenseXml.md)，因为可以获得与许可证关联的所有文本和元数据。
