# Alpha Radar · 功能与口径

替换原个股社区；入口沿用用户 Market 长图中的 Master Holdings。统一改名 Alpha Radar，保留政客、Aime 组合、高收益用户，并增加 KOL。

## 可交互路径

- Market 默认 KOL：NVDA、MSFT、AMD 报价、涨跌、去重多空人数、作者摘要。
- 点击股票：看多与看空两组完整名单、观点、时间、原帖示例。
- 按股票／按 KOL：代码、公司、昵称搜索，24 小时／7 天、全部／已关注筛选。
- KOL 主页：其看多／看空股单、关注状态；点击股票继续查看两边观点。
- 加入自选：与每日简报和 AI 自选发现共用自选列表。
- 政客、Aime、高收益用户：卡片切换、详情，跳转对应股票的 KOL 多空。
- 竞品缩略图：TipRanks、Stocktwits、DATAROMA，点击放大与跳转来源。

## 数据口径

固定示例截面 2026-09-28 14:30 UTC；6 位虚构 KOL、6 只股票、40 条观点，全部非真实账号与帖子。

先在所选时间窗内按作者／股票保留最新记录，再排除中立；同作者发多条只计一人，最新中立会使旧多空失效。人数与名单从同一数据计算。无观点和未表态不当作看空。观点时间范围为包含端点的 24 或 168 小时。

「全部」仅指已收录账号，不代表全量 Twitter。生产接入需提供获授权数据源、账号覆盖、最后同步时间、原帖链接和观点纠错；原型不包含爬虫、实时 AI 分类或真实通知。

## 官方来源与借鉴

- [TipRanks NVDA Blogger Opinions](https://www.tipranks.com/stocks/nvda/bloggers)：股票 → Bullish/Bearish 作者表 → 原文／关注。
- [TipRanks 官方介绍](https://www.tipranks.com/news/labs/capitalize-the-power-of-financial-bloggers-with-tipranks-blogger-sentiment-tab)：博客观点情绪及作者。包含多个内容平台，不等于全量 X。
- [Tradu 官方 TipRanks 集成](https://www.tradu.com/my/intelligent-tools/)：用于 TipRanks 功能缩略图，标为集成界面。
- [Stocktwits 情绪](https://help.stocktwits.com/sentiment)：多空情绪与股票讨论。
- [Stocktwits 历史指标](https://help.stocktwits.com/c/stocktwits-edge/stocktwits-edge/historical-sentiment-data)：情绪、讨论量及参与广度分别呈现。
- [DATAROMA 持仓](https://www.dataroma.com/m/holdings.php?m=mc)：Holdings/Activity/Buys/Sells/History；申报数据属于历史截面。

## 验证指标

有效阅读 DAU（打开至少一只股票的观点名单并阅读观点）、个股观点打开率、原文打开率、关注后的交易日回访天数。待验证假设；未找到这些单项功能对 DAU 的公开因果证据。
