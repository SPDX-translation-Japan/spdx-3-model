SPDX-License-Identifier: Community-Spec-1.0

# isDeprecatedAdditionId

## Summary

Specifies whether an additional text identifier has been marked as deprecated.

## Description

The isDeprecatedAdditionId property specifies whether an identifier for a
LicenseAddition has been marked as deprecated. If the property is not defined,
then it is presumed to be false (i.e., not deprecated).

If the LicenseAddition is included on the
[SPDX License Exceptions](https://spdx.org/licenses/exceptions-index.html),
then the `deprecatedVersion` property indicates on which version release of the
Exceptions List it was first marked as deprecated.

"Deprecated" in this context refers to deprecating the use of the
_identifier_, not the underlying license addition. In other words, even if a
LicenseAddition's author or steward has stated that a particular
LicenseAddition generally should not be used, that would _not_ mean that the
LicenseAddition's identifier is "deprecated." Rather, a LicenseAddition
operator is typically marked as "deprecated" when it is determined that use of
another identifier is preferable.

## Metadata

- name: isDeprecatedAdditionId
- Nature: DataProperty
- Range: xsd:boolean

## Summary @zh-Hans

指定一个附加文本标识符是否已标记为已弃用。

## Description @zh-Hans

是否是已弃用的附加内容ID（`isDeprecatedAdditionId`）属性，指定了许可证附加内容（`LicenseAddition`）的标识符是否已标记为已弃用。如果未定义该属性，那么将其假定为是假的（即：并未弃用）。

如果许可证附加内容（`LicenseAddition`）包含在[SPDX许可证例外](https://spdx.org/licenses/exceptions-index.html)中，那么已弃用版本（`deprecatedVersion`）这个属性表示其在例外列表的哪个版本上首次被标记为已弃用。

在此上下文中，“已弃用”是指已弃用 *标识符* ，而不是弃用基础的许可证附加内容（`LicenseAddition`）。换句话说，即使许可证附加内容（`LicenseAddition`）的作者或管理员已经声明通常不应使用特定的许可证附加内容（`LicenseAddition`），这 *并不* 意味着该许可证附加内容（`LicenseAddition`）的标识符“已弃用”。相反，当确定使用其他标识符更可取时，许可证附加内容（`LicenseAddition`）的操作符通常会被标记为“已弃用”。
