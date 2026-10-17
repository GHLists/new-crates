# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-10-17 03:19 UTC

New crates published between 2026-10-17 02:18 UTC and 2026-10-17 03:19 UTC.

[Full CSV](data/new-crates-2026-10-17T03-19-33-881069Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-10-17 02:21:30 | [bmux_plugin_runtime](https://crates.io/crates/bmux_plugin_runtime) | 0.0.1-alpha.3 | 0 | Host-owned plugin runtime primitives for bmux |
| 2026-10-17 02:21:43 | [bmux_application_resurrection_plugin_api](https://crates.io/crates/bmux_application_resurrection_plugin_api) | 0.0.1-alpha.3 | 0 | Application resurrection host contracts |
| 2026-10-17 02:23:17 | [mycelium-agent-core](https://crates.io/crates/mycelium-agent-core) | 1.0.0 | 0 | mycelium 领域内核：消息、工具协议、事件、运行状态机、错误体系与配置 |
| 2026-10-17 02:23:25 | [mycelium-agent-macros](https://crates.io/crates/mycelium-agent-macros) | 1.0.0 | 0 | mycelium 过程宏：#[tool] 由普通函数生成 Tool 实现与 JSON Schema |
| 2026-10-17 02:23:35 | [mycelium-agent-model](https://crates.io/crates/mycelium-agent-model) | 1.0.0 | 0 | mycelium 模型提供方抽象（SPI）：ModelProvider trait、请求、流式增量与能力声明 |
| 2026-10-17 02:23:46 | [mycelium-agent-tools](https://crates.io/crates/mycelium-agent-tools) | 1.0.0 | 0 | mycelium 工具抽象（SPI）与注册表：Tool trait、执行上下文、ToolOutput 与 ToolRegistry |
| 2026-10-17 02:24:07 | [mycelium-agent-mcp](https://crates.io/crates/mycelium-agent-mcp) | 1.0.0 | 0 | mycelium 的 MCP（Model Context Protocol）客户端适配：stdio JSON-RPC、tools/list 与 tools/c… |
| 2026-10-17 02:24:31 | [katakuri](https://crates.io/crates/katakuri) | 0.1.0 | 0 | Model ecosystem layer over Zunesha — safetensors weight loading, WordPiece toke… |
| 2026-10-17 02:25:47 | [mycelium-agent-runtime](https://crates.io/crates/mycelium-agent-runtime) | 1.0.0 | 0 | mycelium 执行引擎：AgentRuntime 装配、会话与运行钩子（执行循环自 v0.2 起实现） |
| 2026-10-17 02:26:13 | [mlc-alert-daemon](https://crates.io/crates/mlc-alert-daemon) | 0.1.0 | 0 | Server-side price-alert evaluation and Telegram delivery. |
| 2026-10-17 02:32:57 | [bmux_application_resurrection_plugin](https://crates.io/crates/bmux_application_resurrection_plugin) | 0.0.1-alpha.3 | 0 | Application resurrection host adapter |
| 2026-10-17 02:33:36 | [mycelium-agent-provider-openai](https://crates.io/crates/mycelium-agent-provider-openai) | 1.0.0 | 0 | mycelium 的 OpenAI 兼容 Provider 实现（Chat Completions，流式 SSE） |
| 2026-10-17 02:34:56 | [bmux_broadcast_plugin_api](https://crates.io/crates/bmux_broadcast_plugin_api) | 0.0.1-alpha.3 | 0 | Typed output-only live broadcast contracts |
| 2026-10-17 02:35:10 | [bmux_presentation_state](https://crates.io/crates/bmux_presentation_state) | 0.0.1-alpha.3 | 0 | Neutral bounded semantic presentation fact primitives and retained registry |
| 2026-10-17 02:35:36 | [bmux_web_renderer](https://crates.io/crates/bmux_web_renderer) | 0.0.1-alpha.3 | 0 | Backend-neutral browser presentation of retained bmux TUI output |
| 2026-10-17 02:36:27 | [mylittlechart-server](https://crates.io/crates/mylittlechart-server) | 0.1.0 | 0 | Account, OAuth, update, and telemetry server for a mylittlechart deployment. |
| 2026-10-17 02:37:36 | [bmux_broadcast_plugin](https://crates.io/crates/bmux_broadcast_plugin) | 0.0.1-alpha.3 | 0 | Persistent plugin-owned output-only live broadcast publisher |
| 2026-10-17 02:40:46 | [mise-daemons](https://crates.io/crates/mise-daemons) | 0.0.0 | 0 | Daemon declarations, ports, presets, and runtime for mise (placeholder) |
| 2026-10-17 02:41:41 | [darktable-import-xmp](https://crates.io/crates/darktable-import-xmp) | 0.2.0 | 0 | Import loose XMP sidecar files into Darktable's library database |
| 2026-10-17 02:43:37 | [mycelium-agent](https://crates.io/crates/mycelium-agent) | 1.0.0 | 0 | mycelium agent SDK 门面：统一 re-export、prelude 与端到端示例 |
| 2026-10-17 02:44:57 | [avif-image-buffer](https://crates.io/crates/avif-image-buffer) | 0.1.0 | 0 | Codec-independent checked integer image buffers and immutable views |
| 2026-10-17 02:46:10 | [mlc-warden](https://crates.io/crates/mlc-warden) | 0.1.0 | 0 | eBPF LSM daemon that confines one protected process. |
| 2026-10-17 02:47:37 | [bmux_cluster_plugin_api](https://crates.io/crates/bmux_cluster_plugin_api) | 0.0.1-alpha.3 | 0 | Typed public API of the bmux cluster plugin (BPDL-generated bindings) |
| 2026-10-17 02:49:58 | [verbs](https://crates.io/crates/verbs) | 0.1.0 | 0 | Explicit, named constraints for more verifiable agent-written code |
| 2026-10-17 02:57:33 | [bmux_connections_plugin_api](https://crates.io/crates/bmux_connections_plugin_api) | 0.0.1-alpha.3 | 0 | Typed public API of the bmux connections plugin (BPDL-generated bindings) |
| 2026-10-17 02:58:47 | [cortexkit-anthropic-policy](https://crates.io/crates/cortexkit-anthropic-policy) | 0.1.0 | 0 | Anthropic authentication headers, beta tokens, account limits, credits, and quo… |
| 2026-10-17 03:04:56 | [funbuild-core](https://crates.io/crates/funbuild-core) | 0.1.0 | 0 | funbuild 的发版流程实现：构建类型探测、版本清单读写、命令编排 |
| 2026-10-17 03:05:11 | [funbuild](https://crates.io/crates/funbuild) | 1.6.104 | 0 | Python / 前端 / Flutter / Rust 仓库的一键发版工具 |
| 2026-10-17 03:09:03 | [lena-protocol](https://crates.io/crates/lena-protocol) | 0.1.1 | 0 | A code-to-graph Swiss Army knife for interactive docs, call traces, and LLM con… |
| 2026-10-17 03:09:57 | [pharmaobservatory](https://crates.io/crates/pharmaobservatory) | 0.1.1 | 0 | Rust client for the Pharma Observatory public REST API (https://pharmaobservato… |
| 2026-10-17 03:10:24 | [bmux_cluster_plugin_client](https://crates.io/crates/bmux_cluster_plugin_client) | 0.0.1-alpha.3 | 0 | Client-side native attach adapter for the bmux cluster plugin |
| 2026-10-17 03:13:13 | [lena-core](https://crates.io/crates/lena-core) | 0.1.1 | 0 | A code-to-graph Swiss Army knife for interactive docs, call traces, and LLM con… |
| 2026-10-17 03:15:01 | [lena](https://crates.io/crates/lena) | 0.1.1 | 0 | A code-to-graph Swiss Army knife for interactive docs, call traces, and LLM con… |
| 2026-10-17 03:17:33 | [bmux_connections_plugin](https://crates.io/crates/bmux_connections_plugin) | 0.0.1-alpha.3 | 0 | Bundled endpoint resolution and remote typed-service plugin for bmux |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
