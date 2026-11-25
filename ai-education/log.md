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
- 刘老师指出：已入库的3篇文章（myknowledge-skill、Hermes搭建指南、AutoCLI方案）不属于AI+教育领域
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
- 来源：刘老师在阅读项飙"抓住"与"拉网"后的个人感悟转化
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

## [2026-07-28] ingest | AI个性化学习适配——五维自测法
- 保存原文 raw/articles/2026-07-28-ai-learning-profile-five-dimensions.md
- 创建概念页 [[concepts/ai-personalized-learning-profile|AI个性化学习适配——五维自测法]]
- 五维框架：VARK / 场独立依存 / 能量节奏 / 自我效能 / 考试焦虑
- 关联 [[three-behavior-change-models]]

## [2026-07-28] ingest | AI不是削弱思考，而是让思考进入更高维度
- 保存原文 raw/articles/2026-07-28-ai-elevates-thinking.md
- 创建概念页 [[concepts/ai-elevates-thinking-bloom-zpd|AI提升思考维度——Bloom+ZPD视角]]
- 核心框架：AI降低低阶认知 + Bloom分层 + 维果茨基ZPD
- 与[[high-level-shift-education]]和[[post-literacy-age-ai-impact]]形成互补对照

## [2026-07-28] ingest | AI-TPACK框架——从用好技术到让学习被看见
- 保存原文 raw/articles/2026-07-28-ai-tpack-framework.md
- 创建概念页 [[concepts/ai-tpack-framework|AI-TPACK框架]]
- 核心结构：轴心决断知识(DK) + AIPCK证据链（目标显性化/思维可见化/证据闭环）
- 关联5个概念页

## [2026-07-28] ingest | 中国教师AI应用报告解读（《财经》）
- 保存原文 raw/articles/2026-07-28-teacher-ai-report-caijing.md
- 创建概念页 [[concepts/teacher-ai-report-2026|中国教师AI应用报告解读]]
- 数据：8.6万教师调研，通用热专业冷（96.9% vs 35.2%）、四大不可替代领域、四维三阶模型

## [2026-07-28] ingest | 儿童AI陪伴风险——被动占据vs主动替代
- 保存原文 raw/articles/2026-07-28-ai-native-children-risk.md
- 创建概念页 [[concepts/children-ai-companion-risk|儿童AI陪伴风险]]
- 填补护AI"儿童心理安全"维度（此前只有内容审核）
- 关键框架：HOPE原则 + DETECT清单 + 加工食品类比

## [2026-07-28] ingest | AI赋能教育培训设计——刘欣五段式提纲
- 保存原文 raw/articles/2026-07-28-liuxin-ai-training-outline.md
- 创建概念页 [[concepts/ai-training-five-stage-design|AI赋能教育培训设计]]
- 五段式：破冰→现象→谬误→案例→第一性原理
- 关键概念：认知卸载 / K型分化 / AMV模型（李继刚）/ 提示词≠许愿池

## [2026-07-28] ingest | AI微决策——课程设计中的决策链框架
- 保存原文 raw/articles/2026-07-28-ai-micro-decisions-lesson-design.md
- 创建概念页 [[concepts/ai-micro-decisions-lesson-design|AI微决策]]
- 核心框架：备课是决策链 / 教学问题叙事 / 借脑子三层（Skill→智能体→垂直大模型）
- 关联4个概念页

## [2026-07-28] ingest | OECD数字教育展望2026
- 保存原文 raw/articles/2026-07-28-oecd-digital-education-outlook-2026.md
- 创建概念页 [[concepts/oecd-digital-education-2026|OECD数字教育展望2026]]
- 关键数据：练习+48% / 考试-17%，完成任务≠学习发生
- 与教师报告（中国）+ 后识字时代形成国际证据链

## [2026-07-28] ingest | 教学设计的问题三属性框架
- 保存原文 raw/articles/2026-07-28-ai-lesson-design-anomaly-framework.md
- 创建概念页 [[concepts/question-three-attributes-framework|问题三属性框架]]
- 核心：AI算均值人类提供异常值（韦青）+ 真问题/对的问题/高价值问题
- 关联5个概念页

## [2026-07-28] ingest | AI融合课的克制与留白——教育发生的四瞬间
- 保存原文 raw/articles/2026-07-28-ai-restraint-and-blank-space.md
- 创建概念页 [[concepts/ai-restraint-blank-space-framework|克制与留白框架]]
- 核心：要素齐全≠教育在场（可口可乐隐喻）+ 四瞬间诊断 + 克制三原则
- 关联5个概念页

## [2026-07-28] ingest | AI破坏最近发展区——三机制认知分析
- 保存原文 raw/articles/2026-07-28-ai-destroys-zpd-cognitive-analysis.md
- 创建概念页 [[concepts/ai-destroys-zpd-cognitive-analysis|AI破坏最近发展区]]
- 三机制：认知负荷错配（Sweller）/ 认知卸载（Risko）/ 必要难度消解（Bjork）
- 与[[ai-elevates-thinking-bloom-zpd]]形成正反对照

## [2026-07-28] ingest | AI时代的退行性进步——麦克卢汉自我截除视角
- 保存原文 raw/articles/2026-07-28-ai-regressive-progress-mcluhan.md
- 创建概念页 [[concepts/ai-regressive-progress-mcluhan|退行性进步]]
- 核心：麦克卢汉"自我截除"理论 + 七领域进步/退步对照表
- 关联5个概念页（十六宗错术语的理论化）

## [2026-08-27] ingest | AI复活古人的教育迷思——结构性批判
- 保存原文 raw/articles/2026-08-27-ai-resurrected-ancient-educational-myth.md
- 创建概念页 [[concepts/ai-resurrected-ancient-educational-myth|AI复活古人的教育迷思]]
- 六层透镜：技术理性/SAMR替代/银行式教育/教育之弱/经验断裂/景观化展演性
- 与[[ai-micro-decisions-lesson-design]]"怪病"点形成完整展开

## [2026-08-27] ingest | 教育技术课AI爆改——从作品考核到过程考核
- 保存原文 raw/articles/2026-08-27-edtech-course-experiential-reform.md
- 创建案例页 [[cases/national/edtech-course-process-assessment|教育技术课AI爆改]]
- 用户心得：作品型考核2023年后必须转向过程型考核
- 核心洞察：PBL前提塌方（AI代做绕过学习）+ 作品考核失效

## [2026-08-27] ingest | AI高支持环境教学设计五原则
- 保存原文 raw/articles/2026-08-27-ai-five-design-principles.md
- 创建概念页 [[concepts/ai-five-design-principles|教学设计五原则]]
- 五原则：体验先行/任务驱动/思维可见/刻意摩擦/角色分化
- 与[[ai-tpack-framework]]同作者，是其实践落地版
- 关联6个概念页+案例页

## [2026-08-27] ingest | 人机协同教学设计——AI做宽度教师做深度
- 保存原文 raw/articles/2026-08-27-tsinghua-teacher-ai-partnership.md
- 创建概念页 [[concepts/human-ai-collaboration-width-depth|人机协同教学设计]]
- 来源：中国青年报报道清华OpenMAIC创课节
- 核心：7:3分工 + 思维眼镜卡片 + 教育工程师/终审者角色
- 关联6个概念页

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
- 来源：刘老师感悟，回应"过度依赖AI"担忧
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
- 来源：刘老师教研方法论
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

## [2026-07-21] ingest | 上海市中小学人工智能素养评价框架（日报入库）
- 来源：芥末堆，WAIC 2026国际AI教育论坛发布（日报第1条）
- 保存原文 raw/articles/2026-07-21-shanghai-ai-literacy-framework.md
- 创建概念页 [[concepts/shanghai-ai-literacy-framework|上海市中小学人工智能素养评价框架]]（policy）
- 核心框架：四维度（AI意识/思维/应用与创新/社会责任）+ 12项二级指标 + 三水平递进（感知理解→实践应用→协同创新）+ 分学段聚焦
- 对电教站价值：可直接作为区域制定本地化AI素养评价标准的模板；评估任务示例可复用
- 关联：[[concepts/ai-education-action-plan]] [[concepts/ai-general-education-literacy]] [[concepts/regional-ai-edu-path]]

## [2026-07-21] ingest | WAIC 2026教育论坛——AI时代的人才培养与教育重构（日报入库）
- 来源：澎湃新闻/人民日报，WAIC 2026教育专题论坛（日报第1条）
- 保存原文 raw/articles/2026-07-21-waic-2026-education-panel.md
- 创建概念页 [[concepts/waic-2026-education-reform|WAIC 2026教育论坛——AI时代的人才培养与教育重构]]（practice）
- 核心框架：经师+人师+机师三重身份（马余刚）→ OPC/FDE新人才范式（周刚）→ 徐汇区重构教育三件事 → AI金句集
- 对电教站价值：三重身份框架可用于教师培训目标设定；徐汇区三件事可作为区域推进参照；金句可作培训素材
- 关联：[[concepts/shanghai-ai-literacy-framework]] [[concepts/ai-education-action-plan]] [[concepts/ai-education-current-state]] [[concepts/ai-era-teacher-two-fates]]

## [2026-07-29] ingest | 从工具效率到认知理解——教育AI的深水区转型与认知世界模型（日报入库）
- 来源：芥末堆，复旦大学副校长周磊谈教师转型 + 天立启鸣CWM白皮书（日报第1条）
- 保存原文 raw/articles/2026-07-29-cognitive-world-model-edu-ai.md
- 创建概念页 [[concepts/cognitive-world-model-edu-ai|从工具效率到认知理解——教育AI的深水区转型与认知世界模型]]（research）
- 核心框架：范式转型（工具效率→认知理解）→ 三大结构性难题 → CWM认知世界模型 + LAM闭环 → 认知主权伦理框架
- 对电教站价值：范式框架可用于培训宣讲；三难题可作为区域自评工具；CWM和认知主权可作为产品选型新维度
- 关联：[[concepts/ai-education-current-state]] [[concepts/ai-native-vs-ai-powered]] [[concepts/regional-ai-edu-path]]

## [2026-07-30] ingest | AI时代教师角色的国际探索——光明日报四重角色与四根支柱（日报入库）
- 来源：光明日报，社科院王维国（日报第3条）
- 保存原文 raw/articles/2026-07-30-gmw-teacher-role-international.md
- 创建概念页 [[concepts/gmw-teacher-role-international|AI时代教师角色的国际探索——光明日报四重角色与四根支柱]]（research）
- 核心框架：电动自行车vs扫地机器人隐喻 → 四种不可替代角色（心灵陪伴/价值塑造/创新启发/成长引领）→ 四根治理支柱（制度/素养/规律/护栏）
- 对电教站价值：电动自行车隐喻可直接用于培训开场；四种角色框架可用于教师AI培训模块设计；国际案例可作为说服素材
- 关联：[[concepts/ai-era-teacher-two-fates]] [[concepts/ai-education-current-state]] [[concepts/waic-2026-education-reform]]

## [2026-08-04] ingest | 有规则的AI教育——禁止进课堂不是出路，分层管理才是（日报入库）
- 来源：科学网/中国科学报，郭英剑（日报第3条）
- 保存原文 raw/articles/2026-08-04-banning-ai-in-classroom-risk.md
- 创建概念页 [[concepts/rule-based-ai-education|有规则的AI教育——禁止进课堂不是出路，分层管理才是]]（practice）
- 核心框架：禁止AI的三大反噬（教育悖论/地下化/能力推迟）→ 三层学习环境（禁止/有限/充分）→ 写作重定义 → 披露制度+教师AI教育+过程评价
- 对电教站价值：三层环境框架可直接用于区域AI教育应用规范；防"地下化"预警；写作教学落地抓手
- 关联：[[concepts/ai-education-misuse-analysis]] [[concepts/ai-education-current-state]] [[concepts/ai-era-teacher-two-fates]]

## [2026-08-21] ingest | 全球智慧学校倡议——学校智能化转型的五维度自查框架（日报入库）
- 来源：北京师范大学，2026全球智慧教育大会发布《全球智慧学校倡议》（日报第1条）
- 保存原文 raw/articles/2026-08-21-global-smart-school-initiative.md
- 创建概念页 [[concepts/smart-school-five-dimensions|全球智慧学校倡议——学校智能化转型的五维度自查框架]]（practice）
- 核心框架：智慧学校五维度（学习体验/教学创新/教师发展/学校规划/家校社协同）+ 两个根本问题 + 变革成熟度评估方法论
- 对电教站价值：五维度可直接转化为区域学校智慧化转型自查表；构成学校智慧教育评估指标体系
- 关联：[[concepts/regional-ai-edu-path]] [[concepts/ai-education-current-state]] [[concepts/shanghai-ai-literacy-framework]]

## [2026-08-28] ingest | AI教育的四大风险——认知伙伴时代的挑战与应对（日报入库）
- 来源：新华网，《全球AI创造力发展报告2026——AI教育专项》（日报第2条）
- 保存原文 raw/articles/2026-08-28-global-ai-creativity-report.md
- 创建概念页 [[concepts/ai-education-four-risks|AI教育的四大风险——认知伙伴时代的挑战与应对]]（research）
- 核心框架：认知伙伴阶段判断 → 四大风险（认知外包/信息真实性/算法偏见/情感依赖）→ AI越强越要人做主 → 评价转向"验是否真理解"
- 对电教站价值：四大风险（尤其情感依赖）可作为区域风险自查清单；"AI越强越要人做主"可作培训引用
- 关联：[[concepts/rule-based-ai-education]] [[concepts/ai-education-misuse-analysis]] [[concepts/shanghai-ai-literacy-framework]] [[concepts/smart-school-five-dimensions]]

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

## [2026-08-12] ingest | AI三问学习法——NotebookLM 48小时速通案例
- 来源：X 平台 @ihtesham2005 原帖（2026-03-07，约300万浏览）+ note.com 方法论拆解 + 多平台二创
- 创建概念页 [[concepts/ai-three-questions-learning|AI三问学习法]]（scope: practice）
- 核心内容：三问法（专家思维模型/争议地图/自我检测题）+ 认知科学依据（框架先行、主动回忆）+ 真伪核查表（"导师怀疑作弊"等情节为中文二创虚构）
- 教育价值：提问能力培养案例，可进培训素材，但引用须标注"细节未经验证"，剔除演绎情节
- 关联：[[concepts/teacher-ai-socratic-method]] [[concepts/ai-elevates-thinking-bloom-zpd]] [[concepts/post-literacy-age-ai-impact]] [[concepts/high-level-shift-education]] [[concepts/create-thought-space]]
- 更新 index.md + MOC（页面数37→38，概念30→31）

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

- 关键数据：摩根士丹利2026年7月报告——专业服务行业AI净生产率提升9.6%
- 对电教站价值：教师专业发展的重心应从"技术培训"转向"决策判断力+伦理承担"
- 关联：[[concepts/china-education-macro-trends]] [[concepts/ai-era-teacher-two-fates]] [[concepts/ai-education-current-state]] [[concepts/ai-education-misuse-analysis]]
- 更新 index.md + MOC（页面数34→35）

## [2026-09-22] ingest | 项目化融合课评价：赛课评价工具包 + 教研员角色转变（刘老师原创教研资料）
- 来源：刘老师在 DeepSeek 辅助下整理的两份指导性教研资料（本地文件，非外链）
- 保存原文 raw/articles/2026-09-22-pbl-competition-evaluation-toolkit.md（HTML 提取，5896 字）、raw/articles/2026-09-22-pbl-tech-integration-evaluation.md（4066 字）
- 创建概念页 [[concepts/pbl-competition-evaluation-toolkit|小学项目化融合课赛课评价工具包]]（scope: practice）
  - 8 部分结构：评赛理念与评委须知（三原则 + 评委三角色 + **5 条红线**）、100 分制评分量表、课堂观察记录表、学科评价量规模板（语/数/科/英示例）、过程性证据采集清单（6 类）、评委反馈对话单、跨学科协同评价单、评委使用手册
  - 5 维度权重：学科素养 25% / 项目化设计 30% / 技术融合 20% / 过程成果 15% / 教学评一致 10%
  - 红线处理：①学科素养未发展→降一档 ②为用而用→不得分 ③拼盘式→不认定整合 ④教师代劳→扣分 ⑤技术替代思考→倒扣
- 创建概念页 [[concepts/pbl-tech-integration-evaluation|教研员角色转变与方法框架]]（scope: practice）
  - **核心判断：学科核心素养是主坐标，信息技术融合是条件性、支持性、增值性维度**——信息科技核心素养只在信息科技课程或明确以其为目标的项目中才成为主坐标
  - 五层评价框架：主维度（学科素养目标一致性 / 学科实践深度）+ 辅助增值维度（技术融合适切性）+ 保障维度（过程性证据与教学评一致）+ 条件维度（跨学科整合合理性）+ 发展维度（反馈与改进）
  - 三个转向：评教→评学、技术中心→学科中心、单科裁决→协同判断
  - 反馈机制：证据先行五步（描述证据→解释意义→聚焦问题→提出改进→跟踪再评）
- 关联：[[concepts/333-evaluation-framework]] [[concepts/ai-tpack-framework]] [[concepts/question-three-attributes-framework]] [[cases/national/edtech-course-process-assessment]]
- **索引修复（连带处理，非本次入库内容）**：
  - index.md 曾被行号前缀污染（102/127 行），已重写为干净格式；概念计数 40→65，raw 收录 30→74
  - MOC 检索地图原先仅收录 9 个概念（实际 65 个），已补全 scope 索引表 + 近期变化 + 总页面数三项
  - 归档 5 个回滚残留空占位符（5-country-uni-ai-policy / ai-education-ethics-framework / china-ai-edu-2026-overview / hk-digital-edu-blueprint / regional-ai-edu-international-models）→ `_archive/*.md.removed`
  - tianli-brain-nature-case 元数据从旧格式（type: entity）升级为当前格式（补 domain/scope: product/primary_entry 等）

## [2026-09-22] refresh | 撞库核查 + raw 全文补全：光明日报《AI浪潮下教师角色重塑的国外探索》
- 用户提供链接询问入库价值 → 撞库核查发现 **2026-07-30 已入库**（[[concepts/gmw-teacher-role-international]]），不重复入库
- 补全 raw 原文：raw/articles/2026-07-30-gmw-teacher-role-international.md 原为摘要（1974 字节），
  已重抓全文并写入真实 sha256（13751 字节）
- 增强概念页：新增「AI 接走什么，教师拿回什么」对照表
  - 英国橡树国家学院 "Aila" 备课助手 → AI 搭材料骨架，教师做挑选/删改/重组/校准
  - 美国佐治亚州立大学 "突袭" 聊天机器人 → 第一个夏天 18.5 万次互动，省下的时间要进入真实教育关系
  - 补 3 条关联：[[concepts/ai-restraint-blank-space-framework]] / [[concepts/human-ai-collaboration-width-depth]] / MOC
- **发现系统性问题（待用户决策）**：raw/articles 74 篇中 70 篇 <3000 字节（摘要而非全文），
  15 篇 sha256 为 placeholder，6 篇为空壳（22-37 字节）。raw 层实际退化为"摘要层"，
  原文不可回溯、无法校验概念页忠实度。

## [2026-09-22] refresh | raw 全量回补：74 篇摘要 → 全文（方案 A + C）

**方案 A（规则落地）**：thought-ingest skill 新增
- `5a raw 铁律`：必须存全文（禁摘要/截断）、必须写真实 sha256（禁 placeholder）、正文清洗
- `5b 分站点抓取策略`：新闻站（web_extract）/ 微信（移动端 UA + 正则）/ 头条（移动端 API）/ 无 URL（跳过）
- 注意事项新增 2 条（raw 铁律为硬规则；抓取失败的 raw 不删，标注 note）

**方案 C（全量回补）**：74 篇 raw 原为摘要（中位数 1011 字节）
- **抓取成功 63 篇**：web 站 28（web_extract）+ 微信公众号 29（移动端 UA 正则）+ 头条 4（移动端 API）+ 重试成功 2
- **抓取失败 3 篇**（保留摘要 + note 标注原因）：yznu.edu.cn 站点超时 / 微信环境异常页 / 微信正文 JS 动态加载
- **无法回补 2 篇**：无 source_url（个人感悟类）
- **清理 6 个空壳 raw**（回滚残留，22-37 字节）→ `_archive/raw-*.removed`

**结果**：中位数 1011 → **8750 字节**（↑8.7 倍）；≥3000 字节篇目 4 → 63

