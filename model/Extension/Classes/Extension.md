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

## Summary @ja

Elementの特定の側面を特徴づけるもので、そのElementと一般化された形で関連付けられているクラス

## Description @ja

`Extension` とは、Elementの特定の側面を特徴づけるものであり、そのElementに対して一般化された形で関連付けられる。

`Extension` は、特定の目的別オブジェクトプロパティの使用を通じて特定の `Element` に関連付けられるのではなく、`Extension` は単一の共通の汎用オブジェクトプロパティを用いて、それが特徴付ける `Element` に関連付けられる。

このアプローチは複数の目的を果たす：

1. プロファイルベースのElement拡張特性化をサポートする。SPDXの任意のプロファイルおよび名前空間内でElement特性化拡張の仕様と表現を可能にし、他のプロファイルや名前空間の変更を必要とせず、リモートクラスのローカルサブクラス化（場合によってはエコシステムの相互運用性を阻害する可能性がある）も不要とする。

2. 特定の文脈に特化した独自のElement特性化詳細を持つ個人またはコミュニティの採用によるSPDXの拡張をサポートする。これにより、採用する個人やコミュニティは、SPDXの表現力を活用しつつ、SPDX全体での標準化には適さない、彼ら固有のより専門的な要素特性詳細を表現できるようになる。

3. 世界での使用から明らかになったSPDXカバレッジのギャップに対する表現力豊かな解決策の構造化による捕捉をサポートする。これにより、採用する個人やコミュニティは、現在SPDXで定義されていないが定義されるべきと思われる、彼らが必要とするElement特性の詳細を表現できるようになる。また、以下の実用的なパイプラインを実現する：

    - SPDXに存在する埋めるべきギャップを特定する
    - ギャップに対する解決策を、特定した採用者が拡張ソリューションをSPDXと共に使用可能で、かつ現行SPDXと競合しない形で表現する
    - SPDX互換エコシステム内で定義されるデータが明確に検出可能となる
    - SPDX標準への改訂提案として使用可能な、明確かつ構造化されたギャップ解決策の定義を提供する