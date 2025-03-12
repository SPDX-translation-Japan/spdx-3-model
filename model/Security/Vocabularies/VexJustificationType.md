SPDX-License-Identifier: Community-Spec-1.0

# VexJustificationType

## Summary

Specifies the VEX justification type.

## Description

VexJustificationType specifies the type of Vulnerability Exploitability eXchange (VEX) justification.

## Metadata

- name: VexJustificationType

## Entries

- componentNotPresent: The software is not affected because the vulnerable component is not in the product.
- vulnerableCodeNotPresent: The product is not affected because the code underlying the vulnerability is not present in the product.
- vulnerableCodeCannotBeControlledByAdversary: The vulnerable component is present, and the component contains the vulnerable code. However, vulnerable code is used in such a way that an attacker cannot mount any anticipated attack.
- vulnerableCodeNotInExecutePath: The affected code is not reachable through the execution of the code, including non-anticipated states of the product.
- inlineMitigationsAlreadyExist: Built-in inline controls or mitigations prevent an adversary from leveraging the vulnerability.

## Summary @zh-Hans

指定VEX证明类型。

## Description @zh-Hans

`VexJustificationType`指定漏洞可利用性交换（VEX）证明的类型。

## Entries @zh-Hans

- componentNotPresent: 软件未受影响，因为产品中不包含易受攻击的组件。
- vulnerableCodeNotPresent: 产品未受影响，因为产品中不包含导致漏洞的代码。
- vulnerableCodeCannotBeControlledByAdversary: 存在易受攻击的组件，且该组件包含易受攻击的代码，但易受攻击的代码的使用方式使攻击者无法发起预期攻击。
- vulnerableCodeNotInExecutePath: 受影响的代码无法通过代码执行访问，包括产品的非预期状态。
- inlineMitigationsAlreadyExist: 内置的内联控制或缓解措施可防止攻击者利用漏洞。
