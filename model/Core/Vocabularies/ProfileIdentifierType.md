SPDX-License-Identifier: Community-Spec-1.0

# ProfileIdentifierType

## Summary

Enumeration of the valid profiles.

## Description

There are a set of profiles that have been defined by a profile team.

A profile consists of a namespace that may add properties and classes to the
Core profile unique to the domain covered by the profile.

The profile may also contain additional restrictions on existing properties and
classes defined in other profiles.

If the creator of an SPDX collection of elements includes a profile in the list
of profileConformance, they are claiming that all contained elements conform
to all restrictions defined for that profile.

## Metadata

- name: ProfileIdentifierType

## Entries

- core: the element follows the Core profile specification
- software: the element follows the Software profile specification
- simpleLicensing: the element follows the SimpleLicensing profile specification
- expandedLicensing: the element follows the ExpandedLicensing profile specification
- security: the element follows the Security profile specification
- build: the element follows the Build profile specification
- ai: the element follows the AI profile specification
- dataset: the element follows the Dataset profile specification
- extension: the element follows the Extension profile specification
- lite: the element follows the Lite profile specification

## Summary @zh-Hans

有效配置文件的枚举。

## Description @zh-Hans

配置文件团队定义了一组配置文件。

一个配置文件包含一个命名空间，可以向`Core`配置文件添加特定于该领域的属性和类。

配置文件还可以对其他配置文件中已定义的属性和类施加额外的限制。

如果SPDX `Element`（拿不准需不需要inline）集合的创建者在`profileConformance`列表中包含一个配置文件，则表明所有包含的`Element`都符合该配置文件定义的所有限制。

## Entries @zh-Hans

- core: `Element`遵循`Core`配置文件规范。
- software: `Element`遵循`Software`配置文件规范。
- simpleLicensing: `Element`遵循`SimpleLicensing`配置文件规范。
- expandedLicensing: `Element`遵循`ExpandedLicensing`配置文件规范。
- security: `Element`遵循`Security`配置文件规范。
- build: `Element`遵循`Build`配置文件规范。
- ai: `Element`遵循`AI`配置文件规范。
- dataset: `Element`遵循`Dataset`配置文件规范。
- extension: `Element`遵循`Extension`配置文件规范。
- lite: `Element`遵循`Lite`配置文件规范。
