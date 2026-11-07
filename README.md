# Visual Story Styles · 可复用的图文设计 Skill

**把资料与想法做成有风格、读得懂、有依据的图文。**

Visual Story Styles 是 Jackson 整理的跨平台设计 Skill，适用于小红书轮播、公众号配图、知识卡片和视觉故事。它提供可检查的设计方法与输入示例，由你使用的 Agent 和可用绘图工具执行。

当前版本：**v0.4 · 2026-11-07**。这是设计说明与配方库，不是独立应用或一键渲染引擎。

## 能做什么

| 模块 | 适合的任务 | 入口 |
|---|---|---|
| 剪贴拼贴 Collage | 人物、文化、唱片册与材料层次丰富的故事 | [拼贴配方](references/collage.md) |
| 复古桌面 Retro Desktop | 档案、资料组织、数据比较与改稿过程 | [复古桌面配方](references/retro-desktop.md) |
| 从参考到视觉系统 | 将参考拆成色彩、字体、材质、网格与共享参数 | [视觉系统工作流](references/visual-system-workflow.md) |
| 数据可视化 | 对齐来源、统计口径、图型、版式与复查记录 | [数据可视化流程](references/data-viz-harness.md) |
| 阅读与证据 | 检查手机可读性、数值、对象、分母与局限 | [共用检查](references/reading-and-evidence.md) |

## 开始使用

将整个仓库目录命名为 `visual-story-styles`，放到支持 `SKILL.md` 的 Agent 的技能目录中。例如 Codex 使用 `~/.codex/skills/visual-story-styles/`。安装时保留 `references/` 和 `examples/`，不要只复制入口文件；已有同名技能时先比较版本，勿直接覆盖本地改动。

入口：[SKILL.md](SKILL.md)。不需要作者的私有账号规则。

```text
使用 $visual-story-styles，选择 retro-desktop。
读者是经常制作图文的创作者。请使用 examples/brief.json 的虚构数据，
设计一页能比较三篇内容收藏数的图，保留“虚构演示数据”标识。
解释图型和阅读顺序，使用当前可用工具实际渲染，
交付成图、可编辑源文件、参数和复用说明。
缺少渲染工具时请明确说明，不把设计方案当成已完成图片。
```

切换为 `collage` 可使用拼贴配方。处理真实内容时，请同时提供主问题、稿件、数据来源、可用图片、平台尺寸和期望编辑格式。数字与照片分别管理，生成式装饰不能替代证据。

## 示例输入

- [brief.json](examples/brief.json)：三篇内容的虚构收藏数，供布局与复算练习。
- [system-contract.json](examples/system-contract.json)：风格参数、页面职责与复用测试计划。
- [data-viz-contract.json](examples/data-viz-contract.json)：来源、样本、去重、指标和检查记录模板。

示例中不存在真实账号数据；空字段保留为待填项，不当成零值。

## 输出与验证

按任务输出设计参数、编号成图、可编辑源文件、图表输入与来源、简短替换说明。只有实际渲染并检查后，才报告成图完成；作者自检、真人试读和正式研究分别记录。

当前已整理规则、模块与示例。新题材、不同模型和复杂长标题仍需实际运行；本仓库不承诺任意输入一次成功，也不宣称已经验证普遍的阅读或效率提升。

## 来源与权利

参见 [SOURCES.md](SOURCES.md) 和 [RIGHTS.md](RIGHTS.md)。本库不包含艺人照片、第三方模板、原文 PDF 或私人账号资料。当前未指定开源许可证；公开可见不代表第三方素材获得再分发许可。

维护方向：从真实作品中记录失败与修订，将可重复的方法沉淀为模块。版本变化见 [CHANGELOG.md](CHANGELOG.md)。
