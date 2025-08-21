SPDX-License-Identifier: Community-Spec-1.0

# ConjunctiveLicenseSet

## Summary

Portion of an AnyLicenseInfo representing a set of licensing information
where all elements apply.

## Description

A ConjunctiveLicenseSet indicates that _each_ of its subsidiary
AnyLicenseInfos apply. In other words, a ConjunctiveLicenseSet of two or
more licenses represents a licensing situation where _all_ of the specified
licenses are to be complied with. It is represented in the SPDX License
Expression Syntax by the `AND` operator.

It is syntactically correct to specify a ConjunctiveLicenseSet where the
subsidiary AnyLicenseInfos may be "incompatible" according to a particular
interpretation of the corresponding Licenses.
The
[SPDX License Expression Syntax](../../../annexes/spdx-license-expressions.md)
does not take into account interpretation of license texts, which is
left to the consumer of SPDX data to determine for themselves.

## Metadata

- name: ConjunctiveLicenseSet
- SubclassOf: /SimpleLicensing/AnyLicenseInfo
- Instantiability: Concrete

## Properties

- member
  - type: /SimpleLicensing/AnyLicenseInfo
  - minCount: 2

## Summary @zh-Hans

`AnyLicenseInfo`的一部分，指所有元素都需要遵守的许可信息集。

## Description @zh-Hans

联合许可证集（`ConjunctiveLicenseSet`）表示 *每个* 附属`AnyLicenseInfos`都需要遵守。换句话说，一个由两个或更多许可证组成的`ConjunctiveLicenseSet`代表了一种许可情况，即 *所有* 特定的许可证都需要遵守。它在SPDX许可证表达式语法中通过`AND`运算符来表示。

语法上正确的做法是指定一个`ConjunctiveLicenseSet`，其中的附属`AnyLicenseInfos`可以根据对相应许可证的特定解释而 “不兼容”。

[SPDX License Expression Syntax](../../../annexes/spdx-license-expressions.md)没有考虑到许可证文本的解释，而是将其留给用户自行决定。
