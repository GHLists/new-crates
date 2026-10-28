# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-10-28 01:20 UTC

New crates published between 2026-10-28 00:18 UTC and 2026-10-28 01:20 UTC.

[Full CSV](data/new-crates-2026-10-28T01-20-58-525147Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-10-28 00:23:23 | [hharness-kernel](https://crates.io/crates/hharness-kernel) | 0.1.0 | 0 | The E1 reference kernel binary (Stage-0 skeleton): schema export, the stdio JSO… |
| 2026-10-28 00:34:45 | [hharness-mcp-lab](https://crates.io/crates/hharness-mcp-lab) | 0.1.0 | 0 | The C1 `hh-lab/1` MCP server slice (spec §7.3, R-2.11.3¹; ticket S4.11; ADR-017… |
| 2026-10-28 00:38:39 | [chinese-ime-lm](https://crates.io/crates/chinese-ime-lm) | 0.2.0 | 0 | A character-level language model for reranking Chinese input method candidates |
| 2026-10-28 00:38:41 | [solana_kit_pyth](https://crates.io/crates/solana_kit_pyth) | 0.0.0 | 0 | Reserved off-chain Pyth client crate for the portable Solana Kit SDK |
| 2026-10-28 00:39:16 | [hid-debug](https://crates.io/crates/hid-debug) | 0.1.0 | 0 | USB HID debug tool |
| 2026-10-28 00:41:42 | [signalhouse-sms](https://crates.io/crates/signalhouse-sms) | 1.5.1 | 0 | Official Rust SDK for the SignalHouse platform |
| 2026-10-28 00:45:00 | [aptove-bridge-core](https://crates.io/crates/aptove-bridge-core) | 0.2.9 | 0 | Core library for the Aptove bridge |
| 2026-10-28 00:45:09 | [ccfddl-tui](https://crates.io/crates/ccfddl-tui) | 0.2.0 | 0 | Terminal UI for CCF-ranked conference deadlines, with a conference recommendati… |
| 2026-10-28 00:46:03 | [hharness-subagent](https://crates.io/crates/hharness-subagent) | 0.1.0 | 0 | The C1/Stage-4 subagent kernel slice (spec §5e.3, R-2.6.3¹ + R-2.1.6¹; ticket S… |
| 2026-10-28 00:49:04 | [async-store](https://crates.io/crates/async-store) | 0.1.0 | 0 | A lightweight, TTL-based, async resource storage adn lifecycle handler created… |
| 2026-10-28 00:57:14 | [radiacode-lib](https://crates.io/crates/radiacode-lib) | 0.2.0 | 0 | RadiaCode gamma spectrometer protocol, USB and Bluetooth LE transports, device… |
| 2026-10-28 00:57:33 | [hharness-orchestrator](https://crates.io/crates/hharness-orchestrator) | 0.1.0 | 0 | The C3/Stage-4 sub-agent orchestrator class (spec §5e.3, R-2.6.3; ticket S4.6;… |
| 2026-10-28 01:05:44 | [thruput-event](https://crates.io/crates/thruput-event) | 0.58.0 | 0 | Event trait and topic types for Thruput smart contracts |
| 2026-10-28 01:05:50 | [thruput-exn](https://crates.io/crates/thruput-exn) | 0.58.0 | 0 | Exception trait and abort wire format for Thruput smart contracts |
| 2026-10-28 01:05:56 | [thruput-storage-cost](https://crates.io/crates/thruput-storage-cost) | 0.58.0 | 0 | Storage cost calculation for Thruput smart contracts |
| 2026-10-28 01:06:01 | [thruput-contract-util](https://crates.io/crates/thruput-contract-util) | 0.58.0 | 0 | Utility functions for contract development |
| 2026-10-28 01:06:08 | [thruput-contract-spec](https://crates.io/crates/thruput-contract-spec) | 0.58.0 | 0 | Canonical contract spec model for Thruput contracts |
| 2026-10-28 01:08:52 | [hharness-varhost](https://crates.io/crates/hharness-varhost) | 0.1.0 | 0 | The C0/Stage-2 out-of-process variant host — the kernel side of `plugin_abi/1`… |
| 2026-10-28 01:12:09 | [thruput-sys](https://crates.io/crates/thruput-sys) | 0.58.0 | 0 | Bindings for the external Thruput test environment |
| 2026-10-28 01:20:12 | [hharness-web](https://crates.io/crates/hharness-web) | 0.1.0 | 0 | The C1 read-only web instrument (spec §7.2, R-2.11.2¹; S4.10). A pure projectio… |
| 2026-10-28 01:20:25 | [hharness-xcheck](https://crates.io/crates/hharness-xcheck) | 0.1.0 | 0 | The cross-implementation replay/checker packaging (spec §10.7; ticket R2.21; AD… |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
