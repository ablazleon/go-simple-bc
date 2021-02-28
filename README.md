# go-simple-bc

I followed this tutorial:

https://mycoralhealth.medium.com/code-your-own-blockchain-in-less-than-200-lines-of-go-e296282bcffc

To do so, it is configure an environment in a linux vm ubuntu 20.

```
main.go:15:2: no required module provides package github.com/davecgh/go-spew/spew: working directory is not part of a module
main.go:16:2: no required module provides package github.com/gorilla/mux: working directory is not part of a module
main.go:17:2: no required module provides package github.com/joho/godotenv: working directory is not part of a module
aluche@aluche-VirtualBox:~/PycharmProjects/blockchain-tutorial$ go get github.com/davecgh/go-spew/spew
go: downloading github.com/davecgh/go-spew v1.1.1
aluche@aluche-VirtualBox:~/PycharmProjects/blockchain-tutorial$ go run main.go 
main.go:15:2: no required module provides package github.com/davecgh/go-spew/spew: working directory is not part of a module
main.go:16:2: no required module provides package github.com/gorilla/mux: working directory is not part of a module
main.go:17:2: no required module provides package github.com/joho/godotenv: working directory is not part of a module
aluche@aluche-VirtualBox:~/PycharmProjects/blockchain-tutorial$ go get github.com/gorilla/mux
go: downloading github.com/gorilla/mux v1.8.0
aluche@aluche-VirtualBox:~/PycharmProjects/blockchain-tutorial$ go get github.com/joho/godotenv
go: downloading github.com/joho/godotenv v1.3.0
aluche@aluche-VirtualBox:~/PycharmProjects/blockchain-tutorial$ go run main.go 
main.go:15:2: no required module provides package github.com/davecgh/go-spew/spew: working directory is not part of a module
main.go:16:2: no required module provides package github.com/gorilla/mux: working directory is not part of a module
main.go:17:2: no required module provides package github.com/joho/godotenv: working directory is not part of a module
aluche@aluche-VirtualBox:~/PycharmProjects/blockchain-tutorial$ mv example.env .env
aluche@aluche-VirtualBox:~/PycharmProjects/blockchain-tutorial$ go run main.go 
main.go:15:2: no required module provides package github.com/davecgh/go-spew/spew: working directory is not part of a module
main.go:16:2: no required module provides package github.com/gorilla/mux: working directory is not part of a module
main.go:17:2: no required module provides package github.com/joho/godotenv: working directory is not part of a module

```
