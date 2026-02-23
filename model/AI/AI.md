SPDX-License-Identifier: Community-Spec-1.0

# AI

## Summary

The AI profile is designed to provide a standardized way of documenting and
sharing information about AI software packages (i.e. systems).

## Description

The AI namespace defines a set of concepts and data elements related to AI
system and model artifacts. These artifacts are the tangible outputs of the AI
development process, such as software packages, models, and datasets.

## Metadata

- id: https://spdx.org/rdf/3.0/terms/AI
- name: AI

## Profile conformance

For an element collection to be conformant with this profile,
the following has to hold:

1. for every `/AI/AIPackage` there MUST exist exactly one `/Core/Relationship`
   of type `hasConcludedLicense` having that element as its `from` property
   and a `/SimpleLicensing/AnyLicenseInfo` as its `to` property.
2. for every `/AI/AIPackage` there MUST exist exactly one `/Core/Relationship`
   of type `hasDeclaredLicense` having that element as its `from` property
   and a `/SimpleLicensing/AnyLicenseInfo` as its `to` property.

## Summary @zh-Hans

`AI`配置文件旨在提供一种标准化的方法，用于记录和共享有关AI软件包（即系统）的信息。

## Description @zh-Hans

`AI`命名空间定义了一组与AI系统和模型工件相关的概念和数据元素。这些工件是AI开发过程的有形产出，如软件包、模型和数据集。

## Profile conformance @zh-Hans

为了使元素集合符合此配置文件，以下条件必须满足：

1. 对于每个`/AI/AIPackage`，**必须**存在一个`/Core/Relationship`类型为`hasConcludedLicense`的元素，该元素的`from`属性是该元素，并且其`to`属性是`/SimpleLicensing/AnyLicenseInfo`。
2. 对于每个`/AI/AIPackage`，**必须**存在一个`/Core/Relationship`类型为`hasDeclaredLicense`的元素，该元素的`from`属性是该元素，并且其`to`属性是`/SimpleLicensing/AnyLicenseInfo`。

## Summary @ja

AIプロファイルは、AIソフトウェアパッケージ（すなわちシステム）に関する情報を文書化し、共有するための標準化された方法を提供するように設計されている。

## Description @ja

AI名前空間は、AIシステムおよびモデルの成果物に関連する一連の概念とデータ要素を定義している。これらの成果物は、ソフトウェアパッケージ、モデル、データセットといった、AI開発プロセスの具体的なアウトプットである。

## Profile conformance @ja

ある要素コレクションが本プロファイルに準拠するためには、以下の条件を満たさなければならない：

1. すべての `/AI/AIPackage` に対して、型が `hasConcludedLicense` である `/Core/Relationship` が正確に1つ存在しなければならず、その関係の `from` プロパティには当該要素が、`to` プロパティには `/SimpleLicensing/AnyLicenseInfo` が指定されていなければならない。
2. すべての `/AI/AIPackage` に対して、型が `hasDeclaredLicense` である `/Core/Relationship` が正確に1つ存在しなければならず、その関係の `from` プロパティには当該要素が、`to` プロパティには `/SimpleLicensing/AnyLicenseInfo` が指定されていなければならない。
