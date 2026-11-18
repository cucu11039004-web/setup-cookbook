# 案例：Mac 上烧录 microduck 镜像

> 复现 [microduck-replica](https://github.com/fanhao375/microduck-replica) 时，README 的烧录入口给的是 Windows 版 Rufus，而开发机是 Mac。这里记录 Mac 上的做法：balenaEtcher。

## 背景

| 项目 | 内容 |
|---|---|
| 目标 | 把 microduck 的复刻镜像（`.img.xz` 格式，用于 Radxa Zero 3W）写入 SD 卡 |
| README 入口用的工具 | [Rufus](https://rufus.ie/)，只有 Windows 版 |
| 开发机 | Mac |
| Mac 上的做法 | [balenaEtcher](../tools/balena-etcher.md)；上游的镜像文档也把它列为可用工具 |

## 步骤

> 以下按上游 `software/image/烧录和第一次使用.md` 的流程整理。

1. 下载 `microduck-replica-日期.img.xz` 和同名的 `.sha256` 文件（GitHub Releases 或网盘）。
2. 核对文件没下坏（可跳过，出了怪问题先查这个）：在 Mac 上运行 `shasum -a 256 -c microduck-replica-日期.img.xz.sha256`，即对照 `.sha256` 文件检查镜像的 SHA-256 值。
3. 用 Etcher 烧卡：选镜像文件（`.img.xz` 不用解压）→ 选 SD 卡 → Flash。
4. 把卡插回开发板，上电，等约 3 分钟完成第一次开机，再按上游文档配网。

用 [Raspberry Pi Imager](https://www.raspberrypi.com/software/) 也行：「操作系统」选最下面的「使用自定义镜像」（上游文档的说法）。

注意：Etcher 会清空所选卡的全部数据，Flash 前确认选的是 SD 卡。

注意：上游文档里「烧完弹出格式化提示时点取消」针对的是 Windows，Mac 上没有这个现象时无需处理（作者未实测，待补充）。

## 待补充

- 作者在 Mac 上实际烧录时遇到的问题与解决办法
- 烧录后在 Mac 上用串口登录开发板的工具

## 参考

- 上游教程：[烧录和第一次使用](https://github.com/fanhao375/microduck-replica/blob/main/software/image/烧录和第一次使用.md)
- 相关工具：[balenaEtcher 卡片](../tools/balena-etcher.md)、[Windows 烧录页](../windows/flashing.md)
