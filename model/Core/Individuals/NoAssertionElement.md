SPDX-License-Identifier: Community-Spec-1.0

# NoAssertionElement

## Summary

An Individual Value for Element representing a set of Elements of unknown
identify or cardinality (number).

## Description

NoAssertionElement should be used if

- the SPDX creator has attempted to but cannot reach a reasonable objective
  determination;
- the SPDX creator has made no attempt to determine this field; or
- the SPDX creator has intentionally provided no information (no meaning should
  be implied by doing so).

For example, a Relationship with
`relationshipType`="ancestorOf",
`from`=Element1,
and
`to`=NoAssertionElement
is explicitly expressing that
no assertion is being made about any potential descendants of Element1.

## Metadata

- name: NoAssertionElement
- type: IndividualElement

## Property Values

- name: "NOASSERTION"


## Summary @ja

識別や基数（数）が不明な要素集合を表す Element の個体値。

## Description @ja

NoAssertionElement は次の場合に使用されるべきである：  

- SPDX 作成者が合理的で客観的な判断を試みたが到達できなかった場合  
- SPDX 作成者がこのフィールドの判断をまったく試みていない場合  
- SPDX 作成者が意図的に情報を提供していない場合（そのことから意味を推測してはならない）  

*例*  
例えば、以下のような Relationship があるとする：  
`relationshipType`="ancestorOf"、  
`from`=Element1、  
`to`=NoAssertionElement。  

この場合、Element1 の子孫に関していかなる主張も行っていないことを明示的に表現している。  