# go-versioner

Tool to generate `version.go` file from `VERSION` file.
This allows golang developers to use `VERSION` design pattern and use the version in code without having to bump both files.

## Usage

Add dependency to your project:

```
$ go get github.com/bsick7/go-versioner
```

In `main.go`, add the following lines below `package main`.

```go
package main
//go:generate go-versioner
```
