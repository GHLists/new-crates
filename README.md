# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-09-28 23:20 UTC

New crates published between 2026-09-28 22:21 UTC and 2026-09-28 23:20 UTC.

[Full CSV](data/new-crates-2026-09-28T23-20-23-738549Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-09-28 22:22:44 | [specodelic](https://crates.io/crates/specodelic) | 0.1.0 | 0 | Specodelic — a markdown specification format (Intent / Constraints / Model / Pr… |
| 2026-09-28 22:28:10 | [etude-bigint](https://crates.io/crates/etude-bigint) | 0.1.0 | 0 | Arbitrary-precision signed integers: a small no_std limb library with a canonic… |
| 2026-09-28 22:28:12 | [etude-ensure](https://crates.io/crates/etude-ensure) | 0.1.0 | 0 | Small, dependency-free control-flow macros (ensure! / assume!) |
| 2026-09-28 22:28:15 | [etude-rational](https://crates.io/crates/etude-rational) | 0.1.0 | 0 | Exact rational numbers: a normalized (reduced, positive-denominator) num/den pa… |
| 2026-09-28 22:28:18 | [etude-decimal](https://crates.io/crates/etude-decimal) | 0.1.0 | 0 | Exact base-10 arbitrary-precision decimal numbers (coeff * 10^exp) over etude-b… |
| 2026-09-28 22:29:21 | [etude-buffer](https://crates.io/crates/etude-buffer) | 0.1.0 | 0 | Copy-avoiding byte reader/writer buffer traits |
| 2026-09-28 22:40:41 | [betteroffice-ooxml-diff](https://crates.io/crates/betteroffice-ooxml-diff) | 0.3.0 | 0 | Bounded, dependency-free token LCS diff shared by the OOXML review and comparis… |
| 2026-09-28 22:40:52 | [etude-bytevec](https://crates.io/crates/etude-bytevec) | 0.1.0 | 0 | A chunked byte buffer backed by a relaxed-radix (RRB) rope: O(log32) offset loo… |
| 2026-09-28 22:41:04 | [native-ocr](https://crates.io/crates/native-ocr) | 0.1.0 | 0 | Text recognition with the OCR engine built into the operating system: Windows.M… |
| 2026-09-28 22:41:41 | [clockwerk-core](https://crates.io/crates/clockwerk-core) | 0.5.1 | 0 | Clockwerk software-factory runtime: workflows, agents, gates, permissions, SQLi… |
| 2026-09-28 22:42:14 | [clockwerk](https://crates.io/crates/clockwerk) | 0.5.1 | 0 | Clockwerk desktop software factory (Iced GUI) with built-in Rust workflow autom… |
| 2026-09-28 22:42:49 | [clockwerk-web](https://crates.io/crates/clockwerk-web) | 0.5.1 | 0 | Clockwerk — bin: clockwerk-web, Topcoat trace+agent web dashboard over clockwer… |
| 2026-09-28 22:43:23 | [clockwerk-tui](https://crates.io/crates/clockwerk-tui) | 0.5.1 | 0 | Clockwerk — trace + agent dashboard, terminal app (Ratatui TUI) |
| 2026-09-28 22:51:02 | [etude-strrope](https://crates.io/crates/etude-strrope) | 0.1.0 | 0 | A UTF-8 string rope: a validated-UTF-8 view over the etude-bytevec byte rope |
| 2026-09-28 22:58:45 | [etude-span](https://crates.io/crates/etude-span) | 0.1.0 | 0 | Byte-scanning primitives for copy-avoiding tokenizers over the etude byte-rope:… |
| 2026-09-28 23:01:49 | [enki-apsu](https://crates.io/crates/enki-apsu) | 0.1.0 | 0 | Vulkan GPU memory allocator and device buffer abstractions for Enki |
| 2026-09-28 23:02:06 | [nomic](https://crates.io/crates/nomic) | 0.1.0 | 0 | Nomic Core 0.1 reference machine: a deterministic executable specification lang… |
| 2026-09-28 23:02:14 | [nomic-fmt](https://crates.io/crates/nomic-fmt) | 0.1.0 | 0 | Canonical formatter for Nomic models |
| 2026-09-28 23:02:20 | [nomic-cli](https://crates.io/crates/nomic-cli) | 0.1.0 | 0 | The `nomic` command line: check, run, explore, cite, and format Nomic models |
| 2026-09-28 23:08:38 | [enki-utu](https://crates.io/crates/enki-utu) | 0.1.0 | 0 | Vulkan abstraction layer, window surface, and swapchain presentation integratio… |
| 2026-09-28 23:14:33 | [etude-json](https://crates.io/crates/etude-json) | 0.1.0 | 0 | Copy-avoiding JSON over the etude byte-rope: a tokenizer whose tokens reference… |
| 2026-09-28 23:17:52 | [yamled](https://crates.io/crates/yamled) | 0.0.0 | 0 | Format-preserving YAML edits: change what you meant, keep every other byte |
| 2026-09-28 23:19:39 | [glypher](https://crates.io/crates/glypher) | 0.0.1 | 0 | A simple text shaping and texture atlas packing crate. |
| 2026-09-28 23:20:17 | [deser-core](https://crates.io/crates/deser-core) | 0.9.0 | 0 | Core traits and types of deser, use the deser crate instead |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
