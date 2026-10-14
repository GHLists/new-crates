# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-10-14 04:19 UTC

New crates published between 2026-10-14 03:20 UTC and 2026-10-14 04:19 UTC.

[Full CSV](data/new-crates-2026-10-14T04-19-40-928825Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-10-14 03:26:44 | [footfall_analysis](https://crates.io/crates/footfall_analysis) | 0.1.0 | 0 | Spans, frames, and per-frame counter changes from Footfall snapshots, live or f… |
| 2026-10-14 03:37:02 | [footfall_session_wtransport](https://crates.io/crates/footfall_session_wtransport) | 0.1.0 | 0 | Serve Footfall sessions over local WebTransport, and discover, fetch, and subsc… |
| 2026-10-14 03:38:40 | [frc_autolog_macro](https://crates.io/crates/frc_autolog_macro) | 0.1.0 | 0 | Proc-macros for the robot-rust project. |
| 2026-10-14 03:43:13 | [xj_scanf_core](https://crates.io/crates/xj_scanf_core) | 0.1.0 | 0 | Shared byte-oriented C scanning format parser and destination requirements |
| 2026-10-14 03:47:14 | [footfall](https://crates.io/crates/footfall) | 0.1.0 | 0 | Low-overhead instrumentation with semantic attribution: one entry point for ins… |
| 2026-10-14 03:57:39 | [footfall_cli](https://crates.io/crates/footfall_cli) | 0.1.0 | 0 | The footfall command: record running sessions, watch them live, and ask why fra… |
| 2026-10-14 04:03:28 | [w1](https://crates.io/crates/w1) | 0.1.1 | 0 | Wrap7501: makes TUI coding agents (Codex, OpenCode, Gemini, Copilot, ...) repor… |
| 2026-10-14 04:05:57 | [raw-files](https://crates.io/crates/raw-files) | 0.1.0 | 0 | Pure-Rust camera RAW library: extracts embedded JPEG previews from Nikon NEF an… |
| 2026-10-14 04:09:48 | [ptal](https://crates.io/crates/ptal) | 0.1.0 | 0 | Terminal tool for reviewing a single throwaway text file: comment in a TUI, res… |
| 2026-10-14 04:13:09 | [h11types](https://crates.io/crates/h11types) | 0.0.1 | 0 | h11spec core types |
| 2026-10-14 04:14:29 | [blueprint-h11spec](https://crates.io/crates/blueprint-h11spec) | 0.0.1 | 0 | yaws h11spec blueprint |
| 2026-10-14 04:15:34 | [aegis-netguard-protocol](https://crates.io/crates/aegis-netguard-protocol) | 0.1.0-alpha.1 | 0 | Aegis wire protocol — the intent-only contract every crate depends on. |
| 2026-10-14 04:15:35 | [aegis-netguard-telemetry](https://crates.io/crates/aegis-netguard-telemetry) | 0.1.0-alpha.1 | 0 | Aegis telemetry: records guard verdicts as features for the anomaly detector (p… |
| 2026-10-14 04:15:38 | [aegis-netguard-client-sdk](https://crates.io/crates/aegis-netguard-client-sdk) | 0.1.0-alpha.1 | 0 | Aegis programmable bots — one honest driver plus one cheat per file — for exerc… |
| 2026-10-14 04:15:39 | [aegis-netguard-detector](https://crates.io/crates/aegis-netguard-detector) | 0.1.0-alpha.1 | 0 | Aegis anomaly detector (pillar C): reads the telemetry stream and flags players… |
| 2026-10-14 04:15:39 | [aegis-netguard-relay](https://crates.io/crates/aegis-netguard-relay) | 0.1.0-alpha.1 | 0 | Aegis relay: the only address clients ever see. Forwards to an origin whose add… |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
