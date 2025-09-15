SPDX-License-Identifier: Community-Spec-1.0

# DateTime

## Summary

A string representing a specific date and time.

## Description

A DateTime is a string representation of a specific date and time.

It has resolution of seconds and is always expressed in UTC time zone.

The specific format is one of the most commonly used ISO-8601 formats.

## Metadata

- name: DateTime
- SubclassOf: xsd:dateTimeStamp

## Format

- pattern: ^\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\dZ$

## Summary @ja

特定の日付と時刻を表す文字列。

## Description @ja

DateTime は特定の日付と時刻を表現する文字列である。秒までの解像度を持ち、常に UTC タイムゾーンで表現される。形式は広く利用されている ISO-8601 形式の一つである。