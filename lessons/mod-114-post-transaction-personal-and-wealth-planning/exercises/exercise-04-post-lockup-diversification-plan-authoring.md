# exercise-04: Post-Lockup Diversification Plan Authoring

**Estimated effort:** 3 hours

## Objective

Author a specific post-lockup diversification plan for your frozen fact pattern — quantifying the specific concentration-risk starting point, selecting among the sale-based and hedge-based toolkit, sequencing the diversification across months 0–36+, and producing a plan document you could hand to a fiduciary wealth manager and CPA for implementation review. By the end of the exercise you should be able to defend each tool choice against the alternatives, each sequencing decision against the founder's specific life goals, and each cost line against the tax and fee calculus.

## Background

This exercise covers material from:

- [Chapter 4 — Post-Lockup Diversification](../04-post-lockup-diversification.md)
- Dependencies on [Chapter 1 — QSBS Fundamentals](../01-irc-1202-qsbs-fundamentals.md), [Chapter 2 — Stacking](../02-qsbs-stacking-mechanics.md), [Chapter 3 — 10b5-1 Plans](../03-rule-10b5-1-trading-plans.md), and interaction with [Chapter 5 — Charitable Vehicles](../05-charitable-vehicles.md).

For founders whose exit is M&A cash-out, the 10b5-1 chapter 3 overlay does not apply — the staged-sale tool runs through specific M&A-consideration sales, specific earn-out milestones, or specific hold-and-sell choices for stock-form consideration from the acquirer. For IPO founders, the 10b5-1 plan from exercise-03 is the execution mechanic for the staged-sale tool.

## Prerequisites

- The frozen personal fact-pattern profile from exercise-01.
- The QSBS tranche inventory and cap-arithmetic from exercise-01.
- The stacking plan (if applicable) from exercise-02.
- The 10b5-1 plan draft (if applicable) from exercise-03.
- Access to primary sources: §1259 (constructive sales), §1092 (straddles), §1234 (option tax treatment), §721 (exchange-fund-contribution non-recognition), §1091 (wash-sale rule), §170 (charitable-deduction limits), and the current federal capital-gains and NIIT rates.
- A list of your specific non-negotiable life goals (retirement funding target, home purchase, education funding for children, specific philanthropic commitments, specific angel-investing programme funding, etc.) with specific dollar amounts and specific horizons.
- Rough estimates of your other investable assets (public-market portfolio, retirement accounts, real estate, private-fund LP positions, angel positions) and your other liabilities.

## Tasks

### 1. The concentration quantification

Compute the specific concentration-risk starting point:

**Position-value math.**

- Current share count held personally after any exercise-02 stacking transfers.
- Current share price (at the measurement date — for IPO founders, use the lock-up expiration price or a forward-looking expected price; for M&A founders, use the specific transaction price).
- Position value = share count × price.

**Net-worth math.**

- Position value (as above).
- Other liquid investments (public-market portfolios, mutual funds, cash, money-market).
- Illiquid financial assets (private-fund LP interests, angel positions).
- Real estate net of mortgages (excluding primary residence if you have no intention of selling).
- Other investable net worth (minus consumer debt, minus any specific illiquid obligations).
- Total investable net worth = sum of the above.

**Concentration ratio.**

- Position value / total investable net worth.
- Note: for exercise-02 stacking recipients (trusts, family members), separately compute their concentration ratios — the trust's QSBS block may represent the trust's entire investable net worth, which is its own concentration-risk situation.

**Human-capital exposure.**

- If still employed at the issuer: present-value of future expected salary (3–7 year horizon at a reasonable discount rate) + expected future equity grants (RSUs, options). Add to the position's issuer-exposure total.
- Note the specific issuer-aggregate exposure (shares + salary NPV + future-grant NPV) as a percentage of broader economic exposure (including human-capital and off-issuer-wealth).

**Drawdown scenario math.**

- Sector-comparable drawdown — look at peak-to-trough drawdowns in the issuer's sector over the past 3–5 years. For SaaS, consider the 2021–2022 multiple-compression period; for biotech, the XBI drawdowns; for fintech, the FINX drawdowns.
- Idiosyncratic drawdown — a 50% single-stock drawdown is a realistic worst-case over a multi-year horizon.
- Dollar wealth at risk — concentrated-position value × drawdown percentage.
- Compare against the non-negotiable life-goals total (from prerequisites) — if a 50% drawdown would compromise the non-negotiable goals, the concentration must be reduced to the level where even in a 50% drawdown the goals remain funded.

### 2. The life-goals and liquidity-needs breakdown

For each of your specific non-negotiable life goals, document:

