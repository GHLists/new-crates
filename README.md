# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-11-07 20:19 UTC

New crates published between 2026-11-07 19:20 UTC and 2026-11-07 20:19 UTC.

[Full CSV](data/new-crates-2026-11-07T20-19-50-946671Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-11-07 19:38:20 | [nornir-mimir-ingest](https://crates.io/crates/nornir-mimir-ingest) | 0.1.0 | 0 | Mímir v2 consumer: a repo's first-parent git history as the change log (Debeziu… |
| 2026-11-07 19:38:51 | [nornir-mimir-room](https://crates.io/crates/nornir-mimir-room) | 0.1.0 | 0 | Mímir v2 code room, read side: the event log folded into a snapshot (dense ordi… |
| 2026-11-07 19:39:03 | [git-compose-commit](https://crates.io/crates/git-compose-commit) | 0.2.1 | 0 | Build well-formatted Git commit messages from the command line |
| 2026-11-07 19:39:48 | [nornir-mimir-exec](https://crates.io/crates/nornir-mimir-exec) | 0.1.0 | 0 | Mímir v2: executes the code graph like a program. Reads the lossless MIR rows (… |
| 2026-11-07 19:43:18 | [nornir-trace](https://crates.io/crates/nornir-trace) | 0.1.0 | 0 | Function-level run traces for the Mímir code map — reads an LLVM XRay basic-mod… |
| 2026-11-07 19:45:05 | [ciber_cbr](https://crates.io/crates/ciber_cbr) | 0.1.0 | 0 | CBR data format parser, formatter, and document handling library |
| 2026-11-07 19:51:37 | [pscon](https://crates.io/crates/pscon) | 0.1.0 | 0 | Browser-assisted reconnaissance console with an interactive TUI and headless CLI |
| 2026-11-07 19:54:29 | [convex-typegen-macros](https://crates.io/crates/convex-typegen-macros) | 1.0.0 | 0 | Derive macros for convex-typegen-runtime |
| 2026-11-07 19:55:07 | [convex-typegen-runtime](https://crates.io/crates/convex-typegen-runtime) | 1.0.0 | 0 | Typed Convex client runtime for convex-typegen bindings |
| 2026-11-07 20:01:27 | [skribble_rough](https://crates.io/crates/skribble_rough) | 0.0.0 | 0 | skribble's hand-drawn rendering engine for Rust: seeded rough shapes, sketched… |
| 2026-11-07 20:01:31 | [skribble_leptoskit](https://crates.io/crates/skribble_leptoskit) | 0.0.0 | 0 | Hand-drawn leptoskit components from the skribble design system: rough borders,… |
| 2026-11-07 20:01:34 | [skribble_leptoskit_charts](https://crates.io/crates/skribble_leptoskit_charts) | 0.0.0 | 0 | Hand-drawn financial charts for leptoskit: candlesticks, lines, bars, volume, a… |
| 2026-11-07 20:01:38 | [skribble_leptoskit_maps](https://crates.io/crates/skribble_leptoskit_maps) | 0.0.0 | 0 | Hand-drawn vector maps for leptoskit apps from the skribble design system: sket… |
| 2026-11-07 20:12:50 | [mcp-moat-core](https://crates.io/crates/mcp-moat-core) | 0.1.0 | 0 | Policy engine, path jail, secret masking, and audit log chain for mcp-moat |
| 2026-11-07 20:12:57 | [mcp-moat-tty](https://crates.io/crates/mcp-moat-tty) | 0.1.0 | 0 | Terminal prompts (/dev/tty and CONIN$), unified diffs, and session approval cac… |
| 2026-11-07 20:13:18 | [mcp-moat-proxy](https://crates.io/crates/mcp-moat-proxy) | 0.1.0 | 0 | Stdio JSON-RPC proxy and stream engine for mcp-moat |
| 2026-11-07 20:13:41 | [mcp-moat](https://crates.io/crates/mcp-moat) | 0.1.0 | 0 | Stdio policy proxy for Model Context Protocol (MCP) servers |
| 2026-11-07 20:15:41 | [heine](https://crates.io/crates/heine) | 0.12.1 | 0 | A small, checked static-site generator |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
