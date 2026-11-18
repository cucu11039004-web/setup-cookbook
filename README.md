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

跨平台的工具在每个系统页里都会列出，「平台」列用 🍎🪟🐧 标明支持哪几个系统。

## 背景与目标

起因是复现 [microduck](https://github.com/fanhao375/microduck-replica) 时，开发机是 Mac，教程用的却是 Windows 上的烧录软件，只好另找替代品（balenaEtcher）。这类「换个系统就找不到对应工具」的问题很常见，所以把踩过的工具和坑整理成一个公开仓库：工具失效或更新时，大家可以一起改。

## 范围

| 项目 | 内容 |
|---|---|
| 当前收录 | 系统镜像烧录、终端与开发基础、Mac 效率与系统增强、AI 工具与远程连接、代理与密码管理 |
| 计划补充 | 深度学习环境（CUDA、conda/uv、PyTorch、Docker 等）、机器人与嵌入式工具链 |
| 当前不做 | 安装与配置教程（先收录「有什么工具、做什么用」，配置另行整理）；破解版和盗版软件 |

## 当前成果

骨架和样板条目已就位：macOS 页收录了 18 个工具（多数是作者本机在用的），其中 6 个有详细卡片；Windows 与 Linux 页只有烧录类的少量示例；另有 3 套需求清单草稿和 1 篇案例。其余分类仍待补充，目录里标明了「待补充」。

## 参与维护

发现工具失效、链接 404、信息过期，或想推荐新工具，请看 [CONTRIBUTING.md](CONTRIBUTING.md)。每个条目都带「验证日期」，超过一年没人确认的条目会被标为待核实。

## 文档入口

| 文档 | 用途 |
|---|---|
| [CONTRIBUTING.md](CONTRIBUTING.md) | 如何反馈失效、添加条目、提交 PR |
| [AGENTS.md](AGENTS.md) | 工作环境、协作与 Git 提交约定 |
| [CODEBASE_MAP.md](CODEBASE_MAP.md) | 目录结构与各部分职责 |
| [GLOSSARY.md](GLOSSARY.md) | 仓库里的术语和标记含义 |
| [docs/](docs/README.md) | 独立成篇的案例与笔记 |

## 许可证

文档内容采用 [CC BY 4.0](LICENSE)；若日后加入脚本，脚本采用 [MIT](LICENSE-MIT)。

## English summary

setup-cookbook is a community-maintained catalog of developer and everyday tools, organized by operating system (macOS, Windows, Linux). Each entry says what the tool is, which platforms it supports (🍎🪟🐧), its cost, and when it was last verified. It also collects short "recipes" (tool sets for a given need) and write-ups such as flashing OS images from a Mac when the tutorial assumes Windows. The content is mostly in Chinese for now; English pull requests and issues are welcome. If a tool breaks or a link dies, please open an issue or PR following [CONTRIBUTING.md](CONTRIBUTING.md). Installation and configuration guides are out of scope for now.
