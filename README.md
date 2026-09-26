# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-09-26 13:18 UTC

New crates published between 2026-09-26 12:19 UTC and 2026-09-26 13:18 UTC.

[Full CSV](data/new-crates-2026-09-26T13-18-56-095733Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-09-26 12:22:18 | [bonsai-lang-python](https://crates.io/crates/bonsai-lang-python) | 0.4.1 | 0 | Python language support for bonsai-lint |
| 2026-09-26 12:22:22 | [silicon-peek-client](https://crates.io/crates/silicon-peek-client) | 0.1.1 | 0 | Wire types, validators and a stateless HTTP client for Peek; the `runtime` feat… |
| 2026-09-26 12:22:40 | [silicon-peek-cli](https://crates.io/crates/silicon-peek-cli) | 0.1.1 | 0 | The peek command-line interface: IAM login, positions, drawings and speak/show/… |
| 2026-09-26 12:29:48 | [farhand-agent](https://crates.io/crates/farhand-agent) | 1.9.0 | 0 | Farhand agent daemon: persistent workspace caching, process isolation, and buil… |
| 2026-09-26 12:30:09 | [farhand-cli](https://crates.io/crates/farhand-cli) | 1.9.0 | 0 | Farhand CLI client: offload compilation, test, and build jobs to remote machines |
| 2026-09-26 12:34:37 | [konomanoasa-tree-sitter-posix-awk](https://crates.io/crates/konomanoasa-tree-sitter-posix-awk) | 0.18.0 | 0 | Tree-sitter grammar for POSIX awk. |
| 2026-09-26 12:34:39 | [hlin-bridge](https://crates.io/crates/hlin-bridge) | 0.1.0 | 0 | The Hlin module bridge on the wire: every message between a module's frame and… |
| 2026-09-26 12:35:33 | [hlin-module](https://crates.io/crates/hlin-module) | 0.1.0 | 0 | The SDK for a Leptos module hosted by Hlin: the bridge to the shell, so a modul… |
| 2026-09-26 12:36:45 | [hlin-sample-checklist](https://crates.io/crates/hlin-sample-checklist) | 0.1.0 | 0 | A reference platform for Hlin that accepts writes: shared checklists, with rule… |
| 2026-09-26 12:36:49 | [hlin-sample-feed](https://crates.io/crates/hlin-sample-feed) | 0.1.0 | 0 | A reference platform for Hlin that accepts writes: a feed of posts, and who may… |
| 2026-09-26 12:39:24 | [onthou](https://crates.io/crates/onthou) | 0.0.0 | 0 | Onthou (on-TOH), Afrikaans for 'remember': persistent agent memory in Rust |
| 2026-09-26 12:49:58 | [konomanoasa-tree-sitter-gitignore](https://crates.io/crates/konomanoasa-tree-sitter-gitignore) | 0.2.0 | 0 | Tree-sitter grammar for gitignore. |
| 2026-09-26 12:53:45 | [unlit_ecs](https://crates.io/crates/unlit_ecs) | 0.1.0-dev.1 | 0 | A compact archetype ECS: immutable archetypes, cell-based components, behaviour… |
| 2026-09-26 12:53:59 | [unlit_wgpu](https://crates.io/crates/unlit_wgpu) | 0.1.0-dev.1 | 0 | A compact, opinionated WebGPU renderer for unlit draws: resource graph, vertex… |
| 2026-09-26 12:54:27 | [unlit3d](https://crates.io/crates/unlit3d) | 0.1.0-dev.1 | 0 | The high-level WebGPU rendering API over unlit_wgpu and unlit_ecs: ECS componen… |
| 2026-09-26 12:58:15 | [conui-cell](https://crates.io/crates/conui-cell) | 0.1.0 | 0 | Grapheme-aware terminal cell buffer, colors, styles and frame differ for conui |
| 2026-09-26 12:58:16 | [conui-input](https://crates.io/crates/conui-input) | 0.1.0 | 0 | Incremental terminal input parser: keys, mouse, bracketed paste and focus |
| 2026-09-26 12:58:17 | [conui-term](https://crates.io/crates/conui-term) | 0.1.0 | 0 | Raw mode, capability detection and a minimal-escape ANSI writer for conui |
| 2026-09-26 12:58:19 | [conui](https://crates.io/crates/conui) | 0.1.0 | 0 | A devkit for building console applications with a proper user interface |
| 2026-09-26 13:01:57 | [authz-details-rs](https://crates.io/crates/authz-details-rs) | 0.3.0 | 0 | RFC 9396 OAuth 2.0 Rich Authorization Requests evaluation engine |
| 2026-09-26 13:02:19 | [konomanoasa-tree-sitter-gitconfig](https://crates.io/crates/konomanoasa-tree-sitter-gitconfig) | 0.2.0 | 0 | Tree-sitter grammar for gitconfig. |
| 2026-09-26 13:16:51 | [konomanoasa-tree-sitter-gitattributes](https://crates.io/crates/konomanoasa-tree-sitter-gitattributes) | 0.1.0 | 0 | Tree-sitter grammar for gitattributes. |
| 2026-09-26 13:18:48 | [omgbase-reconcile](https://crates.io/crates/omgbase-reconcile) | 2.1.0 | 0 | omgbase reconciliation: keeps block identity across edits — the matcher that de… |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
