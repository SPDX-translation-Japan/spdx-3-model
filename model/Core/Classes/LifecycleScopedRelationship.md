SPDX-License-Identifier: Community-Spec-1.0

# LifecycleScopedRelationship

## Summary

Provide context for a relationship that occurs in the lifecycle.

## Description

Certain relationships are sensitive to where they occur in the lifecycle.  This parameter lets us avoid a proliferation of relationships, by parameterizing this context information for a relationship.

## Metadata

- name: LifecycleScopedRelationship
- SubclassOf: Relationship
- Instantiability: Concrete

## Properties

- scope
  - type: LifecycleScopeType
  - minCount: 0
  - maxCount: 1

## Summary @ja

ライフサイクル内で発生する関係に文脈を与える。

## Description @ja

一部の関係は、ライフサイクルのどこで発生するかに依存する。このパラメータにより、関係の文脈情報をパラメータ化することで、関係の種類が不必要に増えるのを防ぐ。
