# 海外 DTC 品牌内容 AI 工作流

用 Claude Code + Skills + 子 Agent 搭建的海外 DTC 品牌内容生产与复盘体系，
覆盖 JD 要求的全部职责：品牌内容、SEO/GEO、短视频、社媒、网红/论坛种草、数据复盘。

## 目录结构
- `.claude/skills/` — 4 个可复用 Skill（文案去AI化 / SEO+GEO / 短视频脚本 / 内容复盘）
- `.claude/agents/` — 4 个子 Agent（策略总控 / 内容生产 / SEO-GEO / 数据复盘）
- `brand-knowledge/` — 品牌知识库（定位、卖点、人群、竞品、SEO词库、GEO本地化、复盘数据）
- `content_output/` — AI 批量产出资产（文案 / 社媒 / 脚本 / GEO内容 / 复盘资产）

## 怎么用
1. 把 `brand-knowledge/` 里的示例替换成你的真实品牌信息
2. 用 content-strategist 总控定选题 → 分发给 copy-producer / seo-geo-specialist 生产
3. 用 data-review-agent 复盘数据 → 迭代策略 → 沉淀资产

## 核心能力（对应 JD）
- Skill 化：把「去AI化文案 / SEO-GEO / 脚本 / 复盘」沉淀成可复用技能
- 子 Agent 编排：总控 + 生产 + SEO + 数据四个角色协同
- 知识库接入：品牌调性 / 卖点 / 词库 / 本地化参数统一管理
- 文件夹级批量产出：`content_output/` 按类型自动归档
