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
- exportControlAssessment: A reference to an export control assessment for a package.
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

## Summary @zh-Hans

指定`ExternalRef`的类型。

## Description @zh-Hans

`ExternalRefType`指定`ExternalRef`的类型。

## Entries @zh-Hans

- altDownloadLocation: 备用下载位置的引用。
- altWebPage: 备用网页的引用。
- binaryArtifact: 与包相关的二进制工件的引用。
- bower: Bower包的引用。包定位符格式在[Bower API文档](https://bower.io/docs/api/#install)"install"部分中定义，如`package#version`。
- buildMeta: 与已发布包相关的构建元数据的引用。
- buildSystem: 用于创建或发布包的构建系统的引用。
- chat: 包维护者使用的即时通讯系统的引用。
- certificationReport: 来自认证/独立机构的包认证报告的引用。
- componentAnalysisReport: 软件组成分析（Software Composition Analysis，SCA）报告的引用。
- cwe: [通用缺陷列表（CWE）](https://csrc.nist.gov/glossary/term/common_weakness_enumeration)。对[CWE清单](https://cwe.mitre.org/data/)中的软件缺陷来源的引用，符合[CWE规范](https://cwe.mitre.org/)。
- documentation: 包文档的引用。
- dynamicAnalysisReport: 包动态分析报告的引用。
- eolNotice: 与包相关的销售终止（EOS）和/或寿命终止（EOL）信息的引用。
- exportControlAssessment: 包出口控制评估的引用。
- funding: 与包相关的资助信息的引用。
- issueTracker: 包问题跟踪器的引用。
- license: 与工件相关的附加许可证信息的引用。
- mailingList: 包维护者使用的邮件列表的引用。
- mavenCentral: Maven仓库工件的引用。工件定位符格式，在[Maven文档](https://maven.apache.org/guides/mini/guide-naming-conventions.html)中定义，如`groupId:artifactId[:version]`。
- metrics: 与包相关的指标的引用，如OpenSSF记分卡。
- npm: npm包的引用。包定位符格式在[npm文档](https://docs.npmjs.com/cli/v10/configuring-npm/package-json)中定义，如`package@version`。
- nuget: NuGet包的引用。包定位符格式在[NuGet文档](https://docs.nuget.org)中定义，如`package/version`。
- other: 用于类型与其他选项不匹配的情况。
- privacyAssessment: 包的隐私评估的引用。
- productMetadata: 附加产品元数据的引用，例如组织产品目录中的参考。
- purchaseOrder: 包的采购订单的引用。
- qualityAssessmentReport: 包的质量评估的引用。
- releaseHistory: 包的已发布版本列表的引用。
- releaseNotes: 包发行说明的引用。
- riskAssessment: 包的风险评估的引用。
- runtimeAnalysisReport: 包的运行时分析报告的引用。
- secureSoftwareAttestation: 信息引用，确保软件按照[NIST SP 800-218安全软件开发框架 （SSDF）第1.1版](https://csrc.nist.gov/pubs/sp/800/218/final)或[CISA软件开发安全性证明表](https://www.cisa.gov/resources-tools/resources/secure-software-development-attestation-form)中定义的安全实践进行开发。
- securityAdversaryModel: 包的安全对手模型的引用。
- securityAdvisory: 可能影响一个或多个元素的已发布安全公告（根据[ISO 29147:2018](https://www.iso.org/Standard/72311.html)定义）的引用，例如供应商公告或特定的NVD条目。
- securityFix: 修复漏洞的补丁或源代码的引用。
- securityOther: 未指定类型的相关安全信息的引用。
- securityPenTestReport: 包的[渗透测试](https://en.wikipedia.org/wiki/Penetration_test)报告的引用。
- securityPolicy: 报告新发现的包安全漏洞的说明的引用。
- securityThreatModel: 包的[安全威胁模型](https://en.wikipedia.org/wiki/Threat_model)的引用。
- socialMedia: 包的社交媒体渠道的引用。
- sourceArtifact: 包含包源的工件的引用。
- staticAnalysisReport: 包的静态分析报告的引用。
- support: 软件支持渠道或包的其他支持信息的引用。
- vcs: 与软件工件相关的版本控制系统的引用。
- vulnerabilityDisclosureReport: 漏洞披露报告（Vulnerability Disclosure Report，VDR）的引用，该报告提供软件供应商的分析和发现，说明报告中的漏洞对供应商SBOM中包或产品的影响（或没有影响），如[NIST SP 800-161网络安全供应链风险管理系统和组织实践](https://csrc.nist.gov/pubs/sp/800/161/r1/final)定义。
- vulnerabilityExploitabilityAssessment: 漏洞可利用性交换（Vulnerability Exploitability eXchange，VEX）声明的引用，提供有关产品是否受包含包中特定漏洞影响的信息，如果受影响，是否有建议的补救措施。另见[NTIA VEX单页摘要](https://ntia.gov/files/ntia/publications/vex_one-page_summary.pdf)。
