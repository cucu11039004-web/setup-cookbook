# setup-cookbook

> 按操作系统整理的开发与日常工具清单。每个工具写清楚：是什么、解决什么问题、支持哪些系统、现在还能不能用。内容由社区维护，工具失效了欢迎提 Issue 或 PR。

## 怎么找工具

| 想找什么 | 入口 |
|---|---|
| 🍎 macOS 上的工具 | [macos/](macos/README.md) |
| 🪟 Windows 上的工具 | [windows/](windows/README.md) |
| 🐧 Linux 上的工具 | [linux/](linux/README.md) |
| 按需求找一套工具（如「Mac 上复现树莓派类机器人项目」） | [recipes/](recipes/README.md) |
| 某个工具的详细说明、注意事项、替代品 | [tools/](tools/README.md) |

跨平台的工具在每个系统页里都会列出，「平台」列用 🍎🪟🐧 标明支持哪几个系统。每个条目带「验证日期」，记录最后一次核对官网的时间，用来判断信息是否过时。

## 背景与目标

起因是复现 [microduck](https://github.com/fanhao375/microduck-replica) 时，开发机是 Mac，教程用的却是 Windows 上的烧录软件，只好另找替代品（balenaEtcher）。这类「换个系统就找不到对应工具」的问题很常见，所以把踩过的工具和坑整理成一个公开仓库：工具失效或更新时，大家可以一起改。

## 范围

| 项目 | 内容 |
|---|---|
| 当前准备做 | 按系统收录工具（系统镜像烧录、终端与开发基础、Mac 效率、AI 与远程连接、代理与密码管理，后续补深度学习环境、机器人与嵌入式）；按需求给出工具组合；记录实操案例 |
| 当前不做 | 安装与配置教程；破解版和盗版软件 |
| 主要约束 | 平台、费用、许可必须来自官网或官方仓库，查不到的标「待核实」 |

## 当前成果

macOS 页收录了 18 个工具（多数是作者本机在用的），其中 6 个有详细卡片；Windows 与 Linux 页只有烧录类的少量示例；另有 3 份需求清单草稿和 1 篇案例。深度学习环境、机器人与嵌入式两类尚未开始。

## 许可证

文档内容采用 [CC BY 4.0](LICENSE)；若日后加入脚本，脚本采用 [MIT](LICENSE-MIT)。

## English summary

setup-cookbook is a community-maintained catalog of developer and everyday tools, organized by operating system (macOS, Windows, Linux). Each entry says what the tool is, which platforms it supports (🍎🪟🐧), its cost, and when it was last verified. It also collects short "recipes" (tool sets for a given need) and write-ups such as flashing OS images from a Mac when the tutorial assumes Windows. The content is mostly in Chinese for now; English pull requests and issues are welcome. If a tool breaks or a link dies, please open an issue or PR. Installation and configuration guides are out of scope for now.
