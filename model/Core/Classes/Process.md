SPDX-License-Identifier: Community-Spec-1.0

# Process

## Summary
Class that describes a process.

## Description
Processes are composed of systematic task(s) required to achieve a goal.

## Metadata
- name: Process
- SubclassOf: /Core/Artifact
- Instantiability: Abstract

## Properties
- version
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- rationale 
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- status
  - type: DocumentState
  - minCount: 0
  - maxCount: 1