**工具修复**（wiki_rebuild_index.py）：原版重建会丢失 Reports/Cases/Decisions/Raw Articles 四段，
已补齐；raw 标题中的 `|` 转义残留已清洗

## [2026-09-22] ingest | AI时代教师作为 Hub——U型理论视角下的课堂重构
- 来源：微信公众号「刘欣教学设计」，2026-09-16 发布，4192 字（用户指定入库）
- 保存原文 raw/articles/2026-09-16-liuxin-teacher-as-hub.md（全文 12512 字节 + 真实 sha256）
- 创建概念页 [[concepts/ai-era-teacher-as-hub|AI时代教师作为 Hub]]（scope: practice）
- **入库前增量评估**（已核查库内无此框架）：
  - **U型理论 Hub 框架**：AI 是知识源、教师是 Hub；**容器 vs 管道**（管道传输信息，容器孕育思想）；Hub 的本地性；产出是行动不是答案
  - **6 个高校课堂改造案例**：哈工大齐超（诊断室）/ 清华卢滇楠（竞技场·三次人机对决）/ 大连理工（师生机三元）/ 台湾中央大学张家凯（**让 AI 刻意延后回答**）/ 广美（1800 名新生"轰"出教室）/ 兰州交大辛惠娟（给 AI 纠错）
  - "学生逃离的是无感不是学习"三层归因（课程与生命经验断连 / 知识触手可及 / 课程价值判断方式变了）
- **重叠说明**：教师角色转向母题库内已有多页覆盖（teacher-role-teaching-vs-education / ai-era-teacher-two-fates / gmw-teacher-role-international），本页聚焦 Hub 的机制区分与案例，不重复论述
- 关联：[[concepts/ai-native-teacher-formula]]（同作者）[[concepts/ai-restraint-blank-space-framework]] [[concepts/human-ai-collaboration-width-depth]] [[concepts/create-thought-space]]
- 更新 index.md + MOC（总页面数 65→66）

## [2026-09-22] ingest | "先做后讲"五活动链——把"用"前置的课堂重构实操
- 来源：微信公众号「刘欣教学设计」，2026-09-24 发布，2862 字（用户指定入库）
- 保存原文 raw/articles/2026-09-24-liuxin-five-activity-chain.md（全文 8595 字节 + 真实 sha256）
- 创建概念页 [[concepts/ai-lesson-five-activity-chain|"先做后讲"五活动链]]（scope: practice）
- **入库前增量评估**（已核查）：五活动链、教师三身份（体验设计师/思辨引发者/AI护栏员）库内均无
- 四项增量：
  - **查→辩→论→验→省 五活动链**：查（3分钟微型演讲，教师只补盲点纠偏差）/ 辩（"手机看老电影算新媒体吗"，不许用手机回答）/ 论（立场辩论 + 三组论证支架）/ 验（3/5/10 秒微实验观察表）/ 省（200 字发群，不许用 AI）
  - **教师三身份**：第三个 **AI 护栏员** 为库内新概念——"课堂上必须留下的，恰恰是学生自己做判断、自己负责任的那部分"
  - **翻转路径**：概念→案例→作业 改为 真实困境→工具→自我建构（奥苏贝尔有意义学习）
  - **护栏设计原则**："退，不是放。我退得越多，护栏就要设计得越细"——讲授的量减下去，设计的量升上来
- **定位区分**（避免与已有页重叠）：
  - 与 [[concepts/ai-era-teacher-as-hub]]：同作者姊妹篇，Hub 是"为什么"（理论），本页是"怎么做"（实录）
  - 与 [[concepts/ai-lesson-four-step-transformation]]：同作者，那页改**内容呈现方式**，本页改**课堂顺序结构与活动链**
  - 不重复"教师角色转向"母题（库内已有 5 页覆盖）
- 已建立双向链接（Hub 页 ↔ 五活动链页）
- 更新 index.md + MOC（总页面数 66→67）

## [2026-09-22] ingest | 中国教育报 9-15「智慧教育」专版 3 篇（提升学生AI素养系列①）
- 来源：中国教育报 2026-09-15 第04版「智慧教育」专刊，栏目「智见·本期关注：提升学生人工智能素养①」
- 用户提供版面文字版合集（本地文件）→ 按三篇独立文章**拆分**入库（各自有原文链接与作者）
- 保存原文 3 个 raw（均含真实 sha256）：
  - raw/articles/2026-09-15-jyb-collaboration-competency.md（3074 字）
  - raw/articles/2026-09-15-jyb-ai-thinking-catalyst.md（1122 字）
  - raw/articles/2026-09-15-jyb-data-portrait-growth.md（1776 字）
- 创建页面 3 个：
  - [[concepts/ai-collaboration-competency-framework|学生人机协同能力培养框架]]（scope: practice）
    杨俊锋（杭州师范大学教授，浙江省社科重大课题）**三段九法**：问题意识（用前立判断·用中设冲突·用后做复盘）+ 提问能力（精准·辩证·多维提问）+ 真实问题（真问题·真求解·真价值）
  - [[cases/yong-ai/chicken-rabbit-ai|AI作为思维催化剂——"鸡兔同笼"小学数学课例]]（scope: practice）
    王燕琳（舟山沈家门一小）**四轮 AI 追问链** + 能力进阶链（发散→有序→直观→建模→创新）+ 三层任务
  - [[cases/chuang-ai/data-portrait-growth|数据画像里的成长密码]]（scope: product）
    宁夏吴忠金积中心学校"数字成长秀"班队会 + **翻译数据三步**（具象化/故事化/游戏化）+ 硬成效（体质优良率 56.07%→77.78%，近视率 29.63%→20.48%）
- **入库前增量评估**：三个主题库内均无重叠（人机协同能力培养框架 / 鸡兔同笼课例 / 数据画像育人）
- 更新：cases/yong-ai/index.md（11→12）、cases/chuang-ai/index.md（8→9）、index.md + MOC（概念 67→68）
- 注：本专版为"提升学生人工智能素养"系列策划**第①期**，后续可能续发（按现行策略不做自动追踪）

## [2026-09-22] ingest | 中国教育报 9-22「智慧教育」系列②（2/3 篇入库）
- 来源：中国教育报 2026-09-22 第04版「智慧教育」· 智见·提升学生人工智能素养②
- 抓取方式：paper.jyb.cn 文章页（curl，注意该站 SSL 不兼容 urllib）
- **入库 2 篇**：
  - [[concepts/ai-general-education-rollout|普及人工智能教育的关键点]]（scope: practice）
    程蓓、曹培杰（中国教育科学研究院数字教育研究所）——**降成本四维落地框架**：① 课进课表（共同底线+多元载体、四大核心模块、校本"课程实施表"五列）② 师资能上课（三层次 + 爱沙尼亚AI Leap/新加坡路线图参照 + 三个"首次"定向支持）③ 公共供给担共性成本（平台建设/课程开发/工具筛选/安全审查/账号管理/运维上收）
  - [[concepts/human-ai-collaboration-five-steps|人机协同五步法]]（scope: practice）
    王晓勇（厦门市思明区教育局局长）——**人机协同五步法**（以人为主定目标 / 分工明确 / 协同执行理解逻辑 / 测试辨析认清边界 / 优化迭代闭环提升）+ 配套三件套（《思明区指南》、校园场景资源、AI大课堂城市实践基地矩阵）
- **评估后未入库 1 篇**：
  - 向世界讲述中国数字教育发展故事（黄璐璐）——展会现场报道（亚教展新品首发、35国采购代表），
    属**行业新闻动态**而非知识沉淀，信息密度低、对区域教研无直接可用框架，故不入库
- 原文 raw 2 个（全文 + 真实 sha256）
- 更新 index.md + MOC（概念 68→70）

## [2026-09-22] ingest | AI赋能跨学科教学——从"拼盘"到"熔炉"的六路实践
- 来源：中国教育报 2026-09-08 第04版「智慧教育」专刊（6 篇稿件合集，周二出版）
- 抓取：www.jyb.cn 文章页（**注意**：同期的 paper.jyb.cn 对应页面正文为动态加载，www.jyb.cn 侧有完整静态正文）
- 保存原文 raw/articles/2026-09-08-jyb-ai-cross-disciplinary.md（全文 16974 字节 + 真实 sha256）
- 创建概念页 [[concepts/ai-cross-disciplinary-teaching|AI赋能跨学科教学]]（scope: practice），整合 6 篇：
  1. **三遍提问法**（广撒网/深聚焦/挑错打磨）+ **AI 三角色**（情境催化剂/结构梳理器/认知冲突设计者）—— 丁德文（山东省教科院通用技术教研员）
  2. **AI 预答辩三条实操**（角色定位"只提问题不给答案" / 追问变"清单式支架" / 必交"修改说明"）—— 张楠（大连望海小学校长）
  3. **跨学科评价"三要三不要"**（指标少而精 / 坚守数据伦理出个人雷达图 / 正视技术局限防伪痕迹）—— 杨立成（河北景县龙华镇二小）
  4. **AI 进入探究的四个支架环节**（数据解释/变量梳理/证据比对/方案修改）—— 徐培培、温国蕾（北京房山）
  5. AI 备课"神助攻"（蚕的一生、小小气象播报员）—— 胡国强（长沙芙蓉区大同二小）
  6. **思维导图三阶段**（内化→转化→深化）—— 刘妙灵（深圳螺岭外国语实验学校）
- **入库价值**：库内 PBL 评价两页（赛课工具包 / 评价框架）只给出"拼盘式跨学科＝不认定整合"的**判据**，
  本页补上"**怎么走向真整合**"的**方法**——已与两页建立双向链接，形成判据↔方法闭环
- 更新 index.md + MOC（概念 70→71）

## [2026-09-29] ingest | 09-29 日报前三条评估后入库 2 篇
- 来源：2026-09-29 AI 教育日报（5 条）前三条的入库价值评估
- **入库 2 篇**：
  - [[concepts/haiding-ai-edu-practice|海淀AI教育样本——区级统筹的"政产学研用"组织范式]]（scope: practice）
    北京日报（中国教育信息化网转载）——**"智启"智能体的三方组织架构**（海淀教研院/教师进修学校出教研数据资产 + 智谱华章出模型底座 + 凯文×智谱合资公司做运营）；
    AI 把教师经验沉淀为"知识资产"；四校差异化路径（人大附小AI跨学科智能体 / 五十七中26位老师搭30个学科智能体 / 二十中《如何向AI提问》手册 / 交大附中分校"使用监测—问题收集—反馈优化"机制）；
    核心判断：**海淀值得被看见的不是资源禀赋，而是资源整合模式**
  - [[concepts/ai-native-school-time-redistribution|AI原生学校的时间重构——教育最稀缺的资源是儿童的生命时间]]（scope: research）
    芥末堆原创——**时间视角的教育哲学**：知识制度对应时间制度（含工业化溯源与1862年课表）；学校不可替代的三功能（空间/关系/动力）；
    重新分配一天（压缩学知识时间，还给创造与共同生活时间）；AI负责知识人负责人；**四个"反"**（含"算法保留30%空间"）；
    理论支撑（科利生命历程制度化 / 贝克尔人力资本 / 2026《Synthese》时间委托）
    ⚠️ **已在概念页与 log 显著标注：理念宣言、原点学院 2027-09 才落地、无实证**
- **评估后未入库 1 篇**：
  - 广东深圳：让好课堂留在雪域高原（光明日报）——援藏通讯报道，可迁移方法论仅"三级培训网络"一句，信息密度低，
    对区域教研无长期参考价值（若做对口帮扶方案可随时取用）
- 撞库：10 个关键词（海淀/智启/政产学研/察隅/援藏/双师课堂/原点学院/AI原生学校/时间密度/生命时间）**全部命中 0**
- 更新 index.md + MOC（概念 71→73）

## [2026-10-13] ingest | 家长如何划定孩子使用AI的边界（人民日报"四问AI+教育"①）
- 来源：人民日报 2026-09-03 第013版，「教育优质均衡发展·四问"人工智能+教育"」系列报道**第①期**（记者丁雅诵）
- 保存原文 raw/articles/2026-09-03-rmrb-ai-homework-parents.md（全文 11232 字节 + 真实 sha256）
- 创建概念页 [[concepts/parents-guide-ai-homework-boundary|家长如何划定孩子使用AI的边界]]（scope: practice）
- **入库前撞库**：8 个关键词（红线/绿线/算法驱动应试/白名单/分类分级/学生模型/代写作业/AI味）**命中 0**
- 核心增量（4 组可复用框架）：
  - **3 条红线 + 3 条绿线**（徐琳）：红线＝原始观察/情感顿悟/逻辑训练不可替代；绿线＝灵感催化剂/素材帮手/诊断助手（**但修改仍需孩子自己完成**）
  - **四个"不匹配"**（孟天广）：认知能力/学习能力/评价能力/伦理价值 → 主张**分类分级治理**＋开发"**学生模型**"
  - **大模型白名单制度**（陈志文）：进校产品不能只看技术指标、响应速度、调用成本，须将**价值导向、内容安全、知识体系**纳入考量
  - **"算法驱动应试"警示**（陈志文）：防止 AI 把"人盯人应试"升级为"算法驱动应试"
  - **执行缺口**：教育部《中小学生成式AI使用指南（2025年版）》已明确"小学阶段禁止独自使用开放式内容生成功能"，但**家庭监管盲区 + 工具内嵌难辨别**导致落空
- **入库价值判断：补上库内缺失的家长视角** —— 73 个概念页绝大多数是教师视角，涉及家长的仅 1 页（儿童AI陪伴风险），本页提供的是"给家长的话术与依据"
- 注：本系列为"四问"第①期，后续可能续发 ②③④（按现行策略不做自动追踪）
- 更新 index.md + MOC（概念 73→74）—— 由**自适应版 wiki_rebuild_index.py 安全追加模式**完成（自动补 2 条 + 更新计数）

## [2026-10-13] extend | 追加「学生视角」至五活动链页面（同一节课的学生版）
- 来源：微信公众号「刘欣教学设计」2026-10-13《当课堂不再从碎碎念定义开始》——**24级教技G7（学生第七组）撰稿，刘欣审核**
- 保存原文 raw/articles/2026-10-13-liuxin-student-voice-five-activities.md（全文 12389 字节 + 真实 sha256）
- **按 skill「同一主题的直接回应 → 追加」规则，追加而非新建**：新增第七节「学生视角：他们真实经历了什么」至 [[concepts/ai-lesson-five-activity-chain|"先做后讲"五活动链]]
- 撞库：8 个关键词（24级教技/第七组/学生视角/谁负责判断/不替你想/扫雷/出动了/碎碎念定义）**命中 0**；库内原本**无任何学生视角页面**
- **增量价值（教师版给不出的）**：
  - 对活动①的实证："听一遍和讲一遍是两回事。坐在下面听，你可以假装懂；站到台上讲，**理解是无法伪装的**"
  - 活动②的认知冲突实录："在问问题还是在**扫雷**"→ 自己发现"新媒体传播关键不是新设备而是**双向互动**"
  - 活动③的价值观引领实录：**"我是在用'晚了'当借口，掩盖'我不敢开始'"**（教师版说"不讲，让他们自己辩出来"）
  - **学生自己提炼的核心洞察**："整条链本质上是在重新分配'**谁负责判断**'这件事……这不是教学方法，这是教育目的本身"
  - **对"留白"的最佳表述**："肯把一小块'**不替你想、不替你兜、不替你圆**'的空地留出来"；"不是老师把灯全关了，是她把灯往我这边偏了一寸"
- ⚠️ **已在页面显著标注**：这是**单一小组学生的质性反思**，不是量化效果证据；可用于说明"设计意图如何被学生接收到"，不可当作"教学效果已验证"
- 更新 index.md + MOC（该页 sources 增至 2 条；索引由安全追加模式补 1 条 raw）

### [2026-10-13] chore | 五活动链页面增加「课程实录索引」槽
- 在 [[concepts/ai-lesson-five-activity-chain]] 页首新增「📚 课程实录索引」表（登记日期/视角/作者/一句话/写入位置）+ 追加约定表
- 现有 2 条：#1 教师版（2026-09-24，刘欣，设计意图 → 主体节）、#2 学生版（2026-10-13，24级教技G7，真实体验 → 第七节）
- 追加约定：教师视角写主体节 / 学生视角追加第七节 / 其他视角（听课者·教研员·家长·同行评议）新建章节后登记
- 表内已标注**各视角证据强度差异**（设计说明 ≠ 已验证效果）
- 页首提示"新实录请先登记一行再写入对应章节"，避免日后零散追加
- 同步写入 skill `thought-ingest` 注意事项 16（同一主题多视角材料 → 一页聚合 + 页首实录索引）

## [2026-10-15] ingest | "挖坑式"课堂与AI知识可视化（刘欣《教学系统设计》课·学生版）
- 来源：微信公众号「刘欣教学设计」2026-10-15，**24级教技G3 学生撰稿**（指导老师刘欣）
- 保存原文 raw/articles/2026-10-15-liuxin-pit-digging-knowledge-viz.md（全文 6372 字节 + 真实 sha256）
- 创建概念页 [[concepts/ai-knowledge-visualization-pit-digging|"挖坑式"课堂与AI知识可视化]]（scope: practice），含页首「课程实录索引」槽（本页对应《教学系统设计》课，与五活动链页分开维护）
- **撞库**：8 个关键词中 7 个命中 0（挖坑/Mermaid/知识可视化/迪克凯瑞/认知漏洞/关系图谱/放大错误）；"教学评一致"仅在 PBL 评价页作为概念提及
- 核心增量（三层）：
  - **教学法层**："挖坑式"——老师讲迪克凯瑞模型时提出"教学评一致性"，**不给定义**让学生用 AI 自检索画图，然后连续两次判定"全错"
  - **AI 使用层**（库内全新）：
    - 掉坑1.0 概念偏差 → **"AI 会把人的错误不断放大"**；"工具只会根据浅层关键词生成通俗化解释，无法输出教学设计的专业逻辑"
    - 掉坑2.0 关系混乱 → 老师：**"要想调用 AI 这个超级牛的助理，你得比它更懂这个理论"**；**"没有理解到位，关系混乱就是映射你自己内在也没有搞清楚"**
    - 出坑3.0 → **Mermaid 提示词三条经验**（箭头文字精简不交叉 / 节点文字简短防变形 / 布局整洁）
  - **学生洞察**："AI 分不清对错，很容易放大我们本身的认知漏洞；Mermaid 只是绘图工具，根源还是我们自己先把逻辑理明白"
- **与五活动链的关系**：同一作者、同一教学法思路（都靠"让学生自己撞"），已建双向关联；本页把该教学法命名为"**挖坑式**"
- 更新 index.md + MOC（概念 74→75）

## [2026-10-15] entity | 新建作者索引页：刘欣（"刘欣教学设计"）作品脉络
- 背景：用户发现该公众号内容渐多，要求建作者/系列索引页
- **完整盘点**（扫描全部 raw 文件的来源）：该公众号在库内已有 **21 篇原文 → 19 个页面**，是**库内最大的单一来源**（远高于之前估计的 7 篇）
- 新建 `entities/liuxin-teaching-design.md`（**entities/ 目录首次启用**）：
  - 一、方法论框架（教学设计 7 篇 + 教师角色 3 篇）
  - 二、批判与反思（7 篇）
  - 三、课堂实录（学生撰稿 5 篇，已标注证据强度为质性反思）
  - 四、跨篇脉络：**立场 → 主张 → 方法 → 课堂 → 证据** 五层结构；主线"AI 承担知识与效率，判断必须留在人这里"
  - 五、对区域教研的意义 + 更新约定（新文章入库时在本页追加一行）
  - 命名了三个教学法：**四步改造法 / 五活动链 / 挖坑式**
- **工具同步增强**：`wiki_rebuild_index.py` 增加 **Entities 段**支持（build_index 生成 + patch_index_append 追加 + extract_existing_rows 识别），entities/ 目录的页面今后自动进索引
- 更新 index.md（新增 Entities 段）+ MOC

