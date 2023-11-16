# Changelog

## Unreleased changes

- Add a new health service that conforms to the API expected
  by Google https://github.com/grpc/grpc-proto/blob/master/grpc/health/v1/health.proto
- Add `DryRun` endpoint.
- Remove `UpdateInstructionSignature`. It was not used in any endpoints.
- Remove V1 API.
- Extend enum `ProtocolVersion` enum with a protocol version 7 variant `PROTOCOL_VERSION_7`.

## Node 6.1 API

- Add `GetBakersRewardPeriod` endpoint.
- Add `GetBlockCertificates` endpoint.
- Add `GetBakerEarliestWinTime` endpoint.
- Add `GetWinningBakersEpoch` endpoint.
- Add `GetFirstBlockEpoch` endpoint.
- Add a `CommissionRates` field for `PoolCurrentPaydayInfo`.

## Node 6.0 API

- Expand `BlockHashInput` to support querying by block height.
- Add `protocol_version` to the return of BlockInfo.
- Make `slot_duration` optional in `ConsensusInfo`.
- Add optional fields `current_timeout_duration`, `current_round`, `current_epoch`,
  and `trigger_block_time` to `ConsensusInfo`.
- Make `slot_number` optional in `BlockInfo`.
- Add optional fields `round` and `epoch` to `BlockInfo`.
- Make `election_difficulty` optional in `ElectionInfo`.
