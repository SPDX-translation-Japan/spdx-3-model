SPDX-License-Identifier: Community-Spec-1.0

# Extension

## Summary

A characterization of some aspect of an Element that is associated with the Element in a generalized fashion.

## Description

An Extension is a characterization of some aspect of an Element that is associated with the Element in a generalized fashion.

Rather than being associated with a particular Element through the typical use of a purpose-specific object property an Extension is associated with the Element it characterizes using a single common generalized object property.

This approach serves multiple purposes:

1. Support profile-based extended characterization of Elements. Enables specification and expression of Element characterization extensions within any profile and namespace of SPDX without requiring changes to other profiles or namespaces and without requiring local subclassing of remote classes (which could inhibit ecosystem interoperability in some cases).

2. Support extension of SPDX by adopting individuals or communities with Element characterization details uniquely specialized to their particular context. Enables adopting individuals or communities to utilize SPDX expressive capabilities along with expressing more arcane Element characterization details specific to them and not appropriate for standardization across SPDX.

3. Support structured capture of expressive solutions for gaps in SPDX coverage from real-world use. Enables adopting individuals or communities to express Element characterization details they require that are not currently defined in SPDX but likely should be. Enables a practical pipeline that:

    - identifies gaps in SPDX that should be filled,
    - expresses solutions to those gaps in a way that allows the identifying adopters to use the extended solutions with SPDX and does not conflict with current SPDX,
    - can be clearly detected among the SPDX content exchange ecosystem,
    - provides a clear and structured definition of gap solution that can be used as submission for revision to SPDX standard

## Metadata

- name: Extension
- Instantiability: Abstract

## Summary @zh-Hans

`Element`某个方面的特征描述，以广义的方式与`Element`关联。

## Description @zh-Hans

`Extension`是对某个`Element`某个方面的特征描述，以广义的方式与该`Element`关联。

`Extension`并不是通过特定目的的对象属性与某个特定`Element`关联，而是通过一个共同的广义对象属性与它所描述的`Element`关联。

此方法有多种用途：

1. 支持基于配置文件的`Element`扩展特征描述。允许在任何SPDX配置文件和命名空间内指定和表达`Element`特征描述扩展，无需对其他配置文件或命名空间进行更改，也无需对远程类进行本地子类化（在某些情况下可能会阻碍生态系统的互操作性）。

2. 通过采用具有特定上下文的`Element`特征细节的个人或社区，支持SPDX的扩展。这使得这些个人或社区能够利用SPDX的表达能力，同时表达更专业的`Element`特征化细节，这些细节不适合在SPDX中进行标准化。

3. 支持结构化捕捉现实应用中SPDX未覆盖的表达方案。允许采用的个人或社区表达他们所需的`Element`特征化细节，这些细节目前在SPDX中尚未定义，但应该被定义。实现一个实用的流水线，能够：

    - 识别SPDX中需要填补的缺口，
    - 提供以某种方式表达这些缺口的方案，使采用者能够在不与当前SPDX冲突的情况下使用扩展方案，
    - 在SPDX内容交换生态系统中清晰识别，
    - 为缺口方案提供一个清晰、结构化的定义，可提交作为对SPDX标准的修订。
