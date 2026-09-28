# Ainvest · Market 原型覆盖清单

核查日期：2026-09-28。主文件：`stock-prototype.html`，包含样式、脚本和 Market 参考图，可直接在浏览器打开。

## 页面结构

- 每个模块都有「Market 一级页 → 功能二级页 → 详情弹层」，可返回首页。
- 一级页使用提供的 Market 截图；搜索、市场分类、指数、榜单及其他区域模糊，仅新增模块清晰且可点击。
- 左侧为手机原型，右侧固定三部分：需求是什么、为什么能解决、竞品怎么做。窄屏按阅读顺序堆叠。
- 名称统一为 Ainvest；移除「功能 01／05／07」编号。

## 每日简报

| 功能与元素 | 原型操作 | 竞品依据 |
|---|---|---|
| 自选、持仓、单股 | 切换范围；单股下拉选择；自选与其他模块同步 | Robinhood 组合／资产摘要；Yahoo 组合新闻 |
| 日报、滚动周报 | 盘前、收盘、近一周；时间窗口同步更新 | moomoo Daily & Weekly Briefs |
| 市场与收益 | 持仓对比 SPY；收益贡献／涨跌幅切换；查看仓位 | Robinhood Return Drivers、Top Movers、基准 |
| 个股详情 | 事件、价格、量比、研报、技术指标、来源类型 | Robinhood methodology；moomoo 交易细节 |
| 关键事件 | 宏观、财报、公司行动；详情与提醒切换 | Robinhood upcoming events |
| 更新状态 | 更新时间、突发信息条、更新后未读、暂无分析 | Robinhood breaking news；moomoo 无分析状态 |
| 通知 | 盘前、收盘、每周、重大变化偏好 | Yahoo 日／周摘要提醒；Ainvest 自定义节奏 |

逐项 21 项事实与限制见 [简报研究清单](./brief-inventory.md)。自选没有持仓权重，因此不显示伪造的“我的收益”。

## 个股社区

| 功能与元素 | 原型操作 | 竞品依据 |
|---|---|---|
| 股票上下文 | 价格、走势周期、加入自选、价格提醒 | Stocktwits Ticker Page |
| 立场与活动 | 三态投票；情绪指数、讨论热度、参与广度及解释 | Stocktwits Sentiment、Message Volume、Participation Ratio；观望为 Ainvest 扩展 |
| 历史 | 关注人数及变化；价格叠加情绪／讨论量／关注人数；历史表 | Stocktwits Edge 历史数据与叠加图 |
| 信息流 | 精选、最新、已关注、自选、热门、收藏、我的；暂停与模拟新动态 | Stocktwits feeds；moomoo 时间顺序；收藏／我的为流程整合 |
| 搜索与过滤 | 股票／关键词、作者、时间、立场、帖子类型、媒体 | Stocktwits stream filters 与 advanced search |
| 作者与相关股票 | Top Voices、作者主页、关注和新帖提醒；关联股票切换 | Stocktwits、moomoo |
| 帖子互动 | 赞、回复、收藏、分享摘要、翻译、举报、静音、屏蔽与恢复 | moomoo comments；Stocktwits 内容治理 |
| 创作 | 观点、提问、立场、依据、图表／图片／视频、2–3 选项投票 | Stocktwits posts；Webull Community |
| 配套信息 | 新闻来源、财报提醒、电话会文字实录、AI 摘要依据、基本面字段 | Stocktwits ticker context |

逐项事实、23 组来源及平台限制见 [社区研究清单](./community-inventory.md)。综合情绪分数与用户投票占比分开；关注人数不是 DAU。

## AI 自选发现

| 功能与元素 | 原型操作 | 竞品依据 |
|---|---|---|
| 自选驱动 | 自选主题推断、相关标的扩展、排除已有、自动／暂停、新增／移出原因 | Ainvest 组合设计；不能写成竞品已验证同一流程 |
| AI 条件生成 | 示例提示词、输入校验、生成／停止、解释与规则编辑 | TradingView AI Screener；moomoo SG AI Screener |
| 范围与因子 | 自选扩展／自选内／市场；上市地、交易所、股票类型、主题、因子与阈值 | TradingView 筛选器；moomoo 多因子筛选 |
| 规则操作 | 添加、停用、移除、清空；撤销／重做 | TradingView filters 与 custom screens |
| 策略 | 保存、加载、改名、复制、删除、自动保存、预设、新建 | TradingView custom screens；moomoo 策略保存 |
| 结果比较 | 列表、表格、图表、热图；字段顺序、排序；图表周期、类型、均线、网格 | TradingView 结果视图与表格 |
| 结果处理 | 单只／批量自选、详情依据、不感兴趣、CSV 导出 | TradingView、moomoo |
| 分享与显示 | 策略配置复制／导入、公司名称／类型／币种、财务币种换算、刷新 | TradingView screen sharing 与 screener settings |
| 提醒 | 入选／移出／涨跌阈值、频率、时段偏好、开关、触发记录 | TradingView watchlist alerts；入选／移出记录为 Ainvest 扩展 |

逐项事实与来源见 [筛选研究清单](./screener-inventory.md)。TradingView AI Screener 和原生移动端筛选器有平台限制；此处借鉴其流程，重新排成 Ainvest 手机体验。

## 演示边界与 DAU

- 本原型覆盖上述三个模块在已核查官方资料中的功能族；不包含竞品所有资产、付费权限和交易执行服务。
- 行情、持仓、用户、新闻、事件、财务指标和图表均为模拟。筛选使用 20 只样本与本地规则；因子目录用代表指标演示操作，没有全量行情服务。
- 发帖、通知、策略与举报仅在浏览器本地演示；分享复制文本，不向社区发布。电话会展示文字实录；自定义帖子不会伪称已完成 AI 翻译。
- 竞品资料证明功能存在。功能级 DAU、独立 DAU 增量没有可靠公开证据；采用人数、关注人数、累计社区使用比例不当作 DAU。
- 上线实验以每用户活跃天数、增量 DAU、D7／D28 留存为结果指标；同时观察阅读完成、有效自选加入、提醒退订与举报率。

浏览器交互与视觉验收见 [设计 QA](./design-qa.md)。


## Market 一级页行情优化（2026-09-28）

| 模块 | 默认股票示例 | 首页操作 |
|---|---|---|
| 每日简报 | NVDA、MSFT、TSM | 自选／持仓；每股价格、涨跌、走势与事件摘要；单股简报；完整简报 |
| 个股社区 | NVDA、MSFT、AMD | 热门／自选；报价、情绪、参与人数与话题；进入对应个股讨论 |
| AI 自选发现 | AVGO、ANET、GOOGL | 候选／新入选／移出；报价、自选关联；查看依据；直接加自选并重筛 |

共用报价行参考 moomoo 自选列表；社区入口参考 Stocktwits Trending Tickers；AI 结果前置参考 moomoo Screener。来源与采纳边界见 [首页设计依据](market-entry-references.md)。所有数值为示例，不代表当前行情。验收对照图：`qa/market-home-v2-comparison.png`。


## 竞品界面缩略图

3 个竞品分析区共 8 张图片，可点击放大、缩放细节、访问图片出处；HTML 内嵌图片，离线可见。全部来源和界面匹配说明见 [竞品图片来源](competitor-image-sources.md)。Yahoo 使用已明确标注的相关组合界面，其他 7 张为对应功能图／教程截图。
