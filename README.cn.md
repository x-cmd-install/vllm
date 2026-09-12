# vllm

[English version](./README.md)

A high-throughput and memory-efficient inference and serving engine for LLMs

![vllm](https://repo.x-cmd.io/vllm.svg?lang=zh)

## 安装

```sh
x install vllm
```

## 代码洞察

合计: **1,687,911** 行代码（覆盖前 5 种语言、共 **5727** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Python | 1,322,579 | 94,904 | 205,951 | 4621 |
| Json | 155,895 | 0 | 4 | 631 |
| Rust | 97,440 | 2,370 | 12,077 | 327 |
| Cuda | 44,618 | 5,270 | 5,449 | 98 |
| Cpp | 22,339 | 2,364 | 2,855 | 50 |

## 源代码

- **上游仓库**: <https://github.com/vllm-project/vllm>
- **官网**: <https://vllm.ai>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v0.29.0` (2026-09-09)
- **最近提交**: 2026-09-12
- **Release 含资产**: 9 个

## 流行度

- **Star**: 91,530 · **Fork**: 22,081 · **开放 issue**: 18,102 · **贡献者**: 3,371

## 累计统计

- **发布数**: 105 · **已合并 PR**: 21155 · **开放 PR**: 5487 · **已关闭 issue**: 15707 · **开放 issue**: 2395 · **提交数**: 21201

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-13 | 2 | 975 | 1976 | 153 | 683 | 2061 |
| last60d | 2026-07-14 | 6 | 2140 | 3031 | 349 | 1193 | 4192 |
| 90d | 2026-06-14 | 9 | 3242 | 3787 | 534 | 1548 | 5985 |
| last180d | 2026-03-16 | 19 | 6049 | 5110 | 1872 | 2170 | 9924 |
| 360d | 2025-09-17 | 31 | 11436 | 5457 | 4961 | 2326 | 16913 |
| last720d | 2024-09-22 | 67 | 18414 | 5487 | 11195 | 2386 | 18467 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [vllm-0.29.0+cpu-cp312-cp312-macosx_11_0_arm64.whl](https://github.com/vllm-project/vllm/releases/download/v0.29.0/vllm-0.29.0+cpu-cp312-cp312-macosx_11_0_arm64.whl) | 26.7 MiB | `native/darwin/arm64` |
| [vllm-0.29.0+cpu-cp38-abi3-manylinux_2_34_aarch64.whl](https://github.com/vllm-project/vllm/releases/download/v0.29.0/vllm-0.29.0+cpu-cp38-abi3-manylinux_2_34_aarch64.whl) | 65.1 MiB | `native/linux/arm64` |
| [vllm-0.29.0+cpu-cp38-abi3-manylinux_2_34_x86_64.whl](https://github.com/vllm-project/vllm/releases/download/v0.29.0/vllm-0.29.0+cpu-cp38-abi3-manylinux_2_34_x86_64.whl) | 131.5 MiB | `native/linux/x64` |
| [vllm-0.29.0+cu129-cp38-abi3-manylinux_2_28_aarch64.whl](https://github.com/vllm-project/vllm/releases/download/v0.29.0/vllm-0.29.0+cu129-cp38-abi3-manylinux_2_28_aarch64.whl) | 497.5 MiB | `native/linux/arm64` |
| [vllm-0.29.0+cu129-cp38-abi3-manylinux_2_28_x86_64.whl](https://github.com/vllm-project/vllm/releases/download/v0.29.0/vllm-0.29.0+cu129-cp38-abi3-manylinux_2_28_x86_64.whl) | 523.1 MiB | `native/linux/x64` |
| [vllm-0.29.0+xpu-cp38-abi3-manylinux_2_34_x86_64.whl](https://github.com/vllm-project/vllm/releases/download/v0.29.0/vllm-0.29.0+xpu-cp38-abi3-manylinux_2_34_x86_64.whl) | 30.1 MiB | `native/linux/x64` |
| [vllm-0.29.0-cp38-abi3-manylinux_2_28_aarch64.whl](https://github.com/vllm-project/vllm/releases/download/v0.29.0/vllm-0.29.0-cp38-abi3-manylinux_2_28_aarch64.whl) | 295.7 MiB | `native/linux/arm64` |
| [vllm-0.29.0-cp38-abi3-manylinux_2_28_x86_64.whl](https://github.com/vllm-project/vllm/releases/download/v0.29.0/vllm-0.29.0-cp38-abi3-manylinux_2_28_x86_64.whl) | 301.3 MiB | `native/linux/x64` |
| [vllm-0.29.0.tar.gz](https://github.com/vllm-project/vllm/releases/download/v0.29.0/vllm-0.29.0.tar.gz) | 39.0 MiB | `native/unknown` |

## 改进这些数据

vllm 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `vllm` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/vllm.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260912.yml` · 2026-09-12T04:42:38Z._
