# Wiki Log — Hermes 知识管理工作流

## [2026-06-02] create | 知识库初始化
- 创建 SCHEMA.md、index.md、log.md
- 录入 3 篇原文 + 3 个概念页

## [2026-06-02] move | 从 ai-education 迁移至此
- 因不属 AI+教育领域，从 `~/wiki/ai-education/` 迁移至本目录
- 补充 [[wikilinks]] 互链
- 创建 moc/hermes-knowledge.md 检索地图
- 升级 index.md 为表格引用格式

## [2026-07-04] ingest | 《Skill 验证、版本与交接》
- 保存原文 raw/articles/skill-verification-handover.md
- 创建概念页 [[concepts/skill-engineering-methodology|Skill 工程方法论]]
- 关联 [[concepts/hermes-kb-guide]]

## [2026-07-08] ingest | AI知识库幻觉原理与应对方案
- 来源：人人都是产品经理（邹叔），头条原文
- 保存原文 raw/articles/2026-07-08-ai-kb-hallucination-analysis.md

## [2026-07-04] ingest | 《从囤积到经营：认知资产库构建》
- 保存原文 raw/articles/from-hoarding-to-cultivating.md
- 创建概念页 [[concepts/cognitive-asset-framework|认知资产库构建框架]]
- 关联已有 3 篇概念页（[[wikilinks]] 已补充）

## [2026-07-04] ingest | 《AI工程的第四次跃迁》
- 保存原文 raw/articles/ai-engineering-four-evolutions.md
- 创建概念页 [[concepts/ai-engineering-four-evolutions|AI工程四次跃迁]]
- EXTEND——与 [[concepts/loop-engineering-framework|循环工程框架]] 形成互补
- 创建概念页 [[concepts/ai-kb-hallucination-solutions|AI知识库幻觉原理与应对方案]]
- 核心内容：LLM"接梗王"本质 → 文档切块上下文断裂 → 三套实操方案对比 → 数据外挂法提升准确率至95%
- 关联：[[concepts/myknowledge-methodology]] [[concepts/hermes-kb-guide]]

## [2026-07-08] ingest | Karpathy LLM Wiki——知识库的复利增长模型
- 来源：今日头条 / AI架构之家，介绍 Karpathy LLM Wiki 理念
- 保存原文 raw/articles/2026-07-08-karpathy-llm-wiki.md
- 创建概念页 [[concepts/karpathy-llm-wiki|Karpathy LLM Wiki——知识库的复利增长模型]]
- 核心框架：三层架构（Raw→Wiki→Schema）→ 三大操作（Ingest→Query→Lint）→ 知识复利闭环
- 本知识库定位：LLM Wiki 提供理论顶层设计，与已有实操方案互补
- 关联：[[concepts/myknowledge-methodology]] [[concepts/hermes-kb-guide]] [[concepts/ai-kb-hallucination-solutions]]

## [2026-09-29] extend | 追加 SECI 模型至「知识治理方法论」（方案 A）
- 来源：微信公众号「AI4KIDs」《云笔记赋能教师个人知识管理》（2025-05-31，源自杭州市 2019 年教师现代教育技术小课题 19X17004）
- **评估结论：不整篇入库**——工具层落点是"云笔记"（印象笔记/有道云笔记），**全文无一次提到 AI**，已被当前"AI+知识库"实践超越；且 采集→组织→深化→应用 循环与本库已有内容重叠
- **执行方案 A（萃取增量）**：
  - 追加 **SECI 模型**（野中郁次郎：隐性↔显性知识四象限——社会化/外在化/组合化/内在化）至 [[concepts/myknowledge-methodology|知识治理方法论]]
  - 建立理论关联：本库"持续编译"原则本质是**最大化「外在化」与「组合化」**（碎片盒捕获隐性经验 → wiki 结构化组合 → Agent 萃取）
  - 追加 **「思维支架」五问**（提炼/联结/批判/迁移/元认知）
  - 保存溯源 raw：raw/articles/2026-05-31-yunbiji-teacher-pkm.md（frontmatter 标注"仅萃取 SECI 模型，未整体入库"）
- **顺带修复本库索引漂移**（发现时已严重：计数停在 5，实际 10 页）：
  - index.md：计数 5→10；补录遗漏 raw（kb-engineering-practice）；清除 6 处 `🟢` 污染 + 2 处转义残留（`\|`）
  - moc/hermes-knowledge.md：计数 5→10；「我该从哪里找」从 5 页补全至 10 页；「三条脉络」更新（补 Sean 系列与 Karpathy 脉络）
