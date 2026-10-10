# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-10-10 20:19 UTC

New crates published between 2026-10-10 19:19 UTC and 2026-10-10 20:19 UTC.

[Full CSV](data/new-crates-2026-10-10T20-19-57-778595Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-10-10 19:20:31 | [brenn-git-fixture](https://crates.io/crates/brenn-git-fixture) | 0.1.0 | 0 | Hermetic git spawning for test fixtures, with a repo-escape canary |
| 2026-10-10 19:24:32 | [subcrate-core](https://crates.io/crates/subcrate-core) | 0.1.0 | 0 | Shared logic for the `subcrate` crate: subcrate identity/naming and attribute p… |
| 2026-10-10 19:24:37 | [subcrate-macros](https://crates.io/crates/subcrate-macros) | 0.1.0 | 0 | Procedural macro implementation for the `subcrate` crate. Use `subcrate` instea… |
| 2026-10-10 19:24:44 | [subcrate](https://crates.io/crates/subcrate) | 0.1.0 | 0 | Define real, independently compiled Rust crates with inline `#[subcrate]` modul… |
| 2026-10-10 19:28:33 | [megabase](https://crates.io/crates/megabase) | 0.0.0 | 0 | Name reserved for MEGABASE, a Rust reimplementation of Supabase built by AI age… |
| 2026-10-10 19:30:45 | [tmtr](https://crates.io/crates/tmtr) | 0.0.5-alpha.1 | 0 | Minimal CLI time tracker with a TUI stopwatch |
| 2026-10-10 19:34:35 | [wasi-dbms-key-value-memory](https://crates.io/crates/wasi-dbms-key-value-memory) | 0.11.0 | 0 | Cached key-value memory provider for wasm-dbms on WASI |
| 2026-10-10 19:40:03 | [slap](https://crates.io/crates/slap) | 1.1.0 | 0 | Keep your Mac awake with a playful space-themed terminal timer |
| 2026-10-10 19:42:59 | [gneiss-macros](https://crates.io/crates/gneiss-macros) | 0.1.0 | 0 | Macros for gneiss, an SDK for pebble watches |
| 2026-10-10 19:43:00 | [gneiss-types](https://crates.io/crates/gneiss-types) | 0.1.1 | 0 | Shared types across gneiss libs and build tools |
| 2026-10-10 19:43:02 | [gneiss-build](https://crates.io/crates/gneiss-build) | 0.1.1 | 0 | Build-time resource compiling and bundling for gneiss apps |
| 2026-10-10 19:43:06 | [cargo-gneiss](https://crates.io/crates/cargo-gneiss) | 0.1.0 | 0 | Create, build and install gneiss Pebble apps |
| 2026-10-10 19:43:07 | [gneiss-sys](https://crates.io/crates/gneiss-sys) | 0.1.1 | 0 | Raw PebbleOS app syscall bindings for gneiss |
| 2026-10-10 19:44:18 | [spate-clickhouse-derive](https://crates.io/crates/spate-clickhouse-derive) | 0.2.0 | 0 | Proc-macro backing #[derive(ClickHouseRow)] for spate-clickhouse: generates the… |
| 2026-10-10 19:52:32 | [gneiss](https://crates.io/crates/gneiss) | 0.1.1 | 0 | Safe Rust SDK for Pebble watchapps and watchfaces |
| 2026-10-10 19:55:50 | [sniff-rs](https://crates.io/crates/sniff-rs) | 0.1.0 | 0 | Profile a data file and produce a data dictionary - observed types, missing %,… |
| 2026-10-10 19:58:44 | [minimenta](https://crates.io/crates/minimenta) | 0.1.0 | 0 | Minuere impedimenta: an interactive disk usage analyzer for the terminal |
| 2026-10-10 20:12:51 | [staticly-hash](https://crates.io/crates/staticly-hash) | 0.1.0 | 0 | Compile-time lookup generator |
| 2026-10-10 20:12:53 | [staticly-macros](https://crates.io/crates/staticly-macros) | 0.1.0 | 0 | Compile-time lookup generator |
| 2026-10-10 20:12:55 | [staticly](https://crates.io/crates/staticly) | 0.1.0 | 0 | Compile-time lookup generator |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