### [2026-10-15] entity | 刘欣索引页增补「适用边界速查」
- 背景：该公众号内容占库内约 1/4（21 篇/19 页），但作者是**高校教师、授课对象是师范生**，需标注可迁移性
- 核实关键事实：`cases/yong-ai/tuiqiao-ai`（学段：初中/小学高段）、`sui-yangdi-ai-debate`（初中/高中）是**师范生设计的课例**（设计稿，非真实课堂实施记录）；`ai-lesson-five-activity-chain`（《教育新媒体创作实务》）、`ai-knowledge-visualization-pit-digging`（《教学系统设计》）、`edtech-course-process-assessment`（《现代教育技术》）均为**高校课程**
- 新增第五节「适用边界速查」：**20 条**逐条标注
  - ✅ 可直接用（13 条）：批判反思类全部 + 原生教师公式 / 五段式培训 / 微决策 / 问题三属性 / 四步改造法 / 工具层经验
  - ⚠️ 需改造（4 条）：AI-TPACK（DK 积累路径不同）/ 五条设计原则（"高支持环境"前提）/ **五活动链**（90 分钟→40 分钟需拆课时；"不许用手机"部分学校不可行）/ **挖坑式**（建议改"单点挖坑"）
  - 🔬 仅作参考（1 条）："学校里边不需要老师讲课"——高校语境，中小学不可照搬
- 三个现实约束：**课时 / 学生自主性 / 进度压力**；落地建议：**取其一环，而非照搬全链**
- 同步在「更新约定」中要求：**每新增一篇都补一条边界判断**，判断前先问"结论是在哪个学段、哪类学生身上得出的"

## [2026-10-15] ingest | 第八届智能教育论坛——AI进课堂的变化与隐忧
- 来源：光明日报 2026-10-14 第08版（记者陈慧娟、吴春燕），第八届智能教育论坛暨中国教育技术协会智能教育专业委员会第二届学术年会（珠海）
- 保存原文 raw/articles/2026-10-14-gmw-intelligent-education-forum.md（全文 6092 字节 + 真实 sha256）
- 创建概念页 [[concepts/intelligent-education-forum-2026|第八届智能教育论坛——AI进课堂的变化与隐忧]]（scope: research）
- **撞库**：16 个关键词中 **13 个命中 0**；仅"认知外包"（2 页）、"胡小勇"（2 页，但论点为问课/AI放大器）、"师—生—机"（1 页）相关
- **重叠检查**：`ai-education-four-risks` 仅"认知外包"一个概念点重合，**无本篇的数据与多专家判断** → 判定为增量
- 核心增量（四层）：
  - **正向变化**：汪琼（技术增强环境下可用更多时间做综合复杂的事）· 钟晓流（AI 解放教师，使其有时间倾听激励）· 章伟（教学从"点对面"变"点对点"）
  - ⭐ **"只有机器发生了学习"**（胡小勇）：教师用AI备课出题→学生用AI做题→教师用AI改卷，"在这样的闭环中，只有机器发生了学习"
  - ⭐⭐ **硬数据**：2025 年中国青少年研究中心对 7 省 **8500 余名**中小学生调查——AI 使用率超六成、超七成用于辅助作业、**超两成"更愿意依赖 AI 思考、不想自己思考"**
  - ⭐⭐ **陈丽："课堂是教学变革的落脚点，但不一定是撬动点"**——评价制度/教育文化不变，仅要求改变课堂教学模式，变革不可持续
  - 新概念：钟晓流"**精准的效率表盘**"（实时计算全班有效学习时间/普遍卡顿环节/连续滞后学生，"一个都不能少"从理想变可操作）；汪琼"**知道和掌握是两回事**"
  - 政策数据：全国 **509 所**人工智能教育基地校；《中小学生成式AI使用指南（2025年版）》《教师生成式AI应用指引（第一版）》
- **入库价值**：学界集体判断的横截面（7 位权威专家），与 `ai-education-four-risks`（报告视角）形成"风险清单 + 学界共识与数据"的完整论述
- 更新 index.md + MOC（概念 75→76）

## [2026-10-20] ingest | AI时代科学教育如何"做中学"（中国教育报 10-20 智慧教育）
- 来源：中国教育报 2026-10-20 第04版「智慧教育」，作者：山东省烟台高新技术产业开发区实验中学校长
- 保存原文 raw/articles/2026-10-20-jyb-ai-science-learning-by-doing.md（全文 8365 字节 + 真实 sha256）
- 创建概念页 [[concepts/ai-science-education-learning-by-doing|AI时代科学教育如何"做中学"]]（scope: practice）
- **撞库**：11 个关键词中 6 个命中 0（科学实验/初中科学/人机融合/误差思辨/思维记录单/…）→ **库内原无"科学学科+AI"专门页面，明确空白**
- 三层增量：
  - **开篇两个矛盾**（最有价值）：① 探究过程简化 vs 学生深度认知发展——仿真平台简化观测统计数据运算，**压缩了学生试错探究、自主研判、深度思辨的成长空间**；② 算法标准化评价 vs 探究过程个性化——预设算法难以捕捉临场生成的创新思路，**造成思维闪光点流失**
  - **三阶段递进**：人机交互（自主建构认知：生活化探究项目 + 与AI多轮认知对话 + 思维记录单）→ 人机协同（AI 从补位模式转向**认知伙伴关系**：仿真预演/变量筛查 + 高频数据捕捉，形成定性体验+定量采集互补证据链）→ 人机融合（智能诊断区分"操作不规范/方法不科学/原理理解不透彻" + 专属复盘 + 人机协同复盘建知识体系）
  - **两个可直接借用的课例**：力学定量探究（数据偏差来自人为操作/器材精度/环境干扰三分法）、物态变化探究（零散反常数据的分层排查，让微小误差成为深度学习生长点）
  - **一条不可让渡的边界**：实验设计、实地采样、基础操作、现象观察等核心探究环节，**必须坚持学生自主实践为主体**
- **重叠说明**：与 [[concepts/ai-cross-disciplinary-teaching]] 的"AI 四支架"（含误差归因）相似，但本页是**科学实验场景的具体化**；与 [[concepts/ai-plus-hi-collaboration-model]] 的递进模型区分（那为教师能力递进，本页为学生探究层次递进）
- 更新 index.md + MOC（概念 76→77）

## [2026-10-20] ingest | 别让信息科技课沦为"网页点读机"（周歌的信息科技课堂）
- 来源：微信公众号「周歌的信息科技课堂」2026-10-19，作者小周（**一线信息科技教师个人公众号**，非官媒）
- 保存原文 raw/articles/2026-10-19-webpage-activity-pitfalls.md（全文 9936 字节 + 真实 sha256）
- 创建概念页 [[concepts/webpage-activity-pitfalls-in-it-class|别让信息科技课沦为"网页点读机"]]（scope: practice）
- **撞库**：14 个关键词中 **10 个命中 0**（网页活动/互动幻觉/数据黑洞/技术过载/非必要不用/预制菜/点读机/公开课/评优课/军备竞赛/技术展示场）
- 核心增量（三层）：
  - **三个陷阱**（命名精准、可传播）：
    - **互动幻觉**——点击代替思考，拖拽匹配是"试错"不是理解，"三次之内总能蒙对"；**"手指在动，大脑却在休眠"**
    - **数据黑洞**——回收数据→显示正确率→表扬→继续下一环节，**"数据成了教学装饰品，而不是教学决策的依据"**
    - **技术过载**——**"教师花在网页制作上的时间，往往与学生获得的学习深度成反比"**；"你精心设计的每一个动效，都可能是学生认知通道上的路障"
  - **三条铁律**：① 非必要不用网页（自检："去掉它，学习效果会打折扣吗？"）② 互动必须制造**认知冲突**而非操作快感 ③ 数据必须形成**教学闭环**
  - **四个追问**：对应哪个学习目标 / 会发生什么认知过程 / 没有网页能否发生 / 网页介入是促进还是干扰 → **"不是会用多少工具，而是知道什么时候不用工具"**
- ⭐ **最有价值的是对评价机制的批判**：公开课/评优课看"热闹程度和技术含量"→ 网页活动复杂程度成了"创新性"的替代指标 → 教师被迫进入**军备竞赛**
  （这补齐了 [[concepts/pbl-competition-evaluation-toolkit]] 红线⑤"技术替代思考"的**机制解释**：不是教师爱堆技术，是评价导向倒逼）
- 另有"网页活动是**教学界的预制菜**——加热即食，卖相不错，但营养存疑"的比喻
- 更新 index.md + MOC（概念 77→78）

### [2026-10-20] revise | 修正「网页点读机」页面的适用范围定位
- **刘老师指出**：这篇文章覆盖的不只是信息科技课堂，**所有用互动网页开展教学的课堂都需要反思**
- **我的判断窄了**：入库时按文章举例的学科（信息科技）设定了 topic 和 primary_entry，把结论的适用范围当成了举例的范围
- **修正确认**：三个陷阱取决于**载体**（互动网页/互动课件）而非**学科内容**——
  - 互动幻觉：数学拖拽分类、语文连线题、英语单词配对、科学器材匹配，都是"试错三次能蒙对"的同构设计
  - 数据黑洞：希沃/雨课堂/ClassIn/问卷星的答题数据，任何学科都停在"正确率上屏→表扬→下一环节"
  - 技术过载：认知负荷理论不分学科
- 页面修改：topic 改为「课堂设计与评价（跨学科）」；primary_entry 去掉"信息科技"限定；**新增第六节「为什么这不止是信息科技课的问题」**（含跨学科同构表现对照 + 唯一差异在"例子" + 更强适用对象"互动课件依赖症的课堂"）；章节重编号
- MOC 描述同步放宽
- **教训**：区分"内容主题（举例）"与"适用范围（结论依赖的机制）"——判断方法是问一句"这个结论依赖的是那个学科的特性，还是那个载体/机制的共性？"

## [2026-10-20] ingest | 五站旅程：终·图·路·走·检（刘欣·教学设计总纲）
- 来源：微信公众号「刘欣教学设计」2026-10-20 23:01，作者刘欣（lusinda66）
- 原文 raw/articles/2026-10-20-liuxin-five-station-design.md（3337 字 / 9479 字节 + 真实 sha256）
- 创建概念页 [[concepts/five-station-lesson-design|五站旅程：终·图·路·走·检]]（scope: practice，15285B）
- **撞库**：23 个关键词中 **19 个命中 0**（克拉夫基/Klafki/Bildungsinhalt/Bildungsgehalt/五站/认知图谱/地形图/错因/讲三成/行程单/四件套/互评打回/翻车点/最小对立词对/副驾…）
- **定位**：刘欣这套方法论的**总纲**（标题问的是"力气该花哪"），不是单篇课例
- 三层核心增量：
  - ⭐⭐ **理论起点：克拉夫基（Klafki）的「内容 vs 内涵」**（库内完全空白）
    - **Bildungsinhalt = 内容（现成的）** vs **Bildungsgehalt = 内涵（要发掘的，且因人而异）**
    - 教学分析五问之首要："**在几乎无穷多可以教的东西里，哪些值得占用学生有限的时间**"
    - **"备课的核心不是讲明白知识点，而是回答'这个内容对这些学生的成长为什么重要'"**
    - **"AI 让'内容'贬值，让'判断'成为新的稀缺品"** → 教师若还当"内容投递员"就会越来越可有可无
  - ⭐⭐ **地形图 vs 导航**（最可迁移）：**知识图谱=地形图（对谁都一样）** vs **认知图谱=导航（一人一份）**。**"最容易踩的坑，是把地形图当导航"**。"只抄课本小标题，那叫书架，不叫地形图"
    → **补上了 [[concepts/ai-knowledge-visualization-pit-digging]] 缺的那一半**：画完地形图还不算备课
  - ⭐⭐ **N1–N5 错因分层**（学情画像具体方法）：同一件事五个学生卡在五个地方——N1 y不当元音(city) / N2 按字母数硬切 / N3 辅音连缀硬拆(**father→fa-ther**) / N4 重音错 / N5 例外当规则。**"学生卡在N1到N5的不同路口，没做导航，练得再多也只是把错练熟"**
- 五站详解：**终**（可观察动词+数量·"说到石碑前合影"）/ **图**（零件图+应用图）/ **路**（N1-N5导航）/ **走**（四件套：目标/任务/支撑/产出·**讲3成走7成**·"没有产出的体验点就是景点门前拍照就走"）/ **检**（五条清单·**互评打回"不是挑刺，是保命"**）
- **"AI 是副驾，盯仪表盘报数据；你才是握方向盘、决定此刻该不该踩刹车的人"** — AI 能批量生成最小对立词对/归错因清单/起草活动，但给不了"**此刻这个孩子卡在 N3**"的瞬间判断
- 五个翻车点 + 五站检查单
- **与已有关键关系**：本页=**教师备课设计流程**（终图路走检）；[[concepts/ai-lesson-five-activity-chain]]=**课堂学生经历流程**（查辩论验省）。**两页合起来才是完整"备课→上课"闭环**
- 同步更新：`ai-knowledge-visualization-pit-digging` 加"地形图vs导航"关联；`entities/liuxin-teaching-design` 计数 21→22 raw / 19→20 pages，§1.1 加行，§四 方法层+教学法3→4，§五 适用边界加第21条（⚠️框架可整用但100分钟体验课的时间配比需压缩；N1-N5最可迁移）
- 更新 index.md + MOC（概念 78→79）

## [2026-10-26] ingest | 教学设计不是流程表，是证据链——迪克·凯瑞模型（刘欣）
- 来源：微信公众号「刘欣教学设计」2026-10-25 12:42，作者刘欣
- 原文 raw/articles/2026-10-25-liuxin-dick-carey-evidence-chain.md（2959 字 / 8835 字节 + 真实 sha256）
- 创建概念页 [[concepts/dick-carey-evidence-chain|迪克凯瑞模型的九格与三条虚线]]（scope: **theory**，16729B）
- **撞库**：22 个关键词中 **17 个命中 0**（Dick/Carey/先决条件/技能层级/行为目标/形成性评价/总结性评价/心理动词/活动拼盘/集体礼貌/定点手术/情绪表达/九问/ADDIE/加涅/系统取向）
- ⭐ **这是一次伏笔回收**：`di-knowledge-visualization-pit-digging` 里只有一句"老师讲迪克凯瑞模型时补充提出教学评一致性"，**模型本体库里从来没有**。刘欣讲了一学期《教学系统设计》，库内存的都是"他怎么上课"，**唯一没存的是他课上教的那个东西本身**
- ⭐⭐ **解开昨天五站旅程的血统**：五站（终图路走检）是**迪克凯瑞九格的口语化简版**。映射：终≈①锚+④磨 / 图≈②拆 / 路≈③测+⑤选 / 走≈⑤选+⑥编 / 检≈⑦+⑧+⑨
  - **五站少掉的三格最要紧**：③测的**情境维度**（课时/场地/设备/班额）、⑧萃（判断**设计本身**有效性）、⑨**调**（定点手术）
  - ⭐ 尤其 ⑨："**整个模型只有这一格是'向后指'的。它是系统的活口：它承认设计一定会错，并把'改'写进流程，而不是留给老师的良心**"
  - **"五站旅程教你怎么设计；迪克凯瑞告诉你设计一定会错，并要求你改"**
- 核心命题：**"你的每一个决定，都要为下一个决定提供证据"**；**"别看方框，看箭头。方框回答'做什么'，箭头回答'凭什么'"**
- 关键区分：**"写教案是把一节课记录下来；做教学设计，是让一节课在发生之前就已经被推理过一遍"**
- 九格要点：①锚（可检验·"培养语文素养"不能当锚·**"锚偏一寸后面八格全偏"**）②拆（**"知识点是平行的，先决条件是嵌套的"**）③测（**"不是考试是校准"**·**"没有起点，由浅入深只是形容词"**·写"基础一般"是评语不是分析）④磨（**模型分水岭**·行为+条件+标准·心理动词替换表）⑤选（**"策略的本质是顺序与节奏"**·**"删掉某活动目标还达得到吗"**）⑥编（**"好材料唯一标准：有没有替学生完成那段最该由他自己走的思维"**·"把结论写太满的讲义都在替学生走路"）⑦形成性（**"我的设计在哪里断了"**·**"这不是形成性评价，这是集体礼貌"**·看手和笔别只听嘴）⑧萃（**"是提炼不是打分"**·判断设计有效性而非学生过关）⑨调（**活口**·定点手术）
- 三条虚线：⑦→③（"学生没学会，有时不是教法问题，是你对起点估错了"）/ ⑨→②③④⑤⑥（"**定位不到具体环节的修改，只是情绪表达**"）/ ⑨本身（**"好的设计不是一次做对的，是改对的"**）
- ⭐ **"真正发生在课堂里的，只有中间三格。其余六格全在课前课后"** → **"写教案只是第六格，重心六成在课前与课后"**
- 九问自检表（9 环节 × 不达标信号）+ 收尾："模型不保证你上得好，它保证你的设计可以被追问"
- **"证据链"两个含义必须区分**：学习证据链（学生表现，见赛课工具包/AI-TPACK）vs **设计证据链（设计决策，本页）**
- 同步更新：`five-station-lesson-design` 加「〇、理论源头提示」节（五站是简化版 + 缺三格 + 建议用法"口诀负责记得住，模型负责查得严"）；`ai-knowledge-visualization-pit-digging` 补注模型专页已建；`entities/liuxin-teaching-design` 计数 22→23 raw / 20→21 pages，§1.1 加行，§四 方法层+教学法 4→5，§五 边界加第 22 条（✅ 通用理论，但日常课只需 ①④⑦ 三格）
- 更新 index.md + MOC（概念 79→80）

## [2026-10-26] append | 五活动链 §7.8 全班集体翻车（24级教技G10，第三个视角）
- 来源：微信公众号「刘欣教学设计」2026-10-16 08:55，**24级教技G10 学生撰稿**
- 原文 raw/articles/2026-10-16-liuxin-student-voice-g10-class-flunk.md（2929 字 / 9092 字节 + 真实 sha256）
- **判断：追加而非新建**——这是《教育新媒体创作实务》的**第三个实录**（教师版 09-24 + G7 学生版 10-13 + **G10 学生版 10-16**），撞库显示 `老电影`/`奥苏贝尔`/`有意义学习` 均已命中五活动链页
- 页面改动（17734 → **25677 字节**）：
  1. **课程实录索引**加第 3 行
  2. **证据强度说明**更新：教师版=设计说明 / G7=质性反思 / **G10=含"学生自己拆解设计意图"（意图被接住的证据）**
  3. **活动②「辩」**补两小节：**苏格拉底四轮追问链** + **⚠️ 组织方式两处记载不一致（待核实）**
  4. **新增 §7.8** 全校集体翻车（5 个小节）
