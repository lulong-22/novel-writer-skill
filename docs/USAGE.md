# 使用教程（USAGE.md）

> 本技能为 GitHub Agent Skill（SKILL.md），适用于支持 Agent 技能的工具。

## 1. 安装

### GitHub Copilot / Claude Code / OpenHands
将本仓库 `.github/skills/novel-writer/` 放入项目的 `.github/skills/` 目录，工具会自动识别并可按需加载。

### gh skill 一键安装
```bash
gh skill install lulong-22/novel-writer-skill novel-writer
```

### 其他平台（豆包 / Cursor / Kimi 等）
复制 `.github/skills/novel-writer/SKILL.md` 全文到「自定义角色 / 系统提示词」，保存后即生效。

## 2. 核心指令

| 指令 | 作用 |
| ---- | ---- |
| `启用网文写作技能` | 手动强制加载本技能 |
| `生成小说大纲` | 按赛道规则输出大纲 |
| `生成小说章节` | 生成章节正文 |
| `润色章节文本` | 合规弱化 + 润色 |
| `执行章节合规质检` | 输出 P0/P1/P2 质检报告 |
| `编辑违禁词库` | 自定义增删词条 |

## 3. 合规质检输出格式

```
【章节风险质检报告】
🔴 P0 高危条目：
序号｜原文片段｜风险说明｜修改方案
🟡 P1 风险条目：
序号｜原文片段｜风险说明｜推荐替换词
🟢 P2 提醒条目：
序号｜原文片段｜风险说明｜优化建议

【总结判定】
整体风险等级：低 / 中 / 高
修改优先级：P0 → P1 → P2
```

示例见 `assets/quality-report-sample.md`。

## 4. 注意事项
1. 语境优先：虚构设定合法，现实可复刻危险/违法实操为红线。
2. AI 产出章节，发布时按平台要求勾选「含 AI 生成内容」标签。
3. 完整版（作者蒸馏、全套赛道词库、风格快照）为付费私有仓库，联系作者获取。
