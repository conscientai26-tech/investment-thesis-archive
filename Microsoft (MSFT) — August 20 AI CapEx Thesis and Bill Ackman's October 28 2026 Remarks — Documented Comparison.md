# I wrote down the AI CapEx argument in August. Bill Ackman made the same case for Microsoft publicly in October.

**A dated comparison of independent investment reasoning**  
**Original thesis:** August 20, 2026  
**Bill Ackman interview published:** October 28, 2026  
**This retrospective:** October 29, 2026

On October 28, 2026, Norges Bank Investment Management released an episode of *In Good Company* featuring Bill Ackman. At approximately 14:18, he explained why Pershing Square had bought Microsoft after its share price came under pressure. Management was telling investors that demand was so substantial that the company needed to spend more on capital investment than previously expected. Investors marked down the shares anyway. Ackman saw a buying opportunity.

That argument sounded familiar to me because I had written it down more than two months earlier.

On **August 20, 2026**, I recorded a broader investment framework, *Investing Through the AI Transition*, in Notion and in this GitHub repository. It was not a commentary on Ackman, nor an attempt to predict his eventual positions. It was my own attempt to distinguish economically productive capital expenditure from the kind of spending that merely absorbs cash without creating sufficient future value. My analysis specifically addressed the possibility that investors would mistake demand-driven capacity expansion for deteriorating economics.

The resemblance is not just that both arguments are favourable to AI investment. It concerns the same causal interpretation of an apparently negative fact: **a company spends more, its reported free cash flow is pressured, and its stock falls—despite the expenditure being a response to demand the company already has.**

I am documenting the chronology because the ability to identify that mechanism before seeing it articulated by a prominent investor may say something about the quality of my analytical process. Whether it eventually produces superior investment returns is a separate question.

## The contemporary record, not a reconstructed memory

The most important evidence is an August 20 GitHub commit, not the date printed at the top of this retrospective.

