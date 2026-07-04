---
title: Hermes 知识库搭建指南
created: 2026-06-02
updated: 2026-06-02
type: concept
status: current
objects:
  - Hermes Agent
  - MEMORY.md
  - USER.md
---
# Hermes 知识库搭建指南

来自 AI 实战派老陈的实操方案。

## 架构
三层：应用层（CLI/WebUI）→ 检索层（MEMORY.md + 技能）→ 存储层（文件目录）

## 核心要点
- 数字前缀四大分类（不超过 5 个）
- MEMORY.md + USER.md 是底座
- 标签控制在 5 个以内
- 定时任务：每日整理 + 每周周报
- 多设备同步：Syncthing

## 与本知识库其他文章的关系
- [[myknowledge-methodology|知识治理方法论]] — 本文实操背后遵循的理论原则
- [[hermes-autocli-workflow|Hermes+AutoCLI 知识系统方案]] — 同类工作流的不同实现
