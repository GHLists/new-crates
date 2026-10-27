# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-10-27 01:21 UTC

New crates published between 2026-10-27 00:19 UTC and 2026-10-27 01:21 UTC.

[Full CSV](data/new-crates-2026-10-27T01-21-10-677434Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-10-27 00:22:53 | [cronoq-store-sqlite](https://crates.io/crates/cronoq-store-sqlite) | 0.2.0 | 0 | SQLite store for cronoq: durable state in a local file, with standby processes… |
| 2026-10-27 00:23:03 | [xur-std](https://crates.io/crates/xur-std) | 0.1.1 | 0 | The standard library of the Xur language |
| 2026-10-27 00:24:41 | [bboxy450-yarn](https://crates.io/crates/bboxy450-yarn) | 0.1.0 | 0 | A no_std reactor kernel for explicit, compile-checked async orchestration |
| 2026-10-27 00:32:27 | [xur-bytecode](https://crates.io/crates/xur-bytecode) | 0.1.1 | 0 | The register-based bytecode of the Xur language, and lowering to it |
| 2026-10-27 00:33:31 | [cronoq-server](https://crates.io/crates/cronoq-server) | 0.2.0 | 0 | gRPC/HTTP server for the cronoq scheduler with remote workers |
| 2026-10-27 00:34:41 | [bboxy450-doc](https://crates.io/crates/bboxy450-doc) | 0.1.0 | 0 | Native Markdown documents on bboxy's retained UI and text pipeline |
| 2026-10-27 00:35:31 | [verdict-gate](https://crates.io/crates/verdict-gate) | 0.0.0 | 0 | Verdict: the agent writes claims, never verdicts. Command-line tool (vdt). |
| 2026-10-27 00:42:57 | [xur-jit](https://crates.io/crates/xur-jit) | 0.1.1 | 0 | A Cranelift JIT for Xur bytecode (not implemented yet) |
| 2026-10-27 00:44:41 | [bboxy450-keychain](https://crates.io/crates/bboxy450-keychain) | 0.1.0 | 0 | Explicit identity custody backend selection |
| 2026-10-27 00:48:05 | [countyroot-verify](https://crates.io/crates/countyroot-verify) | 0.1.0 | 0 | Verify CountyRoot parcel proofs (leaf v2) against on-chain CountyRoot roots ins… |
| 2026-10-27 00:52:27 | [xur-vm](https://crates.io/crates/xur-vm) | 0.1.1 | 0 | The bytecode interpreter of the Xur language |
| 2026-10-27 00:53:03 | [libmap](https://crates.io/crates/libmap) | 0.1.0 | 0 | System-wide ELF dependency index: reverse deps, symbol-version ABI checks, and… |
| 2026-10-27 00:54:41 | [bboxy450-render](https://crates.io/crates/bboxy450-render) | 0.1.0 | 0 | Retained GPU rendering, terminal text shaping and compositor primitives |
| 2026-10-27 01:04:42 | [bboxy450-book](https://crates.io/crates/bboxy450-book) | 0.1.0 | 0 | Native component gallery, document rendering and visual parity tools |
| 2026-10-27 01:06:56 | [codex-commit](https://crates.io/crates/codex-commit) | 0.2.0 | 0 | Commit Git changes with Codex Luna at Max reasoning, with optional push |
| 2026-10-27 01:14:42 | [bboxy450-mux](https://crates.io/crates/bboxy450-mux) | 0.1.0 | 0 | Local terminal sessions, durable messaging and knowledge-provider coordination |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
