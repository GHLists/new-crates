# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-10-14 03:20 UTC

New crates published between 2026-10-14 02:20 UTC and 2026-10-14 03:20 UTC.

[Full CSV](data/new-crates-2026-10-14T03-20-07-771726Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-10-14 02:23:53 | [locus-sqlite-adapter](https://crates.io/crates/locus-sqlite-adapter) | 0.1.0 | 0 | SQLite NodeStore and semantic index for Locus hosts |
| 2026-10-14 02:28:48 | [energyml](https://crates.io/crates/energyml) | 0.1.0 | 0 | The EnergyML library in one dependency: read, write and compute RESQML, WITSML,… |
| 2026-10-14 02:38:48 | [energyml-cli](https://crates.io/crates/energyml-cli) | 0.1.0 | 0 | Command-line tool to inspect and validate EnergyML data stores (EPC files today… |
| 2026-10-14 02:40:02 | [jay-task](https://crates.io/crates/jay-task) | 0.3.1 | 0 | Local project manager with a CLI, plain-text tasks, and MCP integration |
| 2026-10-14 02:41:09 | [tisvlay-core](https://crates.io/crates/tisvlay-core) | 0.3.0 | 0 | Core library for multi-vendor TV control |
| 2026-10-14 02:41:10 | [tisvlay-protocol](https://crates.io/crates/tisvlay-protocol) | 0.3.0 | 0 | The zenoh protocol TisVlay's TV-control services and clients speak: key space,… |
| 2026-10-14 02:41:12 | [tisvlay](https://crates.io/crates/tisvlay) | 0.3.0 | 0 | Client library for TisVlay, the Linux daemon that controls smart TVs from the d… |
| 2026-10-14 02:43:39 | [skill-extract](https://crates.io/crates/skill-extract) | 0.1.0 | 0 | Configuration-driven key-value extraction from natural language instructions wi… |
| 2026-10-14 02:43:50 | [diting](https://crates.io/crates/diting) | 0.0.0 | 0 | The diting library. Placeholder release; the API is not yet defined. |
| 2026-10-14 02:44:53 | [footfall_core](https://crates.io/crates/footfall_core) | 0.1.0 | 0 | The Footfall instrumentation API: static descriptors, semantic contexts, levels… |
| 2026-10-14 02:45:07 | [footfall_runtime](https://crates.io/crates/footfall_runtime) | 0.1.0 | 0 | Bounded in-process capture for Footfall: counters, a window of recent events, a… |
| 2026-10-14 02:45:12 | [footfall_memory](https://crates.io/crates/footfall_memory) | 0.1.0 | 0 | Scratch-buffer and cache metrics for Footfall, built on counters. |
| 2026-10-14 02:45:19 | [footfall_fanout](https://crates.io/crates/footfall_fanout) | 0.1.0 | 0 | A Footfall backend that forwards every emission to two others, such as a runtim… |
| 2026-10-14 02:45:29 | [footfall_tracy](https://crates.io/crates/footfall_tracy) | 0.1.0 | 0 | A Footfall backend that shows scopes, counters, and frames live in the Tracy pr… |
| 2026-10-14 02:45:36 | [awpy-proto](https://crates.io/crates/awpy-proto) | 0.1.11076591+2000924 | 0 | Protobuf definitions for Counter-Strike 2 demo files |
| 2026-10-14 02:46:11 | [awpy](https://crates.io/crates/awpy) | 3.0.0 | 0 | Awpy is a Counter-Strike 2 demo parser |
| 2026-10-14 02:56:20 | [footfall_session](https://crates.io/crates/footfall_session) | 0.1.0 | 0 | Footfall snapshots outside the process: owned snapshots, a compact versioned wi… |
| 2026-10-14 03:02:40 | [swnb-ureq](https://crates.io/crates/swnb-ureq) | 2.12.1 | 0 | ureq 2.12.1 with an optional TcpConnector hook for cancellable connects (fork u… |
| 2026-10-14 03:06:02 | [footfall_tracing](https://crates.io/crates/footfall_tracing) | 0.1.0 | 0 | A tracing layer that forwards spans and events into Footfall. |
| 2026-10-14 03:08:30 | [sc-docli](https://crates.io/crates/sc-docli) | 0.2.0 | 0 | Language-agnostic CLI documentation generator: HTML + Markdown from a neutral c… |
| 2026-10-14 03:15:33 | [footfall_export](https://crates.io/crates/footfall_export) | 0.1.0 | 0 | Chrome Trace JSON export of Footfall snapshots, for Perfetto and chrome://traci… |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
