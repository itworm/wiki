# Wiki Schema — 旅行知识库

> 参照 `~/wiki/ai-education/system/wiki-harness.md` 的通用规范执行。本文件定义 travel 库的结构、标签和约定。

---

## Domain

个人出行与旅行规划，涵盖：行程方案（多日路线）、目的地攻略（景点/美食/住宿）、交通衔接（车次/换乘）、在地体验。

## Directory Structure

```
wiki/travel/
├── moc/                  # MOC 检索地图
│   └── travel.md         # 旅行总览
├── destinations/         # 目的地攻略页（按城市/区域）
├── itineraries/          # 多日行程方案页
├── concepts/             # 通用概念（如雨季出行、温泉选择）
├── comparisons/          # 对比分析（同类目的地/方案对比）
├── raw/                  # 原始材料（攻略截图、票务截图）
├── _archive/             # 已归档/过期页面
├── SCHEMA.md             # 本文件
├── index.md              # 页面索引
└── log.md                # 结构性变更日志
```

## Metadata

新建或更新页面必须补 metadata：

```yaml
---
title: 页面标题
domain: travel
scope: itinerary | destination | logistics | experience
topic: 主题名
primary_entry: 主入口           # 用户最可能用什么问题找回
secondary_entries:
  - 辅入口
status: current                 # draft | current | archive | unknown
date: YYYY-MM-DD
updated: YYYY-MM-DD
objects:
  - 城市/景点/交通枢纽/酒店
---
```

### scope 说明

| scope | 用途 | 示例 |
|-------|------|------|
| `itinerary` | 多日行程方案 | 昆明-建水-弥勒九日 |
| `destination` | 单个目的地攻略 | 建水古城攻略 |
| `logistics` | 交通/票务/换乘 | 建水↔弥勒交通方案 |
| `experience` | 美食/住宿/在地体验 | 建水美食清单 |

### status 说明

- `draft` 草稿：方案正在形成
- `current` 当前：可执行的有效方案
- `archive` 归档：已被新版取代的历史方案，**不默认代表当前口径**

## 归档规则

行程方案被新版取代时：
1. 旧版加 `status: archive` + `superseded_by: <新页面名>`
2. 移入 `_archive/`，**不删除**（保留决策痕迹）
3. MOC 与 index **只列 current 页面**，归档页不进检索地图
