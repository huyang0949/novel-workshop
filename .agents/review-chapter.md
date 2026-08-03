# 审稿流程

## 目标

审阅指定草稿，输出结构化审稿报告到 `perigee/reviews/`。

## 输入

必须读取：

- 待审草稿，例如 `perigee/drafts/chapter-001.md`
- `perigee/working/chapter-intent.md`
- `perigee/working/context-pack.md`
- `perigee/canon/book-profile.md`
- `perigee/canon/world-state.md`
- `perigee/canon/characters.md`
- `perigee/canon/open-hooks.md`

按需读取：

- `perigee/worldview/ability-contract.md`
- `perigee/plot/volume-strategy.md`

## 审稿维度

1. 章节目标是否完成。
2. 人物动机是否成立。
3. 情绪推进是否连贯。
4. 爽点、悬念或压迫感是否有效。
5. 世界观设定是否冲突。
6. 伏笔是否新增、推进、兑现或遗忘。
7. 对话是否符合角色。
8. 是否有明显 AI 腔、空泛描写或解释过量。

## 输出格式

写入 `perigee/reviews/chapter-XXX.review.md`：

```markdown
# chapter-XXX 审稿报告

## 结论

- 建议：通过 / 小修 / 大修 / 重写

## 主要问题

| 严重级别 | 位置 | 问题 | 修改建议 |
|---|---|---|---|

## 维度检查

## 可保留亮点

## 修订优先级
```

## 规则

- 审稿只指出问题和建议，不直接改正文。
- 邮件式客套、泛泛夸奖和空洞建议不要写。
- 发现设定冲突时引用对应资料路径。
