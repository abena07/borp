# borp

a go-native rpc framework built on top of [bogo](https://github.com/bubunyo/bogo) binary serialization

## what

borp is a lightweight rpc framework built on top of [bogo](https://github.com/bubunyo/bogo) — a fast, compact binary serialization format. the aim is to build something akin to grpc but using bogo as the exchange format instead of protobuf, with no code generation and no separate schema files. your go structs are the schema.

## how to run

```bash
go run .
```
