# HTTP server
This repository provides a base project to learn how HTTP communication works.

The project can be built with either Docker or Go 1.17.
Telnet client will be required to check if the provided implementation is working.

It originally works as a bare TCP server.
This means, when you access it from your Web browser (Chrome, Firefox, Safari, etc.), it will not provide any valid responses.
The exercise here is to make the server reply valid responses following Hyper-Text Transport Protocol (HTTP) to clients.

You can run the server with the following commands;
```sh
$ docker-compose up -d
$ docker-compose exec app go run main.go
```
Or, you can directly execute `go run main.go` if you have Go development tools.
