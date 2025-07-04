SPDX-License-Identifier: Community-Spec-1.0

# DisjunctiveLicenseSet

## Summary

Portion of an AnyLicenseInfo representing a set of licensing information where
only one of the elements applies.

## Description

A DisjunctiveLicenseSet indicates that _only one_ of its subsidiary
AnyLicenseInfos is required to apply. In other words, a DisjunctiveLicenseSet
of two or more licenses represents a licensing situation where _only one_ of
the specified licenses are to be complied with.

A consumer of SPDX data would typically understand this to permit the recipient
of the licensed content to choose which of the corresponding license they would
prefer to use. It is represented in the SPDX License Expression Syntax by the
`OR` operator.

## Metadata

- name: DisjunctiveLicenseSet
- SubclassOf: /SimpleLicensing/AnyLicenseInfo
- Instantiability: Concrete

## Properties

- member
  - type: /SimpleLicensing/AnyLicenseInfo
  - minCount: 2

## Summary @zh-Hans

`AnyLicenseInfo`的一部分，指仅有一个元素需要遵守的许可信息集。

## Description @zh-Hans

分离许可证集（`DisjunctiveLicenseSet`）表示 *仅有一个* 附属`AnyLicenseInfos` 需要遵守。换句话说，两个或多个许可证的`DisjunctiveLicenseSet`代表一种许可情况，即 *仅有一个* 特定的许可证应遵守。

SPDX数据的用户一般认为应该允许被许可的内容的接收者选择他们更喜欢使用哪个对应许可证。它在SPDX许可证表达式语法中通过`OR`运算符来表示。
