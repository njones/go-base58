[![GoDoc](https://godoc.org/github.com/njones/base58?status.svg)](https://godoc.org/github.com/njones/base58)
[![Go Report Card](https://goreportcard.com/badge/njones/base58)](https://goreportcard.com/report/njones/base58)
[![Go Coverage](https://img.shields.io/codecov/c/github/njones/base58.svg)](https://codecov.io/gh/njones/base58)

# Base58    

A fast implementation of base58 encoding and decoding written in go.

Base algorithms are copied from https://github.com/trezor/trezor-crypto/blob/master/base58.c

If you know how to improve it, please make pull request.

Without big.Int divisions it works more than 4 times faster.

## Installation

    go get github.com/njones/base58

## License

base58 is available under the [MIT License](https://opensource.org/licenses/MIT).