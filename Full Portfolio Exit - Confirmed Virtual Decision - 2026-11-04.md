# Portfolio Risk Reduction — 15 initially sold, APP subsequently repurchased, Tokyo Ohka retained — November 4, 2026

Decision date: November 4, 2026
Decision time: Approximately 17:35 CET (Europe/Berlin). This is the time the decision was documented, not a verified trade execution time.
Action: November 4 approximately 17:35 CET: originally documented 16-position full exit; corrected shortly thereafter to 15 sold, with Tokyo Ohka retained. AppLovin was included in the original sale record. The owner later reports repurchasing APP shortly after 22:00 CET, before the Q3 release; the repurchase was not recorded on GitHub until 22:16:09 CET.
Status: CONFIRMED
Portfolio: Virtual investment portfolio
Scope: After the earlier sale and the owner-reported same-evening APP repurchase, 14 holdings remained sold, with APP and Tokyo Ohka held at the end of November 4. This final status must not be misread as proof APP was never sold.

## Decision

This record initially documented a virtual sale of all 16 positions at approximately 17:35 CET. A correction at 17:37 CET excluded Tokyo Ohka, leaving 15 virtual sales including AppLovin. The owner subsequently reports purchasing APP again shortly after 22:00 CET, before the company's Q3 results release. The GitHub correction at 22:16 CET instead presented APP as continuously held, an inaccurate transaction chronology according to the owner's later account. The final November 4 balance is 14 positions sold, plus APP (reopened) and Tokyo Ohka (retained). The specific APP repurchase minute and executable price have not been independently established.

I am choosing to remove near-term equity exposure because I believe the downside risk has become less attractive relative to the additional return I might earn by remaining fully invested. The decision is based on portfolio-level risk, not on an attempt to identify the exact intraday high.

## Positions covered

The table lists the November 4 sale sequence around 17:35 CET, after the Tokyo Ohka correction. The separately reported APP repurchase shortly after 22:00 CET is reflected in the chronology below.

| Company | Ticker | Action |
| --- | --- | --- |
| Alphabet | GOOGL | Sell entire position |
| Microsoft | MSFT | Sell entire position |
| Meta Platforms | META | Sell entire position |
| Salesforce | CRM | Sell entire position |
| Amazon | AMZN | Sell entire position |
| SAP | SAP | Sell entire position |
| Wolters Kluwer | WKL | Sell entire position |
| Ambiq | AMBQ | Sell entire position |
| Synopsys | SNPS | Sell entire position |
| Netflix | NFLX | Sell entire position |
| UiPath | PATH | Sell entire position |
| Pegasystems | PEGA | Sell entire position |
| Mastercard | MA | Sell entire position |
| Micron Technology | MU | Sell entire position |
| AppLovin | APP | Sold in the original virtual exit record; owner reports repurchase shortly after 22:00 CET (exact minute not independently verified) |
| Tokyo Ohka Kogyo | 4186.T | HOLD entire position. Do not sell. |

Tokyo Ohka Kogyo was excluded from the sale after the 17:37 CET correction and stayed invested. AppLovin was in the sale list and, according to the owner's later clarification, was repurchased later that evening. These were distinct actions.

## Rationale

The broad US equity rally on November 4 followed a sharp correction and an unusually rapid reassessment of the US midterm election results. Part of the rebound can be explained by reduced political uncertainty, lower oil prices, and strong earnings from several large technology companies. But the scale and speed of the move also leave room for temporary positioning effects, including investors restoring exposure after the election and covering defensive trades. I cannot establish how much of today's buying came from short covering, and I am not treating a short squeeze as a proven cause.

The underlying macro risks have not disappeared. A renewed military escalation involving Iran could raise energy prices, inflation expectations, and bond yields. Higher discount rates and a renewed risk premium would matter particularly for growth and technology stocks.

