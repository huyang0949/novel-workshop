# novel-workshop

本仓库用于沉淀小说项目资料、写作工作流和 AI 协作流程。

## 当前项目

| 目录 | 说明 |
|---|---|
| `perigee/` | 现代异能灾变题材项目，只放小说内部资料 |
| `workflow/` | 写作流程、模板、审稿和参考分析 |
| `the_musician_of_dreams/` | 独立作品资料目录 |
| `.agents/` | AI 写作流程手册 |

## perigee 工作流

`perigee/` 只保留小说本身相关内容；写作流程、模板、审稿、候选推演和参考拆解统一放在 `workflow/`。

推荐流程：

```text
workflow/working -> perigee/drafts -> workflow/reviews -> revision -> perigee/canon
```

核心目录：

- `perigee/canon/`：已确认正史入口。
- `perigee/worldview/`：世界观、能力、人物与组织设定。
- `perigee/plot/`：卷纲和长线剧情规划。
- `perigee/drafts/`：章节草稿和修订稿。
- `workflow/working/`：当前写作任务和上下文包。
- `workflow/reviews/`：审稿报告。
- `workflow/forecasts/`：候选剧情推演，不自动进入正史。
- `workflow/model/`：拆解、对照和参考分析。

常用流程见 `.agents/`：

- 写下一章：`.agents/write-next-chapter.md`
- 审稿：`.agents/review-chapter.md`
- 修订：`.agents/revise-chapter.md`
- 剧情推演：`.agents/forecast-plot.md`
- 导入旧稿：`.agents/import-existing-draft.md`
