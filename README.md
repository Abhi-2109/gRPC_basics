# proto_basics

Basics Of Protocol Buffers

Protocol buffers are Google's language-neutral, platform-neutral, extensible mechanism for serializing structured data – think XML, but smaller, faster, and simpler. You define how you want your data to be structured once, then you can use special generated source code to easily write and read your structured data to and from a variety of data streams and using a variety of languages.

https://developers.google.com/protocol-buffers/


In the repo there is a example to implement protocol buffers in go

###To Download Protocol Buffers

`
go get -u github.com/golang/protobuf/protoc-gen-go
`

### To convert the .proto file in golang

`
  protoc --go_out=. todo.proto
`

The example is to use protobuffers to encode and decode into/from the file.

to insert --> add function
`
go run main.go add abhishek
`

to see list -> list function
`
go run main.go list
`
