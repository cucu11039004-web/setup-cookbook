---
name: balenaEtcher
platforms: [macos, windows, linux]
category: flashing
cost: 免费开源
status: 可用
verified: 2026-11-18
website: https://etcher.balena.io/
repo: https://github.com/balena-io/etcher
author_version: 2.1.9
---

# balenaEtcher

> 把系统镜像写入 SD 卡或 U 盘的图形工具，三步完成：选镜像、选盘、Flash。教程用 Windows 烧录软件而你的电脑是 Mac 时，它是最常见的替代。

## 平台与费用

| 系统 | 支持情况 | 备注 |
|---|---|---|
| 🍎 macOS | 有；官网列 macOS 10.10 及以上 | 提供 x64 与 arm64 两种 dmg，Apple 芯片选 arm64 |
| 🪟 Windows | 有；官网列 Windows 10 及以上 | Windows 7、8 或 32 位系统，官网称最后兼容版本是 v7.9.0 |
| 🐧 Linux | 有；大多数发行版 | 官网下载页提供 x64 zip，另有 Debian（.deb）和 Red Hat（.rpm）软件源 |

费用与许可：免费，开源（官网称“always will be free and open source”）。

## 注意

- 注意：Etcher 会擦除目标盘的全部数据后再写入，烧录前确认选对了盘。它默认隐藏系统盘，以免误擦。
- 注意：用 Etcher 烧出来的 Windows 安装镜像不能直接启动（官网 FAQ 说明）。要做 Windows 安装盘，在 Windows 上用 [Rufus](https://rufus.ie/)。
- 烧录失败：先换读卡器、USB 口或卡重试；从 URL 直接烧录失败时，先下载文件再从本地烧录。
- 压缩镜像：`.img.xz` 可直接选择，不用先解压（出自 [microduck-replica](https://github.com/fanhao375/microduck-replica) 的烧录文档，Etcher 官网没有明说）。

## 替代品

| 替代品 | 区别 |
|---|---|
| [Rufus](https://rufus.ie/) | 只有 Windows 版；可制作 Windows 安装盘 |
| [Raspberry Pi Imager](https://www.raspberrypi.com/software/) | 三平台；树莓派官方出品，面向树莓派系统 |

## 来源

- 官网：<https://etcher.balena.io/>（含 FAQ 与下载表，2026-11-18 查阅）
- 官方仓库：<https://github.com/balena-io/etcher>
- 案例：[Mac 上烧录 microduck 镜像](../docs/01-mac-flash-microduck.md)
