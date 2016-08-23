# Chat App

Demo application built for Code School's Watch Us Build episide on
the Go programming language.

## Runing

* The host: `go run main.go -listen <local-ip-address>`
* The guest: `go run main.go <local-ip-address>`

## Cross-Compiling for Windows

In order to cross-compile the program to run on a windows64 machine,
run the following command:

`GOOS=windows GOARCH=amd64 go build -o mychat.exe`

