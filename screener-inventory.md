# Ainvest · 自选驱动 AI 筛选竞品核查

核查日期：2026-09-28。范围：股票筛选、筛选结果处理、自选列表提醒、AI 条件生成；未把其他资产交易或整个终端都算进本模块。以下为产品能力证据，不是功能 DAU 或因果提升证据。

## 已确认的功能与原型覆盖建议

| 能力 | 已确认竞品事实 | Ainvest 原型元素 / 操作 |
|---|---|---|
| 市场入口 | moomoo 可由 Markets 进入 Screener。[操作教程](https://www.moomoo.com/us/learn/how-to-use-stock-screener-on-moomoo) | Market 首页清晰模块 → 筛选二级页 |
| 筛选范围 | TradingView 可选自选和颜色标记列表；只显示当前筛选器支持的资产类型。[自选范围](https://www.tradingview.com/support/solutions/43000724549-how-to-scan-watchlist-or-flagged-list/) | 自选内筛选 / 从自选扩展 / 全市场；明确扩展是 Ainvest 方案 |
| 地域与上市地 | TradingView 支持全球、单一和多市场，并可仅显示主要上市地。[全球市场](https://www.tradingview.com/support/solutions/43000669877-how-to-scan-global-stocks/) | 市场、交易所、股票类型、主要上市地筛选；演示数据不足时显示空态 |
| 条件操作 | TradingView 的条件可搜索、添加、编辑、停用、移除、全部清空，并可折叠条件栏。[条件编辑](https://www.tradingview.com/support/solutions/43000718745-how-to-use-filters-in-screener/) | 条件编辑面板、运算符、值、移除、添加；一键重置 |
| 因子目录 | moomoo 列出范围、行情描述、估值、股本、技术、每股、盈利、增长、效率、偿债、现金、券商持仓、公司估值、特色指标 14 类。[指标说明](https://www.moomoo.com/us/support/topic3_68) | 分组因子选择器；每类用一个可计算演示指标说明流程，不声称具备全量数据服务 |
| 指标参数 | moomoo 的技术指标有周期和预设信号；TradingView 可使用财务期间、技术指标参数与盘前盘后数据列。[moomoo](https://www.moomoo.com/us/support/topic3_68) · [TradingView](https://www.tradingview.com/support/solutions/43000718866-tradingview-stock-screener-trade-smarter-not-harder/) | 因子说明、周期、条件值和盘前 / 正常 / 盘后时段 |
| 模板管理 | TradingView 支持新建、打开、命名、保存、复制、删除、自动保存和撤销 / 重做；保存条件、列、排序、视图。[模板管理](https://www.tradingview.com/support/solutions/43000718804-how-to-create-save-and-update-a-custom-screen/) | 我的策略面板、预设策略、保存输入、载入/复制/改名/删除；条件撤销 / 重做 |
| 自定义表格 | TradingView 可新增、移除、重排列、修改参数、升降序；同一指标可配不同周期。[表格](https://www.tradingview.com/support/solutions/43000718744-working-with-tables/) | 列选择、上下移动、排序字段与方向、表格横向滚动 |
| 多视图 | TradingView 股票筛选已有表格、图表、热图。图表可改日期范围、线/柱/蜡烛等类型、网格、均线和成交量。[视图](https://www.tradingview.com/support/solutions/43000724233-chart-view-mode/) | 列表 / 表格 / 图表 / 热图；图表周期、类型和均线；手机采用单列卡片 |
| 展示与刷新 | TradingView 可控制标志、名称、类型、币种显示及自动刷新频率。[筛选概览](https://www.tradingview.com/support/solutions/43000718866-tradingview-stock-screener-trade-smarter-not-harder/) | 展示设置、刷新设置、最后更新时间；原型刷新只更新模拟轮次 |
| 币种 | TradingView 财务数据可换算为统一货币；最新价仍为标的报价币种。[币种](https://www.tradingview.com/support/solutions/43000639101-currency-conversion-in-the-stock-screener/) | 财务单位 USD/EUR，股价保留 USD，演示汇率注明 |
| 加入自选 | moomoo 和 TradingView 均支持单只及批量处理筛选结果。[moomoo](https://www.moomoo.com/us/learn/how-to-use-stock-screener-on-moomoo) · [TradingView](https://www.tradingview.com/support/solutions/43000473930-how-to-add-the-screener-search-results-to-the-watchlist/) | 勾选、全选、批量加入；已在自选的标的显示已有状态 |
| 导出 | TradingView 可从模板菜单导出结果。[导出](https://www.tradingview.com/support/solutions/43000474432-how-to-export-screener-data/) | 下载当前筛选结果 CSV，带当前选择的列 |
| 分享 | TradingView 可开关单个筛选方案的分享并复制链接；接收者可复制。私有自选、未登录和套餐可能限制内容。[分享](https://www.tradingview.com/support/solutions/43000766328-how-to-share-your-screen/) | 生成可导入的本地配置文本；原型不假装发布云端链接 |
| 批量提醒 | TradingView 将同一条件独立应用于列表内每只标的，自选增删后同步更新；美股/ETF 可含盘前盘后。[列表提醒](https://www.tradingview.com/support/solutions/43000739708-watchlist-alerts-your-trading-edge/) | 条件、阈值、频率、时段、启停、触发记录；演示触发可验证 |
| AI 条件生成 | TradingView AI Screener 将自然语言映射为现有条件、列和排序，并提供原因解释。[AI Screener](https://www.tradingview.com/support/solutions/43000785770-how-to-use-the-ai-screener/) | 输入框、示例提示词、生成过程、可编辑规则、规则映射解释 |
| AI 状态与限制 | TradingView 有预置提示词、剩余额度、停止、输入错误；公测为付费用户，股票专用，不支持移动设备。[AI Screener](https://www.tradingview.com/support/solutions/43000785770-how-to-use-the-ai-screener/) | 示例模板、字数校验、无法识别时说明；Ainvest 手机布局是改编，不标成竞品移动端现状 |
| moomoo AI | 新加坡官网确认 AI Stock Screener；AI 可自然语言提问，结合行情、新闻、社区，跳转依据；会员与地区有差异。[SG 功能矩阵](https://www.moomoo.com/sg/events/ai-features) | AI 依据入口与风险偏好输入。该页面不能证明美国所有账户已开通，也不能证明自动读取自选或定时后台扫描 |

## 必须与竞品事实区分的 Ainvest 扩展

- 用现有自选归纳业务主题，再主动找未关注的相近标的。
- 自选变化后自动重筛；关闭后保留上次依据与结果，手动更新。
- 比较相邻两轮结果，给出「新入选 / 已移出」及原因。
- 在 Market 一级页显示候选数量、变化摘要，点击进入完整工作台。
- 标签相关只表示业务联系；原型匹配分不得称为涨跌概率或收益置信度。

这些组合是设计假设，不能写为 TradingView 或 moomoo 已有的同一条完整链路。TradingView 官方仍表示 iOS/Android 筛选器未支持：[移动端限制](https://www.tradingview.com/support/solutions/43000675385-how-do-i-find-a-mobile-screener/)。

## 简洁右侧文案

**需求是什么**：用户已有自选，却不知道哪些相近公司值得研究；传统筛选器要求先懂指标、再配置规则，结果变化也难追踪。

**为什么能解决**：AI 把自选与一句话需求变成可修改的条件；用来源股票、命中指标解释入选；自动保留新入选和移出记录；一键加入自选后形成下一轮研究起点。衡量入口到筛选完成率、有效候选加入率及使用后 D7 回访；DAU 提升需实验验证。

**竞品怎么做**：TradingView 擅长完整筛选工作台与列表提醒，AI 可解释条件映射；moomoo 把移动端多因子筛选、策略保存、批量加自选放在市场发现路径。Ainvest 保留这些能力，把默认起点改为用户现有自选。
