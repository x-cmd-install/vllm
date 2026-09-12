# vllm

[中文版本](./README.cn.md)

A high-throughput and memory-efficient inference and serving engine for LLMs

![vllm](https://repo.x-cmd.io/vllm.svg)

## Install

```sh
x install vllm
```

## Code insight

Total: **1,687,911** lines of code across **5727** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Python | 1,322,579 | 94,904 | 205,951 | 4621 |
| Json | 155,895 | 0 | 4 | 631 |
| Rust | 97,440 | 2,370 | 12,077 | 327 |
| Cuda | 44,618 | 5,270 | 5,449 | 98 |
| Cpp | 22,339 | 2,364 | 2,855 | 50 |

## Source

- **Upstream**: <https://github.com/vllm-project/vllm>
- **Homepage**: <https://vllm.ai>
- **License**: Apache-2.0

## Release

- **Latest**: `v0.29.0` (2026-09-09)
- **Last commit**: 2026-09-12
- **Assets in release**: 9

## Popularity

- **Stars**: 91,530 · **Forks**: 22,081 · **Open issues**: 18,102 · **Contributors**: 3,371

## Totals (cumulative)

- **Releases**: 105 · **Merged PRs**: 21155 · **Open PRs**: 5487 · **Closed issues**: 15707 · **Open issues**: 2395 · **Commits**: 21201

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-13 | 2 | 975 | 1976 | 153 | 683 | 2061 |
| last60d | 2026-07-14 | 6 | 2140 | 3031 | 349 | 1193 | 4192 |
| 90d | 2026-06-14 | 9 | 3242 | 3787 | 534 | 1548 | 5985 |
| last180d | 2026-03-16 | 19 | 6049 | 5110 | 1872 | 2170 | 9924 |
| 360d | 2025-09-17 | 31 | 11436 | 5457 | 4961 | 2326 | 16913 |
| last720d | 2024-09-22 | 67 | 18414 | 5487 | 11195 | 2386 | 18467 |

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

_Snapshot: `data/card/260912.yml` · 2026-09-12T04:42:37Z._
