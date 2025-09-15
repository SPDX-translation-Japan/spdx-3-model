SPDX-License-Identifier: Community-Spec-1.0

# ProfileIdentifierType

## Summary

Enumeration of the valid profiles.

## Description

There are a set of profiles that have been defined by a profile team.

A profile consists of a namespace that may add properties and classes to the
Core profile unique to the domain covered by the profile.

The profile may also contain additional restrictions on existing properties and
classes defined in other profiles.

If the creator of an SPDX collection of elements includes a profile in the list
of profileConformance, they are claiming that all contained elements conform
to all restrictions defined for that profile.

## Metadata

- name: ProfileIdentifierType

## Entries

- core: the element follows the Core profile specification
- software: the element follows the Software profile specification
- simpleLicensing: the element follows the SimpleLicensing profile specification
- expandedLicensing: the element follows the ExpandedLicensing profile specification
- security: the element follows the Security profile specification
- build: the element follows the Build profile specification
- ai: the element follows the AI profile specification
- dataset: the element follows the Dataset profile specification
- extension: the element follows the Extension profile specification
- lite: the element follows the Lite profile specification

## Summary @ja

有効なプロファイルの列挙。

## Description @ja

いくつかのプロファイルはプロファイルチームによって定義されている。  

プロファイルは、対象となる領域に固有の Core プロファイルへプロパティやクラスを追加することができる名前空間で構成される。  

また、プロファイルには、他のプロファイルで定義された既存のプロパティやクラスに対する追加の制約が含まれる場合もある。  

SPDX 要素の集合の作成者が `profileConformance` の一覧に特定のプロファイルを含める場合、それはすべての要素がそのプロファイルに定義された制約に準拠していると主張することを意味する。  

## Entries @ja

- core: 要素は Core プロファイル仕様に従う。  
- software: 要素は Software プロファイル仕様に従う。  
- simpleLicensing: 要素は SimpleLicensing プロファイル仕様に従う。  
- expandedLicensing: 要素は ExpandedLicensing プロファイル仕様に従う。  
- security: 要素は Security プロファイル仕様に従う。  
- build: 要素は Build プロファイル仕様に従う。  
- ai: 要素は AI プロファイル仕様に従う。  
- dataset: 要素は Dataset プロファイル仕様に従う。  
- extension: 要素は Extension プロファイル仕様に従う。  
- lite: 要素は Lite プロファイル仕様に従う。  
