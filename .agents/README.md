# novel-workshop Agent 流程

本目录保存可复用的写作工作流说明。它们不是全局规范，只用于本仓库的 AI 写作协作。

## 流程清单

| 文件 | 用途 |
|---|---|
| [write-next-chapter.md](write-next-chapter.md) | 根据章节意图生成上下文包并写草稿 |
| [review-chapter.md](review-chapter.md) | 审阅草稿，输出问题和修订建议 |
| [revise-chapter.md](revise-chapter.md) | 根据审稿报告修订章节 |
| [forecast-plot.md](forecast-plot.md) | 推演未来剧情候选路线，不污染正史 |
| [import-existing-draft.md](import-existing-draft.md) | 导入旧稿并提取可回写状态 |

## 通用约束

- 先读作品目录下的 `perigee/canon/README.md` 和 `workflow/README.md`。
- 候选内容放 `workflow/forecasts/` 或 `workflow/working/`，不要直接写入 `perigee/canon/`。
- 修改 `perigee/canon/` 前必须明确说明要回写的事实，并等待用户确认。
- 不把大体量源文件全文复制进上下文包；只提炼与当前任务有关的事实。
- 如果发现原始资料存在乱码、冲突或缺口，先报告，不做批量替换。
