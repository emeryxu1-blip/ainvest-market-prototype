# Alpha Radar 入口更新

参考用户提供 Market 长图中的 Master Holdings：保留黑色选中胶囊和持仓卡片层级，原政客／Aime Portfolio／High-Return Users 改用简短中文，新增 KOL 并默认选中。KOL 采用三只股票行情行、多空人数和作者摘要，股票进入双方作者名单。

以下为前版入口研究记录；个股社区已替换。

---

# Ainvest · Market 一级入口参考

核查：2026-09-28。范围仅覆盖三个新增模块；行情与社区指标均用原型静态样例，不代表实时数据。

## 四个官方参考

| 参考 | 已核实的元素与交互 | 用到 Ainvest |
|---|---|---|
| [moomoo · Watchlist 导航](https://www.moomoo.com/us/learn/what-is-the-watchlist-tab) | 股票按市场分组；列表可按价格、成交量、涨跌幅排序；可切换报价列、加入自选；长按股票进入编辑。 | 行情行固定 ticker / 公司名 / 价格 / 涨跌幅；价格右对齐，涨跌带正负号。一级保留三个静态例子，点击股票进入对应内容。 |
| [moomoo · Screener](https://www.moomoo.com/screener) | 顶部市场、行业、Watchlist Only；Add Filter / Save Screener；结果显示数量及 Symbol、Stock Name、Price、% Chg、Chg、Market Cap、Volume。 | AI 卡片先展示股单，再展示命中标签；“来自你的自选”说明输入来源；“查看全部”进入完整筛选，不能只放一句 AI 功能介绍。 |
| [Stocktwits · 首页](https://stocktwits.com/) | Trending Tickers 每项组合排名、ticker、价格、涨跌幅和社区讨论摘要，整项链接股票页；Market Pulse 有 Most Active / New Watchers；内容流有 For You / Following。 | 社区一级直接显示三只热门股票，每行有行情及讨论量 / 看多比例。保留“最热 / 自选”分组；点行进入该股票社区；“查看全部”进入社区。 |
| [Yahoo Finance · Most added to watchlist](https://finance.yahoo.com/research-hub/screener/most_watched_tickers/) | 官方搜索索引显示表格含 Symbol、Name、1D Chart、Price (Intraday)、Change、Change %、Volume、Follow，并有 Heatmap View、Customize、Save。本次直开限流，字段由官方页面索引核实。 | 每行提供股票身份、报价和独立的涨跌信号；可用短行情线补充走势。对简报加入“一句为何异动”；首页直接满足看行情，再引导阅读。 |

## 三个模块的内容结构

**个性化简报：** 标题“与你相关的行情” → 盘前 / 收盘 → 三行行情及异动摘要 → “阅读完整简报”。示例：NVDA / 英伟达 / 142.87 / +2.34%，次行“新增订单预期改善”；MSFT / 微软 / 428.62 / +0.86%，次行“云业务投入仍是关注点”。第三行用现有行情数据。点击股票应进入该股简报详情；底部入口进入完整简报。

**股票社区：** 标题“市场正在聊” → 最热 / 自选 → 三行股票，每行行情下方显示“1.2k 条讨论 · 68% 看多”等明确为样例的指标 → “查看全部讨论”。看多 / 看空双向表达用细条或文字，不能让价格涨跌颜色承担情绪含义。点击股票直接进入对应社区，避免先落到默认 NVDA。

**AI 股单：** 标题“AI 为你发现” → “基于 NVDA、MSFT、TSM、AMD” → 三行候选股票及行情 → 每行一句“为何匹配”，例如“AVGO · 与 NVDA 同属 AI 算力”；可以显示“新入选”标签及“＋”加入自选 → “查看完整股单”。点击股票打开命中详情，独立加号避免整行点击与加自选冲突。来源说明、命中标签是 Ainvest 的产品设计建议，不声称竞品已有同款 AI 解释。

## UI 建议

- 一个白色模块，标题 19–20px；股票代码 15–16px 半粗，解释 11–12px；行高 72–84px。白底细分隔线，避免每只股票都叠独立卡片。
- ticker 左侧、数字右侧；价格采用等宽数字。涨跌幅带正负号和颜色，按美国市场惯例绿涨红跌。
- 三行默认完整可见；“查看全部”作为底部轻量文本入口，不用抢夺行情区域的大号 CTA。
- 保留 Market 参考图其余区域的模糊处理。新增模块信息清晰，不能只有按钮和宣传语。

可直接看的官方行情列表图：[moomoo Watchlist 截图](https://nnqimage.futunn.com/16249603406101-101000103-web-a77d5c1695e751a7.png)。该图来自 moomoo 官方教学页，展示代码、名称、价格、涨跌及盘前列；只作布局参考。
