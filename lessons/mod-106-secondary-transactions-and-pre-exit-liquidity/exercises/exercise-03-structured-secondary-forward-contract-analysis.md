# exercise-03: Structured Secondary Forward Contract Analysis

**Estimated effort:** 3–4 hours

## Objective

Evaluate three structured-secondary instruments — a collateralised loan, a fixed-share forward contract, and a prepaid variable forward contract (PVFC) — against a specific shareholder's fact pattern, and produce an instrument-selection memo (6–8 pages) that names the recommended instrument, defends the choice against the two rejected alternatives, sizes the transaction at defensible economics, analyses the §1259 constructive-sale and §1202 QSBS interactions, and defends the counterparty selection against the counterparty-credit-risk profile. At the end you should be able to walk the shareholder and their personal tax and legal advisors through the trade-offs and reach an execute-or-decline decision.

## Background

This exercise covers material from:

- [Chapter 4 — Structured Secondaries — Forward Contracts, Collateralised Loans, and Counterparty-Credit Risk](../04-structured-secondaries-and-forward-contracts.md) — the collateralised-loan mechanic, the forward-contract mechanic, the PVFC variant, the §1259 constructive-sale envelope, the counterparty landscape, and the counterparty-credit risk.

Supporting references:

- [Chapter 1 — Founder Secondary](../01-founder-secondary-structuring.md) — the direct-sale alternative that the structured secondary replaces.
- [Chapter 6 — ROFR and Co-Sale Choreography](../06-rofr-and-co-sale-choreography.md) — a structured secondary that transfers economic exposure without transferring record ownership may or may not trigger the target's ROFR depending on the target's specific agreement.
- [mod-103 chapter on IRC §1202 QSBS](../../mod-103-mna-deal-structures-and-consideration/README.md) for the QSBS holding-period-preservation discipline that the forward-contract structure can protect.

## Prerequisites

- The hypothetical target and shareholder from exercise-01 (or a comparable shareholder profile — founder, executive, or long-tenured senior IC with a meaningful vested position).
- Access to the IRC §1259 constructive-sale statute and Treasury regulations, and the IRS's technical guidance on §1259 as applied to forward contracts and non-recourse loans.
- Access to the counterparty landscape at chapter 4's depth — Setter Capital, ClearList, Rainmaker Securities, DBO Partners, and specialist private-securities-lending arms of large financial-services firms (Bank of America, Morgan Stanley, Goldman Sachs, JPMorgan private banks). Public websites and press coverage sufficient; specific transaction terms are typically bilateral and not published.
- A spreadsheet for the instrument-comparison and after-tax modelling.

## Tasks

### 1. Set the shareholder-and-need baseline

Write a 1-page shareholder-and-need baseline covering:

- **Shareholder profile** — role, employment status, current common holdings (share count, per-share basis, current 409A common price, current market-implied value at last preferred round), grant history including 83(b) elections and QSBS-qualification analysis, state residence.
- **Liquidity need** — the specific dollar amount required, the timing (immediate vs. within 12 months), and the specific use (household stabilisation, tax-payment obligation, other-venture investment, family situation). Distinguish "need cash today" from "want to lock in current valuation."
- **§1202 QSBS status** — is the position §1202-qualifying? What is the current holding period? If the 5-year mark is not reached, when is it reached?
- **Alternative direct-sale option** — could the shareholder access a direct secondary today (chapter 1 founder secondary, chapter 2 employee tender participation, or chapter 5 platform-cleared secondary)? What are the constraints (ROFR notice timing, tender-eligibility rules, platform-relationship posture)? Why is the direct sale not sufficient?
- **Time horizon to plausible liquidity** — the target's expected M&A / IPO horizon and the shareholder's tolerance for waiting.

### 2. Evaluate the collateralised-loan instrument

Produce a specific collateralised-loan proposal covering:

