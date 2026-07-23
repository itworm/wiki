# Wiki Log — AI 教育知识库

> 按时间顺序记录所有操作。追加模式。超过 500 条时轮转。

## [2026-06-02] restructure | Phase 1 知识库骨架升级
- 创建 system/ moc/ 治理层
- 升级 SCHEMA.md / index.md

## [2026-06-02] clear | 清空内容
- 清空 raw/ entities/ concepts/ comparisons/ queries/
- 以后只保存精选内容（用户指定或白名单自动入库）

## [2026-06-02] ingest | 《AI 时代，构建本地AI知识库》
- 保存原文 raw/articles/2026-06-02-myknowledge-skill.md
- 创建概念页 [[knowledge-governance-methodology|知识治理方法论]]
- 本文是 Phase 1 骨架升级的蓝图

## [2026-06-02] ingest | 《用 Hermes Agent 搭建个人知识库》
- 保存原文 raw/articles/2026-06-02-hermes-kb-guide.md
- 创建概念页 [[hermes-kb-guide|Hermes 知识库搭建指南]]
- 同步话题：raw/articles/2026-06-02-myknowledge-skill.md（内容重复，跳过）

## [2026-06-02] note | 第2条文章已存在
- URL 7643322864422109737（Wcof myknowledge-skill）已于上一步入库，跳过

## [2026-07-04] ingest | 谷歌AI教育产品路线分析
- 概念提取入库，聚焦"AI是关系增强器"核心理念
- 保存原文 raw/articles/2026-07-04-google-ai-education-iste2026.md
- 创建概念页 [[concepts/ai-edu-product-strategy|AI教育产品路线：关系增强 vs 效率替代]]
- 原文AI痕迹较重，仅提取有价值观点

## [2026-06-02] ingest | 《Hermes+AutoCLI+Obsidian：打造自动入库...》
- 保存原文 raw/articles/2026-06-02-hermes-autocli-obsidian-kb.md
- 创建概念页 [[hermes-autocli-workflow|Hermes+AutoCLI 知识系统方案]]
- 本文是整个日报+知识库系统的起源文章

## [2026-06-02] fix | 清除分类错误的文章
- 老板指出：已入库的3篇文章（myknowledge-skill、Hermes搭建指南、AutoCLI方案）不属于AI+教育领域
- 已删除 3 个概念页 + 3 篇原文
- 已重置 index.md
- 已重写 MOC（清除所有过期引用）
- 教训：入库前必须判断 scope，不是用户发来的所有文章都放 ai-education

## [2026-06-03] ingest | 五部门印发《"人工智能+教育"行动计划》
- 来源：今日AI教育日报第3条
- 保存原文 [[raw/articles/2026-04-10-ai-education-action-plan|原文全文]]
- 创建概念页 [[concepts/ai-education-action-plan|"人工智能+教育"行动计划]]
- scope: policy — 国家AI教育顶层政策文件
- 本文件是AI教育知识库的首条精选入库内容

## [2026-06-03] ingest | 她说"看了个寂寞"，然后自己学会了AI
- 来源：人人都是产品经理（白名单），2026-05-12发布
- 保存原文 [[raw/articles/2026-05-12-ai-learning-methodology|原文全文]]
- 创建概念页 [[concepts/ai-learning-methodology|AI学习路径与方法]]
- scope: research — AI学习方法论研究
- 核心观点："不是学会了再上路，是上了路才会学"——对教师AI素养培训设计有直接启示

## [2026-06-03] ingest | 教师AI备课的正确"打开方式"
- 来源：微信公众号「AI在教育」（白名单），2026-05-06发布
- 保存原文 [[raw/articles/2026-05-06-ai-lesson-prep-methodology|原文全文]]
- 创建概念页 [[concepts/ai-lesson-prep-methodology|AI备课方法论]]
- scope: practice — AI辅助备课课堂实践
- 核心方法：先拆解课堂（学情预判→核心问题→问题链→课堂结构→活动设计）→ 再生成教案
- 可直接作为教师AI培训的实操课程素材

## [2026-06-03] ingest | 飞象老师5分钟生成互动试卷讲评课件
- 来源：微信公众号「良心为师」，2026-05-31发布
- 保存原文 [[raw/articles/2026-05-31-ai-exam-review-courseware|原文全文]]
- 创建概念页 [[concepts/ai-exam-review-courseware|AI试卷讲评互动课件]]
- scope: practice — AI工具辅助试卷讲评课堂实践
- 核心工具：国家中小学智慧教育平台 → 飞象老师（互动课件功能）
- 核心方法：三步法（上传材料→确认大纲→生成HTML互动课件）
- 亮点：零技术门槛、5分钟搞定、可因班施教实时调整

