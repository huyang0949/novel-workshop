# novel-workshop

本仓库用于沉淀小说项目资料、写作工作流和 AI 协作流程。

## 当前项目

| 目录 | 说明 |
|---|---|
| `perigee/` | 现代异能灾变题材项目，已建立轻量写作工作台 |
| `the_musician_of_dreams/` | 独立作品资料目录 |
| `.agents/` | AI 写作流程手册 |

## perigee 工作流

`perigee/` 采用轻量状态机：

```text
chapter-intent -> context-pack -> draft -> review -> revision -> canon update
```

核心目录：

- `perigee/canon/`：已确认正史入口。
- `perigee/working/`：当前写作任务和上下文包。
- `perigee/drafts/`：章节草稿和修订稿。
- `perigee/reviews/`：审稿报告。
- `perigee/forecasts/`：候选剧情推演，不自动进入正史。

常用流程见 `.agents/`：

- 写下一章：`.agents/write-next-chapter.md`
- 审稿：`.agents/review-chapter.md`
- 修订：`.agents/revise-chapter.md`
- 剧情推演：`.agents/forecast-plot.md`
- 导入旧稿：`.agents/import-existing-draft.md`
