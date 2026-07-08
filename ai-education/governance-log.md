# Governance Log — AI 教育知识库

> 治理记录：健康检查、结构性变更、发现但暂不处理的问题。
> 结构性变更同时写入 `log.md`。超过 500 条时轮转。

## [2026-06-02] restructure | Phase 1 — 知识库骨架升级

### 变更
- 创建 `system/wiki-harness.md` — 知识库宪法
- 创建 `system/wiki-governance.md` — 治理细则
- 创建 `moc/ai-education.md` — AI 教育检索地图
- 创建 `governance-log.md` — 本日志

### 待处理问题
| 问题 | 原因 | 建议下一步 |
|------|------|-----------|
| 现有 13 个页面缺少 `status`/`domain`/`scope` 等 metadata | 旧版 metadata 字段不同 | 下次 ingesting 时逐步补齐；按 page threshold 分批更新 |
| 部分 `raw/` 文章已提炼为概念页，但原文尚未标注 `status: archive` | 不紧急，不阻塞检索 | 随健康检查逐步处理 |

## [2026-06-02] fix | 清除分类错误
- 入库了3篇不属于 ai-education 领域的文章（Hermes知识库搭建类），已删除
- 教训：入库前需严格判断 scope，不能用户发了就收

## [2026-07-07] lint | 健康检查
- 共扫描 54 个页面
- ⚠️ 孤立页: 7 个
  - [[district-ai-evaluation|district-ai-evaluation]] — 没有被任何页面引用
  - [[log|log]] — 没有被任何页面引用
  - [[SCHEMA|SCHEMA]] — 没有被任何页面引用
  - [[system/wiki-harness|wiki-harness]] — 没有被任何页面引用
  - [[system/wiki-governance|wiki-governance]] — 没有被任何页面引用
  - [[concepts/hk-digital-edu-blueprint|hk-digital-edu-blueprint]] — 没有被任何页面引用
  - [[concepts/5-country-uni-ai-policy|5-country-uni-ai-policy]] — 没有被任何页面引用
- 🔗 断链: 57 个
  - [[raw/articles/2024-11-28-education-ai-agent-review]] — 目标页面不存在
  - [[concepts/ai-education-action-plan\\]] — 目标页面不存在
  - [[../../cases/yong-ai/index\\]] — 目标页面不存在
  - [[raw/articles/2026-06-05-gaokao-450k-drop-education-trends]] — 目标页面不存在
  - [[concepts/333-evaluation-framework\\]] — 目标页面不存在
  - [[raw/articles/2026-06-11-gaokao-reform-ai-era]] — 目标页面不存在
  - [[raw/articles/2026-06-29-wenke-ai-era-research-paradigm]] — 目标页面不存在
  - [[concepts/ai-era-gaokao-reform\\]] — 目标页面不存在
  - [[raw/articles/2026-04-01-education-digitalization-deployment]] — 目标页面不存在
  - [[raw/articles/2026-06-17-loop-engineering-ima]] — 目标页面不存在
  - [[concepts/ai-education-misuse-analysis\\]] — 目标页面不存在
  - [[raw/articles/2026-06-02-edu-tech-automation-obsession]] — 目标页面不存在
  - [[concepts/ai-lesson-prep-methodology\\]] — 目标页面不存在
  - [[concepts/ai-learning-methodology\\]] — 目标页面不存在
  - [[raw/articles/2026-05-31-ai-exam-review-courseware]] — 目标页面不存在
  - [[concepts/ai-two-mode-collaboration\\]] — 目标页面不存在
  - [[concepts/ai-cannot-solve-motivation\\]] — 目标页面不存在
  - [[concepts/ai-edu-three-routes\\]] — 目标页面不存在
  - [[raw/articles/2026-06-04-edtech-global-trends]] — 目标页面不存在
  - [[raw/articles/2026-02-22-teacher-ai-socratic]] — 目标页面不存在
  - [[concepts/ai-automation-century-myth\\]] — 目标页面不存在
  - [[raw/articles/2026-05-10-ai-two-mode-collaboration]] — 目标页面不存在
  - [[raw/articles/2026-04-10-ai-education-action-plan]] — 目标页面不存在
  - [[raw/articles/2026-06-12-ai-edu-three-routes]] — 目标页面不存在
  - [[raw/articles/2026-05-08-ai-education-analysis]] — 目标页面不存在
  - [[concepts/ai-exam-review-courseware\\]] — 目标页面不存在
  - [[raw/articles/2026-01-06-forbes-education-trends]] — 目标页面不存在
  - [[raw/articles/2026-05-12-ai-learning-methodology]] — 目标页面不存在
  - [[concepts/create-thought-space\\]] — 目标页面不存在
  - [[hermes-autocli-workflow]] — 目标页面不存在
  - [[concepts/teacher-ai-socratic-method\\]] — 目标页面不存在
  - [[../../cases/chuang-ai/index\\]] — 目标页面不存在
  - [[concepts/teacher-ai-application-guidelines\\]] — 目标页面不存在
  - [[raw/articles/2026-06-30-khan-academy-ai-motivation-gap]] — 目标页面不存在
  - [[wikilinks]] — 目标页面不存在
  - [[concepts/loop-engineering-framework\\]] — 目标页面不存在
  - [[concepts/wenke-wise-classroom-research\\]] — 目标页面不存在
  - [[concepts/ai-era-teacher-two-fates\\]] — 目标页面不存在
  - [[raw/articles/2026-06-24-disappearing-middle-layer-teachers]] — 目标页面不存在
  - [[raw/articles/2026-04-15-southern-daily-ai-general-education]] — 目标页面不存在
  - [[concepts/ai-general-education-literacy\\]] — 目标页面不存在
  - [[raw/articles/2026-03-26-tianli-brain-nature-index]] — 目标页面不存在
  - [[raw/articles/2026-parallelism-learning-theory]] — 目标页面不存在
  - [[concepts/ai-education-current-state\\]] — 目标页面不存在
  - [[concepts/education-ai-agent-review\\]] — 目标页面不存在
  - [[../../cases/hu-ai/index\\]] — 目标页面不存在
  - [[raw/articles/2026-01-22-teacher-ai-guidelines]] — 目标页面不存在
  - [[concepts/china-education-macro-trends\\]] — 目标页面不存在
  - [[concepts/ai-era-learning-theory\\]] — 目标页面不存在
  - [[raw/articles/2026-ai-era-learning-theory]] — 目标页面不存在
  - [[concepts/2026-education-trends\\]] — 目标页面不存在
  - [[concepts/tianli-brain-nature-case\\]] — 目标页面不存在
  - [[raw/articles/2026-05-06-ai-lesson-prep-methodology]] — 目标页面不存在
  - [[hermes-kb-guide]] — 目标页面不存在
  - [[raw/articles/2026-06-29-ai-edu-sixteen-mistakes]] — 目标页面不存在
  - [[knowledge-governance-methodology]] — 目标页面不存在
  - [[页面]] — 目标页面不存在
