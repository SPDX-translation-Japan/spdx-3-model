SPDX-License-Identifier: Community-Spec-1.0

# PositiveIntegerRange

## Summary

A tuple of two positive integers that define a range.

## Description

PositiveIntegerRange is a tuple of two positive integers that define a range.
"beginIntegerRange" must be less than or equal to "endIntegerRange".

## Metadata

- name: PositiveIntegerRange
- SubclassOf: none
- Instantiability: Concrete

## Properties

- beginIntegerRange
  - type: xsd:positiveInteger
  - minCount: 1
  - maxCount: 1
- endIntegerRange
  - type: xsd:positiveInteger
  - minCount: 1
  - maxCount: 1

## Summary @ja

範囲を定義する二つの正の整数の組。

## Description @ja

PositiveIntegerRange は、範囲を定義する二つの正の整数の組である。"beginIntegerRange" は "endIntegerRange" 以下でなければならない。
