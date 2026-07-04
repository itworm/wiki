# Wiki Schema — AI 教育知识库

> 参照 `system/wiki-harness.md` 执行。本文件定义结构、标签和约定。

---

## Domain

人工智能在教育领域的应用，涵盖：课堂教学、教育数字化政策、AI 教学工具、大模型教育场景、智慧教育案例。

## Directory Structure

```
wiki/ai-education/
├── system/               # 治理层：宪法 + 细则（只存放规则文件）
│   ├── wiki-harness.md   # 宪法 — 最高执行规范
│   └── wiki-governance.md # 细则 — 晋级/模板/健康检查
├── moc/                  # MOC 检索地图（按主题组织入口）
│   └── ai-education.md   # AI 教育总览
├── raw/                  # 原始材料（不可修改）
│   └── articles/
├── entities/             # 结构化实体页
├── concepts/             # 结构化概念页
├── comparisons/          # 对比分析页
├── queries/              # 已归档查询
├── _archive/             # 已归档/过期页面
├── SCHEMA.md             # 本文件
├── index.md              # 页面索引（derived output）
├── log.md                # 结构性变更日志
└── governance-log.md     # 治理记录日志
```

## Conventions

- 文件名：小写加连字符，如 `ai-classroom-tools.md`
- 每页正文前加 YAML frontmatter
- 使用 `[[wikilinks]]` 关联相关笔记（每页至少 2 个出链）
- 更新页面时更新 `updated` 日期
- 每新页面必须加入 `index.md`
- 每次结构性变更写入 `log.md`
- 每次治理动作写入 `governance-log.md`

## Metadata

```yaml
---
title: 页面标题
created: YYYY-MM-DD
updated: YYYY-MM-DD
domain: ai-education
scope: policy | product | tool | research | practice
topic: 主题名
primary_entry: 主入口（用户怎么找回这篇材料）
secondary_entries:
  - 辅入口1
  - 辅入口2
status: current               # draft | current | archive | unknown
tags: [ai, education, tool]
sources: [raw/articles/source.md]
objects:
  - 机构/人名/产品/事件
---
```

### status 生命周期

| 值 | 含义 | 可引用？ |
|----|------|---------|
| `draft` | 正在整理，待确认 | ❌ 不可作为最终口径 |
| `current` | 当前有效 | ✅ 可查询、引用 |
| `archive` | 历史材料，追溯用 | ⚠️ 仅作为背景 |
| `unknown` | 未整理，尚未判断 | ❌ 不默认引用 |

### scope 枚举

| scope | 说明 | 示例 |
|-------|------|------|
| policy | 政策、标准、考试安全 | 教育部行动计划 |
| product | 产品、公司、平台 | 网易有道、SchoolAI |
| tool | 教学工具、AI 工具 | 演示工具、端侧引擎 |
| research | 研究、理论、趋势 | 教育大模型理论 |
| practice | 课堂实践、教学案例 | AI 进课堂 |

## Tag Taxonomy

- **领域**: ai, education, policy, tool, case
- **场景**: classroom, teacher, student, curriculum, assessment
- **技术**: llm, agent, multimodal, adaptive, nlp, edge-ai
- **机构**: company, research, government, school
- **类型**: product, research-paper, news, opinion, case-study, standard
- **地域**: china, global

## Page Thresholds

- 同一概念出现在 2+ 来源中 → 创建概念页
- 单篇来源的核心信息 → 追加到已有页面
- 单次提及 → 不创建页面
- 页面超 200 行 → 拆分子页面

## Update Policy

新信息与已有内容冲突时：
1. 按时间优先（更新信息覆盖旧信息）
2. 真实矛盾则两说并存，标注日期和来源
3. 在 frontmatter 中标记 `confidence: low` 或 `contested: true`
4. 在 governance-log.md 中记录冲突

## Query Priority

Agent 回答问题时：
1. 先判断 `scope`，读对应 MOC 入口
2. 优先读 `status: current` 的页面
3. `archive` 和 `unknown` 仅作为背景
