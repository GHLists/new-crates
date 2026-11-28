# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-11-28 08:19 UTC

New crates published between 2026-11-28 07:21 UTC and 2026-11-28 08:19 UTC.

[Full CSV](data/new-crates-2026-11-28T08-19-02-802763Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-11-28 07:25:40 | [grft-core](https://crates.io/crates/grft-core) | 0.1.0 | 0 | The git library behind grft. |
| 2026-11-28 07:25:43 | [grft](https://crates.io/crates/grft) | 0.1.0 | 0 | A git-compatible command line, built on the grft libraries. |
| 2026-11-28 07:26:55 | [brynja-legacy-hkdf](https://crates.io/crates/brynja-legacy-hkdf) | 0.1.0 | 0 | Explicit legacy-only HKDF-SHA-1 compatibility |
| 2026-11-28 07:28:35 | [brynja-cipher-chacha](https://crates.io/crates/brynja-cipher-chacha) | 0.1.0 | 0 | Portable no_std RFC 8439 ChaCha20 stream cipher for Brynja |
| 2026-11-28 07:29:26 | [brynja-cipher-aes](https://crates.io/crates/brynja-cipher-aes) | 0.1.0 | 0 | Opt-in no_std AES block cipher and explicit execution owners for Brynja |
| 2026-11-28 07:30:30 | [brynja-universal-hash-ghash](https://crates.io/crates/brynja-universal-hash-ghash) | 0.1.0 | 0 | Opt-in no_std GHASH over framed blocks for Brynja |
| 2026-11-28 07:31:39 | [xorevia-acme](https://crates.io/crates/xorevia-acme) | 0.0.1-alpha.1 | 0 | 自研 ACME 客户端：多 CA 厂商、DNS-01 / HTTP-01 / TLS-ALPN-01 / 自定义头验证、证书存储与续期 |
| 2026-11-28 07:31:54 | [xorevia-core](https://crates.io/crates/xorevia-core) | 0.0.1-alpha.1 | 0 | Xorevia 报文内核与跨层共享类型：HTTP/1.1 解析/序列化、错误模型、内部工具、连接上下文 |
| 2026-11-28 07:32:01 | [xorevia-regex](https://crates.io/crates/xorevia-regex) | 0.0.1-alpha.1 | 0 | 零依赖回溯式正则引擎：nginx 配置层用到的 PCRE 子集 |
| 2026-11-28 07:32:17 | [xorevia-cli](https://crates.io/crates/xorevia-cli) | 0.0.1-alpha.1 | 0 | Xorevia 统一包管理 CLI：add / update / remove / list 语言包、CA、DNS 适配器与 ACME 扩展 |
| 2026-11-28 07:32:31 | [xorevia-empty-gif](https://crates.io/crates/xorevia-empty-gif) | 0.0.1-alpha.1 | 0 | Xorevia 组件：1×1 透明 GIF 响应（Nginx ngx_http_empty_gif_module 的等价物） |
| 2026-11-28 07:32:54 | [tilo-action-calls](https://crates.io/crates/tilo-action-calls) | 0.5.3 | 0 | Answering action calls against a provider: serving each request a peer sends, h… |
| 2026-11-28 07:33:08 | [tilo-ui-app](https://crates.io/crates/tilo-ui-app) | 0.5.3 | 0 | The Tilo UI app runner: the App that drives a widget tree in a window, its head… |
| 2026-11-28 07:34:02 | [tilo-os-release](https://crates.io/crates/tilo-os-release) | 0.5.3 | 0 | The os-release format, read strictly: the shell-like assignments /etc/os-releas… |
| 2026-11-28 07:34:46 | [xorevia-h2](https://crates.io/crates/xorevia-h2) | 0.0.1-alpha.1 | 0 | Xorevia 的 HTTP/2 协议层（自研帧层与 HPACK 头部压缩，未接入门面，属进行中组件） |
| 2026-11-28 07:38:30 | [moatless-cli](https://crates.io/crates/moatless-cli) | 0.1.0 | 0 | Command-line interface for Moatless coding agents and sandboxes |
| 2026-11-28 07:41:51 | [brynja-aead-gcm](https://crates.io/crates/brynja-aead-gcm) | 0.1.0 | 0 | Opt-in no_std AES-GCM authenticated encryption and GMAC authentication |
| 2026-11-28 07:44:10 | [czarlib](https://crates.io/crates/czarlib) | 0.17.1 | 0 | C language bindings for zarlib |
| 2026-11-28 07:45:03 | [zarmcp](https://crates.io/crates/zarmcp) | 0.17.1 | 0 | Model Context Protocol server for ZAR archives |
| 2026-11-28 07:47:18 | [expanse-kv-core](https://crates.io/crates/expanse-kv-core) | 0.0.0 | 0 | RESP2/RESP3 wire codec and order-preserving key codecs for expanse-kv (no_std +… |
| 2026-11-28 07:47:39 | [expanse-kv-engine](https://crates.io/crates/expanse-kv-engine) | 0.0.0 | 0 | In-memory storage engine for expanse-kv on expanse-trie: typed operations, expi… |
| 2026-11-28 07:47:41 | [expanse-kv-persist](https://crates.io/crates/expanse-kv-persist) | 0.0.0 | 0 | Append-only log and snapshot persistence for expanse-kv |
| 2026-11-28 07:48:25 | [arks-config](https://crates.io/crates/arks-config) | 0.1.0 | 0 | Git config read-side: parse, merged precedence, identity |
| 2026-11-28 07:48:42 | [arks-hash](https://crates.io/crates/arks-hash) | 0.1.0 | 0 | In-engine Git object-format hashing (SHA-1-CD / SHA-256) |
| 2026-11-28 07:49:00 | [arks-hostfs](https://crates.io/crates/arks-hostfs) | 0.1.0 | 0 | Host FS honesty helpers — DriveFS / OneDrive CfAPI / sync-root detect (advisory) |
| 2026-11-28 07:49:00 | [xorevia-handler](https://crates.io/crates/xorevia-handler) | 0.0.1-alpha.1 | 0 | Xorevia 处理器层：Handler trait、impl_handler! 元组实现、ErasedHandler 与内置提取器 |
| 2026-11-28 07:49:17 | [arks-oid](https://crates.io/crates/arks-oid) | 0.1.0 | 0 | Git object ID (OID) newtype: parse, format, compare |
| 2026-11-28 07:49:34 | [arks-protocol](https://crates.io/crates/arks-protocol) | 0.1.0 | 0 | pkt-line framing and capability string helpers |
| 2026-11-28 07:51:08 | [arks-index](https://crates.io/crates/arks-index) | 0.1.0 | 0 | Git index file (gitformat-index) read/write for claimed versions |
| 2026-11-28 07:59:36 | [xorevia-middleware](https://crates.io/crates/xorevia-middleware) | 0.0.1-alpha.1 | 0 | Xorevia 中间件链内核：Middleware / Next / Endpoint / map_request\|map_response / middle… |
| 2026-11-28 08:00:48 | [arks-net](https://crates.io/crates/arks-net) | 0.1.0 | 0 | HTTPS client policy: operator CA trust anchors + proxy (shared by remote and hu… |
| 2026-11-28 08:06:10 | [rca](https://crates.io/crates/rca) | 0.0.1 | 0 | Rust Composable Architecture preview with owned state snapshots |
| 2026-11-28 08:06:12 | [rust-composable-architecture](https://crates.io/crates/rust-composable-architecture) | 0.0.1 | 0 | Re-exports the Rust Composable Architecture preview from rca |
| 2026-11-28 08:11:07 | [arks-object](https://crates.io/crates/arks-object) | 0.1.0 | 0 | Loose Git object encode/decode for claimed object kinds |
| 2026-11-28 08:11:26 | [xorevia-sse](https://crates.io/crates/xorevia-sse) | 0.0.1-alpha.1 | 0 | Xorevia 组件：Server-Sent Events（事件序列化 + 有界背压发送端） |
| 2026-11-28 08:16:49 | [html2feed](https://crates.io/crates/html2feed) | 0.1.0 | 0 | Turn any URL into an RSS feed |
| 2026-11-28 08:16:51 | [html2feed-cli](https://crates.io/crates/html2feed-cli) | 0.1.0 | 0 | Turn any URL into an RSS feed |
| 2026-11-28 08:17:36 | [funshell-core](https://crates.io/crates/funshell-core) | 0.1.0 | 0 | Core shell command execution, port/process discovery, and process termination e… |
| 2026-11-28 08:17:40 | [funshell](https://crates.io/crates/funshell) | 2.0.0 | 0 | Cross-platform shell execution and port/process query & kill CLI |
| 2026-11-28 08:17:43 | [funpub-core](https://crates.io/crates/funpub-core) | 0.1.0 | 0 | Core multi-channel artifact publishing engine for funpub |
| 2026-11-28 08:17:47 | [funpub](https://crates.io/crates/funpub) | 0.2.0 | 0 | Multi-channel artifact publishing CLI |
| 2026-11-28 08:17:50 | [funmirror-core](https://crates.io/crates/funmirror-core) | 0.1.0 | 0 | Async repository and release mirroring engine across GitHub, Gitee, GitLab, and… |
| 2026-11-28 08:18:51 | [funmirror](https://crates.io/crates/funmirror) | 0.7.0 | 0 | Mirror git repositories and releases between GitHub, Gitee, GitLab, and GitCode |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
