# Changelog

## Unreleased

- Add `GetBakersRewardPeriod` endpoint.
- Add `GetBlockCertificates` endpoint.

## Node 6.0 API

- Expand `BlockHashInput` to support querying by block height.
- Add `protocol_version` to the return of BlockInfo.
- Make `slot_duration` optional in `ConsensusInfo`.
- Add optional fields `current_timeout_duration`, `current_round`, `current_epoch`,
  and `trigger_block_time` to `ConsensusInfo`.
- Make `slot_number` optional in `BlockInfo`.
- Add optional fields `round` and `epoch` to `BlockInfo`.
- Make `election_difficulty` optional in `ElectionInfo`.
