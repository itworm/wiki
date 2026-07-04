# Wiki Schema — 个人成长与效能

> 参照 `system/wiki-harness.md` 执行。本文件定义结构、标签和约定。

---

## Domain

个人成长、效率提升、副业创业、职业发展、学习方法和思维模型。

## Directory Structure

```
wiki/personal-growth/
├── system/               # 治理层
├── moc/                  # MOC 检索地图
│   └── personal-growth.md
├── raw/                  # 原始材料
│   └── articles/
├── concepts/             # 概念页
├── _archive/
├── SCHEMA.md
├── index.md
└── log.md
```

## Conventions

- 文件名：小写加连字符
- 每页正文前加 YAML frontmatter
- 每页至少 2 个 `[[wikilinks]]` 出链

## Metadata

```yaml
---
title: 页面标题
created: YYYY-MM-DD
updated: YYYY-MM-DD
domain: personal-growth
scope: entrepreneurship | productivity | career | learning | mindset
status: current
tags: []
sources: [raw/articles/source.md]
---
```

## Tag Taxonomy

- **领域**: entrepreneurship, productivity, career, learning, mindset, finance
- **类型**: article, book, course, method, case
- **来源**: book, blog, social-media, course
