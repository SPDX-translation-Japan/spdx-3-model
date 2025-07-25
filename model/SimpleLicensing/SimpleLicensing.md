SPDX-License-Identifier: Community-Spec-1.0

# SimpleLicensing

## Summary

Additional metadata relating to software licensing.

## Description

The SimpleLicensing profile provides classes and properties to express licenses
as a [license expression](../../annexes/spdx-license-expressions.md) string.

It also provides the base abstract class, AnyLicenseInfo, used for references
to license information.

The SimpleLicensingText class provides a place to record any license text found
that does not match a license on the
[SPDX License List](https://spdx.org/licenses/).

The ExpandedLicensing profile can be used to represent the complete parsed
license expressions.

## Metadata

- id: https://spdx.org/rdf/3.0/terms/SimpleLicensing
- name: SimpleLicensing

## Summary @zh-Hans

与软件许可相关的附加元数据。

## Description @zh-Hans

`SimpleLicensing`配置文件提供了以[许可证表达式](../../annexes/spdx-license-expressions.md)字符串来表达许可表达式的类和属性。

它还提供了一个基本的抽象类`AnyLicenseInfo`，用于引用许可信息。

`SimpleLicensingText`类为记录与[SPDX许可证列表](https://spdx.org/licenses/)上许可证不匹配的许可证文本提供了的位置。

`ExpandedLicensing`配置文件可用于表示完全解析的许可证表达式。