- **Advance rate** — the fraction of fair value the lender is willing to advance, calibrated against the target's stage and the shareholder's specific counterparty (25%–50% typical for growth-stage private-company shares, higher for late-stage with IPO visibility).
- **Interest rate** — annual rate (10–15% typical for growth-stage, PIK vs. cash-pay). Model the accrued-interest burden across 3-year and 5-year terms.
- **Recourse vs. non-recourse** — the specific choice and its §1259 implication (non-recourse with high advance rates approaches constructive-sale treatment; recourse preserves the shareholder's other-asset exposure but avoids §1259).
- **Term and maturity trigger** — fixed maturity date, IPO or M&A trigger, or a combination.
- **Cash today** — the loan advance the shareholder receives at closing.
- **Retained upside** — at a range of exit valuations (2×, 3×, 5× current), the shareholder's residual equity value after loan repayment.
- **Downside scenario** — what happens if the target's exit is below the loan basis; the recourse-vs-non-recourse implication.
- **§1259 risk read** — where the specific advance rate + interest rate + recourse profile sits on the constructive-sale envelope.

### 3. Evaluate the fixed-share forward-contract instrument

Produce a specific forward-contract proposal covering:

- **Forward price** — the fixed per-share settlement price the counterparty offers, expressed as a discount to current 409A or to last-round preferred.
- **Upfront advance** — the percentage of forward price paid at execution (50–80% typical).
- **Settlement date** — fixed date (typically 12–36 months out) or trigger-event (IPO or M&A).
- **Interim economics** — any accrued fees or economics between execution and settlement.
- **Record-ownership retention** — the shareholder retains record ownership until settlement, preserving voting rights and — critically — holding-period discipline for §1202 and long-term capital gains.
- **Cash today** — the upfront advance the shareholder receives at closing.
- **Cash at settlement** — the residual payment at settlement.
- **§1259 risk read** — analyse whether the fixed-share forward with the specific upfront advance and the specific settlement structure is a constructive sale under §1259 (a fixed-share forward with an upfront advance above ~60% and no offsetting variable-delivery component typically is a constructive sale; below that level, may be treated as an executory contract).
- **§1202 QSBS interaction** — if the position is §1202-qualifying but has not yet reached the 5-year mark, does the forward preserve the holding period? (Yes, if not a constructive sale; no, if it is.) Compute the §1202 exclusion available at settlement under each scenario.

### 4. Evaluate the prepaid variable forward contract (PVFC)

Produce a specific PVFC proposal covering:

- **Upfront advance** — the percentage of current fair value paid at execution (75–90% typical in the public-company version; the private-company version is rare and typically at lower advance rates).
- **Collar** — the floor and ceiling per-share prices that define the variable-delivery mechanism. If settlement price is above the ceiling, the shareholder delivers fewer shares (retaining upside above the ceiling); below the floor, delivers the full pledged block.
- **Settlement date and delivery mechanic** — how shares are delivered at settlement based on the settlement-date price relative to the collar.
- **§1259 protection** — the variable-delivery mechanic that preserves risk-of-loss and opportunity-for-gain, protecting the PVFC from constructive-sale treatment.
- **Private-company challenge** — the specific counterparty concern with the PVFC in the private-company context: without a public market price at settlement, the collar and delivery mechanic require a specific valuation methodology, which most private-company counterparties will not absorb.
- **Feasibility read** — under what circumstances would a private-company PVFC actually be executable, and what specific counterparties (if any) offer the structure?

### 5. Compare the three instruments across a common set of dimensions

Produce a comparison matrix covering (at minimum):

- Cash today (as % of underlying fair value).
- Retained upside at plausible exit scenarios.
- Downside protection (does the shareholder lose their other assets if the target underperforms?).
- §1259 constructive-sale exposure.
- §1202 QSBS preservation.
- Voting-rights retention.
- Holding-period preservation for LTCG.
- Target-company ROFR / co-sale implications (does the instrument trigger the ROFR? Does it require the target's consent?).
- Counterparty-credit-risk profile.
- Fee-and-cost transparency.
- Reversibility (can the shareholder unwind the instrument mid-term if their circumstances change?).

Rank the three instruments against the shareholder's specific fact pattern and recommend one.

### 6. Analyse the counterparty landscape and select a counterparty

For the recommended instrument, evaluate the counterparty options from chapter 4:

- **Setter Capital** — Toronto-headquartered, longstanding private-secondary intermediary, principal in structured secondaries.
- **ClearList** — private-company-securities transaction infrastructure.
- **Rainmaker Securities** — FINRA-registered broker-dealer with a private-secondary practice.
- **DBO Partners** — private-company-securities investment bank.
- **Specialist private-securities-lending arms** — Bank of America, Morgan Stanley, Goldman Sachs, JPMorgan private banks; typically require the shareholder to be an existing private-banking client.
- **Purpose-built forward-contract funds** — smaller, specialist counterparties emerging from the venture-secondary ecosystem.

For the selected counterparty, cover:

- Why this counterparty fits the instrument and the shareholder's fact pattern.
- The counterparty's specific reputation for the instrument type.
- The counterparty's own credit profile — capitalisation, funding source, term-mismatch risk, and the shareholder's exposure if the counterparty fails between execution and settlement.
- The specific counterparty-credit-risk mitigants available — collateral posted by counterparty, custody escrow, third-party settlement agent.
- The alternative counterparty you rejected and why.

### 7. Work the tax analysis

Draft a 2–3 page tax analysis covering:

- **Timing of the taxable event** — at execution or at settlement, and the specific driver of the timing (§1259 constructive-sale analysis for forwards, §1001 sale-or-exchange analysis for high-advance non-recourse loans).
- **Character of the gain** — LTCG at settlement (for forwards that preserve the holding period) or LTCG at execution (for constructive-sale forwards); interest-expense deductibility on collateralised loans (typically limited under §163 investment-interest rules for individual shareholders).
- **§1202 QSBS analysis** — the specific timing implication and the §1202 exclusion available at execution vs. settlement.
- **State tax** — the state-residence treatment of the taxable event and any state-timing considerations.
- **Withholding** — for direct-sale forwards, none (the shareholder is responsible for their own estimated-tax); for loan structures, none unless the loan is recharacterised.
- **Recommendation** — a specific tax-optimising sequence or structure choice, subject to counsel confirmation.

### 8. Draft the risk-and-decision memo

Author a 6–8 page memo suitable for the shareholder's personal tax and legal advisors, covering:

- Shareholder-and-need baseline.
- Instrument comparison across the three options.
- Recommended instrument with defence.
- Counterparty selection with defence.
- §1259 and §1202 analysis.
- Downside scenarios and their handling.
- Recommended execute-or-decline decision, with the specific conditions under which the recommendation would change.

## Starter guidance

Common structured-secondary evaluation errors to avoid:

- **Treating the forward-contract structure as tax deferral without §1259 analysis.** A high-advance fixed-share forward with no offsetting variable-delivery component is usually a §1259 constructive sale — gain is recognised at execution, not at settlement. The deferral the shareholder often hopes to achieve does not survive.
- **Ignoring the counterparty-credit risk.** A forward-contract counterparty that fails between execution and settlement leaves the shareholder as an unsecured creditor for the residual settlement payment. The shareholder's due diligence on the counterparty's capitalisation, funding, and reputation is the critical risk mitigant.
- **Underestimating the interest burden on collateralised loans.** A 12% PIK-accruing rate over 5 years compounds materially — the loan basis at maturity can be well above the initial advance, consuming a large fraction of the retained-upside promise. Model the accrued interest before signing.
- **Assuming the target's ROFR does not apply.** Some target agreements' ROFR provisions capture economic-transfer transactions even where record ownership does not change; the specific ROFR / co-sale agreement must be read against the specific instrument.
- **Focusing on cash-today at the expense of retained-upside.** A shareholder who takes 70% of fair value today at the cost of forfeiting 4×+ upside if the target hits a plausible exit has usually made a poor trade unless the immediate need is genuinely urgent.
- **Ignoring the §1202 timing implication.** For a §1202-qualifying position not yet at the 5-year mark, a structure choice that triggers recognition at execution can forfeit an exclusion worth $10M+ in federal tax. The 5-year clock is worth waiting for whenever the shareholder's circumstances permit.
- **Trusting a counterparty's proprietary pricing methodology at face value.** Structured-secondary pricing is opaque; the shareholder's advisor should benchmark the counterparty's offered advance rate and interest rate against comparable transactions and against the target's current 409A + secondary-market clearing observations.

## Acceptance criteria

You can demonstrate that:

- Shareholder-and-need baseline is written with §1202 posture, alternative direct-sale option, and time horizon.
- Three instruments are each evaluated with specific proposed terms (advance rate, interest rate, forward price, upfront advance, settlement date).
- §1259 constructive-sale analysis is completed for each instrument with a specific risk read.
- §1202 QSBS interaction is analysed for each instrument with the specific exclusion available under each timing scenario.
- Instrument comparison matrix ranks the three across at least ten dimensions.
- Recommended instrument is selected with a defence against the two rejected alternatives.
- Counterparty is selected from the chapter-4 landscape with a defence and a counterparty-credit-risk mitigant analysis.
- Tax analysis is drafted at 2–3 pages with federal, state, and timing analysis.
- Risk-and-decision memo is drafted at 6–8 pages.

## Reflection

Add a short reflection:

1. Where did the §1259 constructive-sale analysis force a structure change you would not otherwise have made, and what does that tell you about the specific limits of forward-contract tax-deferral planning?
2. If the shareholder's §1202 5-year mark was 6 months away, would you delay the direct sale that long or execute the structured secondary now? What would tip the decision?
3. Which counterparty-credit-risk mitigant (collateral, custody escrow, third-party settlement agent, or diversification across multiple counterparties) would you insist on before signing, and what specific failure mode does it address?
4. What is the single question you would insist the shareholder's personal tax counsel confirm before you would approve the instrument?

## Stretch goals

- **Bilateral-negotiation role-play.** Draft the specific counter-offer letter the shareholder's advisor would send back to Setter Capital (or the chosen counterparty) with proposed changes to the advance rate, interest rate, and covenant terms.
- **Multi-counterparty sourcing.** Solicit proposals (in simulation) from three counterparties for the same instrument and shareholder facts, and compare the specific terms. Model the negotiation leverage the multi-counterparty solicitation creates.
- **§1259 depth-analysis.** Read the Treasury regulations and IRS guidance on §1259 in detail and draft the specific tax opinion the counterparty's counsel would deliver for the recommended structure.
- **Full instrument-payoff modelling.** Build a spreadsheet or notebook that models the shareholder's after-tax net proceeds under each instrument across a distribution of exit valuations (from below the preference stack through 10× current implied valuation) and computes the probability-weighted expected value.
- **Comparable-transaction sourcing.** Research publicly-observable structured-secondary transactions (rare in the private-company context, more common in the public-company post-lockup context) and compare their terms against the proposed instrument.
- **Private-banking client-onboarding path.** If the shareholder does not currently have a private-banking relationship with one of the large financial-services firms, work through the onboarding path — what asset-under-management threshold, what relationship-establishment timeline, what documentation — and factor that into the counterparty-selection decision.
