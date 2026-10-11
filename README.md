# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-10-11 17:20 UTC

New crates published between 2026-10-11 16:19 UTC and 2026-10-11 17:20 UTC.

[Full CSV](data/new-crates-2026-10-11T17-20-41-845162Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-10-11 16:21:50 | [syllabix-native](https://crates.io/crates/syllabix-native) | 0.1.1 | 0 | Shared ggml plus whisper.cpp and llama.cpp frontends |
| 2026-10-11 16:21:54 | [syllabix-core](https://crates.io/crates/syllabix-core) | 0.1.1 | 0 | Voice-agent SDK: shared types, provider contracts, and an in-memory speech-to-s… |
| 2026-10-11 16:24:38 | [redknife](https://crates.io/crates/redknife) | 0.1.0 | 0 | A Swiss Army knife for offensive pentesting. |
| 2026-10-11 16:28:42 | [struct2md_derive](https://crates.io/crates/struct2md_derive) | 0.1.0 | 0 | Proc-macro derive for struct2md |
| 2026-10-11 16:29:08 | [struct2md](https://crates.io/crates/struct2md) | 0.1.1 | 0 | Declarative macro to serialize Rust structs into Markdown via field attributes |
| 2026-10-11 16:36:44 | [lacodda-tear](https://crates.io/crates/lacodda-tear) | 0.1.0 | 0 | A TCP proxy for tests that tears connections where you say: after so many bytes… |
| 2026-10-11 16:40:47 | [witness-log-core](https://crates.io/crates/witness-log-core) | 0.3.5 | 0 | Cryptographic audit-trail core: RFC 6962-style Merkle log, Ed25519 identity, sa… |
| 2026-10-11 16:41:01 | [witness-log-network](https://crates.io/crates/witness-log-network) | 0.3.5 | 0 | Witness protocol: peer countersigning of checkpoints and quorum/diversity scori… |
| 2026-10-11 16:41:18 | [witness-log-cli](https://crates.io/crates/witness-log-cli) | 0.3.5 | 0 | witness-log: offline verification CLI for witnessed audit logs and witness quor… |
| 2026-10-11 16:45:29 | [acctswap-core](https://crates.io/crates/acctswap-core) | 0.2.1 | 0 | The rules of acctswap: which saved Claude Code login to switch to, and how to s… |
| 2026-10-11 16:45:41 | [acctswap](https://crates.io/crates/acctswap) | 0.2.1 | 0 | Switch the account every Claude Code session on a machine uses, from saved logi… |
| 2026-10-11 16:48:25 | [pound-derive-impl](https://crates.io/crates/pound-derive-impl) | 0.3.0 | 0 | expansion behind pound's derive macros |
| 2026-10-11 16:51:33 | [lodestone-wire](https://crates.io/crates/lodestone-wire) | 0.0.2 | 0 | Generated public wire types for the current Lodestone API |
| 2026-10-11 16:52:32 | [wakuwaku-entity](https://crates.io/crates/wakuwaku-entity) | 0.1.0 | 0 | Capability-typed queries, hooks and pure transaction flows over sqlx, Redis and… |
| 2026-10-11 16:52:45 | [lodestone-client](https://crates.io/crates/lodestone-client) | 0.0.2 | 0 | Current-only asynchronous Rust client for the Lodestone API |
| 2026-10-11 17:04:35 | [trtask](https://crates.io/crates/trtask) | 0.1.0 | 0 | Cross-platform task spawning utilities for Terrarium. |
| 2026-10-11 17:07:31 | [squadleader-scenario](https://crates.io/crates/squadleader-scenario) | 0.1.0 | 0 | Scenario builder tools for the SquadLeader system. |
| 2026-10-11 17:11:00 | [log-bill](https://crates.io/crates/log-bill) | 0.1.0 | 0 | Offline estimate of log costs per pattern |
| 2026-10-11 17:16:40 | [tidal-player-audio](https://crates.io/crates/tidal-player-audio) | 1.0.0 | 0 | Decode and audio output engine for tidal-player |
| 2026-10-11 17:16:41 | [tidal-player-core](https://crates.io/crates/tidal-player-core) | 1.0.0 | 0 | Pure domain types, protocol and state machines for tidal-player (no I/O) |
| 2026-10-11 17:16:42 | [tidal-player-api](https://crates.io/crates/tidal-player-api) | 1.0.0 | 0 | Tidal HTTP API client for tidal-player |
| 2026-10-11 17:16:44 | [tidal-player](https://crates.io/crates/tidal-player) | 1.0.0 | 0 | Terminal Tidal player: standalone, daemon and client |
| 2026-10-11 17:17:00 | [prototext-schema](https://crates.io/crates/prototext-schema) | 0.3.2 | 0 | On-demand FileDescriptorProto loading from a mmapped descriptor set and its rky… |
| 2026-10-11 17:17:04 | [prototools-complete](https://crates.io/crates/prototools-complete) | 0.3.2 | 0 | Bash completion for clap from the raw command line, shared by the prototools CL… |
| 2026-10-11 17:19:12 | [polloc](https://crates.io/crates/polloc) | 0.2.0 | 0 | A fixed size pool allocator with safe typed slots and reusable memory blocks |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
