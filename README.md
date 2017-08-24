[![GoDoc](https://godoc.org/github.com/njones/go-base58?status.svg)](https://godoc.org/github.com/njones/go-base58)

# go-base58

Fast implementation of base58 encoding on golang.

Base algorithms are copied from https://github.com/trezor/trezor-crypto/blob/master/base58.c

If your know how to improve it, please make pull request.

Without big.Int divisions it works more than 4 times faster.

## Installation

    go get github.com/njones/go-base58

## License

go-base58 is available under the [MIT License](https://opensource.org/licenses/MIT).