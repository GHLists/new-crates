# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-10-31 03:18 UTC

New crates published between 2026-10-31 02:19 UTC and 2026-10-31 03:18 UTC.

[Full CSV](data/new-crates-2026-10-31T03-18-29-75459Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-10-31 02:27:07 | [noxi-store](https://crates.io/crates/noxi-store) | 0.0.1 | 0 | A local Nix store compatible with CppNix's on-disk format |
| 2026-10-31 02:35:30 | [phi-wire-protocol](https://crates.io/crates/phi-wire-protocol) | 0.1.0 | 0 | Provider wire protocol for the phi family: versioned requests, replies, and err… |
| 2026-10-31 02:35:38 | [phi-wire-adapter](https://crates.io/crates/phi-wire-adapter) | 0.1.0 | 0 | Provider contract shared by phi wire clients and platform adapters |
| 2026-10-31 02:35:45 | [phi-wire-client](https://crates.io/crates/phi-wire-client) | 0.1.0 | 0 | Correlated JSON-lines subprocess transport for the phi family: cancellation nev… |
| 2026-10-31 02:41:43 | [frust-rs](https://crates.io/crates/frust-rs) | 0.1.1 | 0 | A thin accelerator that sits on top of your installed Rust toolchain: shared co… |
| 2026-10-31 02:46:05 | [provenance-contract](https://crates.io/crates/provenance-contract) | 0.0.0 | 0 | Internal part of Provenance for the operation wire contract |
| 2026-10-31 02:50:55 | [sqlx-doris-mysql](https://crates.io/crates/sqlx-doris-mysql) | 0.9.0 | 0 | Doris-compatible MySQL driver implementation for SQLx, bundled with sqlx-doris;… |
| 2026-10-31 02:51:23 | [sqlx-doris](https://crates.io/crates/sqlx-doris) | 0.1.0 | 0 | SQLx MySQL and Apache Doris connections, native types, and operations |
| 2026-10-31 02:52:15 | [voltik](https://crates.io/crates/voltik) | 0.16.0 | 0 | CircuiTikZ circuits to SVG and PNG with no TeX install, as a library of tikra. |
| 2026-10-31 02:52:34 | [voltik-cli](https://crates.io/crates/voltik-cli) | 0.16.0 | 0 | Command line for voltik: CircuiTikZ to SVG and PNG. |
| 2026-10-31 02:55:27 | [kyln](https://crates.io/crates/kyln) | 0.3.0 | 0 | A guarded TUI for reviewing old caches and diagnostic logs |
| 2026-10-31 02:56:23 | [autoseek](https://crates.io/crates/autoseek) | 0.1.0 | 0 | 只做一件事的 agent：给定问题、数据和目标，自己写代码、跑实验、分析结果，反复迭代出技术方案 |
| 2026-10-31 02:59:21 | [hf-fetch](https://crates.io/crates/hf-fetch) | 0.1.0 | 0 | Small blocking Hugging Face model downloader with a Python-compatible cache |
| 2026-10-31 03:03:40 | [punct-converter](https://crates.io/crates/punct-converter) | 0.1.0 | 0 | Fast CLI & library to convert Chinese full-width punctuation to English/half-wi… |
| 2026-10-31 03:09:30 | [toskar](https://crates.io/crates/toskar) | 0.4.0 | 0 | The official Rust SDK for Toskar: local AI across your own computers. |
| 2026-10-31 03:10:38 | [writerslogic-warm](https://crates.io/crates/writerslogic-warm) | 0.6.4 | 0 | Local-first search engine and agent memory: fast approximate nearest-neighbor a… |
| 2026-10-31 03:15:39 | [buildl-core](https://crates.io/crates/buildl-core) | 0.1.0 | 0 | Domain data, ports, and pure pipeline logic for the buildl build system — no I/… |
| 2026-10-31 03:15:42 | [buildl-lua](https://crates.io/crates/buildl-lua) | 0.1.0 | 0 | Lua build-file evaluation for buildl, on the airsl embedded runtime. |
| 2026-10-31 03:15:47 | [buildl](https://crates.io/crates/buildl) | 0.1.0 | 0 | A sandboxed, deterministic build system whose build files are written in Lua an… |
| 2026-10-31 03:15:51 | [buildl-cli](https://crates.io/crates/buildl-cli) | 0.1.0 | 0 | The `buildl` binary — the command-line entry point to the buildl library. |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