- ⭐⭐ 四个真实增量：
  - **① 苏格拉底四轮追问链**（可直接当模板）：手机是新媒体→那手机看老电影是吗？"是，因为用了手机" → 新媒体核心特征是什么？"**双向互动**" → 单纯安静看老电影能双向交流吗？"不能，只能被动接收" → **早年在电视上看老电影，本质有区别吗？"没有"** → 所以不属于！**"设备不等于媒介，缺少双向互动，就还是传统传播"**
    - 结构：承认说法 → 抽核心特征 → 用特征检验 → **找"换了设备但本质相同"的等价反例** → 结论自己塌出来（教师不宣判）
    - ⭐ 第4轮（电视看老电影）是关键——**把"设备"这个干扰项彻底剥离**
  - **② 奥苏贝尔 表面学习 vs 理解性学习**完整对照（库里此前只有一句"新知识须与已有经验建立联系"）：表面学习=关注外在标签/孤立记忆/**"知识像临时存进大脑，考完试很快清空"**；理解性学习=连已有知识/吃透本质/举一反三
    - ⭐ 学生的归因很重要：**"并不是因为我们完全没有学过，而是理解只停在表面。记住了'手机''新媒体'这些词，却没有真正理解它们之间的关系"** → 印证五活动链"定义先行为什么失效"的起点判断
  - **③ ⭐⭐ 学生自己拆解"设计意图"四点**（前两批材料都是"我感受到什么"，这批是"老师为什么这么设计"）：巧用认知陷阱制造认知冲突 / 用亲身经历激活理论 / 重塑媒介判断思维 / 锻炼思辨习惯
    - **"全班集体答错的名场面，比枯燥的理论讲解冲击力强百倍"** — 教师培训讲"要制造认知冲突"可直接引这句
  - **④ 量化事实：14 人连续答错**（前两篇无此数字）
- ⚠️ **不建议猜的差异已标注**：教师版记载活动②是"小组讨论+不许用手机回答"，G10 记载是"随机点一整排依次作答"。可能是①同课不同环节 ②不同班级调整 ③学生记忆偏差——**标注为待核实，未做判断**
- 学生提炼："新媒体的'新'不在于新软件新设备，而在于新逻辑新关系新能力" / "学习的终点不是拿到分数，而是学会如何思考"
- 局限已写明：**两批学生实录都是单班质性反思，无前后测无对照班**——只能说是"设计意图被感知并复述"，不能说是"效果提升的量化证据"
- 同步更新：`entities/liuxin-teaching-design` 计数 23→24 raw（页面数不变），§三 课堂实录加 G10 行，§五 适用边界加第 23 条（苏格拉底追问链 ✅ 可迁移）、第 24 条（表面学习诊断 ✅ 不分学段）
- 更新 MOC（页面总数不变，仍是 80 个概念 + 追加实录）

## [2026-10-26] ingest | 温州智慧校园3.0——市·区·校三级治理（中国教育信息化网）
- 来源：中国教育信息化网（ictdedu.cn）2026-10-29，**原发温州市教育局**；场景为温州市中小学智慧校园3.0项目研讨会暨领航校长高级班沙龙（瓯海区外国语学校，250余人）
- 原文 raw/articles/2026-10-29-wenzhou-smart-campus-3.md（2699 字 / 8191 字节 + 真实 sha256；GBK 编码，curl 后 decode('gbk')）
- 创建概念页 [[concepts/wenzhou-smart-campus-3-governance|温州智慧校园3.0——市区校三级治理与"五个转变"]]（scope: practice，14834B）
- **撞库**：17 个关键词中 **12 个命中 0**（串珠成链/一核多景/五个转变/择优推荐/批发式/循证教研/智阅协同/教学法第一/辅助不替代/领航校长/数据治理中台/温州）
- ⭐⭐⭐ **本页补的是库内最缺的一块：区县一级该干什么**（刘老师本人岗位视角）
  - **市**：搭公共底座（数据治理中台/可视化平台/TeleAgent/省级平台/通识三阶课程·覆盖率目标>80%）→ **"学校只管把场景做深做透"**
  - ⭐ **区（县）：定位就是"服务"** —— 建机制定清单 · 重过程搭平台 · 强保障给倾斜 · 守底线防风险
  - ⭐⭐ **"择优推荐、不搞批发式申报"** — 全文最有原则性一句。批发式=为覆盖率每校都报，凑数量凑指标，每校都做浅；培育逻辑天然要求筛选
  - **校**：校长第一责任人（**破局的实践者/审视的研究者/带队伍的领航者**）+ 四件实事（定好选题/写好方案/守好场景/把好节点）
- ⭐⭐ **五个转变**（温州 2.0→3.0）：机制（标准化创建→高水平培育）/ 形态（应用驱动→**师生机人机协同**）/ 结构（五维指标→**基础性+发展性+创新性**）/ ⭐**评价（"建了没有"→"用得活不活"）** / ⭐**理念（"数字化+教育"→"教育+数智技术"）**
  - 第5条是**主客关系倒转**：技术从主语变成工具
- ⭐ **三个根本转变**：标准之变（市里定标准→**市里提方向、学校定方案**）/ 尺度之变（填表→**真问题真解法真成效**）/ 目的之变（有了什么→**育人方式变化**）
- 方法论：**"一核多景、串珠成链"**（定核心→选场景→讲相关→画路线→列成果）+ "场景即应用、案例即路径" + 每校讲清"**数据怎么流/成果怎么用/谁给谁支撑**"
- ⭐ **三校样本各有一可借点**：
  - **瓯海区外国语学校**（叶会乐）：浙江省一等奖"发现式学习"为基底 + **"生疑→定向→重构→创造→进化"新发现式学习闭环** + 校本课程《瓯窑数字修复师》《榉园龙舟智造》《温州方言智能创作》→ **从"用AI"到"造AI"**；⭐**选题全是本地文化题材**（黄陂可照做：木兰文化/盘龙城/汉绣/楚剧）
  - **温州艺术学校**（陶光胤）：⭐**"不拼投入、拼思路"**；AI智能练琴（反馈从"下一节课"到"**下一秒**"）+ **自研低成本"艺术品扫描箱"**（立体作品分钟级电子化）+ "AI三分钟/实操作业/火种教师"机制
  - **龙湾区实验小学**（张洁雅）：⭐⭐直面**"有数据≠有证据、有工具≠能改进"** + **"机器管'对不对'、老师管'好不好'"**（智阅协同）+ 《盘古开天地》**同课同构实证数据**→经验走向**循证** + "一场景·一方案·一团队"
- ⭐ **王佑镁（浙江东方职院校长）**："**教学法第一、人工智能第二**" + 三原则"**辅助不替代、透明不黑箱、赋能不僭越**" + **教师行动清单**（每周用AI改一次教案/每月搭一个教学智能体/每学期参与一次AI教学赛事）
- ⚠️ **局限已写明**：① 会议报道非研究，三校均汇报摘要、无实施数据无成效对比 ② **TeleAgent 环节是产品发布，含"登录送积分"，收录功能定位但不作推荐依据** ③ 温州发达地区，公共底座黄陂不具备同等条件，能借的是方法论与职责划分 ④ "3.0"是温州版本号 ⑤ **温州2.0的"五维创建指标"与全球智慧学校倡议五维度不是同一套**
- 建立 4 处双向关联：`regional-ai-edu-path`（横向图景 vs 纵向治理）、`smart-school-five-dimensions`（⚠️ 非同一套五维，但三维培育是迭代参考）、`webpage-activity-pitfalls-in-it-class`（"有数据≠有证据"区域层 vs "数据黑洞"课堂层）、`ai-general-education-rollout`（"公共供给担共性成本"的地方实践版）
- 新增第六节 **对黄陂区电教站的 10 条具体参考**（含区级教师行动清单改造、本地文化选题、同课同构循证）
- 更新 index.md + MOC（概念 80→81）

## [2026-10-26] distribute | 刘老师碎片摘录集（两份）分拣并入 9 个概念页
- 素材：`#人机共生的知识库构建之路.txt`（5726B）+ `@ai教育反思.txt`（9484B），刘老师本人整理的碎片摘录集
- raw 存档：`raw/articles/2026-10-26-fragments-ai-edu-reflection.md`（9821B，真实 sha256）；知识库那份存于 hermes-knowledge 库
- **逐条撞库后分拣，只收真增量、跳过已有**（田爱丽/助产士/江丰光四阶段/张家凯/管道容器/高位转移/"只有机器发生了学习"/提对问题/过程型考核 等均已有，未重复收录）
- **ai-education 库 5 页追加**：
  - [[concepts/ai-empower-new-paradigm]] 加 **田爱丽「可编码/不可编码」**:AI 承担知识传递/数据采集/初步反馈(可编码),教师承担点燃好奇心/组织有温度讨论/捕捉情绪变化/引导价值判断/设计真实任务(不可编码);**"教师变得更重要了"** + **"从'讲台上的圣人'到'学生身边的教练',是专业性的升维"**
    - 同页加 **刘欣「技术是助产士，也是麻醉剂」**:可放大观察/感知/连接,也可**替代观察/用数据画像固化自我/用预测未来压缩当下**;与"AI是实习生不是替身"、"圣人→教练"构成一组教师立场
  - [[concepts/ai-restraint-blank-space-framework]] 加 **两把标尺**:①**"是超级答案制造机,还是认知支架?"**+刘老师原创两问(**"你有没有真实的教研增益?学生有没有真实的学习收益?"** — 狠处是把教师自己算进收益核算) ②**"老师替学生想了,还是推着学生想?AI替学生想了,还是推着学生想?"** + **"克制与留白是传统课堂要修炼的教学能力,也是要让AI学会的工作能力"**(把留白从教师修养变成产品设计要求)
  - [[concepts/ai-education-misuse-analysis]] 加 **豆包「外包闭环」**:"老师用豆包做课件→学生用豆包写作业→家长用豆包检查→老师用豆包批改→家长问豆包孩子学得怎么样→豆包说挺好的。**从头到尾唯一在学习的就是豆包**";剖出闭环稳定性来源=**每一环都有人受益,唯独没人在学习**;+「机器学习」新解;+外包/协同分界线(**AI做了之后人有没有变得更会做**)
  - [[concepts/ai-destroys-zpd-cognitive-analysis]] 加 **⭐⭐生产效率≠学习效率**(cognitive offloading 的关键区分):专业人士用已具备能力换效率=真提效;学生卸载掉的**正是要形成的能力**;推论=**"我自己用AI很高效"不能推出"学生用AI也高效",两者目标函数不同**
  - [[concepts/ai-science-education-learning-by-doing]] 把"效率提升发生在哪个环节,认知损失就发生在哪个环节"**可操作化为定位方法**:找到效率增益点→问该环节原本要求学生做什么;补四行对照表(观测统计→试错探究/检索→筛选判断/生成→构思表达/记忆→可省)

## [2026-10-26] ingest | 四代教师培训与 Plus 版（刘欣接续李琰辉框架）
- 来源：微信公众号「刘欣教学设计」2026-10-30 16:02，作者刘欣（lusinda66）
- 原文 raw/articles/2026-10-30-liuxin-four-generation-training-plus.md（2119 字 / 6399 字节 + 真实 sha256）
- 创建概念页 [[concepts/four-generation-teacher-training|四代教师培训与 Plus 版]]（scope: practice，12667B）
- **撞库**：18 个关键词中 **15 个命中 0**（四代/李琰辉/产出导向/可清点/替代性完成/真场景/小产出/强伴随/能迭代/主体觉醒/交付物/满意度/isw）
- **谱系说明**：四代划分是**李琰辉**提出，本文是刘欣的**接续批评与升级**（不是原创），已在 frontmatter 与正文标注
- 四代：讲座式 → 研讨式 → 技能工作坊式 → **产出导向式（学员即生产者）**
- 第四代三条真贡献：① **终点从"讲完"→"交出"**（过去看气氛和问卷，现在看学员手上产出）② **填上"知道"到"做到"的沟**（"讲座的问题从来不是内容不好，是内容停在耳朵里"）③ **学员是生产者不是容器**（"讲师要交出控制权——不再控制所有人走到哪一步，只控制最后的规格"）
- ⭐⭐⭐ **核心洞察：产出导向在 AI 时代失效**
  - **"当产出导向把'可清点'当成唯一验收标准，而'可清点'的东西在 AI 时代最容易被'替代性完成'"**
  - 隐性成长（观念转变、主体性思考）**因不好呈现而被忽略**
  - 现象：AI 一键生成 + 高密度资源包，**拼装**出几百份 PPT/整学期教案，"**脑子并没有真正动起来**"
  - ⭐ **"动作上极致的繁荣，掩盖了认知上可能的怠惰"**；回去后"**缺乏个人真实建构的替代品依然会吃灰**"
  - **核心矛盾表**：可清点→易被替代 / 难呈现→被忽略
- ⭐⭐ **Plus 版**：链路=发现真痛点→拆解真问题→调教AI生成V1→批判性修改→形成V2
  - ① **真场景**：不用"完美假数据"，用老师下周一的真课 ② ⭐**小产出**："**微小但深刻，胜过宏大但空洞。1件能深度思考过的，比十件好看的更值钱**" ③ ⭐⭐**强伴随**：作品出来**立刻**给反馈、当场改再输出，**至少一个完整来回**；"**培训越进化，对培训师的要求越高**" ④ **能迭代**：产品至少迭代一轮才有资格验收
  - ⭐ **"理想状态下，必要的产出里应该保留产品设计的思考轨迹和改进方向数据"** → **这是防 AI 代劳的检测手段**（成品分不出谁做的，思考轨迹骗不了人）
  - 分界线：第四代="离场时手里有什么"；Plus="拿回去还知道怎么继续优化"
- ⭐⭐ **「主体」定义**："不是指他能独立完成一件件作品——**那顶多叫熟练**。主体是指教师能**自己在课堂里发现问题**；能**判断这个工具该不该用、什么时候不该用**；能**在没有人给他图纸的时候，自己画一张**"
- ⭐ 规模判断："1-2 天别指望有高质量大产出，**ISW 五天就磨了 10 分钟的课**，含金量在于以小见大"
- ⭐ **新增第七节：对刘老师 120 分钟培训的改造建议** — 指出两头都有病（讲演为主=第一代"内容停在耳朵里"；加产出=第四代"替代性完成"），中间位置=**带走一个能自己继续改的东西 + 一次被追问过的思考轨迹**；三个动作：① 带真实材料来（真场景）② 产出压到极小：只跑通一个页面入库（小产出）③ **跑之前先写"我认为该不该入库，为什么"，跑完对比（留思考轨迹）**
- ⚠️ 局限已写明：① 经验总结非实证 ② Plus 版作者自称"探索"，未成熟 ③ **强伴随成本极高，大班额几乎无法做到，需 AI 助教或分组** ④ 观念类/政策类培训难设"产品" ⑤ "主体"标准偏主观，培训结束时难以测量
- 建立 6 处双向关联：`ai-training-five-stage-design`（单场结构 vs 模式演进）、`ai-education-misuse-analysis`（豆包闭环课堂版 vs 拼装式产出培训版，同一机制）、`webpage-activity-pitfalls-in-it-class`（互动幻觉 vs 拼装式产出，同族判断）、`dick-carey-evidence-chain`（思考轨迹=培训场景的证据链）、`pbl-competition-evaluation-toolkit`（过程性证据链的评价化落地）、`ai-destroys-zpd`（生产效率≠学习效率的培训推论）
- entities：25 raw / 22 pages，§1.1 加行，§五 边界第 25 条
- 更新 index.md + MOC（概念 81→82）

## [2026-11-03] ingest | 教师是 AI 时代的天然生产者（差评X.PIN 访谈）
- 来源：今日头条·差评X.PIN 2026-11-03 10:31，3998 字，两个一线教师深度访谈
- 原文 raw/articles/2026-11-03-chaping-teachers-ai-density.md（11740 字节 + 真实 sha256）
- 创建概念页 [[concepts/teachers-as-ai-tool-builders|教师是AI时代的天然生产者]]（scope: practice，14949B）
- **撞库**：22 个关键词中 **17 个命中 0**（常昊男/周斌/清华附中/华图/差评/AI浓度/提示词工程师/游戏树/化学游戏/320版/PK对战/豆包工作/算力积分/备课功底/外行/机械劳动）
- ⭐⭐⭐ **核心：换了一套叙事** — 不是"老师要学会用AI"，而是**"技术门槛消失后，老师原有的专业能力终于能直接变成产品"**
  - ① **"老师这行，天生就是提示词工程师"**：整天给学生提要求、批作业、不行打回重做 = 提示词工程早已炉火纯青，"只是自己不知道"
  - ② **"当写代码的门槛消失之后，真正决定东西好不好用的，其实是老师最原始的备课功底"**：游戏关卡不是AI想的，是老师把**学生常犯的错**总结出来拆成题目；"AI 只是顺着他的思路出题，顺便把界面做好看些" → ⭐注意分工方向是**人做内容、AI做界面**，工具越强人的专业性越不可替代
  - ③ **"没人比他们更懂日复一日的机械劳动了"** → ⭐反直觉：**技术能力不是门槛，痛点深度才是**
- ⭐ **解释了"为什么外行做不好教育产品"**："外行终归摸不准教学的门道"；**"你没有办法去优化它，因为你不知道它好在哪、不好在哪"** → 外行能做出功能完整的产品但无法迭代，因为迭代依赖教学判断力
  - 对区域含义：**采购成套方案 vs 让一线老师自己做，不是效率差别，是"能否知道好在哪"的能力差别**
- 两个极端样本：
  - **常昊男（清华附中化学）**：教满六年后辞职去**字节做AI教育产品4年**，去年被校长请回；一周只上六节课，其余带全校研究AI。痛点="纯碱不是碱，干冰不是冰"**很难判断学生是不是真懂了**（PPT讲得口干舌燥→作业都对但考试错误率高）。做法=AI做化学游戏+课堂**PK对战**投大屏；**时间成本是PPT的1/10**；会先试玩排查科学性硬伤。⭐**"站过讲台的才知道，能让全班抬头有多难"**
  - **扩散效应**（最有价值）：曾建川收作业小程序（二维码一扫谁交谁没交）；姜兴来"**游戏树**"挂八九个竞赛小游戏一天用掉3000积分；学校先买**200万积分两月用光又补600万**。常的三年目标="高考前把这棵化学游戏树玩完基本能考80分"
  - **周斌（华图襄阳辅导员）**：教育专业**没碰过代码**，3个月（8/3→10/30）**迭代到V320**（一天3版多）。起因只为省填表（打卡积分要企业微信手填，一人带四五十人）。路径=算分→整合散落数据→学员档案→督学助手→岗位匹配→选岗导出。效果=**每天省2-3小时**+每人专属学情报告（细到"概括归纳怎么做""综合分析怎么答"）。痛点原状="辅导员和家长只能看见**分数和正负号**，除此没有任何分析"
- ⭐⭐ **"用归用，但绝不把方向盘交给 AI"**（周斌）→ **跨来源独立复现**：五站旅程里刘欣说"AI是副驾，你才是握方向盘决定该不该踩刹车的人"。**两个作者两个领域同一个比喻**，撞库显示全库"方向盘"仅两处，本页是第二处
- ⭐ **谈心为什么AI干不来**（最具体的场景）："AI 确实能写出挺周全的话术，但直接冰冷地发给学生，很多学生也不一定能够接受。**一个刚考砸了的学生，要是收到老师转发过来的一段 AI 建议，多半只会觉得心里凉凉**。只有辅导员看完分析、心里有了数，再把人叫过来畅聊一会儿，学生才听得进去" → 问题不在内容对不对，在**谁在说、说不说得出**
- 另两句："学生对AI其实挺包容的，只要东西有用。**真让人嫌弃的，往往是花里胡哨却学不到东西的内容**" / "**把省下来的时间，花在那些没有标准答案的学生身上，才是 AI 永远完不成的课题**"
- ⭐⭐ **新增第六节：对教师培训的直接用途** — 换开场叙事：现在教师第一反应是"我不会"，替代叙事是**"你早就会了——你每天给学生提要求批作业打回重做，那就是提示词工程。你缺的不是能力，是知道自己有这个能力"**
  - ⭐ **价值在于把"学习"变成"认领"**：畏难心理的根源不是难度，是**位置错认**（"我是被技术淘汰的那一方"）。**改位置比降难度有效**
  - 三个动作：① 让教师写出最拿手的"批改话术"再对照 prompt 结构 ② **先讲痛点再讲工具**（痛感是动力）③ 降低首次产出门槛（不要求做游戏，只要求做个小工具解决自己一件麻烦事）
  - **区域推进启示**：清华附中不是"全员培训后人人会用"，而是**一个种子教师+年级组长+竞赛教练**先跑起来；**最小可行单元可能是一个种子教师 + 一笔算力额度，不是一轮全员培训**
- ⚠️ 局限已写明：① 自媒体访谈非研究，无成效数据 ② **两个案例都是极端个例**（常昊男有字节4年AI产品经历；周斌320版非凡人节奏），不可作普通教师参照 ③ **含产品曝光**（豆包/飞书积分及金额明确），只取判断不取产品名，不作采购依据 ④ "老师天生是提示词工程师"是**修辞性判断**，适合做激励性开场不适合做能力评估标准 ⑤ 扩散效应可能有**幸存者偏差**（清华附中顶尖学校，积分两月用光在多数学校不会发生）⑥ 两个案例都在"工具制造"层面，**做出来≠有效**
- 建立 7 处双向关联（五站旅程方向盘/原生教师公式/四代培训/可编码不可编码/网页点读机/温州治理/五活动链）
- 更新 index.md + MOC（概念 82→83）

## [2026-11-03] ingest | 教师AI应用的现实困境——助攻还是越位（中国教育报 11-03）
- 来源：《中国教育报》2026-11-03 第03版「新闻·视点」，记者焦以璇/梁丹/胡若晗/李帆，约 4700 字
- 原文 raw/articles/2026-11-03-jyb-teacher-ai-tech-mastery.md（5087 字 / 15189 字节 + 真实 sha256）
- 创建概念页 [[concepts/teacher-ai-dilemma-2026-survey|教师AI应用的现实困境]]（scope: practice，19091B）
- **抓取注意**：paper.jyb.cn 是 IIS/ASP.NET，**urllib 会 SSLV3_ALERT_HANDSHAKE_FAILURE，必须用 curl**；本页 h5 版是 **utf-8**（不是 gbk）
- **撞库**：36 个关键词中 **20 个命中 0**，但发现**库内已有三个强相关页**（teacher-ai-application-guidelines / teacher-ai-report-2026 / ai-education-current-state）→ **据此决定只收增量、不重复政策条文与数据**，并在页面开头写明三页分工
- 三层增量：
  - ⭐⭐⭐ **地方规范三种形态**（库内全无）：山东省教育厅"**教师是教学设计的责任主体**"，严禁AI"直接替代"备课授课，但允许"**辅助探究、启发思考、优化反馈**"；**湖北省武汉市江岸区教育局建立「能用、慎用、禁用」三类场景分级管理机制**（⭐对黄陂区是同城同级可比对象）；浙江等省陆续出台。共同指向="**鼓励合理使用，禁止越界替代**"
  - ⭐⭐ **核心困境"助攻还是越位"**（库内全无）：四组具体设问——AI辅助写教案是"启发思路"还是"代写代办"？学生用AI查资料是"辅助学习"还是"**思维外包**"？→ **"浅层应用有余、深层融合不足"**；"普遍来看教师还没跨越从'会用'到'用得好'的门槛"
    - 葛丽亚（邢台襄都区）的培训现场困惑："这节课用了3次AI是不是太多了"；引导法="闭上眼想一遍流程，教学难点痛点在哪？AI能不能解决？"；美术教师案例**自己意识到"是不是替代学生表达了"**；解法反转=**让AI根据学生的表达生成画作，引导学生用更精准语言让作品表现力更强**（AI成了学生表达的镜子而非替代品）
  - ⭐⭐ **三个库内没有的新概念**：
    - **AI 均质化**（窦文韬，北京十一学校）："**AI有均质化的倾向，你的思考越少、个人色彩越弱，输出的内容就越相似**"；对策=**用AI之前学生必须先画出思维导图、拿出初步方案，再让AI完善**
    - **遇强则强 + 手握种子**（王林浩，河南周口文昌小学）："**AI是遇强则强、遇弱则弱**"；"**如果你空空如也，那你也不能指望AI凭空给你变出一座花园，你得手握种子才行**" ← 对应余胜泉（北师大）"**内部认知网络与外部认知网络匹配、持续互动、产生有意义连接，从而增强人的认知能力、塑造认知格局**"
    - **技术的影子**（胡姣，中国教科院）：确立**以学习治理为核心的主体意识**（对学习目标/认知投入/人机分工主动统筹，警惕师生过度依赖）+ 发挥人类独有优势（**情感劳动、创造力与伦理判断，是教师不可让渡的职责**）
- ⭐ 胡小勇（华南师大）："**不能再用旧尺子量新世界**"；"从'怎么做更高效'的**工具理性**转向'为什么这么做'的**价值理性**" ← **与克拉夫基"内容vs内涵"是同一个转向的中德两版**
- 四个一线案例：**罗晨**（贵州乡镇小学，指令AI生成本土化风俗素材补齐乡村资源短板，分层教学常态化）/ **窦文韬**（AI均质化对策）/ **朱明鲲**（广东实验中学，OpenMAIC平台让**3个AI智能体扮演不同学派科学家**就每份证据交锋，学生自己判断哪种更可信）/ **王林浩**（扮演"小白"与星光教师智能体共创，⭐**AI识别《观潮》是写景散文而非照搬科学实验**，转而把握"真实问题/学生主体/实践主线/反思复盘/表现性评价"五要素，设计"为什么钱塘江大潮是天下奇观"问题驱动）
- ⭐⭐ **窦文韬人机协同三要点**（可直接做区级培训纲目）：①**分清主次**（教师始终居主导，不能为技术方便放弃教学方向把控）②**划清辅助边界**（AI可做信息检索/数据整理，但**教学设计、学情判断、价值引领绝不能外包**）③**强化把关意识**（AI内容须真实性校准，教师是"守门人"）
  - 反向警示："**不能反过来为了让课堂效果更华丽引入AI，而把传统课堂中那些已经成熟的东西丢掉**"
- ⭐ **三个认知层面条件**：有深厚学科知识体系才能提出好问题 / 有敏锐教学洞察力才能判断AI输出适切性 / 有清晰育人目标才能赋予技术以教育意义
- ⭐ 可引用区域数据：上海奉贤**6000余名**教师全覆盖 / 深圳福田多学科AI工具包+**千余个**案例+"先锋班" / 江苏滨海、贵州罗甸骨干引领分层研修
  - 胡姣："**AI属于新兴教育技术，仅凭教师个人的摸索，很多人只能停留在浅层使用**" → 为"区域必须组织培训"提供依据
- ⭐ **辟谣价值**：网络传言"禁止教师用AI备课"源于部分自媒体把"规范使用"解读为"全面禁止"；胡姣澄清"指引、细则恰恰是在**为教师划定安全边界**，而不是给技术应用套上枷锁"
- ⚠️ 局限已写明：① 记者调查非研究，案例为受访者自述无成效数据 ② **政策条文与8.6万数据已有专页，本页不重复**（仅补库内缺失的 **69.4%**）③ ⭐**"能用/慎用/禁用"三类清单未公开，页面第二节档位是常识性推测非原文**（已明确标注）④ 案例皆为成功样本存在选择性呈现 ⑤ "遇强则强"易被误读为"能力强者才配用AI"，忽略工具设计与培训支持等外部条件
- 建立 10 处双向关联（指引/report/current-state/温州/网页点读机/五活动链/五站旅程/教师造工具/可编码不可编码/认知卸载）
- 更新 index.md + MOC（概念 83→84）

### [2026-11-03] revise | 教师AI困境页补充「主理人·划线人·守门人」三类比
- **刘老师提出**：为窦文韬人机协同三要点拟三个类比 —— **主理人 / 划线人 / 守门人**，要求补充进页面
- 判断：三个类比**对仗工整**（都以"人"结尾）、**每字对应原文核心动作**、**可记忆可复述**，比原三句短语（分清主次/划清辅助边界/强化把关意识）更适合培训传播
  - ① 分清主次 → **主理人**（招牌/菜品/风格由他定，可请厨师但味道标准不由厨师定）→ 管**方向与标准的所有权**
  - ② 划清辅助边界 → **划线人**（线内 AI 可跑，线外必须人上）→ 管**边界的划定权**
  - ③ 强化把关意识 → **守门人**（谁进谁不进由他判，进来的也要查验）→ 管**质量的最终裁定权**
- ⚠️ **来源标注已做**：「**守门人**」是**窦文韬原话自带**；「主理人」「划线人」是**刘老师补充**的类比，页面已明确区分，不混淆作者
- 新增三块内容：
  - 三要点表格加「类比角色」「这个角色管什么」两列
  - **三个角色的具体含义**（比喻在说什么 / 换成教师的话各一行）
  - ⭐ **三个角色 = 三个自问**（主理人问"这家店要开成什么样"→育人目标；划线人问"哪条线不能过"→哪些环节 AI 一步都不能让；守门人问"这东西能放进来吗"→事实对不对适不适合我的学生）
- ⭐ **额外做的系统化**：发现库内另有一组「教师三身份」（五活动链：体验设计师/思辨引发者/AI护栏员），**两组互补不重复**，已做对照表：
  - 本页三角色处理 **教师↔AI**（对工具怎么用）；那页三身份处理 **教师↔学生**（课堂上怎么带）
  - ⭐ **辨析两个易混身份**：**AI护栏员**（防学生用AI越界，**在人之间**）vs **守门人**（防AI内容失真，**在AI与课堂之间**）
  - **合用顺序**：先讲教师↔AI（解决"我和工具谁说了算"），再讲教师↔学生（解决"我怎么带学生"）——**顺序不能反，不先定住支配地位，后面课堂设计会被AI牵着走**
- 页面 19091 → 22620B；关联行同步更新

## [2026-11-06] append | 「有意保留必要的费力环节」补入克制与留白页（中国教育报广西大学篇）
- 来源：中国教育信息化网（原载《中国教育报》）2026-11-05《广西大学探索人工智能赋能本科育人——把效率还给AI，把成长留给人》，**作者赵双良（广西大学副校长）**
- 原文 raw/articles/2026-11-05-gxu-efficiency-to-ai-growth-to-human.md（净正文 2106 字 / 6915 字节 + 真实 sha256）
- **技术情报（重要）**：ictdedu.cn **整站已上瑞数（Riversafe）动态防护** —— curl 各种 UA/完整浏览器头全部 **HTTP 412 + JS 挑战（$_ts、随机 meta id）**；连首页 index.html 也 412；**上次成功的 10-29 那篇现在同样 412**（说明是近期整站升级）；archive.today 四域全不通；Wayback 无快照；JINA_API_KEY 未配置；本地 Chromium 启动超时；**只有 `web_extract` 能过**。→ 以后抓 ictdedu.cn 直接用 web_extract，不要试 curl。（日报采集 paper.jyb.cn 不受影响）
- ⚠️ **入库判断经过一次修正**：初评建议"新建 ai-labor-division-checklist 大页面"，刘老师追问"「有意保留必要的费力环节」跟「让学生经历认知挣扎」是不是一回事"，撞库后发现库内「认知挣扎」已有厚实基础（post-literacy-age 专节 / ai-three-questions「保留挣扎」/ 本页四瞬间的挣扎感 / ai-destroys-zpd 必要难度）→ **改判为不新建，补进已有页面**
- **辨析结论（三者不同层）**：
  - **必要难度**（Bjork）= 理论机制，回答"为什么难反而学得好"
  - **认知挣扎** = 学习者体验，回答"学生那边怎么了"（**诊断**）
  - **有意保留必要的费力环节** = 教师设计，回答"我该做什么"（**决策**）← 唯一带动作的
  - ⭐ 关键差别在**"必要"是筛选器**："挣扎"这个说法不自带边界，容易滑成"越难越好"；"必要的费力"划出**最近发展区**内的范围
- 补入 5 块内容（位于"克制与留白三原则"之后，作为第 1 条原则的展开）：
  1. ⭐ **三个词拆开读**：**有意**（挡掉"放任"，是主动设计）/ **必要**（挡掉"越难越好"，只在能力形成必经处保留）/ **环节**（挡掉"笼统"，**逼你回答是哪一步**）
  2. **三者不同层对照表** + 与库内已有表述的链接
  3. ⚠️ **"必要的费力"≠"挫败"**（在ZPD内→挣扎→突破；超出ZPD→反复失败→自我否定；后者教师应立刻降难度或给支架）+ 引 parents-guide 的"巨人版模型导致挫败感"作现实注解
  4. ⭐ **正面分工清单**（库内此前全是否定式）：交给AI=知识记忆/格式化写作/程序化计算；留给人=**真实阅读/开放判断/长期协作**；判断新场景可先问"落在左列还是右列"
  5. **四条「AI能X不能Y」**：能复制知识不能复制人格 / 能给出答案不能制造内驱力 / 能产出"看似正确的答案" / 生活体验无法由模型生成；+ 五个教育家的线（纽曼→怀特海→孔子→蔡元培→竺可桢）+ "不能仅仅停留于培养会用AI的人"
- ⚠️ **明确不收**（原文六成篇幅）：广西大学"六个转型、一个特色"（成立AI学院/新增机器人工程/面向东盟/智师计划/数字西大/学生画像驾驶舱等）—— 高校特有且校本专名，对区级教研无可迁移性，已在页面内注明不收理由
- 页面 4149 → 8500B；建立 5 处双向关联（后识字时代/三问学习法/破坏ZPD/家长指南/科学教育做中学）

## [2026-11-06] ingest | AI赋能怎么加——两条判断原则与「教学需要vs展示需要」（许友森·福建省赛课例）
- 来源：微信公众号「许友森思政工作室 / 许老师的备课手记」，作者许友森；**上中下三篇**（2026-10-18 / 10-20 / 10-21）
- 原文 raw/articles/2026-10-18-xu-yousen-ai-when-to-add.md（三篇合并 **7646 字** / 22908 字节 + 真实 sha256）
- 创建概念页 [[concepts/ai-integration-when-to-add|AI赋能怎么加]]（scope: practice，21382B）
- **撞库**：29 个关键词中 **21 个命中 0**（许友森/够不到/效率太低/教学核心/**展示需要**/侯喜/小漳老师/厝边阿姨/漳州古城/防AI幻觉/查AI/信息素养/信息能力/扳回来/案由/微提案/参赛课件/八环节…）
- ⭐⭐⭐ **两层核心增量**：
  - **一、两条判断原则 + 一个反问**（库内只有"原则"没有"判据"）：
    - 原则一**够不到**：学生能力够不到，但教学确实需要他做到 → 加
    - 原则二**太慢且非核心**：学生能做到但效率太低，且不是这节课的教学核心 → 加
    - **反面：学生能做的、并且这件事本身就是教学要练的 → 坚决不加**
    - ⭐⭐ **最锋利的反问**："**如果我把AI从这个环节拿掉，学生的思维会变差吗？如果不会变差，那我加它干什么？**"
    - "真正难的，不是记住它，是每加一处之前，老老实实拿它检验一遍"
  - **二、⭐⭐⭐ 教学需要 vs 展示需要**（库内完全空白，且揭开"赛课AI滥用"的真实动因）：
    - **教学需要**=学生思维不加这一步转不过去，**对象是学生**；**展示需要**=让看课的人看见这堂课好在哪，**对象是评审/听课者**
    - **"这两种需要都是真的，但它们的对象不同。搞混了，就会出问题"**
    - 数字人「侯喜」出镜8次，**按前两条原则"一次都不该出现"**——真实原因：**"因为这是一个参赛课件"**（提交课件+专家评审，无学生无说课）
    - ⭐ **"一节好课，一半的东西在『人』这个因素上"**；"这些动作，全在四十五分钟里发生，也全在四十五分钟里消失"；**"评委打开我的课件，看到的是一堆静止的页面"**
    - ⭐⭐⭐ **警告**："很多老师看到侯喜效果不错，会想那我也做一个。然后就会掉进坑里——在真实课堂上放一个数字人。**我劝你别**"；"**在有真实学生的课堂里，老师本人就是最好的数字人**"（"这个动作里有一半的信息，是眼神和停顿给的"）
    - 处理原则：常态课按教学需要（老师能说的老师说）；赛课/交材料按展示需要补（"**这不是作假，这是把你的课翻译成别人能看懂的形式**"）
