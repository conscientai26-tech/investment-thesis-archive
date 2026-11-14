# Dynamic Portfolio Quality Hurdle
## Relative Admission, Marginal Opportunity Cost, and Rising Standards

**Date:** 14 November 2026  
**Status:** Proposed investment principle (v0.1), not a backtested rule or an executed trade.  
**Related:** [The Architecture of Alpha](./The%20Architecture%20of%20Alpha%20%E2%80%94%20An%20Investment%20Philosophy%20%E2%80%94%202026-11-07.md), [The Root Moat, Reinvestment, and Expectations Engine](./The%20Root%20Moat%20Reinvestment%20and%20Expectations%20Engine%20%E2%80%94%202026-11-07.md), [13 November selectivity shift](./Portfolio%20Rebalance%20-%20Official%20Virtual%20Partial%20Sales%20MU%20NFLX%20PATH%20-%202026-11-13.md).

## Core proposition

> **A stock is sufficiently attractive for my portfolio only if committing capital to it is better supported than the best realistic marginal use of that capital in my *current* portfolio. As the quality of those alternatives improves, the admission hurdle should rise accordingly, but only when the underlying evidence justifies the increase.**

This is not a fixed minimum alpha target, an arbitrary number of holdings, or a desire to select ever more exciting stories. It is a **dynamic, opportunity-cost-based quality floor**. The floor is endogenous to the investable opportunities already available.

The objective is progressive improvement in the **forward-looking quality of capital allocation**, not merely an increasing average of my own optimistic return estimates.

## Three layers of quality

1. **Business quality:** causally identifiable and durable economic advantage; economic profit; reinvestment returns and runway; competitive response; survival of technological architecture changes; quality of capital conversion.
2. **Investment quality at today's price:** implied market expectations; defensible scenario range for total shareholder returns; prospective alpha against the same-period S&P 500 benchmark; downside and valuation error tolerance; independence and strength of evidence; time needed for the expected price/value gap to close.
3. **Portfolio quality:** incremental expected benefit after position sizing, financing alternatives, overlap of causal drivers, common adverse scenarios, concentration, liquidity, turnover and costs. An apparently lower-return security can improve a concentrated portfolio if it brings genuine independent exposure or materially reduces tail risk. A higher-alpha estimate can fail because the estimate is fragile or because the exposure is redundant.

**Company excellence is not identical to investment attractiveness, and neither guarantees a desirable marginal portfolio allocation.**

## Admission rule: absolute floor, relative floor, evidence premium

For each candidate, establish in the following order:

**Gate A — Absolute investability.** There must be a clear, falsifiable economic mechanism, credible advantage and capital-capture path, a defensible interpretation of market expectations, measurable sources, and a plausible margin over a realistic index/cash alternative. The analysis must survive reasonable errors in the major assumptions. A candidate with a merely asserted expected alpha fails this gate regardless of its apparent numerical lead.

**Gate B — Best feasible alternative.** Compare *the next euro* allocated to the candidate with the best feasible next euro allocated to: (i) existing holdings at current prices and target position limits; (ii) an index; (iii) cash; and (iv) other investigated candidates. For a proposed substitution, compare the realistic full portfolio before and after removing or shrinking the marginal incumbent. Compare equal horizons, consistent total returns, and plausible downside cases.

**Gate C — Evidential margin.** Demand a sufficiently convincing incremental advantage after trading costs, taxes where applicable, forecast uncertainty, correlation and common-factor losses. A tiny modeled improvement is not a compelling improvement if it is smaller than the error of the estimates.

A conceptual test is:

**Admit only if** `MarginalPortfolioValue(candidate allocation) > MarginalPortfolioValue(best feasible alternative) + DecisionMargin`.

Here, marginal portfolio value is a qualitative/risk-adjusted decision metric supported by scenarios; it is **not** a precisely observable scalar, and the decision margin must be justified rather than invented. If the probability distribution is not defensible, use scenarios, break-even thresholds, and explicit conditions for outperforming.

## The rising-hurdle mechanism

1. **Measure the current frontier.** Re-estimate *remaining* prospective upside, robustness and downside of existing positions from their **current** prices, not entry prices or historical gains.
2. **Locate the marginal slot.** Identify the weakest *marginal use of capital*, rather than mechanically selling the stock with the lowest expected raw alpha. Position limits and portfolio complementarities matter.
3. **Challenge it.** The new stock needs a credible and material incremental improvement, not just positive standalone alpha.
4. **Replace or abstain.** If it passes the gates, add/replace/reweight; if not, remain in current holdings or cash.
5. **Recalculate the floor.** After genuine improvement, the next candidate faces a stronger incumbent opportunity set. Over time, weaker ideas are systematically squeezed out.

**Non-monotonic exception:** the hurdle must not *automatically* increase with calendar time, research volume, or past stock performance. When prices rise faster than fundamentals, existing holdings become less attractive and the real floor may fall. A high estimate can likewise decline after thesis deterioration. The ratchet applies only to **substantiated forward quality**, not narrative confidence.

## Worked example (entirely hypothetical, not current portfolio estimates)

Assume three existing positions have *illustrative* annualized expected benchmark-relative returns of **5, 7 and 9 percentage points**, on comparable horizons and with similar evidential reliability.

- A new candidate at **4 pp** does not automatically qualify; it could nevertheless improve the portfolio if it substantially offsets a shared downside that the current positions have.
- A new candidate at **6 pp** does not replace a **7 pp** incumbent solely because it is new or diversifies nominal sectors. It might improve the marginal **5 pp** allocation if its downside and evidence are at least comparable.
- A new candidate at **8 pp** could displace the **5 pp** position if the proposed trade survives portfolio-level stress tests, uncertainty and costs.
- After a successful replacement, the frontier strengthens. The next stock must earn its place against the *updated* opportunity set; **8 pp is not a permanent entry threshold**.

Expected alpha is not known: every point estimate above is an analytical illustration, not a verified or precise forecast.

## Research worksheet for every candidate

| Question | Required output |
| --- | --- |
| What will happen? | Technological/economic change and causal transmission path |
| Why this business? | Root moat, value capture, reinvestment runway, best competitor/bypass case |
| What is the market pricing? | Reverse-implied expectations; valuation and market-price timestamp |
| How much might shareholders earn? | Coherent bear/base/bull total-return scenarios and break-even conditions |
| Relative to what? | Same-period index, cash, next-best current holding, and competing candidate |
| What must be true? | 3–5 leading indicators, evidence grade, failure conditions |
| What can go wrong jointly? | Portfolio factor exposure, common downside, liquidity and concentration |
| What would make this a genuinely better allocation? | Marginal portfolio delta, required margin, decision and position size |
| What would reverse the decision? | Explicit monitoring checkpoints and revision triggers |

Record the decision-time values, alternative foregone, source dates, and rejected candidates. Revisit them without inserting future knowledge into the original judgment.

## What to test empirically

Test, on held-out periods when feasible, whether raising the relative admission hurdle adds risk-adjusted benchmark outperformance after turnover costs, compared with: (i) an index; (ii) a fixed absolute-alpha gate; (iii) a simpler next-best-position rule; and (iv) the original broader portfolio. Track the frequency of false rejections, overestimated conviction, sector concentration, and opportunity costs of waiting. Additional selectivity is not evidence of skill unless the decision record improves.

## Compressed rule

**No new holding merely because it is good. A new holding must improve the best attainable marginal portfolio allocation at today's price, with evidence strong enough to survive realistic uncertainty. The portfolio sets the hurdle; genuinely better holdings can raise it; weaker holdings or higher prices can lower it.**
