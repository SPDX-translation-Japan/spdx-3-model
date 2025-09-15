SPDX-License-Identifier: Community-Spec-1.0

# MediaType

## Summary

Standardized way of indicating the type of content of an Element or a Property.
A String constrained to the RFC 2046 specification.

## Description

A MediaType is a string constrained to the
[RFC 2046 MIME Part Two: Media Types](https://datatracker.ietf.org/doc/rfc2046/).
It provides a standardized way of indicating the type of content of an Element
or a Property.

*Example*

- `application/java-archive`
- `application/vcard+json`
- `application/vnd.oasis.opendocument.text`
- `image/avif`
- `text/csv;charset=UTF-8`
- `text/javascript`
- `text/spdx`

A list of all possible media types is available at
[IANA Protocol Registries](https://www.iana.org/assignments/media-types/media-types.xhtml).

## Metadata

- name: MediaType
- SubclassOf: xsd:string

## Format

- pattern: ^[^\/]+\/[^\/]+$

## Summary @ja

要素またはプロパティの内容の種類を示す標準化された方法。RFC 2046 仕様に制約された文字列。

## Description @ja

MediaType は [RFC 2046 MIME Part Two: Media Types](https://datatracker.ietf.org/doc/rfc2046/) に準拠した文字列である。  
これは要素やプロパティの内容の種類を標準化された方法で示す。

*例*
- `application/java-archive`
- `application/vcard+json`
- `application/vnd.oasis.opendocument.text`
- `image/avif`
- `text/csv;charset=UTF-8`
- `text/javascript`
- `text/spdx`

利用可能なすべてのメディアタイプの一覧は [IANA Protocol Registries](https://www.iana.org/assignments/media-types/media-types.xhtml) で公開されている。
