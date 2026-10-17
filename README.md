# 网文工业化写作引擎（Agent Skill · 免费公开版）

> 一个符合 GitHub Agent Skill（SKILL.md）规范的网文工业化写作技能包，帮你更高效地创作网文、自动做平台合规自检。

![GitHub release](https://img.shields.io/badge/version-V2.3.0--lite-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## 🎯 这是什么
面向 **番茄小说 / QQ 阅读** 等平台网文作者与写手的 AI 辅助写作技能，提供：
- 小说大纲撰写、章节生成、润色扩写、bug 修复
- **P0/P1/P2 分级合规质检**（降低限流、下架风险）
- 人设防 OOC、伏笔追踪、节奏打分
- 抽屉项目隔离（每本书独立存储人设/大纲/词库）

## ✨ 功能亮点
- **合规前置自检**：把违规风险按 P0（必改）/P1（建议改）/P2（提醒）三级拆解，输出替换方案
- **避免 AI 味**：遵循语境优先、虚实隔离，产出更贴合网文语感
- **安装即用**：符合 Agent Skill 规范，Copilot / Claude Code / OpenHands 可直接识别

## 📦 快速安装
```bash
gh skill install lulong-22/novel-writer-skill novel-writer
```
或在支持 Agent Skill 的环境，直接引用本仓库 `.github/skills/novel-writer/SKILL.md`。

## 🚀 使用示例
```
启用网文写作技能
生成小说大纲
生成小说章节
执行章节合规质检
```

## 📸 演示（待补充截图）
> （此处预留使用效果截图：大纲生成、章节生成、质检报告示例）

## 🆚 免费版 vs 完整版
| 能力 | 免费版（本仓库） | 完整版（付费私有） |
| ---- | ---- | ---- |
| 大纲/章节/润色 | ✅ | ✅ |
| P0/P1/P2 合规质检 | ✅ | ✅ |
| 人设/伏笔/节奏 | ✅ | ✅ |
| **作者风格蒸馏** | ❌ | ✅ |
| **全套 8 大分赛道风控词库** | ❌ | ✅ |
| 抽屉记忆 + 风格快照 | ❌ | ✅ |
| 综合质检报告（含风格匹配） | ❌ | ✅ |

> 需要完整版请联系作者（GitHub 主页 / 私信）购买私有仓库访问权。

## 📄 目录结构
```
├─ .github/skills/novel-writer/
│  ├─ SKILL.md
│  ├─ README.md
│  └─ assets/ (risk-rule.md / distill-snapshot-sample.md)
├─ README.md
└─ LICENSE
```

## ⚖️ 版权与合规声明
本 Skill 仅提供写作规则、合规质检、文风蒸馏能力，用于**辅助原创创作**。
严禁用于批量洗稿、抄袭他人小说；使用者须遵守目标平台内容规则与相关法律法规。

## 📄 协议
[MIT](LICENSE)

## 版本历史
- V2.3.0-lite：免费公开版发布（核心写作 + 合规质检）