## [2026-06-03] ingest | AI教育真相：6000万师生仅获浅层辅助
- 来源：今日头条「预见未来Future」，2026-05-08发布
- 保存原文 [[raw/articles/2026-05-08-ai-education-analysis|原文全文]]
- 创建概念页 [[concepts/ai-education-current-state|AI教育当前阶段分析]]
- scope: research — AI教育现状批判性分析
- 核心判断：教育AI化处于"浅层应用遍地开花、深层变革尚未突破"阶段
- 未来方向："AI辅助、教师主导"模式——AI承担事务性工作，教师聚焦情感引导与思维启发
- 与[[concepts/ai-learning-methodology|AI学习路径与方法]]形成互补

## [2026-06-04] ingest | 美媒预测2026年六大教育趋势
- 来源：今日AI教育日报第3条（《中国教育技术装备》编译福布斯文章）
- 保存原文 [[raw/articles/2026-01-06-forbes-education-trends|原文全文]]
- 创建概念页 [[concepts/2026-education-trends|2026年六大教育趋势]]
- scope: research — 教育趋势预测
- 六大方向：AI智能体、AI素养、技能重塑、学习能力、游戏化体验式学习、以人为中心技能
- 对电教站价值：游戏化学习契合教研偏好、AI素养可提前规划区域课程、以人为中心技能支持教师不可替代性理念

## [2026-06-04] create | 教师创造思想空间——让学生成为思考的主体
- 来源：老板在阅读项飙"抓住"与"拉网"后的个人感悟转化
- 创建概念页 [[concepts/create-thought-space|教师创造思想空间]]
- scope: practice — 教学理念
- 灵感：项飙"创造思想空间"理念在教育中的转化——教师不应只是知识传递者，更应是思想空间的营造者
- 关联：[[concepts/ai-lesson-prep-methodology]] [[concepts/ai-exam-review-courseware]] [[concepts/ai-learning-methodology]]

## [2026-07-04] update | 补充李政涛"新智人"视角
- 概念页 [[concepts/ai-general-education-literacy]] 新增"从获得答案到提对问题"章节
- 新增人机协同/人机交互/人机共创三种能力定义

## [2026-07-04] ingest | 个人感悟：教师角色的重新定位
- 创建概念页 [[concepts/teacher-role-teaching-vs-education|AI时代教师角色的重新定位]]
- 核心命题：教书与育人分离，教师从知识传授转向三观/习惯/情绪/创新养成
- 关联 [[ai-era-teacher-two-fates]] [[ai-in-classroom]]

## [2026-07-04] update | 补充陈玉琨出处+"认知外包"概念
- UPDATE [[teacher-role-teaching-vs-education]]
- 补充陈玉琨"把教书交给机器，把育人留给教师"原文出处
- 新增刘大伟"认知外包"概念+UK研究数据
- 新增"三层人机协同边界"框架
- 来源：校长派微信公众号

## [2026-07-04] ingest | AI+HI人机协同递进模型
- 学术论文入库（《中小学信息技术教育》2026年6期）
- 保存原文 raw/articles/2026-07-04-ai-plus-hi-teacher-cognition.md
- 创建概念页 [[concepts/ai-plus-hi-collaboration-model|AI+HI人机协同递进模型]]
- 四阶段框架：事务型→情境型→实践型→协同型

## [2026-07-04] ingest | AI赋能新范式而非旧范式
- 概念提取入库，聚焦"教学范式先于技术"核心论点
- 保存原文 raw/articles/2026-07-04-ai-empower-new-paradigm.md
- 创建概念页 [[concepts/ai-empower-new-paradigm|AI赋能新范式而非旧范式]]

## [2026-07-04] ingest | AI原生教师公式（刘欣）
- 保存原文 raw/articles/2026-07-04-ai-native-teacher-formula.md
- 创建概念页 [[concepts/ai-native-teacher-formula|AI原生教师=教学系统设计内功×AI外功]]
- 核心公式：内功（教学系统设计能力）× 外功（AI工具能力）

## [2026-07-04] ingest | AI融合课四步改造法（刘欣实操案例）
- 保存原文 raw/articles/2026-07-04-liuxin-math-ai-case.md
- 创建概念页 [[concepts/ai-lesson-four-step-transformation|AI融合课四步改造法]]
- 四步：静态→动态 / 计算→建模 / 解题→出题 / 经验→数据
- 关联 [[ai-native-teacher-formula]]（同一作者，理论→实操）

