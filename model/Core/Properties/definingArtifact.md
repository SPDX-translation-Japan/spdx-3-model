SPDX-License-Identifier: Community-Spec-1.0

# definingArtifact

## Summary

Artifact representing a serialization instance of SPDX data containing the
definition of a particular Element.

## Description

A definingArtifact property is used to link the Element identifier for an
Element defined external to a given SpdxDocument to an Artifact Element
representing the SPDX serialization instance which contains the definition for
the Element.

## Metadata

- name: definingArtifact
- Nature: ObjectProperty
- Range: Artifact

## Summary @ja

特定の Element の定義を含む SPDX データのシリアライズインスタンスを表す Artifact。

## Description @ja

`definingArtifact` プロパティは、ある SpdxDocument の外部で定義された Element の識別子を、その Element の定義を含む SPDX シリアライズインスタンスを表す Artifact 要素に結びつけるために用いる。
