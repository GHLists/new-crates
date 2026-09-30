# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-09-30 07:21 UTC

New crates published between 2026-09-30 06:19 UTC and 2026-09-30 07:21 UTC.

[Full CSV](data/new-crates-2026-09-30T07-21-43-365697Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-09-30 06:20:37 | [abnegate-vcs](https://crates.io/crates/abnegate-vcs) | 0.1.0 | 0 | Git operations over the git command line: branches, worktrees, merge-conflict r… |
| 2026-09-30 06:24:08 | [regain-transport](https://crates.io/crates/regain-transport) | 0.5.1 | 0 | Bounded serial I/O and USB recovery shared by vendor protocols |
| 2026-09-30 06:24:09 | [regain-worker](https://crates.io/crates/regain-worker) | 0.5.1 | 0 | Bounded JSON-line IPC shared by accessory workers |
| 2026-09-30 06:24:10 | [regain-core](https://crates.io/crates/regain-core) | 0.5.1 | 0 | Camera worker supervision and capture recovery for PulsarFab regain |
| 2026-09-30 06:24:10 | [regain-deepskydad](https://crates.io/crates/regain-deepskydad) | 0.5.1 | 0 | SDK-free Deep Sky Dad OFP2 flat panel protocol |
| 2026-09-30 06:24:11 | [regain-pegasus](https://crates.io/crates/regain-pegasus) | 0.5.1 | 0 | SDK-free Pegasus Astro FocusCube3 focuser protocol |
| 2026-09-30 06:28:23 | [regain-wanderer](https://crates.io/crates/regain-wanderer) | 0.5.1 | 0 | SDK-free Wanderer Astro ETA tilt and back-focus protocol |
| 2026-09-30 06:31:14 | [abnegate-agent-cli](https://crates.io/crates/abnegate-agent-cli) | 0.1.0 | 0 | Coding agent CLIs (Claude Code, Codex) driven as child processes behind the abn… |
| 2026-09-30 06:38:45 | [regain-zwo](https://crates.io/crates/regain-zwo) | 0.5.1 | 0 | ZWO camera, rotator, filter wheel and focuser protocols |
| 2026-09-30 06:42:08 | [abnegate-agent](https://crates.io/crates/abnegate-agent) | 0.1.0 | 0 | A ReAct agent loop with a sandbox-aware tool registry, background jobs, token-a… |
| 2026-09-30 06:42:59 | [flags-local](https://crates.io/crates/flags-local) | 1.0.0 | 0 | High-performance Rust client SDK for flags-local feature flag management |
| 2026-09-30 06:44:12 | [tc_dstu7624](https://crates.io/crates/tc_dstu7624) | 0.1.0 | 0 | DSTU 7624:2014 (Kalyna) block cipher with 128-, 256- and 512-bit blocks. |
| 2026-09-30 06:48:00 | [regain-device](https://crates.io/crates/regain-device) | 0.5.1 | 0 | Unified hardware worker and diagnostic CLI for PulsarFab regain |
| 2026-09-30 06:52:32 | [abnegate-comfy](https://crates.io/crates/abnegate-comfy) | 0.1.0 | 0 | ComfyUI image, video, and audio generation, model inventory, and LoRA training |
| 2026-09-30 06:55:57 | [taconite-qwen35](https://crates.io/crates/taconite-qwen35) | 0.1.0 | 0 | Qwen3.5-2B chat about text and images (hybrid Gated DeltaNet / attention LLM +… |
| 2026-09-30 06:58:26 | [regain-alpaca](https://crates.io/crates/regain-alpaca) | 0.5.1 | 0 | Alpaca server for cameras, rotators, filter wheels, focusers and flat panels, w… |
| 2026-09-30 06:59:12 | [ebctl](https://crates.io/crates/ebctl) | 0.1.0 | 0 | An Event Driven Framework - operator CLI for the event_base gRPC control plane |
| 2026-09-30 07:18:29 | [faucet-common-singer](https://crates.io/crates/faucet-common-singer) | 1.0.0 | 0 | Shared Singer protocol types (messages, encoding, redaction, private config fil… |
| 2026-09-30 07:18:51 | [faucet-sink-singer](https://crates.io/crates/faucet-sink-singer) | 1.0.0 | 0 | Singer target bridge sink for the faucet-stream ecosystem — run any Singer targ… |
| 2026-09-30 07:19:03 | [pinakes](https://crates.io/crates/pinakes) | 0.0.0 | 0 | A self-hosted knowledge service: an LLM-maintained wiki with fast, LLM-free rea… |
| 2026-09-30 07:20:33 | [lstm-shapecalc](https://crates.io/crates/lstm-shapecalc) | 0.1.0 | 0 | LSTM layer parameter-count and output-shape math matching PyTorch nn.LSTM |
| 2026-09-30 07:20:57 | [ai-mention-rs](https://crates.io/crates/ai-mention-rs) | 0.1.0 | 0 | Detect brand mentions and sentence-level citations in AI-generated answer text |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
