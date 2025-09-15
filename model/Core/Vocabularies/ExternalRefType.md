SPDX-License-Identifier: Community-Spec-1.0

# ExternalRefType

## Summary

Specifies the type of an external reference.

## Description

ExternalRefType specifies the type of an external reference.

## Metadata

- name: ExternalRefType

## Entries

- altDownloadLocation: A reference to an alternative download location.
- altWebPage: A reference to an alternative web page.
- binaryArtifact: A reference to binary artifacts related to a package.
- bower: A reference to a Bower package. The package locator format, looks like `package#version`, is defined in the "install" section of [Bower API documentation](https://bower.io/docs/api/#install).
- buildMeta: A reference build metadata related to a published package.
- buildSystem: A reference build system used to create or publish the package.
- chat: A reference to the instant messaging system used by the maintainer for a package.
- certificationReport: A reference to a certification report for a package from an accredited/independent body.
- componentAnalysisReport: A reference to a Software Composition Analysis (SCA) report.
- cwe: [Common Weakness Enumeration](https://csrc.nist.gov/glossary/term/common_weakness_enumeration). A reference to a source of software flaw defined within the official [CWE List](https://cwe.mitre.org/data/) that conforms to the [CWE specification](https://cwe.mitre.org/).
- documentation: A reference to the documentation for a package.
- dynamicAnalysisReport: A reference to a dynamic analysis report for a package.
- eolNotice: A reference to the End Of Sale (EOS) and/or End Of Life (EOL) information related to a package.
- exportControlAssessment: A reference to a export control assessment for a package.
- funding: A reference to funding information related to a package.
- issueTracker: A reference to the issue tracker for a package.
- mailingList: A reference to the mailing list used by the maintainer for a package.
- mavenCentral: A reference to a Maven repository artifact. The artifact locator format is defined in the [Maven documentation](https://maven.apache.org/guides/mini/guide-naming-conventions.html) and looks like `groupId:artifactId[:version]`.
- metrics: A reference to metrics related to package such as OpenSSF scorecards.
- npm: A reference to an npm package. The package locator format is defined in the [npm documentation](https://docs.npmjs.com/cli/v10/configuring-npm/package-json) and looks like `package@version`.
- nuget: A reference to a NuGet package. The package locator format is defined in the [NuGet documentation](https://docs.nuget.org) and looks like `package/version`.
- license: A reference to additional license information related to an artifact.
- other: Used when the type does not match any of the other options.
- privacyAssessment: A reference to a privacy assessment for a package.
- productMetadata: A reference to additional product metadata such as reference within organization's product catalog.
- purchaseOrder: A reference to a purchase order for a package.
- qualityAssessmentReport: A reference to a quality assessment for a package.
- releaseNotes: A reference to the release notes for a package.
- releaseHistory: A reference to a published list of releases for a package.
- riskAssessment: A reference to a risk assessment for a package.
- runtimeAnalysisReport: A reference to a runtime analysis report for a package.
- secureSoftwareAttestation: A reference to information assuring that the software is developed using security practices as defined by [NIST SP 800-218 Secure Software Development Framework (SSDF) Version 1.1](https://csrc.nist.gov/pubs/sp/800/218/final) or [CISA Secure Software Development Attestation Form](https://www.cisa.gov/resources-tools/resources/secure-software-development-attestation-form).
- securityAdvisory: A reference to a published security advisory (where advisory as defined per [ISO 29147:2018](https://www.iso.org/standard/72311.html)) that may affect one or more elements, e.g., vendor advisories or specific NVD entries.
- securityAdversaryModel: A reference to the security adversary model for a package.
- securityFix: A reference to the patch or source code that fixes a vulnerability.
- securityOther: A reference to related security information of unspecified type.
- securityPenTestReport: A reference to a [penetration test](https://en.wikipedia.org/wiki/Penetration_test) report for a package.
- securityPolicy: A reference to instructions for reporting newly discovered security vulnerabilities for a package.
- securityThreatModel: A reference the [security threat model](https://en.wikipedia.org/wiki/Threat_model) for a package.
- socialMedia: A reference to a social media channel for a package.
- sourceArtifact: A reference to an artifact containing the sources for a package.
- staticAnalysisReport: A reference to a static analysis report for a package.
- support: A reference to the software support channel or other support information for a package.
- vcs: A reference to a version control system related to a software artifact.
- vulnerabilityDisclosureReport: A reference to a Vulnerability Disclosure Report (VDR) which provides the software supplier's analysis and findings describing the impact (or lack of impact) that reported vulnerabilities have on packages or products in the supplier's SBOM as defined in [NIST SP 800-161 Cybersecurity Supply Chain Risk Management Practices for Systems and Organizations](https://csrc.nist.gov/pubs/sp/800/161/r1/final).
- vulnerabilityExploitabilityAssessment: A reference to a Vulnerability Exploitability eXchange (VEX) statement which provides information on whether a product is impacted by a specific vulnerability in an included package and, if affected, whether there are actions recommended to remediate. See also [NTIA VEX one-page summary](https://ntia.gov/files/ntia/publications/vex_one-page_summary.pdf).

## Summary @ja

外部参照の種類を指定する。

## Description @ja

ExternalRefType は、外部参照の種類を指定する。

## Entries @ja

- altDownloadLocation: 代替ダウンロード場所への参照。  
- altWebPage: 代替ウェブページへの参照。  
- binaryArtifact: パッケージに関連するバイナリアーティファクトへの参照。  
- bower: Bower パッケージへの参照。パッケージロケータ形式（例: `package#version`）は [Bower API ドキュメント](https://bower.io/docs/api/#install) の「install」セクションで定義されている。  
- buildMeta: 公開されたパッケージに関連するビルドメタデータへの参照。  
- buildSystem: パッケージを作成または公開するために使用されたビルドシステムへの参照。  
- chat: パッケージのメンテナが使用するインスタントメッセージングシステムへの参照。  
- certificationReport: 公認または独立した機関によるパッケージの認証レポートへの参照。  
- componentAnalysisReport: ソフトウェア構成解析 (SCA) レポートへの参照。  
- cwe: [Common Weakness Enumeration](https://csrc.nist.gov/glossary/term/common_weakness_enumeration)。公式 [CWE List](https://cwe.mitre.org/data/) 内で定義され、[CWE specification](https://cwe.mitre.org/) に準拠したソフトウェア欠陥の情報源への参照。  
- documentation: パッケージのドキュメントへの参照。  
- dynamicAnalysisReport: パッケージに関する動的解析レポートへの参照。  
- eolNotice: パッケージに関連する販売終了 (EOS) やサポート終了 (EOL) 情報への参照。  
- exportControlAssessment: パッケージに関する輸出規制評価への参照。  
- funding: パッケージに関連する資金提供情報への参照。  
- issueTracker: パッケージの課題管理システムへの参照。  
- mailingList: パッケージのメンテナが使用するメーリングリストへの参照。  
- mavenCentral: Maven リポジトリのアーティファクトへの参照。アーティファクトロケータ形式（例: `groupId:artifactId[:version]`）は [Maven ドキュメント](https://maven.apache.org/guides/mini/guide-naming-conventions.html) で定義されている。  
- metrics: OpenSSF スコアカードなど、パッケージに関連するメトリクスへの参照。  
- npm: npm パッケージへの参照。パッケージロケータ形式（例: `package@version`）は [npm ドキュメント](https://docs.npmjs.com/cli/v10/configuring-npm/package-json) で定義されている。  
- nuget: NuGet パッケージへの参照。パッケージロケータ形式（例: `package/version`）は [NuGet ドキュメント](https://docs.nuget.org) で定義されている。  
- license: アーティファクトに関連する追加のライセンス情報への参照。  
- other: 種類が他の選択肢のいずれにも一致しない場合に使用される。  
- privacyAssessment: パッケージに関するプライバシー評価への参照。  
- productMetadata: 組織の製品カタログ内での参照など、追加の製品メタデータへの参照。  
- purchaseOrder: パッケージの発注書への参照。  
- qualityAssessmentReport: パッケージに関する品質評価レポートへの参照。  
- releaseNotes: パッケージのリリースノートへの参照。  
- releaseHistory: パッケージの公開されたリリース一覧への参照。  
- riskAssessment: パッケージに関するリスク評価への参照。  
- runtimeAnalysisReport: パッケージに関する実行時解析レポートへの参照。  
- secureSoftwareAttestation: [NIST SP 800-218 Secure Software Development Framework (SSDF) Version 1.1](https://csrc.nist.gov/pubs/sp/800/218/final) または [CISA Secure Software Development Attestation Form](https://www.cisa.gov/resources-tools/resources/secure-software-development-attestation-form) で定義されたセキュリティ実践に従ってソフトウェアが開発されたことを保証する情報への参照。  
- securityAdvisory: 公開されたセキュリティアドバイザリへの参照（例: ベンダーのアドバイザリや特定の NVD エントリ）。[ISO 29147:2018](https://www.iso.org/standard/72311.html) で定義される「アドバイザリ」を意味する。  
- securityAdversaryModel: パッケージのセキュリティ敵対者モデルへの参照。  
- securityFix: 脆弱性を修正するパッチやソースコードへの参照。  
- securityOther: 特定されていない種類のセキュリティ関連情報への参照。  
- securityPenTestReport: パッケージに関する [侵入テスト](https://en.wikipedia.org/wiki/Penetration_test) レポートへの参照。  
- securityPolicy: パッケージにおいて新たに発見されたセキュリティ脆弱性を報告するための手順への参照。  
- securityThreatModel: パッケージの [セキュリティ脅威モデル](https://en.wikipedia.org/wiki/Threat_model) への参照。  
- socialMedia: パッケージのソーシャルメディアチャネルへの参照。  
- sourceArtifact: パッケージのソースを含むアーティファクトへの参照。  
- staticAnalysisReport: パッケージに関する静的解析レポートへの参照。  
- support: パッケージのソフトウェアサポートチャネルまたはその他のサポート情報への参照。  
- vcs: ソフトウェアアーティファクトに関連するバージョン管理システムへの参照。  
- vulnerabilityDisclosureReport: 脆弱性開示報告 (VDR) への参照。ソフトウェア供給者が提供する分析や調査結果を含み、SBOM 内のパッケージや製品に報告された脆弱性が影響を与えるかどうかを説明する。[NIST SP 800-161](https://csrc.nist.gov/pubs/sp/800/161/r1/final) で定義される。  
- vulnerabilityExploitabilityAssessment: 脆弱性利用可能性交換 (VEX) ステートメントへの参照。特定のパッケージに含まれる脆弱性が製品に影響を与えるかどうか、影響がある場合は推奨される対応策があるかを示す。詳細は [NTIA VEX one-page summary](https://ntia.gov/files/ntia/publications/vex_one-page_summary.pdf) を参照。
