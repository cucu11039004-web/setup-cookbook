# 烧录与系统镜像（Windows）

> 把系统镜像写入 SD 卡或 U 盘，也可以做 Windows 安装盘。

| 工具 | 平台 | 用途 | 费用 | 验证 | 详情 |
|---|---|---|---|---|---|
| [Rufus](https://rufus.ie/) | 🪟 | 制作启动盘，可写入 Windows 安装镜像和多数 Linux 镜像 | 免费开源 | 可用 · 2026-11-18 | — |
| [balenaEtcher](https://etcher.balena.io/) | 🍎🪟🐧 | 把系统镜像写入 SD 卡或 U 盘，三步完成 | 免费开源 | 可用 · 2026-11-18 | [卡片](../tools/balena-etcher.md) |
| [Raspberry Pi Imager](https://www.raspberrypi.com/software/) | 🍎🪟🐧 | 烧录树莓派系统（树莓派官方出品） | 免费开源 | 可用 · 2026-11-18 | — |

## 注意

- 注意：做 Windows 安装盘用 Rufus；Etcher 烧出的 Windows 镜像不能直接启动。
- Rufus 只有 Windows 版（Windows 8 及以上），GPL-3.0 或更新版本许可；官网列出标准版、便携版、x86 和 ARM64 构建，免安装，下载后运行。
- 注意：烧录会清空目标盘，写入前确认选对了盘。
