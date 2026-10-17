# vllm

[English version](./README.md)

A high-throughput and memory-efficient inference and serving engine for LLMs

[![x-cmd/install — vllm Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/vllm.svg?lang=zh)](https://x-cmd.com/install/vllm)

## 安装

```sh
x install vllm
```

## 代码洞察

合计: **1,962,573** 行代码（覆盖前 5 种语言、共 **6393** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Python | 1,560,494 | 104,702 | 236,126 | 5195 |
| Json | 169,622 | 0 | 4 | 690 |
| Rust | 116,863 | 2,738 | 13,566 | 359 |
| Cuda | 45,754 | 5,730 | 5,439 | 96 |
| Cpp | 23,904 | 2,545 | 3,064 | 53 |

## 源代码

- **上游仓库**: <https://github.com/vllm-project/vllm>
- **官网**: <https://vllm.ai>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v0.31.0` (2026-10-05)
- **最近提交**: 2026-10-17
- **Release 含资产**: 9 个

## 流行度

- **Star**: 93,959 · **Fork**: 23,468 · **开放 issue**: 19,079 · **贡献者**: 3,701

## 累计统计

- **发布数**: 107 · **已合并 PR**: 23200 · **开放 PR**: 6292 · **已关闭 issue**: 16439 · **开放 issue**: 2640 · **提交数**: 23243

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-09-17 | 2 | 1250 | 2090 | 194 | 626 | 3347 |
| last60d | 2026-08-18 | 4 | 2684 | 3563 | 439 | 1247 | 6003 |
| 90d | 2026-07-19 | 7 | 3993 | 4488 | 674 | 1749 | 8107 |
| last180d | 2026-04-20 | 17 | 7024 | 5875 | 1837 | 2355 | 12689 |
| 360d | 2025-10-22 | 32 | 12401 | 6256 | 5037 | 2576 | 19599 |
| last720d | 2024-10-27 | 66 | 20064 | 6291 | 11446 | 2630 | 20103 |

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

_数据快照: `data/card/261017.yml` · 2026-10-17T04:23:01Z._
