# Wiki Schema — AI 教育知识库

> 参照 `system/wiki-harness.md` 执行。本文件定义结构、标签和约定。

---

## Domain

人工智能在教育领域的应用，涵盖：课堂教学、教育数字化政策、AI 教学工具、大模型教育场景、智慧教育案例。

## Directory Structure

```
wiki/ai-education/
├── system/               # 治理层：宪法 + 细则
│   ├── wiki-harness.md   # 宪法 — 最高执行规范
│   └── wiki-governance.md # 细则 — 晋级/模板/健康检查
├── decisions/            # 决策记录（架构取舍记录）
├── moc/                  # MOC 检索地图
│   └── ai-education.md   # AI 教育总览
├── raw/                  # 原始材料
│   └── articles/
├── cases/                # 教师案例
│   ├── yong-ai/
│   ├── chuang-ai/
│   └── hu-ai/
├── practice-log/         # 教研手记（对话中涌现的教研建议，单条一记，满3条升格）
│   └── {topic}/          # 按主题分目录（如 micro-course/ teacher-training/）
├── entities/             # 结构化实体页
├── concepts/             # 结构化概念页
├── comparisons/          # 对比分析页
├── queries/              # 已归档查询
├── _archive/             # 已归档/过期页面
├── SCHEMA.md             # 本文件
├── index.md              # 页面索引
├── log.md                # 结构性变更日志
└── governance-log.md     # 治理记录日志
```

---

## 教研手记（practice-log/）

**为什么存在**：本库原有三类内容，只有两处有位置——外链文章进 `raw/articles`，已成文的本地资料同样进 `raw/articles`（source_url 写"本地资料"）。但**对话中涌现的教研建议**（无成文、无 URL、一次讨论产生多条）**没有归属**，拿 concepts 的"成文标准"去接必然接不住。

这类内容不是「文章」，是「**病例**」：谁、卡在哪、我怎么建议的、后来怎么样。

### 单条格式（5 行内写完，不要求成文）

```markdown
### YYYY-MM-DD 一句话标题
**场景**：（谁 / 什么需求 / 卡在哪）
**我的建议**：（原话，可直接引用）
**后来**：（可空，验证后再补）
```

### 升格规则（硬规则）

1. **同主题满 3 条 → 提炼成 `concepts/` 页面**
2. 单条**永远留在** practice-log，**不删**
3. concepts 页末尾**链接回** practice-log 的原始条目（保留场景可追溯）

### 什么情况不必记

某个建议**从不再出现**（一次性、不重复）→ 不记，直接扔碎片盒。
判据一句话：**这个建议我是不是第三次说了？**

### 与碎片盒的分工

| | 碎片盒（飞书多维表格） | practice-log |
|---|---|---|
| 性质 | 收件箱（**未加工**） | **已判断、待聚合** |
| 位置 | 飞书云 | wiki 本地（随 git 同步） |
| 出口 | 可能被丢弃 | **满 3 条必升格** |
| 谁记 | 随手 | 墨墨按讨论内容整理 |

> 两者是**上下游**关系，不是替代关系：现场随手扔碎片盒 → 值得留的转 practice-log → 满 3 条升格进 concepts。
