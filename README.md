# vllm

[中文版本](./README.cn.md)

A high-throughput and memory-efficient inference and serving engine for LLMs

![vllm](https://repo.x-cmd.io/vllm.svg)

## Install

```sh
x install vllm
```

## Code insight

Total: **1,725,183** lines of code across **5795** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Python | 1,355,425 | 96,041 | 210,002 | 4684 |
| Json | 156,061 | 0 | 4 | 631 |
| Rust | 100,879 | 2,416 | 12,338 | 332 |
| Cuda | 44,958 | 5,327 | 5,459 | 98 |
| Cpp | 22,362 | 2,370 | 2,857 | 50 |

## Source

- **Upstream**: <https://github.com/vllm-project/vllm>
- **Homepage**: <https://vllm.ai>
- **License**: Apache-2.0

## Release

- **Latest**: `v0.29.0` (2026-09-09)
- **Last commit**: 2026-09-18
- **Assets in release**: 9

## Popularity

- **Stars**: 92,055 · **Forks**: 22,350 · **Open issues**: 18,265 · **Contributors**: 3,431

## Totals (cumulative)

- **Releases**: 105 · **Merged PRs**: 21528 · **Open PRs**: 5632 · **Closed issues**: 15842 · **Open issues**: 2423 · **Commits**: 21574

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-19 | 2 | 1097 | 1953 | 170 | 670 | 2466 |
| last60d | 2026-07-20 | 5 | 2321 | 3090 | 380 | 1200 | 4577 |
| 90d | 2026-06-20 | 8 | 3379 | 3862 | 557 | 1584 | 6448 |
| last180d | 2026-03-22 | 18 | 6192 | 5212 | 1880 | 2195 | 10433 |
| 360d | 2025-09-23 | 31 | 11604 | 5601 | 4978 | 2355 | 17406 |
| last720d | 2024-09-28 | 66 | 18710 | 5632 | 11238 | 2412 | 18755 |

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

_Snapshot: `data/card/260918.yml` · 2026-09-18T04:54:05Z._
