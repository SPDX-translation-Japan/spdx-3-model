SPDX-License-Identifier: Community-Spec-1.0

# SupportType

## Summary

Indicates the type of support that is associated with an artifact.

## Description

SupportType is an enumeration of the various types of support commonly found for artifacts in the software supply chain. Specific details of what that support entails are provided by agreements between the producer and consumer of the artifact.

## Metadata

- name: SupportType

## Entries

- development: the artifact is in active development and is not considered ready for formal support from the supplier.
- support: the artifact has been released, and is supported from the supplier.   There is a validUntilDate that can provide additional information about the duration of support.
- deployed: in addition to being supported by the supplier, the software is known to have been deployed and is in use.  For a software as a service provider, this implies the software is now available as a service.
- limitedSupport: the artifact has been released, and there is limited support available from the supplier. There is a validUntilDate that can provide additional information about the duration of support.
- endOfSupport: there is a defined end of support for the artifact from the supplier.  This may also be referred to as end of life. There is a validUntilDate that can be used to signal when support ends for the artifact.
- noSupport: there is no support for the artifact from the supplier, consumer assumes any support obligations.
- noAssertion: no assertion about the type of support is made.   This is considered the default if no other support type is used.

## Summary @ja

アーティファクトに関連付けられたサポートの種類を示す。  

## Description @ja

SupportType は、ソフトウェアサプライチェーンにおいてアーティファクトに対して一般的に見られるさまざまなサポートの種類を列挙したものである。サポートの具体的な内容は、アーティファクトの提供者と利用者との間で結ばれる契約によって定義される。  

## Entries @ja

- development: アーティファクトは現在開発中であり、提供者からの正式なサポートを受けられる準備が整っていない状態である。  
- support: アーティファクトはリリース済みで、提供者からサポートが提供されている。有効期限を示す `validUntilDate` によって、サポートの期間に関する追加情報が提供される場合がある。  
- deployed: 提供者によるサポートがあることに加え、そのソフトウェアが実際に展開され、利用されていることを示す。ソフトウェアがサービスとして提供される場合（SaaS など）、この状態はソフトウェアがサービスとして利用可能になっていることを意味する。  
- limitedSupport: アーティファクトはリリース済みであり、提供者から限定的なサポートが提供される。有効期限を示す `validUntilDate` によって、サポートの期間に関する追加情報が提供される場合がある。  
- endOfSupport: 提供者によるアーティファクトのサポート終了が定義されている。これは「サポート終了」または「製品寿命終了（End of Life, EOL）」とも呼ばれる。有効期限を示す `validUntilDate` によって、サポート終了時期を通知できる。  
- noSupport: 提供者からアーティファクトへのサポートは一切提供されず、利用者がすべてのサポート責任を負う。  
- noAssertion: サポートの種類について何の表明も行われない。他のサポート種別が指定されていない場合、これがデフォルトとして扱われる。  
