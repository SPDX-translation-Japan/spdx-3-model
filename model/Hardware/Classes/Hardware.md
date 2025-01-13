SPDX-License-Identifier: Community-Spec-1.0

# Hardware

## Summary
Class that describes a instance of Hardware.

## Description
A hardware artifact is a distinct unit related to hardware.

## Metadata
- name: Hardware
- SubclassOf: /Core/Element
- Instantiability: Abstract

## Properties
- organizationalEntity
  - type: /Core/Organization
  - minCount: 1
  - maxCount: 1
- version
  - type: xsd:string
  - maxCount: 1
- partNumber
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- releaseDate
  - type: /Core/DateTime
  - maxCount: 1
- serialNumber
  - type: xsd:string
  - maxCount: 1
- batchNumber 
  - type: xsd:string
  - maxCount: 1
- informationElementList 
  - type:/Core/DictionaryEntry
