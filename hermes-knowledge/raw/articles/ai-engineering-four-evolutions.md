---
source_url: https://www.woshipm.com/ai/6414536.html
source_name: 人人都是产品经理
author: 枝酒
ingested: 2026-07-04
---
# AI 工程的第四次跃迁：从 Prompt、Context、Harness 到 Loop Engineering

作者：枝酒 ｜ 来源：人人都是产品经理

## 核心论点

AI工程最值钱的能力一直在往外挪：Prompt（语言）→ Context（信息）→ Harness（控制）→ Loop（管理）。现在站上最外层的人是设计"循环"的人——把模糊需求拆成机器可执行的精准指令。

## 四次跃迁

| 阶段 | 时间 | 核心问题 | 稀缺能力 |
|------|------|---------|---------|
| Prompt Engineering | 2022 | 一轮对话里把事说清楚 | 语言能力 |
| Context Engineering | 2024-2025 | 模型此刻需要知道什么 | 信息筛选与组织 |
| Harness Engineering | 2026初 | 给Agent一套规矩和工具 | 控制论、规则设计 |
| Loop Engineering | 2026中 | 怎样让系统自己转 | 目标管理、管理学 |

## 关键引用

- **Peter Steinberger**（OpenClaw作者）："别一条条写提示词了，去设计一个循环"——X平台500万+浏览
- **Boris Cherny**（Anthropic）：代码100%由Claude Code产出，每天10-30个PR
- **Mitchell Hashimoto**（HashiCorp创始人）：Agent每次犯错不做手动修复，改Harness永久修复
- **Addy Osmani**：循环工程五要素（自动触发、worktree隔离、项目知识、MCP连接器、子Agent分工）
- **斯坦福+清华研究**：同一模型因Harness不同表现差6倍
- **LangChain**：Terminal Bench 2.0上仅改Harness从52.8%→66.5%

## 公式

Agent = Model + Harness（模型负责脑子，Harness负责规矩、工具、校验、边界）

## 最小可用循环四要素

触发 → 指令 → 状态文件（STATE.md）→ 验证门

## 三个坑

- Ralph Wiggum循环：看着在转，原地打转，烧钱
- 理解债务：代码能跑但没人懂，出事救不了
- 安全税：权限和密钥风险随自动化膨胀
