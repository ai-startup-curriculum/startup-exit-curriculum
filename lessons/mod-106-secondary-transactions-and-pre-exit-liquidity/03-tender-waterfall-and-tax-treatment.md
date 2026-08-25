# Tender Waterfall Analysis and Tax Treatment — Preference Stack, ISO vs. NSO vs. RSU

## Why this matters

The tender-price paper number — "the tender is at $63.75 per share" — is the same for every participating employee. The *economics* of participating are not. An employee holding early-exercised ISO shares held for more than one year past exercise nets a very different after-tax result than an employee tendering shares acquired at the same tender by same-day cashless exercise of NSOs, who nets a different result again than an employee whose RSUs are being settled and immediately tendered. The preference stack layered above the common — the accumulated liquidation preferences of Series Seed through Series D — determines what a *rational* tender price should be for common relative to preferred, and the interaction of that price with the current 409A determines what any specific tax authority is going to treat as the fair-market value of the shares.

A tender that ignores the waterfall and tax layer clears a defensible headline number but leaves participating employees with tax bills they did not anticipate, unequal after-tax outcomes across categorically similar employees, and — in the worst cases — participating employees who owe more in tax withholding than they receive in cash. The company's compensation committee gets a stream of individual inquiries about "why did I only get $63K on a $100K tender." The company's tax function scrambles to produce individualised tax-treatment memos. The next tender is more difficult to run because the workforce has learned the tax mechanics the hard way.

This chapter installs the waterfall-and-tax discipline. It covers the preference-stack analysis that anchors a defensible tender price for common, the four tax-treatment categories a modern tender must handle (already-held common, same-day cashless-exercise NSO, held ISO shares, and RSU-settle-and-tender), and the tax-withholding operational discipline that keeps every participating employee informed of their after-tax result before they submit their election.

> **Reminder: education, not tax advice.** The categories and analyses here are the practitioner framework; individual tax outcomes require personal-tax-advisor analysis and depend on state residence, other-income posture, and (for §1202-eligible shares) the QSBS analysis of mod-103 chapter 8. The company running a tender does not provide personal tax advice; the tender documentation directs participants to their own tax advisors. This chapter installs the vocabulary that lets the tender's designer, the compensation committee, and the participant-education materials cover the necessary ground.

## The waterfall — pricing common under a preference stack

At the tender's design phase, the price for common must be defensible against the current 409A common valuation and — critically — must reflect the reality that common carries no liquidation preference while preferred does. The waterfall analysis is the practitioner tool that translates a preferred-round headline price into a defensible common-price.

### The mechanic

Suppose the target has the following cap structure (illustrative):

- Series D Preferred: 20M shares at $85.00, raised $1.7B, non-participating with 1× liquidation preference.
- Series C Preferred: 15M shares at $45.00, raised $675M, non-participating with 1× liquidation preference.
- Series B Preferred: 10M shares at $18.00, raised $180M, non-participating with 1× liquidation preference.
- Series A Preferred: 8M shares at $6.00, raised $48M, non-participating with 1× liquidation preference.
- Series Seed Preferred: 5M shares at $2.00, raised $10M, non-participating with 1× liquidation preference.
- Common (founder + employee + option pool): 50M shares.

Total liquidation preference stack: $2.613B.

If a hypothetical liquidation event occurred immediately at a valuation equal to the last-round headline (implied $2.55B at $85 × 30M diluted preferred equivalent), the entire proceeds would be consumed by the preference stack and common would receive $0. Common only participates *above* the preference-stack conversion point where preferred converts to common — for non-participating preferred, that is the price at which conversion to common yields more than the preference.

Suppose we run the waterfall at a $10B liquidation:

- Preferred preference stack payout: $2.613B (paid first, if preferred takes preference; or preferred converts to common if conversion yields more).
- At $10B: preferred would take preference and receive $2.613B; the remaining $7.387B would go to common's 50M shares = $147.74/share for common.
- Or preferred converts. At $10B, if all preferred converts, the total shares outstanding become 108M (58M preferred + 50M common). Each share receives $10B / 108M = $92.59/share. Preferred converts if the conversion payout exceeds their preference payout — for Series D at $85, they receive $92.59 either way (converted). For Series Seed at $2, they receive $92.59 vs. their $2 preference = converted. For all series, conversion is preferable at $10B.
- So at $10B, all preferred converts; each share (preferred converted to common + common) receives $92.59.

At $10B, common per-share is $92.59 — higher than the current $85 Series D preferred round headline.

At $5B, the analysis is different:

- If preferred takes preference: $2.613B to preferred, $2.387B to common's 50M shares = $47.74/common.
- If all preferred converts to common: $5B / 108M = $46.30 per share.
- Preferred series compare their per-share preference to $46.30. Series D at $85 preference vs. $46.30 converted — Series D takes preference. Series C at $45 vs. $46.30 — Series C converts. Series B at $18 vs. $46.30 — converts. Series A, Seed — convert.
- So at $5B: Series D takes preference for $1.7B; the remaining $3.3B is distributed to the converted-preferred (30M non-D shares) plus common (50M shares) = $3.3B / 80M = $41.25 per share for common (and for the converted preferred).

At $5B: common per-share is $41.25. Well below the $85 Series D preferred price.

The full waterfall analysis produces a curve of common per-share as a function of exit valuation. The tender-price question becomes: **at what exit valuation would common's per-share equal the tender price?** If the answer is a plausible exit valuation, the tender price is defensible; if it requires implausibly high exit valuations, the tender is overpaying for common.

### The 409A-vs-tender-vs-preferred relationship

This waterfall analysis is essentially what an independent 409A appraiser performs — a probability-weighted analysis (Option Pricing Model, Probability-Weighted Expected Return Method) of common under a distribution of possible exit outcomes. The 409A common price is the *time-value-discounted expected value* of common across scenarios; the tender price is a *point-price* the buyer is willing to pay.

Three canonical patterns emerge:

- **Tender at the current 409A common price.** Simplest case — no 409A refresh implication, and the tender-buyer accepts the OPM-derived common price. Typical when the buyer is a company-affiliated repurchase or a routine investor-syndicate tender.
- **Tender at a premium to the 409A common price.** Common at the 409A is $18; the tender is at $28. Two implications: (a) the buyer is signalling that they value common more highly than the OPM baseline (a positive read for the company), and (b) the tender may trigger a 409A refresh at a common price closer to $28 (chapter 8). The compensation committee must be prepared for the ISO-strike-price adjustment consequence.
- **Tender at the preferred price.** Common at 409A is $18; last-round preferred is $85; tender is at $85. This is the most aggressive pricing and effectively treats common as worth the same as preferred at the transaction date. The 409A refresh implication is significant — the common price would likely reset to substantially higher, driving up subsequent ISO strike prices materially. The compensation committee must weigh the tender-participant benefit against the future-grant impact.

## The four tax-treatment categories in a modern tender

At the participant level, the tax treatment of a tender depends on how the participant acquired their shares and how long they have held them. Four canonical categories:

### Category 1 — Already-held common shares (long-term)

The participant holds vested common shares that they acquired more than one year ago via ISO exercise, NSO exercise, or restricted-stock grant. At the tender:

- **Federal**: long-term capital gains on (tender price − basis). Top rate 20% + 3.8% NIIT for high-income participants.
- **State**: state capital-gains treatment (varies by state; California treats capital gains as ordinary income at 13.3% top rate).
- **§1202 QSBS**: if the shares are §1202-qualifying and the 5-year holding period has been met, up to $10M (or 10× basis) of the federal LTCG is excluded (mod-103 chapter 8). California and Pennsylvania do not conform.
- **Withholding**: no employer withholding (this is capital gains on already-held stock, not compensation). Participant is responsible for their own estimated-tax payments.

Practitioner discipline: the tender documentation should identify participants likely holding §1202-qualifying shares and prompt them to consult their tax advisor about the exclusion. Some tender-offer administrators (Carta especially) can compute a per-participant estimated QSBS eligibility based on the grant record.

### Category 2 — Same-day cashless exercise of NSOs

The participant holds vested but unexercised non-qualified stock options and elects to exercise them at the tender window with the exercise cost netted from the tender proceeds. At the tender:

- **Ordinary compensation**: the spread between the tender price and the exercise price is treated as **ordinary compensation** income under IRC §83. If the participant's option strike is $18 and the tender price is $63.75, the $45.75 per-share spread is ordinary compensation.
- **Employer withholding**: the company is required to withhold **federal income tax at the supplemental-wage rate** (currently 22% up to $1M, 37% above $1M), **FICA (Social Security up to the wage base and Medicare 1.45%, plus additional Medicare 0.9% above $200K)**, and **state income tax** at the participant's residence rate. The withholding is deducted from the tender proceeds; the participant receives net cash.
- **Capital gain**: no capital gain (the shares were acquired at the tender window and sold at the tender window; there is no gain over the immediately-acquired-and-sold basis).
- **W-2 reporting**: the ordinary compensation is added to the participant's W-2 for the year.

Concrete calculation. A participant tenders 10,000 same-day-exercised NSOs. Exercise price $18. Tender price $63.75. Spread per share = $45.75.

