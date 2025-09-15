SPDX-License-Identifier: Community-Spec-1.0

# RelationshipType

## Summary

Information about the relationship between two Elements.

## Description

Provides information about the relationship between two Elements.
For example, you can represent a relationship between two different Files,
between a Package and a File, between two Packages, or between one SpdxDocument
and another SpdxDocument.

Relationship names should be descriptive enough to easily deduce the correct direction
from their name. The best way to do this is to make sure that the relationship
name completes the sentence:

`from` (is) (a) `RELATIONSHIP` `to`

## Metadata

- name: RelationshipType

## Entries

- affects: The `from` Vulnerability affects each `to` Element. The use of the `affects` type is constrained to `VexAffectedVulnAssessmentRelationship` classed relationships.
- amendedBy: The `from` Element is amended by each `to` Element.
- ancestorOf: The `from` Element is an ancestor of each `to` Element.
- availableFrom: The `from` Element is available from the additional supplier described by each `to` Element.
- configures: The `from` Element is a configuration applied to each `to` Element, during a LifecycleScopeType period.
- contains: The `from` Element contains each `to` Element.
- coordinatedBy: The `from` Vulnerability is coordinatedBy the `to` Agent(s) (vendor, researcher, or consumer agent).
- copiedTo: The `from` Element has been copied to each `to` Element.
- delegatedTo: The `from` Agent is delegating an action to the Agent of the `to` Relationship (which must be of type invokedBy), during a LifecycleScopeType (e.g. the `to` invokedBy Relationship is being done on behalf of `from`).
- dependsOn: The `from` Element depends on each `to` Element, during a LifecycleScopeType period.
- descendantOf: The `from` Element is a descendant of each `to` Element.
- describes: The `from` Element describes each `to` Element. To denote the root(s) of a tree of elements in a collection, the rootElement property should be used.
- doesNotAffect: The `from` Vulnerability has no impact on each `to` Element. The use of the `doesNotAffect` is constrained to `VexNotAffectedVulnAssessmentRelationship` classed relationships.
- expandsTo: The `from` archive expands out as an artifact described by each `to` Element.
- exploitCreatedBy: The `from` Vulnerability has had an exploit created against it by each `to` Agent.
- fixedBy: Designates a `from` Vulnerability has been fixed by the `to` Agent(s).
- fixedIn: A `from` Vulnerability has been fixed in each `to` Element. The use of the `fixedIn` type is constrained to `VexFixedVulnAssessmentRelationship` classed relationships.
- foundBy: Designates a `from` Vulnerability was originally discovered by the `to` Agent(s).
- generates: The `from` Element generates each `to` Element.
- hasAddedFile: Every `to` Element is a file added to the `from` Element (`from` hasAddedFile `to`).
- hasAssessmentFor: Relates a `from` Vulnerability and each `to` Element with a security assessment. To be used with `VulnAssessmentRelationship` types.
- hasAssociatedVulnerability: Used to associate a `from` Artifact with each `to` Vulnerability.
- hasConcludedLicense: The `from` SoftwareArtifact is concluded by the SPDX data creator to be governed by each `to` license.
- hasDataFile: The `from` Element treats each `to` Element as a data file. A data file is an artifact that stores data required or optional for the `from` Element's functionality. A data file can be a database file, an index file, a log file, an AI model file, a calibration data file, a temporary file, a backup file, and more. For AI training dataset, test dataset, test artifact, configuration data, build input data, and build output data, please consider using the more specific relationship types: `trainedOn`, `testedOn`, `hasTest`, `configures`, `hasInput`, and `hasOutput`, respectively. This relationship does not imply dependency.
- hasDeclaredLicense: The `from` SoftwareArtifact was discovered to actually contain each `to` license, for example as detected by use of automated tooling.
- hasDeletedFile: Every `to` Element is a file deleted from the `from` Element (`from` hasDeletedFile `to`).
- hasDependencyManifest: The `from` Element has manifest files that contain dependency information in each `to` Element.
- hasDistributionArtifact: The `from` Element is distributed as an artifact in each `to` Element (e.g. an RPM or archive file).
- hasDocumentation: The `from` Element is documented by each `to` Element.
- hasDynamicLink: The `from` Element dynamically links in each `to` Element, during a LifecycleScopeType period.
- hasEvidence: Every `to` Element is considered as evidence for the `from` Element (`from` hasEvidence `to`).
- hasExample: Every `to` Element is an example for the `from` Element (`from` hasExample `to`).
- hasHost: The `from` Build was run on the `to` Element during a LifecycleScopeType period (e.g. the host that the build runs on).
- hasInput: The `from` Build has each `to` Element as an input, during a LifecycleScopeType period.
- hasMetadata: Every `to` Element is metadata about the `from` Element (`from` hasMetadata `to`).
- hasOptionalComponent: Every `to` Element is an optional component of the `from` Element (`from` hasOptionalComponent `to`).
- hasOptionalDependency: The `from` Element optionally depends on each `to` Element, during a LifecycleScopeType period.
- hasOutput: The `from` Build element generates each `to` Element as an output, during a LifecycleScopeType period.
- hasPrerequisite: The `from` Element has a prerequisite on each `to` Element, during a LifecycleScopeType period.
- hasProvidedDependency: The `from` Element has a dependency on each `to` Element, dependency is not in the distributed artifact, but assumed to be provided, during a LifecycleScopeType period.
- hasRequirement: The `from` Element has a requirement on each `to` Element, during a LifecycleScopeType period.
- hasSpecification: Every `to` Element is a specification for the `from` Element (`from` hasSpecification `to`), during a LifecycleScopeType period.
- hasStaticLink: The `from` Element statically links in each `to` Element, during a LifecycleScopeType period.
- hasTest: Every `to` Element is a test artifact for the `from` Element (`from` hasTest `to`), during a LifecycleScopeType period.
- hasTestCase: Every `to` Element is a test case for the `from` Element (`from` hasTestCase `to`).
- hasVariant: Every `to` Element is a variant the `from` Element (`from` hasVariant `to`).
- invokedBy: The `from` Element was invoked by the `to` Agent, during a LifecycleScopeType period (for example, a Build element that describes a build step).
- modifiedBy: The `from` Element is modified by each `to` Element.
- other: Every `to` Element is related to the `from` Element where the relationship type is not described by any of the SPDX relationship types (this relationship is directionless).
- packagedBy: Every `to` Element is a packaged instance of the `from` Element (`from` packagedBy `to`).
- patchedBy: Every `to` Element is a patch for the `from` Element (`from` patchedBy `to`).
- publishedBy: Designates a `from` Vulnerability was made available for public use or reference by each `to` Agent.
- reportedBy: Designates a `from` Vulnerability was first reported to a project, vendor, or tracking database for formal identification by each `to` Agent.
- republishedBy: Designates a `from` Vulnerability's details were tracked, aggregated, and/or enriched to improve context (i.e. NVD) by each `to` Agent.
- serializedInArtifact: The `from` SpdxDocument can be found in a serialized form in each `to` Artifact.
- testedOn: The `from` Element has been tested on the `to` Element(s).
- trainedOn: The `from` Element has been trained on the `to` Element(s).
- underInvestigationFor: The `from` Vulnerability impact is being investigated for each `to` Element. The use of the `underInvestigationFor` type is constrained to `VexUnderInvestigationVulnAssessmentRelationship` classed relationships.
- usesTool: The `from` Element uses each `to` Element as a tool, during a LifecycleScopeType period.

