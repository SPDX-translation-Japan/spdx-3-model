SPDX-License-Identifier: Community-Spec-1.0

# DictionaryEntry

## Summary

A key with an associated value.

## Description

The class used for implementing a generic string mapping (also known as
associative array, dictionary, or hash map) in SPDX.

Each DictionaryEntry contains a key-value pair which maps the key to its
associated value.

To implement a dictionary, this class is to be used in a collection with
unique keys.

## Metadata

- name: DictionaryEntry
- Instantiability: Concrete

## Properties

- key
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- value
  - type: xsd:string
  - maxCount: 1

## Summary @ja

関連する値を持つキー。

## Description @ja

DictionaryEntry クラスは、SPDX において汎用的な文字列マッピング（連想配列、辞書、またはハッシュマップとも呼ばれる）を実装するために使用される。  

各 DictionaryEntry はキーとそれに対応する値のペアを含み、そのキーを関連する値に対応づける。  

辞書を実装する場合、このクラスはユニークなキーを持つコレクションの中で使用される。  
