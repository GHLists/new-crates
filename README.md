# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-09-30 03:18 UTC

New crates published between 2026-09-30 02:20 UTC and 2026-09-30 03:18 UTC.

[Full CSV](data/new-crates-2026-09-30T03-18-47-771206Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-09-30 02:20:23 | [ring_spsc](https://crates.io/crates/ring_spsc) | 0.1.0 | 0 | Single-producer single-consumer ring API |
| 2026-09-30 02:20:43 | [ring_mpsc](https://crates.io/crates/ring_mpsc) | 0.1.0 | 0 | Multi-producer single-consumer ring API |
| 2026-09-30 02:21:04 | [ring_core](https://crates.io/crates/ring_core) | 0.1.0 | 0 | Composed ring over an SPSC, MPSC, or crossbeam backend behind one surface |
| 2026-09-30 02:21:49 | [gluonscan-core](https://crates.io/crates/gluonscan-core) | 0.0.1-beta.1 | 0 | Core domain types and adapter ports for gluonscan: the read + normalize contrac… |
| 2026-09-30 02:21:57 | [gluonscan-testing](https://crates.io/crates/gluonscan-testing) | 0.0.1-beta.1 | 0 | Contract-based mock transports for gluonscan: replay recorded request/response… |
| 2026-09-30 02:22:02 | [gluonscan-math](https://crates.io/crates/gluonscan-math) | 0.0.1-beta.1 | 0 | Exact-integer DeFi math for gluonscan (Uniswap V3 Q64.96 tick math, etc.). No f… |
| 2026-09-30 02:22:10 | [gluonscan-evm](https://crates.io/crates/gluonscan-evm) | 0.0.1-beta.1 | 0 | EVM on-chain helpers for gluonscan: eth_call over an injected ChainProvider, mi… |
| 2026-09-30 02:22:20 | [gluonscan-solana](https://crates.io/crates/gluonscan-solana) | 0.0.1-beta.1 | 0 | Solana on-chain helpers for gluonscan: RPC over an injected ChainProvider, base… |
| 2026-09-30 02:22:50 | [feign-discovery](https://crates.io/crates/feign-discovery) | 1.0.0 | 0 | fast-feign 服务发现实现：静态配置 / 配置文件 / Nacos / Consul / etcd / Kubernetes |
| 2026-09-30 02:24:26 | [mori-cli](https://crates.io/crates/mori-cli) | 0.1.0 | 0 | mori — the git for cognition. Compile context with the Locus SDK and keep it in… |
| 2026-09-30 02:32:49 | [gluonscan-aave](https://crates.io/crates/gluonscan-aave) | 0.0.1-beta.1 | 0 | Aave V3 protocol adapter for gluonscan (HTTP API backend). |
| 2026-09-30 02:32:58 | [feign-elastic](https://crates.io/crates/feign-elastic) | 1.0.0 | 0 | fast-feign 弹性容错：超时 / 指数退避重试 / 熔断器 / 降级兜底 |
| 2026-09-30 02:39:21 | [nats-lens](https://crates.io/crates/nats-lens) | 0.1.2 | 0 | NATS JetStream delivery guarantee violation detector |
| 2026-09-30 02:43:06 | [feign-observability](https://crates.io/crates/feign-observability) | 1.0.0 | 0 | fast-feign 可观测性：W3C TraceContext 注入/提取、tracing 链路、OTLP 导出 |
| 2026-09-30 02:43:21 | [gluonscan-uniswap](https://crates.io/crates/gluonscan-uniswap) | 0.0.1-beta.1 | 0 | Uniswap V3 protocol adapter for gluonscan (subgraph discovery + on-chain uncoll… |
| 2026-09-30 02:45:14 | [crystal-lattice](https://crates.io/crates/crystal-lattice) | 0.1.0 | 0 | Crystallographic data structures with unit cells, Bravais lattices, Miller indi… |
| 2026-09-30 02:53:16 | [feign-transport-reqwest](https://crates.io/crates/feign-transport-reqwest) | 1.0.0 | 0 | fast-feign 的 reqwest 传输层实现 |
| 2026-09-30 02:53:55 | [gluonscan-pendle](https://crates.io/crates/gluonscan-pendle) | 0.0.1-beta.1 | 0 | Pendle protocol adapter for gluonscan (market catalog via HTTP + on-chain PT/YT… |
| 2026-09-30 03:02:13 | [wgsl-rs-ir](https://crates.io/crates/wgsl-rs-ir) | 0.1.0-beta.1 | 0 | The owned IR for the wgsl-rs transpiler: module, type, expression and statement… |
| 2026-09-30 03:03:19 | [const-bool](https://crates.io/crates/const-bool) | 0.1.0 | 0 | Type-level booleans to bypass 'where A::Flag == B::Flag' limitations in const g… |
| 2026-09-30 03:03:26 | [feign-governance](https://crates.io/crates/feign-governance) | 1.0.0 | 0 | fast-feign 治理能力：舱壁隔离、令牌桶限流、灰度标签路由、就近路由 |
| 2026-09-30 03:03:37 | [wgsl-rs-macros](https://crates.io/crates/wgsl-rs-macros) | 0.1.0-beta.1 | 0 | Procedural macro support for wgsl-rs: the #[wgsl] module macro. |
| 2026-09-30 03:04:12 | [wgsl-rs-layout-macros](https://crates.io/crates/wgsl-rs-layout-macros) | 0.1.0-beta.1 | 0 | Procedural macro support for wgsl-rs-layout: #[derive(Layout)]. |
| 2026-09-30 03:04:34 | [gluonscan-kamino](https://crates.io/crates/gluonscan-kamino) | 0.0.1-beta.1 | 0 | Kamino protocol adapter for gluonscan (Solana lending via the Kamino HTTP API). |
| 2026-09-30 03:07:15 | [wgsl-rs-layout](https://crates.io/crates/wgsl-rs-layout) | 0.1.0-beta.1 | 0 | WGSL memory layout for wgsl-rs: WgslLayout and #[derive(Layout)] so CPU structs… |
| 2026-09-30 03:13:37 | [feign-transport-hyper](https://crates.io/crates/feign-transport-hyper) | 1.0.0 | 0 | fast-feign 的 hyper 传输层实现（验证传输层可插拔：只支持明文 HTTP/1.1） |
| 2026-09-30 03:14:56 | [sidewinder-core](https://crates.io/crates/sidewinder-core) | 0.1.0 | 0 | Core of the Sidewinder sidechain library: the pipeline, authenticated store, th… |
| 2026-09-30 03:14:58 | [sidewinder-membership](https://crates.io/crates/sidewinder-membership) | 0.1.0 | 0 | Monotonic, node-free authorization for epic #240: a preloaded membership cache… |
| 2026-09-30 03:15:01 | [sidewinder-api](https://crates.io/crates/sidewinder-api) | 0.1.0 | 0 | The client-facing API for a Sidewinder node: the pipeline-backed Api implementa… |
| 2026-09-30 03:15:02 | [sidewinder-chain](https://crates.io/crates/sidewinder-chain) | 0.1.0 | 0 | Algorand parent-chain binding for Sidewinder (LocalNet in v0). |
| 2026-09-30 03:15:03 | [sidewinder-op](https://crates.io/crates/sidewinder-op) | 0.1.0 | 0 | Built-in Sidewinder operations, including the Slot reference operation. |
| 2026-09-30 03:15:07 | [gluonscan-raydium](https://crates.io/crates/gluonscan-raydium) | 0.0.1-beta.1 | 0 | Raydium CLMM protocol adapter for gluonscan (Solana on-chain position reads). |
| 2026-09-30 03:16:23 | [quilt-vm-wasm](https://crates.io/crates/quilt-vm-wasm) | 0.1.0 | 0 | Layer 1 of the polyformalism — the 5 opcodes (BIND/LINK/EFFECT/VIEW/TICK) as a… |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
