# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-09-30 02:20 UTC

New crates published between 2026-09-30 01:18 UTC and 2026-09-30 02:20 UTC.

[Full CSV](data/new-crates-2026-09-30T02-20-16-339436Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-09-30 01:27:17 | [kcode-k1-daemon-web-startup](https://crates.io/crates/kcode-k1-daemon-web-startup) | 0.1.0 | 0 | Open the K1 daemon's fixed Web HTTP router |
| 2026-09-30 01:28:59 | [emblema-text](https://crates.io/crates/emblema-text) | 0.0.1 | 0 | Reserved name for part of the emblema renderer. Glyph atlas packing and placeme… |
| 2026-09-30 01:30:26 | [benostream-gpu-ann](https://crates.io/crates/benostream-gpu-ann) | 0.1.0 | 0 | Universal GPU-accelerated vector indexing & ANN search for Rust (CUDA, Apple Me… |
| 2026-09-30 02:01:10 | [fast-feign-macros](https://crates.io/crates/fast-feign-macros) | 1.0.0 | 0 | fast-feign 声明式客户端过程宏：#[feign_client] 与 #[get]/#[post]/#[put]/#[delete] 方法宏 |
| 2026-09-30 02:01:12 | [feign-core](https://crates.io/crates/feign-core) | 1.0.0 | 0 | fast-feign 核心抽象：请求/响应模型、编解码、服务发现与负载均衡 trait、中间件抽象、配置模型 |
| 2026-09-30 02:01:13 | [feign-testkit](https://crates.io/crates/feign-testkit) | 1.0.0 | 0 | fast-feign 的测试支持库：可复用的极简 HTTP/1.1 mock 服务端 |
| 2026-09-30 02:01:18 | [feign-balancer](https://crates.io/crates/feign-balancer) | 1.0.0 | 0 | fast-feign 客户端负载均衡：轮询 / 随机 / 加权轮询 / P2C |
| 2026-09-30 02:01:20 | [feign-codec](https://crates.io/crates/feign-codec) | 1.0.0 | 0 | fast-feign 的扩展编解码器：MessagePack |
| 2026-09-30 02:02:11 | [polidog-jev](https://crates.io/crates/polidog-jev) | 0.1.0 | 0 | Unofficial, provider-neutral CLI for TypeSafe Jev |
| 2026-09-30 02:03:04 | [bhr](https://crates.io/crates/bhr) | 0.1.0 | 0 | Turn Chrome history into a per-day list of pages you read (CLI/TUI) |
| 2026-09-30 02:12:40 | [feign-auth](https://crates.io/crates/feign-auth) | 1.0.0 | 0 | fast-feign 认证能力：Bearer / Basic / ApiKey / JWT 透传与解析 |
| 2026-09-30 02:14:52 | [mhome-os-permissions](https://crates.io/crates/mhome-os-permissions) | 0.1.0 | 0 | In-process operating-system permission status, requests, and Settings links |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
