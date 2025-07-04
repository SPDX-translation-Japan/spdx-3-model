SPDX-License-Identifier: Community-Spec-1.0

# isFsfLibre

## Summary

Specifies whether the License is listed as free by the
Free Software Foundation (FSF).

## Description

isFsfLibre specifies whether the
[Free Software Foundation (FSF)](https://fsf.org)
has listed this License as "free" in their commentary on licenses, located at
the time of this writing at
[Various Licenses and Comments about Them](https://www.gnu.org/licenses/license-list.en.html).

A value of "true" indicates that the license is in the list of licenses that
FSF publishes as libre.

A value of "false" indicates that the license is explicitly not in the
corresponding list of FSF libre licenses (e.g., FSF has the license on a
non-free list).

If the isFsfLibre field is not specified, the SPDX data creator makes no
assertions about whether the License is listed in the FSF's commentary.

## Metadata

- name: isFsfLibre
- Nature: DataProperty
- Range: xsd:boolean

## Summary @zh-Hans

指定许可证（`License`）是否被自由软件基金会（FSF）列为自由(许可证)。

## Description @zh-Hans

`isFsfLibre`字段指定[自由软件基金会 (FSF)](https://fsf.org)是否在其许可证评论中，将本许可证(`License`)列为“自由”许可证，在本Spec写作之时该评论位于 [各种许可证及其相关评论](https://www.gnu.org/licenses/license-list.en.html)。

如果数值为“真”，表示许可证在FSF公布的自由许可证列表中。

如果数值为“假”，表示许可证明确不在FSF相应的自由许可证列表中（例如，FSF将该许可证列于非自由许可证列表中）。

如果未指定`isFsfLibre`字段，则 SPDX 数据创建者不会做出有关许可证是否列在FSF评论中的断言。
