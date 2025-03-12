SPDX-License-Identifier: Community-Spec-1.0

# License

## Summary

Abstract class for the portion of an AnyLicenseInfo representing a license.

## Description

A License represents a license text, whether listed on the
[SPDX License List](https://spdx.org/licenses/)
(ListedLicense) or defined by an SPDX data creator (CustomLicense).

## Metadata

- name: License
- SubclassOf: ExtendableLicense
- Instantiability: Abstract

## Properties

- /SimpleLicensing/licenseText
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- isDeprecatedLicenseId
  - type: xsd:boolean
  - minCount: 0
  - maxCount: 1
- isFsfLibre
  - type: xsd:boolean
  - minCount: 0
  - maxCount: 1
- isOsiApproved
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
- standardLicenseHeader
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- standardLicenseTemplate
  - type: xsd:string
  - minCount: 0
  - maxCount: 1

## Summary @zh-Hans

表示许可证的 `AnyLicenseInfo` 一部分的抽象类。

## Description @zh-Hans

License代表一段许可证文本，或者已在[SPDX License List](https://spdx.org/licenses/)中列出（`ListedLicense`），或者由一个SPDX数据创建者定义（`CustomLicense`）。
