# AI 教育知识库 Wiki Harness

本文件是 `~/wiki/ai-education/` 的唯一执行规范。所有 Agent 在整理、查询、晋级、更新该知识库时，必须以本文件为准。

---

## 角色

Agent 是知识库维护者，职责是把每日新闻、文章、碎片信息整理为可持续积累、可查询、可复用、可汇报的结构化知识。

## 核心方法

**优先解决「以后怎么找」，再决定「现在放哪里」。** 分类必须从真实材料和检索场景中推导，不能从固定模板套用。

## Metadata

新建或更新页面必须补 metadata。字段名用英文，说明中英双写：

```yaml
---
title: 页面标题
domain: ai-education           # 固定值：ai-education
scope: policy | product | tool | research | practice
topic: 主题名
primary_entry: 主入口           # 用户最可能用什么问题找回
secondary_entries:
  - 辅入口                     # 交叉找回路径
status: current                # draft | current | archive | unknown
date: YYYY-MM-DD
objects:
  - 对象/机构/人名/系统/事件
---
```

`status` 四类：
- `draft` 草稿：内容正在形成，不能作为最终口径
- `current` 当前：当前有效，可引用
- `archive` 归档：历史材料，不默认代表当前口径
- `unknown` 未知：未整理或尚未判断有效性

## 入口规则

每个页面必须有 `primary_entry`，允许多个 `secondary_entries`。每个入口必须能转换成一句自然语言找回问题。

## 结构性变更审核

涉及以下情况时，Agent 必须在最终回复中明确披露发现的问题、暂不处理的原因、建议下一步：

- 移动或重命名文件
- 创建新的主题目录
- 合并多个页面
- 删除或归档页面
- 改动超过 5 个页面
- 修改检索入口体系

保守处理是允许的。先修复低风险问题，把结构性动作留到后续。

## 发现但暂不执行的问题

但凡识别出以下问题且选择暂不执行，必须显式告知用户：

- 内容页位置不符合当前目录规则
- 页面缺少或不符合 metadata
- MOC 检索地图缺失或入口不清
- 存在断链、孤立页、重复页、过时页或应归档页

## Query 流程

Agent 回答知识库相关问题时：

1. 判断问题属于哪个 scope
2. 读取 MOC 检索地图，找到入口
3. 优先读取 `status: current` 的页面
4. `archive` 和 `unknown` 只作为背景
5. 如果本次查询暴露找回困难，更新检索地图

## Log 规则

结构性变更写入 `wiki/log.md`。治理记录写入 `wiki/governance-log.md`。单页小范围内容更新可以不写。

## 禁止事项

1. 禁止把固定模板强套到所有主题
2. 禁止为了整齐创建空目录
3. 禁止没有主入口就移动文件
4. 禁止复制正文到多个入口
5. 禁止把「其他/杂项/未分类」作为长期正式分类
6. 禁止不读主题现状就直接新建主题
7. 禁止大规模迁移后不更新链接、metadata、检索地图
8. 禁止让 `SCHEMA.md` 复制本文件的长规则
