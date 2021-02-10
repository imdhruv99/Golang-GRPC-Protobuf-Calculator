# GOLANG-GRPC-Calculator

- Simple Calculator using GRPC and Protobufs in Golang.

### Requirements

- First of all need to setup Protobuf compiler, dowload and setup using given [link](https://github.com/protocolbuffers/protobuf/releases).

### Install Require packages

- gin: `go get -u github.com/gin-gonic/gin`
- grpc: `go get -u google.golang.org/grpc`
- protobuf: `go get -u github.com/golang/protobuf`

### Running

- You can generate your own `service.pb.go` file using below command, if you want to modify proto file.

- `protoc --proto_path=proto --proto_path=ThirdParty --go_out=plugins=grpc:proto service.proto`

- Run below command to run server and client
- ``` go run server/main.go```
- ``` go run client/main.go```

### Execution
- ##### Addition

- ##### Substraction

- ##### Multiplication

- ##### Division