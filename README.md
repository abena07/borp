# borp

a go-native rpc framework built on top of [bogo](https://github.com/bubunyo/bogo) binary serialization

## what

borp is a lightweight rpc framework powered by [bogo](https://github.com/bubunyo/bogo), a fast and efficient binary serialization format. its goal is to offer a grpc-style developer experience without the complexity of code generation or standalone schema files. with borp, your go structs define the schema, and bogo handles the wire format.

## how to run

```bash
go run .
```