My holdings are spread across multiple companies, but a large share of the portfolio remains exposed to common factors: technology valuations, AI capital expenditure, cloud demand, software spending, and institutional appetite for growth stocks. The number of holdings therefore overstates the degree of effective diversification during a correlated selloff.

Several of these businesses still have strong fundamentals. These sales are not a claim that their long-term investment theses have failed. It is a decision to reduce aggregate risk at a point when the expected additional return from staying fully exposed does not, in my judgment, justify the potential drawdown.

The portfolio has accumulated substantial estimated outperformance relative to the S&P 500. The recent figure discussed was approximately 10 to 11 percentage points, but that estimate has unresolved data and methodology limitations. Relative outperformance is not the same as a realized cash gain. I am not using that figure as a verified sale profit.

I accept that prices may continue to rise after this decision, including in the positions I am selling. The purpose of the reduction is to limit exposure to an unfavorable range of outcomes, not to make a precise short-term market prediction. Any later re-entry will require a new assessment of valuation, fundamental developments, correlated risk, and the expected return relative to remaining in cash.

**Central evidence ledger:** [November 3–5 APP and Midterm audit](./November%203-5%202026%20%E2%80%94%20AppLovin%20and%20Midterm%20Event%20Audit%20Ledger.md). An earlier ChatGPT exchange dated **November 4, 17:37:04 CET** discussed when to repurchase APP before earnings. The assistant's reply did **not** confirm a repurchase and instead treated it as pending; this is not a confirmed pre-earnings instruction or execution. No verified 21:00 CET portfolio-system modification has been identified. The app's Q3 earnings release was distributed at **22:05 CET** according to contemporaneous reporting. See ledger for public commits, original-chat versus later-report evidence classifications.

## Portfolio record, amendments, and execution limits

**Original GitHub evidence and corrected chronology (Europe/Berlin, CET):**

1. **November 4, 17:35:46:** original GitHub commit `b2f2d3f0c55154a906bd43bc3f0eec001701115a` entered a confirmed virtual exit from all 16 holdings, including APP and Tokyo Ohka.
2. **November 4, 17:37:50:** commit `c9f09bd20ef34c03801ffa352e1a18694af30c68` removed Tokyo Ohka from the sale, leaving **15 sales including APP**.
3. **November 4, shortly after 22:00 (owner-reported):** APP was repurchased ahead of the Q3 earnings release. **The precise minute, price, and contemporaneous proof of this repurchase remain unverified.** This is a historical decision claim, not the time of a GitHub publication.
4. **November 4, 22:16:09:** commit `257ac8abc2a6d25372bcfc677f00c7b580d588db` removed APP from the sale list and described APP as retained continuously. That recorded **the final holding status** but, according to the owner's later account, **not the true sequence of sale followed by repurchase**. This correction explicitly supersedes that description without changing the earlier commit.
5. **November 5:** 14 other positions were reopened in the virtual portfolio. APP had already been reopened the prior evening; Tokyo Ohka was held throughout.

**End-of-day November 4 virtual holdings:** APP and Tokyo Ohka only; 14 positions still marked sold. The initial 15-sale step and subsequent APP repurchase must be retained in any transaction-level performance or benchmark calculation. A continuously-held APP assumption would be incorrect if the owner-reported trade sequence is corroborated.

**Evidence limits:** This archive records virtual decisions, not actual broker orders. No verified fill time, APP repurchase price, share count, cash proceeds, real account execution, or independently established timestamp proving that the APP repurchase preceded the earnings release has been provided. Historical GitHub committer timestamps remain unchanged; a later text amendment does not backdate publication.

The November 3 simulated liquidation and November 4 04:30 simulated re-entry are separate hypothetical scenarios, **not** actual executions of this confirmed November 4 portfolio sale.

Reference records:
- Simulated portfolio liquidation on November 3, 2026.
- Simulated repurchase on November 4, 2026 at 04:30 CET.
- Portfolio return and alpha checkpoint dated November 4, 2026.