## [2026-07-04] ingest | 后识字时代——阅读衰退与AI认知影响
- 译自《大西洋月刊》，万字长文
- 保存原文 raw/articles/2026-07-04-end-of-reading-atlantic.md
- 创建概念页 [[concepts/post-literacy-age-ai-impact|后识字时代——阅读衰退与AI认知影响]]
- 三条论据：AI摘要替代不了一手阅读 / 认知挣扎是学习必要条件 / 深度思维能力系统性衰退

## [2026-07-04] ingest | 高位转移——AI教育问题升维框架
- 保存原文 raw/articles/2026-07-04-high-level-shift-education.md
- 创建概念页 [[concepts/high-level-shift-education|高位转移——AI教育问题升维框架]]
- 核心框架：效率退潮→质量显形 / 技术止步→人性登场 / 工具退后→哲学升维

## [2026-07-04] ingest | 伟大事物——课堂中心与AI融合的哲学基础
- 保存原文 raw/articles/2026-07-04-palmer-great-things.md
- 创建概念页 [[concepts/great-things-classroom-center|伟大事物——课堂中心与AI融合的哲学基础]]
- 帕尔默《教学勇气》：让学科本身而非教师/学生居于课堂中心
- 关联 [[ai-lesson-four-step-transformation]]

## [2026-07-04] ingest | 持久行为改变的三个模型（概念提取）
- 概念提取入库：阶梯模型/社交磁力/要事为先
- 创建概念页 [[concepts/three-behavior-change-models|持久行为改变的三个模型]]
- 来源：Sean Young《如何想到又做到》，游戏化学习的理论根基

## [2026-07-04] ingest | 乘法算理大师——三年级AI智能体课堂实录
- 保存原文 raw/articles/2026-07-04-multiplication-ai-agent-case.md
- 创建案例页 [[cases/national/multiplication-ai-agent-case|乘法算理大师课堂实录]]
- 新增 cases/national/ 目录，收录全国优秀案例
- 关联 [[teacher-role-teaching-vs-education]] [[ai-lesson-four-step-transformation]] [[great-things-classroom-center]] [[high-level-shift-education]]

## [2026-06-04] ingest | AI时代呼唤新的学习理论
- 来源：微信公众号「教育技术学自留地」（白名单），2026年发布
- 保存原文 [[raw/articles/2026-ai-era-learning-theory|在人工智能时代，我们是否需要提出一种新的学习理论？]]
- 创建概念页 [[concepts/ai-era-learning-theory|AI时代呼唤新的学习理论]]
- scope: research — 学习理论
- 核心命题：行为主义/认知主义/建构主义已不足以解释AI时代的学习现象，需要整合性的新理论
- 关联：[[concepts/ai-education-current-state]] [[concepts/create-thought-space]] [[concepts/ai-learning-methodology]]

## [2026-06-04] update | AI时代呼唤新的学习理论 — 追加并行学习
- 追加来源 [[raw/articles/2026-parallelism-learning-theory|并行学习理论（Parallelism）]]
- 更新概念页 [[concepts/ai-era-learning-theory]]: 新增"一个具体的回答：并行学习理论"章节
- 并行学习核心理念：不要让AI替我学，而要和AI一起学
- 四大原则：协作优先于自动化、双向互学、创造协同效应、动态知识应用
| 2026-06-04 | 入库《新闻联播学习：三条最新AI教育政策》与《教师创造思想空间：教学实践与理论》（practice/research）

## [2026-06-04] ingest | 苏格拉底式AI交互法——让AI问你问题
- 来源：微信公众号「雯老师的历史番外」（白名单），2026-02-22
- 保存原文 [[raw/articles/2026-02-22-teacher-ai-socratic|老师用AI最大的错误：一直在问AI，却从没让AI问过你]]
- 创建概念页 [[concepts/teacher-ai-socratic-method|苏格拉底式AI交互法]]
- scope: practice — AI教学交互方法
- 三大应用：苏格拉底式引导、需求前置、AI心理咨询师
- 核心心法：不要让AI替代你思考，而是让AI增强你的思考

## [2026-06-05] ingest | 2026年部署会追加 + 教师AI应用指引
- 来源：今日AI教育日报第3条 + 第5条
- [[raw/articles/2026-04-01-education-digitalization-deployment|国家教育数字化战略行动2026年部署会原文]]
- [[raw/articles/2026-01-22-teacher-ai-guidelines|教师生成式AI应用指引原文]]
- 追加「2026年部署会」到 [[concepts/ai-education-action-plan|"人工智能+教育"行动计划]]（policy）
  - 怀进鹏部长讲话，六大战略布局，五个更要求，新平台发布
