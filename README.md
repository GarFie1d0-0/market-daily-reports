# market-daily — Proma Agent Skill

全球金融市场深度日报生成器。覆盖 A 股、港股、美股、日股、加密货币五大市场。

## 功能

- 并行搜索 8-14 个信息源（中英文双语），覆盖五大市场
- 技术分析：支撑/阻力位、均线、RSI、MACD、链上数据
- 多 AI 源交叉验证：展示多空逻辑链分歧及根源
- 事件日历 + 风险矩阵
- 报告自动 Git 存档于本地 `reports/` 目录

## 结构

- `skill/SKILL.md` — Skill 定义文件
- `reports/` — 每日报告存档（不纳入版本控制）
- `.gitignore` — 排除敏感文件和报告

## 触发方式

在 Proma Agent 中手动调用，说"市场日报"/"market daily"/"全球市场报告"即可。
