SPDX-License-Identifier: Community-Spec-1.0

# Action

## Summary

Class that describes an action that has occurred.

## Description

Action defines an event that has occurred. This is an Abstract Action. 

## Metadata
- name: Action
- SubclassOf: /Core/Artifact
- Instantiability: Abstract

## Properties

- actionStartTime
  - type: /Core/DateTime
  - minCount: 0
  - maxCount: 1
- actionEndTime
  - type: /Core/DateTime
  - minCount: 0
  - maxCount: 1
