SPDX-License-Identifier: Community-Spec-1.0

# specVersion

## Summary

Provides a reference number that can be used to understand how to parse and
interpret an Element.

## Description

The specVersion provides a reference number that can be used to understand how
to parse and interpret an Element.
It will enable both future changes to the specification and to support backward
compatibility.

The major version number shall be incremented when incompatible changes between
versions are made (one or more sections are created, modified or deleted).
The minor version number shall be incremented when backwards compatible changes
are made.
The patch version number shall be incremented when backward compatible bug
fixes are made.

Here, parties exchanging information in accordance with the SPDX specification
need to provide 100% transparency as to which SPDX specification version such
information is conforming to.

## Metadata

- name: specVersion
- Nature: DataProperty
- Range: SemVer

## Summary @ja

要素の解釈およびパース方法を理解するために用いられる参照番号を提供する。

## Description @ja

specVersion は、要素をどのように解釈しパースするかを理解するために用いられる参照番号を提供する。これは将来の仕様変更を可能にし、後方互換性の維持にも資する。

非互換な変更（1つ以上のセクションの新設・変更・削除）が行われた場合はメジャーバージョン番号をインクリメントする。後方互換な変更が行われた場合はマイナーバージョン番号をインクリメントする。後方互換なバグ修正が行われた場合はパッチバージョン番号をインクリメントする。

SPDX 仕様に従って情報をやり取りする当事者は、当該情報が準拠する SPDX 仕様のバージョンについて、100% の透明性を提供しなければならない。
