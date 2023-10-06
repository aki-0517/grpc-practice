# hello-grpc-go

Hello World for gRPC with Go

https://zenn.dev/s_takashi/articles/efe242c3d3c9f5
https://zenn.dev/hsaki/books/golang-grpc-starting/viewer/rpc
https://zenn.dev/stray_cat/articles/52d60b452f58a3
https://stackoverflow.com/questions/60578892/protoc-gen-go-grpc-program-not-found-or-is-not-executable

## Download Packages

```sh
go mod tidy
```

## Run Server

```sh
go run server/main.go
server is runnig...
```

## Run Client

```sh
% go run client/main.go Pin
Pon!
```

```sh
% go run client/main.go hoge
Please need words 'Pin'!
```