- The specific dollar amount.
- The specific horizon (within 1 year, within 5 years, 5–10 years, 10+ years).
- The specific funding source priority (which investments or which proceeds-tranche funds this goal).

Compute the aggregate liquidity needs across horizons and compare against the planned sale schedule. Any mismatch (needing $10M for a home purchase in year 1 but the sale schedule only produces $4M of liquidity in year 1) is a specific sequencing problem to address.

### 3. The tool-selection decision

For each portion of the concentrated position, decide which diversification tool applies. Build a specific allocation table:

| Portion | Share count | Tool | Horizon | Rationale |
|---|---|---|---|---|
| QSBS within cap | X | Direct sale under 10b5-1 (or at closing for M&A) | Months 1–18 | $0 federal tax; no reason to defer |
| QSBS above cap, retained in founder's hands | X | Direct sale under 10b5-1 + tax-loss-harvesting offset where available | Months 1–24 | Tax at ~23.8% + state; staged-sale minimises market impact |
| QSBS above cap, pre-close contribution to charitable vehicle | X | Contribute to DAF / CRT before transaction (exercise 05) | Pre-close | $0 federal tax on contributed appreciation; §170 deduction |
| Non-QSBS, large block, immediate-cash need | X | Prepaid variable forward (PVF) | 1–5 years | Immediate cash without current-year tax; counterparty engagement required |
| Non-QSBS, large block, no immediate need | X | Exchange fund contribution | 7 years lock | Diversification without current-year tax; defer gain |
| Non-QSBS, residual retained position | X | Options collar for bridge protection | 6–24 months | Protect downside during initial high-volatility window |
| Residual retained position for long-term hold | X | Hold | Indefinite | Long-term exposure to issuer growth; founder's thesis |

For each row, justify the specific tool choice vs. alternatives. Address: why the chosen tool, why not the other tools, specific trade-offs on tax, cost, duration, and complexity.

### 4. The 10b5-1 or M&A-sale execution plan

For IPO founders, this is the exercise-03 10b5-1 plan with specific tax-aware tranche sequencing:

- **QSBS-within-cap tranches sold first.** The federal tax on the excluded gain is $0, so there is no reason to defer these sales. Early execution maximises the probability of completing the full QSBS-eligible sale before any specific adverse event.
- **QSBS-above-cap tranches sold next, timed with charitable-vehicle contributions.** Coordinate the above-cap sales with the §170 deduction from any pre-close charitable-vehicle contribution to offset the taxable portion.
- **Non-QSBS tranches sold last.** The tax rate is the same (~23.8% blended for long-term capital gains), but these tranches do not benefit from the cap. Delay these sales so other planning (hedge-structures, charitable contributions) can reduce the net tax.

For M&A founders:

- **Cash consideration received at closing.** Immediate QSBS exclusion applies on the cash portion up to cap (if the sale is a stock sale). For asset-sale structures, QSBS does not apply at the shareholder level — plan accordingly.
- **Stock consideration (acquirer stock).** Carries over QSBS characteristics under §1202(h)(4) if the acquirer stock is QSBS-eligible. The founder's eventual sale of the acquirer stock will be subject to §1202 analysis at that time. Plan the acquirer-stock-sale schedule under a specific 10b5-1 plan if the acquirer is public, or under a specific lock-up and private-sale discipline if the acquirer is still private.
- **Earn-out consideration.** Milestone payments are taxed as additional sale consideration (generally capital gain) in the year received. Plan the earn-out-receipt tax exposure separately.

### 5. The exchange-fund decision (if applicable)

If your allocation includes an exchange-fund contribution:

- **Provider selection.** Cache Financial, Long Angle, Eaton Vance (Morgan Stanley Investment Management), Ithan Creek Capital Partners (Wellington), BNY Mellon Lockwood, or others. Note each provider's specific minimum contribution, specific fee structure, specific portfolio composition, and specific track-record data.
- **Contribution amount and timing.** Specific contribution amount; specific contribution date. Note that exchange-fund contribution typically forfeits QSBS; confirm your contribution is the non-QSBS or above-cap portion of the position, not QSBS-within-cap.
- **7-year lock implications.** Model your cash-flow needs over the 7-year lock period. Confirm you have adequate liquidity from other sources to not need the exchange-fund interest during the lock.
- **Portfolio composition review.** Review the specific fund's current portfolio (approximate single-position concentration, sector exposure, number of underlying positions). Confirm the diversification you receive is meaningfully different from the diversified exposure you could build with cash from direct sale.
- **Basis-carryover modelling.** On eventual withdrawal (year 7+), you receive a basket of the fund's holdings at the fund's basis. Model the eventual-sale tax when you later diversify out of the basket. Compare the deferred-tax-with-exchange-fund NPV against the direct-sale-pay-tax-now NPV. For large positions above cap, deferral often has positive NPV; for QSBS within cap, direct sale is strictly better.
- **All-in cost modelling.** Management fees (0.5–1.5% annually), any placement or participation fees, carry charges if applicable. Multiply by the 7-year horizon to compute the all-in deferral cost. Compare against the tax saved by deferral.

