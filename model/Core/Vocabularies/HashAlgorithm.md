SPDX-License-Identifier: Community-Spec-1.0

# HashAlgorithm

## Summary

A mathematical algorithm that maps data of arbitrary size to a bit string.

## Description

A HashAlgorithm is a mathematical algorithm that maps data of arbitrary size to
a bit string (the hash) and is a one-way function, that is, a function which is
practically infeasible to invert.

## Metadata

- name: HashAlgorithm

## Entries

- adler32: Adler-32 checksum is part of the widely used zlib compression library as defined in [RFC 1950](https://datatracker.ietf.org/doc/rfc1950/) Section 2.3.
- blake2b256: BLAKE2b algorithm with a digest size of 256, as defined in [RFC 7693](https://datatracker.ietf.org/doc/rfc7693/) Section 4.
- blake2b384: BLAKE2b algorithm with a digest size of 384, as defined in [RFC 7693](https://datatracker.ietf.org/doc/rfc7693/) Section 4.
- blake2b512: BLAKE2b algorithm with a digest size of 512, as defined in [RFC 7693](https://datatracker.ietf.org/doc/rfc7693/) Section 4.
- blake3: [BLAKE3](https://github.com/BLAKE3-team/BLAKE3-specs/blob/master/blake3.pdf)
- crystalsDilithium: [Dilithium](https://pq-crystals.org/dilithium/)
- crystalsKyber: [Kyber](https://pq-crystals.org/kyber/)
- falcon: [FALCON](https://falcon-sign.info/falcon.pdf)
- md2: MD2 message-digest algorithm, as defined in [RFC 1319](https://datatracker.ietf.org/doc/rfc1319/).
- md4: MD4 message-digest algorithm, as defined in [RFC 1186](https://datatracker.ietf.org/doc/rfc1186/).
- md5: MD5 message-digest algorithm, as defined in [RFC 1321](https://datatracker.ietf.org/doc/rfc1321/).
- md6: [MD6 hash function](https://people.csail.mit.edu/rivest/pubs/RABCx08.pdf)
- other: any hashing algorithm that does not exist in this list of entries
- sha1: SHA-1, a secure hashing algorithm, as defined in [RFC 3174](https://datatracker.ietf.org/doc/rfc3174/).
- sha224: SHA-2 with a digest length of 224, as defined in [RFC 3874](https://datatracker.ietf.org/doc/rfc3874/).
- sha256: SHA-2 with a digest length of 256, as defined in [RFC 6234](https://datatracker.ietf.org/doc/rfc6234/).
- sha384: SHA-2 with a digest length of 384, as defined in [RFC 6234](https://datatracker.ietf.org/doc/rfc6234/).
- sha512: SHA-2 with a digest length of 512, as defined in [RFC 6234](https://datatracker.ietf.org/doc/rfc6234/).
- sha3_224: SHA-3 with a digest length of 224, as defined in [FIPS 202](https://csrc.nist.gov/pubs/fips/202/final).
- sha3_256: SHA-3 with a digest length of 256, as defined in [FIPS 202](https://csrc.nist.gov/pubs/fips/202/final).
- sha3_384: SHA-3 with a digest length of 384, as defined in [FIPS 202](https://csrc.nist.gov/pubs/fips/202/final).
- sha3_512: SHA-3 with a digest length of 512, as defined in [FIPS 202](https://csrc.nist.gov/pubs/fips/202/final).


## Summary @ja

任意長のデータをビット列にマップする数学的アルゴリズム。

## Description @ja

HashAlgorithm は、任意長のデータをビット列（ハッシュ）にマップする数学的アルゴリズムであり、一方向関数、すなわち実際上逆変換が不可能な関数である。

## Entries @ja

- adler32: Adler-32 チェックサム。広く用いられる zlib 圧縮ライブラリの一部であり、[RFC 1950](https://datatracker.ietf.org/doc/rfc1950/) セクション 2.3 で定義される。  
- blake2b256: ダイジェスト長 256 の BLAKE2b。定義は [RFC 7693](https://datatracker.ietf.org/doc/rfc7693/) セクション 4。  
- blake2b384: ダイジェスト長 384 の BLAKE2b。定義は [RFC 7693](https://datatracker.ietf.org/doc/rfc7693/) セクション 4。  
- blake2b512: ダイジェスト長 512 の BLAKE2b。定義は [RFC 7693](https://datatracker.ietf.org/doc/rfc7693/) セクション 4。  
- blake3: [BLAKE3](https://github.com/BLAKE3-team/BLAKE3-specs/blob/master/blake3.pdf)。  
- crystalsDilithium: [Dilithium](https://pq-crystals.org/dilithium/)。  
- crystalsKyber: [Kyber](https://pq-crystals.org/kyber/)。  
- falcon: [FALCON](https://falcon-sign.info/falcon.pdf)。  
- md2: MD2 メッセージダイジェストアルゴリズム。[RFC 1319](https://datatracker.ietf.org/doc/rfc1319/) で定義。  
- md4: MD4 メッセージダイジェストアルゴリズム。[RFC 1186](https://datatracker.ietf.org/doc/rfc1186/) で定義。  
- md5: MD5 メッセージダイジェストアルゴリズム。[RFC 1321](https://datatracker.ietf.org/doc/rfc1321/) で定義。  
- md6: [MD6 ハッシュ関数](https://people.csail.mit.edu/rivest/pubs/RABCx08.pdf)。  
- other: この一覧に存在しない任意のハッシュアルゴリズム。  
- sha1: SHA-1（Secure Hash Algorithm 1）。[RFC 3174](https://datatracker.ietf.org/doc/rfc3174/) で定義。  
- sha224: ダイジェスト長 224 の SHA-2。[RFC 3874](https://datatracker.ietf.org/doc/rfc3874/) で定義。  
- sha256: ダイジェスト長 256 の SHA-2。[RFC 6234](https://datatracker.ietf.org/doc/rfc6234/) で定義。  
- sha384: ダイジェスト長 384 の SHA-2。[RFC 6234](https://datatracker.ietf.org/doc/rfc6234/) で定義。  
- sha512: ダイジェスト長 512 の SHA-2。[RFC 6234](https://datatracker.ietf.org/doc/rfc6234/) で定義。  
- sha3_224: ダイジェスト長 224 の SHA-3。[FIPS 202](https://csrc.nist.gov/pubs/fips/202/final) で定義。  
- sha3_256: ダイジェスト長 256 の SHA-3。[FIPS 202](https://csrc.nist.gov/pubs/fips/202/final) で定義。  
- sha3_384: ダイジェスト長 384 の SHA-3。[FIPS 202](https://csrc.nist.gov/pubs/fips/202/final) で定義。  
- sha3_512: ダイジェスト長 512 の SHA-3。[FIPS 202](https://csrc.nist.gov/pubs/fips/202/final) で定義。  
