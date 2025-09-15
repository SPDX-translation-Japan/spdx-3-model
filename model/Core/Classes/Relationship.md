SPDX-License-Identifier: Community-Spec-1.0

# Relationship

## Summary

Describes a relationship between one or more elements.

## Description

A Relationship is a grouping of characteristics unique to an assertion
that one Element is related to one or more other Elements in some way.

To explicitly assert that no such relationships exist, the `to` property
should contain the NoneElement individual and no other elements.

A relationship that contains NoneElement and additional elements in the `to`
property is not valid.

To explicitly assert that no assertions are being made regarding the
existence of such relationships, the `to` property should contain the
NoAssertionElement individual.

## Metadata

- name: Relationship
- SubclassOf: Element
- Instantiability: Concrete

## Properties

- from
  - type: Element
  - minCount: 1
  - maxCount: 1
- to
  - type: Element
  - minCount: 1
- relationshipType
  - type: RelationshipType
  - minCount: 1
  - maxCount: 1
- completeness
  - type: RelationshipCompleteness
  - minCount: 0
  - maxCount: 1
- startTime
  - type: DateTime
  - minCount: 0
  - maxCount: 1
- endTime
  - type: DateTime
  - minCount: 0
  - maxCount: 1

## Summary @ja

1 つ以上の要素間の関係を記述する。

## Description @ja

Relationship は、ある Element が 1 つ以上の他の Element と何らかの形で関係していることを示す主張を特徴づける集合である。  

そのような関係が存在しないことを明示的に表明する場合、`to` プロパティには NoneElement 個体のみを含め、他の要素を含めてはならない。`to` プロパティに NoneElement と追加の要素が含まれる関係は無効である。  

また、そのような関係の存在について何も表明しないことを明示する場合、`to` プロパティには NoAssertionElement 個体を含めるべきである。  