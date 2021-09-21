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
Secret Key: 97ad55c9533340cec80a04cfb26856ab

Single Block Tests
------------------
iv: 067b9ab31787a30596c2f124684f4bc4
plain text: 'SingleBlock Text'
Ciphertext Hex: 4af695de10126c3dba2f5eb28e65307e
Plaintext: SingleBlock Text
Single Block Test Passed Successfully

Short Text Tests
----------------
iv: 8fa2dbb0129501244c15ef467c147bfd
plain text: 'Just Text'
Ciphertext Hex: 91c2f376cdc3d5912d91e6708b2c1f60
Plaintext: Just Text
Short Text Test Passed Successfully

Arbitrary Length Tests
----------------------
iv: 96c55d1e422c5650dd4cf1ca0efe5760
plain text: 'This Text is longer than one block'
Ciphertext Hex: 7a952cc630790f2064d60592c02aa7e03c555cacc82e1ea332c5a4027371ec25b3bd104c02e7615546cfca3b4c959bef
Plaintext: This Text is longer than one block
Arbitrary Length Text Test Passed Successfully
```

## Roadmap

In the future, I will add an implementations of another major AES modes of operations, such as OCB, CTR, etc.

## Authors and acknowledgment

- **Or Gur Arie** - Creator and Maintainer - [orgurar](https://gitlab.com/orgurar)

## License

Doraemon is licensed under the MIT license, see the [LICENSE](LICENSE) file for details.
