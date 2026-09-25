# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-09-25 05:19 UTC

New crates published between 2026-09-25 04:19 UTC and 2026-09-25 05:19 UTC.

[Full CSV](data/new-crates-2026-09-25T05-19-13-907909Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-09-25 04:37:48 | [deep_causality_tempfile](https://crates.io/crates/deep_causality_tempfile) | 0.1.0 | 0 | Scratch files and directories removed on drop, std only, for the deep_causality… |
| 2026-09-25 04:42:11 | [decision-core](https://crates.io/crates/decision-core) | 0.1.0 | 0 | Provider-agnostic contracts for typed decision providers |
| 2026-09-25 04:42:44 | [decision-jev](https://crates.io/crates/decision-jev) | 0.1.0 | 0 | Jev adapter for decision-core |
| 2026-09-25 04:43:15 | [decision-openai](https://crates.io/crates/decision-openai) | 0.1.0 | 0 | OpenAI-compatible adapter for decision-core |
| 2026-09-25 04:43:40 | [decision-local-onnx](https://crates.io/crates/decision-local-onnx) | 0.1.0 | 0 | Embedded local ONNX decision provider for decision-core |
| 2026-09-25 04:46:37 | [summa-mal](https://crates.io/crates/summa-mal) | 2.0.0 | 0 | Model Architecture Language (MAL) parser — the single source of truth for Summa… |
| 2026-09-25 04:47:09 | [summa-tokenizer](https://crates.io/crates/summa-tokenizer) | 2.0.0 | 0 | Stable-Rust byte-level BPE tokenization for Summa |
| 2026-09-25 04:47:29 | [claude-session-restore](https://crates.io/crates/claude-session-restore) | 0.1.2 | 0 | CLI tool for summarizing and restoring Claude Code sessions |
| 2026-09-25 04:47:46 | [summa-broker](https://crates.io/crates/summa-broker) | 2.0.0 | 0 | gRPC broker routing across multiple Summa server instances |
| 2026-09-25 04:47:48 | [summa-tool](https://crates.io/crates/summa-tool) | 2.0.0 | 0 | CLI tools for Summa - index management, simhash, sorting, and data processing |
| 2026-09-25 04:48:10 | [hexgridrect](https://crates.io/crates/hexgridrect) | 0.1.0 | 0 | A library for working with hexagonal grids in a rectangular coordinate system. |
| 2026-09-25 04:48:13 | [neura-ir](https://crates.io/crates/neura-ir) | 0.2.0 | 0 | Backend-independent Rust compute intermediate representation |
| 2026-09-25 04:48:52 | [neura-macro](https://crates.io/crates/neura-macro) | 0.2.0 | 0 | Compile-time Rust frontend for native compute kernels |
| 2026-09-25 04:49:38 | [neura-compiler](https://crates.io/crates/neura-compiler) | 0.2.0 | 0 | Rust compute frontend, validated device IR and native code generation |
| 2026-09-25 04:50:16 | [neura-op](https://crates.io/crates/neura-op) | 0.2.0 | 0 | Pointwise operations and differentiation rules shared by graph and shader |
| 2026-09-25 04:50:57 | [neura-precision](https://crates.io/crates/neura-precision) | 0.2.0 | 0 | Tensor storage precision and host packing |
| 2026-09-25 05:03:05 | [cargo-tops](https://crates.io/crates/cargo-tops) | 0.1.1 | 0 | init / check / gate for the Rust-TOPS protocol. Orchestrates existing Cargo too… |
| 2026-09-25 05:06:49 | [websec-diagnostics](https://crates.io/crates/websec-diagnostics) | 0.1.0 | 0 | Source locations, severity, and machine-readable diagnostics for WEBSEC |
| 2026-09-25 05:07:04 | [websec-lexer](https://crates.io/crates/websec-lexer) | 0.1.0 | 0 | WEBSEC lexer |
| 2026-09-25 05:07:08 | [websec-ast](https://crates.io/crates/websec-ast) | 0.1.0 | 0 | WEBSEC generic and typed abstract syntax trees |
| 2026-09-25 05:07:11 | [websec-parser](https://crates.io/crates/websec-parser) | 0.1.0 | 0 | WEBSEC recursive-descent parser |
| 2026-09-25 05:07:16 | [websec-semantic](https://crates.io/crates/websec-semantic) | 0.1.0 | 0 | WEBSEC semantic analysis and typed-policy lowering |
| 2026-09-25 05:10:34 | [oppex-integration-sdk](https://crates.io/crates/oppex-integration-sdk) | 1.0.0 | 0 | Oppex incident API client: post incidents to Oppex from Rust applications. |
| 2026-09-25 05:14:20 | [nexuss](https://crates.io/crates/nexuss) | 0.1.1 | 0 | High-performance, standalone search and retrieval engine for AI agents. Multi-e… |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
