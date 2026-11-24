# Investing and Markets Track: From First Trade to Valuation

Track 2 of 3 · Pranav's self-study roadmap · starts Wed 25 Nov 2026

This track rotates with Quant and Crypto: one track per day, Sundays free for catch-up. The full calendar is at the bottom.

Everything here is free. Paid books are marked "(paid, optional)" and nothing depends on them.

The goal is to understand markets well enough to invest your own money sensibly and to read charts, financial statements and option chains with real understanding. Where a technique is popular but weak (a lot of chart reading), the plan says so and makes you test it with data instead of taking it on faith.

---

## 0. How to use this file

Each session is about 60 minutes:

| Block | Time | What you do |
|---|---|---|
| Market check | 5 min | Glance at Nifty, Sensex, S&P 500, USD/INR, 10-year G-sec yield. Write one line on what moved and why |
| Learn | 25 min | The Varsity chapter, ChartSchool page or lecture listed |
| Practice | 25 min | Charting on TradingView, a Python notebook, or a spreadsheet |
| Journal | 5 min | Update `notes/investing.md` and your paper-trade journal |

Accounts and tools (all free):
- TradingView free account, for charts and paper trading.
- Screener.in, for Indian company financials and exporting data.
- Python with `yfinance`, `pandas` and `mplfinance` (use the `.NS` suffix for NSE tickers, like `TCS.NS`).
- A paper-trade journal spreadsheet with columns for date, ticker, setup, entry, stop, target, size, exit, P&L, R-multiple, and lessons.

Rule for this whole track: no real money in individual stock trades until you finish Checkpoint 2. Starting a small index-fund SIP is fine at any time.

---

## 1. Map of this world

| Area | Question it answers | Main source here |
|---|---|---|
| Market structure | How do exchanges, brokers, depositories and IPOs work? | Varsity Module 1, IndiaInvestments wiki |
| Technical analysis | What are price and volume telling me right now? | Varsity Technical Analysis, StockCharts ChartSchool, Bulkowski |
| Fundamental analysis | Is this a good business? | Varsity Fundamental Analysis, annual reports, Screener.in |
| Valuation | What is it worth, and is the price reasonable? | Damodaran's free online classes |
| Derivatives | How do futures and options work, and who loses money in them? | Varsity Futures and Options modules |
| Portfolio and behaviour | How much of what, and how do I avoid hurting myself? | IndiaInvestments wiki, Howard Marks memos, Berkshire letters |

---

## 2. Core resources

