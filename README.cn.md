# vllm

[English version](./README.md)

A high-throughput and memory-efficient inference and serving engine for LLMs

[![x-cmd/install — vllm Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/vllm.svg?lang=zh)](https://x-cmd.com/install/vllm)

## 安装

```sh
x install vllm
```

## 代码洞察

合计: **1,837,227** 行代码（覆盖前 5 种语言、共 **6071** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Python | 1,447,512 | 100,224 | 221,581 | 4921 |
| Json | 163,349 | 0 | 4 | 646 |
| Rust | 111,318 | 2,592 | 13,226 | 354 |
| Cuda | 44,770 | 5,334 | 5,375 | 96 |
| Cpp | 23,867 | 2,550 | 3,071 | 54 |

## 源代码

- **上游仓库**: <https://github.com/vllm-project/vllm>
- **官网**: <https://vllm.ai>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v0.30.0` (2026-09-22)
- **最近提交**: 2026-10-02
- **Release 含资产**: 9 个

## 流行度

- **Star**: 93,051 · **Fork**: 22,924 · **开放 issue**: 18,658 · **贡献者**: 3,541

## 累计统计

- **发布数**: 106 · **已合并 PR**: 22322 · **开放 PR**: 5912 · **已关闭 issue**: 16104 · **开放 issue**: 2554 · **提交数**: 22365

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-09-02 | 2 | 1192 | 2108 | 158 | 662 | 2813 |
| last60d | 2026-08-03 | 5 | 2488 | 3373 | 387 | 1264 | 4938 |
| 90d | 2026-07-04 | 8 | 3610 | 4198 | 598 | 1724 | 6908 |
| last180d | 2026-04-05 | 17 | 6571 | 5516 | 1861 | 2298 | 11257 |
| 360d | 2025-10-07 | 31 | 11977 | 5879 | 4998 | 2489 | 18062 |
| last720d | 2024-10-12 | 67 | 19349 | 5912 | 11323 | 2543 | 19390 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [vllm-0.30.0+cpu-cp312-cp312-macosx_11_0_arm64.whl](https://github.com/vllm-project/vllm/releases/download/v0.30.0/vllm-0.30.0+cpu-cp312-cp312-macosx_11_0_arm64.whl) | 27.6 MiB | `native/darwin/arm64` |
| [vllm-0.30.0+cpu-cp38-abi3-manylinux_2_39_aarch64.whl](https://github.com/vllm-project/vllm/releases/download/v0.30.0/vllm-0.30.0+cpu-cp38-abi3-manylinux_2_39_aarch64.whl) | 65.2 MiB | `native/linux/arm64` |
| [vllm-0.30.0+cpu-cp38-abi3-manylinux_2_39_x86_64.whl](https://github.com/vllm-project/vllm/releases/download/v0.30.0/vllm-0.30.0+cpu-cp38-abi3-manylinux_2_39_x86_64.whl) | 140.6 MiB | `native/linux/x64` |
| [vllm-0.30.0+cu129-cp38-abi3-manylinux_2_28_aarch64.whl](https://github.com/vllm-project/vllm/releases/download/v0.30.0/vllm-0.30.0+cu129-cp38-abi3-manylinux_2_28_aarch64.whl) | 495.9 MiB | `native/linux/arm64` |
| [vllm-0.30.0+cu129-cp38-abi3-manylinux_2_28_x86_64.whl](https://github.com/vllm-project/vllm/releases/download/v0.30.0/vllm-0.30.0+cu129-cp38-abi3-manylinux_2_28_x86_64.whl) | 520.2 MiB | `native/linux/x64` |
| [vllm-0.30.0+xpu-cp38-abi3-manylinux_2_34_x86_64.whl](https://github.com/vllm-project/vllm/releases/download/v0.30.0/vllm-0.30.0+xpu-cp38-abi3-manylinux_2_34_x86_64.whl) | 31.1 MiB | `native/linux/x64` |
| [vllm-0.30.0-cp38-abi3-manylinux_2_28_aarch64.whl](https://github.com/vllm-project/vllm/releases/download/v0.30.0/vllm-0.30.0-cp38-abi3-manylinux_2_28_aarch64.whl) | 295.6 MiB | `native/linux/arm64` |
| [vllm-0.30.0-cp38-abi3-manylinux_2_28_x86_64.whl](https://github.com/vllm-project/vllm/releases/download/v0.30.0/vllm-0.30.0-cp38-abi3-manylinux_2_28_x86_64.whl) | 300.3 MiB | `native/linux/x64` |
| [vllm-0.30.0.tar.gz](https://github.com/vllm-project/vllm/releases/download/v0.30.0/vllm-0.30.0.tar.gz) | 40.5 MiB | `native/unknown` |

## 改进这些数据

vllm 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `vllm` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/vllm.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/261002.yml` · 2026-10-02T05:37:39Z._
