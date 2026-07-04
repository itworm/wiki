# Wiki Schema — Hermes 知识管理工作流

## Domain
Hermes Agent 知识库搭建方法、知识管理方法论、自动化工作流设计。

## Conventions
- 文件名：小写加连字符
- 每页正文前加 YAML frontmatter
- 使用 `[[wikilinks]]` 关联相关笔记
- 每新页面必须加入 index.md
- 每次操作写入 log.md

## Metadata
```yaml
---
title: 页面标题
created: YYYY-MM-DD
updated: YYYY-MM-DD
type: concept | article
status: current
objects:
  - 工具/人物/项目
---
```
