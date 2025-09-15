SPDX-License-Identifier: Community-Spec-1.0

# LifecycleScopeType

## Summary

Provide an enumerated set of lifecycle phases that can provide context to relationships.

## Description

This enumeration summarizes common phases when dependency and other relationships, have different implications, based on their context.  For example,  a build dependency, may have different implications than a operational dependency.

## Metadata

- name: LifecycleScopeType

## Entries

- design: A relationship has specific context implications during an element's design.
- development: A relationship has specific context implications during development phase of an element.
- build: A relationship has specific context implications during an element's build phase, during development.
- test: A relationship has specific context implications during an element's testing phase, during development.
- runtime: A relationship has specific context implications during the execution phase of an element.
- other: A relationship has other specific context information necessary to capture that the above set of enumerations does not handle.

## Summary @ja

関係に文脈を与えることができるライフサイクルの各段階を列挙した集合。

## Description @ja

この列挙は、依存関係やその他の関係が、その文脈に基づいて異なる意味を持つ典型的な段階を要約する。  
例えば、ビルド時の依存関係は、運用時の依存関係とは異なる意味を持つ場合がある。

## Entries @ja

- design: 要素の設計段階において、関係が特定の文脈的意味を持つことを示す。  
- development: 要素の開発段階において、関係が特定の文脈的意味を持つことを示す。  
- build: 要素の開発中におけるビルド段階で、関係が特定の文脈的意味を持つことを示す。  
- test: 要素の開発中におけるテスト段階で、関係が特定の文脈的意味を持つことを示す。  
- runtime: 要素の実行段階において、関係が特定の文脈的意味を持つことを示す。  
- other: 上記の列挙では扱えないが、記録が必要となるその他の特定の文脈情報を示す。  
