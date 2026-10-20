# retention-funnel-analysis

留存/转化漏斗分析的链式推进方法：全景扫描 → 断裂点拆解 → 用户分类画像 → 假设验证 → 行动建议，附数据踩坑速查。

## 安装

```bash
git clone https://github.com/imQiwei/retention-funnel-analysis.git ~/.claude/skills/retention-funnel-analysis
```

Claude Code 会按 `SKILL.md` 里的 `description` 自动匹配触发，也可以用 `/retention-funnel-analysis` 手动调用。完整说明见 [SKILL.md](SKILL.md)。

出 HTML 报告时配合 [data-report-html](https://github.com/imQiwei/data-report-html) 使用。

skill 用中文编写。示例数字均为虚构，表名、字段名为通用占位，请按自己的数据平台替换。

同系列 skills：[data-task-spec](https://github.com/imQiwei/data-task-spec) · [data-report-html](https://github.com/imQiwei/data-report-html) · [briefing-script](https://github.com/imQiwei/briefing-script)