### 6. The options-collar decision (if applicable)

If your allocation includes a collar:

- **Collar structure.** Protective put strike (typically 5–15% below current price), covered call strike (typically 15–35% above current price). Choose specific strikes based on your downside tolerance and your view on realistic upside.
- **Expiration.** Typical range 6–24 months. Longer expirations have less-liquid options and higher premium costs; shorter expirations require rolling.
- **Zero-cost vs. low-cost structure.** Zero-cost collar structures put and call premiums to offset. Low-cost collars pay a small net premium (typically for tighter put protection). Model both and choose.
- **§1259 constructive-sale analysis.** Confirm the collar structure does not trigger constructive-sale under §1259. Rule of thumb: wider strikes (90% put, 110% call) typically avoid constructive-sale; tighter strikes (95% put, 105% call) may trigger it. Tax counsel review required.
- **§1091 straddle-rule analysis.** Confirm the collar does not restart the holding period of the underlying stock in a way that affects §1202 or long-term-capital-gain treatment. Tax counsel review required.
- **Options approval and broker selection.** Options strategies require an options-approved brokerage account at the appropriate level (typically Level 3 or higher for collar strategies). Confirm the broker's options-approval status and the specific strategy limits.
- **Counterparty and liquidity.** Exchange-listed options are liquid; OTC collars (for very large positions) require specific counterparty engagement (major investment banks: Goldman Sachs, Morgan Stanley, JP Morgan, Citi, Deutsche Bank, UBS). Document the counterparty selection and specific counterparty-credit-review.

### 7. The prepaid-variable-forward decision (if applicable)

For founders with very-large positions (typically $100M+) needing immediate cash without current-year tax:

- **Counterparty selection.** Major investment-bank counterparties (Goldman Sachs, Morgan Stanley, JP Morgan, Citi, Deutsche Bank, UBS). Note that PVFs are private-placement, bespoke transactions — the specific counterparty's execution capability, documentation quality, and ongoing relationship-management matter.
- **Prepayment amount.** Typically 75–90% of current market value of the reference shares. Model the specific prepayment amount.
- **Maturity and delivery formula.** 1–5 year maturity typical. The delivery formula includes a cap (above which founder forgoes upside), a floor (below which founder is protected from downside), and a variable-share-count mechanic between the two.
- **§1259 constructive-sale analysis.** Confirm the structure preserves material downside exposure (below the floor) or upside exposure (above the cap) to avoid constructive-sale. Tax counsel review required.
- **Pledge and Form 4 disclosure.** The reference shares are typically pledged as collateral. Pledges by Section 16 insiders are disclosed on Form 4. The transaction may also be disclosed in the issuer's proxy statement under Item 407(i) if treated as a hedging arrangement.
- **Hedging-arrangement-policy compliance.** Many issuers' insider-trading policies prohibit or restrict hedging arrangements by insiders. Confirm the specific policy allows PVFs — this is typically negotiated with the audit committee at plan inception.
- **All-in cost modelling.** The haircut from current market value (10–25%) is effectively the fee. Model the all-in cost over the contract term and compare against alternatives.

### 8. The charitable-vehicle coordination (preview to exercise 05)

For any pre-close charitable-vehicle contributions planned in exercise 05, document the specific contribution amounts, specific vehicle types (DAF, CRT, private foundation), and specific timing. These contributions:

- Reduce the aggregate direct-sale amount.
- Produce a §170 deduction that can offset the taxable portion of the above-cap direct sales (subject to the §170 AGI percentage limits with 5-year carryforward).
- Must be complete before the transaction becomes effectively certain to avoid anticipatory-assignment-of-income recharacterisation.

### 9. The sequence calendar

Build a specific month-by-month calendar across months 0 (lock-up expiry or transaction-close date) through month 36:

