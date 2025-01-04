SPDX-License-Identifier: Community-Spec-1.0

# attributionText

## Summary

Provides a place for the SPDX data creator to record acknowledgement text for
a software Package, File or Snippet.

## Description

An attributionText for a software Package, File or Snippet provides a consumer
of SPDX data with acknowledgement content, to assist redistributors of the
Package, File or Snippet with reproducing those acknowledgements.

For example, this field may include a statement that is required by a
particular license to be reproduced in end-user documentation, advertising
materials, or another form.

This field may describe where, or in which contexts, the acknowledgements
need to be reproduced, but it is not required to do so. The SPDX data creator
may also explain elsewhere (such as in a comment field) how they intend for
data in this field to be used.

An attributionText is not meant to include the software Package, File or
Snippet's actual complete license text. Use hasConcludedLicense to identify the
corresponding license.

## Metadata

- name: attributionText
- Nature: DataProperty
- Range: xsd:string

## Summary @zh-Hans

为SPDX数据创建者提供了一个记录软件包、文件或代码片段的署名文本的地方。

## Description @zh-Hans

署名文本（`attributionText`）为软件包、文件或代码片段提供了一个让消费者了解SPDX数据的署名内容的地方，以帮助软件包、文件或代码片段的再分发者复制这些署名。

例如，这个字段可能包含特定许可证要求在最终用户文档、广告材料或其他形式中复制的声明。

这个字段可能描述了署名需要在何处或在哪些情境下被复制，但这不是必需的。SPDX数据创建者也可以在其他地方（例如，在注释字段中）解释他们打算如何使用这个字段中的数据。

署名文本不意味着包括软件包、文件或代码片段的实际完整许可证文本。使用`hasConcludedLicense`来标识相应的许可证。
