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
