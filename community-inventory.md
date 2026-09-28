# Ainvest 个股社区竞品清单

核查日期：2026-09-28。范围为「个股讨论与社区发现」及其内嵌行情、新闻、财报上下文。以下是已核查的功能族，不能宣称复刻了竞品所有全球产品。页面存在、官方帮助说明与 DAU 因果是三种不同证据。

## 已确认功能与原型映射

| 功能族 | 竞品已确认的功能 / 元素 | 原型落点 | 限制 / 注意 |
|---|---|---|---|
| 股票上下文 | Stocktwits 个股名称、价格、变动、盘后状态、图表、价格提醒、+Watch | 报价、时间范围、加入/移出自选、价格提醒表单 | 行情为演示；关注读写共享自选，联动简报与AI筛选 |
| 群体立场 | Stocktwits 看多 / 看空投票；发帖情绪标签 | 保留三态投票；发帖立场 | 观望是 Ainvest 扩展；百分比投票不等于 Stocktwits 综合情绪分数 |
| 综合情绪 | Stocktwits Sentiment 结合标签、点赞、回复与活动，近期活动权重更高 | 社区指标：情绪指数；点击解释 | 原型指数为固定示例，未复制私有算法 |
| 讨论量 | Stocktwits 24h Message Volume，相对于该股票平时活跃度，0–100 分 | 社区指标：讨论热度 | 热度不等于人数或 DAU |
| 参与广度 | Stocktwits 独立发帖账号相对于帖子量 | 社区指标：参与广度 | 用来区分很多人参与与少数人重复发言 |
| 关注人数 | Watchers 是加入自选该股的用户数；可比较增量 | 报价下方人数 / 日增量；关注 / 取消 | 不是该股 DAU |
| 历史与叠加图 | 情绪、消息量历史；Watchers / Sentiment / Volume 叠加价格 | 社区指标：三类叠加图、1D–ALL、历史表 | Stocktwits 长历史与扩展关注数据属 Edge；免费为当前对比前一天 |
| 精选与实时流 | Stocktwits 重设计将实时帖子与情绪前置；Latest 可暂停 / 恢复 | 精选 / 最新；实时开关；新动态按钮 | 暂停操作官方明确 web；app 默认实时。原型为本地更新模拟 |
| 个性化流 | Stocktwits Following / Watchlist / Trending / Suggested | 已关注 / 自选 / 热门 / 精选；额外收藏 / 我的 | 自选读取现有 state.seeds；主题流 Beta 不作为稳定全量能力 |
| 流筛选 | Stocktwits 按帖子类型、看多看空、媒体；高级搜索按股票、作者、日期 | 筛选与搜索 sheet | 帮助页对 media-only 表述有歧义，不照搬 GIF/多cashtag 的隐含语义 |
| 作者发现 | Stocktwits Top Voices；moomoo 头像打开主页，Follow | 活跃作者折叠卡、主页、关注作者 | 活跃不代表可信或盈利能力 |
| 作者提醒 | Stocktwits 作者主页铃铛订阅新帖 | 作者主页新帖提醒开关 | 本地偏好，不发通知 |
| 关联标的 | Stocktwits Related Symbols 覆盖相似ticker、主题、行业 | 关联股票卡，点击切换 | 仅用 market 中存在的ticker；无帖子时明确空态 |
| 基础互动 | moomoo 新帖在前、赞、回复、分享 | 原有赞 / 回复；分享摘要及复制 | 不向真实社区发送 |
| 更多操作 | moomoo Save、Report、Translate | 收藏 / 收藏流；举报表单与记录；译文 | 静态帖有预置译文；自定义内容不伪装已翻译 |
| 内容治理 | Stocktwits 静音用户/股票，屏蔽，举报，可从设置恢复 | 帖子菜单，偏好与屏蔽，恢复 | 举报仅本地模拟；不声称平台已处理 |
| 发布 | Stocktwits $TICKER、文字、情绪、图片/图表；Webull 分享观点、问题、创建投票 | 发帖文本、依据、立场；附行情图 / 文件；创建投票 | 至多4张图片或单个视频；本地上传总计限4MB，Stocktwits图片上限为4张 |
| 热门投票 | Stocktwits Top Discussions，投票后显示结果与总票；可关闭投票 | 内置主题投票 / 新建投票；偏好显示开关 | 仅投票参与者意见 |
| 新闻 | Stocktwits 个股 News | 新闻tab、条目来源sheet | 虚构材料示例 |
| 财报 | Stocktwits Earnings Calendar / Live Calls / AI Earnings Summary | 财报tab：日程、提醒、实录、摘要、依据 | 原型没有真实音频，只演示文字实录路径 |
| 基本面 | Stocktwits 官方重设计描述 Fundamentals；公开 NVDA 页也有该tab | 基本面tab字段快照 | 数值明确为展示字段，不是真实公司数据 |

## 官方来源

