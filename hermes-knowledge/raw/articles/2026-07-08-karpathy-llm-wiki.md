---
source_url: https://www.toutiao.com/article/7659800113972150811
ingested: 2026-07-08
sha256: placeholder
---

# Karpathy 开源新方案：Agent+Obsidian，让 LLM 帮你构建复利知识库

**来源：** 今日头条 / AI架构之家
**日期：** 2026年

Andrej Karpathy 在 X 发文分享个人知识库管理方案：LLM+Agent+Obsidian，让大模型像程序员写代码一样持续维护结构化知识库。配套 Gist 发布两周 Star 破 5000。

## 核心思想

传统 RAG 本质是**无状态**的：上传文件→检索片段→生成回答。每次提问都要从零挖掘信息，不存在知识沉淀。整合5份文档观点时，模型每次要重新检索拼接。

Karpathy 的 **LLM Wiki** 思路：LLM 持续搭建、维护一套持久化维基库，由相互链接的 Markdown 文件组成。新增资料时，LLM 完整阅读、提取核心信息，整合进已有维基体系：更新实体词条、修订主题综述、标注新旧矛盾。

**核心差异：** 知识仅需编译一次，后续永久可用。

## 三层架构

**原始资料层（Raw Sources）** — 唯一数据源，存放原始素材。**不可变**：LLM 仅有读取权限，不修改原始文件。

**知识库层（The Wiki）** — 系统核心载体，LLM 全部工作输出。包含摘要页、实体词条、概念解读、对比分析、主题综述。

**规则配置层（The Schema）** — 指导 LLM 标准化工作的规则说明书。适配不同 Agent（CLAUDE.md / AGENTS.md 等）。

## 三大核心操作

**录入（Ingest）** — 将新素材放入原始资料目录，LLM 读取后生成摘要页，更新索引和关联页面。推荐单份逐个录入。

**提问（Query）** — LLM 仅检索 Wiki 内关联页面，整合输出。优质问答结论可回存 Wiki 生成新页面。

**体检（Lint）** — 定期全局巡检：观点冲突、过时信息、孤立页面、缺失引用。AI 输出后续补充建议。

## 金句

> **Obsidian 是 IDE，LLM 是程序员，Wiki 是代码库。**

## 关联工具

- sage-wiki（Go 语言，轻量化部署，支持 MCP Server）
- Claude Code Skill
- Obsidian Web Clipper（一键网页转 Markdown）
- Git 版本管理

原文链接：https://www.toutiao.com/article/7659800113972150811
