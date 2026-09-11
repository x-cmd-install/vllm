# vllm

[中文版本](./README.cn.md)

A high-throughput and memory-efficient inference and serving engine for LLMs

![vllm](https://repo.x-cmd.io/vllm.svg)

## Install

```sh
x install vllm
```

## Code insight

Total: **1,673,941** lines of code across **5709** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Python | 1,310,853 | 94,759 | 204,715 | 4607 |
| Json | 155,895 | 0 | 4 | 631 |
| Rust | 96,446 | 2,354 | 12,017 | 324 |
| Cuda | 43,478 | 5,190 | 5,378 | 97 |
| Cpp | 22,284 | 2,364 | 2,849 | 50 |

## Source

- **Upstream**: <https://github.com/vllm-project/vllm>
- **Homepage**: <https://vllm.ai>
- **License**: Apache-2.0

## Release

- **Latest**: `v0.29.0` (2026-09-09)
- **Last commit**: 2026-09-11
- **Assets in release**: 9

## Popularity

- **Stars**: 91,516 · **Forks**: 22,071 · **Open issues**: 18,085 · **Contributors**: 3,370

## Totals (cumulative)

- **Releases**: 105 · **Merged PRs**: 21138 · **Open PRs**: 5484 · **Closed issues**: 15684 · **Open issues**: 2401 · **Commits**: 21184

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 2 | 1010 | 2017 | 158 | 692 | 2033 |
| last60d | 2026-07-13 | 6 | 2157 | 3056 | 356 | 1201 | 4164 |
| 90d | 2026-06-13 | 9 | 3237 | 3786 | 541 | 1545 | 5957 |
| last180d | 2026-03-15 | 19 | 6084 | 5113 | 1865 | 2181 | 9896 |
| 360d | 2025-09-16 | 31 | 11477 | 5454 | 4967 | 2333 | 16885 |
| last720d | 2024-09-21 | 67 | 18407 | 5484 | 11179 | 2392 | 18460 |

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

_Snapshot: `data/card/260911.yml` · 2026-09-11T20:03:59Z._