Indian markets
- Zerodha Varsity: [zerodha.com/varsity](https://zerodha.com/varsity/), free modules with an app. You'll use Introduction to Stock Markets, [Technical Analysis](https://zerodha.com/varsity/module/technical-analysis/), Fundamental Analysis, Futures Trading, Options Theory, Markets and Taxation, and Personal Finance.
- Varsity's YouTube videos on technical analysis: [English series](https://www.youtube.com/playlist?list=PLX2SHiKfualEyD05J9JsklEq1JFGbG6qJ) and a [Hindi series](https://youtube.com/playlist?list=PLX2SHiKfualGOP9093b6qo11EsgCz8IuQ) that Varsity's own team links from the chapter pages.
- CA Rachana Ranade on YouTube: clear explanations of fundamentals, balance sheets, IPOs and the basics of how markets work.
- [r/IndiaInvestments wiki](https://www.indiainvestments.wiki): community-written guides, starting with the "Zero to Investing" series for absolute beginners.
- SEBI's investor site (investor.sebi.gov.in) and NSE's investor education pages, for official rules.

Technical analysis
- StockCharts ChartSchool: [table of contents](https://chartschool.stockcharts.com/table-of-contents). Covers chart types, support and resistance, trend lines, gaps, [chart patterns](https://chartschool.stockcharts.com/table-of-contents/chart-analysis/chart-patterns), candlesticks and indicators, plus John Murphy's free "Charting Made Easy" ebook.
- Thomas Bulkowski's [ThePatternSite](https://thepatternsite.com/): over 650 free articles with actual statistics on how often each pattern works and fails. See the [performance ranking](https://www.thepatternsite.com/id75.html) and his free [Patternz software](https://thepatternsite.com/PatternzNew.html), which finds patterns automatically.
- Lo, Mamaysky and Wang (2000), "Foundations of Technical Analysis": [NBER paper](https://www.nber.org/papers/w7613). MIT researchers turned chart patterns into algorithms and tested them on 31 years of US stocks. They found that some patterns do carry information, but less than chartists claim.

Valuation and investing philosophy
- Aswath Damodaran (NYU Stern), all free on YouTube:
  - [Foundations of Finance Online](https://www.youtube.com/playlist?list=PLUkh9m2BorqndWimijiJ-VCAXjJUrzJQU)
  - [Corporate Finance Online](https://www.youtube.com/playlist?list=PLUkh9m2BorqnDenjSLZ2DHIXrdxoN4Bn_) (36 short sessions)
  - [Valuation Online](https://www.youtube.com/playlist?list=PLUkh9m2BorqnKWu0g5ZUps_CbQ-JGtbI9) (25 sessions)
  - Investment Philosophies, linked from his [class list](https://pages.stern.nyu.edu/~adamodar/New_Home_Page/classlist.htm), along with his slides, spreadsheets and datasets.
- Howard Marks' memos (oaktreecapital.com/insights/memos) and Warren Buffett's Berkshire Hathaway shareholder letters (berkshirehathaway.com/letters/letters.html). Free and written for everyone.
- Morgan Housel's essays on the Collab Fund blog. The original "Psychology of Money" essay that became the book is free there.

Classic books (paid, optional): Japanese Candlestick Charting Techniques (Nison); Technical Analysis of the Financial Markets (Murphy); The Intelligent Investor (Graham); One Up on Wall Street (Lynch); Coffee Can Investing (Mukherjea).

---

## 3. The sessions

### Block A · How markets work

#### I01 · Wed 25 Nov 2026 · The plumbing of Indian markets
- Read: Varsity Introduction to Stock Markets, the first chapters (why invest, regulators, market intermediaries, the IPO market, the stock market).
- Read: IndiaInvestments wiki "Zero to Investing" part one.
- Practice: draw a one-page diagram showing what happens when you buy 1 share of TCS on Zerodha, from the app to the broker, the exchange, the clearing corporation and the depository (CDSL/NSDL). Note what T+1 settlement means.

#### I02 · Sat 28 Nov 2026 · IPOs, indices, corporate actions
- Read: the Varsity Module 1 chapters on IPOs, trading terminology, indices, and corporate actions (dividends, splits, bonuses, buybacks).
- Practice: pick a recent or upcoming mainboard IPO. Open its Red Herring Prospectus (RHP) on SEBI or NSE and read three sections: Objects of the Issue, Risk Factors and Basis for Issue Price. Write five bullet points on whether the pricing looks reasonable compared with listed peers.
- Note on "grey market premium" (GMP): it's unofficial and unregulated. Track it for one IPO and compare it with the actual listing price.

#### I03 · Wed 2 Dec 2026 · Personal finance foundations
- Read: Varsity Personal Finance module (the first chapters) and the IndiaInvestments wiki on emergency funds, index funds and SIPs.
- Practice: write your own money rules: emergency fund size, the percentage that goes to index funds, the percentage you allow for active trading or crypto, and when you'll rebalance. You'll refine this at I27.
- Look up the current equity tax rules (STCG, LTCG, and the exemption limit) in Varsity's Markets and Taxation module, since these change with budgets.

#### I04 · Sat 5 Dec 2026 · Market psychology and history
- Read: one Howard Marks memo (start with "The Most Important Thing" or any memo about risk) and the 2008 Berkshire letter (written during the crisis).
- Read: Morgan Housel's original "The Psychology of Money" essay on the Collab Fund blog.
- Practice: list 3 biases you've personally fallen for (FOMO, anchoring, loss aversion and so on) and one rule each to prevent them. Add the rules to your journal header.

#### I05 · Wed 9 Dec 2026 · US markets and investing abroad from India
- Watch: Damodaran Foundations of Finance Online, the first 3 to 4 sessions.
- Learn: NYSE vs Nasdaq, ETFs vs mutual funds, how indices like the S&P 500 are built, and how Indians invest abroad (the LRS route through platforms, or Indian international funds). Note the tax and currency differences.
- Practice: in Python, compare the 10-year return of Nifty 50, the S&P 500 in USD, and the S&P 500 in INR (multiply by USD/INR). Plot all three. The INR line shows how much the currency adds.

#### I06 · Sat 12 Dec 2026 · CHECKPOINT 1: Your market map and investment policy draft
Deliverable `reports/cp1_market_map.md`:
1. Your plumbing diagram from I01.
2. The IPO analysis from I02, plus how it actually listed.
3. Your money rules from I03 (version 1).
4. The Nifty vs S&P (INR and USD) chart from I05 and three things you learned from it.

Report back: your money rules and the IPO result.

### Block B · Technical analysis, then testing it

#### I07 · Wed 16 Dec 2026 · Charts and candles
- Read: Varsity Technical Analysis chapters 1 to 4 (background, introducing TA, chart types, getting started with candlesticks). Watch the matching Varsity videos.
- Practice: set up TradingView with Nifty 50 daily, Bank Nifty and 3 stocks you know. In Python, draw a candlestick chart with `mplfinance` for one stock, with volume.

#### I08 · Sat 19 Dec 2026 · Single candlestick patterns
- Read: Varsity TA chapters 5 to 7 (Marubozu, Doji, Spinning Tops, Hammer, Hanging Man, Shooting Star) and ChartSchool "Introduction to Candlesticks".
- Practice: find 2 real examples of each pattern on Nifty charts from the last year and screenshot them into your notes.
- Code: a function that flags Doji and Hammer candles from OHLC data using your own rule (for example, body under 10% of range). Overlay the flags on your chart.

#### I09 · Wed 23 Dec 2026 · Multiple candlestick patterns
- Read: Varsity TA chapters 8 to 10 (engulfing, harami, piercing, dark cloud cover, morning and evening star, gaps).
- Code: an engulfing-pattern detector. For every bullish engulfing on 20 Nifty stocks over 10 years, measure the 5-day forward return, and compare it with the average 5-day return on all days. That's your first honest pattern test.

#### I10 · Sat 26 Dec 2026 · Support, resistance, trend lines, volume
- Read: Varsity TA chapter 11 onwards (support and resistance, volume) and ChartSchool "Support and Resistance", "Trend Lines", and "Gaps and Gap Analysis".
- Practice: mark support and resistance by hand on 5 charts before looking at the indicator. Then code a simple version that finds local minima and maxima with `scipy.signal.argrelextrema` and compare it with what you drew.

#### I11 · Wed 30 Dec 2026 · Classic chart patterns
- Read: the ChartSchool chart patterns pages for head and shoulders, double top and bottom, triangles, flags and pennants, wedges, and cup with handle.
- Read: Bulkowski's performance and failure rate ranking pages. Note which patterns he finds work best and how often they fail.
- Practice: find a live example of three of these patterns on current charts. Write down the breakout level, the target he'd measure, and the stop. Check back in two weeks.

#### I12 · Sat 2 Jan 2027 · Indicators
- Read: the Varsity TA chapters on moving averages and indicators (RSI, MACD, Bollinger Bands) and the ChartSchool indicator pages.
- Code: implement SMA, EMA, RSI, MACD, Bollinger Bands and ATR in pandas yourself, without a TA library. Then check your numbers against TradingView for the same stock and dates.

#### I13 · Wed 6 Jan 2027 · Dow theory, Fibonacci, timeframes, and risk
- Read: the remaining Varsity TA chapters (Fibonacci retracements, Dow theory, the final notes) and ChartSchool on multiple timeframe analysis.
- Most important part: position sizing. Learn to risk a fixed 1% of capital per trade, set stops based on ATR, and measure trades in R-multiples. Put these rules in your journal.
- Practice: start paper trading on TradingView with at most 2 trades a week, each logged in your journal with setup, stop and target before entry.

#### I14 · Sat 9 Jan 2027 · CHECKPOINT 2: Do chart patterns actually work?
Deliverable `reports/cp2_pattern_test.ipynb`:
1. Pick two patterns (for example, bullish engulfing and a 52-week-high breakout). Detect them across the Nifty 50 for 10 years.
2. Measure hit rate and average 5, 10 and 20-day forward returns, compared against random entry dates (bootstrap 1,000 random samples).
3. Read Lo, Mamaysky and Wang's introduction and conclusions and compare their findings with yours.
4. Review your first paper trades: win rate, average R, and rule violations.

Report back: pattern returns vs the random baseline, and your paper-trading stats.

### Block C · Fundamental analysis and valuation

#### I15 · Wed 13 Jan 2027 · Reading a business
- Read: Varsity Fundamental Analysis, the first chapters (introduction, mindset of an investor, how to read the annual report).
- Practice: download the latest annual report of one company you understand (say Asian Paints, TCS or HDFC Bank) and read the Chairman's letter and Management Discussion and Analysis. Write down the business model in 5 sentences.

#### I16 · Sat 16 Jan 2027 · The three statements
- Read: Varsity FA chapters on the P&L, balance sheet and cash flow statement.
- Practice: for your company, use Screener.in to pull 10 years of revenue, operating profit, net profit, operating cash flow, debt and equity. Check how closely net profit and operating cash flow track each other.

#### I17 · Wed 20 Jan 2027 · Ratios that matter
- Read: Varsity FA chapters on financial ratios (profitability, leverage, operating, valuation).
- Code: export Screener data to CSV and compute ROE, ROCE, debt-to-equity, operating margin, asset turnover and P/E for your company and 3 peers. Show them in a comparison table and a chart.

#### I18 · Sat 23 Jan 2027 · Valuation I: the big picture
- Watch: Damodaran Valuation Online, the first 4 sessions (approaches to valuation, intrinsic vs relative, discount rates).
- Practice: in one paragraph, write the story of your company: how it grows, what its margins will look like, and what could go wrong. Damodaran's whole approach starts with "story, then numbers".

#### I19 · Wed 27 Jan 2027 · Valuation II: build a DCF
- Watch: Damodaran Valuation Online sessions on cash flows, growth and terminal value.
- Download: his free spreadsheets and his industry data (cost of capital and margins by sector, including India and emerging markets) from his NYU site.
- Practice: build a simple 10-year FCFF DCF in a spreadsheet or Python for your company. Then run a sensitivity table of value vs growth and discount rate.

#### I20 · Sat 30 Jan 2027 · Relative valuation and pricing an IPO
- Watch: the Damodaran Valuation Online sessions on multiples and relative valuation.
- Practice: compare your company's P/E, EV/EBITDA and P/B with 4 peers. Then revisit the IPO from I02 and compare its issue-price multiples with peers'.

#### I21 · Wed 3 Feb 2027 · Investment philosophies
- Watch: the first sessions of Damodaran's Investment Philosophies class (linked from his class list).
- Read: one Howard Marks memo on risk or cycles.
- Practice: write which philosophy fits you (passive index, value, growth, momentum or trading) and why. Be honest about the time you actually have.

#### I22 · Sat 6 Feb 2027 · CHECKPOINT 3: Equity research note
Deliverable `reports/cp3_equity_note.md` (aim for 2 pages):
1. Business story, competitive advantages, and risks.
2. 10-year financial summary and ratios vs peers.
3. DCF value with a sensitivity table, plus a relative valuation.
4. Verdict: buy, hold or avoid at today's price, and what would change your mind.
5. Bonus: a short version of the same for one US company.

Report back: the note itself. I'll review your assumptions.

### Block D · Derivatives, macro, portfolio and real-time practice

#### I23 · Wed 10 Feb 2027 · Futures, and the reality of F&O
- Read: Varsity Futures Trading, the first chapters (forwards, futures, margins, leverage, mark to market).
- Read: SEBI's study of individual traders' losses in equity F&O (published September 2024). It found that around 9 in 10 individual F&O traders lost money over three years. Write down why you think this happens.
- Code: simulate a leveraged futures position on Nifty with daily mark to market and margin calls.

#### I24 · Sat 13 Feb 2027 · Options basics
- Read: Varsity Options Theory, the opening chapters (call and put options, buying vs selling, payoffs, moneyness).
- Code: payoff diagrams in Python for long call, long put, covered call, protective put and a bull call spread. This links to Quant session Q16, where you price these options.

#### I25 · Wed 17 Feb 2027 · Greeks, IV and the option chain
- Read: Varsity Options Theory chapters on delta, gamma, theta, vega and volatility.
- Practice: open the NSE Nifty option chain. Note IV across strikes for the nearest expiry and plot the "smile". Why are out-of-the-money puts usually more expensive in IV terms?

#### I26 · Sat 20 Feb 2027 · Macro and what moves markets
- Read: the latest RBI Monetary Policy Statement (rbi.org.in), focusing on the repo rate decision, the inflation projection and the growth projection.
- Learn: the relationships between interest rates, bond yields, equity valuations, FII and DII flows, and the rupee.
- Practice: plot Nifty against the 10-year G-sec yield and USD/INR over 10 years. Write three observations, keeping in mind that correlation isn't causation.

#### I27 · Wed 24 Feb 2027 · Building a portfolio
- Read: the IndiaInvestments wiki on asset allocation and mutual funds (index vs active, expense ratios, direct vs regular plans), and the Bogleheads wiki on rebalancing.
- Practice: version 2 of your money rules from I03, with target allocations, rebalancing bands, and how much goes to experiments (trading, crypto). Check how much your chosen mutual funds overlap.

#### I28 · Sat 27 Feb 2027 · Costs and taxes, all of them
- Read: Varsity Markets and Taxation module (STT, brokerage, exchange charges, GST, stamp duty, and how trading income is classified).
- Code: a cost calculator. For 100 round-trip intraday trades of ₹50,000 each, how much goes to costs? How much does a strategy need to make just to break even?

#### I29 · Wed 3 Mar 2027 · A real-time practice routine
- Design your weekly routine, aiming for 30 minutes on Sundays:
  1. Market review (index levels, sector moves, macro news)
  2. Watchlist update with 5 to 10 stocks and why each is on it
  3. Screener.in scan for one idea, using your own filter
  4. Paper-trade journal review: rule violations and average R
- Practice: run the routine once today and save the template.

#### I30 · Sat 6 Mar 2027 · CHECKPOINT 4 (capstone): Review and Investment Policy Statement
Deliverable `reports/cp4_ips.md`:
1. Paper-trading review: all trades since I13, with win rate, average R, max drawdown, and your three biggest lessons.
2. Investment Policy Statement: goals, time horizon, allocation, rebalancing, what you'll never do (for example, naked option selling, or trading on tips), and when you'll review the statement.
3. A decision on what to do next: continue discretionary trading, move to systematic trading (Quant track), or stay a long-term investor with a small trading allocation.

Report back: the IPS and your paper-trading stats.

---

## 4. Going deeper after session 30

| Interest | Next step | Free resource |
|---|---|---|
| Charting | Volume profile, market breadth, sector rotation | ChartSchool's market analysis sections; Bulkowski's studies page |
| Fundamentals | Industry deep dives, forensic accounting | Annual reports plus concalls; Damodaran's blog |
| Valuation | Valuing young, loss-making and cyclical firms | The rest of Damodaran's Valuation classes |
| Options | Volatility trading, spreads | All of Varsity's Options and Option Strategies modules; Quant track Q16 and Q17 |
| Systematic | Turn your rules into code | Quant track Block D |

---

## 5. Activity log (send to me at each checkpoint)

| Checkpoint | Date | Key result | What surprised me | Open question |
|---|---|---|---|---|
| CP1 Market map | Sat 12 Dec 2026 | | | |
| CP2 Pattern test | Sat 9 Jan 2027 | | | |
| CP3 Equity note | Sat 6 Feb 2027 | | | |
| CP4 IPS | Sat 6 Mar 2027 | | | |

---

## 6. Full rotation calendar

Codes: Q = Quant (01_quant.md), I = Investing (02_investing.md), C = Crypto (03_crypto.md). Sundays are catch-up days. All 90 sessions finish on Mon 8 Mar 2027. If you miss a day, just do the next session in the rotation; the order matters more than the dates.

| Week of | Mon | Tue | Wed | Thu | Fri | Sat | Sun |
|---|---|---|---|---|---|---|---|
| 23 Nov |  | 24 Q01 | 25 I01 | 26 C01 | 27 Q02 | 28 I02 | 29 catch-up |
| 30 Nov | 30 C02 | 1 Q03 | 2 I03 | 3 C03 | 4 Q04 | 5 I04 | 6 catch-up |
| 7 Dec | 7 C04 | 8 Q05 | 9 I05 | 10 C05 | 11 Q06 | 12 I06 | 13 catch-up |
| 14 Dec | 14 C06 | 15 Q07 | 16 I07 | 17 C07 | 18 Q08 | 19 I08 | 20 catch-up |
| 21 Dec | 21 C08 | 22 Q09 | 23 I09 | 24 C09 | 25 Q10 | 26 I10 | 27 catch-up |
| 28 Dec | 28 C10 | 29 Q11 | 30 I11 | 31 C11 | 1 Q12 | 2 I12 | 3 catch-up |
| 4 Jan | 4 C12 | 5 Q13 | 6 I13 | 7 C13 | 8 Q14 | 9 I14 | 10 catch-up |
| 11 Jan | 11 C14 | 12 Q15 | 13 I15 | 14 C15 | 15 Q16 | 16 I16 | 17 catch-up |
| 18 Jan | 18 C16 | 19 Q17 | 20 I17 | 21 C17 | 22 Q18 | 23 I18 | 24 catch-up |
| 25 Jan | 25 C18 | 26 Q19 | 27 I19 | 28 C19 | 29 Q20 | 30 I20 | 31 catch-up |
| 1 Feb | 1 C20 | 2 Q21 | 3 I21 | 4 C21 | 5 Q22 | 6 I22 | 7 catch-up |
| 8 Feb | 8 C22 | 9 Q23 | 10 I23 | 11 C23 | 12 Q24 | 13 I24 | 14 catch-up |
| 15 Feb | 15 C24 | 16 Q25 | 17 I25 | 18 C25 | 19 Q26 | 20 I26 | 21 catch-up |
| 22 Feb | 22 C26 | 23 Q27 | 24 I27 | 25 C27 | 26 Q28 | 27 I28 | 28 catch-up |
| 1 Mar | 1 C28 | 2 Q29 | 3 I29 | 4 C29 | 5 Q30 | 6 I30 | 7 catch-up |
| 8 Mar | 8 C30 |  |  |  |  |  |  |
