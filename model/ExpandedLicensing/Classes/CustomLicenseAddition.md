SPDX-License-Identifier: Community-Spec-1.0

# CustomLicenseAddition

## Summary

A license addition that is not listed on the SPDX Exceptions List.

## Description

A CustomLicenseAddition represents an addition to a License that is not listed
on the
[SPDX License Exceptions](https://spdx.org/licenses/exceptions-index.html),
and is therefore defined by an SPDX data creator.

It is intended to represent additional language which is meant to be added to
a License, but which is not itself a standalone License.

## Metadata

- name: CustomLicenseAddition
- SubclassOf: LicenseAddition
- Instantiability: Concrete

## Summary @zh-Hans

未在SPDX例外清单中列出的许可证附加内容。

## Description @zh-Hans

自定义许可证附加内容（`CustomLicenseAddition`）表示未在[SPDX License Exceptions](https://spdx.org/licenses/exceptions-index.html)中列出因而由SPDX数据创建者定义的许可证附加信息。

它是指附加语言，用于添加到许可证（`License`）中，但其本身并不是独立的许可证。
