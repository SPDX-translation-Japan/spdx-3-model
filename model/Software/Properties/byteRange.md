SPDX-License-Identifier: Community-Spec-1.0

# byteRange

## Summary

Defines the byte range in the original host file that the snippet information
applies to.

## Description

This field defines the byte range in the original host file that the snippet
information applies to.

A range of bytes is independent of various formatting concerns, and the most
accurate way of referring to the differences. The choice was made to start the
numbering of the byte range at 1 to be consistent with the W3C pointer method
vocabulary.

## Metadata

- name: byteRange
- Nature: DataProperty
- Range: /Core/PositiveIntegerRange

## Summary @zh-Hans

定义了原始宿主文件中代码片段信息所适用的字节范围。

## Description @zh-Hans

该字段定义了原始宿主文件中代码片段信息所适用的字节范围。

字节范围与各种格式化问题无关，是引用差异最准确的方式。选择从1开始编号字节范围是为了与W3C指针方法词汇表保持一致。

