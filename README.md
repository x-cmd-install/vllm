# vllm

[中文版本](./README.cn.md)

A high-throughput and memory-efficient inference and serving engine for LLMs

![vllm](https://repo.x-cmd.io/vllm.svg)

## Install

```sh
x install vllm
```

## Code insight

Total: **1,707,625** lines of code across **5761** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Python | 1,340,700 | 95,549 | 208,172 | 4653 |
| Json | 155,895 | 0 | 4 | 631 |
| Rust | 98,772 | 2,383 | 12,172 | 329 |
| Cuda | 44,692 | 5,287 | 5,453 | 98 |
| Cpp | 22,340 | 2,365 | 2,855 | 50 |

## Source

- **Upstream**: <https://github.com/vllm-project/vllm>
- **Homepage**: <https://vllm.ai>
- **License**: Apache-2.0

## Release

- **Latest**: `v0.29.0` (2026-09-09)
- **Last commit**: 2026-09-15
- **Assets in release**: 9

## Popularity

- **Stars**: 91,777 · **Forks**: 22,208 · **Open issues**: 18,170 · **Contributors**: 3,386

## Totals (cumulative)

- **Releases**: 105 · **Merged PRs**: 21309 · **Open PRs**: 5542 · **Closed issues**: 15762 · **Open issues**: 2408 · **Commits**: 21355

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-16 | 2 | 1030 | 1975 | 165 | 678 | 1879 |
| last60d | 2026-07-17 | 5 | 2186 | 3031 | 360 | 1187 | 3990 |
| 90d | 2026-06-17 | 8 | 3263 | 3805 | 540 | 1548 | 5861 |
| last180d | 2026-03-19 | 19 | 6045 | 5138 | 1856 | 2177 | 9846 |
| 360d | 2025-09-20 | 31 | 11485 | 5511 | 4958 | 2337 | 16819 |
| last720d | 2024-09-25 | 67 | 18528 | 5542 | 11201 | 2398 | 18585 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [vllm-0.29.0+cpu-cp312-cp312-macosx_11_0_arm64.whl](https://github.com/vllm-project/vllm/releases/download/v0.29.0/vllm-0.29.0+cpu-cp312-cp312-macosx_11_0_arm64.whl) | 26.7 MiB | `native/darwin/arm64` |
| [vllm-0.29.0+cpu-cp38-abi3-manylinux_2_34_aarch64.whl](https://github.com/vllm-project/vllm/releases/download/v0.29.0/vllm-0.29.0+cpu-cp38-abi3-manylinux_2_34_aarch64.whl) | 65.1 MiB | `native/linux/arm64` |
| [vllm-0.29.0+cpu-cp38-abi3-manylinux_2_34_x86_64.whl](https://github.com/vllm-project/vllm/releases/download/v0.29.0/vllm-0.29.0+cpu-cp38-abi3-manylinux_2_34_x86_64.whl) | 131.5 MiB | `native/linux/x64` |
| [vllm-0.29.0+cu129-cp38-abi3-manylinux_2_28_aarch64.whl](https://github.com/vllm-project/vllm/releases/download/v0.29.0/vllm-0.29.0+cu129-cp38-abi3-manylinux_2_28_aarch64.whl) | 497.5 MiB | `native/linux/arm64` |
| [vllm-0.29.0+cu129-cp38-abi3-manylinux_2_28_x86_64.whl](https://github.com/vllm-project/vllm/releases/download/v0.29.0/vllm-0.29.0+cu129-cp38-abi3-manylinux_2_28_x86_64.whl) | 523.1 MiB | `native/linux/x64` |
| [vllm-0.29.0+xpu-cp38-abi3-manylinux_2_34_x86_64.whl](https://github.com/vllm-project/vllm/releases/download/v0.29.0/vllm-0.29.0+xpu-cp38-abi3-manylinux_2_34_x86_64.whl) | 30.1 MiB | `native/linux/x64` |
| [vllm-0.29.0-cp38-abi3-manylinux_2_28_aarch64.whl](https://github.com/vllm-project/vllm/releases/download/v0.29.0/vllm-0.29.0-cp38-abi3-manylinux_2_28_aarch64.whl) | 295.7 MiB | `native/linux/arm64` |
| [vllm-0.29.0-cp38-abi3-manylinux_2_28_x86_64.whl](https://github.com/vllm-project/vllm/releases/download/v0.29.0/vllm-0.29.0-cp38-abi3-manylinux_2_28_x86_64.whl) | 301.3 MiB | `native/linux/x64` |
| [vllm-0.29.0.tar.gz](https://github.com/vllm-project/vllm/releases/download/v0.29.0/vllm-0.29.0.tar.gz) | 39.0 MiB | `native/unknown` |

## Improve this data

Install metadata for vllm lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `vllm` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/vllm.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260915.yml` · 2026-09-15T05:17:49Z._
