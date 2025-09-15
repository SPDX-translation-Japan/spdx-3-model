SPDX-License-Identifier: Community-Spec-1.0

# SpdxDocument

## Summary

A collection of SPDX Elements that could potentially be serialized.

## Description

The SpdxDocument provides a convenient way to express information about
collections of SPDX Elements that could potentially be serialized as complete
units (e.g., all in-scope SPDX data within a single JSON-LD file).

SpdxDocument is independent of any particular serialization format or instance.

Information we wish to preserve about a specific instance of serialization of
this SPDX content is NOT expressed using the SpdxDocument but rather using an
associated Artifact representing a particular instance of SPDX data physical
serialization.

Any instance of serialization of SPDX data MUST NOT contain more than one
SpdxDocument element definition.

## Metadata

- name: SpdxDocument
- SubclassOf: ElementCollection
- Instantiability: Concrete

## Properties

- import
  - type: ExternalMap
- namespaceMap
  - type: NamespaceMap
- dataLicense
  - type: /SimpleLicensing/AnyLicenseInfo
  - maxCount: 1

## Summary @ja

シリアライズ可能な SPDX 要素の集合。

## Description @ja

SpdxDocument は、完全な単位としてシリアライズ可能な SPDX 要素の集合に関する情報を表現する便利な方法を提供する。例えば、単一の JSON-LD ファイル内に含まれるすべての SPDX データなどが対象となる。  

SpdxDocument 自体は、特定のシリアライズ形式やそのインスタンスには依存しない。  

この SPDX コンテンツの特定のシリアライズインスタンスについて保持すべき情報は SpdxDocument では表現されず、むしろ SPDX データの物理的なシリアライズの特定インスタンスを表す関連する Artifact を用いて表現される。  

SPDX データのシリアライズインスタンスはいかなる場合でも、複数の SpdxDocument 要素定義を含んではならない。  