- 创建概念页 [[concepts/teacher-ai-application-guidelines|教师生成式人工智能应用指引（第一版）]]（practice）
  - 首份国家层面教师AI应用规范，覆盖备课/批改/管理/反思数十个场景
  - 人机协同的未来图景：知识性AI承接 + 育人性教师专注

## [2026-06-05] insight | 追加「记不住是AI时代的新能力」
- 来源：老板感悟，回应"过度依赖AI"担忧
- 追加到 [[concepts/ai-era-learning-theory|AI时代呼唤新的学习理论]]（research）
- 核心论点：记不住是认知策略的进化，依赖不是坏事但单点依赖是，风险可以备灾但趋势无法逆转
- 与「边练边学」感悟形成互补：教学方法论翻转 + 学习本体论翻转
- 关联：[[concepts/ai-lesson-prep-methodology]] [[concepts/create-thought-space]] [[concepts/ai-learning-methodology]]

## [2026-06-05] ingest | 中国教育宏观趋势——高考锐减45万
- 来源：微信公众号「校长派」，用户指定入库
- 保存原文 [[raw/articles/2026-06-05-gaokao-450k-drop-education-trends|高考锐减45万：给全国中小学校长的三个深层警示]]
- 创建概念页 [[concepts/china-education-macro-trends|中国教育宏观趋势：生源结构转型与教育分层]]（research）
- 三条核心趋势：普职分流主动化、复读模式终结、教育公平从机会公平→素养差距
- 对区域电教站的意义：职教信息化新需求 + AI素养成刚需 + 8年窗口期推动教育数字化升级

## [2026-06-05] ingest | "333"教研评课框架
- 来源：老板教研方法论
- 创建概念页 [[concepts/333-evaluation-framework|"333"教研评课框架]]（practice）
- 结构：3个优点 + 3个缺点 + 3条建议，先说好再说不好
- 已在默默~反馈场景中实操验证并获确认

## [2026-06-08] ingest | 教育大模型智能体综述
- 来源：今日AI教育日报第6条
- 保存原文 [[raw/articles/2024-11-28-education-ai-agent-review|教育大模型智能体的开发、应用现状与未来展望]]
- 创建概念页 [[concepts/education-ai-agent-review|教育大模型智能体综述]]（research）
  - 学术综述梳理20个典型教育AI智能体，涵盖技术架构、开发框架、四大应用场景（教/学/管/评）
  - 核心发现：以LLM为"大脑"，ReAct推理循环，"人人都有一个智能体"是终极愿景
  - 对区域电教站的意义：低门槛平台（Coze/Dify）可快速试点，关注教和评场景最有落地价值
- 关联：[[concepts/ai-education-current-state]] [[concepts/teacher-ai-application-guidelines]]

## [2026-06-08] ingest | 教育自动化的百年迷思——教育技术学自留地（白名单）
- 来源：微信公众号「教育技术学自留地」焦建利，2026-06-02发布
- 保存原文 [[raw/articles/2026-06-02-edu-tech-automation-obsession|教育科技的百年执念：自动化学习]]
- 创建概念页 [[concepts/ai-automation-century-myth|教育自动化的百年迷思]]（research）
- 核心论点：过去100年自动化"承诺-落空"循环永不完结，AI时代教师角色不可替代
- 对电教站价值：提供历史纵深的批判性视角，防止重蹈过度承诺覆辙

## [2026-06-08] ingest | EdTech全球风向标 2026-06-04——教育技术学自留地（白名单）
- 来源：微信公众号「教育技术学自留地」焦建利，2026-06-04发布
- 保存原文 [[raw/articles/2026-06-04-edtech-global-trends|EdTech全球风向标 2026年6月4日]]
- 更新 [[concepts/ai-education-current-state]]：追加Nature元分析数据 + OECD报告 + 中国教师AI报告（92.3%）
- 更新 [[concepts/ai-learning-methodology]]：追加K-12"慢用比快用更有效"发现
- 更新 [[concepts/education-ai-agent-review]]：追加LLM教育智能体演进 + 微软Build/Khanmigo改版/AIED 2026动态

## [2026-06-09] ingest | 天立学科大脑登上《2026自然指数—中国》
- 来源：今日AI教育日报第4条，中国科学报报道
- 保存原文 [[raw/articles/2026-03-26-tianli-brain-nature-index|原文全文]]
- 创建概念页 [[concepts/tianli-brain-nature-case|天立学科大脑（Tianli Brain）]]（product）
  - 首个登上《自然指数—中国》的中国AI+教育案例
  - 107所学校部署、25万+师生服务
  - 核心突破：从"是否答对"到"是否真正理解"的认知建模路径
  - 在偏远地区实现常态化应用，证明AI可成为弥合教育资源差距的基础设施
