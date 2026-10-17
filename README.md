# 网文工业化写作引擎（Agent Skill · 免费公开版）

> 一个符合 **GitHub Agent Skill（SKILL.md）** 规范的网文工业化写作技能包，帮你更高效地写网文、自动做平台合规自检，降低限流和下架风险。

![version](https://img.shields.io/badge/version-V2.3.0--lite-blue)
![license](https://img.shields.io/badge/license-MIT-green)
![platform](https://img.shields.io/badge/platform-Copilot%20%2F%20Claude%20Code%20%2F%20OpenHands-lightgrey)

---

## 🎯 这是什么

面向 **番茄小说 / QQ 阅读** 等平台的网文作者、写手、码字工作室，提供一套 AI 辅助写作 + 合规自检的 Agent 技能：

- ✍️ 小说**大纲撰写**、**章节生成**、**润色扩写**、**bug 修复**
- 🛡️ **P0/P1/P2 分级合规质检**（把风险拆成必改 / 建议改 / 提醒三级，附替换方案）
- 👤 **人设防 OOC**、🔁 **伏笔追踪**、📈 **节奏打分**
- 📂 **抽屉项目隔离**（每本书独立存储人设 / 大纲 / 词库，互不干扰）

---

## ✨ 功能亮点

| 能力 | 说明 |
| ---- | ---- |
| **合规前置自检** | 基于语境判定，区分虚构设定与现实实操，避免机械误判 |
| **三级风控体系** | 🔴 P0 必改 / 🟡 P1 建议改 / 🟢 P2 提醒，直接给替换词 |
| **防 AI 味** | 遵循「语境优先 / 虚实隔离 / 代价守恒」，产出更贴网文语感 |
| **安装即用** | 符合 Agent Skill 规范，主流 Agent 工具可直接识别调用 |

---

## 📦 快速安装

### 方式一：gh skill（推荐）
```bash
gh skill install lulong-22/novel-writer-skill novel-writer
```

### 方式二：直接在仓库内使用
本技能位于 `.github/skills/novel-writer/SKILL.md`，支持 Agent Skill 的环境（GitHub Copilot / Claude Code / OpenHands）会自动识别。

### 方式三：其他平台（豆包 / Cursor / Kimi）
把 `.github/skills/novel-writer/SKILL.md` 全文复制到该平台的「自定义角色 / 系统提示词」即可等效使用。

---

## 🚀 使用示例

```
启用网文写作技能
生成小说大纲
生成小说章节
润色章节文本
执行章节合规质检
```

详细说明见 [docs/USAGE.md](docs/USAGE.md)。

---

## 📸 使用截图

> 以下为演示占位，正式发布前替换为真实截图。

| 大纲生成 | 章节生成 | 合规质检报告 |
| ---- | ---- | ---- |
| `占位图：outline.png` | `占位图：chapter.png` | `占位图：quality-report.png` |

> 📌 说明：以上三张为演示**占位图**，正式上架前请替换为真实使用截图（放入 `docs/images/` 目录，文件名见上表）。目录说明见 [docs/images/README.md](docs/images/README.md)。

---

## 📄 目录结构

```
novel-writer-skill/
├─ .github/skills/novel-writer/
│  ├─ SKILL.md                          # 技能核心规则
│  ├─ README.md                         # 技能说明
│  └─ assets/
│     ├─ risk-rule.md                   # 违禁词分级风控词库
│     └─ quality-report-sample.md       # 质检报告样例
├─ docs/
│  └─ USAGE.md                          # 使用教程
├─ README.md
├─ LICENSE                              # MIT
└─ .gitignore
```

---

## 🆚 免费版 vs 完整版

| 能力 | 免费版（本仓库） | 完整版（付费私有） |
| ---- | ---- | ---- |
| 大纲 / 章节 / 润色 | ✅ | ✅ |
| P0/P1/P2 合规质检 | ✅ | ✅ |
| 人设 / 伏笔 / 节奏 | ✅ | ✅ |
| **作者风格蒸馏** | ❌ | ✅ |
| **全套 8 大分赛道风控词库** | ❌ | ✅ |
| 抽屉记忆 + 风格快照 | ❌ | ✅ |
| 综合质检报告（含风格匹配） | ❌ | ✅ |

> 需要完整版请联系作者（GitHub 主页 / 私信）购买私有仓库访问权。

---

## ⚖️ 版权与合规声明

本 Skill 仅提供写作规则、合规质检、文风蒸馏能力，用于**辅助原创创作**。
严禁用于批量洗稿、抄袭他人小说；使用者须遵守目标平台内容规则与相关法律法规。本工具不构成任何医疗、法律建议。

---

## 📄 协议

[MIT](LICENSE) © 2026 lulong-22

---

## 📌 版本历史

- **V2.3.0-lite**：免费公开版发布（核心写作 + 合规质检）
