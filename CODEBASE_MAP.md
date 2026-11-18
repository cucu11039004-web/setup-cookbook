# 代码地图

setup-cookbook 是按操作系统整理开发与日常工具的公开文档仓库，面向需要在 macOS、Windows、Linux 之间找对应工具的开发者，产出是工具条目、需求清单和案例文档。

本文件让人和 AI 在修改前先定位改动区域：目录各自装什么，哪类需求通常落在哪里。项目目标见 [README.md](README.md)，环境与协作约定见 [AGENTS.md](AGENTS.md)。

## 目录结构

- `macos/` ——🍎 macOS 工具，按用途分文件
  - `README.md` ——分类索引与表格列说明
  - `flashing.md` ——烧录与系统镜像
  - `dev-basics.md` ——终端与开发基础
  - `efficiency.md` ——效率与系统增强
  - `ai-remote.md` ——AI 工具与远程连接
  - `network-security.md` ——代理与密码管理
- `windows/` ——🪟 Windows 工具（目前只有 `flashing.md` 示例）
- `linux/` ——🐧 Linux 工具（目前只有 `flashing.md` 示例）
- `tools/` ——工具卡片，一个工具一个文件；`_template.md` 是卡片模板
- `recipes/` ——按需求组合的工具清单
- `docs/` ——独立成篇的案例与笔记
- `.github/` ——Issue 表单与 PR 模板
- `CONTRIBUTING.md` ——反馈与贡献流程
- `LICENSE`、`LICENSE-MIT` ——文档（CC BY 4.0）与脚本（MIT）的许可

## 各部分职责

| 分组 | 涉及位置 | 职责 | 典型改动 |
|---|---|---|---|
| 系统页 | `macos/`、`windows/`、`linux/` | 每个系统下的工具摘要表，一行一个工具，标明平台、费用和验证日期 | 新增工具行、更新验证日期、标记工具失效 |
| 工具卡片 | `tools/` | 单个工具的详细信息：用途、平台差异、注意事项、替代品 | 新增卡片、更正平台或费用、补充踩坑 |
| 需求清单 | `recipes/` | 针对一类需求给出一组工具及选择理由 | 新增场景清单、替换失效工具 |
| 案例与笔记 | `docs/` | 带上下文的实操记录，如 Mac 上烧录 microduck 镜像 | 补充案例、修正过时内容 |
| 协作 | `.github/`、`CONTRIBUTING.md` | 让别人能反馈失效、提交新条目 | 调整表单字段、更新贡献流程 |

一个跨平台工具改动时，通常要同时改它的卡片和每个系统页里的对应行。
