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
Tests Passed Successfully
```

## Roadmap

In the future, I will add an implementations of another major AES modes of operations, such as OCB, CTR, etc.

## Authors and acknowledgment

- **Or Gur Arie** - Creator and Maintainer - [orgurar](https://gitlab.com/orgurar)

## License

Doraemon is licensed under the MIT license, see the [LICENSE](LICENSE) file for details.
