SPDX-License-Identifier: Community-Spec-1.0

# suppliedBy

## Summary

Identifies who or what supplied the artifact or VulnAssessmentRelationship
referenced by the Element.

## Description

Identify the actual distribution source for the artifact (e.g., snippet, file,
package, vulnerability) or VulnAssessmentRelationship being referenced.

This might or might not be different from the originating distribution source
for the artifact (e.g., snippet, file, package, vulnerability) or
VulnAssessmentRelationship.

## Metadata

- name: suppliedBy
- Nature: ObjectProperty
- Range: Agent

## Summary @ja

要素によって参照されるアーティファクトや VulnAssessmentRelationship を、誰または何が供給したのかを識別する。

## Description @ja

suppliedBy は、スニペット、ファイル、パッケージ、脆弱性などのアーティファクト、または VulnAssessmentRelationship が参照している対象について、実際にそれを配布した供給元を特定するために用いられる。この供給元は、アーティファクトや VulnAssessmentRelationship の起源となる配布元と同一である場合もあれば、異なる場合もある。
