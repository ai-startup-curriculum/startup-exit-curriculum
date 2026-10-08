# exercise-03: Rule 10b5-1 Trading Plan Authoring Drill

**Estimated effort:** 3 hours

## Objective

Author a specific, defensible Rule 10b5-1 trading plan for a newly-public founder (your frozen fact pattern from exercise-01 if the exit is an IPO, or a realistic IPO fact pattern you build for this exercise if your exercise-01 fact pattern is M&A), together with the specific adoption-and-approval choreography that would get the plan reviewed by issuer counsel and approved by the audit committee. By the end of the exercise you should be able to defend each plan-design decision against the SEC 2023-amendment requirements, the plaintiffs'-bar scrutiny that follows 10b5-1 disclosures, and the issuer-level insider-trading-policy constraints that overlay the federal rule.

## Background

This exercise covers material from:

- [Chapter 3 — Rule 10b5-1 Trading Plans](../03-rule-10b5-1-trading-plans.md)
- Dependencies on [Chapter 1 — IRC §1202 QSBS Fundamentals](../01-irc-1202-qsbs-fundamentals.md) (for the QSBS-aware tranche selection) and interaction with [Chapter 4 — Post-Lockup Diversification](../04-post-lockup-diversification.md) and the exercise-04 diversification plan.

This exercise applies only to founders whose exit is a public-company situation — an IPO (with a lock-up expiry) or an insider position at an already-public company. For founders whose exit is a strictly-private M&A cash-out, this exercise is optional context.

## Prerequisites

- The frozen personal fact-pattern profile from exercise-01, with specific adaptation for a public-company scenario if your exercise-01 fact pattern is M&A.
- Access to primary sources: 17 CFR §240.10b5-1 (the amended rule), the SEC's 2022 adopting release (SEC Release No. 33-11138, December 14, 2022), 17 CFR §229.408 (Item 408 of Regulation S-K), 17 CFR §230.144 (Rule 144 safe harbour), Section 16 of the Securities Exchange Act, and 17 CFR §240.16a-1 et seq.
- The frozen issuer's expected or actual IPO lock-up terms (period, staggered-release pattern, early-release provisions, carve-outs).
- The frozen issuer's draft or final insider-trading policy and any defined open-trading-window schedule.
- Access to specific recent 10b5-1 plan disclosures from Form 10-Q filings by comparable newly-public issuers via SEC EDGAR (specifically Item 408(a) disclosures) for benchmarking.

## Tasks

### 1. The founder-insider profile

Author a one-page insider profile at the top of your working document. Include:

