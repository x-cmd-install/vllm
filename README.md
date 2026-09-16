# vllm

[中文版本](./README.cn.md)

A high-throughput and memory-efficient inference and serving engine for LLMs

![vllm](https://repo.x-cmd.io/vllm.svg)

## Install

```sh
x install vllm
```

## Code insight

Total: **1,712,701** lines of code across **5773** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Python | 1,344,678 | 95,566 | 208,624 | 4664 |
| Json | 156,061 | 0 | 4 | 631 |
| Rust | 99,432 | 2,386 | 12,234 | 330 |
| Cuda | 44,924 | 5,298 | 5,458 | 98 |
| Cpp | 22,348 | 2,365 | 2,855 | 50 |

## Source

- **Upstream**: <https://github.com/vllm-project/vllm>
- **Homepage**: <https://vllm.ai>
- **License**: Apache-2.0

## Release

- **Latest**: `v0.29.0` (2026-09-09)
- **Last commit**: 2026-09-16
- **Assets in release**: 9

## Popularity

- **Stars**: 91,875 · **Forks**: 22,253 · **Open issues**: 18,202 · **Contributors**: 3,399

## Totals (cumulative)

- **Releases**: 105 · **Merged PRs**: 21368 · **Open PRs**: 5583 · **Closed issues**: 15771 · **Open issues**: 2431 · **Commits**: 21414

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-17 | 2 | 1052 | 1985 | 171 | 675 | 2152 |
| last60d | 2026-07-18 | 5 | 2226 | 3058 | 364 | 1201 | 4263 |
| 90d | 2026-06-18 | 8 | 3266 | 3817 | 536 | 1561 | 6134 |
| last180d | 2026-03-20 | 19 | 6067 | 5162 | 1833 | 2199 | 10119 |
| 360d | 2025-09-21 | 31 | 11526 | 5552 | 4959 | 2360 | 17092 |
| last720d | 2024-09-26 | 66 | 18568 | 5583 | 11187 | 2421 | 18620 |

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

_Snapshot: `data/card/260916.yml` · 2026-09-16T04:58:45Z._
