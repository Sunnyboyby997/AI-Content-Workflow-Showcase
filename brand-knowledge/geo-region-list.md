# GEO 多地区本地化参数（示例）

> 用于 seo-geo-builder 做 GEO 多地区本地化内容时读取。

## 目标市场
| 地区 | 语言 | 货币 | 主流搜索 / AI 平台 | 本地化要点 |
|---|---|---|---|---|
| 美国 US | 英语 | USD | Google / ChatGPT / Perplexity | 价格用 $，口语化 |
| 英国 UK | 英语 | GBP | Google / Bing | 拼写差异（colour / color） |
| 德国 DE | 德语 | EUR | Google | 需本地语种翻译 + 文化适配 |
| 日本 JP | 日语 | JPY | Google / Yahoo | 措辞礼貌，强调细节 |

## 本地化规则
- 价格、尺寸、电压单位按地区换算
- 案例 / 达人 / KOL 用当地真实的
- 关键词不能直译，要查当地真实搜索词（见 seo-keyword-bank.csv 的 target_region）
