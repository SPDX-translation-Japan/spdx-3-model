SPDX-License-Identifier: Community-Spec-1.0

# spdxId

## Summary

Identifies an Element to be referenced by other Elements.

## Description

An spdxId uniquely identifies an Element which may thereby be referenced by other Elements.
These references may be internal or external.
While there may be several versions of the same Element, each one needs to be able to be referred to uniquely
so that relationships between Elements can be clearly articulated.

## Metadata

- name: spdxId
- Nature: DataProperty
- Range: xsd:anyURI

## Summary @ja

他の要素から参照される要素を識別する。

## Description @ja

spdxId は要素を一意に識別し、他の要素から参照できるようにする。これらの参照は内部でも外部でもよい。同一の要素に複数のバージョンが存在する場合でも、各バージョンが明確に参照できるように一意である必要がある。
