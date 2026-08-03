# 导入旧稿流程

## 目标

读取已有章节或片段，提取章节摘要、人物状态、世界状态变化和伏笔变化，供用户确认后回写。

## 输入

- 用户指定的旧稿文件。
- `perigee/canon/book-profile.md`
- `perigee/canon/world-state.md`
- `perigee/canon/characters.md`
- `perigee/canon/open-hooks.md`

## 步骤

1. 识别旧稿章节边界、标题、视角人物和时间地点。
2. 为每章生成摘要：核心事件、人物变化、世界状态变化、新增伏笔、兑现伏笔。
3. 输出提取结果到 `workflow/reviews/import-<source>.md`。
4. 向用户列出建议回写到 `perigee/canon/` 的事实，等待确认。

## 规则

- 不直接改 `perigee/canon/`。
- 不把旧稿中互相冲突的内容自动合并；冲突要单独列出。
- 不从风格或语气推断隐藏设定，只记录文本中明确可见的信息。
