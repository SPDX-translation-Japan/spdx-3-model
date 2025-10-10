SPDX-License-Identifier: Community-Spec-1.0

# SoftwarePurpose

## Summary

Provides information about the primary purpose of an Element.

## Description

This field provides information about the primary purpose of an Element.

Software Purpose is intrinsic to how the Element is being used rather than the
content of the Element.

This field is a reasonable estimate of the most likely usage of the Element
from the producer and consumer perspective from which both parties can draw
conclusions about the context in which the Element exists.

## Metadata

- name: SoftwarePurpose

## Entries

- application: The Element is a software application.
- archive: The Element is an archived collection of one or more files (.tar, .zip, etc.).
- bom: The Element is a bill of materials.
- configuration: The Element is configuration data.
- container: The Element is a container image which can be used by a container runtime application.
- data: The Element is data.
- device: The Element refers to a chipset, processor, or electronic board.
- diskImage: The Element refers to a disk image that can be written to a disk, booted in a VM, etc. A disk image typically contains most or all of the components necessary to boot, such as bootloaders, kernels, firmware, userspace, etc.
- deviceDriver: The Element represents software that controls hardware devices.
- documentation: The Element is documentation.
- evidence: The Element is the evidence that a specification or requirement has been fulfilled.
- executable: The Element is an Artifact that can be run on a computer.
- file: The Element is a single file which can be independently distributed (configuration file, statically linked binary, Kubernetes deployment, etc.).
- filesystemImage: The Element is a file system image that can be written to a disk (or virtual) partition.
- firmware: The Element provides low level control over a device's hardware.
- framework: The Element is a software framework.
- install: The Element is used to install software on disk.
- library: The Element is a software library.
- manifest: The Element is a software manifest.
- model: The Element is a machine learning or artificial intelligence model.
- module: The Element is a module of a piece of software.
- operatingSystem: The Element is an operating system.
- other: The Element doesn't fit into any of the other categories.
- patch: The Element contains a set of changes to update, fix, or improve another Element.
- platform: The Element represents a runtime environment.
- requirement: The Element provides a requirement needed as input for another Element.
- source: The Element is a single or a collection of source files.
- specification: The Element is a plan, guideline or strategy how to create, perform or analyze an application.
- test: The Element is a test used to verify functionality on a software element.

## Summary @zh-Hans

提供有关元素的主要目的信息。

## Description @zh-Hans

该字段提供了有关元素的主要目的信息。

软件目的与元素的使用方式内在相关，而不是元素的内容。

这个字段是对元素最可能用途的合理估计，从生产者和消费者的角度来看，双方都可以从中得出关于元素存在的上下文的结论。

## Entries @zh-Hans

- application: (应用程序) 该元素是一个软件应用程序。
- archive: (归档文件) 该元素是一个或多个文件的归档集合（如.tar、.zip等）。
- bom: (物料清单) 该元素是一个物料清单。
- configuration: (配置数据) 该元素是配置数据。
- container: (容器) 该元素是一个容器镜像，可以被容器运行时应用程序使用。
- data: (数据) 该元素是数据。
- device: (设备) 该元素指的是芯片模组、处理器或电路板。
- diskImage: (磁盘映像) 该元素指的是可以写入磁盘、在虚拟机中启动等的磁盘映像。磁盘映像通常包含启动所需的大部分或全部组件，如引导加载程序、内核、固件、用户空间等。
- deviceDriver: (设备驱动程序) 该元素代表控制硬件设备的软件。
- documentation: (文档) 该元素是文档。
- evidence: (证据) 该元素是证明规范或要求已得到满足的证据。
- executable: (可执行文件) 该元素是可以计算机上运行的工件。
- file: (文件) 该元素是一个可以独立分发的单个文件（配置文件、静态链接的二进制文件、Kubernetes部署等）。
- filesystemImage: (文件系统映像) 该元素是一个可以写入磁盘（或虚拟）分区的文件系统映像。
- firmware: (固件) 该元素提供对设备硬件的低级控制。
- framework: (框架) 该元素是一个软件框架。
- install: (安装程序) 该元素用于在磁盘上安装软件。
- library: (库) 该元素是一个软件库。
- manifest: (清单) 该元素是一个软件清单。
- model: (模型) 该元素是机器学习或人工智能模型。
- module: (模块) 该元素是软件的一个模块。
- operatingSystem: (操作系统) 该元素是一个操作系统。
- other: (其他) 该元素不属于其他任何类别。
- patch: (补丁) 该元素包含一组用于更新、修复或改进另一个元素的更改。
- platform: (平台) 该元素代表一个运行时环境。
- requirement: (需求) 该元素提供了作为另一个元素输入所需的需求。
- source: (源代码) 该元素是单个或一组源代码文件。
- specification: (规范) 该元素是一个计划、指南或策略，说明如何创建、执行或分析应用程序。
- test: (测试) 该元素是用来验证软件元素功能的测试。

## Summary @jp

Elementの主な目的に関する情報を提供する。

## Description @jp

このフィールドは、Elementの主な目的に関する情報を提供する。

Software Purposeは、Elementの内容ではなく、Elementの使用方法に本質的に関係する。

このフィールドは、作成者と利用者の観点から見た、Elementの最も可能性の高い使用法の合理的な推定であり、これにより両者はElementが存在する文脈について結論を導ける。

## Entries @jp

- application: Element はソフトウェアアプリケーションである。
- archive: Elementは、1つ以上のファイルのアーカイブされたコレクション(.tar、.zipなど)である。
- bom: Elementは部品表である。
- configuration: Elementは構成データである。
- container: Elementは、コンテナーランタイムアプリケーションで使用されうるコンテナーイメージである。
- data: Elementはデータである。
- device: Elementは、チップセット、プロセッサー、電子基板を指す。
- diskImage: Elementは、ディスクに書き込まれたり、VMで起動されたりする、ディスイメージを指す。ディスク イメージは、通常、ブートローダー、カーネル、ファームウェア、ユーザー空間など、起動に必要なコンポーネントのほとんどまたはすべてが含まれている。
- deviceDriver: Elementは、ハードウェアデバイスを制御するソフトウェアを示す。
- documentation: Elementは文書である。
- evidence: Elementは、仕様もしくは要求が達成されたことの証拠である。
- executable: Elementは、コンピューター上で実行できるArtifactである。
- file: Elementは、独立して配布できる単一のファイルである(構成ファイル、静的にリンクされたバイナリ、Kubernetesデプロイメントなど)。
- filesystemImage: Elementは、ディスク(または仮想)パーティションに書き込むことができるファイルシステムイメージである。
- firmware: Elementは、デバイスのハードウェアに対する低レベルの制御を提供する。
- framework: Elementはソフトウェアフレームワークである。
- install: Elementは、ディスクにソフトウェアをインストールするために使われる。
- library: Elementはソフトウェアライブラリである。
- manifest: Elementはソフトウェアマニフェストである。
- model: Elementは、機械学習もしくは人工知能のモデルである。
- module: Elementは、一片のソフトウェアのモジュールである。
- operatingSystem: Elementはオペレーティングシステムである。
- other: Elementは、他のカテゴリのいずれにも該当しない。
- patch: Elementは、他のElementを更新、修正、改善するための一連の変更を含む。
- platform: Elementは実行環境を指す。
- requirement: Elementは、他のElementの入力として必要な要求を提供する。
- source: Elementは、ひとつか複数のソースファイルである。
- specification: Elementは、アプリケーションを生成、実行あるいは分析する方法の計画、ガイドラインもしくは戦略である。
- test: Elementは、ソフトウェア要素の機能を検証するために使われるテストである。
