# 使用规范变更记录（CHANGELOG）

> 记录 `docs/usage-spec` 分支上每次版本变动。最新版本在最上方。

## v1.1 — 2026-10-27

### 变更内容
- 将"如何使用 dsh-dfy-Agent 仓库"打包为 DSH Skill。
- Skill 名称：`dsh-dfy-agent`；位置：`resources/runtime/office-skills/dsh-dfy-agent/SKILL.md`。
- 内容覆盖：仓库信息、分支约定、目录结构、使用规范版本管理、常用命令、工作流程、提交规范。
- 归档文件：`usage-spec-v1.1.md`。

### 操作记录
- 在 `office-skills` 下新建 `dsh-dfy-agent/SKILL.md`（YAML frontmatter + Markdown）。
- 预留 `references/` 子目录。
- 规范升版：v1.0 → v1.1。

## v1.0 — 2026-10-27

### 变更内容
- 初始建立使用规范与工作总结。
- 覆盖内容：
  - 仓库定位（DSH 智能体个人工作仓库）。
  - 本次工作总结（dsh-agent → dsh-dfy-Agent 改名、清空重建、骨架创建、分支预留）。
  - 分支规范、目录规范、工作流程、提交信息规范。
  - 快速参考命令。
- 归档文件：`usage-spec-v1.0.md`。

### 操作记录
- 仓库改名：`dsh-agent` → `dsh-dfy-Agent`
- 彻底清空旧历史，重建根提交 `bcfe3a7`
- 新增骨架：`README.md`、`AGENTS.md`、`main.py`、`.gitignore`
- 预留分支：`projects/example/v1`
- 使用规范分支：`docs/usage-spec`
