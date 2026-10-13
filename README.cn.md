# vllm

[English version](./README.md)

A high-throughput and memory-efficient inference and serving engine for LLMs

[![x-cmd/install — vllm Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/vllm.svg?lang=zh)](https://x-cmd.com/install/vllm)

## 安装

```sh
x install vllm
```

## 代码洞察

合计: **1,911,178** 行代码（覆盖前 5 种语言、共 **6256** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Python | 1,510,782 | 102,983 | 230,223 | 5061 |
| Json | 169,639 | 0 | 4 | 690 |
| Rust | 115,636 | 2,703 | 13,491 | 357 |
| Cuda | 45,177 | 5,581 | 5,388 | 95 |
| Cpp | 23,893 | 2,543 | 3,063 | 53 |

## 源代码

- **上游仓库**: <https://github.com/vllm-project/vllm>
- **官网**: <https://vllm.ai>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v0.31.0` (2026-10-05)
- **最近提交**: 2026-10-13
- **Release 含资产**: 9 个

## 流行度

- **Star**: 93,690 · **Fork**: 23,301 · **开放 issue**: 18,958 · **贡献者**: 3,660

## 累计统计

- **发布数**: 107 · **已合并 PR**: 22899 · **开放 PR**: 6142 · **已关闭 issue**: 16350 · **开放 issue**: 2608 · **提交数**: 22943

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-09-13 | 2 | 1222 | 2065 | 188 | 649 | 2778 |
| last60d | 2026-08-14 | 4 | 2522 | 3463 | 409 | 1260 | 5434 |
| 90d | 2026-07-15 | 7 | 3796 | 4373 | 640 | 1735 | 7538 |
| last180d | 2026-04-16 | 18 | 6826 | 5738 | 1852 | 2336 | 12120 |
| 360d | 2025-10-18 | 32 | 12198 | 6107 | 5011 | 2544 | 19031 |
| last720d | 2024-10-23 | 66 | 19796 | 6141 | 11408 | 2597 | 19849 |

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

_数据快照: `data/card/261013.yml` · 2026-10-13T06:57:21Z._
