SPDX-License-Identifier: Community-Spec-1.0

# CvssSeverityType

## Summary

Specifies the CVSS base, temporal, threat, or environmental severity type.

## Description

CvssSeverityType specifies the Common Vulnerability Scoring System (CVSS)
severity type, defined in the CVSS specifications as the textual representation
of the numeric CVSS score.

The severity type entries are inclusive of and applicable to enumerations found
in
[Common Vulnerability Scoring System v3.0: Specification Document](https://www.first.org/cvss/v3.0/specification-document#Qualitative-Severity-Rating-Scale)
and
[Common Vulnerability Scoring System version 4.0: Specification Document](https://www.first.org/cvss/v4.0/specification-document#Qualitative-Severity-Rating-Scale).

CvssSeverityType is a mandatory field because baseSeverity is required in the
[CVSS 3.0 schema](https://www.first.org/cvss/cvss-v3.0.json),
[CVSS 3.1 schema](https://www.first.org/cvss/cvss-v3.1.json), and
[CVSS 4.0 schema](https://www.first.org/cvss/cvss-v4.0.json).

The field can be used to document the base, temporal, threat, or environmental
severity.

## Metadata

- name: CvssSeverityType

## Entries

- critical: When a CVSS score is between 9.0 - 10.0.
- high: When a CVSS score is between 7.0 - 8.9.
- medium: When a CVSS score is between 4.0 - 6.9.
- low: When a CVSS score is between 0.1 - 3.9.
- none: When a CVSS score is 0.0.

## Summary @zh-Hans

指定CVSS基本、时态、威胁或环境严重性级别。

## Description @zh-Hans

`CvssSeverityType`指定通用漏洞评分系统（CVSS）严重级别，在CVSS规范中定义为CVSS分数的文本表示。

严重性级别条目包含并适用于[CVSS v3.0 规范文档](https://www.first.org/cvss/v3.0/specification-document#Qualitative-Severity-Rating-Scale)和[CVSS v4.0 规范文档](https://www.first.org/cvss/v4.0/specification-document#Qualitative-Severity-Rating-Scale)中的列举。

`CvssSeverityType`是必填字段，因为[CVSS 3.0 模式](https://www.first.org/cvss/cvss-v3.0.json)、[CVSS 3.1 模式](https://www.first.org/cvss/cvss-v3.1.json)和[CVSS 4.0 模式](https://www.first.org/cvss/cvss-v4.0.json)中需要`baseSeverity`。

此字段可用于记录基本、时态、威胁或环境严重性级别。

## Entries @zh-Hans

- critical: CVSS分数在9.0到10.0之间
- high: CVSS分数在7.0到8.9之间
- medium: CVSS分数在4.0到6.9之间
- low: CVSS分数在0.1到3.9之间
- none: CVSS分数为0.0

## Summary @ja

CVSS の Base、Temporal、Threat、または Environmental の深刻度タイプを指定する。

## Description @ja

**CvssSeverityType** は、Common Vulnerability Scoring System（CVSS）における深刻度タイプを指定する。
これは、CVSS 仕様で定義されている数値スコアの文字列表現として定義されている。

深刻度タイプのエントリは、以下の文書に示されている列挙値を含み、それらに適用できる。
[Common Vulnerability Scoring System v3.0: Specification Document](https://www.first.org/cvss/v3.0/specification-document#Qualitative-Severity-Rating-Scale) および
[Common Vulnerability Scoring System version 4.0: Specification Document](https://www.first.org/cvss/v4.0/specification-document#Qualitative-Severity-Rating-Scale)。

CvssSeverityType** は必須フィールドである。これは、これらスキーマで baseSeverity が必須項目として定義されているためである。
[CVSS 3.0 schema](https://www.first.org/cvss/cvss-v3.0.json)、
[CVSS 3.1 schema](https://www.first.org/cvss/cvss-v3.1.json)、
[CVSS 4.0 schema](https://www.first.org/cvss/cvss-v4.0.json)。

このフィールドは、Base、Temporal、Threat、または Environmental の深刻度を文書化するために使用できる。

## Entries @ja

- critical: CVSSスコアが 9.0 - 10.0 の間。
- high: CVSSスコアが between 7.0 - 8.9 の間。
- medium: CVSSスコアが between 4.0 - 6.9 の間。
- low: CVSSスコアが between 0.1 - 3.9 の間。
- none: CVSSスコアが 0.0。