- 更新 [[moc/ai-education]]：新增product scope首个条目
- 关联：[[concepts/education-ai-agent-review]] [[concepts/ai-education-current-state]] [[concepts/ai-learning-methodology]]

## [2026-06-11] ingest | AI时代的考试改革——高考内容与形式需与时俱进
- 来源：今日AI教育日报第5条，中国教育和科研计算机网（CERNET）李志民专栏
- 保存原文 [[raw/articles/2026-06-11-gaokao-reform-ai-era|原文全文]]
- 创建概念页 [[concepts/ai-era-gaokao-reform|AI时代的考试改革——高考内容与形式需与时俱进]]（policy）
  - 核心论点：高考从"记忆知识"转向"运用知识"，增加开放性试题
  - 五大改革方向：知识→认知能力 / 高阶思维 / 真实情境 / 形式创新 / 人才观改革
  - "当机器越来越擅长计算和记忆时，高考更应选拔善于提出问题的人"
- 更新 index.md + MOC（scope索引/近期变化/页面数）
- 关联：[[concepts/china-education-macro-trends]] [[concepts/ai-education-action-plan]] [[concepts/teacher-ai-socratic-method]] [[concepts/333-evaluation-framework]]

## [2026-06-02] ingest | 批量入库18个教师案例
- 用AI（课堂教学）9个：数学/英语/科学课堂AI教学实践
- 创AI（管理平台）8个：校园智能体/批改/OA/心理监测等
- 护AI（AI安全）1个：古诗文AI生成内容审核
- 原始文件保存至 raw/cases/
- 更新 index.md + MOC

## [2026-06-12] ingest | AI教育的三条路径——大厂效率、教培名师与"认知断点"路线
- 来源：今日AI教育日报第1条，芥末堆（钛媒体），2026-06-11发布
- 保存原文 [[raw/articles/2026-06-12-ai-edu-three-routes|原文全文]]
- 创建概念页 [[concepts/ai-edu-three-routes|AI教育的三条路径——大厂效率、教培名师与"认知断点"路线]]（research）
  - 核心框架：2026年AI教育三大路径对比（大厂效率/教培名师/认知断点）
  - 洋葱学园13年方法论：不空降概念、思维链外化、动态可视化
  - AI智能学伴6大角色（自学大师/私人助教/思维教练/规划导师/自律伙伴/情感树洞）
  - 人机复合型教师模式：AI承接收授与答疑，教师回归"育人"
  - 对外经贸附中实战案例（2000+学校深度服务）
- 对电教站价值：AI教育产品选型参考——优先支持"苏格拉底式追问"而非简单答题；三条路径互补策略
- 关联：[[concepts/ai-education-current-state]] [[concepts/teacher-ai-socratic-method]] [[concepts/ai-learning-methodology]] [[concepts/ai-era-learning-theory]] [[concepts/ai-lesson-prep-methodology]]
- 更新 index.md + MOC（research scope索引/近期变化/页面数）

## [2026-06-23] ingest | 《两种AI协同：一种让课堂更好看，一种让教师更深刻》
- 保存原文 raw/articles/2026-05-10-ai-two-mode-collaboration.md（来源：公众号「苏天平」）
- 创建概念页 [[concepts/ai-two-mode-collaboration|两种AI协同模式：内容生产者 vs 思维伙伴]]（practice）
- 核心观点：AI作为内容生产工具（让课堂更好看）vs AI作为思维伙伴（让教师更深刻）
- 三大原则：诊断先于建议、诚实宣告边界、从现象到结构的追问
- 对电教站价值：提供了一个评估教师AI应用深度的框架——从"展示AI做了什么"转向"揭示AI追问如何改变了教师的认知"
- 关联：[[concepts/teacher-ai-socratic-method]] [[concepts/create-thought-space]] [[concepts/ai-lesson-prep-methodology]] [[concepts/333-evaluation-framework]]
- 更新 index.md + MOC（practice scope索引/近期变化/页面数18）

## [2026-06-23] ingest | 《腾讯ima Copilot + 循环工程》
- 保存原文 raw/articles/2026-06-17-loop-engineering-ima.md（来源：公众号「星享AI笔记」）
- 创建概念页 [[concepts/loop-engineering-framework|循环工程（Loop Engineering）——AI自动化系统的四大核心要素]]（research）
- 核心框架：Addy Osmani 总结的循环工程四要素——定时自动触发任务、持久化状态记忆、技能知识沉淀、外部工具连接器
- 关键洞察：人从AI的操作员变成系统的设计者——与 Hermes 的 cron+skill+memory+API 架构高度对应
- 对电教站价值：教育数字化自动化工作流设计的理论参考——评估项目是否具备完整的四个循环要素
- 关联：[[concepts/ai-two-mode-collaboration]] [[concepts/teacher-ai-socratic-method]] [[concepts/ai-education-current-state]] [[concepts/ai-learning-methodology]]
- 更新 index.md + MOC（research scope索引/近期变化/页面数19）

