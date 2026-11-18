# 烧录与系统镜像（Linux）

> 把系统镜像写入 SD 卡或 U 盘。

| 工具 | 平台 | 用途 | 费用 | 验证 | 详情 |
|---|---|---|---|---|---|
| [balenaEtcher](https://etcher.balena.io/) | 🍎🪟🐧 | 把系统镜像写入 SD 卡或 U 盘，三步完成 | 免费开源 | 可用 · 2026-11-18 | [卡片](../tools/balena-etcher.md) |
| [Raspberry Pi Imager](https://www.raspberrypi.com/software/) | 🍎🪟🐧 | 烧录树莓派系统（树莓派官方出品） | 免费开源 | 可用 · 2026-11-18 | — |

## 注意

- Etcher 在 Linux 提供 zip 包，另有 Debian（.deb）和 Red Hat（.rpm）软件源，见 [官网下载页](https://etcher.balena.io/#download-etcher)。
- Raspberry Pi Imager 在 Linux 上提供 AppImage（据第三方资料，Ubuntu 上需先装 `libfuse2t64`）；树莓派系统可直接 `sudo apt install rpi-imager`。
- 注意：烧录会清空目标盘，写入前确认选对了盘。
