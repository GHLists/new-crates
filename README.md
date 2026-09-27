# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-09-27 19:21 UTC

New crates published between 2026-09-27 18:18 UTC and 2026-09-27 19:21 UTC.

[Full CSV](data/new-crates-2026-09-27T19-21-29-022185Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-09-27 18:29:48 | [stackup-eda-parser](https://crates.io/crates/stackup-eda-parser) | 0.1.0 | 0 | Reads and writes stackup's KDL design format |
| 2026-09-27 18:30:21 | [vysx_std](https://crates.io/crates/vysx_std) | 0.1.0 | 0 | vysx standard library, a set of utilities that default rust std does not have. |
| 2026-09-27 18:30:25 | [stackup-eda](https://crates.io/crates/stackup-eda) | 0.1.1 | 0 | Elaborates a stackup design and writes what a PCB tool imports |
| 2026-09-27 18:41:30 | [tollgate-core](https://crates.io/crates/tollgate-core) | 0.30.1 | 0 | Zero-I/O, clock-free domain layer for quota admission and accounting: cost tabl… |
| 2026-09-27 18:41:35 | [tollgate-auth](https://crates.io/crates/tollgate-auth) | 0.30.1 | 0 | Credential verification for latency-critical services: digests at rest, and a s… |
| 2026-09-27 18:41:44 | [tollgate-store](https://crates.io/crates/tollgate-store) | 0.30.1 | 0 | Storage abstraction for tollgate: LeaseAllocator, SnapshotSource, and UsageSink… |
| 2026-09-27 18:41:54 | [tollgate-admission](https://crates.io/crates/tollgate-admission) | 0.30.1 | 0 | Per-request admission pipeline: snapshot lookup, permission and staleness check… |
| 2026-09-27 18:42:23 | [tollgate-store-postgres](https://crates.io/crates/tollgate-store-postgres) | 0.30.1 | 0 | PostgreSQL backend for tollgate: transactional fenced lease allocation, idempot… |
| 2026-09-27 18:44:58 | [tollgate-client](https://crates.io/crates/tollgate-client) | 0.30.1 | 0 | Instance-side quota runtime: background lease refill into the admission layer's… |
| 2026-09-27 18:46:51 | [cs2-api](https://crates.io/crates/cs2-api) | 1.0.0 | 0 | CS2 API client for Rust: Counter-Strike 2 live scores, match results, player st… |
| 2026-09-27 18:51:14 | [gorilla-rust](https://crates.io/crates/gorilla-rust) | 1.4.2 | 0 | A pixel-faithful Rust port of the 1990 QBasic GORILLAS, measured against the or… |
| 2026-09-27 18:55:51 | [tollgate-server](https://crates.io/crates/tollgate-server) | 0.30.1 | 0 | Control-plane HTTP service: fenced lease allocation, snapshot distribution, ide… |
| 2026-09-27 19:00:08 | [links_and_nodes_rdb](https://crates.io/crates/links_and_nodes_rdb) | 0.7.0 | 0 | Read Links and Nodes lnrecorder databases (lnrdb) in pure Rust. |
| 2026-09-27 19:00:32 | [cexy](https://crates.io/crates/cexy) | 0.1.0-dev.1 | 0 | Official Rust SDK for the CEXY.io exchange API (REST + WebSocket) |
| 2026-09-27 19:02:06 | [veloci](https://crates.io/crates/veloci) | 0.1.1 | 0 | Veloci Redactor: redact secrets and PII from text and structured files, with st… |
| 2026-09-27 19:06:24 | [fontsrc](https://crates.io/crates/fontsrc) | 0.0.0 | 0 | Read and write authored font sources (UFO, Designspace, Glyphs) in Rust and Typ… |
| 2026-09-27 19:06:29 | [orx-col-dim](https://crates.io/crates/orx-col-dim) | 0.1.0 | 0 | Dimension trait and implementations for multi-dimensional collections |
| 2026-09-27 19:07:32 | [kbfold](https://crates.io/crates/kbfold) | 0.2.0 | 0 | KBFold: a multilinear polynomial commitment from the Boolean-kernel basis, with… |
| 2026-09-27 19:08:10 | [riverqueue-pro](https://crates.io/crates/riverqueue-pro) | 0.0.0 | 0 | River Pro for Rust — placeholder for the forthcoming implementation. |
| 2026-09-27 19:11:54 | [JoystickHackx](https://crates.io/crates/JoystickHackx) | 0.1.0 | 0 | Joystick driver for hackxpansion! |
| 2026-09-27 19:18:44 | [mistralai-sdk](https://crates.io/crates/mistralai-sdk) | 0.4.0 | 0 | Unofficial Mistral AI SDK reproducibly generated from the official OpenAPI spec… |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
