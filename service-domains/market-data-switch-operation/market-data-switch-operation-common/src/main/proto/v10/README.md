# gPRC for com.redhat.mercury.marketdataswitchoperation.v10

This service domain operates the internal information distribution facility/switch in compliance with administered external subscription information feed service access rights. Note the content is retrieved by the Market Feed Operation service domain from the various external feed services. Internal information can also be published over the switch from various bank sources (such as bank rates provided by treasury).

## Overview
These files were generated by the [OpenAPI Generator](https://openapi-generator.tech) project.

- API version: 10.0.0
- Package version: 
- Build package: org.openapitools.codegen.languages.ProtobufSchemaCodegen

## Usage

Below are some usage examples for Go and Ruby. For other languages, please refer to https://grpc.io/docs/quickstart/.

### Go
```
# assuming `protoc-gen-go` has been installed with `go get -u github.com/golang/protobuf/protoc-gen-go`
mkdir /var/tmp/go/
protoc --go_out=/var/tmp/go/ services/*
protoc --go_out=/var/tmp/go/ models/*
```

### Ruby
```
# assuming `grpc_tools_ruby_protoc` has been installed via `gem install grpc-tools`
RUBY_OUTPUT_DIR="/var/tmp/ruby/com.redhat.mercury.marketdataswitchoperation.v10"
mkdir $RUBY_OUTPUT_DIR
grpc_tools_ruby_protoc --ruby_out=$RUBY_OUTPUT_DIR --grpc_out=$RUBY_OUTPUT_DIR/lib services/*
grpc_tools_ruby_protoc --ruby_out=$RUBY_OUTPUT_DIR --grpc_out=$RUBY_OUTPUT_DIR/lib models/*
```