- ⭐ **八环节对照表**（加3/不加5）：课前查脉络[加]/课前实地拍照写说明[不加·地基]/课中查法条[加]/课中核验AI[不加]/课中厝边阿姨辩驳[不加]/课中青少年如何贡献[不加]/课后概念图[加]/课后微提案案由建议[不加]
- 三处「加」的细节：① 课前调研（"**这套活，是一个调研员干半个月的事**"；"实地去看是这节课的地基，这个'看见'AI替不了"；⭐**故意的"对不上"是伏笔**）② 小漳老师智能体（"**他做得到，只要给他时间。但这不是这节课要练的能力**"——练的是"怎么用法治方式回应"不是"怎么在法规库检索"）③ 课后概念图（绘画技能非本课核心）
- ⭐⭐ **防AI幻觉任务**（最实用设计）：查完AI必须"**登录漳州市人民政府官方网站查阅条例原文（禁止使用百科、自媒体等非权威渠道）**"，核对条文/记录差异/形成结论 → **"『用AI』教的是信息能力，『查AI』教的是信息素养"**；"AI的语气是确定的，格式是规范的，看起来特别可信——但它可能是错的"
- ⭐⭐⭐ 三处「不加」的理由：① 厝边阿姨辩驳——外包的是"**扳回来**"的过程（"看似反驳别人，实则教育自己"；"AI给他漂亮答案，他抄下来得高分，但**脑子里那个弯，永远没转过来**"）；学生真实产出"**法条能罚他乱停车，罚不了他心里不觉得自己错**" ② 青少年如何做贡献——"**问的不是知识，是认同**"；"**你让AI生成一段'青少年应该怎样'的话，他只会点头，不会起身**"；只能靠同龄人真实行动触发（红领巾讲解员：累计59名·286场·5.7万人次）③ 微提案案由与建议——"**AI写的是一份提案，不是这个孩子的判断**"
- ⭐⭐ **判断产出真伪的标准**（可直接评课）："**这个案由，是不是他自己从那张照片里看出来的？这条建议，是不是他自己从那句反驳词里长出来的？AI写的提案，看不出这两件事**"；"**概念图可以让AI画，案由和建议，一个字都不能代**"
- ⭐⭐ **指令 vs 求助**："现在请大家查一下条例对非机动车的规定" vs "我们古城早就有专属的法律保护伞，可这两件武器到底是怎么守护古城的呢？" → "**同一件事，一句是指令，一句是求助**"；⭐⭐"**但这二者的区别，其实跟有没有数字人无关。你完全可以自己站在讲台上说'老师这儿有个想不通的地方，你们帮我看看'。效果是一样的**"
- 侯喜四类功能表，其中"**问题追问**"是唯一不能扔的（"它的价值不在谁来说，而在说什么——**把关键问题从老师嘴里拿出来，交给学生**"）
- ⚠️ 局限已写明：① 单人单课无成效数据 ② **学科依赖强**（三处不加固依赖价值认同，数学物理等知识型学科判决会更宽）③ **"展示需要"的坦白有代价**——说明赛课课件与真实课堂是两套东西，不可当"赛课范例"引用，应作"对赛课形式的反思" ④ 两条原则仍偏经验，无客观标尺 ⑤ 该课为项目式长课时（45分钟+课前课后），"太慢"的余量比常规单课时大
- 建立 8 处双向关联（克制留白/助攻越位/网页点读机/赛课工具包/十六宗错/破坏ZPD/教师造工具/四代培训）
- 更新 index.md + MOC（概念 84→85）
- ⚠️ **本次 MCP 计划卡失败**：报 `Unauthorized. Web UI token was not accepted`（传 profile=default 仍失败）—— 与之前 `does not exist`（deferred 工具）不是同一类问题，属认证层故障，未阻塞入库

## [2026-11-06] structure | 新建 practice-log/ 教研手记机制 + 首个升格页（微课设计）
- **缘起**：刘老师与本地老师讨论如何改进「面向本校教师的 AI 教学应用微课」（原以操作流程介绍为主），给出四条建议后**追问「类似这样的日常教研点滴，如何入库更好」**
- **诊断**：库内原有两类内容都有位置——外链文章 → raw/articles；已成文本地资料 → raw/articles（source_url 写"本地资料"，见 skill 注意事项18）。但**对话中涌现的教研建议**（无成文、无 URL、一次讨论出多条）**无处安放**；`decisions/` 装的是架构取舍装不了教研建议；碎片盒能收但**没有转 wiki 的桥**
- **核心判断**：这类内容**不是「文章」，是「病例」** —— 谁、卡在哪、我怎么建议的、后来怎么样。拿 concepts 的成文标准去接，必然接不住
- **落地一：新建 `practice-log/`（教研手记）**
  - `SCHEMA.md` 目录结构加 `practice-log/{topic}/`，并新增一节「教研手记」说明定位、5 行格式、升格规则、什么不必记、与碎片盒分工
  - 建 `practice-log/index.md`（总索引）+ `practice-log/micro-course/index.md` + `practice-log/teacher-training/index.md`
  - **硬规则**：同主题满 **3 条** → 提炼成 concepts；单条永远保留不删；concepts 页链接回原始条目（`#YYYY-MM-DD` 锚点）
  - **什么不必记**：一次性、不再出现的建议 → 扔碎片盒。判据："**这个建议我是不是第三次说了？**"
