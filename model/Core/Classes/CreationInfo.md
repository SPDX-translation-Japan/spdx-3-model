SPDX-License-Identifier: Community-Spec-1.0

# CreationInfo

## Summary

Provides information about the creation of the Element.

## Description

The CreationInfo provides information about who created the Element, and when
and how it was created.

The dateTime created is often the date of last change
(e.g., a git commit date), not the date when the SPDX data was created, as
doing so supports reproducible builds.

## Metadata

- name: CreationInfo
- Instantiability: Concrete

## Properties

- specVersion
  - type: SemVer
  - minCount: 1
  - maxCount: 1
- comment
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- created
  - type: DateTime
  - minCount: 1
  - maxCount: 1
- createdBy
  - type: Agent
  - minCount: 1
- createdUsing
  - type: Tool
  - minCount: 0

## Summary @ja

要素の作成に関する情報を提供する。

## Description @ja

CreationInfo は、要素を誰が、いつ、どのように作成したかに関する情報を提供する。作成日時は多くの場合、SPDX データが作成された日付ではなく、最終変更日（例: git のコミット日）である。これにより再現可能なビルドを支援する。
