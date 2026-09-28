**10 competitor feature ideas for growing daily active usage**

Research date: September 28, 2026. Audience: US/global retail stock investors and traders.

My recommendation is to start with a personalized daily brief, watchlist alerts, and an earnings companion, supported by a useful watchlist/portfolio home. These give investors a reason to return on days when they do not trade. This prioritization is a product judgment; it is not a measured forecast of DAU uplift.

Public evidence does not support a defensible ranking of ten features by attributable DAU. The research below separates app-level daily usage, feature adoption, and verified functionality. No public controlled experiment establishing incremental DAU was found for these ten features. Competitor size alone does not prove that a feature caused success.

The order balances audience reach, recurring usefulness, evidence of adoption, and implementation effort. It assumes basic quotes, watchlists, news and trading already exist. If these foundations are missing, build the watchlist/portfolio home first. Effort labels are relative judgments, not engineering estimates.

**What the usage evidence actually says**

| Evidence | Observation period | Interpretation and limitation |
|---|---|---|
| Robinhood: approximately **2.7M estimated DAU**, +4.5% quarter over quarter, −1.8% year over year. | Q1 2026; Apptopia article published May 19, 2026. | App-level vendor estimate. Public article does not specify geography, OS coverage, or average versus endpoint aggregation. Not stock-only activity or feature attribution. [Apptopia](https://apptopia.com/en/insights/robinhood-markets-mobile-app-performance-apr-27-2026/) |
| Moomoo reports **DAU +13%** and user-generated content +26% quarter over quarter in its community discussion. | Q3 2025; release March 9, 2026. | A useful community engagement signal. Absolute DAU, population definition and methodology are not given; no causal feature attribution. [Company release](https://en.prnasia.com/releases/apac/moomoo-named-best-global-investment-platform-by-sensor-tower-capping-a-year-of-robust-growth-and-innovation-524450.shtml) |
| Moomoo reports **No. 1 DAU in Singapore and Malaysia**, citing Sensor Tower. | End of Q4 2025. | Regional rank, with no absolute value or fully specified comparison set in the release. Do not generalize to US leadership. [Company release](https://en.prnasia.com/releases/apac/moomoo-named-best-global-investment-platform-by-sensor-tower-capping-a-year-of-robust-growth-and-innovation-524450.shtml) |
| Investing.com displays **5.15M Daily Mobile Visitors**. | Undated measurement; page accessed September 28, 2026. | Daily audience proxy only. App versus mobile web scope, uniqueness and averaging are not explained. Do not relabel this app DAU or compare it directly with Robinhood. [About page](https://www.investing.com/about-us/) |
| Webull: **over 51%** of registered users had participated in virtual trading; **33%** had accessed a community room. | As of December 31, 2025. | Feature-level cumulative adoption, not daily or monthly usage. [2025 Form 20-F](https://www.sec.gov/Archives/edgar/data/1866364/000121390026041653/ea0283691-20f_webull.htm) |
| Webull Vega AI: approximately **480,000 total active users**, including approximately 160,000 new users during the quarter. | Q2 2026; reported August 19, 2026. | Feature-specific usage, but the active-user window and definition are unspecified. Not DAU. [Quarterly release](https://www.sec.gov/Archives/edgar/data/1866364/000121390026091702/ea030257601ex99-1.htm) |
| Robinhood: around **90% of Legend users** center their setups around charts. | Reported June 17, 2025. | Strong adoption signal within a selected active-trader product; not 90% of all Robinhood users and not daily usage. [Product announcement](https://robinhood.com/us/en/newsroom/introducing-robinhood-legend-charts-on-mobile/) |
| Stocktwits calls symbol pages its **most-trafficked surface**. | June 1, 2026. | Qualitative evidence that ticker-level community is central to usage; no numeric feature DAU. [Company announcement](https://www.globenewswire.com/news-release/2026/06/01/3304759/0/en/stocktwits-deepens-its-social-finance-leadership-with-all-new-symbol-pages-centered-on-community-intelligence.html) |

No comparable recent public app DAU was verified for Webull, TradingView, Yahoo Finance or Stocktwits. Public registrations, monthly visitors, funded accounts, downloads and daily average revenue trades were not converted to DAU. This research uses public sources, not a licensed cross-app analytics export.

**1. Personalized daily portfolio brief — Robinhood Cortex and moomoo AI**

Existing pattern: Robinhood summarizes portfolio return drivers and upcoming events. Moomoo provides stock briefs before the open and after the close. Robinhood access is tied to Gold and Portfolio Digests are described as a rolling release. [Robinhood support](https://robinhood.com/us/en/support/articles/cortex-digests/), [moomoo support](https://www.moomoo.com/us/support/topic3_980).

Build: a 60-second home card answering “What changed in my stocks?”, “What explains it?” and “What happens next?” Use holdings, or a watchlist for users without connected accounts. Show three material changes with source links and timestamps. Let users choose morning or closing delivery.

Daily-use hypothesis: personally relevant information changes every trading day. Broad audience; medium effort. Evidence is verified functionality plus app-level context, with no digest-specific DAU. Test brief availability separately from notification delivery so their effects are distinguishable.

**2. One alert rule for a whole watchlist — TradingView**

Existing pattern: an alert condition applies across a watchlist and adjusts when symbols are added or removed. [Official launch, January 23, 2025](https://www.tradingview.com/blog/en/watchlist-alerts-on-tradingview-49839/).

Build: offer three understandable presets: material price move, unusual volume, and earnings release. The latter presets are proposed adaptations, not a claim that TradingView supports this exact bundle. Each alert opens a ticker page explaining the trigger. Add per-user frequency limits and deduplicate related events.

Daily-use hypothesis: users return when something relevant happens, without setting up every ticker separately. Broad audience; medium effort. No public feature DAU found. Measure incremental active days among all assigned users, not only click-through among those receiving an alert.

**3. A watchlist and portfolio home that stays useful — Yahoo Finance**

Existing pattern: iOS Home displays portfolios, watchlists and holdings, including holdings and balances from linked brokerage accounts. The web homepage also supports a personalized portfolio dock. [Yahoo iOS guide](https://help.yahoo.com/kb/SLN22069.html), [homepage dock guide](https://help.yahoo.com/kb/SLN28273.html).

Build: a persistent home showing followed stocks, daily change, holdings performance and relevant headlines. Start with manual holdings or watchlists; brokerage aggregation can follow. Clearly distinguish price changes from total returns and label quote freshness. Make adding the first few symbols fast.

Daily-use hypothesis: users accumulate a personalized resource worth revisiting. Broad audience; low-to-medium effort without account aggregation. Functionality is verified; feature DAU is unavailable. Test the new home against the existing home and measure additional active days, not the count of homepage impressions.

**4. Earnings and macro-event companion — moomoo and Investing.com**

Existing pattern: moomoo offers earnings calendar filters and reminders; Investing.com provides economic releases with forecast, previous and actual values. [Moomoo calendar guide](https://www.moomoo.com/au/manual/topic-14-166), [Investing.com calendar](https://www.investing.com/economic-calendar).

Build: a calendar filtered to holdings/watchlists plus selected macro events. Show a countdown and consensus before the event, then actual results, guidance and a sourced summary afterward. Prioritize a small set of companies before expanding coverage.

Daily-use hypothesis: preparation and follow-up create multiple useful return occasions. Broad audience; medium effort. Earnings are episodic for each company, so portfolio breadth matters. Feature DAU is unavailable; Investing.com's daily mobile visitor figure is only platform context. Run evaluation across both earnings and non-earnings weeks.

**5. Ticker communities with transparent sentiment — Stocktwits, Webull and moomoo**

Existing pattern: ticker discussions, sentiment and followed contributors. Stocktwits' June 2026 redesign emphasizes these on its highest-traffic surface. Webull's filing and moomoo's release provide the adoption and DAU signals in the evidence table.

Build: pilot discussion on a small set of liquid stocks. Surface thoughtful bullish and bearish theses, distinct contributor counts and changes in attention. Add follow and reply notifications. Establish enough credible participation and moderation before widening the pilot.

Daily-use hypothesis: evolving discussion and replies create reasons to return beyond price checking. Medium-to-high audience potential; high ongoing operating effort. The evidence is observational, with no isolated DAU lift. Measure incremental active days for readers as well as contributors; monitor spam, reports and concentration of posting.

**6. Paper trading with a short review loop — Webull and TradingView**

Existing pattern: Webull offers simulated trading, with cumulative participation exceeding 51% of registered users. TradingView supports historical Bar Replay. [Webull filing](https://www.sec.gov/Archives/edgar/data/1866364/000121390026041653/ea0283691-20f_webull.htm), [TradingView replay update](https://www.tradingview.com/blog/en/backtest-with-heikin-ashi-in-bar-replay-53136/).

Build: a virtual portfolio using the familiar order flow, followed by a brief session review. An optional historical scenario lets users practice when markets are closed. The journal and daily scenario are proposed additions; do not present them as proven competitor growth tactics.

Daily-use hypothesis: learning and monitoring simulated positions add active days before funding. Best for beginners and aspiring traders; medium-to-high effort. Test repeat practice over several weeks and keep practice engagement distinct from real-money trading volume.

**7. Saved discovery screens showing what changed — TradingView and moomoo**

Existing pattern: screeners, market rankings and heat maps help users find relevant securities. TradingView saves filters, columns, sorting and display settings; moomoo documents screeners and rankings. TradingView's screeners are a web workflow to adapt for mobile: its current help says they are unsupported in native iOS/Android apps. [TradingView saved screens](https://www.tradingview.com/support/solutions/43000718804-how-to-create-save-and-update-a-custom-screen/), [native-app limitation](https://www.tradingview.com/support/solutions/43000675385-how-do-i-find-a-mobile-screener/), [moomoo walkthrough](https://www.moomoo.com/us/learn/quick-overview).

Build: start with a few explainable screens, such as unusual volume and earnings movers. Let users save a screen and see new entrants or departures since their last visit. The change view is the proposed improvement. Provide a reason for every match and a path to add it to a watchlist.

Daily-use hypothesis: the same research question produces fresh answers each day. Best for self-directed stock pickers; medium effort. No public screener DAU found. Test whether discovery adds active days, including quiet market periods, rather than merely diverting existing ticker-page traffic.

**8. Resume a saved chart setup anywhere — Robinhood Legend**

Existing pattern: mobile and desktop charts synchronize custom views, trendlines and setups. Around 90% of Legend users center their setups around charts. [Robinhood announcement](https://robinhood.com/us/en/newsroom/introducing-robinhood-legend-charts-on-mobile/).

Build: save a small set of chart layouts, indicator preferences and annotations across devices. Add a “continue my analysis” entry point. Start with reliable state persistence and fast chart loading.

Daily-use hypothesis: traders return to their own ongoing analysis instead of recreating it. Narrower active-trader audience; medium-to-high effort. Strong selected-audience adoption, but no DAU uplift evidence. Measure active days across deduplicated identities so switching devices does not inflate success.

**9. Contextual research copilot — Webull Vega AI**

Existing pattern: Webull's Q2 2026 release reports approximately 480,000 total active Vega users, without a daily or monthly definition. [Quarterly release](https://www.sec.gov/Archives/edgar/data/1866364/000121390026091702/ea030257601ex99-1.htm).

Build: place a few useful questions on stock pages, such as “What changed since I last checked?” and “How did results compare with expectations?” Answer with supporting sources and timestamps, then allow follow-up questions. This is a pull-based research workflow, distinct from the scheduled brief in idea 1.

Daily-use hypothesis: the app becomes the place users resolve recurring market questions. Medium-to-high potential; high content-quality effort. Feature adoption is encouraging, but daily repeat usage is unproven. Measure incremental active days alongside answer accuracy, latency, repeat use and cost per additional active user-day.

**10. Extended-hours monitoring and trading — Robinhood 24 Hour Market**

Existing pattern: Robinhood reported more than $10B cumulative overnight volume by March 6, 2024; on its busiest days, up to 25% of total daily volume occurred outside regular hours. This is historical trading-volume evidence, not unique users or DAU. [Company announcement](https://robinhood.com/us/en/newsroom/robinhood-24-hour-market-reaches-10b-in-total-volume-traded-overnight/).

Build: begin with session-aware quotes, news and notifications. If execution infrastructure supports it, add eligible overnight limit orders with clear session selection, pricing and liquidity information.

Daily-use hypothesis: greater accessibility for users outside US market hours. Segment-dependent; very high effort for execution. Evaluate unique active days and users who previously could not participate. Additional evening sessions from already-active users do not increase DAU.

**How to measure success using DAU**

Keep conventional DAU as the primary metric: distinct deduplicated users with a foreground app session per day, excluding background refresh and notification delivery. Define a fixed reporting timezone before testing; also analyze local-day behavior for global users. Report calendar-day and US trading-day averages separately.

Add qualified DAU as a quality check: distinct daily users who intentionally consume a brief, inspect a quote or chart, read research, review a portfolio, practice, or trade. Fix the qualifying events before launch. Record feature DAU separately; feature adoption is not the same as incremental app DAU.

Randomize access at user level and analyze all assigned users, including people who never use the feature. Segment before randomization by existing activity, investor versus trader behavior, geography and account status. A 4–6 week test is a starting planning window; calculate sample size from baseline variance and the minimum meaningful effect, and cover multiple market conditions.

For community features, account for shared-content effects using suitable community or network clusters. Ordinary user-level randomization can be contaminated when treatment users create content that control users also see.

For a fixed cohort, let r be average daily active users divided by assigned users. Estimate incremental DAU at rollout as N × (r_treatment − r_control), where N is the eligible population. Use uncertainty estimates at the randomization unit. This estimates additional daily-active users on an average day. Multiply by the observation-day count to obtain incremental active user-days; repeated opens within a day contribute no additional DAU. Do not add individual feature lifts together without measuring overlap.

Illustrative arithmetic only: 100,000 eligible users × a 2 percentage-point increase in daily activity = 2,000 additional average DAU. This is not a forecast or competitor benchmark.

Check D28 retention from assignment/enrollment and active days per user alongside DAU. Monitor notification opt-outs, low-value sessions, inaccurate explanations, crashes and user complaints. Separate acquired, retained and reactivated users, and use a concurrent control so a market rally is not credited to a release. A higher DAU/MAU ratio by itself can reflect a shrinking MAU denominator.

**Suggested first sequence**

1. Establish the watchlist/portfolio foundation and metric definitions. Audit whether the app can personalize content reliably.
2. Test the daily brief and watchlist alerts, separating content value from notification effects. Start with sourced, narrow content coverage.
3. Add the earnings companion and test sustained activity after earnings season. Evaluate combined lift before rolling the bundle out broadly.
4. Choose the next investment using the audience mix: paper trading for beginners, chart workspaces for active traders, or a curated community pilot where participation is already available.

Actual delivery dates and lift targets require the app's baseline DAU, retention, existing feature inventory and engineering capacity. No uplift forecast is warranted from competitor disclosures alone.
