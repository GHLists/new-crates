# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-10-05 08:19 UTC

New crates published between 2026-10-05 07:20 UTC and 2026-10-05 08:19 UTC.

[Full CSV](data/new-crates-2026-10-05T08-19-51-310859Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-10-05 07:25:22 | [parsyng-fallback](https://crates.io/crates/parsyng-fallback) | 0.1.0 | 0 | A pure-Rust implementation of the `proc_macro` token types, used by `parsyng` o… |
| 2026-10-05 07:25:22 | [parsyng-proc-macros](https://crates.io/crates/parsyng-proc-macros) | 0.1.0 | 0 | Procedural macros used in `parsyng` |
| 2026-10-05 07:25:22 | [parsyng-quote-macros](https://crates.io/crates/parsyng-quote-macros) | 0.1.0 | 0 | Quote macros used in `parsyng` |
| 2026-10-05 07:32:41 | [parsyng-core](https://crates.io/crates/parsyng-core) | 0.1.0 | 0 | Core components of `parsyng` |
| 2026-10-05 07:32:43 | [parsyng](https://crates.io/crates/parsyng) | 0.1.1 | 0 | An easy-to-use, fast-compiling replacement for `syn` + `quote` for writing proc… |
| 2026-10-05 07:34:08 | [tc_chacha_aead](https://crates.io/crates/tc_chacha_aead) | 0.1.0 | 0 | ChaCha20-Poly1305 (RFC 8439) and XChaCha20-Poly1305 authenticated encryption, o… |
| 2026-10-05 07:47:16 | [mppi-provider](https://crates.io/crates/mppi-provider) | 0.1.0 | 0 | MPPI provider payment runtime, protocol services and integration interfaces |
| 2026-10-05 07:50:08 | [laser_tele](https://crates.io/crates/laser_tele) | 2.1.0 | 0 | Telegram Bot API library with async and blocking API: updates, messages, keyboa… |
| 2026-10-05 08:03:02 | [arachne-kv-seam](https://crates.io/crates/arachne-kv-seam) | 0.1.0 | 0 | Arachne seam: the leaf crate holding the core value types and the injectable se… |
| 2026-10-05 08:04:53 | [arachne-kv-transport-tonic](https://crates.io/crates/arachne-kv-transport-tonic) | 0.1.0 | 0 | Arachne tonic/rustls transport — the ONLY crate allowed to reference tonic/rust… |
| 2026-10-05 08:05:43 | [arachne-kv](https://crates.io/crates/arachne-kv) | 0.1.0 | 0 | Arachne: transport-agnostic product core (consensus, WAL storage, KV state mach… |
| 2026-10-05 08:16:01 | [multicriteria-dijkstra](https://crates.io/crates/multicriteria-dijkstra) | 0.1.0 | 0 | A generic multicriteria Dijkstra. |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
