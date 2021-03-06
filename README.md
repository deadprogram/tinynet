# tinynet

A `net` implementation for Go and TinyGo based on [unisockets](https://github.com/pojntfx/unisockets), targeting both WebAssembly and native platforms.

![make CI](https://github.com/pojntfx/tinynet/workflows/make%20CI/badge.svg)
![Mirror](https://github.com/pojntfx/tinynet/workflows/Mirror/badge.svg)
[![PkgGoDev](https://pkg.go.dev/badge/github.com/pojntfx/tinynet)](https://pkg.go.dev/github.com/pojntfx/tinynet)

## Overview

tinynet implements a subnet of the [Go `net` package](https://golang.org/pkg/net/). Because it is based on [unisockets](https://github.com/pojntfx/unisockets), it supports more platforms (WASM/JS, WASM/WASI, TinyGo, Go etc.) than the official `net` package.

## Usage

Check out [![PkgGoDev](https://pkg.go.dev/badge/github.com/pojntfx/tinynet)](https://pkg.go.dev/github.com/pojntfx/tinynet) for API documentation. Many examples on how to use it (clients, servers and an example distributed system) can also be found in [the `cmd` package](https://pkg.go.dev/github.com/pojntfx/tinynet/cmd). Additionally, the [`Makefile`](https://github.com/pojntfx/tinynet/blob/main/Makefile) might also be of interest; it shows how to build native and WASM binaries.

## License

tinynet (c) 2020 Felix Pojtinger

SPDX-License-Identifier: AGPL-3.0