- Total spread = 10,000 × $45.75 = $457,500 (ordinary income).
- Federal supplemental withholding at 22% = $100,650.
- FICA withholding (assuming already over wage base for SS; Medicare only) at 1.45% + 0.9% (above $200K) = $10,751.
- State (assume 10%) = $45,750.
- Exercise cost = 10,000 × $18 = $180,000.
- Gross tender proceeds = 10,000 × $63.75 = $637,500.
- Net to participant = $637,500 − $180,000 (exercise) − $100,650 (federal) − $10,751 (FICA) − $45,750 (state) = $300,349.

The participant has a $457,500 income event but $300,349 in cash. If the 22% supplemental rate under-withholds relative to the participant's true marginal rate (as it will for high-income participants), the participant will owe additional tax at filing time and should reserve accordingly.

Practitioner discipline: the tender documentation must provide a per-participant estimated-tax breakout that shows gross proceeds, exercise cost, withholding, and net cash *before* the participant elects. Otherwise the participant tenders expecting one number and receives a materially different amount.

### Category 3 — ISO shares held long enough for LTCG (ISO qualifying disposition)

The participant exercised ISOs at some prior date, held the resulting common shares for the required ISO holding period (at least 2 years from the grant date and 1 year from the exercise date, per IRC §422), and now tenders. At the tender:

