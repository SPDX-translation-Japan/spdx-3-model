SPDX-License-Identifier: Community-Spec-1.0

# NoneElement

## Summary

An Individual Value for Element representing a set of Elements with
cardinality (number/count) of zero.

## Description

NoneElement should be used if the SPDX creator desires to assert that
there are NO elements for the given context of use.

For example, a Relationship with
`relationshipType`="ancestorOf",
`from`=Element1,
and `to`=NoneElement
is explicitly expressing an assertion that
Element1 has no descendants.

## Metadata

- name: NoneElement
- type: IndividualElement

## Property Values

- name: "NONE"

## Summary @ja

基数（数）がゼロである要素集合を表す Element の個体値。

## Description @ja

NoneElement は、SPDX 作成者が「与えられた利用コンテキストにおいて要素は存在しない」と明示的に表明する場合に使用されるべきである。  

*例*  
例えば、以下のような Relationship があるとする：  
`relationshipType`="ancestorOf"、  
`from`=Element1、  
`to`=NoneElement。  

この場合、Element1 には子孫が存在しないことを明示的に表現している。  
