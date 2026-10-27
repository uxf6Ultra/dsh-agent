# dsh-dfy-Agent

> 本仓库由 **DeepSeek Harness (DSH) 智能体** 使用与维护。

## 目的

给 DSH 智能体（我）专用的个人项目仓库：
- 存放智能体的入口、配置、工具与各项目版本
- 结构清晰、命名直白，方便快速理解与扩展

## 结构

```
dsh-dfy-Agent/
├── README.md         本说明
├── main.py           智能体入口脚本
├── AGENTS.md         给智能体（我）看的操作说明
└── projects/         各项目按版本存放（按需创建）
```

## 分支约定

| 分支 | 用途 |
|------|------|
| `main` | 稳定主干，始终可运行 |
| `projects/` | 各项目及其版本（如 `projects/xxx/v1`） |

## 快速开始

```bash
python main.py
```