- **Month -12 to -3 (pre-close).** Charitable-vehicle contributions (per exercise 05), stacking-gift finalisation (per exercise 02), personal-counsel and wealth-manager engagements, 10b5-1 plan drafting and audit-committee approval (for IPO).
- **Month 0 to 3 (lock-up window or immediate post-close).** 10b5-1 plan cooling-off period runs; no sales. For IPO, watch price action and company performance; do not deviate from plan.
- **Month 3 to 12 (initial sale window).** 10b5-1 plan executes initial sales. QSBS-within-cap tranches sold first. Potential bridge-protection collar over a portion of the position. Tax-loss harvesting coordinated with CPA.
- **Month 12 to 24 (continued sale window).** Plan continues. QSBS-above-cap and non-QSBS tranches sold. Concentration ratio monitored against target. Potential plan renewal or extension if continued diversification needed.
- **Month 24 to 36 (residual-position-management window).** For residual positions still above target concentration, consider exchange-fund contribution, longer-duration collar, or continued slow sales. Begin exploring estate-planning transfers and philanthropic transfers for the residual.
- **Month 36+ (long-term-hold management).** Residual position becomes a long-term concentrated holding subject to ongoing wealth-management discipline, periodic rebalancing, and estate-plan integration.

### 10. The diversification-plan memo

Produce a 3–4 page memo you would hand to a fiduciary wealth manager and CPA at the first implementation review meeting. The memo should include:

- The concentration-quantification result (specific numbers for position value, net worth, concentration ratio, human-capital exposure, drawdown scenarios, wealth at risk).
- The life-goals and liquidity-needs breakdown.
- The tool-allocation table with per-portion justifications.
- The 10b5-1 or M&A-sale execution plan.
- The exchange-fund, collar, and PVF decisions (if applicable).
- The charitable-vehicle coordination summary.
- The sequence calendar.
- The specific unresolved questions for the wealth manager and CPA (e.g., "Confirm the specific tax-loss-harvesting opportunities across the broader portfolio for the year of the largest planned sale"; "Confirm the specific exchange-fund provider selection against three alternatives").

## Starter guidance

Three anti-patterns to avoid:

- **The "wait for the right price" delay.** The most consistent finding in behavioural finance is that concentrated-position holders systematically delay diversification waiting for a price that never arrives (or arrives after a large drawdown). The 10b5-1 plan's mechanical schedule and the exchange-fund's commitment are specific commitment devices against this bias.
- **The "defer-everything via hedges" mistake.** Hedges defer tax; they do not eliminate it. A plan built entirely around deferral eventually faces the tax bill when the hedges unwind, often at a less favourable time. Hedge for specific purposes (bridge protection, immediate cash for specific need), not as a substitute for eventual sale.
- **The "sell everything in year 1" mistake.** Compressed sale horizons concentrate market-timing risk. A founder who sold the entire position in the first 90 days post-lock-up might capture a specific low. Spreading over 12–36 months distributes the risk.

## Acceptance criteria

You can demonstrate that:

- The concentration quantification is specific in dollars and percentages, with specific drawdown-scenario math against specific life goals.
- The tool-allocation table assigns every portion of the position to a specific tool with a specific rationale.
- The 10b5-1 or M&A-sale execution plan sequences QSBS-within-cap, QSBS-above-cap, and non-QSBS tranches with specific tax-aware ordering.
- The exchange-fund, collar, and PVF decisions (where applicable) are specific on provider, structure, cost, and §1259 and other tax-rule compliance.
- The charitable-vehicle coordination with exercise 05 is explicit.
- The sequence calendar runs month-by-month from pre-close through month 36+ with specific activities.
- The diversification-plan memo is specific enough that a fiduciary wealth manager and CPA would be able to begin implementation review without preliminary scoping.
- A critical reader (a fiduciary RIA, a CPA, a securities-tax counsel) can test each tool choice and sequencing decision and find it defensible.

## Reflection

Add a short reflection (½ page):

1. If the stock drops 40% in the first 90 days after lock-up expiry, how does your plan respond? Which plan elements adjust and which do not?
2. If a specific unexpected life event (illness, divorce, forced residency change) occurs in year 2 of the plan, which specific plan elements can adjust and which are structurally committed?
3. What specific coordination gap between the wealth manager, CPA, personal securities counsel, and private-client tax attorney is most likely to produce a failure in your plan? What specific coordination mechanism (from chapter 7) addresses it?

## Stretch goals

- **Monte-Carlo wealth-outcome modelling.** For your specific plan, build a simple Monte-Carlo simulation of wealth outcomes over the 36-month horizon under specific assumptions about stock-price volatility, correlation to the market, and your other investments' returns. What is the probability that your plan satisfies the non-negotiable life goals? What specific plan adjustments increase that probability?
- **Alternative-plan comparison.** Build two alternative plans — one more aggressive on diversification (faster sale, more hedging) and one more conservative (slower sale, more retained position) — and compare the expected wealth outcomes against your base-case plan.
- **Comparable-founder analysis.** Research the specific post-IPO diversification patterns of 3–5 publicly-traded issuers' founders over the first 24 months post-lock-up (via Form 4 filings on EDGAR). What specific sale patterns emerge, and how do they compare to your proposed plan?
