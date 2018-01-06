# Golang package test.


## Test package

`go get github.com/vcgo/packagetest`

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

`go get github.com/vcgo/packagetest/tool/testcmd`

    $ testcmd