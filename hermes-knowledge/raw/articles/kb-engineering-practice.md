---
source_url: https://www.woshipm.com/ai/6427281.html
source_name: 人人都是产品经理
author: Sean
ingested: 2026-07-04
note: 三部曲第二篇，工程实操篇
---
# 3个脚本、4个Skill、3层防线：AI知识库的工程化实践

作者：Sean

## 目录设计：从按主题分改为按状态分

`Inbox → Processed → Review → Archives`

目录即状态——文件在哪里就代表它走到哪一步，不用额外加布尔字段。

## 预处理脚本三连

1. **batch_ai_process** — 原文→结构化笔记
2. **validate_notes** — 校验元数据完整性
3. **batch_fix_notes** — 自动修复校验问题

## 四个Skill的演进顺序

deep-discuss（单篇深度讨论）
→ topic-deep-discuss（同主题多篇聚合）
→ card-govern（知识网络治理）
→ kb-apply（知识库输出检验）

## 三层防线

- 脚本层：守住格式（validate + fix）
- Skill层：守住结构（card-govern）
- Dataview层：守住全局（全景视图）

## 准入准出条件

在每两个流程节点之间加检查点——阶段N的准入条件是"阶段N-1已完成并盖章"，准出条件是"本阶段产物已锁定"。防止LLM在长流程中"漂移"。
