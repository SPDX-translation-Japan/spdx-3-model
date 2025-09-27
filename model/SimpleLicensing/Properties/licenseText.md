SPDX-License-Identifier: Community-Spec-1.0

# licenseText

## Summary

Identifies the full text of a License or Addition.

## Summary @ja

ライセンスまたは追加条項の全文を表す。

## Description

A licenseText contains the plain text of the License or Addition,
without templating or other similar markup.

Users of the licenseText for a License can apply the
[SPDX License List Matching Guidelines](../../../annexes/license-matching-guidelines-and-templates.md)
when comparing it to another text for matching purposes.

## Description @ja

licenseTextは、ライセンスまたは追加条項の本文を、テンプレートやマークアップを使わずプレーンなテキストとして表現する。

ライセンスの利用者は、licenseTextを他のテキストと[SPDXライセンスリストマッチングガイドライン](../../../annexes/license-matching-guidelines-and-templates.md)に従って照合することができる。

## Metadata

- name: licenseText
- Nature: DataProperty
- Range: xsd:string

## Summary @zh-Hans

标识许可证（`License`）或附加内容（`Addition`）的全文。

## Description @zh-Hans

一个许可证文本（`licenseText`）包含许可证（`License`）或附加内容（`Addition`）的纯文本，不含模板或其他类似标记。

许可证（`License`）的许可证文本（`licenseText`）用户在将其与其他文本进行匹配时，可应用[SPDX许可证列表匹配指南](../../../annexes/license-matching-guidelines-and-templates.md)。
