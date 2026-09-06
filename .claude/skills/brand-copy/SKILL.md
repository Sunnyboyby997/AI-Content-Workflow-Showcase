---
name: brand-copy
description: >
  Use when the user asks to write, rewrite, or de-AI-ify marketing copy for a
  DTC brand (English or Chinese) — product descriptions, landing page copy, social posts,
  short-video scripts, or ad copy. Applies the brand voice and removes
  AI-sounding phrasing. Trigger phrases: "写文案", "去AI化", "产品文案", "社媒贴",
  "短视频脚本", "product copy", "social post", "rewrite this copy", "brand voice".
---

# Brand Copy — 去AI化品牌文案

写任何文案前，按顺序执行以下规则。

## 1. 先读品牌知识库（有就用，没有就问）
写之前先读项目里这些文件（如果存在）：
- `brand-knowledge/品牌定位.md`
- `brand-knowledge/产品卖点.md`
- `brand-knowledge/目标用户.md`
- `brand-knowledge/竞品分析.md`

缺哪个文件，就先向用户要对应的信息，不要瞎编。

## 2. 品牌语气（tone）
- 像真人说话，用第一/第二人称（"you"，不要写 "users/customers"）。
- 短句，一句一个意思。
- 给具体数字和细节，不要堆形容词。"11-hour battery" 而不是 "long-lasting"。
- 有观点、有态度，可以诚实说产品的边界和适用场景。
- 不要套话、不要口号。

## 3. 去AI化规则（禁用词 & 禁用句式）

### 英文 AI 味词 / 句式（一律不用）
- "In today's fast-paced world"、"Unleash the power of"、"Elevate your experience"
- "Game-changer"、"Revolutionary"、"Seamless"、"Robust"、"Cutting-edge"
- "Harness the power of"、"Dive into"、"It's not just X, it's Y"
- "Whether you're... or..."、"Looking for...?"、"In the world of..."

### 中文 AI 味词（一律不用）
- 动词类：赋能、打造、引领、助力、解锁、焕新、重塑、颠覆、破圈、出圈、深耕、发力、触达、击穿、沉淀、对齐、复盘
- 名词/形容词类：极致、重磅、重磅来袭、重磅上线、全方位、闭环、抓手、矩阵、颗粒度、链路、体感、心智、声量、渗透、赛道、生态、布局、降本增效
- 套话短句：不容错过、值得期待、一触即达、尽享、品质之选、匠心之作、精益求精、全新体验、无限可能

### 中文 AI 味句式（一律不用）
- "在这个…的时代"、"随着…的发展"、"不仅…更…"、"通过…实现…"
- "致力于"、"旨在"、"让…成为可能"、"重新定义…"、"开启…新时代"、"为你带来全新体验"

替代做法：给一个具体事实、一个真实场景、或一句大白话。中文同理——给具体数字和真实场景，比如"续航 40 小时"而不是"超长续航"、"充电 5 分钟听歌 2 小时"而不是"极速快充"。

## 4. 输出格式
- 产品文案：标题 + 3 段短段落 + 3 条要点（每条 ≤ 12 词）
- 社媒贴：钩子（第一行）+ 2-3 行 + 3-5 个 hashtag
- 短视频脚本：HOOK(0-3s) / 痛点或场景(3-10s) / 演示(10-20s) / CTA(最后3s)，每段写"口播词 + 屏上文字"


## 5. 质量线
- 每次输出末尾加一行「去AI化自查」，列出本次删掉/避开的 AI 味词。
- 直到没有禁用词、每句都像人话，才算完成。
- 如果要求批量生成，先出草稿，再标注哪些需要人工挑选。

## 6. 输出前自检
- 逐行扫描：确认没有出现上面全部AI禁用词、禁用句式
- 检查：全部优先使用具体数字/场景，禁止空泛形容词
- 校验：必须包含产品边界，写明适合/不适合什么场景
> 如果发现违规，立刻原地重写，不要输出带问题文案。