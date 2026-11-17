# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-11-17 16:19 UTC

New crates published between 2026-11-17 15:20 UTC and 2026-11-17 16:19 UTC.

[Full CSV](data/new-crates-2026-11-17T16-19-39-702696Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-11-17 15:23:47 | [slashbuilder-substrate-kit](https://crates.io/crates/slashbuilder-substrate-kit) | 0.1.0 | 0 | Linux and dockerd substrate for the SlashBuilder Kit ecosystem: container lifec… |
| 2026-11-17 15:25:02 | [nornir-mimir-node-map](https://crates.io/crates/nornir-mimir-node-map) | 0.1.0 | 0 | Shared node-map wire types and proof identifiers, without a decoder |
| 2026-11-17 15:25:03 | [nornir-mimir-libc](https://crates.io/crates/nornir-mimir-libc) | 0.1.0 | 0 | Mímir's model of a C run-time: one trait (LibcModel) with glibc, musl and Eyra… |
| 2026-11-17 15:28:01 | [moul-store](https://crates.io/crates/moul-store) | 0.0.1 | 0 | SQLite access for Moul: the shared, writer-only and device stores, system table… |
| 2026-11-17 15:29:48 | [karyos-cluster](https://crates.io/crates/karyos-cluster) | 0.1.0-alpha.3 | 0 | Consensus module, service container, snapshots and guards. |
| 2026-11-17 15:31:41 | [moul-rules](https://crates.io/crates/moul-rules) | 0.0.1 | 0 | Parser, SQL compiler and record evaluator for Moul's access-rule language. |
| 2026-11-17 15:32:02 | [moul-web](https://crates.io/crates/moul-web) | 0.0.1 | 0 | Browser host for the Moul engine: worker entry point, message protocol and tab… |
| 2026-11-17 15:32:13 | [moul-server](https://crates.io/crates/moul-server) | 0.0.1 | 0 | Native host for one Moul database: HTTP API, realtime, mail, jobs and MCP. |
| 2026-11-17 15:34:34 | [moul-hub](https://crates.io/crates/moul-hub) | 0.0.1 | 0 | Moul Hub: runs many Moul apps side by side, each in its own database, opened on… |
| 2026-11-17 15:38:57 | [clipdeck-core](https://crates.io/crates/clipdeck-core) | 2.1.2 | 0 | Clipboard history, pinboards and encrypted storage for ClipDeck |
| 2026-11-17 15:39:00 | [clipdeck-app](https://crates.io/crates/clipdeck-app) | 2.1.2 | 0 | Fast native clipboard manager with search, pinboards and paste stack |
| 2026-11-17 15:40:03 | [karyos](https://crates.io/crates/karyos) | 0.1.0-alpha.3 | 0 | Public facade: re-exports the client, Archive and Cluster APIs and defines kary… |
| 2026-11-17 15:49:53 | [slashbuilder-bitchain](https://crates.io/crates/slashbuilder-bitchain) | 0.2.0 | 0 | Content-addressed binary storage CLI for the SlashBuilder Kit ecosystem: format… |
| 2026-11-17 15:57:37 | [wasmnest-p2p-engine](https://crates.io/crates/wasmnest-p2p-engine) | 0.1.0 | 0 | WasmNest libp2p 机制引擎：节点身份桥（node_id↔PeerId）+ swarm 生命周期 + 入站准入闸门 + 流协议名注册表。默认形态… |
| 2026-11-17 15:57:55 | [wasmnest-cli-engine](https://crates.io/crates/wasmnest-cli-engine) | 0.0.1 | 0 | WasmNest CLI 能力域机制骨架：内建命令目录（词汇真源）+ argv 解析 + 帮助与补全 + 本机 IPC wire 帧契约。默认形态 = 纯机制… |
| 2026-11-17 15:58:50 | [egui-bevy](https://crates.io/crates/egui-bevy) | 0.0.1 | 0 | Integration between egui and Bevy |
| 2026-11-17 16:02:21 | [igris](https://crates.io/crates/igris) | 0.0.0 | 0 | Agent orchestration: a chat assistant hands coding work to agents in Herdr, a d… |
| 2026-11-17 16:03:00 | [h3wire-masque](https://crates.io/crates/h3wire-masque) | 0.1.0 | 0 | MASQUE CONNECT-UDP (RFC 9298) and the HTTP capsule codec (RFC 9297) over h3wire… |
| 2026-11-17 16:05:06 | [foom](https://crates.io/crates/foom) | 0.1.0 | 0 | foom |
| 2026-11-17 16:09:16 | [octoii-ai](https://crates.io/crates/octoii-ai) | 0.0.2 | 0 | Octoii's access to models: one vocabulary of conversations in and out, the cata… |
| 2026-11-17 16:11:42 | [mhtml](https://crates.io/crates/mhtml) | 0.4.0 | 0 | Convert Markdown to a beautiful, self-contained HTML page — preview in your bro… |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