## [2026-06-25] ingest | 《消失的中间层教师——在那片AI浸润的绿野上，你是春风，还是过客？》
- 来源：微信公众号「刘欣教学设计」，2026-06-24发布
- 保存原文 raw/articles/2026-06-24-disappearing-middle-layer-teachers.md
- 创建概念页 [[concepts/ai-era-teacher-two-fates|AI时代教师的两种命运——中间地带正在消失]]（practice）
- 着眼点：面对AI侵蚀职业中间层，教育应如何发力
- 核心论点：不存在"中等水平"的AI使用者，教师在"协作"与"依赖"之间没有中间地带
- 对电教站价值：为教师AI素养评估提供了新维度——从"技术熟练度"转向"思考在场度"；可设计教师AI使用反思机制
- 关联：[[concepts/ai-two-mode-collaboration]] [[concepts/create-thought-space]] [[concepts/teacher-ai-socratic-method]] [[concepts/ai-lesson-prep-methodology]] [[concepts/ai-education-current-state]]
- 更新 index.md + MOC（practice scope索引/近期变化/页面数20）

## [2026-06-29] ingest | 《AI赋能教育的十六宗错——一边用一边错》
- 来源：微信公众号「刘欣教学设计」，2026-06-27发布
- 保存原文 raw/articles/2026-06-29-ai-edu-sixteen-mistakes.md
- 创建概念页 [[concepts/ai-education-misuse-analysis|AI教育常见误区分析：十六宗错与三个层次]]（practice）
- 系统梳理教师使用AI的16个误区，按三个递进层次组织：工具误用（效率崇拜/替代焦虑/工具中心论/内容堆砌/表面个性化/答案优先）→ 判断权丧失（技术替代判断/数据崇拜/全天候陪伴/全知全能为师）→ 教育本质迷失（无缝课堂/模拟等同体验/自动化教研/回应等于在场/AI生成等于权威知识/技术让教育更透明）
- 核心洞见：所有误用根源在于默认接受"教育=信息处理，教师=内容生产者"的错误假设
- 刘欣清醒三原则：从效率转向发展、从工具转向范式、从替代转向守护
- 与[[concepts/ai-era-teacher-two-fates]]同作者，形成互补：一篇说"什么不该做"，一篇说"什么正在消失"
- 关联：[[concepts/ai-two-mode-collaboration]] [[concepts/ai-era-learning-theory]] [[concepts/ai-era-teacher-two-fates]] [[concepts/ai-education-current-state]] [[concepts/create-thought-space]]
- 更新 index.md + MOC（practice scope索引/近期变化/页面数21）

## [2026-06-29] ingest | 《问课课堂研究：WISE框架与AIED人机协同教研模型》
- 来源：概念提取入库（百度百科+华南师范大学官网+百家号文章），2026-06-29
- 保存原文 raw/articles/2026-06-29-wenke-ai-era-research-paradigm.md（百家号《AI时代教研新范式：用"问课"把课堂问透》）
- 创建概念页 [[concepts/wenke-wise-classroom-research|问课课堂研究：WISE框架与AIED人机协同教研模型]]（research）
- 核心人物：胡小勇（华南师范大学教育人工智能研究院常务副院长）
- WISE框架（《电化教育研究》2026年第2期）：教学结构(Framework)→教学行为(Interaction)→教学策略(Strategy)→教学成效(Effectiveness)，四层递进回答问课"问什么"
- AIED教研模型（实践版）：Aim定位目标→Interpret解读现象→Explore探究证据→Derive萃取智慧，四步循环回答"怎么问"
- 问课大模型：与科大讯飞合作共研，已组建20家单位智慧教研共同体
- 对电教站价值：WISE+333可组合使用（WISE做分析、333做输出），覆盖从分析到呈现的完整教研闭环
- 关联：[[concepts/333-evaluation-framework]] [[concepts/teacher-ai-socratic-method]] [[concepts/ai-two-mode-collaboration]] [[concepts/ai-education-current-state]] [[concepts/ai-education-misuse-analysis]]
- 更新 index.md + MOC（research scope索引/近期变化/页面数22）

