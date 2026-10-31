# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-10-31 10:19 UTC

New crates published between 2026-10-31 09:19 UTC and 2026-10-31 10:19 UTC.

[Full CSV](data/new-crates-2026-10-31T10-19-30-772546Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-10-31 09:30:49 | [normalization-rs](https://crates.io/crates/normalization-rs) | 0.1.0 | 0 | Decimal-precision numeric normalization: z-score standardization, min-max scali… |
| 2026-10-31 09:42:23 | [vulkane-spirv-parse](https://crates.io/crates/vulkane-spirv-parse) | 0.19.0 | 0 | SPIR-V module model and reflection for Vulkane: decode a binary module, list en… |
| 2026-10-31 09:43:03 | [vulkane-spirv-emit](https://crates.io/crates/vulkane-spirv-emit) | 0.19.0 | 0 | The SPIR-V compute-shader emitter for Unpopped: IR to a binary SPIR-V module (G… |
| 2026-10-31 09:53:32 | [terraphim-meta-skill](https://crates.io/crates/terraphim-meta-skill) | 0.1.0 | 0 | Local-first skill management and routing with terraphim rolegraph search |
| 2026-10-31 09:58:50 | [rigorix-client](https://crates.io/crates/rigorix-client) | 0.9.0 | 0 | Protocol-only typed client for the frozen rigorix.* JSON-RPC catalog — governed… |
| 2026-10-31 10:00:17 | [keri-store-redb](https://crates.io/crates/keri-store-redb) | 0.1.0 | 0 | A keri-kel store on redb: key event logs, escrows and replies kept in an embedd… |
| 2026-10-31 10:00:18 | [keri-watch](https://crates.io/crates/keri-watch) | 0.1.0 | 0 | A KERI watcher's decisions as pure functions: when to poll, and which witnesses… |
| 2026-10-31 10:00:18 | [keri-watcher](https://crates.io/crates/keri-watcher) | 0.1.0 | 0 | A KERI watcher: keeps the key event logs it is sent and answers queries about t… |
| 2026-10-31 10:01:32 | [async-throttle-rs](https://crates.io/crates/async-throttle-rs) | 0.1.1 | 0 | Client side rate limiting |
| 2026-10-31 10:07:09 | [ontomark-jev](https://crates.io/crates/ontomark-jev) | 0.6.1 | 0 | Host-side Jev option for Ontomark assisted ingest: typed Choice/Noul decisions… |
| 2026-10-31 10:10:23 | [nordisk-heimdall-seccomp](https://crates.io/crates/nordisk-heimdall-seccomp) | 0.2.0 | 0 | Heimdall is a defensive sandbox: seccomp profile types per workload/arch/libc,… |
| 2026-10-31 10:10:29 | [nordisk-heimdall-probe](https://crates.io/crates/nordisk-heimdall-probe) | 0.2.0 | 0 | Heimdall is a defensive sandbox: the learning-mode tracer (seccomp USER_NOTIF l… |
| 2026-10-31 10:10:43 | [nordisk-heimdall-container](https://crates.io/crates/nordisk-heimdall-container) | 0.2.0 | 0 | Heimdall is a defensive sandbox: heimdall-container is the protected native Job… |
| 2026-10-31 10:11:13 | [wasm-transferable-macro](https://crates.io/crates/wasm-transferable-macro) | 0.1.1 | 0 | Internal proc-macro crate for wasm-transferable. Please use the main wasm-trans… |
| 2026-10-31 10:14:24 | [git-whoami](https://crates.io/crates/git-whoami) | 0.1.0 | 0 | Verify which Git identity (and git-persona persona) is active |
| 2026-10-31 10:15:43 | [wasm-transferable](https://crates.io/crates/wasm-transferable) | 0.1.1 | 0 | Serialize Rust structs into JsValue while collecting Transferable Objects |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
