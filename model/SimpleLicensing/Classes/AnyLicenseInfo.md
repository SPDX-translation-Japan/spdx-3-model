SPDX-License-Identifier: Community-Spec-1.0

# AnyLicenseInfo

## Summary

Abstract class representing a license combination consisting of one or more licenses.

## Description

AnyLicenseInfo is
an abstract class representing a license combination consisting of one or more
licenses (optionally including additional text), which may be combined
according to the
[SPDX license expression syntax](../../../annexes/spdx-license-expressions.md).

An AnyLicenseInfo is used by licensing properties of software artifacts.

It can be:

- a NoneLicense;
- a NoAssertionLicense;
- a single license (either on the
  [SPDX License List](https://spdx.org/licenses/) or
  [a custom-defined license](../../ExpandedLicensing/Classes/CustomLicense.md));
- a single license with an "or later" operator applied;
- the foregoing with additional text applied; or
- a set of licenses combined by applying "AND" and "OR" operators recursively.

## Metadata

- name: AnyLicenseInfo
- SubclassOf: /Core/Element
- Instantiability: Abstract

## Summary @zh-Hans

表示一个或多个许可证组合的抽象类。

## Description @zh-Hans

`AnyLicenseInfo`是一个抽象类，表示由一个或多个许可证（可选包括附加文本）组成的许可证组合，这些许可证可根据[SPDX许可证表达式语法](../../../annexes/spdx-license-expressions.md)进行组合。

`AnyLicenseInfo`可用于软件工件的许可属性。

它可以是

- `NoneLicense`；
- `NoAssertionLicense`；
- （在[SPDX许可证列表](https://spdx.org/licenses/)或[自定义许可证](../../ExpandedLicensing/Classes/CustomLicense.md)）的单一许可证；
- 应用了“or later”操作符的单一许可证；
- 应用了附加文本的上述许可证；或
- 通过递归应用“AND”和“OR”运算符组合的许可证集。
