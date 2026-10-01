# vllm

[English version](./README.md)

A high-throughput and memory-efficient inference and serving engine for LLMs

[![x-cmd/install — vllm Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/vllm.svg?lang=zh)](https://x-cmd.com/install/vllm)

## 安装

```sh
x install vllm
```

## 代码洞察

合计: **1,830,314** 行代码（覆盖前 5 种语言、共 **6053** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Python | 1,444,609 | 100,415 | 221,135 | 4912 |
| Json | 162,909 | 0 | 4 | 645 |
| Rust | 108,058 | 2,517 | 12,967 | 346 |
| Cuda | 44,511 | 5,261 | 5,358 | 96 |
| Cpp | 23,856 | 2,550 | 3,067 | 54 |

## 源代码

- **上游仓库**: <https://github.com/vllm-project/vllm>
- **官网**: <https://vllm.ai>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v0.30.0` (2026-09-22)
- **最近提交**: 2026-10-01
- **Release 含资产**: 9 个

## 流行度

- **Star**: 93,017 · **Fork**: 22,876 · **开放 issue**: 18,634 · **贡献者**: 3,530

## 累计统计

- **发布数**: 106 · **已合并 PR**: 22259 · **开放 PR**: 5845 · **已关闭 issue**: 16086 · **开放 issue**: 2548 · **提交数**: 22303

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-09-01 | 2 | 1217 | 2067 | 152 | 676 | 2677 |
| last60d | 2026-08-02 | 5 | 2477 | 3338 | 382 | 1270 | 4802 |
| 90d | 2026-07-03 | 8 | 3560 | 4137 | 583 | 1719 | 6772 |
| last180d | 2026-04-04 | 17 | 6518 | 5451 | 1851 | 2295 | 11121 |
| 360d | 2025-10-06 | 31 | 11943 | 5812 | 4996 | 2483 | 17926 |
| last720d | 2024-10-11 | 67 | 19290 | 5845 | 11316 | 2537 | 19340 |

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

_数据快照: `data/card/261001.yml` · 2026-10-01T05:58:59Z._