- **落地二：新建概念页** [[concepts/micro-course-design-for-teacher-training|教师培训微课设计]]（practice，12726B）
  - 四原则：① 形式=案例场景式先抛问题（+**线上调查收集教师真问题**）② 内容=结合受训者身份有详略取舍（"**微课不是操作手册——手册可以查，微课只能看一遍**"）③ 工具=圈点标画注释 ④ 交互=断点
  - ⭐⭐ **核心洞察「被动接受的舒适状态」**："以免观看者陷入被动接受的舒适状态，实际上大脑已经停止活动了" → 微课是最被动的形式（无互动/无反馈/无社交压力/可随时跳过）→ 产生"**看得下去 + 觉得懂了 + 但复述不出来**"的欺骗性状态；⭐**"看得下去"本身就是危险信号**（没有阻力）
  - **断点为什么有效**：本质不是"强制点击"是"**打断连续流**"；三种断点（提问/反思/小结）成本递减，原则=**必须落在"容易误以为懂"的地方**，不平均分布
  - ⭐ **与 `webpage-activity-pitfalls-in-it-class` 的正反对照**：网页点读机的"互动幻觉"是**试错型假互动**（三次总能蒙对，手指在动大脑休眠）vs 本页"断点提问"是**产出型真打断**（必须说出自己的想法）；**判据同一个：这次互动有没有让学习者产生"自己的内容"**
  - **工具判断降权**：Instant Demo 本身过时（只出 exe、微信发不出、不跨平台），但"断点"机制有效；当前更实用载体按成本排序（H5P/Lumi → 普通视频分段 → 平台自带答题卡点）；⭐ **微信群场景"分段 + 每段结尾一个问题"已能实现 80% 效果**（下一集不自动播，本身就是断点）
  - ⭐ **与四代培训 Plus 的对照**：真场景↔① / 小产出↔② / **强伴随↔④断点**（微课做不到真伴随，断点提问是代偿手段："用学习者的自我追问替代导师的即时反馈，代偿不完整但比完全没有强得多"）
  - 含 8 条自检清单（第 8 条为终检："看完只剩'挺好'而说不出具体步骤，说明全程没有真正打断过"）
- **落地三：写进 skill** `thought-ingest` 新增**注意事项 34**（教研点滴的独立流程）：三类内容对照表、5 行格式、升格规则、不必记的判据、与碎片盒分工，并注明**与注意事项 18 是并列的第四类内容别混用**；含**例外条款**（单次讨论已有结构+独立洞察时可越级直接升格，不为守门槛把成型内容拆碎）
- ⚠️ 页面已写明局限：教研经验非研究（无对照实验、无完播率数据）；四条建议**尚未跟踪实施效果**（practice-log"后来"栏待补）；断点的"度"难把握（建议 5-10 分钟微课 3 个断点起步）；微信群场景需收作业配合否则提问被无视

## [2026-11-17] ingest | 让AI站在思维身后（羊城晚报·广州越秀）
- 来源：羊城晚报·羊城派 2026-11-11，记者何宁，净正文 2978 字（**注意：全文页 12426 字符里约 9500 是与教育无关的站点导航，正文止于"通讯员 于江"，不要误把导航当正文**）
- 原文 raw/articles/2026-11-11-ycwb-yuexiu-ai-classroom.md（9154 字节 + 真实 sha256）
- 创建概念页 [[concepts/yuexiu-ai-classroom-reform|让AI站在思维身后]]（scope: practice，15691B）
- **撞库**：24 个关键词中 **20 个命中 0**（越秀/谢幼如/社会性科学议题/SSI/泰森多边形/质询智能体/决策智能体/思维脚手架/创作磨刀石/站在思维身后/五融并举/三面镜子/不改变学科/吴照东/刘小莲/李洪奇）
- **场合**：教育部"新型教与学模式"实验区 + 广东省智慧教育应用示范区**越秀区成果推广会**（广州七中），直播至新疆喀什疏附县、贵州安顺、西藏林芝波密县及广东福建
- ⭐⭐⭐ **核心命题**："**让技术站在思维背后，让人始终站在课堂中央**"（吴照东）；"AI越强大，越需要学生保有独立判断，越需要教师发挥专业智慧" → 比"AI是副驾"更进一层：**把空间关系说清（身后/中央）**
- ⭐⭐⭐ **两个课堂切片**（本页最具体的技术细节）：
  - **数学课（张卓贤，初三）**：AED 配置的**公共决策评审会**（非计算题）→ **社会性科学议题 SSI** 教学。学生用**泰森多边形**划分服务区域，以服务半径/响应时间/经费预算检验方案；⭐**质询智能体**找逻辑漏洞 + **决策智能体**比较指标（双智能体分工，学生自己裁决）；过程=**立场确立→科学论证→交叉质询→多维决策**；"最优解"升华为**兼顾效率公平与公共利益的"合理决策"**
  - **英语课（梁绵君，高二）**：真实任务"科学精神之光英文展廊"，六课时单元；AI 定位为「**思维脚手架**」和「**创作磨刀石**」；⭐⭐**关键设计=学生必须说清为什么采纳/拒绝/重构某条AI建议，并对照初稿与修改稿** → **比"AI不许代写"高一级：不禁止，但要求交代理由**
- ⭐⭐⭐ **谢幼如（华南师大二级教授）的两条"改进处方"**（报道里罕见的有批评）：
  - 英语课：理清"**任务—方法—修改—完善—展评**"学习线，**"不能让人机对话挤掉人的表达"** ← 点中所有AI写作课死穴；批评的不是"用了AI"而是"人的交流被挤掉"，**问题在人机比不在有无**
  - 数学课：把校外调查画面带回课堂，**推动学生把决策报告提交给相关管理部门，让课堂成果接受真实世界的回应** → 不只情境真实，**出口也要真实**
  - 阶段判断："**已越过'要不要用AI'的初级阶段，进入'怎样用AI才有分寸、更能促进学习'的深水区**"
- ⭐⭐ **广州七中机制**：校长李洪奇"五融并举、一智贯通"；⭐**"不改变学科，只改变学法"**；"四叶草"课程体系；⭐**三面镜子**（避免技术堆砌/教师被边缘化/**学生因答案来得过快而停止思考**）；"数智赋能的质量不看屏幕有多少工具，而看学生是否经历深度思维的学习"
  - ⭐⭐ **团队资产沉淀**（对区域最可复制）：备课组把经过校验的题组、讲义和智能体**沉淀为共同资产**，避免只依赖少数"技术能手"；**"一个人摸索可能成就一节好课；一个团队共研，才可能形成一套能交接、可复制的做法"** → **与清华附中"种子教师"路线形成对照（个人扩散 vs 团队机制）**
  - 数据：2025年12项成果（含省一等奖）、部级精品课6节、省级精品课23节
- ⭐ **区域布局（吴照东三条）**：价值重塑（把"智能时代培养什么样的人"置于技术应用之前，**关键时刻把思维和主动权还给学生**）/ 范式输出（凝练为全学科跨学校的**操作框架、实施要点与证据链**）/ 素养发展（**从示范课的亮点变成日常课堂中稳定而有分寸的实践**）
- ⭐ **新增第六节：对黄陂区 8 条可迁移点**（双智能体拆分的低成本做法、"说清理由"作为防越位手段、本地议题替代教材例题、把"AI后有无师生交流"作听评课指标、成果外投、三面镜子作区级底线、要求留可交接资产、"不改变学科只改变学法"作回应话术）
- ⚠️ 局限已写明：① 活动报道非研究，展示课无效果数据，"走在全国前列"是主办方与专家评价非排名 ② 两节课样本极小且出自百年名校省标杆校，不代表区域平均 ③ "刮目相看"无具体依据 ④ **双智能体技术门槛与推广成本未说明** ⑤ **SSI 课时成本高**（真实点位调研+数据采集），日常课难复制——恰好印证"从示范课到日常实践"之难 ⑥ "12项成果"是学校自述未说评选口径
- 建立 **9 处双向关联**（温州/助攻越位/种子教师/克制留白/网页点读机/科学教育做中学/微课/当前阶段/四代培训）；修正了 `ai-restraint` 页里"本页/那页"指代写反的一处
- 更新 index.md + MOC（概念 84→85）

## [2026-11-17] ingest | 三阶循证教学（中国教育报 2026-11-09 第06版）
- 来源：**中国教育报 2026-11-09 第06版**，作者**王妙倩（青岛莱芜一路小学教师）**，正文 1662 字。URL 是网易号转载（`163.com/dy/article/LB9JKPQ80550CBNY.html`），**原发中国教育新闻网**，属教师实践署名文章非软文
- raw/articles/2026-11-09-jyb-precise-teaching-three-stage.md（5463B + 真实 sha256 `bb182ed1…`）
- 创建概念页 [[concepts/evidence-based-teaching-three-stage|三阶循证教学]]（scope: practice，16136B）
- **撞库**：24 词中 **18 个命中 0**（智链/精诊/适推/智慧纸笔/思维停顿/五维素养/高低阶提问/归因分析/小数减法/小数点对齐/青岛/莱芜/王妙倩/学情知识图谱/生成式调整/双画像/学历案）；命中项是**部分重叠**：`循证`（3页）、`证据支撑`（1）、`经验驱动`（2）、`最近发展区`（3）
- ⭐⭐⭐ **全文最硬的一段**：小数减法课前用国家平台预习数据生成学情知识图谱 —— 教师经验判定的难点"**小数点对齐**"学生正确率 **90% 以上**（白讲大量课时）；**60% 学生卡在"被减数小数位数少于减数"**（无人预料）。教师据此**改备课重心**，重点转向"位数不足时的退位探究"
  - **这是"经验驱动 vs 证据支撑"方向反直觉的实证**，且恰好是最该被怀疑的地方（60%/90% 的样本量原文未说明）
- **三阶模式**：课前**智链定向** / 课中**精诊画像** / 课后**适推闭环** + 单元循证教研迭代。三阶各指一个决策：课前改教什么、课中改怎么教、课后改练什么
- ⭐⭐ **两个读"过程"而非"结果"的设计**：
  - **智慧纸笔读思维停顿**："好几个学生写了又划、划了又写，停顿时间明显偏长"→ 学情预警 → 教师**当即暂停原定练习环节**改小组思辨 → **"这一课堂生成式调整，教学成效远优于按原有教案推进授课"**。⭐ **「课堂生成式调整」这个词记下来：数据不是用来看的，是用来当场撕掉教案下一页的**
  - **语音识别抓逻辑缺陷**：学生解释"为什么小数点要对齐"说「**因为是老师说的**」→ 系统标记**缺乏数学逻辑支撑** → 课后发现**没真正理解位值制，只记住操作步骤**。⭐⭐⭐ **抓的不是答案对错，是理由的性质（权威型 vs 数学型）**，"正确答案配错误理由"= 假会，传统课堂几乎无法发现
- **课后**：**双画像分层作业**（课前基线+课中素养画像 → A 生理解好但解决问题弱推说理迁移题；B 生理解有漏洞增基础巩固题，"落脚于自身最近发展区"）；**智能批阅做归因而非判对错**（批两班作业近两小时→系统归集高频错题，**定位症结在"退位后整数部分处理薄弱"**→增设专项对比训练）
- ⭐⭐ **五步循证教研循环**（单元全部课时结束后）：① 对比前后**五维素养画像**，统计**高低阶提问占比**与分层作业完成 ② 针对探究深度不足重设**梯度化认知问题链** ③ 更新课堂情境素材 ④ 调三阶各环节**时间分配与工具策略** ⑤ **沉淀校本资源**（资源库/素养评价量表/分层作业案例）→ 直接用于下一轮备课 = **「教—学—评—研」一体化**、教学教研双向迭代
- **与库内三处重叠的层次区分**（已写入页面第六节）：重庆八中点阵笔（`regional-ai-edu-path`）= **能采什么**；温州"有数据≠有证据"（`wenzhou-smart-campus-3-governance`）= **要防什么**；本页 = **采到之后做什么**
- **8 处双向关联 + 2 处行内补注**：regional / wenzhou / webpage-activity-pitfalls / dick-carey / ai-elevates-thinking-bloom-zpd / yuexiu / ai-education-current-state / four-generation；行内补注落在 regional "点阵笔是最低门槛"那句之后、wenzhou "同课同构实证 → 从经验走向循证"那行之后（按注意事项 21 回写盲区处理）
- **对区域的可迁移点按成本排序**（页面第七节）：最贵的是"智慧纸笔读停顿"也是**最不该为此立项的一项**；⭐⭐⭐ 零成本的「先验后教一次校准」+「归因式批改」才是真正的入场券
- ⚠️ 局限 7 条已写明，重点：**无前后测无对照**（"成效远优于"是主观判断）/**单校单学科单知识点**（推广到开放学科未知）/**"60% vs 90%"样本量未说明**（全文最有价值的数字说明最少）/四件套成本未提/技术决定论色彩/**技术决定论**/**五维素养画像维度未给**（使"量化育人实效"不可复现）
- 更新 index.md + MOC（概念 85→86）

## [2026-11-17] extend | 四代教师培训 + 刘欣《完成比完美重要：教师AI培训的四参与设计》
- 来源：微信公众号「**教学设计师刘欣**」2026-11-18 07:37，作者刘欣，**正文仅 1146 字**（页面 3.7MB 主要是内联样式）
- raw/articles/2026-11-18-liuxin-four-participation-training.md（3609B + 真实 sha256 `55f35e29…`）
- **未新建页面，扩写 [[concepts/four-generation-teacher-training|四代教师培训与 Plus 版]]**：12667 → **20825B**，新增 §七 §八，原 §七/§八 顺延为 §九/§十
- **撞库结果几乎全空**（本篇是纯增量）：`MVP`/`第0版`/`假进入`/`行为参与`/`情感参与`/`社交参与`/`成功体验`/`怕出丑`/`夏普比率`/`Robinson`/`Steve Blank`/`完成比完美`/`视觉笔记` **全部 ❌0**；仅 `认知参与` 在 webpage-activity-pitfalls 以不同语境出现过
- **为何是扩写不是新建**：① 同作者同主题（教师培训设计）连续线，宿主页已有 Plus 四要素 ② 新篇的「四参与」与那页的「Plus 四要素」是**正交的两套**——**四要素＝设计要素（怎么搭），四参与＝验收集（怎么判断搭成了没有）** ③ 正文 1146 字，单独成页会与宿主页大量重复
- ⭐⭐⭐ **§七「实验的第 0 版」而不是「产品的第一版」**：
  - MVP 考据：Frank Robinson 2001（**经济视角，用最小投入换最大确定性，后用夏普比率解释**）→ Steve Blank / Eric Ries 推向世界成为「构建—测量—学习」最小单位 → **传播中变形为"产品的第一版"**
  - ⭐ 核心二分：**产品的第一版 = 目标"能用"（交付导向）** vs **实验的第 0 版 = 目标"知道该不该继续"（探针导向）**
  - **"我们培训现场缺的，不是产品的第一版，是实验的第 0 版。"**
  - 第 0 版的样子：**一句还很生硬的提示词 / 一张教学板书 AI 赋注设计 / 一个简单的微课设计**；**"把『我不会』变成了『我做过一次』"**
  - 💡 这指出了"产出导向"的**第二重危险**：不只是 §三 的"AI 可替代完成"，而是**方向错了**——把该做实验的地方当成要交付产品的地方，越追求完整反而越丢判断力
- ⭐⭐⭐ **§八「四参与」**（先立病、再给判据）：
  - **病＝「假进入」**："光让老师'动手了'不等于真参与……**手在动，嘴在应，点头说'懂了'，下周一次没用**。这就是假进入——**行为在场，认知和情感没进来**"
  - ⭐⭐ **与库内两处同构**：`webpage-activity-pitfalls` 的学生版"**手指在动，大脑却在休眠**"；`micro-course-design` 的"**看得下去＋觉得懂了＋但复述不出来**"。**同一结构，三个场景**（学生／教师／单向媒介）
  - **四参与**：**行为参与**（真的跑通一个最小动作，不是看我演示）/ ✏️**认知参与**（动脑判断"在我班上成不成立"，**光跟步骤走不算，得说出依据**）/ ❤️**情感参与**（**他怕不怕做错**）/ **社交参与**（互相看作品、**争论"你这个班能用、我这个班不能用"**、向培训者追问）
  - ⭐ 我补的判断：**四者不是并列四维而是一条递进链** —— 行为最低门槛（最易造假）→ 认知是分水岭 → 情感是前置条件（怕就不敢真做）→ 社交是放大器（说出来才被检验）
  - **情感参与三动作**（最具体也最易被忽略）：① 开场公开解除威胁「**今天只要求做出来，不要求做好**」② 请两三位展示**不完美版本** ③ **只找亮点不纠错**
  - ⭐⭐ 第③条是培训者最需克制的：**"第一次展示的功能是'被看见'，不是'被评价'"** —— 第一次出场就纠错＝当众证明"你做得不行"，之后没人敢举手；纠错留到第二轮（那时他已有"我做成了"的底子）
  - **成功体验的重新定义**："不是'我掌握了工具'，是'**这件事我原来觉得干不了，刚才我干成了一次**'"；"对教了二十多年的老师，这比任何功能清单都重要"
  - 收尾：**"开始比完美重要，不是因为完美不重要，而是因为没有开始，完美永远不会发生。"**
- **§九 追加「四参与验收」表** —— 把四参与直接当离场前自查表，映射到原有三个动作；并指出**动作 3（跑之前先写"我认为该不该入库，为什么"）的双重身份**：既是防 AI 代劳的检测，也是**认知参与的证据**
- **3 处双向关联**：`webpage-activity-pitfalls`（互动幻觉↔假进入，学生版↔教师版）+ `micro-course-design`（被动接受的舒适状态↔假进入，单向媒介↔现场培训）+ 本页关联两条；`entities/liuxin-teaching-design` 更新为 **26 篇原文 / 23 个页面**，1.1 表加一行 + §五 适用边界加**第 26 条**（⚠️ 四参与无权重无门槛，实际落地时**情感参与最容易被省**）
- ⚠️ 局限加 3 条：**"假进入"只能靠"说不说得清依据"间接判断**（"下周一次没用"要等一周）/ **四参与无权重无门槛**（未排优先级）/ **MVP 考据属作者个人理解**（"实验的第 0 版 vs 产品的第一版"这个二分是刘欣的提炼，不是 MVP 原始文献表述，溯源勿混淆）
- 更新 index.md + MOC（页面数不变 86，字节大幅增长）

## [2026-11-17] extend | 教师自制工具 + 来林峰《键盘特工》键盘教学小游戏
- 来源：微信公众号「**教学日志随笔**」2026-10-28，作者**来林峰（信息科技教师）**，**正文仅 228 字**
- raw/articles/2026-10-28-keyboard-agent-minigame.md（5103B + 真实 sha256 `2c65bfee…`）；**raw 里明确分区标注**：原文正文 / 图片视觉转录（⚠️非原文文字）/ 6 张微信 CDN 图 URL
- **未新建页面，扩写 [[concepts/teachers-as-ai-tool-builders|教师是 AI 时代的天然生产者]]**：14949 → **21807B**，新增 §八「一个可参考的设计样本：《键盘特工》」（§8.1 起因 / §8.2 六大分区 / §8.3 游戏化外壳 / §8.4 印证什么 / §8.5 局限）
- **为什么不新建页**：正文 228 字（60% 讲学生不会打字、30% 讲积分快过期、10% 讲上线了），零方法论零框架；与宿主页完全同型（教师用 AI 造教学工具）但深度差一个数量级（宿主页是差评 8000 字级深度报道）。**新建页只会稀释宿主页密度**
- **撞库**：`键盘特工` / `输入法` / `来林峰` / `教学日志随笔` **全部 ❌0**；`键盘`/`打字` 仅在 raw 原文出现，**概念页零内容**
- **价值判断过程（关键）**：文字部分几乎无价值 → 用 `vision_analyze` 逐张读 6 张截图 → 发现两个真增量
- ⭐⭐ **AI 对话截图里的一句（⚠️ 出自截图中的 AI 回复，非作者原话，页脚标"内容由 AI 生成"）**：
  - **"学生不是『学不会』，而是『没机会系统地见过整个键盘』了。很多学校信息技术课一上来就教打字指法，默认学生已经认识键了，但触屏长大的孩子中间是缺了这一课的。"**
  - **"游戏的价值，首先不是『练』，而是『把键盘这张地图先摊开给他们看』"**
  - 💡 **与「先做后讲」看似相反实则同源**：那边说"别用名词开场"，这边说"认知地图要先摊开再谈指法"；**共同点：学生缺的从来不是"练"的机会，是"见过"的机会**
- ⭐⭐ **六大任务区＝键盘六个物理分区**（这个设计结构是本页最值得记的）：
  - 密码破译局＝主键区（字母密文/数字与符号/控制键出击，9/9星）
  - 紧急按钮站＝**功能键区 F1–F12 & Esc**（求助信号/刷新与编辑/全屏与调试/终极任务，12/12星）
  - 文档救援队＝**编辑键区** Insert/Delete/Home/End/PgUp/PgDn（光标归位/删改救援/长文阅兵，9/9星）
  - 方向迷宫＝方向键区（**仅用四方向键走迷宫出口**）
  - 特工组合技＝**修饰键组合** Ctrl/Alt/Shift（"高效分水岭"）
  - 数字金库＝小键盘区（财务/录入/算数）
  - ⭐ **按物理分区而非按打字速度/字母顺序组织** → 每个区对应**真实分区+真实用途**（F1=求助、Ctrl+S=保存、Home/End=光标归位）；学生学的不是"打得更快"，是"**这个键在哪儿、什么时候用它**"
  - ⭐⭐ **主界面明写"所有任务需在真实键盘上完成"**（非虚拟键盘点触）→ **这正是规避 [[concepts/webpage-activity-pitfalls-in-it-class|"网页点读机"互动幻觉]]**：用真键盘就点不过去
