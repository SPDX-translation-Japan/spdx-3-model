SPDX-License-Identifier: Community-Spec-1.0

# LifecycleScopeType

## Summary

Provide an enumerated set of lifecycle phases that can provide context to relationships.

## Description

This enumeration summarizes common phases when dependency and other relationships, have different implications, based on their context.  For example,  a build dependency, may have different implications than a operational dependency.

## Metadata

- name: LifecycleScopeType

## Entries

- design: A relationship has specific context implications during an element's design.
- development: A relationship has specific context implications during development phase of an element.
- build: A relationship has specific context implications during an element's build phase, during development.
- test: A relationship has specific context implications during an element's testing phase, during development.
- runtime: A relationship has specific context implications during the execution phase of an element.
- other: A relationship has other specific context information necessary to capture that the above set of enumerations does not handle.

## Summary @zh-Hans

提供一组生命周期阶段的枚举来为关系提供上下文。

## Description @zh-Hans

这组枚举总结了在依赖关系和其他关系中常见的阶段，这些阶段根据上下文具有不同的含义。例如，构建依赖关系可能与操作依赖关系具有不同的含义。

## Entries @zh-Hans

- design: 在元素的设计阶段，关系具有特定的上下文含义。
- development: 在元素的开发阶段，关系具有特定的上下文含义。
- build: 在元素开发期间的构建阶段，关系具有特定的上下文含义。
- test: 在元素开发期间的测试阶段，关系具有特定的上下文含义。
- runtime: 在元素的执行阶段，关系具有特定的上下文含义。
- other: 关系具有其他特定的必要上下文信息，而上述枚举未能覆盖这些信息。
