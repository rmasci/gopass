# getpasswd in Go

Retrieve password from user terminal input without echo

Verified on BSD, Linux, and Windows.

Example:
```go
package main
import "fmt"
import "github.com/rmasci/gopass"
func main() {
	fmt.Printf("Password: ")
	pass := gopass.GetPasswd()
    // Do something with pass
}
```

This is a fork from [https://github.com/howeyc/gopass](https://github.com/howeyc/gopass)
