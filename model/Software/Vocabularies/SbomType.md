SPDX-License-Identifier: Community-Spec-1.0

# SbomType

## Summary

Provides a set of values to be used to describe the common types of SBOMs that
tools may create.

## Description

The set of SBOM types with definitions as defined in
[Types of Software Bill of Material (SBOM) Documents](https://www.cisa.gov/sites/default/files/2023-04/sbom-types-document-508c.pdf),
published on April 21, 2023.

An SBOM type describes the most likely type of an SBOM from the producer
perspective, so that consumers can draw conclusions about the data inside an
SBOM.

A single SBOM can have multiple SBOM document types associated with it.

## Metadata

- name: SbomType

## Entries

- design: SBOM of intended, planned software project or product with included components (some of which may not yet exist) for a new software artifact.
- source: SBOM created directly from the development environment, source files, and included dependencies used to build a product artifact.
- build: SBOM generated as part of the process of building the software to create a releasable artifact (e.g., executable or package) from data such as source files, dependencies, built components, build process ephemeral data, and other SBOMs.
- deployed: SBOM provides an inventory of software that is present on a system. This may be an assembly of other SBOMs that combines analysis of configuration options, and examination of execution behavior in a (potentially simulated) deployment environment.
- runtime: SBOM generated through instrumenting the system running the software, to capture only components present in the system, as well as external call-outs or dynamically loaded components. In some contexts, this may also be referred to as an "Instrumented" or "Dynamic" SBOM.
- analyzed: SBOM generated through analysis of artifacts (e.g., executables, packages, containers, and virtual machine images) after its build. Such analysis generally requires a variety of heuristics. In some contexts, this may also be referred to as a "3rd party" SBOM.

## Summary @zh-Hans

提供一组值，用于描述工具可能创建的常见SBOM（软件物料清单）类型。

## Description @zh-Hans

在2023年4月21日发布的《软件物料清单（SBOM）文档类型》（[Types of Software Bill of Material (SBOM) Documents](https://www.cisa.gov/sites/default/files/2023-04/sbom-types-document-508c.pdf)）中定义的SBOM类型集合及其定义。

SBOM类型从生产者的角度描述了SBOM的最可能类型，以便消费者可以对SBOM内的数据得出结论。

一个SBOM可以与多个SBOM文档类型相关联。

## Entries @zh-Hans

- design: (设计) SBOM是针对预期的、计划中的软件项目或产品，包括了新软件工件的组成部分（其中一些可能尚不存在）。
- source: (源代码) 直接从开发环境、源文件和用于构建产品包的依赖关系中创建的SBOM。
- build: (构建) 在构建软件的过程中生成的SBOM，以从源文件、依赖关系、构建组件、构建过程临时数据和其他SBOMs等数据中创建一个可发布的工件（例如，可执行文件或包）。
- deployed: (部署态) SBOM提供了系统上存在的软件清单。这可能是其他SBOM的组合，结合了配置选项的分析和在（可能是模拟的）部署环境中执行行为的检查。
- runtime: (运行时) 通过监控系统运行软件生成的SBOM，以捕获系统中存在的组件以及外部调用或动态加载的组件。在某些情况下，这也可能被称为“监控”或“动态”SBOM。
- analyzed: (分析) 在构建工件后，通过对工件（例如，可执行文件、包、容器和虚拟机镜像）进行分析生成的SBOM。这种分析通常需要多种启发式方法。在某些情况下，这也可能被称为“第三方”SBOM。
