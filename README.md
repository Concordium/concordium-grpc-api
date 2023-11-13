# gRPC API

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg)](https://github.com/Concordium/.github/blob/main/.github/CODE_OF_CONDUCT.md)

This repository keeps the gRPC protocol definition file and related
documentation on the gRPC interface exposed by concordium-node.

The V2 API consists of three services

- [health.proto](./v2/concordium/health.proto)
- [grpc-health.proto](./grpc/health/v1/health.proto)
- [service.proto](./v2/concordium/service.proto)

and an auxiliary file with all the types for requests and responses

- [types.proto](./v2/concordium/types.proto)

The two health services exist to expose a different API. The first health
service returns status via grpc status codes. The second health service is a
standard Google health service that communicates service health via response
values.

The rendered documentation for the V2 API is available at
http://developer.concordium.software/concordium-grpc-api/
