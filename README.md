# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-09-30 05:21 UTC

New crates published between 2026-09-30 04:18 UTC and 2026-09-30 05:21 UTC.

[Full CSV](data/new-crates-2026-09-30T05-21-55-802629Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-09-30 04:25:01 | [kcode-k1-rust-package-contract-tests](https://crates.io/crates/kcode-k1-rust-package-contract-tests) | 0.1.0 | 0 | Downstream conformance tests for kcode-k1-rust-package |
| 2026-09-30 04:26:43 | [glassworks-envelope](https://crates.io/crates/glassworks-envelope) | 0.2.0 | 0 | The bus wire envelope: typed events and commands, generated from schema/envelop… |
| 2026-09-30 04:33:57 | [qargo](https://crates.io/crates/qargo) | 0.1.1 | 0 | Local Qleisli qrate orchestration with standard lint, format, and documentation… |
| 2026-09-30 04:40:07 | [arcbox-vm-driver](https://crates.io/crates/arcbox-vm-driver) | 0.8.0 | 0 | The VM driver port: the vocabulary of a VM on this host — spec, driver/handle t… |
| 2026-09-30 04:40:07 | [arcbox-vm-proto](https://crates.io/crates/arcbox-vm-proto) | 0.8.0 | 0 | Wire vocabulary shared by the arcbox-computer-runtime sandbox manager and the i… |
| 2026-09-30 04:40:14 | [arcbox-fc-driver](https://crates.io/crates/arcbox-fc-driver) | 0.8.0 | 0 | The Firecracker adapter for the arcbox-vm-driver port: renders a VmSpec into Fi… |
| 2026-09-30 04:40:15 | [arcbox-local-ca](https://crates.io/crates/arcbox-local-ca) | 0.8.0 | 0 | The name-constrained local CA behind HTTPS for ArcBox container domains |
| 2026-09-30 04:40:17 | [arcbox-tap-net](https://crates.io/crates/arcbox-tap-net) | 0.8.0 | 0 | The Linux TAP guest network: address pool, TAP devices, identity-invariant NAT… |
| 2026-09-30 04:44:35 | [tau-tools](https://crates.io/crates/tau-tools) | 0.7.0 | 0 | Built-in native tools for the tau agent harness (read/write/edit/grep/find/ls/b… |
| 2026-09-30 04:47:07 | [arcbox-computer-runtime](https://crates.io/crates/arcbox-computer-runtime) | 0.8.0 | 0 | Sandbox orchestration over nested microVMs behind the arcbox-vm-driver port: bo… |
| 2026-09-30 04:57:08 | [arcbox-vm-agent](https://crates.io/crates/arcbox-vm-agent) | 0.8.0 | 0 | The vm-agent init that runs as PID 1 inside every ArcBox sandbox microVM: exec/… |
| 2026-09-30 04:59:53 | [orcher-proto](https://crates.io/crates/orcher-proto) | 0.1.0 | 0 | Protocol definitions for ORCHER orchestration platform |
| 2026-09-30 05:06:59 | [arcbox-ssh](https://crates.io/crates/arcbox-ssh) | 0.8.0 | 0 | The ArcBox SSH server: `ssh <machine>@arcbox` into Linux machines over the mach… |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
