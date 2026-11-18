# AI 工具与远程连接（macOS）

> AI 编程工具的管理，以及 SSH 与异地组网等远程连接工具。

| 工具 | 平台 | 用途 | 费用 | 验证 | 详情 |
|---|---|---|---|---|---|
| [CC Switch](https://ccswitch.io/) | 🍎🪟🐧 | 集中管理并一键切换 Claude Code、Codex、Gemini CLI 等的服务商配置 | 免费开源 | 可用 · 2026-11-18 | [卡片](../tools/cc-switch.md) |
| [DeepSeek Harness（dsh）](https://deepseek.com/en/harness/) | 🍎🪟🐧 | DeepSeek 的开源智能体运行环境，含命令行、本地网页和桌面应用 | 免费开源 | 可用 · 2026-11-18 | — |
| [FinalShell](https://www.hostbuf.com/) | 🍎🪟🐧 | 图形化 SSH 客户端，带 SFTP 和服务器监控 | 待核实 | 可用 · 2026-11-18 | [卡片](../tools/finalshell.md) |
| [ZeroTier](https://www.zerotier.com/) | 🍎🪟🐧 | 组建虚拟局域网，让异地设备像在同一网络里 | 免费增值 | 可用 · 2026-11-18 | — |

## 注意

- 注意：DeepSeek Harness 的桌面应用目前是开发者预览版，官方安装包只有 macOS（Apple 芯片）和 Windows；Linux 用命令行。官方仓库是 [deepseek-ai/deepseek-harness](https://github.com/deepseek-ai/deepseek-harness)。PyPI 上另有一个无关的 `deepseek-harness` 包，也提供 `dsh` 命令，别装错。
- ZeroTier 的个人免费档限制设备数和网络数，数额随时间调整，商用另有要求，以 [官网定价页](https://www.zerotier.com/pricing/) 为准。
- 注意：SSH 客户端会保存服务器地址和账号，只从官网下载。