## [2026-07-01] ingest | AI将全面进入大中小学课堂——五部门联合推动AI通识教育普及（日报入库）
- 来源：南方日报，2026-04-15发布（日报第3条）
- 保存原文 raw/articles/2026-04-15-southern-daily-ai-general-education.md
- 创建概念页 [[concepts/ai-general-education-literacy|智能体协作的三层意识与AI通识教育普及]]（practice）
- 核心框架：黄秉刚三层意识（成本意识/分层意识/过程留痕意识）、从"工匠"到"指挥家"的能力范式转变、"无人工智能挑战"与逆向工程训练
- 对电教站价值：三层意识框架作为学校AI素养评估实操维度；"工匠→指挥家"用于向教师解释AI时代育人目标转变
- 关联：[[concepts/ai-education-action-plan]] [[concepts/teacher-ai-application-guidelines]] [[concepts/ai-era-gaokao-reform]] [[concepts/ai-education-current-state]] [[concepts/create-thought-space]]

## [2026-07-01] ingest | 可汗学院创始人：AI不是最终解决方案（日报入库）
- 来源：芥末堆，2026-06-30发布（日报第4条）
- 保存原文 raw/articles/2026-06-30-khan-academy-ai-motivation-gap.md
- 创建概念页 [[concepts/ai-cannot-solve-motivation|AI无法解决学习动机问题——可汗学院的反思与教育的社会本质]]（research）
- 核心论点：Khanmigo访问量激增使用率停滞暴露"5%问题"——仅5%学生能受益；学习是社交和关系活动，AI无法复制人情味
- 对电教站价值：为教师AI培训注入"反向思考"（AI不能做什么）；教育科技产品选型中优先选择增强师生互动的产品
- 关联：[[concepts/ai-education-current-state]] [[concepts/ai-automation-century-myth]] [[concepts/ai-era-learning-theory]] [[concepts/create-thought-space]] [[concepts/ai-era-teacher-two-fates]] [[concepts/ai-education-misuse-analysis]]
- 更新 index.md + MOC（research+practice scope索引/近期变化/页面数24）

## [2026-07-08] ingest | 区域AI+教育推进的实践路径与困难（日报入库）
- 来源：新华网，2026-06-17新华视点调研报道（日报第1条）
- 保存原文 raw/articles/2026-07-08-xinhua-ai-plus-education.md
- 创建概念页 [[concepts/regional-ai-edu-path|区域AI+教育推进的实践路径与困难]]（practice）
- 核心框架：四类做法（课堂数据采集/AI减负/资源辐射/顶层设计）→ 三大卡点（工具错位/教师能力/设备鸿沟）→ 三步走推进路径
- 对电教站价值：点阵笔/人机双师/智慧云校等方案可直接参考；三大卡点可提前预判纳入区域规划
- 关联：[[concepts/ai-education-current-state]] [[concepts/ai-cannot-solve-motivation]] [[concepts/teacher-ai-application-guidelines]] [[concepts/ai-education-misuse-analysis]]

## [2026-07-13] ingest | AI-native教育产品——从AI工具到教学决策参与者（日报入库）
- 来源：芥末堆，LingoAce发布Tutor Luna（日报第1条）
- 保存原文 raw/articles/2026-07-13-lingoace-tutor-luna.md
- 创建概念页 [[concepts/ai-native-vs-ai-powered|AI-native教育产品——从AI工具到教学决策参与者的范式转变]]（research）
- 核心框架：AI教育三次跃迁 → AI-powered vs AI-native 分析框架 → 四步学习引擎模型（识别→生成→反馈→建模→优化）→ 从课程交付到能力增长交付
- 对电教站价值：AI-powered/AI-native可作为产品选型判断维度；"能力增长交付"理念可融入区域AI教育评价导向
- 关联：[[concepts/ai-education-current-state]] [[concepts/ai-edu-three-routes]] [[concepts/ai-education-misuse-analysis]]

## [2026-07-14] ingest | 课堂认知盲区与可观测AI（日报入库）
- 来源：OpenAI，SchoolAI利用GPT-4.1打造AI导师Sidekick，覆盖全球100万教室（日报第5条）
- 保存原文 raw/articles/2026-07-14-schoolai-sidekick.md
- 创建概念页 [[concepts/classroom-blindspot-observable-ai|课堂认知盲区与可观测AI]]（research）
- 核心框架：课堂认知盲区（中间80%学生）→ 可观测AI架构 → 教练式引导vs直接给答案 → 智能路由成本优化
- 对电教站价值：认知盲区概念可唤醒教师在AI培训中的需求痛点；"可观测性"可作为AI产品选型硬性门槛
- 关联：[[concepts/ai-native-vs-ai-powered]] [[concepts/ai-education-current-state]] [[concepts/ai-cannot-solve-motivation]] [[concepts/regional-ai-edu-path]]

