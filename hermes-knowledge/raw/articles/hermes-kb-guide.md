---
source_url: https://toutiao.com/group/7628589107953795625/
source_name: 今日头条
author: AI实战派老陈
ingested: 2026-06-02
---
# 用 Hermes Agent 搭建个人知识库：3 天搞定，终身受益

作者：AI实战派老陈

## 核心思路

用 Hermes Agent 搭建个人知识库，解决「资料越存越多但找不到」的痛点。

## 架构设计（三层）

```
应用层 ── CLI / WebUI 对话界面
检索层 ── MEMORY.md + USER.md + 自定义技能
存储层 ── 文件目录（knowledge-base/）
```

## 目录结构

```
knowledge-base/
├── 1-Projects/   # 项目资料
├── 2-Areas/      # 长期领域
├── 3-Resources/  # 参考资料
├── 4-Archive/    # 归档
└── MEMORY.md
```

## 关键配置
- MEMORY.md 存项目信息、知识分类、检索规则
- USER.md 存工作方式、回复偏好
- 标签不超过 5 个（#项目、#技术、#参考、#待办、#归档）

## 踩坑记录
1. Python 环境冲突 → 用 Hermes 自带 venv
2. MEMORY.md 多设备冲突 → Git 管理或单设备编辑
3. 检索准确率 90% → 加关键词提取 + 重要文档加标签
4. 大文件处理慢 → 转文本或只存路径，设 10MB 上限
