SPDX-License-Identifier: Community-Spec-1.0

# ContentIdentifierType

## Summary

Specifies the type of a content identifier.

## Description

ContentIdentifierType specifies the type of a content identifier.

## Metadata

- name: ContentIdentifierType

## Entries

- gitoid: [Gitoid](https://www.iana.org/assignments/uri-schemes/prov/gitoid), stands for [Git Object ID](https://git-scm.com/book/en/v2/Git-Internals-Git-Objects). A gitoid of type blob is a unique hash of a binary artifact. A gitoid may represent either an [Artifact Identifier](https://github.com/omnibor/spec/blob/eb1ee5c961c16215eb8709b2975d193a2007a35d/spec/SPEC.md#artifact-identifier-types) for the software artifact or an [Input Manifest Identifier](https://github.com/omnibor/spec/blob/eb1ee5c961c16215eb8709b2975d193a2007a35d/spec/SPEC.md#input-manifest-identifier) for the software artifact's associated [Artifact Input Manifest](https://github.com/omnibor/spec/blob/eb1ee5c961c16215eb8709b2975d193a2007a35d/spec/SPEC.md#artifact-input-manifest); this ambiguity exists because the Artifact Input Manifest is itself an artifact, and the gitoid of that artifact is its valid identifier. Gitoids calculated on software artifacts (Snippet, File, or Package Elements) should be recorded in the SPDX 3.0 SoftwareArtifact's contentIdentifier property. Gitoids calculated on the Artifact Input Manifest (Input Manifest Identifier) should be recorded in the SPDX 3.0 Element's externalIdentifier property. See [OmniBOR Specification](https://github.com/omnibor/spec/), a minimalistic specification for describing software [Artifact Dependency Graphs](https://github.com/omnibor/spec/blob/eb1ee5c961c16215eb8709b2975d193a2007a35d/spec/SPEC.md#artifact-dependency-graph-adg).
- swhid: SoftWare Hash IDentifier, a persistent intrinsic identifier for digital artifacts, such as files, trees (also known as directories or folders), commits, and other objects typically found in version control systems. The format of the identifiers is defined in the [SWHID specification](https://www.swhid.org/specification/v1.1/4.Syntax) (ISO/IEC DIS 18670). They typically look like `swh:1:cnt:94a9ed024d3859793618152ea559a168bbcbb5e2`.

## Summary @zh-Hans

指定内容标识符的类型。

## Description @zh-Hans

内容标识符类型（`ContentIdentifierType`）指定了内容标识符的类型。

## Entries @zh-Hans

- gitoid：[Gitoid](https://www.iana.org/assignments/uri-schemes/prov/gitoid)代表 [Git Object ID](https://git-scm.com/book/en/v2/Git-Internals-Git-Objects)。类型为blob的gitoid是二进制工件的唯一哈希值。gitoid可以代表软件工件的工件标识符（[Artifact Identifier](https://github.com/omnibor/spec/blob/eb1ee5c961c16215eb8709b2975d193a2007a35d/spec/SPEC.md#artifact-identifier-types)），也可以代表软件工件相关联的工件输入清单（ [Artifact Input Manifest](https://github.com/omnibor/spec/blob/eb1ee5c961c16215eb8709b2975d193a2007a35d/spec/SPEC.md#artifact-input-manifest)）的输入清单标识符（[Input Manifest Identifier](https://github.com/omnibor/spec/blob/eb1ee5c961c16215eb8709b2975d193a2007a35d/spec/SPEC.md#input-manifest-identifier)）；这种模糊性存在是因为工件输入清单本身也是一个工件，而该工件的gitoid就是其有效的标识符。在软件工件（如代码片段、文件或包元素）上计算的Gitoids应该记录在SPDX 3.0 SoftwareArtifact的内容标识符（contentIdentifier）属性中。在工件输入清单（Artifact Input Manifest，输入清单标识符）上计算的Gitoids应该记录在SPDX 3.0元素的外部标识符（externalIdentifier）属性中。参见OmniBOR规范（[OmniBOR Specification](https://github.com/omnibor/spec/)），这是一个描述软件工件依赖图（[Artifact Dependency Graphs](https://github.com/omnibor/spec/blob/eb1ee5c961c16215eb8709b2975d193a2007a35d/spec/SPEC.md#artifact-dependency-graph-adg)）的极简规范。
- swhid：软件哈希标识符，是一种用于数字工件的持久内在标识符，这些数字工件包括文件、树（也称为目录或文件夹）、commits（提交）以及其他通常在版本控制系统中找到的对象。这些标识符的格式在SWHID规范（ [SWHID specification](https://www.swhid.org/specification/v1.1/4.Syntax)）（ISO/IEC DIS 18670）中定义。它们通常看起来像这样 `swh:1:cnt:94a9ed024d3859793618152ea559a168bbcbb5e2`。

## Summary @jp

コンテンツ識別子の種類を指定する。

## Description @jp

ContentIdentifierTypeは、コンテンツ識別子の種類を指定する。

## Entries @jp

- gitoid: [gitoid](https://www.iana.org/assignments/uri-schemes/prov/gitoid)は[Git Object ID](https://git-scm.com/book/en/v2/Git-Internals-Git-Objects)の略称である。blob型のgitoidはバイナリイアーティファクトの一意のハッシュである。gitoidは、ソフトウェアアーティファクトの[Artifact Identifier](https://github.com/omnibor/spec/blob/eb1ee5c961c16215eb8709b2975d193a2007a35d/spec/SPEC.md#artifact-identifier-types)、または、ソフトウェアアーティファクトの関連付けられた[Artifact Input Manifest](https://github.com/omnibor/spec/blob/eb1ee5c961c16215eb8709b2975d193a2007a35d/spec/SPEC.md#artifact-input-manifest)の[Input Manifest Identifier](https://github.com/omnibor/spec/blob/eb1ee5c961c16215eb8709b2975d193a2007a35d/spec/SPEC.md#input-manifest-identifier)のいずれかを表す。このあいまいさは、Artifact Input Manifest自体がアーティファクトであり、そのアーティファクトのgitoidがその有効な識別子であるために生ずる。ソフトウェアアーティファクト(スニペット、ファイル、またはパッケージ要素)で算出されたgitoidは、SPDX 3.0 SoftwareArtifactのcontentIdentifierプロパティに記録されるべきである。Artifact Input Manifest (Input Manifest Identifier)で算出されたgitoidは、SPDX 3.0 ElementのexternalIdentifierプロパティに記録されるべきである。ソフトウェア[Artifact Dependency Graphs](https://github.com/omnibor/spec/blob/eb1ee5c961c16215eb8709b2975d193a2007a35d/spec/SPEC.md#artifact-dependency-graph-adg)を記述するための最小限仕様である、[OmniBOR Specification](https://github.com/omnibor/spec/)を参照のこと。
- swhid: SoftWare Hash IDentifier (ソフトウェアハッシュ識別子)は、ファイル、ツリー(ディレクトリまたはフォルダとも呼ばれる)、コミット、その他バージョン管理システムに典型的に見られるオブジェクトといったデジタルアーティファクトに固有の永続的な識別子である。識別子の形式は[SWHID specification](https://www.swhid.org/specification/v1.1/4.Syntax) (ISO/IEC DIS 18670)で定義されている。通常は`swh:1:cnt:94a9ed024d3859793618152ea559a168bbcbb5e2`のように見える。
