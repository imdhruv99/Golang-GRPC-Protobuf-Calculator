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

- `localhost:8080/add/<number>/<number>`

<img src="https://github.com/imdhruv99/Golang-GRPC-Protobuf-Calculator/blob/main/screenshots/add.png" alt="Addition API" width="500" height="600">

- ##### Substraction

- `localhost:8080/sub/<number>/<number>`

<img src="https://github.com/imdhruv99/Golang-GRPC-Protobuf-Calculator/blob/main/screenshots/sub.png" alt="Subtraction API" width="500" height="600">

- ##### Multiplication

- `localhost:8080/mul/<number>/<number>`

<img src="https://github.com/imdhruv99/Golang-GRPC-Protobuf-Calculator/blob/main/screenshots/mul.png" alt="Multiplication API" width="500" height="600">

- ##### Division

- `localhost:8080/div/<number>/<number>`

<img src="https://github.com/imdhruv99/Golang-GRPC-Protobuf-Calculator/blob/main/screenshots/div.png" alt="Division API" width="500" height="600">

### Thank You !
- D H R U V  P R A J A P A T I