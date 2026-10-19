# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-10-19 20:18 UTC

New crates published between 2026-10-19 19:21 UTC and 2026-10-19 20:18 UTC.

[Full CSV](data/new-crates-2026-10-19T20-18-55-781347Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-10-19 19:24:24 | [manguebyte-pro-io](https://crates.io/crates/manguebyte-pro-io) | 0.1.0 | 0 | ASIO driver support for the Manguebyte Audio Framework, under the GPLv3: a devi… |
| 2026-10-19 19:24:40 | [cwalk-sys](https://crates.io/crates/cwalk-sys) | 0.1.0 | 0 | Raw FFI bindings for the cwalk C path library |
| 2026-10-19 19:25:09 | [egui-frame-meter](https://crates.io/crates/egui-frame-meter) | 0.1.1 | 0 | A compact frame-time graph widget for egui |
| 2026-10-19 19:25:24 | [cwalk-rs](https://crates.io/crates/cwalk-rs) | 0.1.0 | 0 | Safe Rust bindings for the cwalk C path library |
| 2026-10-19 19:25:24 | [dimple](https://crates.io/crates/dimple) | 0.0.1 | 0 | Golf ball-flight physics: aerodynamics, RK4 trajectory, bounce, and rollout |
| 2026-10-19 19:26:07 | [forked-core](https://crates.io/crates/forked-core) | 0.1.0 | 0 | Versioned state for AI agents: fork, rewind and replay structured agent state.… |
| 2026-10-19 19:26:12 | [forked-api](https://crates.io/crates/forked-api) | 0.1.0 | 0 | HTTP API contract for forked: request/response types and a transport-agnostic d… |
| 2026-10-19 19:26:16 | [forked-memory](https://crates.io/crates/forked-memory) | 0.1.0 | 0 | In-memory storage adapter for forked: tests and local development. |
| 2026-10-19 19:26:21 | [forked-sqlite](https://crates.io/crates/forked-sqlite) | 0.1.0 | 0 | SQLite storage adapter for forked (rusqlite, bundled SQLite). |
| 2026-10-19 19:26:33 | [forked-server](https://crates.io/crates/forked-server) | 0.1.0 | 0 | Self-hostable HTTP server for forked: the same /v1 API as forked cloud, over SQ… |
| 2026-10-19 19:30:55 | [ze-node-schema](https://crates.io/crates/ze-node-schema) | 0.1.0 | 0 | Property model layer for ze-node-core (NodeSpec / Property / NodeRegistry / Dyn… |
| 2026-10-19 19:40:54 | [ze-graph-algo](https://crates.io/crates/ze-graph-algo) | 0.1.0 | 0 | Graph algorithms (topo sort, dirty propagation, SCC) for ze-node-core |
| 2026-10-19 19:50:54 | [ze-graph-eval](https://crates.io/crates/ze-graph-eval) | 0.1.0 | 0 | Evaluation strategies (lazy pull) for ze-node-core |
| 2026-10-19 19:54:13 | [testinfra](https://crates.io/crates/testinfra) | 0.1.0 | 0 | Testinfra-inspired infrastructure assertions for Linux and Docker |
| 2026-10-19 19:58:13 | [voicetel](https://crates.io/crates/voicetel) | 2.2.17 | 0 | Official Rust SDK for the VoiceTel REST API (v2.2.17). Provision numbers, place… |
| 2026-10-19 19:58:54 | [amont-agent-guard](https://crates.io/crates/amont-agent-guard) | 2.45.0 | 0 | amont-agent's guard: shell analysis, rules and stances for an agent's tool calls |
| 2026-10-19 19:59:04 | [amont-agent-process](https://crates.io/crates/amont-agent-process) | 2.45.0 | 0 | amont-agent's work process: plan review, implementation review, preview approva… |
| 2026-10-19 20:00:54 | [ze-node](https://crates.io/crates/ze-node) | 0.1.0 | 0 | zela 节点图统一入口：核心 trait + schema + 图算法 + 求值（不含 UI） |
| 2026-10-19 20:05:16 | [mise-lsp](https://crates.io/crates/mise-lsp) | 0.0.0 | 0 | Language server for mise config files (name reserved) |
| 2026-10-19 20:08:52 | [stampeded](https://crates.io/crates/stampeded) | 0.3.1 | 0 | A polyglot job processor on Postgres 18+: claim, execute, schedule, observe |
| 2026-10-19 20:09:19 | [symbiont-memory](https://crates.io/crates/symbiont-memory) | 0.45.0 | 0 | Optional memory across symbiont evolve calls: an archive of evaluated programs,… |
| 2026-10-19 20:10:54 | [zela](https://crates.io/crates/zela) | 0.1.0 | 0 | zela 统一入口：Pod 层 + 节点图基础层（ze-pod + ze-node） |
| 2026-10-19 20:11:24 | [gitenv](https://crates.io/crates/gitenv) | 0.1.0 | 0 | Terminal UI that keeps you on the right git identity for the repo you're in |
| 2026-10-19 20:17:24 | [madcat](https://crates.io/crates/madcat) | 0.1.0 | 0 | madcat — core binary. Memory, MCP, TTS, MQTT mesh, persona system. |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
