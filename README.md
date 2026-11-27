# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-11-27 05:18 UTC

New crates published between 2026-11-27 04:19 UTC and 2026-11-27 05:18 UTC.

[Full CSV](data/new-crates-2026-11-27T05-18-45-288738Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-11-27 04:24:58 | [zippa-db-tree-sitter](https://crates.io/crates/zippa-db-tree-sitter) | 0.1.1 | 0 | Tree-sitter SQL grammar for zippa-db: ANSI base plus MySQL, MariaDB, PostgreSQL… |
| 2026-11-27 04:33:39 | [tilolang-engine](https://crates.io/crates/tilolang-engine) | 0.5.1 | 0 | The device's work for tilolang apps: the engines a crate registers for its app,… |
| 2026-11-27 04:34:42 | [tilo-action-services](https://crates.io/crates/tilo-action-services) | 0.5.1 | 0 | The actions of the services a device and a workspace run: the apps and files it… |
| 2026-11-27 04:36:09 | [mancer-common](https://crates.io/crates/mancer-common) | 0.1.0 | 0 | Shared library for the `mancer` framework. |
| 2026-11-27 04:36:54 | [mancer-nyx](https://crates.io/crates/mancer-nyx) | 0.1.0 | 0 | Nyx proxy core implementation for the `mancer` framework. |
| 2026-11-27 04:37:06 | [mancer-rem](https://crates.io/crates/mancer-rem) | 0.1.0 | 0 | Rem engine core for the `mancer` framework. |
| 2026-11-27 04:37:33 | [mancer](https://crates.io/crates/mancer) | 0.1.0 | 0 | Entrypoint for the `mancer` framework. |
| 2026-11-27 04:46:54 | [efs-bill](https://crates.io/crates/efs-bill) | 0.1.0 | 0 | Offline estimate of AWS EFS Standard/IA GB-month cost from local JSON exports |
| 2026-11-27 04:48:10 | [octara-markdown](https://crates.io/crates/octara-markdown) | 0.0.5 | 0 | Streaming, selectable Markdown documents and replaceable block slots for Octara. |
| 2026-11-27 04:50:31 | [k8s-request-bill](https://crates.io/crates/k8s-request-bill) | 0.1.0 | 0 | Offline overprovisioning of Kubernetes requests vs usage from kubectl JSON |
| 2026-11-27 04:50:40 | [tilo-machine](https://crates.io/crates/tilo-machine) | 0.5.1 | 0 | What a session reaches of the computer it draws on, and where this computer's d… |
| 2026-11-27 04:53:42 | [cur-top](https://crates.io/crates/cur-top) | 1.0.0 | 0 | Offline top costs from an AWS CUR 2.0 CSV |
| 2026-11-27 04:55:47 | [gdb-remote](https://crates.io/crates/gdb-remote) | 0.1.0 | 0 | The GDB Remote Serial Protocol without I/O: framing and the packets of GDB and… |
| 2026-11-27 04:56:37 | [tsroute-macros](https://crates.io/crates/tsroute-macros) | 0.1.0 | 0 | Proc macros for tsroute |
| 2026-11-27 04:56:39 | [tsroute](https://crates.io/crates/tsroute) | 0.1.0 | 0 | Typed TypeScript + TanStack Query clients generated from your existing axum rou… |
| 2026-11-27 05:01:05 | [lattice-model-inkling2](https://crates.io/crates/lattice-model-inkling2) | 0.18.0 | 0 | Inkling 2 looped mixture-of-experts text decoder for Lattice, on the CPU |
| 2026-11-27 05:02:11 | [cli-exit-code](https://crates.io/crates/cli-exit-code) | 0.1.0 | 0 | clap-compatible exit codes (0 ok, 1 error, 2 usage). Not sysexits 64; for that… |
| 2026-11-27 05:02:49 | [cost-check](https://crates.io/crates/cost-check) | 0.1.0 | 0 | One offline Cost Check report for ci-bill, log-bill, dd-metric-bill and rum-met… |
| 2026-11-27 05:06:56 | [disk-full-doctor](https://crates.io/crates/disk-full-doctor) | 0.1.0 | 0 | Read-only report of why a disk looks full when df and du disagree |
| 2026-11-27 05:10:16 | [pgwal-doctor](https://crates.io/crates/pgwal-doctor) | 0.1.0 | 0 | Read-only report of why PostgreSQL's pg_wal keeps growing |
| 2026-11-27 05:12:43 | [termux-sync](https://crates.io/crates/termux-sync) | 2.0.0 | 0 | Back up and restore a Termux environment across devices |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
