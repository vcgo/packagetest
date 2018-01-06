# Golang package test.

## Install

```bash
go get github.com/vcgo/packagetest
go get github.com/vcgo/packagetest/tool/testcmd
```

## Test package

```go
// write a file test.go
package main

import (
	"github.com/vcgo/packagetest"
)

func main() {
	packagetest.Hello()
}

```

    $ go run test.go

## Test cmd

    $ testcmd
