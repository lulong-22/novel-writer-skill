# 网文工业化写作引擎（Agent Skill 仓库）

> GitHub Agent Skill 打包：`netwowen` / 网文工业化写作 V2.3.0

## 这是什么
一个符合 GitHub Agent Skill（SKILL.md）规范的网文工业化写作技能包，支持：
- 小说大纲、章节生成、润色、bug 修复
- P0/P1/P2 分级合规质检
- 作者文风蒸馏仿写（内置版权防护）
- 抽屉项目隔离、人设防 OOC、伏笔追踪、节奏打分

## 目录结构
```
├─ .github/skills/novel-writer/
│  ├─ SKILL.md
│  ├─ README.md
│  └─ assets/ (risk-rule.md / distill-snapshot-sample.md)
├─ README.md
└─ LICENSE
```

## 安装到本地 Agent
```
gh skill install <你的用户名>/novel-writer-skill novel-writer
```

## 使用示例
```
启用网文写作技能
执行作者风格蒸馏（粘贴参考文本）
执行章节合规质检
```

## 版权与合规声明
本 Skill 仅提供写作规则、合规质检、文风蒸馏能力，用于辅助原创创作。
严禁用于批量洗稿、抄袭他人小说，使用者须遵守目标平台内容规则与相关法律法规。

## 版本
V2.3.0
