SPDX-License-Identifier: Community-Spec-1.0

# informationAboutApplication

## Summary

Provides relevant information about the AI software, not including the model
description.

## Description

A free-form text description of how the AI model is used within the software.

It should include any relevant information, such as pre-processing steps,
third-party APIs, and other pertinent details.

It can also include:

- Functionality provided by the AI model within the software application,
  including: any specific tasks or decisions it is designed to perform;
  any pre-processing steps that are applied to the input data before it is
  fed into the AI model for inference, such as data cleaning, normalization,
  or feature extraction;
  and any third-party APIs or services that are used in conjunction with
  the AI model, such as data sources, cloud services, or other AI models.
- Description of any dependencies or requirements needed to run the AI model
  within the software application, including: specific hardware,
  software libraries, and operating systems.

## Metadata

- name: informationAboutApplication
- Nature: DataProperty
- Range: xsd:string

## Summary @zh-Hans

提供有关AI应用的相关内容，但并不包括对模型描述。

## Description @zh-Hans

对软件中AI模型使用的自由格式文本描述。

它应包括任何相关信息，例如预处理步骤、第三方API以及其他相关细节。

它还可以包括：

- AI模型在软件应用中提供的功能，包括：它被设计来执行的任何特定任务或决策；在输入数据被送入AI模型进行推理之前，对其应用的任何预处理步骤，例如数据清洗、标准化或特征提取；以及与AI模型结合使用的任何第三方API或服务，例如数据源、云服务或其他AI模型。
- 描述任何运行软件中AI模型所需的依赖项或要求，包括：特定的硬件、软件库和操作系统。

## Summary @ja

モデルの説明を除いた、AIソフトウェアに関する関連情報を提供する。

## Description @ja

AIモデルがソフトウェア内でどのように使用されているかに関する自由形式のテキストによる説明を提供する。

この説明には、前処理の手順、サードパーティのAPI、その他関連する詳細など、関連情報を含めることが望ましい。

また、以下のような内容も含めることができる：

- ソフトウェアアプリケーション内でAIモデルが提供する機能の説明。たとえば、AIモデルが実行するよう設計されている特定のタスクや意思決定、推論に入力される前に適用される前処理ステップ（データクリーニング、正規化、特徴抽出など）、AIモデルと併用されるサードパーティのAPIやサービス（データソース、クラウドサービス、他のAIモデルなど）。
- ソフトウェアアプリケーション内でAIモデルを実行するために必要な依存関係や要件の説明。たとえば、特定のハードウェア、ソフトウェアライブラリ、オペレーティングシステムなど。
