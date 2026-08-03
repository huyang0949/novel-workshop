# working 入口

`working/` 保存当前写作任务的临时输入和中间结果。这里的内容不等于正史，完成后需要用户确认才能同步到 `canon/`。

## 文件分工

| 文件 | 作用 |
|---|---|
| [current-focus.md](current-focus.md) | 当前阶段、卷/章目标、已确认写作方向 |
| [chapter-intent.md](chapter-intent.md) | 下一章写作意图 |
| [context-pack.md](context-pack.md) | 写作前由资料压缩出的上下文包 |

## 使用规则

- 每次写新章节前，先更新 `chapter-intent.md`。
- 写作前生成或刷新 `context-pack.md`，避免全文塞入模型。
- 草稿输出到 `drafts/`，审稿输出到 `reviews/`。