- **Insider classification.** Section 16 officer, director, both, or neither. Section-16 status determines the 90-day cooling-off, the Form 4 disclosure cadence, and the Section 16(b) short-swing-profit matching exposure.
- **Position summary.** Specific share count held personally, specific share count held in grantor trusts (flow-through, counted as the founder's for §16 and 10b5-1 purposes), specific share count held in non-grantor trusts (potentially separate persons for §16 purposes depending on attribution; specific securities-counsel review required).
- **QSBS-tranche overlay.** From exercise-01, which tranches are QSBS-eligible (and within cap) and which are not. The 10b5-1 plan will sequence sales to capture §1202 treatment where it applies.
- **Stacking-plan overlay.** From exercise-02, which blocks of QSBS have been transferred to which non-grantor trusts. Each trust holding Section-16-attributable stock may need its own 10b5-1 plan.
- **Lock-up terms.** Specific lock-up period (180 days standard, or a specific staggered pattern), specific lock-up expiry date, specific early-release provisions (if any), specific carve-outs the founder qualifies for.
- **Expected earnings calendar.** Specific projected quarterly earnings release dates for the first 4–8 quarters post-IPO. Important for the 90/2-business-days-after-earnings cooling-off calculation.
- **Existing or prior 10b5-1 plans.** Any plan currently in effect; any plan terminated in the past year; any single-trade-plan execution in the past 12 months. These affect the no-overlapping-plans and the single-trade-per-12-months restrictions.
- **Insider-trading-policy constraints.** Issuer's defined open-trading windows, blackout periods, event-driven blackout triggers, and audit-committee-approval requirements.

### 2. The sale-objective definition

Define the specific objective of the 10b5-1 plan in specific, measurable terms. Candidates:

- **Diversification-driven sale.** Sell to reduce concentration from X% to Y% of net worth over a specific horizon.
- **Dollar-target sale.** Sell to achieve a specific dollar amount (for a specific life-goal: home purchase, estate-plan gift, philanthropic commitment, retirement funding).
- **Share-count-target sale.** Sell a specific aggregate share count over the plan horizon.
- **Hybrid.** Combination of a base diversification schedule plus upside-triggered sales at specific price levels.

For the chosen objective, specify:

- **Sale horizon.** 12 months, 18 months, 24 months, 36 months. Choose and justify.
- **Sale pace.** Fixed cadence (monthly, quarterly), volume-participation (percentage of daily trading volume), hybrid.
- **Tax-aware tranche sequencing.** For the §1202-eligible-within-cap portion, prioritise early sales (the federal tax is $0 on the excluded portion). For above-cap portions, consider whether to sell before or after charitable-vehicle contributions (exercise 05) that could offset the tax.

### 3. The cooling-off and adoption-window plan

Choose the specific plan-adoption date. The adoption date must be:

- During the issuer's defined open-trading window (outside quarterly earnings blackouts and event-driven blackouts).
- At a time the founder is defensibly not in possession of MNPI. In practice, 1–3 weeks after an earnings release and before the start of the next quarter's blackout.
- Positioned so the cooling-off period (90 days + 2 business days after the earnings release for the quarter of adoption, capped at 120 days total) completes before the intended first trade date.

For the chosen adoption date, compute:

- The specific 90-day post-adoption date.
- The specific 2-business-days-after-next-earnings-release date.
- The specific 120-day cap on the cooling-off.
- The earliest possible first-trade date.

If the lock-up expiration date is later than the earliest-possible-first-trade date, the first trade date is the lock-up expiration (or the first open-window trading day thereafter). If the lock-up expiration date is earlier than the earliest-possible-first-trade date, the first trade date is the earliest-possible-first-trade date.

### 4. The plan-design decisions

Author the specific plan design. For each design element, document the choice and the justification:

**Trade cadence.**

- Regular-cadence fixed-share-count sales (e.g., 10,000 shares on the first trading day of each month for 24 months).
- Regular-cadence fixed-dollar-amount sales (e.g., $500K per month, with the share count determined by the opening price on each trade date).
- Volume-participation formula (e.g., up to 5% of daily reported trading volume, capped at X shares per day).

**Price-condition triggers (optional).**

- Base cadence plus upside-triggered sales: e.g., "Broker may sell up to an additional X shares on any trading day when the prior-day's closing price was at or above $Y."
- Downside-protection sales: e.g., "Broker shall sell X shares on any trading day when the prior-day's closing price is at or below $Z" (relatively uncommon; usually a sign the plan has an opportunistic structure).
- Multi-tier triggers: e.g., "First tier at $Y, second tier at $Y+Δ, each with incremental share-count limits."

**Event-triggered pauses.**

- Automatic pause during the issuer's standard quarterly blackout periods.
- Automatic pause during specific event-driven blackouts triggered by the issuer's insider-trading-policy administrator.
- Pause-and-resume mechanics specified in the plan to operate without insider or broker discretion.

**Volume limits and Rule 144 compliance.**

- Explicit volume caps per 3-month period reflecting the Rule 144 greater-of-1%-of-outstanding-or-average-weekly-volume limit for affiliates.
- Form 144 filing responsibilities (typically the broker's responsibility under the plan; confirm with the broker).

**Termination provisions.**

- Specific plan end date (e.g., 24 months after the first trade date, or on completion of a defined aggregate sale amount).
- Termination on specific events (change of control of the issuer, insider's death or incapacity).
- Termination at the insider's discretion is heavily disfavoured — if included at all, document the specific permitted-reason categories (specific-estate-planning event, specific-health event).

**Modification provisions.**

- The plan should be hard to modify. Modifications trigger a new cooling-off period and are disclosed in the next Form 10-Q. Document the specific permitted-modification-reasons (which should be narrow).

### 5. The audit-committee-approval process

Author the specific choreography for getting the plan approved by the audit committee (or the committee the issuer's insider-trading policy designates):

- **Pre-committee review.** Issuer securities counsel reviews the draft plan for compliance with the amended Rule 10b5-1 and with the issuer's insider-trading policy. Personal securities counsel for the insider reviews the plan for the insider's interests. Both reviews complete before committee presentation.
- **Committee presentation.** Specific agenda for the committee meeting — summary of the plan terms, confirmation of adoption-window timing, confirmation of no-MNPI representation, review of self-certification language, review of disclosure obligations under Item 408(a).
- **Committee resolution.** Draft resolution the committee adopts approving the plan. Includes specific findings on no-MNPI-at-adoption, good-faith adoption, and compliance with the issuer's insider-trading policy.
- **Documentation record.** Specific documents preserved: the plan document, the self-certification, the committee resolution, the pre-adoption-MNPI-review record. Specify where the record is maintained (issuer's legal file, insider's personal file, broker's compliance file).

### 6. The broker-selection and plan-administration decision

Choose the specific broker that will administer the plan. Options:

- **Issuer's stock-plan-administration broker.** The broker that administers the issuer's RSU-vesting-and-stock-plan services (Fidelity, Morgan Stanley at Work, E*TRADE Corporate Services, Charles Schwab Stock Plan Services, or similar). Convenience and integration with the sell-to-cover plans.
- **Personal-brokerage broker.** The insider's personal wealth-manager's broker-dealer (if the insider has one). Potentially better integration with the insider's broader wealth-planning arc.
- **Specialised 10b5-1 broker.** Firms specialising in insider-plan administration (various major broker-dealers have specialised practices).

For the chosen broker, document the specific fee structure, the specific execution-quality metrics (price-improvement data, VWAP comparison), the specific Rule 144 compliance mechanics (who files Form 144, who manages the volume limits), and the specific coordination with the issuer's insider-trading-policy administrator.

### 7. The Item 408(a) disclosure draft

Draft the specific Item 408(a) disclosure that would appear in the issuer's next Form 10-Q covering the plan adoption. The disclosure must include:

- The insider's name and title.
- The plan adoption date.
- The plan duration (specific end date or expected end-of-plan event).
- The aggregate number of securities subject to the plan.

Note that individual trade prices are not required to be disclosed under Item 408(a) — only the aggregate plan terms.

Compare your draft against actual Item 408(a) disclosures from recent Form 10-Q filings by comparable issuers (EDGAR search). Match the style and specificity.

### 8. The lock-up-interaction plan

Specify how the 10b5-1 plan interacts with the lock-up:

- **Plan adopted during lock-up.** The plan can be adopted during the lock-up (the lock-up bars sales, not plan adoption) with the first-trade date set to the day after lock-up expiration (or later if the 10b5-1 cooling-off period runs past that).
- **Staggered-release interaction.** If the lock-up has a staggered-release pattern (e.g., 25% released at day 90 if a price condition is met, balance at day 180), the plan's trade schedule can be structured to match. Specify the plan's share-availability schedule to track the lock-up release milestones.
- **Early-release trigger interaction.** If the lock-up has an early-release provision, the plan should include a conditional first-trade date that triggers on either the scheduled release or the early-release event, whichever is earlier.
- **Trust-level lock-up.** If exercise-02's stacking plan transferred QSBS to non-grantor trusts before the IPO, the trusts are typically bound by the same lock-up as the founder. The trusts' separate 10b5-1 plans (if applicable) must satisfy the lock-up as well.

### 9. The Section 16 and short-swing-profit coordination

For Section 16 insiders:

- **Form 4 filing cadence.** Form 4 for each plan trade is due within 2 business days of execution. Confirm the broker's Form 4 filing capability and workflow.
- **Section 16(b) short-swing-profit matching.** Any purchase of issuer stock within 6 months before or after a plan sale is matched for short-swing-profit purposes. Common purchases: RSU vesting (treated as acquisition at FMV on delivery), ESPP purchases, option exercises. Model the specific 6-month windows around each plan sale date and identify any potential short-swing exposure.
- **Pre-emptive 6-month-planning.** If the plan is scheduled to begin sales 90 days after the lock-up expiry and RSU vesting events are scheduled 60 days into the plan, the vesting events would match against sales within the subsequent 6 months. Design around this by adjusting the plan start date, the sale schedule, or (if specifically needed) by deferring the sale schedule until a clean 6-month window is available after the last planned acquisition.

### 10. The personal-counsel engagement plan

Document the specific personal-counsel engagement for the plan:

- **Counsel identification.** Specific attorney (name of firm, specific partner's name) retained as the insider's personal securities counsel. See chapter 7's specialist-selection discipline.
- **Scope of engagement.** Review of the plan document, review of the self-certification, review of the committee-approval resolution, review of the broker engagement, ongoing compliance support.
- **Fee structure.** Hourly or flat-fee engagement; typical cost $25K–$75K for a first-plan engagement, with ongoing retainer or hourly for post-adoption support.
- **Coordination with issuer counsel.** Specific communication protocol between the insider's personal counsel and the issuer's securities counsel.

## Starter guidance

Three anti-patterns to avoid:

- **The "adopt the week before earnings" trap.** Adopting the plan immediately before an unannounced earnings surprise puts the insider in an awkward position — the SEC and plaintiffs' counsel will examine whether the insider knew of the pending release at adoption. The clean adoption window is 1–3 weeks after an earnings release and before the start of the next quarter's blackout.
- **The "single large trade on a specific future date" plan.** A plan that specifies one large trade on a specific future date is a single-trade plan under the amended rule. Single-trade plans are limited to one per 12-month period and face sharper scrutiny. For most founders, a multi-trade plan with a regular cadence is both less limited and more defensible.
- **The "I'll just terminate if the market moves against me" fallback.** Termination of a plan is heavily disfavoured. A plan that terminates immediately before a material adverse event, or that is repeatedly adopted-and-terminated, loses the affirmative defence. Plans should be designed to run to completion through market volatility, not to be modified or terminated opportunistically.

## Acceptance criteria

You can demonstrate that:

- The founder-insider profile is specific across Section-16 status, QSBS overlay, stacking overlay, lock-up terms, earnings calendar, prior-plans, and insider-trading-policy constraints.
- The sale objective is specific in dollars or share count, with a specific horizon and tax-aware tranche sequencing.
- The cooling-off calculation is specific — adoption date, 90-day date, 2-business-days-after-earnings date, 120-day cap, earliest-first-trade date.
- The plan-design decisions are specific — cadence, price triggers (if any), event-pauses, volume limits, Rule 144 compliance, termination and modification provisions.
- The audit-committee-approval choreography is specific — pre-review, agenda, resolution, documentation record.
- The broker selection decision is specific with fee structure, execution-quality metrics, and coordination mechanics.
- The Item 408(a) disclosure draft matches the style of recent comparable disclosures from EDGAR.
- The lock-up-interaction plan accounts for the specific lock-up terms, staggered releases, and early-release provisions.
- The Section 16 coordination identifies specific 6-month-matching windows and specific adjustments to avoid short-swing exposure.
- The personal-counsel engagement plan is specific on counsel identification, scope, fees, and coordination with issuer counsel.
- A critical reader (an issuer's securities counsel, a personal-securities-counsel partner, a plaintiffs'-bar monitor) can test each decision and find it defensible.

## Reflection

Add a short reflection (½ page):

1. Which plan-design decision is most likely to be challenged by plaintiffs' counsel if the stock subsequently has a sharp decline, and what is your specific defence?
2. If the earnings calendar shifts after the plan is adopted (e.g., earnings released 2 weeks earlier than expected), how does the plan handle the shift? Which specific plan-document provisions preserve the plan's integrity?
3. If a specific material corporate event occurs during the plan's life (acquisition offer, major product issue, regulatory action), what specific plan-document mechanics govern pausing or terminating the plan without compromising the affirmative defence?

## Stretch goals

- **Comparable-plan benchmark.** Pick 3–5 recent Item 408(a) disclosures from newly-public comparable issuers (within the past 2 years) and reverse-engineer the plan designs (where disclosed). What specific-plan structures are the market standard? Where does your draft plan differ, and why?
- **Trust-level 10b5-1 plan design.** For a stacking plan from exercise-02, design the specific 10b5-1 plans for the non-grantor trusts that hold Section-16-attributable stock. Address the specific attribution rules, the trust-level cooling-off, the trust-level audit-committee-approval, and the trust-level Item 408(a) disclosure.
- **Multi-year plan sequencing.** For a founder with a 36-month expected diversification horizon, design the specific sequence of two or more consecutive 10b5-1 plans with the no-overlapping-plans compliance. What specific gaps between plans are required? What specific triggers cause the second plan to be adopted during the first plan's execution?
