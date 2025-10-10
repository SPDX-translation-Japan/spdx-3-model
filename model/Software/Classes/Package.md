SPDX-License-Identifier: Community-Spec-1.0

# Package

## Summary

Refers to any unit of content that can be associated with a distribution of
software.

## Description

A package refers to any unit of content that can be associated with a
distribution of software.

Typically, a package is composed of one or more files.

Any of the following non-limiting examples may be (but are not required to be)
represented in SPDX as a package:

- a tarball, zip file or other archive
- a directory or sub-directory
- a separately distributed piece of software which another Package or File uses
  or depends upon (e.g., a Python package, a Go module, ...)
- a container image, and/or each image layer within a container image
- a collection of one or more sub-packages
- a Git repository snapshot from a particular point in time

Note that some of these could be represented in SPDX as a file as well.

## Metadata

- name: Package
- SubclassOf: /Software/SoftwareArtifact

## Properties

- downloadLocation
  - type: xsd:anyURI
  - minCount: 0
  - maxCount: 1
- homePage
  - type: xsd:anyURI
  - minCount: 0
  - maxCount: 1
- packageVersion
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- packageUrl
  - type: xsd:anyURI
  - minCount: 0
  - maxCount: 1
- sourceInfo
  - type: xsd:string
  - minCount: 0
  - maxCount: 1

## External properties restrictions

- /Core/Element/name
  - minCount: 1

## Summary @zh-Hans

指的是与软件分发相关的任何内容单元。

## Description @zh-Hans

包(`Package`)指与软件分发相关的任何内容单元。

通常，一个软件包由一个或多个文件组成。

在SPDX中表达一个软件包，包含但不限于以下示例：

- 一个tar,zip或其他压缩文件
- 一个目录或者子目录
- 一个被其他包或文件使用或依赖的独立分发软件(例如 一个Python包, 一个 Go 模块 ...)
- 一个容器镜像，以及/或者容器镜像里的一个镜像层
- 一个或多个子包的集合
- 一个特定时间点的git代码仓库快照

需要注意的是上述内容中的一些也可以在SPDX中被表示为文件。

## Summary @jp

ソフトウェアの配布に関連付けることができるコンテンツの単位を指す。

## Description @jp

パッケージとは、ソフトウェアの配布に関連付けることができるコンテンツの単位を指す。

通常、一つのパッケージは一つ以上のファイルで構成される。

以下の例はいずれもSPDXでパッケージとして表現できる(ただし必須ではない)。なお、パッケージとして表現できるのは以下の例に限定されない。

- tarball、zipファイルもしくはその他のアーカイブ
- ディレクトリもしくはサブディレクトリ
- 他のPackageもしくはFileが使用するもしくは依存する、分離して配布されるソフトウェア(例えば、Pythonパッケージ、Goモジュール)
- コンテナイメージ、かつ/もしくは、コンテナイメージ内の各イメージレイヤー
- 一つ以上のサブパッケージの集合
- 特定時点からのGitリポジトリスナップショット

これらの一部は、SPDXではファイルとして表現できることに注意。
