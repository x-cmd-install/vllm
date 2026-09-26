# vllm

[English version](./README.md)

A high-throughput and memory-efficient inference and serving engine for LLMs

[![x-cmd/install — vllm Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/vllm.svg?lang=zh)](https://x-cmd.com/install/vllm)

## 安装

```sh
x install vllm
```

## 代码洞察

合计: **1,783,520** 行代码（覆盖前 5 种语言、共 **5948** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Python | 1,406,480 | 98,367 | 216,636 | 4825 |
| Json | 158,948 | 0 | 4 | 633 |
| Rust | 103,905 | 2,448 | 12,623 | 340 |
| Cuda | 44,556 | 5,231 | 5,360 | 97 |
| Cpp | 23,681 | 2,545 | 3,032 | 53 |

## 源代码

- **上游仓库**: <https://github.com/vllm-project/vllm>
- **官网**: <https://vllm.ai>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v0.30.0` (2026-09-22)
- **最近提交**: 2026-09-26
- **Release 含资产**: 9 个

## 流行度

- **Star**: 92,692 · **Fork**: 22,676 · **开放 issue**: 18,492 · **贡献者**: 3,503

## 累计统计

- **发布数**: 106 · **已合并 PR**: 21955 · **开放 PR**: 5900 · **已关闭 issue**: 15970 · **开放 issue**: 2522 · **提交数**: 22000

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-27 | 2 | 1144 | 2114 | 143 | 703 | 2897 |
| last60d | 2026-07-28 | 5 | 2397 | 3319 | 371 | 1248 | 4920 |
| 90d | 2026-06-28 | 9 | 3513 | 4122 | 565 | 1694 | 6765 |
| last180d | 2026-03-30 | 19 | 6353 | 5504 | 1837 | 2281 | 10999 |
| 360d | 2025-10-01 | 32 | 11770 | 5868 | 4954 | 2456 | 17959 |
| last720d | 2024-10-06 | 67 | 19065 | 5900 | 11286 | 2512 | 19104 |

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

_数据快照: `data/card/260926.yml` · 2026-09-26T04:58:19Z._
