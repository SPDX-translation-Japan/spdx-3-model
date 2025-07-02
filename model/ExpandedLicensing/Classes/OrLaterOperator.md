SPDX-License-Identifier: Community-Spec-1.0

# OrLaterOperator

## Summary

Portion of an AnyLicenseInfo representing this version, or any later version,
of the indicated License.

## Description

An OrLaterOperator indicates that this portion of the AnyLicenseInfo
represents either (1) the specified version of the corresponding License, or
(2) any later version of that License. It is represented in the SPDX License
Expression Syntax by the `+` operator.

It is context-dependent, and unspecified by SPDX, as to what constitutes a
"later version" of any particular License. Some Licenses may not be versioned,
or may not have clearly-defined ordering for versions. The consumer of SPDX
data will need to determine for themselves what meaning to attribute to a
"later version" operator for a particular License.

## Metadata

- name: OrLaterOperator
- SubclassOf: ExtendableLicense
- Instantiability: Concrete

## Properties

- subjectLicense
  - type: License
  - minCount: 1
  - maxCount: 1

## Summary @zh-Hans

`AnyLicenseInfo`的一部分，表示已声明许可证的此版本或任何更高版本。

## Description @zh-Hans

或操作符(`OrLaterOperator`) 表示，`AnyLicenseInfo`的一部分是指：(1) 相应许可证（`License`）的指定版本，或 (2) 该许可证（`License`）的任何更新版本。它在SPDX许可证表达式中通过`+`运算符来体现。

任何特定许可证（`License`）的“后续版本”，视上下文而定，且SPDX未对此明确。某些许可证（`License`）可能没有具体版本，或者可能没有明确定义的版本顺序。SPDX数据的用户需要自行决定对特定许可证（`License`）的“后续版本”运算符赋予何种含义。
