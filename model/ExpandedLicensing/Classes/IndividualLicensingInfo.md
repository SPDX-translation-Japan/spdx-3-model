SPDX-License-Identifier: Community-Spec-1.0

# IndividualLicensingInfo

## Summary

A concrete subclass of AnyLicenseInfo used by Individuals in the
ExpandedLicensing profile.

## Description

Individuals, such as NoneLicense and NoAssertionLicense, need to reference a
concrete subclass of AnyLicenseInfo.

This class provides the type used by the individuals.

## Metadata

- name: IndividualLicensingInfo
- SubclassOf: /SimpleLicensing/AnyLicenseInfo
- Instantiability: Concrete

## Summary @zh-Hans

在已扩展许可证（`ExpandedLicensing`）配置文件中特殊使用的`AnyLicenseInfo`的具体子类。

## Description @zh-Hans

特殊许可证，例如：无许可证（`NoneLicense`） 和无法断言许可证（`NoAssertionLicense`），需要引用一个`AnyLicenseInfo` 的具体子类。

这个类提供了特殊使用类型。
