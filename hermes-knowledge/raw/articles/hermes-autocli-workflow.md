---
source_url: https://www.toutiao.com/article/7630378445352354344/
source_name: 今日头条
author: 职场AI效率指南
ingested: 2026-06-02
---
# Hermes+AutoCLI+Obsidian：打造自动入库、自动整理、自动微信汇报的知识系统

作者：职场AI效率指南

## 三步流程

```
定时抓取信息 → LLM Wiki 编译 → 微信汇报入库结果
```

## 核心价值
> 最值钱的不是自动化，而是系统感。
四个环节被打通：AutoCLI 抓 → Hermes 编 → Obsidian 看 → 微信报。

## 与本项目的映射
| 原文方案 | 本系统实现 |
|---------|-----------|
| AutoCLI 抓取 X 推文 | RSS 5 源 + Tavily 搜索 |
| Obsidian 存储 | llm-wiki 知识库 |
| LLM Wiki 梳理 | wiki-harness 治理入库 |
| 微信日报 | AI 教育日报（含点评） |
| 每日定时 | 7:45 RSS + 8:00 日报 + 每周一白名单 |
