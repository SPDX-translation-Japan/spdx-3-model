SPDX-License-Identifier: Community-Spec-1.0

# lineRange

## Summary

Defines the line range in the original host file that the snippet information
applies to.

## Description

This field defines the line range in the original host file that the snippet
information applies to.

If there is a disagreement between the byte range and line range, the byte
range values will take precedence.

A range of lines is a convenient reference for those files where there is a
known line delimiter.
The choice was made to start the numbering of the lines at 1 to be consistent
with the W3C pointer method vocabulary.

## Metadata

- name: lineRange
- Nature: DataProperty
- Range: /Core/PositiveIntegerRange

## Summary @zh-Hans

定义了原始宿主文件中代码片段信息所适用的行范围。

## Description @zh-Hans

该字段定义了原始宿主文件中代码片段信息所适用的行范围。

如果字节范围(`byteRange`)和行范围(`lineRange`)之间存在不一致，将以字节范围值为准。

行范围对于那些有已知行分隔符的文件是一个方便的引用。

选择从1开始对行进行编号是为了与W3C指针方法词汇表保持一致。

## Summary @jp

スニペット情報が適用される元のホストファイル内の行範囲を定義する。

## Description @jp

このフィールドは、スニペット情報が適用される元のホストファイル内の行範囲を定義する。

バイト範囲と行範囲が不一致がある場合、バイト範囲の値が優先される。

行範囲は、行区切りが既知のファイルの場合に便利な参照方法である。W3Cのポインターメソッド語彙と一貫性を保つため、行番号は1から始まるようにした。
