# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-11-16 03:19 UTC

New crates published between 2026-11-16 02:19 UTC and 2026-11-16 03:19 UTC.

[Full CSV](data/new-crates-2026-11-16T03-19-16-018798Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-11-16 02:28:33 | [fux-pane](https://crates.io/crates/fux-pane) | 0.38.0 | 0 | fux's pane process: a pane's terminal, its input and its program, and what it a… |
| 2026-11-16 02:32:03 | [aonyx-rakko-rust-binary](https://crates.io/crates/aonyx-rakko-rust-binary) | 0.1.0 | 0 | A Rakko bundle of the actions for Rust projects of Aonyx that ship a binary |
| 2026-11-16 02:36:35 | [rustterm](https://crates.io/crates/rustterm) | 0.1.14 | 0 | A native desktop workspace for terminals, remote desktops, and databases |
| 2026-11-16 02:40:43 | [tgradish-tgs](https://crates.io/crates/tgradish-tgs) | 0.1.0 | 0 | Pure-Rust library that turns pixel art from GIF, APNG, WebP, Aseprite or sprite… |
| 2026-11-16 02:41:04 | [tgradish-core](https://crates.io/crates/tgradish-core) | 2.0.0 | 0 | Library behind tgradish: Telegram video, static and pixel art sticker conversio… |
| 2026-11-16 02:41:29 | [tgradish-gui](https://crates.io/crates/tgradish-gui) | 2.0.0 | 0 | The tgradish GUI: converts with tgradish-core |
| 2026-11-16 02:41:55 | [tgradish](https://crates.io/crates/tgradish) | 2.0.0 | 0 | Telegram video, static and animated stickers and emoji from videos, images or p… |
| 2026-11-16 02:50:26 | [pii-veil-core](https://crates.io/crates/pii-veil-core) | 0.1.0 | 0 | Ultrafast, deterministic, and reversible PII & secret anonymization engine for… |
| 2026-11-16 02:50:44 | [pii-veil-ffi](https://crates.io/crates/pii-veil-ffi) | 0.1.0 | 0 | C-ABI Foreign Function Interface (FFI) bindings for pii-veil-core (for Go cgo,… |
| 2026-11-16 02:53:00 | [brrrty-js](https://crates.io/crates/brrrty-js) | 0.0.3 | 0 | JavaScript-semantics values shared by Brrrty's template engines, for an Elevent… |
| 2026-11-16 02:53:03 | [brrrty-liquid](https://crates.io/crates/brrrty-liquid) | 0.0.3 | 0 | A Liquid template engine that matches LiquidJS as Eleventy configures it, for a… |
| 2026-11-16 02:57:40 | [aonyx-rakko-rust-library](https://crates.io/crates/aonyx-rakko-rust-library) | 0.1.0 | 0 | A Rakko bundle of the actions for Rust projects of Aonyx that publish a library |
| 2026-11-16 03:02:14 | [cfgy-core](https://crates.io/crates/cfgy-core) | 0.1.0 | 0 | Core value IR, conversion traits, and error types for cfgy. Format-agnostic; yo… |
| 2026-11-16 03:02:18 | [cfgy-formats](https://crates.io/crates/cfgy-formats) | 0.1.0 | 0 | Feature-gated TOML, JSON, and YAML adapters that lower source text into the cfg… |
| 2026-11-16 03:02:22 | [cfgy-derive](https://crates.io/crates/cfgy-derive) | 0.1.0 | 0 | Proc-macro implementation of cfgy's `FromConfig` derive. Re-exported by `cfgy`;… |
| 2026-11-16 03:02:27 | [cfgy](https://crates.io/crates/cfgy) | 0.1.0 | 0 | Derive config structs from TOML, JSON, or YAML files, with the file checked at… |
| 2026-11-16 03:05:34 | [orint](https://crates.io/crates/orint) | 0.0.0 | 0 | oi — orchestrating intelligence: agent orchestrator (reserved placeholder, no f… |
| 2026-11-16 03:06:53 | [oi-rs](https://crates.io/crates/oi-rs) | 0.0.0 | 0 | oi — orchestrating intelligence: agent orchestrator (reserved placeholder, no f… |
| 2026-11-16 03:07:31 | [oi-cli](https://crates.io/crates/oi-cli) | 0.0.0 | 0 | oi — orchestrating intelligence: agent orchestrator (reserved placeholder, no f… |
| 2026-11-16 03:11:21 | [maac](https://crates.io/crates/maac) | 0.6.1 | 0 | MaaC (Music as a Code) parser, compiler, and renderer |
| 2026-11-16 03:13:35 | [agt](https://crates.io/crates/agt) | 0.0.0 | 0 | agt — sandboxed agent runtime: isolated per-instance workspaces and launch-secu… |
| 2026-11-16 03:15:20 | [agt-rs](https://crates.io/crates/agt-rs) | 0.0.0 | 0 | agt — sandboxed agent runtime: isolated per-instance workspaces and launch-secu… |
| 2026-11-16 03:18:08 | [agt-cli](https://crates.io/crates/agt-cli) | 0.0.0 | 0 | agt — sandboxed agent runtime: isolated per-instance workspaces and launch-secu… |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
