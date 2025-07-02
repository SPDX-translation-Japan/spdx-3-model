SPDX-License-Identifier: Community-Spec-1.0

# ListedLicense

## Summary

A license that is listed on the SPDX License List.

## Description

A ListedLicense represents a License that is listed on the
[SPDX License List](https://spdx.org/licenses).

## Metadata

- name: ListedLicense
- SubclassOf: License
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

在SPDX许可证列表中列出的许可证。

## Description @zh-Hans

`ListedLicense`表示已在[SPDX License List](https://spdx.org/licenses)列出的许可证。
