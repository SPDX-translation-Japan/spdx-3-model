SPDX-License-Identifier: Community-Spec-1.0

# NamespaceMap

## Summary

A mapping between prefixes and namespace partial URIs.

## Description

A namespace map allows the creator of a collection of serializable Elements
to suggest shorter identifiers ("prefixes") for specific namespace portions
of Element IDs. This map is used in SPDX content serialization to provide
a more human-readable and smaller serialized representation of the Elements.

For details of how NamespaceMap content is to be serialized please refer to
the [Model and serializations](../../../serializations.md) clause
and the various serialization format-specific files within the
[spdx-3-model repository](https://github.com/spdx/spdx-3-model/tree/main/serialization).

Namespace maps support a variety of relevant use cases such as:

1. An SPDX content producer wishing to provide clarity of their serialization
    of an SPDX 2.X simple style collection where all content is newly minted
    and a single prefix-namespace is used. The consumer of SPDX content wishes
    to preserve the name space mapping provided by such a producer.

    In this case, the consumer would record the namespace map prefixes in the
    NamespaceMap such that subsequent serializations could reproduce the
    prefixes / namespaces in the native serialization format.

2. An SPDX content producer wishing to maintain consistent prefix use and
    understanding across multiple different serialization formats of the
    produced content.
  
    For example, an SBOM producer wishes to share/publish the SBOM as JSON-LD
    and XML. The producer can specify the preferred prefix mappings in the
    native serialization format using information from a single NamespaceMap
    accessible local to the producer.

3. An SPDX content consumer/producer wishing to maintain consistent prefix use
    while round tripping from SPDX content received, deserialized,
    modified/extended in some way, and then reserialized in the same
    serialization form.

    In this case the prefix-namespace mappings utilized in the content are
    transformed from the original native namespace/prefix into the in memory
    NamespaceMap then transformed from the NamespaceMap back into the resultant
    serialization native namespace / prefix format.

## Metadata

- name: NamespaceMap
- Instantiability: Concrete

## Properties

- prefix
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- namespace
  - type: xsd:anyURI
  - minCount: 1
  - maxCount: 1

## Summary @ja

プレフィックスと名前空間部分 URI の対応関係。

## Description @ja

NamespaceMap は、シリアライズ可能な Element の集合を作成する者が、Element ID の特定の名前空間部分に短い識別子（プレフィックス）を割り当てることを可能にする。このマップは SPDX コンテンツのシリアライズにおいて、より人間に読みやすく、より小さなシリアライズ表現を提供する。  

NamespaceMap の内容がどのようにシリアライズされるかの詳細については、[Model and serializations](../../../serializations.md) 節および [spdx-3-model リポジトリ](https://github.com/spdx/spdx-3-model/tree/main/serialization) 内の各種シリアライズ形式固有のファイルを参照のこと。  

NamespaceMap は次のような多様なユースケースをサポートする:  

1. SPDX コンテンツのプロデューサーが、すべてのコンテンツが新しく生成され、単一のプレフィックス-名前空間が使用される SPDX 2.X のシンプルスタイルのコレクションをシリアライズする際に、そのシリアライズの明確さを提供したい場合。SPDX コンテンツのコンシューマーは、そのようなプロデューサーによって提供された名前空間マッピングを保持したいと考える。  
   この場合、コンシューマーは NamespaceMap にプレフィックスを記録し、その後のシリアライズにおいてネイティブのシリアライズ形式で同じプレフィックス／名前空間を再現できるようにする。  

2. SPDX コンテンツのプロデューサーが、生成されたコンテンツを複数の異なるシリアライズ形式で表現する際に、一貫したプレフィックスの利用と理解を維持したい場合。  
   例えば SBOM プロデューサーが SBOM を JSON-LD と XML の両方で共有・公開したい場合、プロデューサーはローカルで利用可能な単一の NamespaceMap に基づいて、ネイティブのシリアライズ形式における好ましいプレフィックスマッピングを指定できる。  

3. SPDX コンテンツのコンシューマー／プロデューサーが、受信した SPDX コンテンツをデシリアライズし、何らかの形で修正・拡張した後、同じシリアライズ形式で再シリアライズする「ラウンドトリップ」を行う際に、一貫したプレフィックス利用を維持したい場合。  
   この場合、コンテンツで利用されているプレフィックス-名前空間マッピングは、元のネイティブの名前空間／プレフィックスからメモリ上の NamespaceMap に変換され、その後 NamespaceMap から結果のシリアライズ形式のネイティブ名前空間／プレフィックス形式に戻される。  
