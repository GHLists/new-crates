# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-11-18 03:19 UTC

New crates published between 2026-11-18 02:21 UTC and 2026-11-18 03:19 UTC.

[Full CSV](data/new-crates-2026-11-18T03-19-31-579324Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-11-18 02:26:03 | [ignit_shader_engine](https://crates.io/crates/ignit_shader_engine) | 1.6.0 | 0 | Reusable WGSL nodes for engine rendering in Ignit |
| 2026-11-18 02:28:22 | [gadk-eval](https://crates.io/crates/gadk-eval) | 0.2.1 | 0 | Offline evaluation of gadk agents: eval sets, scorers and an LLM judge |
| 2026-11-18 02:36:08 | [ignit_shader_pbr](https://crates.io/crates/ignit_shader_pbr) | 1.6.0 | 0 | Reusable WGSL PBR nodes for Ignit |
| 2026-11-18 02:38:27 | [gadk-prompts-firestore](https://crates.io/crates/gadk-prompts-firestore) | 0.2.1 | 0 | Firestore store for gadk-prompts |
| 2026-11-18 02:46:07 | [ignit_importer_gltf](https://crates.io/crates/ignit_importer_gltf) | 1.6.0 | 0 | Asynchronous glTF 2.0 importer for Ignit |
| 2026-11-18 02:47:21 | [kombuse-describe](https://crates.io/crates/kombuse-describe) | 0.1.0 | 0 | A command-line tool says what its command line is: `<tool> describe --json` pri… |
| 2026-11-18 02:48:32 | [gadk-telemetry](https://crates.io/crates/gadk-telemetry) | 0.2.1 | 0 | OpenTelemetry tracing, metrics and logs for gadk, with Google Cloud export |
| 2026-11-18 02:52:52 | [kombuse-microvm-guest](https://crates.io/crates/kombuse-microvm-guest) | 0.1.0 | 0 | The guest side of microvm: the job and status a run passes to its init (microvm… |
| 2026-11-18 02:52:58 | [kombuse-microvm-krun-worker](https://crates.io/crates/kombuse-microvm-krun-worker) | 0.1.0 | 0 | The process that runs one libkrun VM: it loads the pinned library, confines its… |
| 2026-11-18 02:53:09 | [kombuse-microvm](https://crates.io/crates/kombuse-microvm) | 0.1.0 | 0 | One command in a fresh microVM, on Firecracker or libkrun, chosen explicitly be… |
| 2026-11-18 02:53:18 | [kombuse-room](https://crates.io/crates/kombuse-room) | 0.1.0 | 0 | Environments for persistent microVM workspaces: definitions from devcontainer.j… |
| 2026-11-18 02:53:53 | [meshdiet-core](https://crates.io/crates/meshdiet-core) | 0.1.0 | 0 | Engine behind meshdiet: reads GLB and glTF files and reports what makes them he… |
| 2026-11-18 02:54:03 | [meshdiet](https://crates.io/crates/meshdiet) | 0.1.0 | 0 | Find the 3D models that make your website slow: audits GLB and glTF weight. |
| 2026-11-18 02:55:06 | [meister](https://crates.io/crates/meister) | 0.5.0 | 0 | Qompass SFW game maker MCP: authoring and project state for SFW games, with a l… |
| 2026-11-18 02:55:19 | [tackle-mcp](https://crates.io/crates/tackle-mcp) | 0.3.0 | 0 | Tackle - live game-editor broker as an MCP stdio server (U1 read core, U2 write… |
| 2026-11-18 02:56:37 | [lumen-mcp](https://crates.io/crates/lumen-mcp) | 2.0.2 | 0 | Lux in motu - cross-platform, cross-media deterministic conversion engine: 2D a… |
| 2026-11-18 02:57:15 | [phlow-mcp](https://crates.io/crates/phlow-mcp) | 1.0.1 | 0 | Newline-delimited JSON-RPC (MCP) server for the phlow agent runtime |
| 2026-11-18 02:57:55 | [skills-mgr](https://crates.io/crates/skills-mgr) | 0.1.0 | 0 | Read the skills-mgr catalog and skill files from Rust without subprocesses |
| 2026-11-18 02:58:38 | [gadk-vertexai](https://crates.io/crates/gadk-vertexai) | 0.2.1 | 0 | Vertex AI Agent Engine session, memory and Example Store services for gadk |
| 2026-11-18 02:58:54 | [gradus](https://crates.io/crates/gradus) | 0.0.0 | 0 | A fast, native build tool for the JVM. |
| 2026-11-18 02:59:03 | [osprey-core](https://crates.io/crates/osprey-core) | 0.1.0 | 0 | Core 64-byte aligned binary formats (.osi, .osv, .osr), FWHT, 1-Bit SuperKMeans… |
| 2026-11-18 02:59:37 | [osprey-simd](https://crates.io/crates/osprey-simd) | 0.1.0 | 0 | Runtime-dispatched SIMD kernels (AVX-512 VPOPCNTDQ/BW, AVX2, ARM64 NEON, scalar… |
| 2026-11-18 03:00:18 | [osprey-storage](https://crates.io/crates/osprey-storage) | 0.1.0 | 0 | Zero-copy memmap2 readers, TSP locality ordering, WaRP DP request coalescing, Z… |
| 2026-11-18 03:00:51 | [osprey-cli](https://crates.io/crates/osprey-cli) | 0.1.0 | 0 | OspreyDB 100% CLI binary for deterministic Parquet/JSONL ingestion, S3Vec vecto… |
| 2026-11-18 03:02:29 | [clauset](https://crates.io/crates/clauset) | 0.3.0 | 0 | Several Claude Code accounts on one Mac, sharing one ~/.claude |
| 2026-11-18 03:05:37 | [sealwax-compose](https://crates.io/crates/sealwax-compose) | 0.4.0 | 0 | PDF documents written from laid-out pages: glyphs, paths, pictures and links. |
| 2026-11-18 03:07:38 | [enigma-mcp](https://crates.io/crates/enigma-mcp) | 1.3.1 | 0 | Enigma MCP: memory server for an Obsidian vault |
| 2026-11-18 03:08:43 | [gadk-agentregistry](https://crates.io/crates/gadk-agentregistry) | 0.2.1 | 0 | Client for the Google Cloud Agent Registry (A2A agents, MCP servers and models)… |
| 2026-11-18 03:09:30 | [aws-s3-transfer](https://crates.io/crates/aws-s3-transfer) | 0.0.1 | 0 | Placeholder for Transfer Manager for Amazon S3 |
| 2026-11-18 03:09:37 | [aws-s3-transfer-ext](https://crates.io/crates/aws-s3-transfer-ext) | 0.0.1 | 0 | Placeholder for extensions to Transfer Manager for Amazon S3 |
| 2026-11-18 03:18:48 | [gadk-cli](https://crates.io/crates/gadk-cli) | 0.2.1 | 0 | The gadk deploy CLI: deploy gadk agents to Cloud Run and Vertex AI Agent Engine |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
