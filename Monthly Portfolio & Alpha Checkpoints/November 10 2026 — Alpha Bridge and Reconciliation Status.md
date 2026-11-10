# November 10, 2026 — Transparent Alpha Bridge: +14.82 pp to ~+17.1 pp (Provisional Scenario)

**Prepared:** November 10, 2026 (Europe/Berlin).  
**Status:** NEW, contemporaneous reconciliation note; **not** an amendment to earlier frozen checkpoints.  
**Portfolio:** Virtual / paper research account. **No audited broker executions, no live-money track record.**  
**Benchmark:** S&P 500 price index; comparisons are not a finalized S&P 500 total-return or time-weighted portfolio audit.

## Executive summary — the exact status of the headline

- **Last committed cumulative model checkpoint: +14.8202 percentage points, dated November 5, 2026.** This figure is documented with its assumptions in the [original November 5 checkpoint](./November%202026%20%E2%80%94%20Interim%20Portfolio%20%26%20Alpha%20Checkpoint%20%E2%80%94%202026-11-05.md).
- **Latest owner/ChatGPT reported scenario: approximately +17.10 pp on November 10.** This was derived by adding a November 6 model adjustment, a November 9 estimated daily stock-basket advantage and a November 10 Tokyo Ohka illustration. It is **not** an independently validated new cumulative alpha figure.
- Using the *actual* November 9 S&P 500 closing return of **+2.3463%**, instead of the rounded **+2.30%** used in the earlier chat, the **same illustrative arithmetic becomes approximately +17.06 pp**, without correcting execution assumptions.
- A reasonable alternative that uses November 10's regular-session opening as the *first regular-session executable reference* for the late-November-9 Tokyo Ohka decision gives an illustrative result near **+16.02 pp**, before other corrections. **Neither scenario is a verified all-position portfolio return.**
- The investor-facing explanation must disclose both the **real, sharp stock-market moves** and the **model/timing assumptions**. An investor must not be led to interpret the +17 pp model as broker-verified realised alpha.

## 1. Frozen inputs and source chronology

| Date / event | Observed or recorded fact | Quality |
|---|---|---|
| Nov 5 US market close | Documented cumulative model alpha **+14.8202 pp**. The nominal-weighted 16-stock basket fell **1.0313%** vs S&P 500 **-4.36%**, giving **+3.3287 pp relative for that day**. | Public dated GitHub model; cumulative component is not fully ledger-reconciled |
| Nov 5 APP move | APP rose **31.02%** in the model; its weighted alpha contribution for the day was **+2.6632 pp** out of the +3.3287 pp. | Recorded market-price comparison; not verified execution P&L |
| Nov 6 | A **-0.17 pp** adjustment appeared in the subsequent ChatGPT bridge. | Chat-derived correction; full position-level ledger reconciliation still missing |
| Nov 9 US session | Revised nominal-weighted stock-basket estimate **+3.31%**, after an Ambiq assumption was changed to +20%. | Chat-derived, not a synchronized audited close snapshot |
| Nov 9 S&P 500 | Index close **7,549.94** vs **7,376.86** on Nov 6 = **+2.3462557%**, rather than precisely +2.30%. | Independently checkable price index close |
| Nov 9 Tokyo | Tokyo Ohka finished at **JPY 6,687**, up **4.42%** from the previous close of JPY 6,404. There was an earlier virtual full exit and a distinct, **late-evening** virtual **$17,000 re-entry decision**. | Dated market close and separate GitHub decisions. No executable re-entry fill proven |
| Nov 10 at 07:00 CET | Owner officially recorded **selling $10,000 of the newly re-entered Tokyo Ohka allocation**, with a **reported +12% gain**, and retaining $7,000 nominal capital. | Virtual portfolio-owner instruction; +12% is owner-reported, not broker-verified |
| Nov 10 Tokyo market | Quoted **JPY 7,532** intraday (approx. +12.64% over JPY 6,687); the reported regular close was **JPY 7,350**, approx. **+9.91%** from prior close. Regular-session open **JPY 7,212**. | External market quotes from different timestamps, not an execution print at precisely 07:00 CET |

### Links to prior decisions

