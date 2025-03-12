SPDX-License-Identifier: Community-Spec-1.0

# ListedLicenseException

## Summary

A license exception that is listed on the SPDX Exceptions list.

## Description

A ListedLicenseException represents an exception to a License (in other words,
an exception to a license condition or an additional permission beyond those
granted in a License) which is listed on the
[SPDX License Exceptions](https://spdx.org/licenses/exceptions-index.html).

## Metadata

- name: ListedLicenseException
- SubclassOf: LicenseAddition
- Instantiability: Concrete

## Properties

- deprecatedVersion
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- listVersionAdded
  - type: xsd:string
  - minCount: 0
  - maxCount: 1

## Summary @zh-Hans

已在SPDX许可证例外列表中列出的许可证例外情形。

## Description @zh-Hans

已列许可证例外（`ListedLicenseException`）表示，列在[SPDX License Exceptions](https://spdx.org/licenses/exceptions-index.html)中的许可证（`License`）的例外情况（换句话说，许可条件的例外情况，或超出这些许可条件的额外许可）
