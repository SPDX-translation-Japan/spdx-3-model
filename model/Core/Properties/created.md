SPDX-License-Identifier: Community-Spec-1.0

# created

## Summary

Identifies when the Element was originally created.

## Description

Created is a date that identifies when the Element was originally created.

The time stamp can serve as an indication as to whether the analysis needs to
be updated.

This is often the date of last change (e.g., a git commit date), not the date
when the SPDX data was created, as doing so supports reproducible builds.

## Metadata

- name: created
- Nature: DataProperty
- Range: DateTime

## Summary @ja

要素が最初に作成された日時を識別する。

## Description @ja

created は要素が最初に作成された日時を識別する日付である。  
このタイムスタンプは分析を更新する必要があるかどうかの目安となる。  
これは多くの場合、SPDX データが作成された日付ではなく、最終変更日（例: git のコミット日）であり、再現可能ビルドを支援する。  
