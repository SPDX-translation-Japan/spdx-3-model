SPDX-License-Identifier: Community-Spec-1.0

# ExternalIdentifierType

## Summary

Specifies the type of an external identifier.

## Description

ExternalIdentifierType specifies the type of an external identifier.

## Metadata

- name: ExternalIdentifierType

## Entries

- cpe22: [Common Platform Enumeration Specification 2.2](https://cpe.mitre.org/files/cpe-specification_2.2.pdf)
- cpe23: [Common Platform Enumeration: Naming Specification Version 2.3](https://csrc.nist.gov/publications/detail/nistir/7695/final)
- cve: Common Vulnerabilities and Exposures identifiers, an identifier for a specific software flaw defined within the official CVE Dictionary and that conforms to the [CVE specification](https://csrc.nist.gov/glossary/term/cve_id).
- email: Email address, as defined in [RFC 3696](https://datatracker.ietf.org/doc/rfc3986/) Section 3.
- gitoid: [Gitoid](https://www.iana.org/assignments/uri-schemes/prov/gitoid), stands for [Git Object ID](https://git-scm.com/book/en/v2/Git-Internals-Git-Objects). A gitoid of type blob is a unique hash of a binary artifact. A gitoid may represent either an [Artifact Identifier](https://github.com/omnibor/spec/blob/eb1ee5c961c16215eb8709b2975d193a2007a35d/spec/SPEC.md#artifact-identifier-types) for the software artifact or an [Input Manifest Identifier](https://github.com/omnibor/spec/blob/eb1ee5c961c16215eb8709b2975d193a2007a35d/spec/SPEC.md#input-manifest-identifier) for the software artifact's associated [Artifact Input Manifest](https://github.com/omnibor/spec/blob/eb1ee5c961c16215eb8709b2975d193a2007a35d/spec/SPEC.md#artifact-input-manifest); this ambiguity exists because the Artifact Input Manifest is itself an artifact, and the gitoid of that artifact is its valid identifier. Gitoids calculated on software artifacts (Snippet, File, or Package Elements) should be recorded in the SPDX 3.0 SoftwareArtifact's contentIdentifier property. Gitoids calculated on the Artifact Input Manifest (Input Manifest Identifier) should be recorded in the SPDX 3.0 Element's externalIdentifier property. See [OmniBOR Specification](https://github.com/omnibor/spec/), a minimalistic specification for describing software [Artifact Dependency Graphs](https://github.com/omnibor/spec/blob/eb1ee5c961c16215eb8709b2975d193a2007a35d/spec/SPEC.md#artifact-dependency-graph-adg).
- other: Used when the type does not match any of the other options.
- packageUrl: Package URL, as defined in the corresponding [Annex](../../../annexes/pkg-url-specification.md) of this specification.
- securityOther: Used when there is a security related identifier of unspecified type.
- swhid: SoftWare Hash IDentifier, a persistent intrinsic identifier for digital artifacts, such as files, trees (also known as directories or folders), commits, and other objects typically found in version control systems. The format of the identifiers is defined in the [SWHID specification](https://www.swhid.org/specification/v1.1/4.Syntax) (ISO/IEC DIS 18670). They typically look like `swh:1:cnt:94a9ed024d3859793618152ea559a168bbcbb5e2`.
- swid: Concise Software Identification (CoSWID) tag, as defined in [RFC 9393](https://datatracker.ietf.org/doc/rfc9393/) Section 2.3.
- urlScheme: [Uniform Resource Identifier (URI) Schemes](https://www.iana.org/assignments/uri-schemes/uri-schemes.xhtml). The scheme used in order to locate a resource.

## Summary @ja

外部識別子の種類を指定する。

## Description @ja

ExternalIdentifierType は、外部識別子の種類を指定する。  

## Entries @ja

- cpe22: [Common Platform Enumeration Specification 2.2](https://cpe.mitre.org/files/cpe-specification_2.2.pdf)。  
- cpe23: [Common Platform Enumeration: Naming Specification Version 2.3](https://csrc.nist.gov/publications/detail/nistir/7695/final)。  
- cve: Common Vulnerabilities and Exposures 識別子。公式の CVE 辞書内で定義され、[CVE specification](https://csrc.nist.gov/glossary/term/cve_id) に準拠した特定のソフトウェア欠陥の識別子。  
- email: [RFC 3696](https://datatracker.ietf.org/doc/rfc3986/) セクション 3 で定義される電子メールアドレス。  
- gitoid: [Gitoid](https://www.iana.org/assignments/uri-schemes/prov/gitoid)（[Git Object ID](https://git-scm.com/book/en/v2/Git-Internals-Git-Objects) の略）。`blob` 型の gitoid はバイナリアーティファクトのユニークなハッシュである。gitoid はソフトウェアアーティファクトの [Artifact Identifier](https://github.com/omnibor/spec/blob/eb1ee5c961c16215eb8709b2975d193a2007a35d/spec/SPEC.md#artifact-identifier-types) を表す場合と、ソフトウェアアーティファクトに関連する [Artifact Input Manifest](https://github.com/omnibor/spec/blob/eb1ee5c961c16215eb8709b2975d193a2007a35d/spec/SPEC.md#artifact-input-manifest) の [Input Manifest Identifier](https://github.com/omnibor/spec/blob/eb1ee5c961c16215eb8709b2975d193a2007a35d/spec/SPEC.md#input-manifest-identifier) を表す場合がある。この曖昧さは、Artifact Input Manifest 自体がアーティファクトであり、その gitoid が正当な識別子となるために生じる。ソフトウェアアーティファクト（Snippet、File、Package Element）の gitoid は SPDX 3.0 SoftwareArtifact の `contentIdentifier` プロパティに記録されるべきである。Artifact Input Manifest の gitoid（Input Manifest Identifier）は SPDX 3.0 Element の `externalIdentifier` プロパティに記録されるべきである。詳細は [OmniBOR Specification](https://github.com/omnibor/spec/) を参照。これはソフトウェア [Artifact Dependency Graphs](https://github.com/omnibor/spec/blob/eb1ee5c961c16215eb8709b2975d193a2007a35d/spec/SPEC.md#artifact-dependency-graph-adg) を記述するための最小仕様である。  
- other: 種類が他の選択肢のいずれにも一致しない場合に使用される。  
- packageUrl: この仕様の [Annex](../../../annexes/pkg-url-specification.md) で定義される Package URL。  
- securityOther: 特定されていない型のセキュリティ関連識別子が存在する場合に使用される。  
- swhid: SoftWare Hash IDentifier。ファイル、ツリー（ディレクトリやフォルダとも呼ばれる）、コミット、その他バージョン管理システムで一般的に見られるオブジェクトなど、デジタルアーティファクトに対する永続的で本質的な識別子。[SWHID specification](https://www.swhid.org/specification/v1.1/4.Syntax)（ISO/IEC DIS 18670）で定義される。典型的には `swh:1:cnt:94a9ed024d3859793618152ea559a168bbcbb5e2` のような形式となる。  
- swid: Concise Software Identification (CoSWID) タグ。[RFC 9393](https://datatracker.ietf.org/doc/rfc9393/) セクション 2.3 で定義される。  
- urlScheme: [Uniform Resource Identifier (URI) Schemes](https://www.iana.org/assignments/uri-schemes/uri-schemes.xhtml)。リソースを特定するために用いられるスキーム。
