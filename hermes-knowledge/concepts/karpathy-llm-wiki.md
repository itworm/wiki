---
title: Karpathy LLM Wiki——知识库的复利增长模型
created: 2026-07-08
updated: 2026-07-08
type: concept
status: current
---

# Karpathy LLM Wiki——知识库的复利增长模型

> Andrej Karpathy 提出的 LLM Wiki 理念：LLM 不再是临时检索工具，而是专职知识工程师。Obsidian 是 IDE，LLM 是程序员，Wiki 是代码库。

---

## 核心洞见：无状态 RAG vs 复利知识库

| 维度 | 传统 RAG | LLM Wiki |
|------|---------|----------|
| 知识定位 | 每次问答临时检索 | 一次性编译，永久复用 |
| 积累机制 | 无积累 | 每次录入/提问都在完善 |
| 检索方式 | 扫描原始文档 | 查询已编译的 Wiki |
| 维护成本 | 低（无需维护库） | 极低（LLM 自动维护） |
| 输出质量 | 每次推导，不稳定 | 越用越准，复利增长 |
| 代表工具 | NotebookLM、ChatGPT 文件上传 | Karpathy Gist、sage-wiki |

**核心隐喻：** 传统 RAG 像每次去图书馆翻书找答案；LLM Wiki 像先把书读一遍写成笔记，以后只看笔记。

## 三层架构

```
原始资料层 (Raw Sources) ← 不可变，仅 LLM 读取
        ↓
知识库层 (The Wiki)       ← LLM 持续编辑，多类型页面
        ↑ 规则驱动
规则配置层 (The Schema)    ← CLAUDE.md / AGENTS.md 等
```

## 三大操作闭环

**Ingest（录入）** → 新资料入 raw，LLM 读取→生成摘要→更新关联页面→更新索引
**Query（提问）** → 仅检索 Wiki 已编译内容，高价值问答结论回存
**Lint（体检）** → 定期巡检：冲突/过时/孤立/缺失，输出补充建议

Hermes 当前的 `wiki-harness.md`（宪法）和 `wiki_lint.py`（体检脚本）在理念上与 LLM Wiki 的 Schema + Lint 高度一致，但 LLM Wiki 提供了更系统的顶层理论框架。

---

## 对本知识库的价值

| 本知识库已有 | LLM Wiki 补充的框架 |
|------------|-------------------|
| 具体实操方案（搭建指南、AutoCLI、幻觉分析） | 顶层哲学：知识是"编译一次永久复用"的资产 |
| 分散的 Ingest/Lint/Query 操作 | 三者闭环的系统化论述 |
| wiki-harness.md（实践层面的宪法规约） | Schema 层的理论阐释 |
| Git 同步用于版本管理 | 知识库即代码库的理论基础 |

---

## 关联页面

- [[concepts/myknowledge-methodology|知识治理方法论]] — Wcof 的四原则四步法，与 Karpathy 的 Schema 理念互补
- [[concepts/hermes-kb-guide|Hermes 知识库搭建指南]] — Hermes 实操落地，LLM Wiki 架构的具体实现
- [[concepts/ai-kb-hallucination-solutions|AI知识库幻觉原理与应对方案]] — 传统 RAG 的缺陷分析，与 LLM Wiki 的"无状态 vs 复利"互为印证
