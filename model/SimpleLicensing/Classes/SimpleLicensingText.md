SPDX-License-Identifier: Community-Spec-1.0

# SimpleLicensingText

## Summary

A license or addition that is not listed on the SPDX License List.

## Description

A SimpleLicensingText represents a License or Addition that is not listed on
the [SPDX License List](https://spdx.org/licenses),
and is therefore defined by an SPDX data creator.

## Metadata

- name: SimpleLicensingText
- SubclassOf: /Core/Element
- Instantiability: Concrete

## Properties

- licenseText
  - type: xsd:string
  - minCount: 1
  - maxCount: 1

## Summary @zh-Hans

未在SPDX许可证列表中列出的许可证或附加内容。

## Description @zh-Hans

单一许可证文本（`SimpleLicensingText`）表示SPDX许可证列表中未列出因而由SPDX数据创建者定义的许可证（`License`）或附加项（`Addition`）。
