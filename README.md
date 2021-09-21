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
Secret Key: ddc3ffd973ad163781e04e0e5efce40a    

Single Block Tests
------------------
iv: 7dfea27e0982f54bd90c19e781c94fdd
plain text: 'SingleBlock Text'
Ciphertext Hex: bbe939744c79a60e80959d7bf9f2f1fd
Plaintext: SingleBlock Text
Single Block Test Passed Successfully

Short Text Tests
----------------
iv: 6f078374b524ddafc40a0d0a8a7752f9
plain text: 'Just Text'
Ciphertext Hex: 4c41935ba7b8a05e9e270b856f571634
Plaintext: Just Text
Short Text Test Passed Successfully

Arbitrary Length Tests
----------------------
iv: d31f1b92955740abbcc1fa751bdaf759
plain text: 'This Text is longer than one block'
Ciphertext Hex: d52c632f96c15839fd3935e38cc9bc570c31a99c4e798bbe798b6d63a63535ecce66f040f2ac3ea39b0dd459c5ebe90b
Plaintext: This Text is longer than one block
Short Text Test Passed Successfully
```

## Roadmap

In the future, I will add an implementations of another major AES modes of operations, such as OCB, CTR, etc.

## Authors and acknowledgment

- **Or Gur Arie** - Creator and Maintainer - [orgurar](https://gitlab.com/orgurar)

## License

Doraemon is licensed under the MIT license, see the [LICENSE](LICENSE) file for details.
