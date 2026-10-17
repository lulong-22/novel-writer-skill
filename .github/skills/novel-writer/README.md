# novel-writer · Agent Skill

网文工业化写作引擎，GitHub Agent Skill（`.github/skills/novel-writer`）。

## 功能
- 小说大纲、章节生成、润色、bug 修复
- P0/P1/P2 分级合规质检
- 作者文风蒸馏仿写（内置版权防护）
- 抽屉项目隔离、人设防 OOC、伏笔追踪、节奏打分

## 目录
```
.github/skills/novel-writer/
├─ SKILL.md                # 核心技能规则
├─ README.md               # 本说明
└─ assets/                 # 附属资源
   ├─ risk-rule.md
   └─ distill-snapshot-sample.md
```

## 加载方式
- GitHub Copilot / Claude Code / OpenHands：放入仓库 `.github/skills/` 目录，自动识别
- 其他平台（豆包/Cursor/Kimi）：把 `SKILL.md` 全文复制进「自定义角色 / 系统提示词」

## 版本
V2.3.0
