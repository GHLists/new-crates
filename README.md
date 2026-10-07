# New crates

Hourly lists of crates newly published to [crates.io](https://crates.io/),
taken from the [crates.io API](https://crates.io/api/v1/crates).
A GitHub Actions workflow runs every hour, fetches the crates published since
the previous list and commits one CSV per run to [`data/`](data/), e.g.
[`data/new-crates-<timestamp>.csv`](data/).

Read the latest list below.

## Latest list — 2026-10-07 00:19 UTC

New crates published between 2026-10-06 23:18 UTC and 2026-10-07 00:19 UTC.

[Full CSV](data/new-crates-2026-10-07T00-19-20-687794Z.csv)

| Created (UTC) | Crate | Version | Downloads | Description |
| :------------ | :---- | :------ | --------: | :---------- |
| 2026-10-06 23:20:35 | [jackdaw_scene_types](https://crates.io/crates/jackdaw_scene_types) | 0.19.0-rc.0 | 0 | Internal crate for the jackdaw editor |
| 2026-10-06 23:30:59 | [jackdaw_select](https://crates.io/crates/jackdaw_select) | 0.19.0-rc.0 | 0 | Engine-agnostic half-edge selection traversal for the jackdaw editor |
| 2026-10-06 23:41:12 | [jackdaw_uv](https://crates.io/crates/jackdaw_uv) | 0.19.0-rc.0 | 0 | Engine-agnostic UV projection math for the jackdaw editor |
| 2026-10-06 23:42:04 | [ikigai-markdown](https://crates.io/crates/ikigai-markdown) | 0.1.0 | 0 | Markdown as a graph for ikigai: urn:markdown:lift — one generic structural lift… |
| 2026-10-06 23:49:40 | [jackdaw_animation_runtime](https://crates.io/crates/jackdaw_animation_runtime) | 0.19.0-rc.0 | 0 | Binds authored animation sets to their glTF skeletons and plays the state they… |
| 2026-10-06 23:51:24 | [taconite-sapiens2](https://crates.io/crates/taconite-sapiens2) | 0.1.0 | 0 | Sapiens2-Pose (308 whole-body keypoints) on an AMD XDNA NPU: IRON kernels repla… |
| 2026-10-06 23:53:39 | [cargo-debuggable](https://crates.io/crates/cargo-debuggable) | 0.1.0 | 0 | Sets up GDB, LLDB and VS Code (CodeLLDB) for the `debuggable` crate, and checks… |
| 2026-10-06 23:53:40 | [debuggable-derive](https://crates.io/crates/debuggable-derive) | 0.1.0 | 0 | Implementation detail of the `debuggable` crate; use that crate instead |
| 2026-10-06 23:53:42 | [debuggable](https://crates.io/crates/debuggable) | 0.1.0 | 0 | Derive macro that makes your types readable in GDB, LLDB and VS Code (CodeLLDB) |
| 2026-10-07 00:00:12 | [jackdaw_camera_rig](https://crates.io/crates/jackdaw_camera_rig) | 0.19.0-rc.0 | 0 | Authorable third/first-person camera-rig components + runtime driver for Jackda… |
| 2026-10-07 00:06:24 | [hoppy](https://crates.io/crates/hoppy) | 0.1.0 | 0 | A friendlier ifconfig, netstat, and ping. See which adapter is on which network… |
| 2026-10-07 00:08:40 | [invoice-kit](https://crates.io/crates/invoice-kit) | 0.1.0 | 0 | Accounts-receivable invoicing for an SME ledger — three orthogonal document sta… |
| 2026-10-07 00:10:36 | [jackdaw_csg](https://crates.io/crates/jackdaw_csg) | 0.19.0-rc.0 | 0 | Mesh-CSG glue between jackdaw brushes and the manifold3d kernel |
| 2026-10-07 00:12:09 | [crc-turbo](https://crates.io/crates/crc-turbo) | 0.0.0 | 0 | Placeholder, do not depend on this version: name reserved for a maintained fork… |

## Data source

Data comes from the [crates.io API](https://crates.io/api/v1/crates).
crates.io is the Rust community's crate registry, operated by the
[Rust Foundation](https://foundation.rust-lang.org/). Crate metadata is
provided by the crate authors and is typically available under the license
stated in each crate's manifest (commonly MIT or Apache-2.0).