- [November 5 portfolio model checkpoint](./November%202026%20%E2%80%94%20Interim%20Portfolio%20%26%20Alpha%20Checkpoint%20%E2%80%94%202026-11-05.md)
- [Tokyo Ohka full exit November 9](../Tokyo%20Ohka%20Kogyo%20(4186)%20%E2%80%94%20Full%20Position%20Exit%20Decision%20%E2%80%94%202026-11-09.md)
- [Tokyo Ohka $17,000 late-evening re-entry November 9](../Tokyo%20Ohka%20Kogyo%20(4186)%20%E2%80%94%20Confirmed%20USD%2017000%20Virtual%20Re-entry%20Before%20Q3%20%E2%80%94%202026-11-09.md)
- [Tokyo Ohka November 10 $10,000 partial sale at user-reported +12%](../Tokyo%20Ohka%20Kogyo%20(4186)%20%E2%80%94%20Official%20USD%2010000%20Partial%20Sale%20at%2012%20Percent%20Gain%20%E2%80%94%202026-11-10.md)

### Independent market-price references

- [Yahoo Finance: S&P 500 history](https://finance.yahoo.com/quote/%5EGSPC/history/) — 2026-11-06 **7,376.86**, 2026-11-09 **7,549.94**.
- [MarketScreener: Tokyo Ohka quotes](https://ca.marketscreener.com/quote/stock/TOKYO-OHKA-KOGYO-CO-LTD-6492211/quotes/) — JPY 6,687 prior close; JPY 7,212 next opening; an intraday quote of JPY 7,532. Exact timestamps vary.
- [Investing.com Japan: Tokyo Ohka historical prices](https://jp.investing.com/equities/tokyo-ohka-kogyo-historical-data) — November 10 regular-session reported close JPY 7,350, opening JPY 7,212.
- [Tokyo Ohka official IR calendar](https://www.tok.co.jp/eng/ir/calender) — November 10 quarterly report announcement.

## 2. Reproduce the previously quoted +17.10 pp

These values explain the *specific conversation calculation*, **not a validated time-weighted alpha history**.

| Step | Illustrative delta | Running reported model |
|---|---:|---:|
| Nov 5 checkpoint | — | **+14.82 pp** |
| Nov 6 intermediate model adjustment | -0.17 pp | +14.65 pp |
| Nov 9 portfolio +3.31% less *rounded* S&P +2.30% | +1.01 pp | +15.66 pp |
| Nov 10 Tokyo: $10,000 at reported +12% = $1,200; $7,000 at assumed +12.3% = $861; $2,061 / $142,848 | +1.4428 pp | **+17.10 pp** (rounded) |

Formula:

`14.82 - 0.17 + (3.31 - 2.30) + (1200 + 861)/142848*100 = 17.1028 pp`.

**Important:** The $1,200 and $861 have been interpreted as returns on the **new, separately documented November 9 re-entry**, not as an additional re-counting of the *old* position closed earlier November 9. This distinction mitigates one double-counting concern, but actual entry pricing is unresolved.

**Precision correction:** Use the November 9 index return actually implied by the two closes:

`(7549.94 / 7376.86 - 1) * 100 = +2.3462557%`.

Hence the November 9 model advantage is `3.31 - 2.3462557 = +0.9637443 pp`, not +1.01 pp. Without any other changes:

`14.8202 - 0.17 + 0.9637443 + 1.4427923 = **+17.0567 pp**`.

Even **+17.06 pp** here is a *conditional reconstructed scenario*, not a validated updated alpha figure.

## 3. Why the apparently rapid rise is economically intelligible

The jump is not a claim of magically steady 15-17 pp annualized alpha. It mainly reflects **event-driven concentration over a few sessions**:

1. **November 5 — benchmark divergence in a severe down day.** The S&P 500 fell 4.36%, while the modeled equity basket lost 1.03%. This difference alone generated +3.33 pp *daily relative basket performance*. AppLovin's approximately +31% move contributed about +2.66 pp of the relative difference, despite its allocation being only ~7.53% of the model capital.
2. **November 9 — broad market rebound with a slightly stronger stock basket.** The S&P 500 rose 2.346%; the chat-modeled stock basket rose ~3.31%, creating ~+0.96 pp additional *estimated relative performance*. The basket estimate includes partly nonsynchronized observations and the earlier Tokyo position's intraday sale, so it needs a final trade-level verification.
3. **November 10 — concentrated Tokyo Ohka earnings-related volatility.** A large ~$17,000 virtual allocation is roughly 11.9% of the modeled $142,848 reference capital. A 12% change on that amount would mechanically equal ~$2,040 or **~1.43 percentage points of modeled portfolio return** in a single session. That is a mathematical explanation of speed, **not** proof that the full rise was captured at executable prices.
4. **Relative alpha can grow sharply on declining markets** even if the portfolio itself is flat or down. Both the relative benchmark move and the chosen denominator matter.

In brief: unusual relative performance over these particular days is not numerically impossible. The unresolved question is *how much of it can be attributed to correctly timestamped and feasibly executable virtual decisions*.

## 4. Critical execution sensitivity: November 9 re-entry was after Tokyo closed

This is the most material missing verification.

The new **$17,000 Tokyo Ohka buy was confirmed late in the evening in Germany on November 9**, when the Tokyo exchange was **closed**. Its GitHub record explicitly acknowledges **no executable purchase price, share quantity or FX conversion**. An investor should not presume the November 9 Tokyo close of JPY 6,687 was an executable purchase price for this later decision.

The **next regular session opened at JPY 7,212 on November 10**, an indicative overnight gap of **+7.85%** relative to JPY 6,687. A same-day quote of JPY 7,532 corresponds to only **+4.44% from that opening**, not +12% from the prior close. The reported Tokyo session close of JPY 7,350 is **+1.91% from that opening**, not +9.91% from the prior close.

A transparent *alternative scenario*, solely to measure the importance of the executable-price assumption:

| Assumption | Model USD contribution |
|---|---:|
| $10,000 cost tranche; sold at illustrative JPY 7,532 vs assumed JPY 7,212 buy | approximately **+$444** |
| $7,000 cost tranche; marked at JPY 7,350 vs assumed JPY 7,212 buy | approximately **+$134** |
| **Total alternative Tokyo contribution** | **approximately +$578** |
| Relative to $142,848 reference capital | **approximately +0.405 pp** |

`14.8202 - 0.17 + 0.9637443 + 0.405 = approximately **+16.02 pp**`, **before** synchronizing the remaining holdings and the November 10 S&P benchmark.

This is **not** a verified return either: it uses the opening price as an execution *proxy*, an independently observed intraday quote *near* the sale time, a Japanese closing mark on the residual $7,000 allocation, assumes frictionless execution and ignores FX. No specific first-session trade or fill has been independently established. It is provided because a credible investor should be able to see the return's sensitivity to entry assumptions, not just the most favorable version.

**Other timing issue:** The November 10 Tokyo trading session was completed before the US November 10 cash market opened. Comparing a Tokyo intraday result with the **November 9** S&P close without specifying the as-of timing does not create a synchronized November 10 daily alpha measurement.

## 5. Methodological status, verification requirements

- **Frozen documented model:** +14.8202 pp on November 5.
- **Later reported ChatGPT bridge:** +17.10 pp (rounded) on November 10; a reconstructed, owner-reported model path.
- **Exact-benchmark version of the same illustrative assumptions:** +17.06 pp.
- **Illustrative next-session-entry sensitivity:** approximately +16.02 pp before other corrections.
- **Validated cumulative portfolio alpha as of November 10:** **not yet established**.
- **October 27 separate capital-time-normalized lot audit:** +5.69 pp under conservative entry prices and +7.94 pp under archive-reference prices; do not add these figures to November results or portray them as the same measure.

To certify the next cumulative figure, first reconstruct all chronological entries, exits, cash and simulated fills at the time *actually available* (especially Tokyo Ohka November 9/10, and November 4/5 rebalance), mark the remaining $7,000 Tokyo exposure at a precise date/time, use USD/JPY conversions, include the other stocks' synchronized marks, compare to an equivalently timed S&P portfolio with cash treatment, check overlapping market and after-hours returns, and compute a standard time-weighted and total-return benchmark comparison.

**Investor-facing wording until then:**

> My latest publicly documented portfolio model checkpoint, dated November 5, reported +14.82 percentage points of cumulative alpha versus the S&P 500. Subsequent market moves led to a provisional, conversation-based estimate around +17 percentage points by November 10. Because the key Tokyo Ohka re-entry was recorded after the previous trading session closed and exact executable reference prices remain unresolved, that later figure is a scenario rather than verified performance. I have published the full numerical bridge, the underlying dated decisions and a sensitivity analysis, rather than silently replacing the earlier checkpoint.

This disclosure is deliberately explicit. It permits investors to investigate an apparently rapid change instead of relying on an unsupported headline.