- **游戏化外壳**：特工代号 K-104 / 段位"键位侦察兵→首席键皇" / 57 星 / 9 枚勋章 / 勋章墙 / 目标"毕业特工"。💡 **命名全是"任务/职业"隐喻而非"练习/考试"**
- **印证宿主页三条判断**：①"痛点深度才是门槛"←他天天被"老师老师～"喊去救火，知道学生卡在大写转换和中英文切换 ②"**人做内容、AI 做界面**"←六大区的教学结构是他定的，勋章星级特工叙事是 AI 的活 ③"从用 AI 到造 AI"有了完整设计样本
- **2 处双向关联**：`webpage-activity-pitfalls`（真键盘 vs 点击式假互动）+ `ai-lesson-five-activity-chain`（认知地图 vs 先做后讲，同源两端）
- ⚠️ 局限 5 条已写：**只有 228 字正文+截图，没有制作方法**（工具/提示词/耗时/踩坑全无，能参考的是设计结果不是制作路径）/ **零效果数据**（学生用了之后会不会了？一句没有，正是宿主页强调的"做出来≠有效"）/ **57/57 是作者自己完成度非学生通关率** / **我未实际运行游戏**（只读截图，手感难度曲线未验证）/ 单校单师个人作品无评议无对照
- 更新 index.md + MOC（页面数不变，宿主页字节大幅增长）

## [2026-11-24] ingest | AI与班级管理（中国教育报 2026-11-24 第04版 智慧教育专刊·整版）
- 来源：**中国教育报 2026-11-24 第04版「智慧教育」专刊整版**，正文 **5428 字**，含**编者按 + 5 篇署名长文 + 大家谈 5 条短评**
- raw/articles/2026-11-24-jyb-ai-classroom-management.md（17049B + 真实 sha256 `9bad7a0b…`）
- 创建概念页 [[concepts/ai-classroom-management-seeing-students|AI是班主任的第二双眼]]（scope: practice，**25967B**）
- **作者清单**：史红升（陕西西安阳光中学·初中班主任）/ 颜丹薇（佛山顺德东逸湾实验学校小学部**校长**）/ 李旭强（深圳观澜中学·高中班主任）/ 高敏娟（厦门双十中学海沧附属学校·小学一年级）/ 林艳（河南漯河郾城区第二实验小学）/ 大家谈：曾莹莹·钟建国·李梦·于华贵
- **撞库**：20 词中 **13 个命中 0**（追光灯/隐身人/发言卡/看见人/第二双眼/排座/座位/情绪地图/荣誉/告状/事务处理者/育人设计者/缺勤）；命中三处全是顺带一提（guidelines 应用场景清单 / data-portrait 一句"精准支持" / xiaobei-agent 家访）→ **库内班主任工作整片空白，这是第一篇**
- ⭐⭐⭐ **核心命题**：**"AI 在班级管理里最珍贵的价值，不是'替我管人'，而是'帮我看见人'"**；**"AI 看不见眼神，听不懂叹息，更替代不了一次真诚的拍肩……不是替我们'管'得更省力，而是让我们'爱'得更到位"**
  - 💡 **给库内补了「AI 定位」第四维，且是唯一"往前补"的一个**：副驾=主次 / 站身后=空间 / 做界面=分工 / **补盲=看见人原本看不见的**。前三句都在讲"AI 该退到哪"，这句讲 AI 往前补一步
- ⭐⭐⭐ **追光灯效应（史红升）**：把一个月手记交给 AI 统计"哪些名字被提到过、哪些一次也没有" → **"结果让我有点儿脸红……班里近一半学生，一次都没'入镜'"**
  - 诊断：**"我的大脑像一束'追光灯'，总打在'台柱子'（成绩好爱表现）和'问题生'（常惹事需盯防）身上。而中间那一大片安静、守规矩、不吭声的孩子，往往成了'隐身人'。"**
  - **"他们没有缺点，也就没有'存在感'。他们不添麻烦，也就很少被点名。"** ← 全篇最锋利：**注意力被"异常"吸引，"正常"不产生信号**。是注意力的物理规律，靠"我更用心"解决不了
  - 做法：AI 每周生成**"沉默名单"**（连续两周没被提及）→ 每天找一两个**"不谈成绩、只闲聊"** → 小林交了第一篇主动作文、小陈第一次举手
  - 💡 **"只闲聊"是"看见人"与"管人"的分界线**：为"了解学习情况"聊天仍是管理对象，只闲聊才是当人
  - 三条边界：AI 只是提醒（**"AI说'小林本周零提及'，不等于'小林有问题'"**）/ 把时间还给人对人 / **隐私红线（脱敏"3号同学"、不上传原始记录、不当"档案库"）**
- ⭐⭐⭐ **发言卡三轮迭代（高敏娟，一年级）—— 库内最完整的 AI 迭代链**：
  - 起点：近半数孩子不举手抢答 → 问 AI → AI 建议**每人 3 张发言卡**，注明"核心是学会筛选**哪些话值得说**"
  - 第一天：**几个孩子 5 分钟用完急得直跺脚**；下午用完卡的孩子开始"**被迫**"听别人说；**最爱抢话的小男孩歪着头听同桌回答、听完还点了点头**——"那表情，像在说'原来听人说话也有意思'"
  - 一周后：**最安静的小女孩第一次发言，说得不顺溜，孩子们安静听还鼓掌** → **"这个办法不只是管住了嘴，好像还护住了一些孩子的胆子"**
  - ⭐ **三轮链**：3 张卡（孩子开始主动留卡）→ **反馈给 AI** → **小组共用发言卡**（话多的占满机会）→ **再问 AI** → **小组内设"轮流组长"每周换人分卡**
  - **"AI 不是问一次就完事，你把实际效果反馈回去，AI 可以顺着新情况再给你更贴合的策略"** ← **「强伴随/能迭代」在真实职场的最完整形态**（导师=AI，作品=班级机制本身，每轮都是新问题逼出来的）
  - ⚠️ "AI 不了解孩子真实学情，方案是否落地、如何取舍，最终仍需要教师自主判断"
- **五个场景（颜丹薇·校长视角）**：
  - **智慧座位魔方**：问卷收性格兴趣 + 教务数据（学业/互动）→ AI 生成多套方案**并附搭配思路**（理科↔文科互助、外向↔内向互补、视力不佳优先）→ **班会民主微调**（不可省：AI 算不到"这俩上周刚闹过矛盾"）
  - **数据预警**：学生**连续 3 天课间独处** → 系统推送 → 谈心+联家长 → **从"事后补救"转向"事前预防"** ⚠️ **3 天阈值是拍脑袋还是调过的？误报率多少？原文未说**（内向孩子本来就常独处）
  - **智能评语**："数据驱动+人文润色" —— 先整理**结构化表格**（学业/典型事例/日常表现）→ AI 生成差异化初稿（"课堂上的专注与运动场上的拼搏始终一致"）→ 教师补细节（"运动会后主动帮同学复盘战术"）。⭐ **AI 找跨场景一致性，教师补具体事件**；"套路化"的病因是**没有素材**
  - **AI 班会**：清明"生命课" → AI 生成 5 套方案 + 可视化课件 + 时间轴 + 递进问题 + **预设情绪波动应对预案** → 备课时长 **8 小时→2 小时**（⚠️估算还是计时未说）
- **AI 考勤（李旭强·高中）**：起点是**"10 分钟的信息差"**（早读点名发现没到、不知去哪、全班沉默的那 10 分钟）→ 三项设置：① 打通请假审批闭环（**预备铃前 15 分钟**推送）② **分层预警三级**（未请假未到校=红立即推送 / 迟到超 5 分钟=黄推班主任但**不公开** / 连续 3 天=进**周关注名单**）③ ⭐⭐ **AI 提醒后必须人工确认**
  - 实证：系统提示赵同学未到校，正打电话，家长主动说"孩子发烧，刚想请假手机没电了"
  - **"AI 提醒只是起点，真正的班级管理是随后那通电话、那次询问、那句'你今天没来，我很担心你'"**
  - 定位转换：**从"记录缺勤"转向"处理缺勤原因"**，每周省 40 分钟；⚠️ 伦理自守：**绝不公开缺勤名单，保护学生自尊**
- ⭐⭐ **家校沟通三个自问（林艳）—— 本篇最零成本可落地的一条**：
  - 难点：**"难的不是'说什么'，而是'怎么说'"**（"请家长加强监督"引发解释或道歉，变成互相"找原因"）
  - AI 要求"不批评、不制造焦虑、不转嫁责任" → 生成温和话术
  - ⭐ **但真价值不在话术，在三个自问**：① **我是在描述问题，还是在评价孩子？**（"作业马虎"是评价，"常在进位退位处出错"是描述）② **我是在寻求家长配合，还是把责任推给家长？**（"请家长加强监督"是推责）③ **除了告诉家长"孩子哪里不好"，我有没有告诉他"我们可以怎么做"？**
  - 效果变化：家长从"解释/道歉" → **"那我们在家具体怎么配合？"**
  - 金句：**"少一点儿'告状味'，多一点商量的语气；少一些简单评价，多一些具体观察"**
- ⭐ **大家谈最妙一条（李梦·河北沧州）**：麦克风采集环境声音，分贝低于阈值**虚拟小树慢慢生长**（枝干变粗叶片变密），超标停止 → **"AI 把'安静'从抽象要求变成孩子能看见的状态"**；**"从'要我安静'到'我要安静'，一字之差，背后是自我管理意识的萌芽"**
  - 其余：曾莹莹（AI 配趣味荣誉标签生成荣誉小卡片记录善意 →"**放大善意**"）/ 钟建国（找中间群体，勾勒**班级情绪地图**）/ 于华贵（学情线索定位重点关注+差异化沟通素材）
  - 💡 **钟建国的"班级情绪地图"与史红升的"沉默名单"同向**：把"不可见的中间状态"变成可见数据 —— 本篇的母题
- **9 处双向关联**：evidence-based-three-stage（同为数据打脸改行为）/ four-generation（发言卡=强伴随课堂版）/ teacher-ai-dilemma（助攻越位答案 + 脱敏写法）/ webpage-activity-pitfalls（数据装饰品反面）/ teachers-as-tool-builders（知道好在哪）/ ai-restraint（克制在师生关系的形态）/ current-state / data-portrait-growth（模糊评价→六场景落地）/ xiaobei-agent（补"## 关联"节）
- **对黄陂按成本排序**（页面第七节）：⭐⭐⭐ 三条**零成本**（沉默名单手记法 / 家校沟通三个自问 / 发言卡手工版）；⚠️ **最贵的三条（排座/考勤/预警）恰恰最不该先做** —— 与三阶循证结论完全一致
- ⚠️ 局限 9 条已写明，重点：**全是教师自述零效果数据**（"近一半"没说班额，小林小陈是**个案叙事**）/**追光灯是个体经验非研究**（未引任何注意力研究）/**隐私被轻描淡写**（"把手记交给AI"本身涉数据出境，只给原则不给操作规范）/**连续3天独处阈值未验证**/**8小时→2小时无法核对**/**获奖是结果关联非因果**/**发言卡有效无法归因到AI**（AI只贡献"3张卡"，其余全是教师执行与迭代）/**"沉默名单"伦理风险未讨论**（可能从"看见人"滑成"标注人"，无防误用机制）
- 更新 index.md + MOC

## [2026-11-24] ingest | 分层作业：分层不分人（公众号「符老师的AI教学论」）
- 来源：微信公众号「**符老师的AI教学论**」，署名"**智课先生**"，2026-07-28，正文 **1600 字**
- raw/articles/2026-07-28-differentiated-homework-not-people.md（5069B + 真实 sha256 `ab6062d3…`）
- 创建概念页 [[concepts/differentiated-homework-design|分层不分人——定锚·搭梯·开菜单·留活口]]（scope: practice，**15262B**）
- **撞库**：`伪分层`/`标签效应`/`定锚`/`搭梯`/`开菜单`/`留活口`/`一境到底`/`免做`/`越层`/`菜单` **全部 ❌0**；`分层作业`/`差异化作业`/`分层` 命中 **上周刚入库的 evidence-based-teaching-three-stage** → **作业设计是库内空白主题**
- ⭐⭐⭐ **核心增量：它校正了我上周入库的那页**。三阶循证页写"双画像分层作业：学生B理解有漏洞→增基础巩固题"，本页直接指出这就是**伪分层**：
  - **"把一套题印三份：基础题、提高题、挑战题，按学生成绩发下去……按人头切难度，等于在作业本上给学生贴了标签"**
  - **"标签效应：老拿基础题的孩子，慢慢就觉得自己是被放弃的那个"**
  - ⭐ **"两边都得不到该有的拉伸"** —— 不只弱生受害，**优生永远做难题也拿不到"回头夯基础"的拉伸**（一端自我否定，一端基础虚浮）
  - 原则：**"分层不分人"** / **"不把学生切成三堆，而是把'任务'分层"**
- ⭐⭐⭐ **分水岭（全篇最锋利）**：**"没人会因为'被分到基础层'而丢脸，因为台阶是公开摆着的，不是老师暗里定的。"**
  - 我做成对照表：老师发的/系统推的（"老师觉得我只能做这个"／被动接受**判定**／失败归因"我笨"／要等重新评估）vs 公开台阶自己选（"我现在先做这一级"／主动**选择**／"这台阶我还没上去"／自己往上爬）
  - ⚠️ **对"数据驱动"路线的直接警告：画像越精准、推送越自动，越是"暗里指定"，孩子连是谁定的都不知道。精准不等于善意**
- **四步法**：
  - **①定锚**：练**素养**不是练知识点（地理读图靶心不是"背比例尺公式"，是"拿到陌生地图能自己找方向判断关系"）；**"锚错，梯子搭得再花也是在训练'刷题肌肉'而不是'真本事'"**
  - **②搭梯**：同一内容 2-3 级认知台阶，**学生自选起点**（借布鲁姆）。数学函数：套公式→换生活情境（话费套餐）→**自己编同类型题**；地理读图：指认→说清关系→**预测上游建坝下游怎么变**。⭐ 三级递进不是"难易"是**认知动作**：套用→迁移→**生成**
  - **③开菜单**：实践/探究类给选项（语文"故乡"：微型小说/人物关系图/短视频旁白；理化生：验证性/探究性/设计性）。**"选什么不重要，重要的是他选了、做了"**。💡 我的补充：**有唯一答案的用梯子，答案多元的用菜单**，用错就出事
  - **④留活口**（他说"最容易被省掉的一步"）：**允许越层** / **设免做**（基础全对则下次免做，时间省给往上爬）/ **用数据诊断调层**。英语口语用**闯关制**，过关自动进下一关——**"比老师给你定层管用得多"**
- ⭐⭐ **「一境到底」**：地理"周末去城郊露营"主线——第一层选哪种地图（地形图/气候图）→第二层辨方向→第三层选扎营位置（**近水但防洪、背风、平缓**）。**"学生自己测自己卡在哪一关，比老师点名'你读图弱'温柔，也准"**
  - 💡 **"温柔"两字又回到贴标签**：同一诊断**做成关卡让他自己撞上** vs **老师当面说"你读图弱"**，信息一样关系不一样
  - 💡 真正价值不在情境好看，在**把"分层"藏进"剧情推进"**：学生感知的是"我要往下走"，不是"我被分到第几档"
- **跨学科速查表**（地理/数学/语文/英语/理化生 × 锚/搭梯/开菜单）+ **五条自查清单**（①有没有把人按成绩切堆 ②有没有 2-3 级台阶能自选 ③实践类给菜单还是唯一答案 ④有没有留越层/免做/诊断的活口 ⑤能不能套进真实情境）
- ⭐⭐ **本页第六节专门处理与三阶循证的关系**（这是本轮最重要的动作）：
  - 两句可并存但**顺序不能反**：**先做到"分层不分人"，再谈"用数据把层分得更准"**；否则只是把贴标签做得**更隐蔽、更高效**
  - 💡 **折中做法（我的建议）**：**数据用于"设计台阶"，不用于"指派台阶"** —— 用画像看出"这个班有三类卡点"，据此设计三级台阶并**全部公开**；但**不要**用画像算出"张三属于二级"直接推给张三。**同样的数据，一种用于设计，一种用于判定；前者是教师，后者是裁判**
- **回写三阶循证页**（按注意事项 21 回写盲区）：在那节末尾插入 ⚠️⚠️ 警告块 + 关联行（16136 → **18098B**）
- **7 处双向关联**：ai-elevates-thinking-bloom-zpd（理论落地，但布鲁姆用法通俗化）/ dick-carey（同一个"锚"）/ ai-classroom-management-seeing-students（同构诊断动作：注意力有偏 vs 评价有偏）/ ai-restraint（留白在作业环节）/ webpage-activity-pitfalls（菜单 vs 唯一答案）/ five-activity-chain（台阶 vs 活动阶梯）/ teachers-as-tool-builders（手工版同样成立）
- **可迁移点按成本排序**：⭐⭐⭐ 三条零成本（五条自查清单 / 改掉"印三份"的格式 / **台阶公开**）、⭐⭐ 一境到底与留活口、⚠️ 闯关工具非必要
- ⚠️ 局限 8 条已写明，重点：**教师个人经验非研究**（无数据无对照）/**"标签效应"没给出处**（只写"研究里有个说法"，Becker 标签理论、Rosenthal 皮格马利翁效应一个没引，**不可核对，引用勿当文献结论**）/**布鲁姆六层被通俗化**（教学分类 ≠ 难度分级）/**四步法是作者自述归纳非公认框架**/**"免做"若是蒙对的怎么办未讨论**/**有轻量工具推广**/**完全没回答时间成本**（备课涨多少？50 人怎么登记越层免做？）/ **"优生也受害"未展开论证**
- 更新 index.md + MOC

## [2026-11-24] ingest | 三师课堂（上观新闻 2026-11-22，奉贤研讨会）
- 来源：**上观新闻（解放日报·第一教育）2026-11-22**，文字曹轶姗，正文 **2215 字**；会议 11-20~22 上海奉贤，主题「AI 时代'未来课堂''三师课堂'助力育人方式变革」
- raw/articles/2026-11-22-sgh-three-teacher-classroom.md（7801B + 真实 sha256 `39418e66…`）
- 创建概念页 [[concepts/three-teacher-classroom-taoxingzhi|三师课堂]]（scope: practice，**16259B**）
- **撞库**：`三师课堂`/`三师`/`AI智能师`/`小先生`/`陶行知`/`生活·实践`/`周洪宇`/`操太圣`/`顾月华`/`郝敬宏`/`功能性支持`/`主体性责任`/`输出式学习`/`教学做合一`/`师生共生活`/`合作探究`/`任务展示` —— **全部 ❌0**；`师—生—机` 命中 3 页（越秀/教師作为Hub/智能教育论坛）；`人机双师` 命中 regional-ai-edu-path
- ⭐⭐⭐ **撞库顺带暴露的结构性问题（写进页面第〇节）**：库内理论几乎**全是从西方搬的** —— 维果茨基 3 页、布鲁姆 4 页、杜威 1 页；而**陶行知 0 / 叶圣陶 0 / 顾明远 0 / 叶澜 0 / 于漪 0 / 佐藤学 0**，孔子与蔡元培各仅 1 页且只引金句
  - **对刘老师的实际后果**：向校长/局长/区教育局汇报时，**讲"维果茨基最近发展区"不如讲"陶行知小先生制"** —— 后者本土、有政策合法性、领导一听就懂。**西方理论再厚也换不来这份本土说服力**
