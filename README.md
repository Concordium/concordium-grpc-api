# gRPC API

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg)](https://github.com/Concordium/.github/blob/main/.github/CODE_OF_CONDUCT.md)

This repository keeps the gRPC protocol definition file and related
documentation on the gRPC interface exposed by concordium-node.

The repository contains two APIs. The legacy V1 API specified in
[concordium_p2p_rpc.proto](./concordium_p2p_rpc.proto) and the new V2 API that
is more comprehensive and much more documented. This consists of two services

- [health.proto](./v2/concordium/health.proto)
- [service.proto](./v2/concordium/service.proto)

and an auxiliary file with all the types for requests and responses

- [types.proto](./v2/concordium/types.proto)

The rendered documentation for the V2 API is available at
http://developer.concordium.software/concordium-grpc-api/