## [2026-07-16] ingest | AI思辨式伴读——从不可能三角看AI在阅读教育中的破局（日报入库）
- 来源：芥末堆，猿辅导AI一对一伴读（日报第2条）
- 保存原文 raw/articles/2026-07-16-yuanfudao-ai-reading.md
- 创建概念页 [[concepts/ai-socratic-reading-companion|AI思辨式伴读——从不可能三角看AI在阅读教育中的破局]]（practice）
- 核心框架：阅读教育"不可能三角"→ AI思辨式伴读四层追问框架（找现象→比行为→挖内因→提规律）→ 陪练式AI vs 问答式AI
- 对电教站价值："不可能三角"可作为区域产品选型通用分析框架；"陪练式AI"维度可融入教师AI培训内容
- 关联：[[concepts/ai-native-vs-ai-powered]] [[concepts/regional-ai-edu-path]] [[concepts/ai-cannot-solve-motivation]]

## [2026-07-12] ingest | 《当古诗"推敲"遇上AI》语文思辨课案例
- 来源：微信公众号「刘欣教学设计」，2026-06-06发布
- 保存原文 raw/articles/2026-06-06-tuiqiao-ai-speculative-chinese.md
- 创建案例页 [[cases/yong-ai/tuiqiao-ai|当古诗"推敲"遇上AI——一堂让孩子告别"非此即彼"的语文思辨课]]（practice）
- AI角色定位亮点：AI扮演贾岛但不给标准答案，制造认知冲突而非提供答案
- 两个可迁移环节：AI扮演角色制造认知冲突、AI生成→学生找茬培养批判性思维
- 有前后测对比的教学效果证据
- 关联：[[concepts/teacher-ai-socratic-method]] [[concepts/ai-two-mode-collaboration]] [[concepts/create-thought-space]] [[concepts/ai-education-misuse-analysis]]
- 更新 index.md + cases/yong-ai/index.md（页面数30→29→30）

## [2026-07-12] ingest | 《历史课变法庭辩论赛——隋炀帝功过辩论中的AI史料助手》
- 来源：微信公众号「刘欣教学设计」，2026-06-10发布
- 保存原文 raw/articles/2026-06-10-sui-yangdi-ai-debate.md
- 创建案例页 [[cases/yong-ai/sui-yangdi-ai-debate|历史课变法庭辩论赛——隋炀帝功过辩论中的AI史料助手]]（practice）
- AI设计亮点：Coze智能体+双私有知识库限定AI知识范围；每次AI输出后教师做"史源验证"（来源→立场→程度）；辩论驱动AI调用而非教师预设播放
- 与"推敲"案例互补：语文思辨+历史史料批判，共同支撑"AI作为思辨伙伴"设计路径
- 关联：[[cases/yong-ai/tuiqiao-ai]] [[concepts/teacher-ai-socratic-method]] [[concepts/ai-two-mode-collaboration]] [[concepts/create-thought-space]] [[concepts/ai-education-misuse-analysis]]
- 更新 index.md + cases/yong-ai/index.md + MOC（页面数31）

## [2026-07-19] ingest | 教育AI战国时代 —— 猿力/松鼠AI/豆神/粉笔/作业帮五路突围
- 来源：人人都是产品经理（白名单C组），2026-04-01发布
- 保存原文 raw/articles/2026-04-01-ai-edu-warring-states.md
- 创建概念页 [[concepts/ai-edu-warring-states-landscape|教育AI战国格局——五家企业的战略路线对比]]（scope: product）
- 核心框架：五家企业战略路线对比表（全栈自研/算法原教旨/人文情感/垂直效率/流量规模）+ 短板分析 + 终局预测
- 关联：[[concepts/ai-edu-three-routes]] [[concepts/ai-edu-product-strategy]] [[concepts/tianli-brain-nature-case]]
- 更新 index.md + MOC（页面数32→34）

## [2026-07-19] ingest | 教育AI技术栈解构 —— 从大模型到智能体的架构实践
- 来源：人人都是产品经理（白名单C组），2026-07-02发布
- 保存原文 raw/articles/2026-07-02-edu-ai-tech-stack.md
- 创建概念页 [[concepts/edu-ai-tech-stack-deconstruction|教育AI技术栈——从大模型到智能体的架构解构]]（scope: research）
- 核心案例：爱学大模型双数据飞轮+三层记忆、微软Study and Learn以问代答、企鹅教师助手经验结构化、学而思T6闭环、2026 WDEC标准之争
- 关联：[[concepts/education-ai-agent-review]] [[concepts/ai-native-vs-ai-powered]] [[concepts/ai-edu-three-routes]] [[concepts/wenke-wise-classroom-research]]
- 更新 index.md + MOC
