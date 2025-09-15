SPDX-License-Identifier: Community-Spec-1.0

# ExternalIdentifier

## Summary

A reference to a resource identifier defined outside the scope of SPDX-3.0 content that uniquely identifies an Element.

## Description

An ExternalIdentifier is a reference to a resource outside the scope of SPDX-3.0 content
that provides a unique key within an established domain that can uniquely identify an Element.

## Metadata

- name: ExternalIdentifier
- SubclassOf: none
- Instantiability: Concrete

## Properties

- externalIdentifierType
  - type: ExternalIdentifierType
  - minCount: 1
  - maxCount: 1
- identifier
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- comment
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- identifierLocator
  - type: xsd:anyURI
  - minCount: 0
- issuingAuthority
  - type: xsd:string
  - minCount: 0
  - maxCount: 1

## Summary @ja

SPDX-3.0 コンテンツのスコープ外で定義されたリソース識別子への参照であり、要素を一意に識別する。

## Description @ja

ExternalIdentifier は SPDX-3.0 コンテンツのスコープ外のリソースへの参照であり、確立されたドメイン内で一意のキーを提供し、要素を一意に識別することができる。
