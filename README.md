# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-11-21 08:20 UTC

New crates published between 2026-11-21 07:19 UTC and 2026-11-21 08:20 UTC.

[Full CSV](data/new-crates-2026-11-21T08-20-50-875239Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-11-21 07:19:53 | [mc683xx-bdm-proto](https://crates.io/crates/mc683xx-bdm-proto) | 0.1.0 | 0 | The mc683xx BDM pod's protocol: CPU32 BDM command sequences and the pod's USB r… |
| 2026-11-21 07:20:05 | [mc683xx-bdm](https://crates.io/crates/mc683xx-bdm) | 0.1.0 | 0 | The host side of the mc683xx BDM pod, a USB debugger for CPU32 (683xx) microcon… |
| 2026-11-21 07:22:56 | [bitcoinleveldbt-issue44](https://crates.io/crates/bitcoinleveldbt-issue44) | 0.2.0 | 0 | Level-zero compaction regressions for upstream LevelDB issue 44. |
| 2026-11-21 07:29:04 | [rust-webx-auth-ef](https://crates.io/crates/rust-webx-auth-ef) | 2.5.0 | 0 | rust-ef-backed durable refresh-token and browser-session stores for rust-webx |
| 2026-11-21 07:30:06 | [rust-webx-mfa](https://crates.io/crates/rust-webx-mfa) | 2.5.0 | 0 | TOTP and recovery-code multi-factor authentication for rust-webx |
| 2026-11-21 07:30:23 | [rust-webx-webauthn](https://crates.io/crates/rust-webx-webauthn) | 2.5.0 | 0 | WebAuthn/Passkey relying-party verification for rust-webx services |
| 2026-11-21 07:32:57 | [bitcoinleveldbt-issue474](https://crates.io/crates/bitcoinleveldbt-issue474) | 0.2.0 | 0 | Logging/flush regression for upstream LevelDB issue 474. |
| 2026-11-21 07:34:58 | [rust-webx-oauth2](https://crates.io/crates/rust-webx-oauth2) | 2.5.0 | 0 | OAuth 2.0 social-login client for rust-webx with provider presets (GitHub, Goog… |
| 2026-11-21 07:35:23 | [vusl-coverage](https://crates.io/crates/vusl-coverage) | 0.1.0-dev.1 | 0 | Caller-selected required term coverage for checked VUSL mapping reviews |
| 2026-11-21 07:35:32 | [rust-webx-oidc](https://crates.io/crates/rust-webx-oidc) | 2.5.0 | 0 | OpenID Connect client for rust-webx: discovery, PKCE, id_token validation and s… |
| 2026-11-21 07:39:09 | [kelir](https://crates.io/crates/kelir) | 0.1.0 | 0 | A small, steerable coding-agent harness |
| 2026-11-21 07:39:27 | [rust-webx-redis](https://crates.io/crates/rust-webx-redis) | 2.5.0 | 0 | Redis distributed cache and event transport for rust-webx (ASP.NET Core style a… |
| 2026-11-21 07:42:57 | [bitcoinleveldbt-mt](https://crates.io/crates/bitcoinleveldbt-mt) | 0.2.0 | 0 | Multithreaded database read/write regression across fixture option configuratio… |
| 2026-11-21 07:46:59 | [rust-webx-nats](https://crates.io/crates/rust-webx-nats) | 2.5.0 | 0 | NATS event transport for rust-webx (ASP.NET Core style add_nats) |
| 2026-11-21 07:48:41 | [oyta-content](https://crates.io/crates/oyta-content) | 0.1.0 | 0 | oyta-frame 内容分析层：原始输入 → 领域权重分布。内置 RuleBased / TFIDF / Hybrid 三种分析器，支持自定义 Domain… |
| 2026-11-21 07:48:45 | [oyta-autograd](https://crates.io/crates/oyta-autograd) | 0.1.0 | 0 | oyta-frame 自动微分引擎：Node 带 domain_id 的稀疏计算图，Op 17+ 变体（含 Conv1dMasked / BatchNorm1… |
| 2026-11-21 07:48:51 | [oyta-loss](https://crates.io/crates/oyta-loss) | 0.1.0 | 0 | oyta-frame 损失函数层：CrossEntropyLoss（label_smoothing）、MSELoss、MultiDomainLoss 按 ac… |
| 2026-11-21 07:49:12 | [oyta-router](https://crates.io/crates/oyta-router) | 0.1.0 | 0 | oyta-frame 稀疏路由 + 参数池层：TopK / Threshold 路由策略，SparseParameterPool 按领域独立维护参数，三层稀疏… |
| 2026-11-21 07:52:40 | [oyta-optim](https://crates.io/crates/oyta-optim) | 0.1.0 | 0 | oyta-frame 优化器 + 调度器层：SparseAdam / SparseSGD 按领域独立维护 HashMap<u32, DomainState>（… |
| 2026-11-21 07:52:57 | [bitcoinleveldbt-snapshot](https://crates.io/crates/bitcoinleveldbt-snapshot) | 0.2.0 | 0 | Snapshot behavior, lifetime and dispatch regressions for the LevelDB port. |
| 2026-11-21 07:56:54 | [condo-quote-units](https://crates.io/crates/condo-quote-units) | 1.0.0 | 0 | Exact numeric and evidence boundaries for condominium sale and rental quotes. |
| 2026-11-21 07:58:24 | [oyta-serialize](https://crates.io/crates/oyta-serialize) | 0.1.0 | 0 | oyta-frame safetensors v0 格式稀疏序列化：手写完整二进制格式（8 bytes header_len + JSON 8 字节对齐 +… |
| 2026-11-21 07:59:28 | [rust-webx-rabbitmq](https://crates.io/crates/rust-webx-rabbitmq) | 2.5.0 | 0 | RabbitMQ (AMQP) event transport for rust-webx (ASP.NET Core style add_rabbitmq) |
| 2026-11-21 08:00:18 | [backout](https://crates.io/crates/backout) | 0.1.0 | 0 | Run async steps with retries and exponential backoff, undoing completed steps i… |
| 2026-11-21 08:01:23 | [razer-headset](https://crates.io/crates/razer-headset) | 0.1.0 | 0 | Command-line control for the Razer BlackShark V2 HyperSpeed headset on Linux |
| 2026-11-21 08:02:57 | [bitcoinleveldbt-sparsemerge](https://crates.io/crates/bitcoinleveldbt-sparsemerge) | 0.2.0 | 0 | Sparse-merge compaction and environment-borrow regressions. |
| 2026-11-21 08:08:05 | [oyta-expert](https://crates.io/crates/oyta-expert) | 0.1.0 | 0 | oyta-frame 专家模块层：MLP / CNN1D / RNN / Transformer 四种专家，ExpertExecutor 框架层 contin… |
| 2026-11-21 08:10:47 | [rust-webx-kafka](https://crates.io/crates/rust-webx-kafka) | 2.5.0 | 0 | Kafka event transport for rust-webx (ASP.NET Core style add_kafka) |
| 2026-11-21 08:15:57 | [bitcoinleveldbt-randomized](https://crates.io/crates/bitcoinleveldbt-randomized) | 0.2.0 | 0 | Deterministic randomized, replay and failure-prefix regressions for the LevelDB… |
| 2026-11-21 08:16:03 | [repose-ui-test](https://crates.io/crates/repose-ui-test) | 0.35.0 | 0 | Deterministic UI testing harness for Repose |
| 2026-11-21 08:19:40 | [nifly-sys](https://crates.io/crates/nifly-sys) | 0.1.0 | 0 | Raw cxx bindings to the nifly C++ NIF library, built from source |
| 2026-11-21 08:19:43 | [nifly](https://crates.io/crates/nifly) | 0.1.0 | 0 | Read, edit and write NIF files from Bethesda's games, Morrowind to Starfield |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
