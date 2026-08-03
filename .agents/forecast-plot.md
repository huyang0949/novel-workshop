# 剧情推演流程

## 目标

为未来剧情生成多个候选路线，输出到 `workflow/forecasts/`，不改正史。

## 输入

必须读取：

- `perigee/canon/book-profile.md`
- `perigee/canon/world-state.md`
- `perigee/canon/characters.md`
- `perigee/canon/open-hooks.md`
- `workflow/working/current-focus.md`

按需读取：

- `perigee/plot/volume-strategy.md`
- `perigee/plot/ten-major-arcs.md`
- `perigee/worldview/worldbuilding-review.md`

## 输出格式

写入 `workflow/forecasts/<topic>.md`：

```markdown
# 剧情推演：<topic>

采用状态：候选

## 推演目标

## 路线 A

- 核心变化：
- 优点：
- 风险：
- 对人物的影响：
- 对世界状态的影响：
- 适合兑现的伏笔：

## 路线 B

## 路线 C

## 推荐
```

## 规则

- 每次输出 2 到 5 条路线。
- 路线必须互相有实质差异，不要只是措辞不同。
- 不把推荐路线写入 `perigee/canon/`。
- 如果路线会推翻既有设定，必须显式标注“需要用户确认”。
