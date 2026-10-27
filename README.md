# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-10-27 07:20 UTC

New crates published between 2026-10-27 06:18 UTC and 2026-10-27 07:20 UTC.

[Full CSV](data/new-crates-2026-10-27T07-20-40-174464Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-10-27 06:26:19 | [ashlar-ui](https://crates.io/crates/ashlar-ui) | 0.1.0 | 0 | ashlar UI components: theme tokens, controls, layout, docking, icons |
| 2026-10-27 06:27:32 | [typed-fuse-core](https://crates.io/crates/typed-fuse-core) | 0.7.0 | 0 | Backend-neutral, node-tracking core for building FUSE filesystems |
| 2026-10-27 06:27:32 | [typed-fuse-sys](https://crates.io/crates/typed-fuse-sys) | 0.6.0 | 0 | Raw bindings to libfuse 3, used by typed-fuse (fork of libfuse-sys) |
| 2026-10-27 06:27:33 | [typed-fuse](https://crates.io/crates/typed-fuse) | 0.8.2 | 0 | High-level, safe Rust wrapper for building FUSE 3 filesystems |
| 2026-10-27 06:33:33 | [wasmnest-plugin-api-macros](https://crates.io/crates/wasmnest-plugin-api-macros) | 0.0.1 | 0 | WasmNest Plugin API proc macros — #[plugin_api] trait 生成 JSON-RPC 分派/客户端 + 构建期… |
| 2026-10-27 06:33:57 | [wasmnest-plugin-api](https://crates.io/crates/wasmnest-plugin-api) | 0.0.1 | 0 | WasmNest Plugin API — trait definitions and shared types for WasmNest plugins |
| 2026-10-27 06:34:38 | [wasmnest-contract](https://crates.io/crates/wasmnest-contract) | 0.0.1 | 0 | WasmNest 插件契约常量（包名 / 版本唯一手写真源）——零依赖，只装常量、不装 WIT |
| 2026-10-27 06:34:43 | [wasmnest-notify-engine](https://crates.io/crates/wasmnest-notify-engine) | 0.0.1 | 0 | WasmNest 通知域契约房（只持 WIT 契约，零实现）— 双端 host-notify 的唯一真源 |
| 2026-10-27 06:35:30 | [wasmnest-link-crypto](https://crates.io/crates/wasmnest-link-crypto) | 0.0.1 | 0 | WasmNest 局域网链路报文加密协议核心——桌面 server 与移动端 Rust 侧（event WS）共享，消除第三份实现 |
| 2026-10-27 06:36:20 | [wasmnest-host-api-core](https://crates.io/crates/wasmnest-host-api-core) | 0.0.1 | 0 | WasmNest host_api 共享实现核：无 WIT 依赖域的机制实现层（双端 wasm-core 各持 adapter） |
| 2026-10-27 06:36:39 | [ashlar-app](https://crates.io/crates/ashlar-app) | 0.1.0 | 0 | ashlar runtime: App builder, frame scheduler, crash guard, logging, telemetry,… |
| 2026-10-27 06:38:53 | [plana-evernight-client](https://crates.io/crates/plana-evernight-client) | 0.1.0 | 0 | Shared evernight broker dispatch client for the PoleMos terminal command routin… |
| 2026-10-27 06:39:56 | [openpaw-engine](https://crates.io/crates/openpaw-engine) | 0.1.0 | 0 | Agent loop: run_turn, three-phase tool execution, compaction, fallback (M2, sta… |
| 2026-10-27 06:40:48 | [openpaw-memory](https://crates.io/crates/openpaw-memory) | 0.1.0 | 0 | Memory and skills: nine memory types, spaced repetition, skill lifecycle (M3). |
| 2026-10-27 06:41:04 | [openpaw-reflect-lite](https://crates.io/crates/openpaw-reflect-lite) | 0.1.0 | 0 | Minimal reflection loop: trigger → single-shot reflect → persist unverified (M4… |
| 2026-10-27 06:41:38 | [olangc-ods](https://crates.io/crates/olangc-ods) | 1.0.0-rc.4 | 0 | ods — the numerical engine behind olang's data stack. Pure kernels, no olang de… |
| 2026-10-27 06:41:41 | [olangc](https://crates.io/crates/olangc) | 1.0.0-rc.4 | 0 | olang, a functional language for real work: pipelines, pattern matching and imm… |
| 2026-10-27 06:46:14 | [wasmnest-ws-client-engine](https://crates.io/crates/wasmnest-ws-client-engine) | 0.0.1 | 0 | WasmNest WS 出站连接能力域：主句柄表 + reader/writer 双任务 + 心跳 + 退避重连 + 帧信封 + 停用回收。默认形态 = 纯引… |
| 2026-10-27 06:46:55 | [ashlar-rs](https://crates.io/crates/ashlar-rs) | 0.1.0 | 0 | Build fast desktop and web apps in Rust: store, commands, UI, native, agent con… |
| 2026-10-27 06:50:12 | [zhandu](https://crates.io/crates/zhandu) | 0.1.1 | 0 | Fast terminal disk usage explorer with group and user accounting |
| 2026-10-27 06:50:32 | [skidbladnir-systemd](https://crates.io/crates/skidbladnir-systemd) | 0.1.0 | 0 | Skíðblaðnir's systemd lifecycle on its own: the backend-neutral ServiceSpec and… |
| 2026-10-27 06:56:13 | [wasmnest-host-kit](https://crates.io/crates/wasmnest-host-kit) | 0.0.1 | 0 | WasmNest 插件宿主机制内核：能力模块契约 + 插件实例状态 + 自动注册表（双端共享锚点） |
| 2026-10-27 06:57:09 | [ashlar-update](https://crates.io/crates/ashlar-update) | 0.1.0 | 0 | Update checks: an app's latest release from a releases API, semantic-version co… |
| 2026-10-27 07:01:03 | [solana-authority-scan](https://crates.io/crates/solana-authority-scan) | 0.1.0 | 0 | Who can change a Solana program, and how fast: upgrade authority, Squads v4 mul… |
| 2026-10-27 07:06:17 | [wasmnest-server-base](https://crates.io/crates/wasmnest-server-base) | 0.0.1 | 0 | WasmNest 桌面 server 基础层：错误/常量/错误边界/系统信息/网络配置形状/连接身份/端口 traits（server-lib-split 票… |
| 2026-10-27 07:16:33 | [wasmnest-crypto-engine](https://crates.io/crates/wasmnest-crypto-engine) | 0.0.1 | 0 | WasmNest 加密引擎：算法实现（x25519/aes_gcm/chacha/hkdf/rsa/hybrid）+ 名称寻址注册表（provider/reg… |
| 2026-10-27 07:17:35 | [gitop](https://crates.io/crates/gitop) | 0.1.0 | 0 | A real-time top-like terminal dashboard for git repositories with branch graph… |
| 2026-10-27 07:20:35 | [markdown-relink](https://crates.io/crates/markdown-relink) | 0.1.5 | 0 | Rename and move a note without breaking the vault: the inbound-wikilink rewrite… |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
