SPDX-License-Identifier: Community-Spec-1.0

# SupportType

## Summary

Indicates the type of support that is associated with an artifact.

## Description

SupportType is an enumeration of the various types of support commonly found for artifacts in the software supply chain. Specific details of what that support entails are provided by agreements between the producer and consumer of the artifact.

## Metadata

- name: SupportType

## Entries

- development: The artifact is in active development and is not considered ready for formal support from the supplier.
- support: The artifact has been released, and is supported from the supplier. There is a validUntilDate that can provide additional information about the duration of support.
- deployed: In addition to being supported by the supplier, the software is known to have been deployed and is in use. For a software as a service provider, this implies the software is now available as a service.
- limitedSupport: The artifact has been released, and there is limited support available from the supplier. There is a validUntilDate that can provide additional information about the duration of support.
- endOfSupport: There is a defined end of support for the artifact from the supplier. This may also be referred to as end of life. There is a validUntilDate that can be used to signal when support ends for the artifact.
- noSupport: There is no support for the artifact from the supplier, consumer assumes any support obligations.
- noAssertion: No assertion about the type of support is made. This is considered the default if no other support type is used.

## Summary @zh-Hans

表示与`Artifact`相关的支持类型。

## Description @zh-Hans

`SupportType`是软件供应链中常见工件（inline？）支持类型的枚举。支持的具体内容由工件的生产者与消费者之间的协议提供。

## Entries @zh-Hans

- development: 工件处于积极开发中，尚未准备好接受供应商的正式支持。
- support: 工件已发布，并得到供应商支持。可以通过`validUntilDate`提供有关支持持续时间的附加（好像有文件里面翻的“额外”）信息。
- deployed: 除了得到供应商的支持外，软件已知已部署并正在使用。对于软件即服务提供商，这意味着软件现已作为服务提供。
- limitedSupport: 工件已发布，供应商提供有限的支持。可以通过`validUntilDate`提供有关支持持续时间的附加（同上）信息。
- endOfSupport: 供应商定义了对工件支持的结束时间。这也可以被称为生命周期的结束。可以通过`validUntilDate`提供有关工件的支持何时结束的信息。
- noSupport: 工件不受供应商支持，任何支持义务由消费者承担。
- noAssertion: 不对支持类型作出断言。如果不使用其他支持类型，则将其视为默认值。
