# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-11-06 00:18 UTC

New crates published between 2026-11-05 23:21 UTC and 2026-11-06 00:18 UTC.

[Full CSV](data/new-crates-2026-11-06T00-18-45-992506Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-11-05 23:21:56 | [pidge-engine](https://crates.io/crates/pidge-engine) | 2.0.0 | 0 | pidge's engine: every mail and calendar operation, once, for the CLI and both M… |
| 2026-11-05 23:24:33 | [axa-seaorm](https://crates.io/crates/axa-seaorm) | 0.1.0 | 0 | SeaORM connections, migration helpers, and model errors for Axum services, with… |
| 2026-11-05 23:26:42 | [cinq](https://crates.io/crates/cinq) | 0.1.0 | 0 | Minimal cue-based show controller in the spirit of QLab |
| 2026-11-05 23:28:31 | [syntaqlite-capi](https://crates.io/crates/syntaqlite-capi) | 0.14.0 | 0 | C API for syntaqlite (libsyntaqlite) |
| 2026-11-05 23:29:35 | [achq-derive](https://crates.io/crates/achq-derive) | 0.1.0 | 0 | Derive macros for the achq crate (validation, redacted Debug and form encoding). |
| 2026-11-05 23:29:37 | [achq](https://crates.io/crates/achq) | 0.1.0 | 0 | A typed client for the ACHQ (SpeedChex) bank payments API, for native and WebAs… |
| 2026-11-05 23:30:13 | [corvus-event-schema](https://crates.io/crates/corvus-event-schema) | 0.1.0 | 0 | Corvus OCSF event schema and protobuf wire types |
| 2026-11-05 23:30:37 | [corvus-agent-sdk-contract](https://crates.io/crates/corvus-agent-sdk-contract) | 0.1.0 | 0 | Transport-neutral Corvus agent SDK contracts |
| 2026-11-05 23:31:04 | [corvus-agent-sdk-impl-grpc](https://crates.io/crates/corvus-agent-sdk-impl-grpc) | 0.1.0 | 0 | Corvus agent SDK gRPC transport implementation |
| 2026-11-05 23:31:21 | [corvus-agent-sdk](https://crates.io/crates/corvus-agent-sdk) | 0.1.1 | 0 | Public Corvus agent SDK facade for OCSF and OTLP submission |
| 2026-11-05 23:31:46 | [heartburn](https://crates.io/crates/heartburn) | 0.1.1 | 0 | The world's fastest CARDIAC emulator, as a library. |
| 2026-11-05 23:32:01 | [cardiac](https://crates.io/crates/cardiac) | 0.1.1 | 0 | Rust language package for cargo-cardiac. Install that, not this. |
| 2026-11-05 23:32:24 | [cardiaq](https://crates.io/crates/cardiaq) | 0.1.1 | 0 | The world's fastest CARDIAC emulator, with a debugger and an assembler. |
| 2026-11-05 23:32:55 | [cargo-cardiac](https://crates.io/crates/cargo-cardiac) | 0.1.1 | 0 | Compile Rust to CARDIAC, the 1968 Bell Labs cardboard computer. |
| 2026-11-05 23:40:32 | [mercury-agent-loop](https://crates.io/crates/mercury-agent-loop) | 4.12.30 | 0 | The agent loop of RFC-0011 for Mercury: the llm.run function runs model turns t… |
| 2026-11-05 23:41:21 | [tickgate](https://crates.io/crates/tickgate) | 0.1.2 | 0 | Deterministic sub-microsecond anomaly gate for market/RPC tick feeds — O(1) per… |
| 2026-11-05 23:41:33 | [tickgate-ffi](https://crates.io/crates/tickgate-ffi) | 0.1.2 | 0 | C ABI shim for tickgate — fixed symbol registry, one call per tick, fail-closed… |
| 2026-11-05 23:44:18 | [typedpg_lint](https://crates.io/crates/typedpg_lint) | 0.6.0 | 0 | SQL lint rules for typedpg queries, migrations and schema |
| 2026-11-05 23:45:31 | [graphblas-sys](https://crates.io/crates/graphblas-sys) | 0.1.0 | 0 | Raw FFI bindings to SuiteSparse:GraphBLAS (system libgraphblas, 7.4 API), our o… |
| 2026-11-05 23:45:33 | [nornir-mimir-graph](https://crates.io/crates/nornir-mimir-graph) | 0.1.0 | 0 | Mimir v2 graph engine: a small safe layer over SuiteSparse:GraphBLAS (via graph… |
| 2026-11-05 23:50:20 | [aureole-animation](https://crates.io/crates/aureole-animation) | 0.0.1-beta.1 | 0 | Aureole 的动画曲线与插值：弹簧、补间、关键帧，不依赖界面和渲染 |
| 2026-11-05 23:50:32 | [aureole-platform](https://crates.io/crates/aureole-platform) | 0.0.1-beta.1 | 0 | Aureole 的平台层：平台后端接口、帧时钟、系统集成（剪贴板、文件对话框、通知、外观）、单实例、本进程的资源用量 |
| 2026-11-05 23:50:37 | [aureole-reactive](https://crates.io/crates/aureole-reactive) | 0.0.1-beta.1 | 0 | Aureole 的细粒度响应式：信号、派生值、副作用、作用域 |
| 2026-11-05 23:50:42 | [aureole-scene](https://crates.io/crates/aureole-scene) | 0.0.1-beta.1 | 0 | Aureole 的场景数据：图元、显示列表、裁剪、分组、合成层的变换、颜色和图集更新，不依赖 GPU |
| 2026-11-05 23:51:03 | [aureole-core](https://crates.io/crates/aureole-core) | 0.0.1-beta.1 | 0 | Aureole 的核心：元素树、属性、样式对象、布局、文字和编辑、事件路由、焦点、浮层、无障碍树、绘制、动画，不依赖窗口和 GPU |
| 2026-11-05 23:55:37 | [kepler](https://crates.io/crates/kepler) | 0.0.0 | 0 | Symbolic regression engine: search, sessions, fitting, and run records |
| 2026-11-05 23:57:53 | [kepler-expr](https://crates.io/crates/kepler-expr) | 0.0.0 | 0 | Expression core of kepler: tape IR, evaluation, gradients, parse and print |
| 2026-11-05 23:57:58 | [kepler-cli](https://crates.io/crates/kepler-cli) | 0.0.0 | 0 | The kepler command: search, fit, check, explain, and serve the protocol and MCP |
| 2026-11-05 23:58:02 | [kepler-macros](https://crates.io/crates/kepler-macros) | 0.0.0 | 0 | Derive and expression macros for kepler |
| 2026-11-06 00:00:10 | [jlens-research](https://crates.io/crates/jlens-research) | 0.1.0 | 0 | Auditable CPU reference algorithms for Jacobian lens research |
| 2026-11-06 00:00:43 | [aureole-render](https://crates.io/crates/aureole-render) | 0.0.1-beta.1 | 0 | Aureole 的 GPU 渲染器：把场景数据画成像素，SDF 实例化图元，分组特效和离屏渲染 |
| 2026-11-06 00:02:26 | [kepler-gpu](https://crates.io/crates/kepler-gpu) | 0.0.0 | 0 | CubeCL evaluation backend for kepler |
| 2026-11-06 00:04:26 | [jacobian-lens](https://crates.io/crates/jacobian-lens) | 0.1.0 | 0 | Model-independent Jacobian lens fitting, decoding, and J-space interpretability |
| 2026-11-06 00:05:04 | [parano1d-mcp](https://crates.io/crates/parano1d-mcp) | 0.1.4 | 0 | MCP server for a local Parano1d node |
| 2026-11-06 00:06:19 | [maxicom](https://crates.io/crates/maxicom) | 0.1.0 | 0 | A fast, modern serial terminal (minicom alternative) built with Rust and Ratatui |
| 2026-11-06 00:06:44 | [game-toolkit-dosvideo](https://crates.io/crates/game-toolkit-dosvideo) | 0.1.0 | 0 | DOS-era PC graphics and sound for game-toolkit: VGA, Mode X, EGA, CGA, Hercules… |
| 2026-11-06 00:07:25 | [nornir-mimir-lens](https://crates.io/crates/nornir-mimir-lens) | 0.1.0 | 0 | Mimir lenses: the graph lenses over a Mimir v2 dump (gate-bypass, size, twins,… |
| 2026-11-06 00:10:46 | [aureole-controls](https://crates.io/crates/aureole-controls) | 0.0.1-beta.1 | 0 | Aureole 的基础控件：日期、时间、颜色、文件选择，按钮、复选框、单选组、开关、下拉选择、滑块、进度条、数字输入、标签，只用核心的公开 API 搭成 |
| 2026-11-06 00:12:24 | [kepler-types](https://crates.io/crates/kepler-types) | 0.0.0 | 0 | Wire types of kepler: events, commands, errors, format versions |
| 2026-11-06 00:16:55 | [asinus](https://crates.io/crates/asinus) | 0.1.0 | 0 | Terminal Color Theme Explorer |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
