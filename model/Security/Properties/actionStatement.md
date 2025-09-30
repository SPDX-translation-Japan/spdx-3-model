SPDX-License-Identifier: Community-Spec-1.0

# actionStatement

## Summary

Provides advise on how to mitigate or remediate a vulnerability when a VEX product
is affected by it.

## Description

When an element is referenced with a VexAffectedVulnAssessmentRelationship,
the relationship MUST include one actionStatement that SHOULD describe actions
to remediate or mitigate the vulnerability.

## Metadata

- name: actionStatement
- Nature: DataProperty
- Range: xsd:string

## Summary @zh-Hans

提供关于在VEX产品受漏洞影响时如何缓解或修复漏洞的建议。

## Description @zh-Hans

使用`VexAffectedVulnAssessmentRelationship`引用元素时，**必须**包含一个`actionStatement`，**应当**描述缓解或修复漏洞的措施。

## Summary @ja

VEX 製品が脆弱性の影響を受けている場合に、その脆弱性を軽減または修正する方法についての助言を提供する。

## Description @ja

要素が VexAffectedVulnAssessmentRelationship によって参照される場合、その関係には少なくとも1つの actionStatement を含めなければならない。
この actionStatement には、脆弱性を修正または軽減するためのアクションを記述することが望ましい。
