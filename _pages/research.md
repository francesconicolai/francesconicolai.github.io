---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
{% include base_path %}

## Working Papers
### [Dynamic Arbitrage from Price-Based Risk Constraints](https://francesconicolai.github.io/papers)

<div style="text-align: justify">
Price-based risk constraints set margin, leverage, or exposure from sampled transaction prices, as in initial-margin and haircut schedules, VaR and drawdown limits, and target-volatility risk-control overlays. Because these rules generate deterministic feedback from transaction prices to future feasibility, a trader can profit from trigger-and-reverse round trips even when the underlying impact model satisfies standard no-price-manipulation (no-dynamic-arbitrage) conditions. Trading inside the sampling window moves the measured statistic, tightens the rule near binding, induces mechanical deleveraging, and the trader unwinds into the predictable flow. We derive a sharp local no-arbitrage condition that screens out such round trips. The test is implementable from public rulebooks and standard liquidity inputs: impact, the statistic's sensitivity to transaction prices, pass-through into required rebalancing near binding, and implementation timing. It yields a liquidity-scaled capacity bound $W_{\max}$ and vulnerability curves. In multi-asset settings with portfolio marking, the most profitable round trip trades only two portfolios: the marked portfolio and the constrained sector's liquidation portfolio. Applied to volatility-controlled and volatility-managed indices used in structured products and indexed annuities, the conservative bound is typically below one day of average daily volume (ADV), and vulnerability rises sharply once aggregate rebalancing reaches roughly one to two days of volume. The diagnostic is an ex ante rulebook stress test that informs capacity limits and implementation choices.</div>

### [An Impossibility Theorem for Price-Based Risk Constraints](https://francesconicolai.github.io/papers)

<div style="text-align: justify">
When margins are updated mechanically from transaction-based risk measures, transaction prices become inputs to constraints, and no price-based, risk-sensitive margin update can jointly satisfy three properties often imposed separately in collateral design: (i) risk sensitivity, (ii) liquidity continuity, and (iii) round-trip manipulation-proofness. An arbitrarily small trade that nudges a sampled mark shifts measured risk, raises the call, triggers predictable forced selling, and can be profitably reversed; with portfolio margins, the same tension propagates through cross-impact and risk aggregation. We prove a constructive local impossibility result for a class of price-based constraints: it requires neither large trades nor large price moves, and it does not rely on turning a slack margin requirement into a binding one. Constrained investors may anticipate manipulation. Continuous trading between discrete updates is allowed. The proof yields a sharp diagnostic. Profitability is governed by a local amplification factor, the product of pass-through from sampled prices to the risk statistic, from the statistic to posted margin, from margin calls to forced sales, and from forced sales back to prices via impact. This amplification is an interpretable magnitude screen: when it is high, rule-induced fire-sale pressure from a small mark distortion outweighs the round-trip trader's own impact costs. As a design implication, the diagnostic implies an effective cap on short-horizon pass-through and rationalizes anti-procyclicality tools, including limited pass-through, smoothing, and state-contingent buffers.</div>

### [Biased Beliefs and Institutional Overcrowding](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5024961)

(with [Simona Risteska](https://risteskasimona.github.io)) 
<div style="text-align: justify">
Understanding the determinants of overcrowding behaviour is challenging due to the difficulty in measuring investor beliefs and preferences. This paper addresses this challenge by exploring the dynamics of investor behaviour within the leveraged loan market. Our major findings reveal that overcrowding among institutional investors in this market is driven by incorrect beliefs about their peers’ actions rather than unobservable asset characteristics or positive spillovers across investors. Using a structural model of entry, along with exclusion restrictions and instrumental variables, we assess the accuracy of investor beliefs regarding their peers’ investment decisions. Our findings refute the hypothesis of unbiased beliefs, indicating that overcrowding is driven by investors’ incorrect assumptions about peer behaviour. Additionally, we recover the out-of-equilibrium beliefs of investors, providing insights into the determinants of their investment choices. These insights have significant implications for understanding market dynamics and quantifying the effect of overcrowding on asset prices.</div>

### __[Revealed Expectations and Learning Biases: Evidence from the Mutual Fund Industry](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3301279)__

(with [Simona Risteska](https://risteskasimona.github.io)) 
<div style="text-align: justify">
By inverting the optimal portfolios of mutual fund managers in a fairly general setting, which allows us to partial out the effect of risk aversion and hedging demands, we provide an estimate of perceived expected excess returns and show that they are significantly affected by experienced returns. The effect of past returns is non-monotone: we provide reduced-form and structural evidence of managers displaying recency and primacy bias. Finally, we estimate an average coefficient of relative risk aversion close to unity.</div>

### [Job Market Paper: Contagion in The Market for Leveraged Loans](https://francesconicolai.github.io/papers/JMP.pdf)
<div style="text-align: justify">
Collateralized Loan Obligations (CLOs) spread shocks in the market for leveraged loans. I document that, in order to satisfy constraints based on the par value of their assets, CLOs become forced sellers of high quality securities when hit by negative shocks to otherwise unrelated securities. Loans sold for non fundamental reasons trade at depressed prices for up to nine months after the shock. The effect cannot be explained by selection on ex-ante or ex-post loan characteristics. A large fraction of the dislocation in secondary markets is transmitted to the market of issuance: shocked companies due to refinance their loans substitute away from institutional tranches towards other types of securities. The substitution is imperfect causing an increase in the cost of borrowing.</div>

[Appendix](https://francesconicolai.github.io/papers/JMP_Appendix.pdf)

## Work in Progress
### [Living on the Edge: the Salience of Property Taxes in the UK Housing Market](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3381519)

(with [Marco Pelosi](https://marcopelosi.github.io/) and [Simona Risteska](https://risteskasimona.github.io)) 
<div style="text-align: justify">
Taxes that happen concurrently with the purchase are more salient than deferred taxes. Using a sharp geographical discontinuity between London Boroughs, we show that the incidence of property taxes deferred to the future is too small compared to the incidence of stamp duty taxes happening at the moment of buying the property. The difference in incidence implies very large discount rates that cannot be easily rationalized even after accounting for liquidity constraints. The lack of salience at the moment of purchase implies that the burden of the tax will be borne in the future to meet the budget constraint. This implies that there is an optimal tax mix, even though one of the two taxes is more distortionary than the other.</div>

### [What Explains Portfolio Concentration?](https://francesconicolai.github.io/research/)

(with [Simona Risteska](https://risteskasimona.github.io)) 

### [Explaining Search Patterns in the Residential Housing Market](https://francesconicolai.github.io/research/)

(with [Simona Risteska](https://risteskasimona.github.io)) 