- ⭐ **这是什么**：「三师课堂」＝**教师 + 小先生 + AI智能师** 三元协同。周洪宇（华中师大国家教育治理研究院院长）定性：对陶行知「**师生共生活**」「**共学、共事、共修养**」与「**小先生制**」的**创造性转化**，也是对「师—生—机」协同课堂的**本土探索**
- ⭐⭐⭐ **三方分工（郝敬宏·华二临港校长，全文最完整一段）**：
  - **教师**＝情境设计者·问题链驱动者·思维点拨者·**价值情感引领者** → 负责**追问和点化**
  - **小先生**（学生）＝学习资源生成者·生生互动**教学者** → 负责**生成和表达**
  - **AI智能师**＝抽象过程的**可视化者**·资料检索的**拓展者** → 负责**看见和检索**
  - **"AI可视化成果与小先生真实思维相互印证……以生为本、以问题为引、以思维为核心"**
  - 💡 **关键设定：学生不是"学习者"，是"教学者"** —— 库内所有"师-生-机"框架里学生始终是"学的人"，只有这套把学生放到**教的位置**。一旦要"教"，就必须先真的懂，且会自己发现哪里其实不懂——**这是 AI 替代不了的检测**
- ⭐⭐⭐ **两条最硬的判断（本页真增量）**：
  - **① 操太圣（南大）："AI 则发挥功能性支持而非主体性责任"** → 给库内补了 **AI 定位的第五个维度＝责任**
    - 已有四维：主次（副驾）/ 空间（站身后）/ 分工（做界面）/ 补盲（帮我看见人）；本页＝**责任归属**
    - 💡 **为什么这维最"文件化"**："副驾"是比喻、"站身后"是意象，**写不进规范**；而"功能性支持/主体性责任"可直接进区级文件。文中已给出拟稿句式
  - **② "教师需要承担课堂治理负荷"** → ⭐⭐ **减负≠变轻松，是负荷转移**（全文最反常识一步）
    - 减负前：**事务性负荷**（累但不难，可加班补）→ 减负后：**治理性负荷**（不一定更累，但更难，不能靠加班补）
    - 💡 **可直接回击"AI 让老师变懒"的质疑**：不是变懒，是负荷从"手上的活"转成"脑子的活"
- ⭐ **实践样本**：上外附属奉贤实验中学（朱俊䶮）**近 10 年**小先生制，三步骤＝**任务发布→合作探究→任务展示**；2025 年成为实验校后与三师课堂融合。"**教学做合一不是一个理念，而是可落地的；师生共成长不是一个口号，而是可实现的**"
  - 💡 与 [[concepts/ai-lesson-five-activity-chain|五活动链]] 同族，关键差别：**五活动链的"做"是个人做，三步骤是合作做+上台教，输出更强**
  - 区域节奏：2025 年奉贤实验区首批 **10 校 + 2 基地**，本次第二批加盟 —— 与温州"**择优推荐、不搞批发式申报**"同逻辑
- ⭐ **顾月华（中国陶行知研究会副会长）**："捕捉学生尚未说出口的疑问，**读懂沉默背后的犹豫**，鼓励跳出标准答案的尝试" → 与刚入库的**追光灯/隐身人**是同一件事两层：**追光灯靠机制（统计，可复制），顾月华靠能力（读懂，只能练）；机制负责发现，能力负责读懂，缺一不可**
- **两个报告（存档，价值较低）**：林炊利（上海市教科院院长）数智时代评价改革——五大挑战含**"技术理性与育人价值"**；杨进（教科文原大使衔代表）STEM 与高阶思维
- **7 处双向关联**：five-activity-chain / ai-classroom-management / regional（双师vs三师）/ ai-restraint（责任维度比克制更硬）/ yuexiu（证据 vs 说法）/ wenzhou（同节奏）/ ai-empower（西方框架 vs 中国框架）
- **对黄陂按成本排序**：⭐⭐⭐ 三条零成本（**用"三师课堂"这个说法去讲**、把"功能性支持非主体性责任"写进区级规范、用"教师承担治理负荷"作培训开场）、⭐⭐ 把小先生制纳入听课观察点、⚠️ AI智能师具体工具通稿未提无法判断成本
- ⚠️ 局限 8 条已写明，重点：**会议通稿**（2215 字约 800 有料，其余致辞+13 个机构头衔）/**零效果数据**/**小先生制潜在问题全未讨论**（会的更会、不会的更不会？优生负担？是否把教学责任下推给学生？）/**三师分工是理想描述非观察结果**（AI 会不会变"第四师"、小先生会不会退化成"小助手"无数据）/**化学课只有一句引入**/**"课堂治理负荷"只有一句未展开**/**周洪宇新书仅发布会式提及**/**"创造性转化"未经检验**（小先生制诞生于 1930 年代师资匮乏的乡村，与 AI 时代城市课堂条件差距极大）
- 更新 index.md + MOC

## [2026-11-24] ingest | AI重构课堂的实践路径（马涛，中小学信息技术教育 2026-11）
- 来源：**《中小学信息技术教育》2026 年第 11 期，24–27 页**（期刊论文），作者**马涛**（北京市丰台区教育学院**副院长**，北京市特级教师、正高级，首届教育部基础教育信息化教学指导专委会委员）｜净正文 **6704 字** / 7 图（原标"6497字"）
- raw/articles/2026-11-24-matao-four-lesson-prep-ai-classroom.md（20375B + 真实 sha256 `258d74fe…`）
- 创建概念页 [[concepts/ai-classroom-reconstruction-path|AI重构课堂的实践路径]]（scope: practice，**24406B**，十一节）
- **为什么是高价值**：**作者身份与刘老师高度对位**（区级教育学院副院长），且是**站在全国一百多节课后面观察的人**。库内首份"从区级教研视角写出来的、成体系的 AI 课堂方法论"
- **撞库**：24 词中 **19 个命中 0**（四次备课/备课迭代/六环节/完整学习时间/课堂小结/创造类/思辨类/三级进阶/科普新知/逻辑推演/创造价值/难度阶梯/技术层次/陈景润/华罗庚/离线包/为技术而技术/数据孤岛/马涛）；命中 5 个均为其他语境（学习设计师=海淀角色表 / 思维教练=三路线 / 学习支架=PBL两页 / 通识教育=政策页 / 师-机-生=技术栈拆解）
- ⭐⭐⭐ **四次备课（本页最值钱，库内首篇"同一节课怎么被改错三次"的完整记录）**：
  - **1** 拍照判题图像识别对答案 → 学生注意力全在**找答案抄作业**，**课堂几乎没引发思考的讨论**
  - **2** 跟大模型对话问知识答案 → "呈现的是人机对话内容，**但问题还是指向答案**……**而知识本来就在教材里，为什么要通过对话去问？**" ← ⭐⭐⭐ **这一刀砍掉当前绝大多数"AI 进课堂"的课：把教材现成内容换个对话形式再问一遍**
  - **3** 问解题方法讨论提炼 → "方向对了，但学生如果只问答案，**教师又该如何组织？**"（错在课堂组织没变）
  - **4** **学生先解题 → 描述自己用的方法和知识 → 让大模型据此命题 → 全班分析评价 AI 出的题考查了哪些知识和能力 → 同学互相做彼此 AI 命制的题** → 被认可
  - ⭐⭐⭐ **第 4 轮是位置反转**：前三轮学生都是"求答案的人"，第四轮 **AI 出题、学生审题、学生互做同伴的题** —— 学生同时是**解题人+命题人+审题人**，AI 从"答案机"退成"命题工具"。**这是"AI 站在思维身后"最彻底的形态**，比越秀"质询智能体"更闭环
  - 命题："**当 AI 只是用来给答案，它就是抄作业的捷径；当 AI 被用来提问题、验想法、出题目、做镜子，它才真正成为点燃思考的伙伴**"（"出题目""做镜子"两个用法库内此前没有）
- ⭐⭐ **公式**：**AI课堂重构 = 学科核心素养 + 课堂学习活动 + 学生个体关注**（缺素养=花架子；缺真实活动=技术不转化为能力；缺个体关注=回到一刀切老路）
- ⭐⭐ **教学设计六环节**（库内 0）：创设情境 / 布置任务 / 提供学习支架 / ⭐**保障完整学习时间** / 组织交流评价 / ⭐**课堂小结**
  - ⭐⭐ **"保障完整学习时间"是库内真空白**："学生借助 AI 自主推进，**教师腾出手巡视个体**" —— 库内都在讲"AI 减负"，**没有一页讲清减下来的时间去了哪**，这是唯一的具体回答
  - ⭐ **"课堂小结：师生共同复盘是怎么用 AI 的"** —— 复盘对象从"学了什么"变成"怎么分工的"，**元认知层面，且是防 AI 代劳最自然的动作（只需换个小结问题）**
  - ⭐ 学习支架："**在学生卡点时进行提示而非直接给答案**"
- ⭐⭐⭐ **三级进阶**：① **科普新知·解释现象**（《百变团花》文生图：把脑中意象翻译成提示词，"检验了表达的明确性"）② **逻辑推演·理性判断**（物理实验：**只给关键词**让 AI 设计实验方案，**学生分析方案的要点与漏洞**）③ **创造价值·创新应用**（浅层工具赋能→深层算法思维→顶层思维创新）
  - ⭐⭐⭐ 第二阶核心："**AI 给出的是可能性，学生要做的是判断**"
  - 配套**技术层次图**（低阶记忆理解应用/中阶分析评价/高阶创新）+ **难度阶梯 Level 1–6**（感知→体验→理解→应用→进阶→创新）
  - 原则："低阶重复性任务让 AI 多承担，**涉及深度思维、价值判断、情感体验的高阶任务必须留给学生**"
  - 红线："**不是让学生用 AI 单纯找答案，而是结合 AI 进行思考**"
- ⭐⭐ **陈景润 vs 华罗庚**：陈景润把专业知识教给学习者让其成为数学家；**华罗庚把高深数学用浅显语言讲给小学生听**。AI 通识教育更像后者 —— "我们培养的是**能够利用 AI 解决问题的社会公民，而不是 AI 工程师**"（⚠️ 比喻有简化，见局限 3）
- ⭐⭐ **五种人机关系（王老师·初中组）**：**验证 / 对话 / 协作 / 导师 / 批判** —— 我之前补充判断：这是**递进**不是并列，前两种 AI 还是工具，后三种才参与思考
- ⭐⭐⭐ **四学段问题清单（本页最实用）**：
  - **小学**：过度依赖（教师把过程全交 AI 自己退到一边）/ 评价不足 / ⭐**方法指导缺位（多数教师没教怎么问）** / ⭐⭐**学生主体未落实（"教师预设、AI 执行、学生围观"）** —— "把答案和成品'喂'给学生，启蒙就变了味"
  - **初中**：照搬预设 / ⭐**端到端代劳** / 答案唯一化 / 评价缺位 —— "**把认知省掉了，只剩应用的空壳**"
  - **高中**：三节课较高阶（对比不同大模型辩论观点 / **有意设计"修正 AI 漏洞"任务** / AI 李白跨时空对话对比润色稿）—— "**技术用得越深，越要靠教师的判断力把准方向**"
  - **学前**：软件适切/目标清晰/方法到位/**深度匹配年龄**（"有的课设计过难，一节课根本完不成"）
  - **八字诀**：小学**敢用**·启蒙 / 初中**会用**·认知 / 高中**善用**·思辨 / 学前**适切**·激趣
- ⭐ **三个短板**（作者主动泼冷水）：复杂问答理解有限 / 细腻情感远不及人 / ⭐**一本正经胡说八道**
- ⭐ **离线包**：针对网络延迟、AI 插号回答 → 预设本地化资源与备用互动，**"甚至把突发故障转化为师生共解问题的教育契机"**（库内对"AI 课翻车怎么办"的唯一具体回答）
- ⭐ **为技术而技术**：为数字人而数字人 / 为单一品牌全功能堆砌；三个平衡：智能精度↔教学容错、活动热闹↔思维沉淀、即时效果↔长期影响
- ⭐ **治理挑战**：① 数据孤岛需统一数字基座 ② ⭐**通用大模型的交互内容学校管理者往往无法获得**（既是隐私也是管理盲区，极少人提）"不是靠一节好课能解决的"
- **11 处双向关联**：five-activity-chain（课怎么备 vs 课怎么走）/ ai-integration-when-to-add（要不要加→加到第几层）/ ai-restraint（卡点提示非给答案）/ three-teacher（减负后时间去哪：治理负荷↔巡视个体）/ differentiated-homework（关注个体是正当性来源）/ ai-classroom-management（统计 vs 巡视）/ yuexiu（审 AI vs 用 AI 出题互审）/ webpage-pitfalls（手指在动↔教师预设AI执行学生围观）/ four-generation（四次备课作培训开场）/ ai-general-education-rollout（进课表 vs 进去了怎么上）/ teachers-as-tool-builders
- **对黄陂按成本排序**：⭐⭐⭐ 四条全零成本（"教师预设、AI执行、学生围观"写进听评课表 / 六环节作备课自查 / **四次备课当培训开场案例** / "知识本来就在教材里"当筛子）、⭐⭐ 陈景润华罗庚·五种人机关系·学段八字诀·让AI出题学生审题、⚠️ 统一数字基座（区域级工程非电教站单方可解）
- ⚠️ 局限 8 条已写明：**经验总结非实证**（一百多节课无系统数据无对照，"被认可了"谁认可按什么标准未说）/**三级进阶六环节难度阶梯都是区域自创框架**（未经效度检验，引用须说"北京丰台区的实践框架"）/**陈景润华罗庚比喻有简化**（华罗庚远不止"讲给小学生听"，懂数学的人会挑）/**四学段清单样本未说明**（哪些学科哪些地区如何抽样由谁评全无）/**成功案例因果无法归因**（设计变好还是教师水平高）/**AI插号只提离线包**（平台稳定性处理偏轻）/**"保障完整学习时间"缺时间参数**/**未讨论学生负担**（六环节+三级进阶+三活动类型全落课堂，学生一周承载几个？方法论很美但没课时账）
- 更新 index.md + MOC

## [2026-11-25] ingest | 四帐记：历史课做成可交互游戏（公众号「刘思远师者打卡集录」）
- 来源：微信公众号「**刘思远师者打卡集录**」2026-11-04，作者**刘思远**，正文 **2382 字** / 12 图（含 3 动图）
- raw/articles/2026-11-04-four-tents-history-game.md（7543B + 真实 sha256 `d397d9fe…`）；raw 已注明**图片未转录、页面文字自身完整**
- 创建案例页 [[cases/yong-ai/four-tents-history-game|《四帐记》]]（scope: **case**，16245B，九节）
- **为什么放 cases 不放 concepts**：它是**单个课例的一手制作实录**，不是跨案例的方法论；且与 cases/yong-ai/sui-yangdi-ai-debate 形成**历史课两种 AI 用法**的对照
- **撞库**：24 词中 **19 个命中 0**（四帐记/辽夏金元/南北面官/猛安谋克/捺钵/行省/四等人制/刘思远/相关不等于/知识点闯关/史官/修志/即梦/Seedream/单文件/采分点/拆思路/数位置）；命中 5 个均其他语境（证据链3页/留白3页/游戏化3页/闯关3页/干扰项）
- ⭐⭐ **起点诊断**："不是记不住南北面官——"北面管宫帐部族，南面管汉人州县"学生背得比我还熟。**是因为他们从来没'站'在辽的营盘里，看见同一堆篝火旁边其实坐着两拨人**"
- ⭐⭐⭐ **"星星后面还是卷子"**："知识点变选择题、答对给星星……**学生三分钟就腻，因为他们一眼看得出来：星星后面还是卷子**" ← 与 webpage-activity-pitfalls 互动幻觉同一病灶，且**学生看穿是准确的**
- ⭐⭐⭐ **三条"反着来"的设计（本页最可复用）**：
  - **① 答案不蹦出来，先让学生自己勾**：点原文任一句 → 摊开批注（译文/难字词/这句在做什么）+ 论证脉络（摆难·立论·史证·现实·喻证·难处·渐进）→ 点"拆思路"四步（审题→定位→提取→作答）→ **第三步"提取"系统自动比对"漏勾了哪几句、多勾了哪几句"** → **第四步才给采分点**
    - ⭐ "学生看到的不是一段标准答案，而是**答案从哪句话哪几个词里长出来的**"
    - 💡 "**多勾了哪几句**"这个反馈极罕见（多数系统只查漏），而"多拿"才是真能力问题（把不相关当相关）
  - **② 证据链考的不是"找对"，是"分清"**：左边六片纸、右边论断笺，拖对的三片过去；**拖错弹回、折角、落朱批当场说为什么撑不住**（"把西夏那片牵到辽的论断上→这是西夏，不是辽"）；**十六条干扰项每条都写了理由，不等提交才揭晓**
    - ⭐⭐⭐ 原话："**相关，不等于能支撑。迁都中都、大定之治、崖山、元亡后的融合，讲的都是真事，可它们讲的是"结果"，不是"制度"，撑不住论断**"
    - 💡 **库内讲证据链的两页（dick-carey=设计的证据链 / 三阶循证=学习的证据链）都在讲怎么"收集"，这一句讲怎么"排除"**；且给了可迁移判别法：**区分"结果"与"制度"**
  - **③ 材料次序每局随机 + 硬约束**（对的三片不集中在前、不许三连排）—— 因为"上一版固定顺序时，**有学生发现"前三个都对"，然后整节课都在数位置**"
    - ⭐⭐ **极珍贵的游戏化漏洞实录**：几乎所有游戏化文章只讲成功，**很少有人写学生怎么把设计玩坏**；而这恰恰暴露了学生真实策略——**任何固定顺序都会暗示规律，规律一旦存在，学生就猜规律而不思考内容**
- ⭐⭐⭐ **AI 做了什么（四层拆解，作者"尽量说实话"）**：① 想法和脚本**人主 AI 辅**（"教学设计、每处要问什么、哪条史料能撑哪条论断，**必须我自己定**"）② 图=AI（5 张 360° 全景，即梦 Seedream）③ 视频=AI（20 光圈 18 段，图生视频）④ 代码=人机共写（**单文件 exe 130MB**，不联网）
  - ⭐⭐ **"AI 生成的永远只是壳"**："全篇二十四条线索、五组二十四条课堂史料库，**全部出自课本和我的课件，原文一字未改**"
  - 💡 与 teachers-as-tool-builders"人做内容 AI 做界面"同源，但多一层学科严谨：**"原文一字未改"是史料教学的前提**，AI 一旦改写引文历史课就废了。**这是"AI 做壳"在特定学科的底线，库内其他页未提**
- ⭐⭐⭐ **最后一句必须留空**：终章「合论」三条论断汇成《治道论》，机器一段段写、**每句带出处**（如"据「因俗而治」「南北面官职掌」「双轨制」"）——**最后一句是空的，必须学生自己写**
  - "**AI 把帐子搭起来、把火点起来、把二十四片纸摊开；至于走进帐子以后看见什么，还是得学生自己看**"
  - 💡 **把留白从"态度"变成"产品设计"**：不是"我们决定不用 AI 写这句"，而是**程序里就是空的、不写就完不成**。**判断权成了流程必经环节，而不是倡议** —— ai-restraint 那页的主张，这里给了可执行形态
- **与库内隋炀帝辩论的对照（同科同能力）**：辩论页=课堂上用 AI 当**史料助手**（横向辨析立场倾向，可复制性高）；本页=课前自制**可交互游戏**，AI 只搭壳不参与判断（纵向辨析相关强度，可复制性低）。**"史料有立场如何辨析" vs "史料是真的但不一定支撑"**
- **7 处双向关联** + cases/yong-ai/index.md 12→**13 个案例**
- **对黄陂按成本排序**：⭐⭐⭐ 三条全零成本（"相关≠能支撑"+"结果 vs 制度"判别法 / "星星后面还是卷子"作游戏化评审标准 / **采分点延后到学生判断之后**）、⭐⭐ "多勾了哪几句"这个批改维度 + 随机防规律、⭐ AI 出图出片、⚠️ **做成 exe/网页不建议区域推**（一人一单元工作量）
- ⚠️ 局限 8 条已写明：**零效果数据**（全文是设计说明非效果报告）/**成本完全没提**（24 线索+5全景+18视频+130MB，花多少时间？这是复制真门槛却恰恰没写）/**只能跑 Windows**（苹果/平板/手机全用不了，130MB 校园网分发也是问题）/**历史学科特例**（史料是现成文本可结构化，换数学物理艺术未必成立）/**三个反着来无对照版本**（"学生在数位置"只是观察无测评）/**"游戏"与"学习"关系未讨论**（记住的是史官体验还是南北面官机制？全文未区分）/ **作者身份不明**（学段学校是否一线教师都没写）/**图未转录**（本页依据文字正文，界面手感动图效果未亲验）
- 更新 index.md + MOC
