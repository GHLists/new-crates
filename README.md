# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-10-11 07:19 UTC

New crates published between 2026-10-11 06:18 UTC and 2026-10-11 07:19 UTC.

[Full CSV](data/new-crates-2026-10-11T07-19-08-425Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-10-11 06:22:27 | [crashpack](https://crates.io/crates/crashpack) | 0.1.0 | 0 | Privacy-first local diagnostic crash bundles for Rust applications |
| 2026-10-11 06:24:59 | [ps-less-avc](https://crates.io/crates/ps-less-avc) | 0.1.5 | 0 | Fork of less-avc 0.1.5 for chuzz WebRTC: pure Rust H.264 encoding |
| 2026-10-11 06:25:03 | [ps-rusty-opus](https://crates.io/crates/ps-rusty-opus) | 1.0.0 | 0 | Synchronous fork of rusty-opus 1.0.0 for chuzz: pure-Rust Opus (RFC 6716) with… |
| 2026-10-11 06:36:07 | [cachec](https://crates.io/crates/cachec) | 0.1.0 | 0 | Ultra fast data structures for concurrency. |
| 2026-10-11 06:37:13 | [ggen-abb-sbb](https://crates.io/crates/ggen-abb-sbb) | 26.10.10 | 0 | IO-free ABB/SBB manufacture admission kernel: SELECT existing SBB \|\| MANUFACTUR… |
| 2026-10-11 06:41:51 | [ironkeys-pkcs11](https://crates.io/crates/ironkeys-pkcs11) | 0.1.0 | 0 | Native PKCS#11 boundary for IronKeys |
| 2026-10-11 06:41:53 | [ironkeys-cng](https://crates.io/crates/ironkeys-cng) | 0.1.0 | 0 | Minimal safe wrapper over Windows CNG and TPM Base Services for IronKeys |
| 2026-10-11 06:41:56 | [ironkeys-tpm2](https://crates.io/crates/ironkeys-tpm2) | 0.1.0 | 0 | A native TPM 2.0 layer in safe Rust for IronKeys: marshalling, sessions and com… |
| 2026-10-11 06:41:58 | [ironkeys-kms](https://crates.io/crates/ironkeys-kms) | 0.1.0 | 0 | An AWS KMS client in safe Rust for IronKeys: credentials, SigV4 and the key ope… |
| 2026-10-11 06:42:01 | [ironkeys](https://crates.io/crates/ironkeys) | 0.1.0 | 0 | Key custody for the IronSecurity stack: one interface over software, HSM, TPM a… |
| 2026-10-11 06:42:50 | [git-claw](https://crates.io/crates/git-claw) | 0.1.0 | 0 | Deterministic git worktree orchestration engine for developers and AI agents |
| 2026-10-11 06:43:37 | [metriken-storage](https://crates.io/crates/metriken-storage) | 0.1.0 | 0 | Storage for metriken recordings: the segment format, column readers, and the de… |
| 2026-10-11 06:44:59 | [modebox-core](https://crates.io/crates/modebox-core) | 0.1.0 | 0 | Run untrusted, agent-written JavaScript/TypeScript in a snapshot-able WebAssemb… |
| 2026-10-11 06:45:01 | [modebox](https://crates.io/crates/modebox) | 0.1.0 | 0 | Sandboxed code execution for AI agents: run agent-written JS/TS in WebAssembly,… |
| 2026-10-11 06:46:07 | [ascmhl](https://crates.io/crates/ascmhl) | 0.1.0 | 0 | Read and validate ASC Media Hash List (MHL) manifests: SHA-256, SHA-1 and MD5 r… |
| 2026-10-11 06:52:05 | [satx-core](https://crates.io/crates/satx-core) | 0.2.0 | 0 | The library behind satx: talks to HP 48 and 49 calculators over a serial cable… |
| 2026-10-11 06:52:24 | [satx](https://crates.io/crates/satx) | 0.2.0 | 0 | satx: transfer files between HP 48/49 calculators and a computer over serial |
| 2026-10-11 06:57:50 | [virtual-bus](https://crates.io/crates/virtual-bus) | 0.3.1 | 0 | Virtual I2C / SPI buses for running embedded-hal 1.0 drivers against IC models… |
| 2026-10-11 06:58:08 | [virtual-bus-build](https://crates.io/crates/virtual-bus-build) | 0.3.1 | 0 | build.rs helper that turns Verilog into a Verilator model usable from virtual-b… |
| 2026-10-11 06:59:23 | [ggen-engine](https://crates.io/crates/ggen-engine) | 26.10.11 | 0 | SPARQL-in-Tera code generation engine (vendored, renamed from praxis/crates/gge… |
| 2026-10-11 07:04:19 | [timecode-tools](https://crates.io/crates/timecode-tools) | 0.1.0 | 0 | Dependency-free SMPTE LTC (linear timecode) and MIDI Time Code readers, timecod… |
| 2026-10-11 07:09:35 | [tauri-plugin-microphone-kessdev](https://crates.io/crates/tauri-plugin-microphone-kessdev) | 0.1.1-beta.0 | 0 | Microphone plugin for Tauri v2: cross-platform audio recording, live metering a… |
| 2026-10-11 07:18:10 | [trclipboard](https://crates.io/crates/trclipboard) | 0.1.0 | 0 | Cross-platform (including web) clipboard access for Rust |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
