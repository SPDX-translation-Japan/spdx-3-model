SPDX-License-Identifier: Community-Spec-1.0

# SsvcDecisionType

## Summary

Specifies the SSVC decision type.

## Description

SsvcDecisionType specifies the type of decision that's been made according to
the
[Stakeholder-Specific Vulnerability Categorization (SSVC)](https://www.cisa.gov/stakeholder-specific-vulnerability-categorization-ssvc).

## Metadata

- name: SsvcDecisionType

## Entries

- act: The vulnerability requires attention from the organization's internal, supervisory-level and leadership-level individuals. Necessary actions include requesting assistance or information about the vulnerability, as well as publishing a notification either internally and/or externally. Typically, internal groups would meet to determine the overall response and then execute agreed upon actions. CISA recommends remediating Act vulnerabilities as soon as possible.
- attend: The vulnerability requires attention from the organization's internal, supervisory-level individuals. Necessary actions include requesting assistance or information about the vulnerability, and may involve publishing a notification either internally and/or externally. CISA recommends remediating Attend vulnerabilities sooner than standard update timelines.
- track: The vulnerability does not require action at this time. The organization would continue to track the vulnerability and reassess it if new information becomes available. CISA recommends remediating Track vulnerabilities within standard update timelines.
- trackStar: ("Track\*" in the SSVC spec) The vulnerability contains specific characteristics that may require closer monitoring for changes. CISA recommends remediating Track\* vulnerabilities within standard update timelines.

## Summary @zh-Hans

指定SSVC决策类型。

## Description @zh-Hans

`SsvcDecisionType`指定根据[利益相关者特定漏洞分类（SSVC）指南](https://www.cisa.gov/stakeholder-specific-vulnerability-categorization-ssvc)做出的决策类型。

## Entries @zh-Hans

- act: 此漏洞需要组织内部、监管层和领导层的人员关注。必要的措施包括请求对此漏洞的帮助或信息，并在内部和/或外部发布通知。通常，内部团队会召开会议确定整体响应，然后执行商定的措施。CISA建议尽快修复Act类漏洞。
- attend: 此漏洞需要组织内部和监管层的人员关注。必要的措施包括请求对此漏洞的帮助或信息，可能需要在内部和/或外部发布通知。CISA建议尽早修复Attend类漏洞，先于标准更新时间表。
- track: 此漏洞目前无需采取任何措施。组织将继续跟踪漏洞，并在获得新信息时重新评估漏洞。CISA建议在标准更新时间表内修复Track类漏洞。
- trackStar: （SSVC规范中为“Track\*”）此漏洞具有特定特征，可能需要更密切地监控其变化。CISA建议在标准更新时间表内修复Track\*类漏洞。

# Summary @ja

SSVC の意思決定タイプを指定する。

## Description @ja

SsvcDecisionType は、
[Stakeholder-Specific Vulnerability Categorization (SSVC)](https://www.cisa.gov/stakeholder-specific-vulnerability-categorization-ssvc)
に基づいて下された意思決定のタイプを指定する。


## Entries @ja

- act: 脆弱性は組織内の管理職レベルおよびリーダーシップレベルの個人による対応を必要とする。必要な対応には、脆弱性に関する支援や情報の要請、または内部および／または外部への通知の発行が含まれる。通常、内部チームが集まり全体的な対応方針を決定し、合意されたアクションを実行する。CISA は Act 脆弱性について、できるだけ早急に修正することを推奨している。
- attend: 脆弱性は組織内の管理職レベルの個人による対応を必要とする。必要な対応には、脆弱性に関する支援や情報の要請が含まれ、場合によっては内部および／または外部への通知の発行が伴う。CISA は Attend 脆弱性について、通常の更新スケジュールよりも早い対応を推奨している。
- track: 現時点では対応を必要としない脆弱性である。組織は引き続き脆弱性を監視し、新たな情報が得られた場合に再評価を行う。CISA は Track 脆弱性について、通常の更新スケジュール内で修正することを推奨している。
- trackStar（SSVC 仕様では "Track*"）: 特定の特性を持ち、状況の変化をより注意深く監視する必要がある脆弱性である。CISA は Track* 脆弱性について、通常の更新スケジュール内で修正することを推奨している。

