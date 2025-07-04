SPDX-License-Identifier: Community-Spec-1.0

# isOsiApproved

## Summary

Specifies whether the License is listed as approved by the
Open Source Initiative (OSI).

## Description

isOsiApproved specifies whether the
[Open Source Initiative (OSI)](https://opensource.org)
has listed this License as "approved" in their list of OSI Approved Licenses,
located at the time of this writing at
[OSI Approved Licenses](https://opensource.org/licenses).

A value of "true" indicates that the license is in the list of licenses that
OSI publishes as approved.

A value of "false" indicates that the license is explicitly not in the
corresponding list of OSI licenses (e.g., OSI has stated publicly that a
license is not approved).

If the isOsiApproved field is not specified, the SPDX data creator makes no
assertions about whether the License is approved by the OSI.

## Metadata

- name: isOsiApproved
- Nature: DataProperty
- Range: xsd:boolean

## Summary @zh-Hans

指定许可证（`License`）是否被列为已获开放源代码促进会（OSI）批准的许可证。

## Description @zh-Hans

`isOsiApproved`字段指定[开源促进会 (OSI)](https://opensource.org)是否在OSI批准许可证列表中已将本许可证列为“已批准”许可证，在本Spec写作之时位于[OSI批准许可证](https://opensource.org/licenses)。

如果数值为“真”，表示许可证在OSI公布的批准许可证列表中。

如果数值为“假”，表示许可证明确不在OSI相应的许可证列表中（例如，OSI已公开表示该许可证未获批准）。

如果未指定`isOsiApproved`字段，则 SPDX数据创建者不会做出关于许可证是否获得OSI批准的断言。
