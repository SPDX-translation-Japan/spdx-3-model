SPDX-License-Identifier: Community-Spec-1.0

# profileConformance

## Summary

Describes one a profile which the creator of this ElementCollection intends to
conform to.

## Description

Describes a profile to which the creator of this ElementCollection intends to
conform.

The profileConformance will apply to all Elements contained within the
collection as well as the collection itself.

Conformance to a profile is defined by the additional restrictions documented
in the profile specific documentation and schema files.

Use of this property allows the creator of an ElementCollection to communicate
to consumers their intent to adhere to the profile additional restrictions.

The profileConformance has a default value of "core" if no other
profileConformance is specified since all ElementCollections and Element must
adhere to the Core profile.

## Metadata

- name: profileConformance
- Nature: ObjectProperty
- Range: ProfileIdentifierType

## Summary @ja

この ElementCollection の作成者が準拠しようと意図するプロファイルを記述する。

## Description @ja

ElementCollection の作成者が準拠しようと意図するプロファイルを記述する。  

profileConformance はコレクション内のすべての Element とコレクション自体に適用される。  

プロファイルへの準拠は、プロファイル固有の文書やスキーマファイルに記載された追加の制約によって定義される。  

このプロパティを利用することで、作成者は利用者に対し、追加制約に従う意図を伝えることができる。  

他の値が指定されない場合、profileConformance のデフォルト値は「core」であり、すべての ElementCollection および Element は Core プロファイルに準拠しなければならない。
