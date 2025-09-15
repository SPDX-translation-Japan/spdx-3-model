SPDX-License-Identifier: Community-Spec-1.0

# IntegrityMethod

## Summary

Provides an independently reproducible mechanism that permits verification of a specific Element.

## Description

An IntegrityMethod provides an independently reproducible mechanism that permits verification
of a specific Element that correlates to the data in this SPDX document. This identifier enables
a recipient to determine if anything in the original Element has been changed and eliminates
confusion over which version or modification of a specific Element is referenced.

Please note that different profiles may also provide additional methods for verifying the integrity of specific subclasses of Elements.

## Metadata

- name: IntegrityMethod
- Instantiability: Abstract

## Properties

- comment
  - type: xsd:string
  - maxCount: 1

## Summary @ja

特定の Element を検証可能にする独立して再現可能な仕組みを提供する。

## Description @ja

IntegrityMethod は、SPDX 文書内のデータに対応する特定の Element を検証可能にする独立して再現可能な仕組みを提供する。この識別子により、受信者は元の Element のどの部分が変更されたかを判断でき、参照されるバージョンや修正に関する混乱を防ぐ。異なるプロファイルは、特定の Element サブクラスの完全性を検証する追加の方法を提供する場合もある。
