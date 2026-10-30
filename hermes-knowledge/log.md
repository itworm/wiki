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

## [2026-10-26] distribute | 碎片摘录集分拣：知识库建设主题并入 4 页
- 素材：`#人机共生的知识库构建之路.txt`，raw 存档 `raw/articles/2026-10-26-fragments-kb-construction.md`（6089B，真实 sha256）
- **4 页追加**：
  - [[concepts/karpathy-llm-wiki]] 加 **「LLM 的角色是图书管理员，不是拆装工」**:知识库应是**人读人写的 Wiki,而不是机器切碎的数据**;AI 是**图书管理员**(整理/关联/维护),不是每次现拆现装;四行对照表(拆装工 vs 图书管理员)
    - ⭐ "图书管理员比程序员更能说明问题:程序员写新代码,图书管理员**不写书,只让已有的书好找、好放、不重、不缺**"
  - [[concepts/cognitive-asset-framework]] 把原 3 行「多角色LLM」**展开为完整章节**(三阶段×做什么×对应 Karpathy 的 Ingest/Lint;**指出"讨论层"是 Karpathy 原框架没有的扩展,正是把 AI 从维护工具变成思维伙伴的关键一步**)
    - 新增 **「从工具到智能体」认知跃迁**:当工具解决问题="有没有知识"(存量)→ 当智能体解决="知识有没有用有没有长"(增量与质量);AI 比喻从**仓库**变成**专家+管家**;**"抛弃软件应用思维,拥抱AI伙伴"**
    - 新增 **「我」不是缺位而是在场**:AI 承担整理关联巡检→人承担"值不值得要/认不认同";**证据=入库请求从"xx,入库"变成"xx,判断入库价值"(人从搬运工变守门人)**
    - 新增 **「让AI定期评价你」**:工作流水帐挪飞书+每日反思 → AI 提炼工作情况提建议;**把反思从靠自觉变成有外部观察者**
  - [[concepts/myknowledge-methodology]] 加 **反面:收藏模式的四种失败** — ①**认知流畅性错觉**("点下收藏那一瞬间,大脑给你快感,好像知识已经是你的了")+**"只拿了个压缩包,根本没解压"** ②**数字骨灰** ③**知道在哪而非知道是什么** ④**"互联网抹平的是信息差,不是知识差,更不是能力差"**(三层差分表)
    - 同页加 **对策:让"待读"有压力**(书签栏挂高高的→每天必看→产生压力;⭐**不是靠自律,是靠环境设计**)
  - [[concepts/skill-engineering-methodology]] 加 **⭐⭐真正的提效=把经验沉淀为Skill**:"真正的提效,不是写更多Prompt,而是把经验沉淀为Skill"/"AI时代的核心竞争力,是把重复劳动变成**数字资产**的能力";六维对照表;**关键差别在"是否可积累"——效率提升是一次性的,资产是可以反复生息的**;判断标准=**这件事我是不是第二次做了?**
