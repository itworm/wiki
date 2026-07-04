---
title: 循环工程（Loop Engineering）——AI自动化系统的四大核心要素
created: 2026-06-23
updated: 2026-06-23
domain: ai-education
scope: research
topic: AI工作流设计方法论
primary_entry: 循环工程（Loop Engineering）的四大核心要素
secondary_entries:
  - Addy Osmani 循环工程框架
  - AI自动化系统的设计原则
  - 定时触发 + 持久记忆 + 技能沉淀 + 外部连接
status: current
tags: [ai, research, automation, workflow, design-pattern, loop-engineering]
sources: [raw/articles/2026-06-17-loop-engineering-ima.md]
objects:
  - Addy Osmani
  - Peter Steinberger
  - Boris Cherny (Claude Code)
  - 腾讯 ima Copilot
  - Loop Engineering
---

# 循环工程（Loop Engineering）—— AI 自动化系统的四大核心要素

## 核心主张

> 过去你控制 AI，现在你设计让 AI 持续自主运转的系统。
> 人从 AI 的"操作员"变成了系统的"设计者"。

循环工程（Loop Engineering）是 2026 年从 AI 编程社区兴起的设计范式，由 Peter Steinberger 提出、Google 工程师 Addy Osmani 系统化阐述。其本质是：**不再手动给 AI 写提示词，而是设计让 AI 自主运转的循环系统。**

---

## 四大核心要素（Addy Osmani）

| # | 要素 | 说明 | 在 Hermes 系统中的对应 |
|---|------|------|----------------------|
| 1 | **定时自动触发的任务** (Scheduled auto-triggered tasks) | 系统按预设频次自动启动，无需人工干预 | cron jobs（日报 8:30、预采集 7:45、碎片盒 10:30、金句 15:00） |
| 2 | **持久化的状态记忆** (Persistent state/memory) | 系统记住历史状态和决策，跨会话持续 | Memory（用户偏好 + 技术踩坑）、数据库持久化 |
| 3 | **技能知识沉淀** (Skill/knowledge accumulation) | 将成功流程固化为可复用的知识模块 | Skills（可复用的 workflow + 检查清单 + 脚本）、wiki 知识库 |
| 4 | **和外部工具打通的连接器** (Connectors to external tools) | 能读取/写入外部系统，不封闭运作 | 飞书 API、微信推送、Tavily 搜索、GitHub CLI、OpenAI API |

---

## 三个关键人物对循环工程的论述

### Peter Steinberger（起点）

> "你不该再手动给 AI 写提示词了，你该设计让 AI 自己给自己写提示词的循环。"

### Boris Cherny（Claude Code 负责人）

> "我已经不给 Claude 写提示词了，我让循环自己跑，由循环来决定下一步干什么，我的工作是写循环本身。"

### Addy Osmani（Google 工程师，系统化阐述者）

他总结了完整循环的四大核心要素（见上表），并将循环工程从编程领域推广到更广泛的工作流设计。

---

## 循环工程的内容创作应用（原文案例）

文章以循环工程的理念设计了「内容选题系统」的三层架构：

1. **素材仓库**：日常信息消费 → 一键存入知识库 + 打标签
2. **选题规则**：在 AI 的设定中明确你的标准和定位
3. **每日扫描**：让 AI 基于你的知识库 + 历史内容 + 定位，输出专属选题建议

这套架构的四个核心模块（定时触发、持久记忆、知识沉淀、外部连接）与循环工程的四要素一一对应，是循环工程从编程领域迁移到内容创作的实践案例。

---

## 对区域电教站的意义

循环工程框架为**教育数字化的自动化工作流设计**提供了一个清晰的理论参考：

- **教育信息采集系统**：定时自动抓取（要素1）→ 持久跟踪（要素2）→ 技能沉淀为可复用的教研流程（要素3）→ 连接飞书/微信推送（要素4）
- **教师专业发展系统**：定时触发教研任务 → 记忆教师成长轨迹 → 沉淀教学案例 → 连接课堂工具
- **评估框架**：在评估 AI 教育项目时，可以检视其是否具备完整的四个循环要素，避免"有触发无沉淀"或"有知识无连接"的半成品架构

---

## 关联页面

- [[concepts/ai-two-mode-collaboration|两种AI协同模式：内容生产者 vs 思维伙伴]] — 思维伙伴型AI需要循环工程来持续运转
- [[concepts/teacher-ai-socratic-method|苏格拉底式AI交互法]] — 追问循环也是一种 Loop Engineering
- [[concepts/ai-education-current-state|AI教育当前阶段分析]] — 从浅层辅助到系统化设计的演进方向
- [[concepts/ai-learning-methodology|AI学习路径与方法]] — "先上路才会学"，与"先设计循环"的思路互补
- [[moc/ai-education|AI教育检索地图]]
