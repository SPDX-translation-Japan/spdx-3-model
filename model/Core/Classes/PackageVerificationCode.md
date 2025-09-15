SPDX-License-Identifier: Community-Spec-1.0

# PackageVerificationCode

## Summary

An SPDX version 2.X compatible verification method for software packages.

## Description

This verification method is provided for compatibility with SPDX 2.X.

Use of this verification code method is discouraged except for scenarios where the `contentIdentifier` property on `Artifact` can not be used.

This verification method provides an independently reproducible mechanism identifying specific contents of a package based on the actual files (except the SPDX document itself, if it is included in the package) that make up each package and that correlates to the data in this SPDX document.

This identifier enables a recipient to determine if any file in the original package (that the analysis was done on) has been changed and permits inclusion of an SPDX document as part of a package.

Algorithm:

    templist = ""

    for all files in the package {
        if file is a packageVerificationCodeExcludedFile
            skip it  /* exclude SPDX analysis file */
        else
            append "algorithm(file)/n" to templist
    }

    sort templist in ascending order by value
    
    /* remove separators from ordered sequence */
    valueslist = remove "/n"s from templist
     
    if valueslist is empty
       hashValue = 0
    else
       hashValue = algorithm(valueslist)

where `algorithm(string)` applies a hash algorithm on a string and returns the result in lowercase hexadecimal digits.

Required sort order: '0', '1', '2', '3', '4', '5', '6', '7', '8', '9', 'a', 'b', 'c', 'd', 'e', 'f' (ASCII order)

## Metadata

- name: PackageVerificationCode
- SubclassOf: /Core/IntegrityMethod

## Properties

- algorithm
  - type: HashAlgorithm
  - minCount: 1
  - maxCount: 1
- hashValue
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- packageVerificationCodeExcludedFile
  - type: xsd:string

## Summary @ja

ソフトウェアパッケージのための SPDX 2.X 互換の検証手法。

## Description @ja

この検証手法は SPDX 2.X との互換性のために提供されている。  

Artifact の `contentIdentifier` プロパティが利用できない場合を除き、この検証コード手法の使用は推奨されない。  

この検証手法は、各パッケージを構成する実際のファイル（パッケージに SPDX 文書自体が含まれる場合はそれを除外する）に基づき、そのパッケージの特定の内容を識別するための、独立して再現可能な仕組みを提供する。そしてこの内容は本 SPDX 文書内のデータと対応している。  

この識別子により、受信者は解析対象となった元のパッケージ内のファイルが変更されていないかを判断でき、さらに SPDX 文書をパッケージの一部として含めることが可能になる。  

Algorithm:

    templist = ""

    for all files in the package {
        if file is a packageVerificationCodeExcludedFile
            skip it  /* exclude SPDX analysis file */
        else
            append "algorithm(file)/n" to templist
    }

    sort templist in ascending order by value
    
    /* remove separators from ordered sequence */
    valueslist = remove "/n"s from templist
     
    if valueslist is empty
       hashValue = 0
    else
       hashValue = algorithm(valueslist)

ここで `algorithm(string)` は文字列にハッシュアルゴリズムを適用し、その結果を小文字の 16 進数で返す。  

ソート順序は ASCII 順序に従い、 `'0'`, `'1'`, …, `'9'`, `'a'`, `'b'`, …, `'f'` とする。  
