---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
description: "Research on margin, haircuts, leverage limits, volatility targeting, and other price-based risk constraints; market impact, forced liquidation, dynamic arbitrage and manipulation; institutional investors in leveraged loans and CLOs; and housing-market search and salience."
---
{% include base_path %}

## Working Papers
### [An Impossibility Theorem for Price-Based Risk Constraints](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6312700)

Risk-sensitive rules that map transaction prices into binding requirements generically create first-order manipulation incentives.

<details>
<summary>Abstract</summary>
<div style="text-align: justify">
Price-based constraints map sampled transaction prices into a risk statistic and then into a binding requirement, such as posted margin, a haircut, a leverage limit, or a mandated portfolio reallocation. We prove a constructive local impossibility theorem: no price-based, risk-sensitive rule can jointly achieve three desirable properties, namely (i) risk sensitivity, (ii) liquidity continuity, and (iii) round-trip manipulation-proofness, in any reachable binding state in which amplification is sufficiently strong. The proof constructs a rule-induced trigger-and-reverse deviation: an arbitrarily small trade tilts the sampled statistic, tightens a binding requirement at first order, induces predictable forced liquidation, and is profitably reversed. Unlike classic manipulation that relies on large trades to move the price level, the incentive here runs through first-order effects of sampled prints on the rulebook and the resulting forced flow; it does not require large trades or large price moves, and it does not rely on making a slack constraint bind. The result holds with continuous trading between discrete measurement and reset times, and it survives strategic responses by constrained traders. Vulnerability is state dependent: marginal sensitivity is highest when realized risk is low, so tranquil states can be most exposed to manipulation. Quantitative relevance is summarized by a local amplification factor, the product of pass-through elasticities along the loop from prices to the statistic, to margin requirements, to forced sales, and back to prices via impact. With portfolio margining and cross-impact, trigger and liquidation directions can differ, generating cross-contract manipulation and spillovers. The design implication is immediate: implementability requires limiting short-horizon pass-through, rationalizing anti-procyclicality tools such as smoothing and state-contingent buffers.
</div>
</details>

### [Dynamic Arbitrage from Price-Based Risk Constraints](https://papers.ssrn.com/abstract=6328819)

(with [Simona Risteska](https://risteskasimona.github.io))

Classical no-manipulation restrictions do not preclude dynamic arbitrage when constraints depend on a risk measure computed from sampled transaction prices; we derive a new viability condition, characterize optimal attacks, and show that volatility-managed funds are often vulnerable.

<details>
<summary>Abstract</summary>
<div style="text-align: justify">
Under classic no-manipulation conditions on market impact, price-based risk constraints (margins, haircuts, leverage limits, volatility targets, mandates) can still generate dynamic arbitrage. We develop a refined no-dynamic-arbitrage test for such environments; it requires only the constraint rule and an estimate of market impact. The test also yields an upper bound on the size of the constrained sector consistent with non-manipulability. We apply it to volatility-managed portfolios: admissible scale is well below one day of average daily volume, and vulnerability increases sharply once linked notional reaches roughly one to two days of daily volume. Manipulation incentives are strongest in low-volatility states, driven by feedback between measured risk and rule-induced trading.
</div>
</details>

### [Biased Beliefs and Institutional Overcrowding](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5024961)

(with [Simona Risteska](https://risteskasimona.github.io))

Overcrowding in leveraged loans is explained by misbeliefs about peers’ actions, identified via a structural entry model with exclusion restrictions.

<details>
<summary>Abstract</summary>
<div style="text-align: justify">
Understanding the determinants of overcrowding behaviour is challenging due to the difficulty in measuring investor beliefs and preferences. This paper addresses this challenge by exploring the dynamics of investor behaviour within the leveraged loan market. Our major findings reveal that overcrowding among institutional investors in this market is driven by incorrect beliefs about their peers’ actions rather than unobservable asset characteristics or positive spillovers across investors. Using a structural model of entry, along with exclusion restrictions and instrumental variables, we assess the accuracy of investor beliefs regarding their peers’ investment decisions. Our findings refute the hypothesis of unbiased beliefs, indicating that overcrowding is driven by investors’ incorrect assumptions about peer behaviour. Additionally, we recover the out-of-equilibrium beliefs of investors, providing insights into the determinants of their investment choices. These insights have significant implications for understanding market dynamics and quantifying the effect of overcrowding on asset prices.
</div>
</details>

### [Revealed Expectations and Learning Biases: Evidence from the Mutual Fund Industry](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3301279)

(with [Simona Risteska](https://risteskasimona.github.io))

Inverting mutual fund portfolios recovers perceived expected returns and reveals non-monotone learning biases tied to experienced returns.

<details>
<summary>Abstract</summary>
<div style="text-align: justify">
By inverting the optimal portfolios of mutual fund managers in a fairly general setting, which allows us to partial out the effect of risk aversion and hedging demands, we provide an estimate of perceived expected excess returns and show that they are significantly affected by experienced returns. The effect of past returns is non-monotone: we provide reduced-form and structural evidence of managers displaying recency and primacy bias. Finally, we estimate an average coefficient of relative risk aversion close to unity.
</div>
</details>

### [Contagion in The Market for Leveraged Loans](https://francesconicolai.github.io/papers/JMP.pdf)

CLO constraints trigger forced sales that depress secondary-market prices and transmit shocks into primary-market borrowing costs.

<details>
<summary>Abstract</summary>
<div style="text-align: justify">
Collateralized Loan Obligations (CLOs) spread shocks in the market for leveraged loans. I document that, in order to satisfy constraints based on the par value of their assets, CLOs become forced sellers of high quality securities when hit by negative shocks to otherwise unrelated securities. Loans sold for non fundamental reasons trade at depressed prices for up to nine months after the shock. The effect cannot be explained by selection on ex-ante or ex-post loan characteristics. A large fraction of the dislocation in secondary markets is transmitted to the market of issuance: shocked companies due to refinance their loans substitute away from institutional tranches towards other types of securities. The substitution is imperfect causing an increase in the cost of borrowing.
</div>
</details>

[Appendix](https://francesconicolai.github.io/papers/JMP_Appendix.pdf)

## Work in Progress

### [Living on the Edge: the Salience of Property Taxes in the UK Housing Market](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3381519)

(with [Marco Pelosi](https://marcopelosi.github.io/) and [Simona Risteska](https://risteskasimona.github.io))

A London-borough border discontinuity shows deferred property taxes are weakly capitalized relative to upfront taxes, implying large discounting or limited salience.

<details>
<summary>Abstract</summary>
<div style="text-align: justify">
Taxes that happen concurrently with the purchase are more salient than deferred taxes. Using a sharp geographical discontinuity between London Boroughs, we show that the incidence of property taxes deferred to the future is too small compared to the incidence of stamp duty taxes happening at the moment of buying the property. The difference in incidence implies very large discount rates that cannot be easily rationalized even after accounting for liquidity constraints. The lack of salience at the moment of purchase implies that the burden of the tax will be borne in the future to meet the budget constraint. This implies that there is an optimal tax mix, even though one of the two taxes is more distortionary than the other.
</div>
</details>

### [Investment Mandates](https://francesconicolai.github.io/research/)

(with [Simona Risteska](https://risteskasimona.github.io))




### [Explaining Search Patterns in the Residential Housing Market](https://francesconicolai.github.io/research/)

(with [Simona Risteska](https://risteskasimona.github.io))


