# 烧录与系统镜像（macOS）

> 把系统镜像写入 SD 卡或 U 盘。教程只给了 Windows 工具时，这里有 Mac 上能用的替代。

| 工具 | 平台 | 用途 | 费用 | 验证 | 详情 |
|---|---|---|---|---|---|
| [balenaEtcher](https://etcher.balena.io/) | 🍎🪟🐧 | 把系统镜像写入 SD 卡或 U 盘，三步完成 | 免费开源 | 可用 · 2026-11-18 | [卡片](../tools/balena-etcher.md) |
| [Raspberry Pi Imager](https://www.raspberrypi.com/software/) | 🍎🪟🐧 | 烧录树莓派系统（树莓派官方出品） | 免费开源 | 可用 · 2026-11-18 | — |

## 注意

- 注意：烧录会清空目标盘，写入前确认选对了盘。
- Rufus 只有 Windows 版，Mac 上没有，替代是 Etcher；见 [windows/flashing.md](../windows/flashing.md)。
- 案例：[Mac 上烧录 microduck 镜像](../docs/01-mac-flash-microduck.md)。
