SPDX-License-Identifier: Community-Spec-1.0

# Sbom

## Summary

A collection of SPDX Elements describing a single package.

## Description

A Software Bill of Materials (SBOM) is a collection of SPDX Elements describing
a single package.

This could include details of the content and composition of the product,
provenance details of the product and/or its composition, licensing
information, known quality or security issues, etc.

## Metadata

- name: Sbom
- SubclassOf: /Core/Bom

## Properties

- sbomType
  - type: SbomType
  - minCount: 0

## Summary @zh-Hans

用于描述一个软件包的SPDX元素集合。

## Description @zh-Hans

软件物料清单(`Sbom`)是用于描述一个软件包的所有SPDX元素集合。

这可能包括产品内容及其组成的详细信息，产品和/或其成分的溯源信息，许可证信息，已知的质量或安全问题等。

## Summary @jp

単一パッケージを記述するSPDX要素のコレクション。

## Description @jp

ソフトウェア部品表 (SBOM) は、単一のパッケージを記述する SPDX 要素のコレクションである。

これには、製品の内容と構成の詳細、製品かつ/またはその構成の由来の詳細、ライセンス情報、既知の品質またはセキュリティの問題などを含めることができる。
