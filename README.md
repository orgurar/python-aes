# AES-CBC-128

## Description

This project is a CBC moded AES-128 pure python implementation.
It requires no dependencies at all as is was implemented with native python3 only.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

The project is written in python3 only, hence it is the only prerequisite.

Run the following in order to verify your python version,
the recommended version is `Python 3.9.7`

```
python --version
```

### Installing

The only step, it to clone your local repository using

```
git clone https://gitlab.com/orgurar/aes.git
```

## Running

You only have to run the main script with python3

```
python main.py
```

### Tests

The `aes.py` module located in the `aes` source folder contains all the automated tests.

Run those tests by running this module as the main module, use

```
cd aes/
python aes.py
```

### Tests Passed

```
AES Tests
=========
Algorithm: AES-CBC-128
Secret Key: dc6cf0c38defedf45aa976a36c245536

Single Block Tests
------------------
iv: 28c4ea339466691141c0a1710469f8a9
plain text: 'SingleBlock Text'
Ciphertext Hex: b705825f9fda52ed58de4c50660e93ab
Plaintext: SingleBlock Text
Single Block Test Passed Successfully

Short Text Tests
----------------
iv: cd08840cb70a3705e7434849fdf095ba
plain text: 'Just Text'
Ciphertext Hex: cda7d99aa256860608b1d123cc9e8102
Plaintext: Just Text
Short Text Test Passed Successfully

Arbitrary Length Tests
----------------------
iv: 9544bd16f9da3ee6e0652ae2d7036ee4
plain text: 'This Text is longer than one block'
Ciphertext Hex: 1bc3c37374e34f973de6095802262093f6244c555a109cd978354d42c5f6687bedee13b48150c4082ab68fc038d085b5
Plaintext: This Text is longer than one block
Arbitrary Length Text Test Passed Successfully
```

## Roadmap

In the future, I will add an implementations of another major AES modes of operations, such as OCB, CTR, etc.

## Authors and acknowledgment

- **Or Gur Arie** - Creator and Maintainer - [orgurar](https://gitlab.com/orgurar)

## License

Doraemon is licensed under the MIT license, see the [LICENSE](LICENSE) file for details.