1. [Stocktwits 2026-06-01 新版 Symbol Pages 公告](https://www.globenewswire.com/news-release/2026/06/01/3304759/0/en/stocktwits-deepens-its-social-finance-leadership-with-all-new-symbol-pages-centered-on-community-intelligence.html)：实时社区与情绪前置，Top Voices，Related Symbols，Watchers 历史及价格叠加；公司称个股页为平台流量最高页面，未公布此功能DAU。
2. [官方周报对新版的说明](https://chartart.stocktwits.com/p/monday-bccd)：精选帖前置、直接看多看空投票、关注数据与关联标的。
3. [个股页说明](https://help.stocktwits.com/c/navigating-the-platform/navigating-the-platform/ticker-page)：图表、情绪、量、新闻、财报、提醒、+Watch。
4. [NVDA 实际公开个股页](https://stocktwits.com/symbol/NVDA)：名称、价格、日内/隔夜变动、关注量、投票、Feed / News / Fundamentals 可见。
5. [Ticker Sentiment](https://help.stocktwits.com/c/key-features-of-stocktwits/key-features-of-stocktwits/ticker-sentiment)：综合情绪来源；不能写成只对看多看空投票计数。
6. [Message Volume](https://help.stocktwits.com/c/faqs/faqs/message-volume)：24小时、相对常态、0–100、历史窗口。
7. [Participation Ratio](https://help.stocktwits.com/c/faqs/faqs/participation-ratio)：独立账号相对消息量，归一化分数。
8. [Watchers](https://help.stocktwits.com/c/faqs/faqs/watchers)：加入自选的人数、头部显示与增量意义。
9. [历史情绪与图表叠加](https://help.stocktwits.com/c/stocktwits-edge/stocktwits-edge/historical-sentiment-data)：免费与 Edge 的明确区分。
10. [Home Feed](https://help.stocktwits.com/c/navigating/articles/home-feed)：Following、Watchlist、Trending、Suggested。
11. [帖子类型筛选](https://help.stocktwits.com/c/key-features-of-stocktwits/key-features-of-stocktwits/stream-filters-post-types)。
12. [情绪与媒体筛选](https://help.stocktwits.com/c/key-features-of-stocktwits/key-features-of-stocktwits/stream-filters-sentiment-and-media)。
13. [实时与暂停](https://help.stocktwits.com/c/key-features-of-stocktwits/key-features-of-stocktwits/real-time-streaming-and-pause-live-feed)：暂停明确为web，app默认实时。
14. [发布消息](https://help.stocktwits.com/c/key-features-of-stocktwits/key-features-of-stocktwits/how-to-post-a-message) 与 [情绪标签](https://help.stocktwits.com/c/key-features-of-stocktwits/key-features-of-stocktwits/bullish-bearish-sentiment-tags)。
15. [图片与图表附件](https://help.stocktwits.com/c/key-features-of-stocktwits/key-features-of-stocktwits/attaching-images-and-charts-to-a-post)：每帖至多4张。
16. [投票与热门讨论](https://help.stocktwits.com/c/key-features-of-stocktwits/key-features-of-stocktwits/polls-and-top-discussions)：投票结果、票数、显示偏好。
17. [作者新帖提醒](https://help.stocktwits.com/c/key-features-of-stocktwits/key-features-of-stocktwits/subscribing-to-creator-notifications)。
18. [静音用户或股票](https://help.stocktwits.com/c/faqs/faqs/mute-user)、[屏蔽与恢复](https://help.stocktwits.com/c/faqs/faqs/block-user)、[举报](https://help.stocktwits.com/c/faqs/faqs/report-post-or-user)。
19. [高级搜索](https://help.stocktwits.com/c/key-features-of-stocktwits/key-features-of-stocktwits/advanced-search)：股票、作者、日期。
20. [财报日历与电话会](https://help.stocktwits.com/c/key-features-of-stocktwits/key-features-of-stocktwits/earnings-calendar-and-live-calls)、[AI财报摘要](https://help.stocktwits.com/c/key-features-of-stocktwits/key-features-of-stocktwits/ai-earnings-summary)。
21. [moomoo Stock comments](https://www.moomoo.com/us/manual/topic-14-28)：时间顺序、赞、回复、分享、Save / Report / Translate、Follow、用户主页、写帖。
22. [Webull Community](https://www.webull.com/feature/community)：可定制内容/类别筛选，观点、提问、投票、互动；Learn 属相邻学习模块，不强塞入个股讨论。
23. [Stocktwits Stream Topics Beta](https://help.stocktwits.com/c/key-features-of-stocktwits/key-features-of-stocktwits/stream-topics-beta)：跨股票主题，正在逐步开放，不应写成所有用户已上线。

## 实现接入与测试

文件：`community-enhancements.js`、`community-enhancements.css`、`community-copy.html`。脚本在现有JS定义之后、Market路由包装之前载入；再调用一次renderAll。语法检查：node --check community-enhancements.js 通过。仅包装renderCommunity和compose；保留原vote / like / reply / follow等事件。新增state在render时默认初始化，重置原型也兼容。

建议测试路径：Market社区入口 → 社区指标 → 切换1W和讨论量 → 返回讨论 → 筛选看空 → 清除 → 关注作者 / 作者提醒 → 收藏 → 收藏tab → 分享 → 更多 → 举报并看记录 → 静音再恢复 → 发布附图/投票 → 最新流查看本地新帖 → 新闻 / 财报 / 基本面tab → 关联AMD空态 → 返回Market。

DAU只作为待实验目标：实际验证可看「按股票阅读/投票/回复后7日内的交易日回访天数」，配合屏蔽率、举报率、有效来源阅读；竞品公开页面没有证明具体按钮提高DAU。
