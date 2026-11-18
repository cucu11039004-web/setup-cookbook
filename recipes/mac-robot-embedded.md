# Mac 上复现树莓派类机器人项目

> 教程按 Windows 写（如用 Rufus 烧卡、用 Windows 串口工具），而你的开发机是 Mac 时，这份清单告诉你每个环节用什么。以 [microduck-replica](https://github.com/fanhao375/microduck-replica) 为例。

| 环节 | 工具 | 说明 |
|---|---|---|
| 烧录系统镜像 | [balenaEtcher](../tools/balena-etcher.md)（🍎🪟🐧） | 教程用 Windows 上的 Rufus 时，Mac 上用它代替；`.img.xz` 不用解压 |
| 烧录树莓派系统 | [Raspberry Pi Imager](../macos/flashing.md)（🍎🪟🐧） | 目标是树莓派时的另一个选择 |
| 登录开发板、传文件 | [FinalShell](../tools/finalshell.md)（🍎🪟🐧） | SSH 终端加 SFTP；板子联网后使用 |
| 异地访问开发板 | [ZeroTier](../macos/ai-remote.md)（🍎🪟🐧） | 板子不在身边时组虚拟局域网 |
| 终端与编辑器 | [Warp](../tools/warp.md)、[Visual Studio Code](../macos/dev-basics.md) | 日常开发 |

## 注意

- 注意：Windows 上的串口工具、驱动在 Mac 上的对应物还没有整理，见 [macOS 页的待补充分类](../macos/README.md#分类索引)。
- 案例全过程见 [Mac 上烧录 microduck 镜像](../docs/01-mac-flash-microduck.md)。
