# 写下一章流程

## 目标

根据 `perigee/working/chapter-intent.md` 生成本章上下文包，并输出章节初稿到 `perigee/drafts/`。

## 输入

必须读取：

- `perigee/canon/README.md`
- `perigee/canon/book-profile.md`
- `perigee/canon/world-state.md`
- `perigee/canon/characters.md`
- `perigee/canon/open-hooks.md`
- `perigee/working/current-focus.md`
- `perigee/working/chapter-intent.md`

按需读取：

- `perigee/plot/volume-strategy.md`
- `perigee/plot/ten-major-arcs.md`
- `perigee/worldview/README.md`
- `perigee/worldview/worldbuilding.md`
- `perigee/worldview/ability-contract.md`
- `perigee/worldview/characters-organizations.md`

## 步骤

1. 检查 `chapter-intent.md` 是否缺少章节编号、视角人物、场景地点、本章目标和结尾钩子。
2. 如果缺口会影响写作，先向用户列出需要确认的问题；如果缺口可合理暂定，在 `context-pack.md` 标注“暂定”。
3. 生成或刷新 `perigee/working/context-pack.md`，只保留本章需要的事实、人物、组织、能力、场景状态和伏笔。
4. 根据上下文包输出草稿到 `perigee/drafts/chapter-XXX.md`。
5. 草稿末尾不要附加解释性总结；需要说明的风险写在回复里或审稿报告里。

## 输出要求

- 草稿要有明确场景、行动、人物目标和结尾推进。
- 异常现象要可感知、可追踪，但不提前解释全部体系。
- 不直接改 `canon/`。
- 不把 `forecasts/` 的候选路线当成已发生事实。
