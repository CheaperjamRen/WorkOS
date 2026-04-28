# CHANGELOG

版本记录。每次更新模板后在这里留痕。

---

## v1.0（2026-04-28）

初始版本发布。

**核心功能**
- 脑倒（Brain Dump）：任意文本 → 5 池子任务分配 + 依赖识别 + 并行机会
- 早报（Daily Brief）：每日工作启动 + 最优执行序列
- 全局（Global View）：项目状态 + 依赖关系 + 健康度评估
- 收工（Checkout）：状态更新 + 记忆沉淀 + 明日建议
- 三种工作模式：正常 / 蒙圈 / 冲刺

**文件结构**
- `CLAUDE.md`：总指挥
- `memory/work-profile.md`：工作身份档案（用户填写）
- `memory/project-state.md`：项目状态（AI 维护）
- `memory/auto-memory.md`：规律积累（AI 维护）
- `skills/task/`：脑倒、早报
- `skills/project/`：全局、并行
- `skills/system/`：收工、模式切换

---

## 待加入（Roadmap）

- `skill-weekly-review.md`：周复盘 skill（回顾这周，准备下周）
- `skill-project-close.md`：项目收尾 skill（归档完成的项目）
- `skill-idea-incubate.md`：想法孵化 skill（将 💡 池子中的想法做系统评估）
- 多平台版本：Cursor Rules 版 / Windsurf 版（不依赖 Claude Code 的版本）
