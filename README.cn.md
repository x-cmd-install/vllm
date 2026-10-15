# vllm

[English version](./README.md)

A high-throughput and memory-efficient inference and serving engine for LLMs

[![x-cmd/install — vllm Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/vllm.svg?lang=zh)](https://x-cmd.com/install/vllm)

## 安装

```sh
x install vllm
```

## 代码洞察

合计: **1,926,895** 行代码（覆盖前 5 种语言、共 **6294** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Python | 1,525,978 | 103,581 | 232,155 | 5098 |
| Json | 169,622 | 0 | 4 | 690 |
| Rust | 115,666 | 2,703 | 13,494 | 357 |
| Cuda | 45,648 | 5,705 | 5,438 | 96 |
| Cpp | 23,906 | 2,545 | 3,064 | 53 |

## 源代码

- **上游仓库**: <https://github.com/vllm-project/vllm>
- **官网**: <https://vllm.ai>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v0.31.0` (2026-10-05)
- **最近提交**: 2026-10-15
- **Release 含资产**: 9 个

## 流行度

- **Star**: 93,811 · **Fork**: 23,394 · **开放 issue**: 19,023 · **贡献者**: 3,682

## 累计统计

- **发布数**: 107 · **已合并 PR**: 23062 · **开放 PR**: 6255 · **已关闭 issue**: 16395 · **开放 issue**: 2628 · **提交数**: 23105

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-09-15 | 2 | 1259 | 2091 | 195 | 622 | 3046 |
| last60d | 2026-08-16 | 4 | 2643 | 3546 | 437 | 1253 | 5702 |
| 90d | 2026-07-17 | 7 | 3888 | 4444 | 662 | 1732 | 7806 |
| last180d | 2026-04-18 | 18 | 6942 | 5849 | 1817 | 2351 | 12388 |
| 360d | 2025-10-20 | 32 | 12328 | 6219 | 5034 | 2564 | 19299 |
| last720d | 2024-10-25 | 66 | 19938 | 6254 | 11421 | 2618 | 19976 |

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

_数据快照: `data/card/261015.yml` · 2026-10-15T04:36:53Z._
