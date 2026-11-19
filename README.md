# mindmap-craft

把大材料做成你能闭卷讲出来、能亲手改、能拿去干活的思维导图。

Turns large, messy material into a mind map you can retell, edit, and use.

## 想法

市面上的导图工具给个想法就吐一张图，图是给人看的，看完就完。这个 skill 把导图当思考的正本：材料先备齐，骨架先立全，一格一格往里填；关键词由人亲手选，因为提取线索里没有本人的编码，记得住才怪；图做完要过闭卷复述，讲不出来就不算完。AI 干组装的活，人只留在选关键词和验收两个点上。

产出物（PRD、报告、讲解稿）不从原始材料直出，先过图，再过复述，最后才投影成文档。

## 安装

把 `SKILL.md` 放进你的 Agent Skills 目录（例如 Claude Code 的 `.claude/skills/mindmap-craft/`），或用 skills CLI：

```bash
npx skills add lyhSuc/mindmap-craft
```

## English

Most mind-map tools hand you a finished diagram. This skill builds the map as your thinking layer instead: gather the full material first, lay out the whole skeleton, fill it one branch at a time, let the human pick the keywords (a retrieval cue without your own encoding in it recalls nothing), and accept the map only after a closed-book retell. The AI assembles; the human stays at exactly two points, keyword selection and acceptance. Documents are never written straight from raw notes. They go through the map, pass the retell test, and only then get projected into deliverables.

## License

MIT