- **Notion original:** [*Investing Through the AI Transition*](https://app.notion.com/p/3cc67b6787f8819c9f4ddad2d2c98cb4). The text itself is dated **2026-08-20**. The retrieved Notion page metadata reports a **last-edited timestamp of 2026-08-30 14:31:15 UTC**.
- **Historical GitHub commit:** [0ae0cdee18f76e9d77a7b5f333d0589472dc8191](https://github.com/conscientai26-tech/investment-thesis-archive/commit/0ae0cdee18f76e9d77a7b5f333d0589472dc8191), with the recorded commit time **2026-08-20 20:27:42 UTC**. Its diff adds the original essay, including the passages cited below.
- **Frozen historical text:** [The August 20 file at that specific commit, lines 27–43](https://github.com/conscientai26-tech/investment-thesis-archive/blob/0ae0cdee18f76e9d77a7b5f333d0589472dc8191/AI-Era%20Investment%20Development/Investing%20Through%20the%20AI%20Transition%20%E2%80%94%202026-08-20.md#L27-L43). This link points to the historical Git object rather than a mutable version on the main branch.
- **Ackman's later public statement:** [Norges Bank Investment Management's official episode page](https://www.nbim.no/en/news-and-insights/podcast/2026/bill-ackman-concentrated-investing-permanent-capital-and-the-value-of-being-challenged/); [episode listing confirming October 28](https://shows.acast.com/in-good-company-with-nicolai-tangen/episodes/bill-ackman-concentrated-investing-permanent-capital-and-the); [speaker-attributed transcript, approximately 14:18](https://ceointerviews.ai/interview/3147822/).

This matters for a simple reason. The August argument is visible in an older version of the work. I am not taking an October interview and retrospectively attributing its logic to an undated private recollection. The original essay exists, and the commit and source note make the chronology inspectable.

**Evidence standard:** the Notion text's internal date, Notion's last-edited metadata, and GitHub's recorded commit timestamp are distinct forms of dating. The GitHub commit shows the exact earlier text and is stronger than merely assigning a past date to a newly written page. Git commit timestamps are still metadata rather than independent proof of the exact time an idea first occurred; an external server-receipt record or independently archived snapshot would strengthen that narrow point further. The claim made here is the documented order of the available records and the public interview, not an impossible claim about what Ackman privately thought before speaking.

## What I actually wrote on August 20

I wrote:

> This leads to another principle: corporate actions can contain information about the future before that future appears in reported revenue. A company that aggressively expands capacity may either be irrationally overinvesting or it may be seeing demand that is not yet fully visible from the outside.

And in the same paragraph:

> If that chain is plausible and demand already exists, a large investment program may be the opposite of waste. It may be the cost of removing an existing bottleneck.

The next paragraph gave the decision rule more directly:

> If a company lacks capacity while demand already exists, additional CapEx can unlock revenue. That is fundamentally different from a company building capacity first and then hoping customers arrive.

Later in the document I described the valuation discrepancy almost exactly in the terms Ackman would use:

> One investor sees high investment and thinks lower free cash flow. Another sees the same investment, combines it with capacity constraints, backlog, and demand, and interprets it as the prerequisite for future growth.

These are quotations from the actual **August 20 version** of the essay, accessible at the commit permalink above, not paraphrases rewritten after the interview.

The analysis also identified the uncertainty that keeps the market from automatically rewarding that expenditure: investors may doubt that AI capital investment will earn an adequate return. The thesis only becomes actionable when the investor can explain why the cash-flow consequences of the expansion are more favourable than the price already assumes.

## What Ackman said on October 28

During the interview with Nicolai Tangen, Ackman discussed several recent purchases. He said Pershing Square had acquired Meta after investors reacted negatively to its commitment to heavy capital spending, and that the firm had made a similar investment in Microsoft.

His description of Microsoft centred on the company effectively telling shareholders that it had **"enormous demand for our service"** and then observing that **"the stock price goes down."**

That was his explanation for why the selloff led Pershing Square to invest in Microsoft. His point, as I understand it, is not that spending is automatically good; it is that the market's immediate reaction to a higher capital budget can overlook the reason the budget was raised.

I made the same distinction in August, before this interview was published. Ackman's statement is particularly close to my August formulation because both focus on *demand already being present*, *capacity being the constraint*, and *investors possibly treating the cost of removing that constraint as evidence against the business*.

One qualification is important for accuracy: Ackman said Amazon was purchased after the tariff announcement, whereas he tied the Meta and Microsoft purchases to reactions to capital spending. The closest comparison here is therefore **Microsoft**, with Meta supporting the broader pattern. I am not claiming his Amazon purchase was based on the same CapEx rationale.

## The economic mechanism I had in mind

The underlying question was never whether a larger capital budget is intrinsically positive. Consider two superficially similar companies.

Company A has spare computing capacity and little evidence that additional customers are coming. It builds expensive new infrastructure in the expectation that demand will eventually materialise.

Company B is already declining or delaying potential workloads because it cannot deliver enough computing capacity. Its existing customers want more. Orders, usage or backlog indicate demand beyond currently available supply. It builds because otherwise it leaves monetisable demand unserved.

Both companies may report the same increase in CapEx. Both may show a lower near-term free-cash-flow figure. But the information contained in the spending decisions is radically different.

For Company B, the relevant mechanism is:

**Existing demand exceeds deliverable capacity → management invests → new capacity becomes operational → customers consume it → revenue and contribution profit increase → the investment may earn an attractive return.**

The market sees an immediate cash outflow and, as the assets enter service, additional depreciation. The possible economic benefit is later and uncertain. That time mismatch can create a valuation gap, especially if investors interpret the increase in spending without adequately distinguishing whether it represents a speculative buildout or the removal of a binding constraint.

This is a hypothesis about the economics of the *marginal dollar*, not about how impressive the infrastructure looks. In a simplified project-level formulation:

**NPV of expansion = present value of incremental after-tax operating cash flows − required incremental investment.**

For a shareholder, the calculation must also take account of the financing structure, future reinvestment, dilution, competitive response, and whether those expected returns are already included in the share price.

The term **capacity constrained** matters because it changes what must be forecast. With speculative capacity, I first have to forecast demand creation. With constrained capacity, there may already be evidence of demand; the remaining forecasts concern how quickly capacity comes online, whether demand persists, the margin earned on additional revenue, and the cost of meeting it.

That difference is economic, not semantic. It is also why backlog alone is insufficient: contracts can change, the backlog can be concentrated, and infrastructure can become obsolete before generating satisfactory returns. Yet with visible customer demand and a binding supply constraint, an incremental expansion may have a substantially different risk profile from an equally expensive bet without such evidence.

## The other notes that show how the argument developed

The August 20 essay was the starting point, not the full extent of the research.

**August 29 — Microsoft explicitly named in the capital-investment analysis.**  
My [*Amazon Analyse* research note](https://app.notion.com/p/3cb67b6787f8817d997ed8ca0901f292) was retrieved with a Notion last-edited timestamp of **2026-08-29 21:58:06 UTC**. Although Amazon was the main case, it included a specific section titled **"Microsoft könnte ein Kandidat für adaptive Investition sein"** (Microsoft could be a candidate for adaptive investment). I considered whether Microsoft's investment process might be better described as *Observe → Build → Observe → Build*, while explicitly leaving that hypothesis subject to empirical testing.

The following section was titled **"Der Markt sieht Kosten früher als Nutzen"** (the market sees costs before benefits). I wrote that CapEx immediately creates cash outflow, depreciation follows, and returns may take years to arrive. The note summarised the possible mispricing as **Market Discount > Actual Economic Risk**. This is a more Microsoft-specific antecedent to the October comparison, although the Notion page's retrieved last-edit metadata is not a version-by-version audit of each sentence.

**August 30 — a separate explanation of why the market and management might disagree.**  
My [*AI-CapEx: Perspektivenfehler, Optionalität und Bottlenecks*](https://app.notion.com/p/3cc67b6787f881099026d344b518e272) note, with retrieved last-edited metadata of **2026-08-30 14:28:34 UTC**, named Amazon, Microsoft, Alphabet and Meta. It examined physical scarcity, investment optionality, ecosystem effects, the management's actual objective, and CapEx as a signal of revealed corporate expectations. I did not assume every aggressive investment was rational; I tried to identify the assumptions under which it would be rational.

**September 3 — a framework for measuring whether the thesis is right.**  
In [*Capital Conversion Framework — Kapital, Information, Cashflow & Valuation*](https://app.notion.com/p/3cf67b6787f881698477f16f598f7cd1), retrieved with last-edited metadata **2026-09-03 12:39:49 UTC**, I distinguished capital already earning money from capital at risk and the future capital still required. I specified demand visibility, utilisation, incremental cash-flow conversion, marginal returns, and valuation as separate tests. A company can be right about AI adoption but wrong about the rate of return on the infrastructure built to serve it.

Those notes demonstrate a developing research programme rather than a one-line bullish reaction to an interview. They also prevent the retrospective from simplifying the argument into an unconditional endorsement of Microsoft at any price.

## Why this comparison is relevant to my judgment

I think there are three things worth examining.

**First, the distinction was formulated before the public comparison became available.** The August essay identifies a specific interpretive error that could be made when capital expenditure rises. It does not merely predict that AI is growing. It explains why the *same financial event* can be interpreted in opposite ways, and which operational evidence can help decide between them.

**Second, the reasoning was causal and testable.** A useful investment thesis does not stop at the observation that management spends billions. It asks whether there is demand, what prevents that demand from becoming revenue, how new capacity removes the restriction, what it costs to do so, and what the resulting return looks like. The early essay even stated its own failure condition: growing capacity accompanied by weak utilisation would damage the thesis.

**Third, I treated market disagreement as a problem of expectations rather than simply a sign of irrationality.** A price decline need not be a mistake. It can reflect justified concern about technology obsolescence, cash-flow timing, poor incremental returns, or the possibility of simultaneous overbuilding by multiple hyperscalers. My task is to determine whether the market has assigned the wrong weight to those risks. The alternative is to confuse a strong company with a good investment.

Taken together, the agreement with Ackman's later public explanation is **evidence consistent with sound independent economic judgment**. It suggests I was analysing a real valuation mechanism, not merely responding to a famous investor's position after the fact. His independent use of the same reasoning is informative corroboration that the mechanism matters in actual professional capital allocation.

That is the claim I am willing to make. I would not claim that Ackman first conceived the idea in October, that I discovered a wholly original principle, or that he adopted an analysis from me. The date established here is the date of **his publicly released explanation**, not the private date on which he formed the view or bought the shares.

Nor does this case establish that Microsoft was undervalued when I wrote the August essay. The essay was a **general analytical framework**, not a dated Microsoft price target or a fully specified buy order. Agreement with Ackman's reasoning is not a measured investment return. Repeated out-of-sample decisions, including misses and rejected opportunities, would be needed to assess whether this reasoning translates into persistent alpha.

Still, those distinctions do not diminish what the record actually shows. On August 20 I had independently articulated the precise economic reason an investor might regard a selloff on higher AI CapEx as an opportunity rather than an automatic warning. On October 28 Ackman used that reason publicly to explain his investment in Microsoft.

The chronology is available for anyone to inspect.

## What would prove or disprove the investment thesis going forward?

For Microsoft itself, the relevant evidence is not the fact that Ackman holds shares. It is whether additional infrastructure spending ultimately delivers satisfactory **incremental returns after all costs**. The research should continue to test:

1. Whether Azure and AI-related demand remain constrained by physical or deployed capacity, rather than primarily by weak final demand.
2. Whether new capacity is utilised quickly enough to justify the timing and scale of expenditure.
3. Whether incremental revenue converts into sustainable operating profit and cash flow after energy costs, depreciation, maintenance and reinvestment.
4. Whether the economics survive falling compute prices, changing model architectures, custom chips, customer concentration and competition.
5. Whether the future returns implied by the actual stock price are below a defensible estimate of future owner cash flows.

The thesis would weaken materially if capacity arrived and utilisation disappointed; if additional capex bought progressively less cash flow; if more powerful competitors competed away the value; or if the original valuation already discounted an even better future.

In other words, the question that mattered in August still matters after the interview: **why is the company spending more, what economic return will that spending create, and what return is the stock market already pricing in?**

---

### Primary-source record

**My earlier material**

- [Original Notion essay, dated August 20, 2026](https://app.notion.com/p/3cc67b6787f8819c9f4ddad2d2c98cb4)
- [Original GitHub commit of the essay, recorded August 20, 2026 at 20:27:42 UTC](https://github.com/conscientai26-tech/investment-thesis-archive/commit/0ae0cdee18f76e9d77a7b5f333d0589472dc8191)
- [Unchanged August 20 historical file at the commit SHA, especially lines 27–43](https://github.com/conscientai26-tech/investment-thesis-archive/blob/0ae0cdee18f76e9d77a7b5f333d0589472dc8191/AI-Era%20Investment%20Development/Investing%20Through%20the%20AI%20Transition%20%E2%80%94%202026-08-20.md#L27-L43)
- [Microsoft-specific sections in *Amazon Analyse*, retrieved last-edited August 29](https://app.notion.com/p/3cb67b6787f8817d997ed8ca0901f292)
- [AI-CapEx perspective and bottlenecks, retrieved last-edited August 30](https://app.notion.com/p/3cc67b6787f881099026d344b518e272)
- [Capital Conversion Framework, retrieved last-edited September 3](https://app.notion.com/p/3cf67b6787f881698477f16f598f7cd1)

**Ackman's later public remarks**

- [Official Norges Bank Investment Management podcast episode, October 28, 2026](https://www.nbim.no/en/news-and-insights/podcast/2026/bill-ackman-concentrated-investing-permanent-capital-and-the-value-of-being-challenged/)
- [Episode date and distribution listing](https://shows.acast.com/in-good-company-with-nicolai-tangen/episodes/bill-ackman-concentrated-investing-permanent-capital-and-the)
- [Speaker-attributed transcript; relevant answer begins at approximately 14:18](https://ceointerviews.ai/interview/3147822/)

*Provenance note (October 29, 2026): This article is a retrospective comparison written after hearing Ackman's interview. The August and September sources were not rewritten for this comparison. The GitHub historical commit is cited separately from the mutable Notion pages so that the earlier wording can be checked. Notion links may require access depending on page-sharing settings.*
