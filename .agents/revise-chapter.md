# 修订章节流程

## 目标

根据审稿报告修订草稿，输出修订稿到 `perigee/drafts/`。

## 输入

必须读取：

- 原草稿，例如 `perigee/drafts/chapter-001.md`
- 审稿报告，例如 `workflow/reviews/chapter-001.review.md`
- `workflow/working/context-pack.md`
- `workflow/working/chapter-intent.md`

按需读取：

- `perigee/canon/world-state.md`
- `perigee/canon/characters.md`
- `perigee/canon/open-hooks.md`
- `perigee/worldview/ability-contract.md`

## 步骤

1. 提取审稿报告中的必须修改项。
2. 判断哪些问题需要重写段落，哪些只需要局部调整。
3. 输出修订稿到 `perigee/drafts/chapter-XXX.revised.md`。
4. 在回复中列出已处理的问题和仍需用户确认的问题。

## 规则

- 不直接覆盖原草稿。
- 不新增审稿报告外的大幅剧情变化，除非用户明确要求。
- 不自动回写 `perigee/canon/`；定稿后再由用户确认是否同步章节摘要和伏笔状态。
