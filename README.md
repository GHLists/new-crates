# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-11-08 22:18 UTC

New crates published between 2026-11-08 21:19 UTC and 2026-11-08 22:18 UTC.

[Full CSV](data/new-crates-2026-11-08T22-18-18-485032Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-11-08 21:19:43 | [ponko_ecs](https://crates.io/crates/ponko_ecs) | 0.0.1 | 0 | The entity-component-system behind Ponko: archetype storage, runtime-registered… |
| 2026-11-08 21:19:44 | [ponko_unity](https://crates.io/crates/ponko_unity) | 0.0.1 | 0 | Reads Unity projects (text YAML scenes, prefabs, materials and meshes, .meta GU… |
| 2026-11-08 21:19:47 | [ponko](https://crates.io/crates/ponko) | 0.0.1 | 0 | A fast 2D game engine for simulating millions of things: ECS on all cores, hot… |
| 2026-11-08 21:19:48 | [ponko_bench](https://crates.io/crates/ponko_bench) | 0.0.1 | 0 | Benchmarks: ponko_ecs vs bevy_ecs vs hecs, and simulation at scale. |
| 2026-11-08 21:19:49 | [ponko_ffi](https://crates.io/crates/ponko_ffi) | 0.0.1 | 0 | C API for Ponko; include/crabby.hpp wraps it for C++17. |
| 2026-11-08 21:23:57 | [ponko_mcp](https://crates.io/crates/ponko_mcp) | 0.0.1 | 0 | MCP server that lets AI agents inspect and drive running Ponko games |
| 2026-11-08 21:31:51 | [vera-identity](https://crates.io/crates/vera-identity) | 0.1.0 | 0 | DID identity types |
| 2026-11-08 21:35:38 | [yamlprims](https://crates.io/crates/yamlprims) | 0.1.0 | 0 | Owned YAML values, strict parsing, typed conversion and bounded wire encoding |
| 2026-11-08 21:40:45 | [quentangled](https://crates.io/crates/quentangled) | 0.1.0 | 0 | A state vector based quantum circuit simulator. |
| 2026-11-08 21:44:11 | [vera-zanzibar](https://crates.io/crates/vera-zanzibar) | 0.1.0 | 0 | Zanzibar relation-tuple evaluation engine |
| 2026-11-08 21:45:08 | [vera-acp](https://crates.io/crates/vera-acp) | 0.1.0 | 0 | Access control policy types and policy YAML parsing |
| 2026-11-08 21:46:02 | [vera-crypto](https://crates.io/crates/vera-crypto) | 0.1.0 | 0 | Cryptographic utilities for vera |
| 2026-11-08 21:47:06 | [vera-domain](https://crates.io/crates/vera-domain) | 0.1.0 | 0 | Domain types for vera |
| 2026-11-08 21:47:44 | [aster-terminal](https://crates.io/crates/aster-terminal) | 0.1.0 | 0 | A customizable Windows terminal emulator and multiplexer written in rust |
| 2026-11-08 21:47:48 | [vera-modules](https://crates.io/crates/vera-modules) | 0.1.0 | 0 | Vera module implementations (ACP, Bulletin, Vera) |
| 2026-11-08 21:48:45 | [vera-permission](https://crates.io/crates/vera-permission) | 0.1.0 | 0 | Verified native permission requests and read evidence |
| 2026-11-08 21:55:16 | [clippy-new-lines](https://crates.io/crates/clippy-new-lines) | 0.1.0 | 0 | Check new lines from VCS for clippy |
| 2026-11-08 21:56:10 | [dimvexa-core](https://crates.io/crates/dimvexa-core) | 0.1.0 | 0 | Unit conversion core: dimensions, exact rationals, parser and prepared conversi… |
| 2026-11-08 21:56:33 | [dimvexa-data](https://crates.io/crates/dimvexa-data) | 0.1.0 | 0 | Unit conversion tables for dimvexa, compiled from audited TOML. Exact factors.… |
| 2026-11-08 21:56:45 | [dimvexa-config](https://crates.io/crates/dimvexa-config) | 0.1.0 | 0 | User config files for dimvexa: your own names, units and density bridges (mt =… |
| 2026-11-08 21:56:52 | [dimvexa](https://crates.io/crates/dimvexa) | 0.1.0 | 0 | Exact, fast unit conversion for Rust: core plus the seed unit table. Exact fact… |
| 2026-11-08 21:57:50 | [vera-client](https://crates.io/crates/vera-client) | 0.1.0 | 0 | Rust client library for vera (EVM + BLS transaction paths) |
| 2026-11-08 22:05:54 | [dimvexa-cli](https://crates.io/crates/dimvexa-cli) | 0.1.0 | 0 | Command-line unit conversion tool built on dimvexa. Exact factors. Loud failure… |
| 2026-11-08 22:06:57 | [vera-verifier](https://crates.io/crates/vera-verifier) | 0.1.0 | 0 | Native proof verification for foreign-language Vera clients |
| 2026-11-08 22:10:25 | [cimoxide-view](https://crates.io/crates/cimoxide-view) | 0.6.1 | 0 | A CGMES or NC model set as views: its grid at substation level, laid out, and i… |
| 2026-11-08 22:13:28 | [muninn-plugin](https://crates.io/crates/muninn-plugin) | 1.3.0 | 0 | SDK for Muninn code space plugins: the stable C ABI (v1), the host API, frames… |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
