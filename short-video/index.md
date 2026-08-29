# 短视频/短剧知识库

> 用途：积累爆款拆解与脚本结构模式，写脚本时"从库里调模式"，而不是每次从零想。
> 联动 skill：`short-video-script`（写脚本的主流程）。

## 导航

| 目录 | 内容 |
|------|------|
| `concepts/` | 脚本结构模式：黄金3秒、反转类型学、钩子公式……每个概念一个文件 |
| `raw/` | 爆款拆解：刷到好视频 → 拆结构入库（hook用了什么、反转在哪、为什么抓人） |
| `moc/` | 概念地图，随时更新引用关系 |

## 使用方式

- **写脚本**：先看 `moc/short-video.md` 选模式，再调用 `short-video-script` skill
- **拆解入库**：看到好视频 → 在 `raw/` 新建 `YYYY-MM-DD-标题.md` → 按拆解模板填 → 提取的模式进 `concepts/` → 更新 MOC
- **维护**：每次入库更新 `log.md`

## 关联

- skill: `short-video-script`（工作流入口）
- skill: `humanizer`（去AI味，脚本必过）
- skill: `creative-ideation`（选题脑暴）
- 工具: 小云雀（字节剪映团队 AI 内容创作 Agent，输入脚本→生成分镜/数字人/成片）
