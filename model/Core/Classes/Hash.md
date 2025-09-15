SPDX-License-Identifier: Community-Spec-1.0

# Hash

## Summary

A mathematically calculated representation of a grouping of data.

## Description

A hash is a grouping of characteristics unique to the result
of applying a mathematical algorithm
that maps data of arbitrary size to a bit string (the hash)
and is a one-way function, that is,
a function which is practically infeasible to invert.

This is commonly used for integrity checking of data.

Please note that different profiles may also provide additional methods for verifying the integrity of specific subclasses of Elements.

## Metadata

- name: Hash
- SubclassOf: IntegrityMethod

## Properties

- algorithm
  - type: HashAlgorithm
  - minCount: 1
  - maxCount: 1
- hashValue
  - type: xsd:string
  - minCount: 1
  - maxCount: 1

## Summary @ja

データ群を数学的に計算して得られる表現。

## Description @ja

ハッシュとは、任意のサイズのデータを数学的アルゴリズムに適用することでビット列（ハッシュ）に写像し、その結果として得られる特有の特性集合である。これは一方向関数であり、実際上その逆を計算することは不可能である。  

ハッシュは通常、データの完全性検証に用いられる。  

また、プロファイルによっては、特定の Element サブクラスの完全性を検証するための追加の方法が提供される場合もある。  