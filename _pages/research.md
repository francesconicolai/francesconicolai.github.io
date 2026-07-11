---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
description: "Research on margin, haircuts, leverage limits, volatility targeting, and other price-based risk constraints; market impact, forced liquidation, dynamic arbitrage and manipulation; institutional investors in leveraged loans and CLOs; and housing-market search and salience."
---
{% include base_path %}

## Working Papers
### [How Big Can Mechanical Rebalancing Get?](https://papers.ssrn.com/abstract=6328819)

(with [Simona Risteska](https://risteskasimona.github.io))

How big can a sector of mechanical rebalancers get before the market is manipulable? We derive an implementable test from the disclosed rule and a market-impact estimate alone, and apply it to volatility-controlled indices in structured products and indexed annuities: safe capacity is below 0.11 days of average daily volume (about 0.09% of the underlying market), and at one day of volume the no-manipulation condition fails in 81-98% of stress states.

<details>
<summary>Abstract</summary>
<div style="text-align: justify">
How large can a mechanically rebalancing sector grow before its own trading makes the market manipulable? Price manipulation is normally unprofitable because moving a price requires trading, and the trader's own market impact makes the round trip lose money. Backward-looking rules such as volatility targeting, margin, and value-at-risk limits break this protection. By mapping today's prices into tomorrow's required trades, they allow a trader to move today's price, change the rule's trigger, and then unwind into the predictable forced trades that result, profiting at the constrained sector's expense. A market can therefore pass the standard no-manipulation test and still allow a profitable round trip. The additional restriction created by this feedback provides a capacity test: given the disclosed rule and an estimate of market impact, it identifies the largest size the sector can reach before manipulation becomes possible. For volatility-managed portfolios, that size is small: below 0.11 days of average trading volume, or about 0.09% of the underlying market. At one day of trading volume, a profitable round trip exists in 84% of stress states, with a median annual return of 11%, rising to 61% at five days of trading volume. Fragility is greatest in calm markets, where the volatility tracked by the rule is easiest to influence.
</div>
</details>

### [An Impossibility Theorem for Price-Based Risk Constraints](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6312700)

Risk-sensitive rules that map transaction prices into binding requirements generically create first-order manipulation incentives.

<details>
<summary>Abstract</summary>
<div style="text-align: justify">
Price-based risk rules map sampled transaction prices into measured risk and then into binding requirements. We prove a local impossibility theorem: in reachable binding states with sufficiently strong amplification, no such rule can simultaneously remain (i) risk-sensitive, (ii) preserve liquidity continuity, and (iii) eliminate profitable round-trip manipulation. Unlike classic manipulation, the mechanism does not require large trades, large price moves, or making a slack constraint bind. A small trade can alter the prices used by the rule, tighten requirements, induce predictable forced selling, and then be reversed profitably. The result holds with continuous trading between discrete measurement and reset dates and survives strategic responses by constrained investors. Fragility is greatest when realized risk is low.
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

### [Biased Beliefs and Institutional Overcrowding](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5024961)

(with [Simona Risteska](https://risteskasimona.github.io))

Overcrowding in leveraged loans is explained by misbeliefs about peers’ actions, identified via a structural entry model with exclusion restrictions.

<details>
<summary>Abstract</summary>
<div style="text-align: justify">
Understanding the determinants of overcrowding behaviour is challenging due to the difficulty in measuring investor beliefs and preferences. This paper addresses this challenge by exploring the dynamics of investor behaviour within the leveraged loan market. Our major findings reveal that overcrowding among institutional investors in this market is driven by incorrect beliefs about their peers’ actions rather than unobservable asset characteristics or positive spillovers across investors. Using a structural model of entry, along with exclusion restrictions and instrumental variables, we assess the accuracy of investor beliefs regarding their peers’ investment decisions. Our findings refute the hypothesis of unbiased beliefs, indicating that overcrowding is driven by investors’ incorrect assumptions about peer behaviour. Additionally, we recover the out-of-equilibrium beliefs of investors, providing insights into the determinants of their investment choices. These insights have significant implications for understanding market dynamics and quantifying the effect of overcrowding on asset prices.
</div>
</details>

### [First Impressions and the Origins of Disagreement: Evidence from the Mutual Fund Industry](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3301279)

(with [Simona Risteska](https://risteskasimona.github.io))

We recover a non-fundamental source of disagreement, tied to when each manager first bought a stock, and use it to settle three open questions: why investors trade against each other, why disagreement raises volatility without news, and when disagreement is priced.

<details>
<summary>Abstract</summary>
<div style="text-align: justify">
How much mutual fund managers disagree about a stock depends in large part on when each of them first purchased it. We invert their holdings into perceived expected returns: a manager's belief anchors to the return earned at her first purchase. Because they buy the same stock at different times, this first impression is the largest measured component of cross-manager disagreement, explaining about a tenth of its cross-sectional variation, an order of magnitude more than analyst-forecast dispersion. The disagreement is non-fundamental: it forecasts future volatility but not earnings surprises, while analyst dispersion does the reverse. It drives trading volume, as managers trade against one another; where short-sale constraints bind it is priced, the most disagreed-upon stocks underperforming by roughly ten percent a year.
</div>
</details>

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


