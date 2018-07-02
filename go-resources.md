## Questions
- Why does this not work? 
```go
package main
import "fmt"

// var greeting string = "Hello World" // this does
greeting := "Hello World" // but this does not 

func main() {
  fmt.Println(greeting)
}
```
Results in ` # command-line-arguments
./main.go:6:1: syntax error: non-declaration statement outside function body`

## Basics
- [Go Cheatsheet](https://github.com/a8m/go-lang-cheat-sheet)

## GoDocs
- [Official Docs](https://godoc.org/)
  - [Math](https://godoc.org/math)
  - [Strings](https://godoc.org/strings)