- **Long-term capital gains**: (tender price − exercise price) is treated as **long-term capital gain**. Top rate 20% + 3.8% NIIT.
- **AMT reconciliation**: at the ISO exercise date, the participant may have had an AMT preference item for the spread between exercise and fair market value. If AMT was paid at exercise, an AMT credit may be available and applied at the tender date. This is a personal-tax-return matter, not a company-withholding matter.
- **Employer withholding**: none — a qualifying disposition of ISO shares is not compensation income. Participant is responsible for their own estimated-tax payments.
- **§1202 interaction**: qualifying ISO shares can also be §1202-qualifying (they were acquired at exercise, which is treated as a "purchase" for §1202 purposes if the exercise price was paid; the 5-year §1202 hold runs from exercise date). Interaction with the ISO 2-year-from-grant hold: for a participant who exercised early (before the grant's 2-year mark), the §1202 clock starts at exercise, not at grant, so the 5-year §1202 hold may be met before the 2-year-from-grant ISO qualifying-disposition hold.

Same 10,000-share example, but with an ISO qualifying disposition:

- Total gain = 10,000 × ($63.75 − $18) = $457,500 (long-term capital gain).
- Federal LTCG at 20% + NIIT 3.8% = $108,833.
- State (assume 10%) = $45,750.
- Total tax = $154,583.
- Gross tender proceeds = $637,500.
- Exercise cost = $180,000 (already paid at ISO exercise).
- Net cash proceeds at tender = $637,500 (no exercise deduction, no withholding — this is capital gains).
- Estimated tax owed at filing = $154,583.
- Net after-tax cash = $637,500 − $154,583 = $482,917.

The ISO qualifying-disposition path yields **$182,568 more** ($482,917 vs. $300,349) than the same-day-cashless-NSO path for the same 10,000 shares, purely from tax treatment. The trade-off: the ISO qualifying-disposition requires the participant to have exercised earlier (paying the cash exercise cost and the AMT if applicable) and to have held long enough. Many employees do not have the cash to exercise earlier and cannot access this path.

For companies designing a tender at a specific point in employee-development, the pattern is: employees who took the risk of early exercise and have held their shares tend to net materially more per-tender than employees exercising same-day. Explaining this asymmetry in the tender documentation is standard practice — some employees will read the tender as unfair until they understand the tax mechanics.

### Category 4 — RSU-settle-and-tender

The participant holds vested-but-unsettled RSUs (service-based vesting complete; liquidity-event trigger not yet met). The tender itself is structured to satisfy the RSU liquidity-event trigger, settling the RSUs into common shares at the tender record date and permitting participation.

- **Ordinary compensation**: the fair market value at settlement — which the tender price defines — is treated as **ordinary compensation** at settlement. If the RSU vests-and-settles at the tender window at $63.75/share, the $63.75/share is ordinary compensation on the settled shares.
- **Employer withholding**: federal (22% supplemental), FICA, state — as with same-day NSO exercise. Withheld from tender proceeds; participant receives net cash.
- **Capital gain**: no capital gain (settled and sold immediately at the same price).
- **W-2 reporting**: the settlement value is reported as W-2 wages.

The tax treatment closely resembles the same-day cashless NSO exercise, except that there is no "spread" — the entire FMV at settlement is compensation, because the participant did not pay an exercise price. For a 10,000-RSU tender at $63.75:

- Total ordinary income = 10,000 × $63.75 = $637,500.
- Federal supplemental at 22% = $140,250.
- FICA (Medicare only, above wage base) = $14,981.
- State at 10% = $63,750.
- Gross proceeds = $637,500.
- Net cash = $637,500 − $140,250 − $14,981 − $63,750 = $418,519.

Note that RSU settlement yields more cash than same-day NSO exercise (because there is no exercise cost) but is fully taxable as compensation, whereas held ISO shares tender cleanly at LTCG rates.

### The instrument-mix implication

A well-designed tender must be capable of handling all four categories at the participant level. The participant-education materials must explain the four categories and the specific tax treatment each triggers. The tender administrator's platform must compute the per-participant estimated tax, based on the participant's specific share-lot inventory, and present the net-cash outcome before the participant elects.

Some tenders offer a **hybrid participation election**: the participant can tender specific-lot shares (early-exercised ISOs) at one tax treatment and same-day-exercise other options at a second tax treatment, all within the tender window. The tax outcomes are aggregated at the individual level and reported at close.

## The specific §1202 QSBS interaction

For participants whose shares are §1202-qualifying (mod-103 chapter 8), the tender can be one of the most tax-efficient exit paths available — potentially zero federal tax on up to $10M of gain per participant per issuer.

The tender-design implications:

- **Identify §1202-qualifying holders in advance.** The company can compute (or Carta can compute) which participants likely hold §1202-qualifying shares based on original-issuance dates. The tender documentation should call out §1202 eligibility for these participants and encourage them to consult their tax advisor.
- **Preserve the holding-period discipline.** A participant whose §1202 5-year hold matures in 2024-11-15 should not tender in a 2024-09 tender if avoidable — sequencing the tender window after the participant's holding-period anniversary preserves the exclusion.
- **The company's 409A analyst may compute per-participant §1202 impacts.** Carta and NPM increasingly offer per-participant §1202 exclusion estimates in tender-offer education materials. This shifts the participant's decision from a "should I tender" question to a "how many shares, of which lots, at which timing" question.

The QSBS interaction is not a tender-design decision — the tender doesn't itself create QSBS eligibility, and a tender that overprices common relative to preferred does not enhance §1202 economics (the exclusion cap is $10M regardless). But the *communication* of §1202 eligibility to potentially-eligible participants can materially reshape participation and after-tax outcomes.

## Multi-jurisdictional workforce complications

For companies with employees resident in multiple jurisdictions — a common pattern for growth-stage software companies — the tender must handle multi-state and multi-country tax withholding correctly.

- **US multi-state**: state withholding at the participant's state of residence (not the company's state). California-resident employees have California withholding; Texas-resident employees have no state withholding. Companies typically administer this through their payroll platform's multi-state configuration.
- **US-employer / non-US-employee**: for a US-domiciled company with employees who have moved abroad, the tax treatment depends on the employee's tax residency, the specific bilateral tax treaty (US-UK, US-Canada, US-Australia, US-Germany, US-Ireland), and whether the equity was granted before or after the employee's expatriation. This is one of the operationally hardest tender-execution scenarios; specialist expat-tax counsel is typically engaged for participants in this category.
- **Non-US-employer / non-US-employee**: for a non-US-domiciled parent (e.g., a Cayman-parented growth-stage company) with employees in multiple countries, each country's local tax treatment applies. Some tenders exclude non-US employees for operational simplicity; others structure a specific per-country tender addendum.

Multi-jurisdictional complications are one of the reasons many tenders are announced 4–6 weeks in advance rather than 2–3 weeks: the operational lead time for confirming multi-country withholding through the payroll and administrator platforms is significant.

## Summary

The waterfall-and-tax layer of a tender translates a headline tender price into per-participant after-tax outcomes that differ materially by share category. The waterfall analysis anchors the defensible per-share common price against the preference stack, sets up the 409A-vs-tender-vs-preferred comparison, and drives the 409A-refresh implication of the tender. The four tax-treatment categories — already-held long-term common, same-day cashless NSO exercise, held ISO qualifying disposition, and RSU settle-and-tender — carry sharply different withholding, ordinary-vs-capital, and after-tax outcomes for participants nominally receiving the same headline number. Practitioner discipline requires the tender documentation to compute the per-participant estimated after-tax number in advance, to call out §1202 QSBS eligibility for potentially-eligible participants, and to handle multi-jurisdictional employees through specialist tax and payroll coordination. Chapter 4 turns to the structured-secondary and forward-contract alternatives that operate outside the tender-offer mechanic altogether.
