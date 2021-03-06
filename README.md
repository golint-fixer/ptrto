ptrto
=====

[![Build Status](https://img.shields.io/travis/mcos/ptrto.svg?style=flat)](https://travis-ci.org/mcos/ptrto)
[![GoDoc](https://godoc.org/github.com/mcos/ptrto?status.svg)](https://godoc.org/github.com/mcos/ptrto)

`ptrto` is a tiny library that exposes functions that return pointers to the `Go` builtin types (http://golang.org/pkg/builtin).

The following types are supported:
* `bool`
* `byte`
* `float32`
* `float64`
* `int`
* `int8`
* `int16`
* `int32`
* `int64`
* `interface`
* `string`
* `struct`
* `uint`
* `uint8`
* `uint16`
* `uint32`
* `uint64`
* `uintptr`

This library is only really useful when testing functions and structs with `interface{}` arguments, types and parameters. Using this library in actual implementation code is probably not a good idea.

Install
======
If you _really_ want to use this, install it by running `go get github.com/mcos/ptrto`

License
======
[MIT License][license-file]


[license-file]: LICENSE
