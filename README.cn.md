# vllm

[English version](./README.md)

A high-throughput and memory-efficient inference and serving engine for LLMs

[![x-cmd/install — vllm Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/vllm.svg?lang=zh)](https://x-cmd.com/install/vllm)

## 安装

```sh
x install vllm
```

## 代码洞察

合计: **1,893,077** 行代码（覆盖前 5 种语言、共 **6223** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Python | 1,497,362 | 102,516 | 228,323 | 5031 |
| Json | 166,525 | 0 | 4 | 687 |
| Rust | 113,779 | 2,658 | 13,380 | 355 |
| Cuda | 45,177 | 5,576 | 5,390 | 96 |
| Cpp | 23,891 | 2,545 | 3,062 | 54 |

## 源代码

- **上游仓库**: <https://github.com/vllm-project/vllm>
- **官网**: <https://vllm.ai>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v0.31.0` (2026-10-05)
- **最近提交**: 2026-10-11
- **Release 含资产**: 9 个

## 流行度

- **Star**: 93,542 · **Fork**: 23,227 · **开放 issue**: 18,901 · **贡献者**: 3,643

## 累计统计

- **发布数**: 107 · **已合并 PR**: 22788 · **开放 PR**: 6096 · **已关闭 issue**: 16325 · **开放 issue**: 2576 · **提交数**: 22832

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-09-11 | 2 | 1193 | 2016 | 185 | 622 | 2534 |
| last60d | 2026-08-12 | 4 | 2540 | 3479 | 409 | 1252 | 5190 |
| 90d | 2026-07-13 | 8 | 3765 | 4367 | 639 | 1729 | 7294 |
| last180d | 2026-04-14 | 18 | 6793 | 5700 | 1876 | 2311 | 11876 |
| 360d | 2025-10-16 | 32 | 12138 | 6062 | 5016 | 2512 | 18787 |
| last720d | 2024-10-21 | 66 | 19718 | 6095 | 11415 | 2565 | 19774 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [vllm-0.31.0+cpu-cp312-cp312-macosx_11_0_arm64.whl](https://github.com/vllm-project/vllm/releases/download/v0.31.0/vllm-0.31.0+cpu-cp312-cp312-macosx_11_0_arm64.whl) | 28.1 MiB | `native/darwin/arm64` |
| [vllm-0.31.0+cpu-cp38-abi3-manylinux_2_39_aarch64.whl](https://github.com/vllm-project/vllm/releases/download/v0.31.0/vllm-0.31.0+cpu-cp38-abi3-manylinux_2_39_aarch64.whl) | 65.5 MiB | `native/linux/arm64` |
| [vllm-0.31.0+cpu-cp38-abi3-manylinux_2_39_x86_64.whl](https://github.com/vllm-project/vllm/releases/download/v0.31.0/vllm-0.31.0+cpu-cp38-abi3-manylinux_2_39_x86_64.whl) | 143.9 MiB | `native/linux/x64` |
| [vllm-0.31.0+cu129-cp38-abi3-manylinux_2_28_aarch64.whl](https://github.com/vllm-project/vllm/releases/download/v0.31.0/vllm-0.31.0+cu129-cp38-abi3-manylinux_2_28_aarch64.whl) | 502.7 MiB | `native/linux/arm64` |
| [vllm-0.31.0+cu129-cp38-abi3-manylinux_2_28_x86_64.whl](https://github.com/vllm-project/vllm/releases/download/v0.31.0/vllm-0.31.0+cu129-cp38-abi3-manylinux_2_28_x86_64.whl) | 527.7 MiB | `native/linux/x64` |
| [vllm-0.31.0+xpu-cp38-abi3-manylinux_2_34_x86_64.whl](https://github.com/vllm-project/vllm/releases/download/v0.31.0/vllm-0.31.0+xpu-cp38-abi3-manylinux_2_34_x86_64.whl) | 31.6 MiB | `native/linux/x64` |
| [vllm-0.31.0-cp38-abi3-manylinux_2_28_aarch64.whl](https://github.com/vllm-project/vllm/releases/download/v0.31.0/vllm-0.31.0-cp38-abi3-manylinux_2_28_aarch64.whl) | 300.8 MiB | `native/linux/arm64` |
| [vllm-0.31.0-cp38-abi3-manylinux_2_28_x86_64.whl](https://github.com/vllm-project/vllm/releases/download/v0.31.0/vllm-0.31.0-cp38-abi3-manylinux_2_28_x86_64.whl) | 305.7 MiB | `native/linux/x64` |
| [vllm-0.31.0.tar.gz](https://github.com/vllm-project/vllm/releases/download/v0.31.0/vllm-0.31.0.tar.gz) | 41.4 MiB | `native/unknown` |

## 改进这些数据

vllm 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `vllm` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/vllm.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/261011.yml` · 2026-10-11T05:53:00Z._