## Summary @ja

2つの要素間の関係に関する情報。  

## Description @ja

2つの要素間の関係に関する情報を提供する。  
例えば、2つの異なるファイル間、パッケージとファイル間、2つのパッケージ間、あるいは SpdxDocument 同士の関係を表現できる。  

関係の名前は、その名前から正しい方向性を容易に推測できる程度に記述的であるべきである。  
最良の方法は、関係名が次の文を完成させるようにすることである。  

`from` (is) (a) `RELATIONSHIP` `to`  

## Entries @ja

- affects: `from` 脆弱性は各 `to` 要素に影響を与える。`affects` 型の使用は `VexAffectedVulnAssessmentRelationship` に限定される。  
- amendedBy: `from` 要素は各 `to` 要素によって修正される。  
- ancestorOf: `from` 要素は各 `to` 要素の祖先である。  
- availableFrom: `from` 要素は各 `to` 要素で記述された追加の提供者から利用可能である。  
- configures: `from` 要素は LifecycleScopeType の期間中に各 `to` 要素に適用される設定である。  
- contains: `from` 要素は各 `to` 要素を含む。  
- coordinatedBy: `from` 脆弱性は `to` エージェント（ベンダー、研究者、または利用者）によって調整される。  
- copiedTo: `from` 要素は各 `to` 要素にコピーされる。  
- delegatedTo: `from` エージェントは、LifecycleScopeType の期間中に、`to` の関係（invokedBy 型でなければならない）を持つエージェントにアクションを委任する（例: `to` invokedBy 関係が `from` の代理で実行される）。  
- dependsOn: `from` 要素は LifecycleScopeType の期間中、各 `to` 要素に依存する。  
- descendantOf: `from` 要素は各 `to` 要素の子孫である。  
- describes: `from` 要素は各 `to` 要素を記述する。コレクション内の要素ツリーの根を示すには rootElement プロパティを使用する。  
- doesNotAffect: `from` 脆弱性は各 `to` 要素に影響を与えない。`doesNotAffect` の使用は `VexNotAffectedVulnAssessmentRelationship` に限定される。  
- expandsTo: `from` アーカイブは各 `to` 要素で記述された成果物として展開される。  
- exploitCreatedBy: `from` 脆弱性に対して各 `to` エージェントによってエクスプロイトが作成される。  
- fixedBy: `from` 脆弱性が `to` エージェントによって修正されたことを示す。  
- fixedIn: `from` 脆弱性は各 `to` 要素内で修正されている。`fixedIn` の使用は `VexFixedVulnAssessmentRelationship` に限定される。  
- foundBy: `from` 脆弱性が最初に `to` エージェントによって発見されたことを示す。  
- generates: `from` 要素は各 `to` 要素を生成する。  
- hasAddedFile: 各 `to` 要素は `from` 要素に追加されたファイルである。  
- hasAssessmentFor: `from` 脆弱性と各 `to` 要素をセキュリティ評価で関連付ける。`VulnAssessmentRelationship` 型で使用される。  
- hasAssociatedVulnerability: `from` アーティファクトを各 `to` 脆弱性と関連付けるために使用される。  
- hasConcludedLicense: `from` SoftwareArtifact が SPDX データ作成者によって各 `to` ライセンスに準拠すると結論づけられる。  
- hasDataFile: `from` 要素が各 `to` 要素をデータファイルとして扱う。データファイルは、機能に必要または任意のデータを保存する成果物であり、データベース、インデックス、ログ、AI モデル、キャリブレーションデータ、一時ファイル、バックアップファイルなどが含まれる。AI 用データについては `trainedOn`, `testedOn`, `hasTest`, `configures`, `hasInput`, `hasOutput` を使用することを推奨。この関係は依存を意味しない。  
- hasDeclaredLicense: `from` SoftwareArtifact が実際に各 `to` ライセンスを含んでいることが検出される。  
- hasDeletedFile: 各 `to` 要素は `from` 要素から削除されたファイルである。  
- hasDependencyManifest: `from` 要素は各 `to` 要素に依存関係情報を含むマニフェストファイルを持つ。  
- hasDistributionArtifact: `from` 要素は各 `to` 要素に成果物として配布される（例: RPM やアーカイブ）。  
- hasDocumentation: `from` 要素は各 `to` 要素によって文書化されている。  
- hasDynamicLink: `from` 要素は LifecycleScopeType の期間中に各 `to` 要素に動的リンクする。  
- hasEvidence: 各 `to` 要素は `from` 要素の証拠と見なされる。  
- hasExample: 各 `to` 要素は `from` 要素の例である。  
- hasHost: `from` ビルドは LifecycleScopeType の期間中に `to` 要素上で実行される。  
- hasInput: `from` ビルドは LifecycleScopeType の期間中に各 `to` 要素を入力として持つ。  
- hasMetadata: 各 `to` 要素は `from` 要素に関するメタデータである。  
- hasOptionalComponent: 各 `to` 要素は `from` 要素のオプションコンポーネントである。  
- hasOptionalDependency: `from` 要素は LifecycleScopeType の期間中に各 `to` 要素にオプションで依存する。  
- hasOutput: `from` ビルド要素は LifecycleScopeType の期間中に各 `to` 要素を出力として生成する。  
- hasPrerequisite: `from` 要素は LifecycleScopeType の期間中に各 `to` 要素を前提条件として持つ。  
- hasProvidedDependency: `from` 要素は LifecycleScopeType の期間中に各 `to` 要素に依存するが、依存は配布成果物には含まれず提供されるものと仮定される。  
- hasRequirement: `from` 要素は LifecycleScopeType の期間中に各 `to` 要素を要求する。  
- hasSpecification: 各 `to` 要素は LifecycleScopeType の期間中に `from` 要素の仕様である。  
- hasStaticLink: `from` 要素は LifecycleScopeType の期間中に各 `to` 要素に静的リンクする。  
- hasTest: 各 `to` 要素は LifecycleScopeType の期間中に `from` 要素のテスト成果物である。  
- hasTestCase: 各 `to` 要素は `from` 要素のテストケースである。  
- hasVariant: 各 `to` 要素は `from` 要素のバリアントである。  
- invokedBy: `from` 要素は LifecycleScopeType の期間中に `to` エージェントによって呼び出される。  
- modifiedBy: `from` 要素は各 `to` 要素によって変更される。  
- other: 各 `to` 要素は `from` 要素と関連するが、その関係の種類は SPDX に定義されていない（方向性を持たない）。  
- packagedBy: 各 `to` 要素は `from` 要素のパッケージ化されたインスタンスである。  
- patchedBy: 各 `to` 要素は `from` 要素に対するパッチである。  
- publishedBy: `from` 脆弱性が各 `to` エージェントによって公開利用可能にされたことを示す。  
- reportedBy: `from` 脆弱性が各 `to` エージェントによって最初に報告されたことを示す。  
- republishedBy: `from` 脆弱性の詳細が各 `to` エージェントによって追跡、集約、補強されたことを示す（例: NVD）。  
- serializedInArtifact: `from` SpdxDocument は各 `to` 成果物内にシリアライズされた形式で存在する。  
- testedOn: `from` 要素は `to` 要素上でテストされる。  
- trainedOn: `from` 要素は `to` 要素上で訓練される。  
- underInvestigationFor: `from` 脆弱性の影響が各 `to` 要素について調査中である。`underInvestigationFor` の使用は `VexUnderInvestigationVulnAssessmentRelationship` に限定される。  
- usesTool: `from` 要素は LifecycleScopeType の期間中に各 `to` 要素をツールとして使用する。  
