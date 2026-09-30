# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-09-30 12:18 UTC

New crates published between 2026-09-30 11:19 UTC and 2026-09-30 12:18 UTC.

[Full CSV](data/new-crates-2026-09-30T12-18-37-541904Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-09-30 11:24:48 | [zincite](https://crates.io/crates/zincite) | 0.0.0-pre | 0 | MiniZinc development tools (placeholder) |
| 2026-09-30 11:24:55 | [zincite-syntax](https://crates.io/crates/zincite-syntax) | 0.0.0-pre | 0 | Source-preserving MiniZinc syntax for Zincite tooling (placeholder) |
| 2026-09-30 11:25:01 | [zincite-fmt](https://crates.io/crates/zincite-fmt) | 0.0.0-pre | 0 | MiniZinc source formatter (placeholder) |
| 2026-09-30 11:25:07 | [zincite-lint](https://crates.io/crates/zincite-lint) | 0.0.0-pre | 0 | MiniZinc source lint advice (placeholder) |
| 2026-09-30 11:25:32 | [unllm-gateway](https://crates.io/crates/unllm-gateway) | 0.0.1 | 0 | A multi-protocol HTTP gateway for unllm |
| 2026-09-30 11:25:40 | [ironwork-jcl](https://crates.io/crates/ironwork-jcl) | 0.1.2 | 0 | ironwork for COBOL: a reader for z/OS job control language |
| 2026-09-30 11:25:49 | [ironwork-rt](https://crates.io/crates/ironwork-rt) | 0.1.2 | 0 | ironwork for COBOL: the runtime a compiled program links, under the runtime exc… |
| 2026-09-30 11:27:54 | [tabit-derive](https://crates.io/crates/tabit-derive) | 0.1.0 | 0 | tabit's #[rig_tool] procedural macro (vendored from rig 0.41.0). |
| 2026-09-30 11:28:09 | [tabit-protocol](https://crates.io/crates/tabit-protocol) | 0.1.0 | 0 | The tabit frontend protocol vocabulary: commands, stamped events, and the hands… |
| 2026-09-30 11:28:17 | [tabit-gate](https://crates.io/crates/tabit-gate) | 0.1.0 | 0 | The default permission gate: pi-sanity's policy ported to Rust (static, heurist… |
| 2026-09-30 11:28:49 | [tabit-providers](https://crates.io/crates/tabit-providers) | 0.1.0 | 0 | tabit's provider layer: Anthropic + OpenAI wire clients, streaming, and the por… |
| 2026-09-30 11:29:04 | [tabit-log](https://crates.io/crates/tabit-log) | 0.1.0 | 0 | The durable conversation: tree, records, context manager, write buffer — agent-… |
| 2026-09-30 11:36:07 | [huskarl-apple](https://crates.io/crates/huskarl-apple) | 0.1.0 | 0 | macOS/iOS Keychain secrets and Secure Enclave cryptography for the huskarl ecos… |
| 2026-09-30 11:38:56 | [asset-transform-geometry](https://crates.io/crates/asset-transform-geometry) | 0.6.4 | 0 | Geometry detection for deterministic image transforms: scan tilt (Hough) and do… |
| 2026-09-30 11:39:00 | [tabit-config](https://crates.io/crates/tabit-config) | 0.1.0 | 0 | Tabit provider/model configuration: schema, loading, validation. |
| 2026-09-30 11:39:08 | [asset-transform-core](https://crates.io/crates/asset-transform-core) | 0.6.4 | 0 | Deterministic, non-generative image transform engine: pure recipe DSL (crop, re… |
| 2026-09-30 11:39:17 | [asset-transform-store](https://crates.io/crates/asset-transform-store) | 0.6.4 | 0 | Content-addressed, append-only asset store for deterministic image transforms:… |
| 2026-09-30 11:40:11 | [atx-mcp](https://crates.io/crates/atx-mcp) | 0.6.4 | 0 | Deterministic (non-generative) asset transformation MCP server: immutable, cont… |
| 2026-09-30 11:46:51 | [smart-command-runner](https://crates.io/crates/smart-command-runner) | 1.0.1 | 0 | Run grouped shell commands from a TOML file with blocks, confirmation modes, an… |
| 2026-09-30 11:47:57 | [certmagic](https://crates.io/crates/certmagic) | 0.1.0 | 0 | Automatic TLS certificate acquisition, renewal, and maintenance for Rust servers |
| 2026-09-30 11:48:18 | [tabit-engine](https://crates.io/crates/tabit-engine) | 0.1.0 | 0 | tabit's agent engine: the turn loop, hooks, tool runtime, and streaming substra… |
| 2026-09-30 11:48:40 | [mdterm-core](https://crates.io/crates/mdterm-core) | 0.3.0 | 0 | Transcript model, discovery, watch and parse for mdterm |
| 2026-09-30 11:48:54 | [mdterm-pty](https://crates.io/crates/mdterm-pty) | 0.3.0 | 0 | Byte-transparent PTY proxy with hotkey interception for mdterm |
| 2026-09-30 11:49:02 | [mdterm-render](https://crates.io/crates/mdterm-render) | 0.3.0 | 0 | Terminal ANSI renderer (markdown + math + images) for mdterm |
| 2026-09-30 11:49:56 | [mdterm-viewer](https://crates.io/crates/mdterm-viewer) | 0.3.0 | 0 | HTML viewer server (axum + SSE) for mdterm |
| 2026-09-30 11:50:30 | [mdterm-cli](https://crates.io/crates/mdterm-cli) | 0.3.0 | 0 | mdterm binary: PTY-proxy wrapper + markdown render surfaces |
| 2026-09-30 11:51:36 | [ktrs-syntax](https://crates.io/crates/ktrs-syntax) | 0.1.0 | 0 | Kotlin syntax kinds and lossless syntax tree, shaped like the Kotlin compiler's… |
| 2026-09-30 11:51:39 | [ktrs-lexer](https://crates.io/crates/ktrs-lexer) | 0.1.0 | 0 | Kotlin and KDoc lexers, ported from the Kotlin compiler's JFlex specs |
| 2026-09-30 11:51:41 | [ktrs-parser](https://crates.io/crates/ktrs-parser) | 0.1.0 | 0 | Kotlin parser producing PSI-identical lossless trees, ported from the Kotlin co… |
| 2026-09-30 11:51:43 | [ktrs-psi](https://crates.io/crates/ktrs-psi) | 0.1.0 | 0 | Typed Kotlin PSI accessors over the ktrs syntax tree, mirroring the compiler's… |
| 2026-09-30 11:51:46 | [ktrs-fmt](https://crates.io/crates/ktrs-fmt) | 0.1.0 | 0 | Kotlin formatter producing byte-identical output to ktfmt |
| 2026-09-30 11:58:18 | [tabit-wire](https://crates.io/crates/tabit-wire) | 0.1.0 | 0 | The frozen wire's client role and the child-process substrate: spawn a tabit-co… |
| 2026-09-30 12:01:09 | [clipfetch](https://crates.io/crates/clipfetch) | 0.1.0 | 0 | Download TikTok, Instagram and YouTube videos from the terminal, with quality s… |
| 2026-09-30 12:02:43 | [ktrs-cli](https://crates.io/crates/ktrs-cli) | 0.1.0 | 0 | Command-line front ends: `ktrs` and a flag-compatible `ktfmt` (binaries: the ro… |
| 2026-09-30 12:06:43 | [smart-file-duplicate-manager](https://crates.io/crates/smart-file-duplicate-manager) | 1.1.0 | 0 | Safe and fast duplicate file manager: multi-stage detection, dry-run, XDG trash… |
| 2026-09-30 12:08:18 | [tabit-rig](https://crates.io/crates/tabit-rig) | 0.1.0 | 0 | One-dependency facade over tabit-providers + tabit-engine + tabit-derive; hosts… |
| 2026-09-30 12:12:20 | [ktrs](https://crates.io/crates/ktrs) | 0.1.0 | 0 | Fast Kotlin tooling: a ktfmt-identical formatter (`ktrs fmt`, drop-in `ktfmt`) |
| 2026-09-30 12:18:13 | [cordis-wasm](https://crates.io/crates/cordis-wasm) | 0.0.1 | 0 | Host-side WASM adapter for the Cordis plugin runtime. |
| 2026-09-30 12:18:18 | [tabit-tools](https://crates.io/crates/tabit-tools) | 0.1.0 | 0 | Tabit coding tools: file reading and shell execution as PortableTools. |
| 2026-09-30 12:18:22 | [cordis-wasm-runner](https://crates.io/crates/cordis-wasm-runner) | 0.0.1 | 0 | Loader and validator for Cordis WASM plugins. |
| 2026-09-30 12:18:30 | [cordis-wit](https://crates.io/crates/cordis-wit) | 0.0.1 | 0 | Versioned WIT contract definitions (worlds/interfaces) for Cordis. |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
