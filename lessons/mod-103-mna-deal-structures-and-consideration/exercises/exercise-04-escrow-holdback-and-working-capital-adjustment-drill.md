# exercise-04: Escrow, Holdback, and Working-Capital-Adjustment Drill

**Estimated effort:** 3.5 hours

## Objective

For a specific transaction with a documented risk profile, size the escrow (general-indemnity + specific-indemnity), design the survival periods and release mechanics, draft the working-capital-adjustment definition and true-up, and reconcile the whole stack with R&W insurance. Benchmark your design against ABA Deal Points Study and SRS Acquiom market data. By the end you should have a defensible escrow-and-adjustment design that you could hand to sell-side counsel as a first-draft position, and you should be able to explain to your board why the escrow terms give up an acceptable amount of shareholder-close cash for an acceptable degree of buyer protection.

## Background

This exercise covers material from:

- [Chapter 4 — Escrow, Holdback, and Working-Capital-Adjustment Mechanics](../04-escrow-holdback-working-capital.md)

Chapter 2 (consideration mix) provides the closing-consideration frame; escrow reduces the closing cash to shareholders. Chapter 3 (earn-out) uses similar deferred-payment mechanics; some of the same drafting principles apply.

## Prerequisites

- You have read chapter 4 in full.
- Access to the ABA Deal Points Studies (Private Target M&A) and SRS Acquiom M&A Deal Terms Study (see resources.md). Even the summary excerpts / press releases are useful for the market ranges.
- Optional: familiarity with R&W insurance policy structure (Marsh, Aon, Willis Towers Watson primers on their websites).

## The fact pattern

**Target:** Delaware C-corp, developer of enterprise workflow software with $42M ARR. 8 years old. Series A/B/C preferred with $110M preference stack.

**Acquirer:** Publicly-traded strategic, $12B market cap. Prior M&A history includes 6 acquisitions in the last 5 years.

**Headline:** $260M all-cash purchase price. Closing expected 4 months after signing (HSR clearance + customary closing conditions).

**Risk profile from diligence (buyer's view):**
- **IP.** One pending patent-infringement letter received 4 months pre-signing from a competitor; target's IP counsel has responded but no litigation filed. Buyer's IP counsel believes claim has "some merit" and estimates $2–8M potential exposure.
- **Tax.** State-nexus questions across 8 states where target has remote employees; buyer's tax diligence estimates $500k–$1.5M potential exposure. R&D credit position has some documentation gaps.
- **Employee benefits.** Two former employees terminated in the last 12 months with severance packages; no current claims but a residual risk.
- **Customer contracts.** Two of the top 10 customers have change-of-control consent rights; consent expected but not yet obtained at LOI signing.
- **General business.** No known other material issues.

**R&W insurance market signal:** initial broker feedback suggests policy limit of $25M (roughly 10% of enterprise value), with the pending IP-infringement letter *excluded* from the policy (the underwriter will not underwrite a known potential claim). Retention (self-insured amount) expected at ~$1.5M-$2M (roughly 0.5-0.75% of enterprise value). Policy pricing expected at approximately 3–4% of the policy limit.

## Tasks

### 1. Size the general-indemnity escrow

Benchmark against ABA Deal Points Study and SRS Acquiom data (chapter 4):

- **Range.** Long-run median 5–10% of purchase price; range 2.5–15%. With R&W insurance in place, escrow sizes have generally decreased in recent years.
- **Your proposed size.** As a percentage of purchase price, and as a dollar number.
- **Rationale.** Given the R&W insurance is expected to be in place (with the IP-letter carve-out and known retention), the escrow can be smaller than the historic 8% median. Where does your number fall relative to the benchmark, and why?
- **Denomination.** Cash from the closing consideration; held with independent escrow agent (SRS Acquiom / Wilmington Trust / JPMorgan / Citi). Note your preferred agent.

Write a ½-page general-escrow sizing memo including the benchmark citation, your proposed size, and the specific rationale.

### 2. Design the specific-indemnity holdbacks

For each of the specific diligence risks (IP letter, tax nexus, R&D credit, employee-benefit), decide whether to structure a specific holdback separate from the general-indemnity escrow.

- **IP letter.** The R&W insurer has carved this out; is a specific holdback appropriate? At what dollar amount (given the estimated $2-8M exposure)? Held for what survival period (typically tied to the resolution of the underlying claim)?
- **Tax nexus / R&D credit.** A specific tax holdback might be appropriate given the identified exposure. Structure? Sized at what?
- **Employee benefits.** Specific holdback or leave to general indemnity?
- **Customer-consent risk.** Specific closing condition or holdback treatment? (Note: this is often handled as a closing condition rather than post-close holdback.)

For each specific holdback, draft a 1-paragraph specification: dollar amount, escrow account type, release trigger, survival period.

### 3. Design the survival periods

For the general-indemnity escrow:
- Standard survival: how long? Benchmark against ABA (median 12–18 months for general reps).
- **Fundamental reps** (organisation, capitalisation, authority, taxes to some extent, brokers' fees) — survive indefinitely or to statutory limitation period? Standard practice is longer or indefinite.
- **Specific reps** (financial statements, IP, employees) — survive general period, or a longer variant?
- **Tax reps.** Often survive to the applicable statute of limitations for the specific tax period (i.e., through the audit-limitation window).

Draft a survival table:

| Rep category | Survival period | Escrow available for this period? |
|---|---|---|
| Fundamental reps | | |
| Tax reps | | |
| Specific reps (financials, IP, employees, contracts) | | |
| General reps | | |

### 4. Draft the working-capital-adjustment mechanic

**4.1 — Define the working-capital target.**

Working-capital adjustment protects the buyer against a seller's pre-close manipulation of working capital (e.g., delaying customer collections, prepaying vendors) to inflate the closing cash the buyer inherits. The parties agree at signing on a *target* working-capital number based on the target's normal-course working-capital position, and adjust the purchase price up or down based on the difference at closing.

- **Working-capital definition.** Which balance-sheet items? Standard: current assets (excluding cash) minus current liabilities (excluding debt), each with specific carve-outs. Draft the specific formula:
  - Include: accounts receivable, inventory, prepaid expenses, other current assets excluding cash.
  - Exclude: cash and cash equivalents.
  - Include: accounts payable, accrued liabilities, deferred revenue (this is a specific and often-disputed inclusion — check chapter 4 for the deferred-revenue issue).
  - Exclude: debt and debt-like items (treated separately, see 4.2), tax liabilities on the transaction, transaction expenses.
- **Deferred revenue treatment.** For a SaaS company, deferred revenue can be a material working-capital item. Two schools of practice:
  - Include deferred revenue as a current liability that reduces working capital (traditional accounting view).
  - Exclude deferred revenue from the working-capital calculation (SaaS-industry view — deferred revenue represents already-collected cash and is not a "true" working-capital obligation in the same sense as unpaid vendors).
  - Draft your position and justify it.
- **Working-capital target.** A specific dollar number based on the target's average working-capital over a trailing 12-month period, with seasonality adjustments. Compute a plausible target from your fact pattern's context and document your methodology.

**4.2 — Closing cash and closing debt.**

Working-capital adjustment usually pairs with:

- **Closing cash.** The target's cash on hand at closing is transferred to the buyer (or, depending on structure, to a specific paying agent for shareholder distribution). Cash-at-closing is typically dollar-for-dollar adjustable.
- **Closing debt.** The target's debt at closing (funded indebtedness, capital leases, deferred taxes payable at closing, specified debt-like items) is subtracted from the enterprise value to derive the equity value. Draft the specific debt definition.
- **Transaction expenses.** Fees paid at closing (banker fees, legal fees, accounting fees, R&W-insurance premiums) are typically borne by the seller; the enterprise value is adjusted to reflect them.

Draft the "cash-free / debt-free" closing formula:
- Enterprise value = Headline purchase price
- Equity value = Enterprise value + Closing cash - Closing debt - Transaction expenses + (Actual working capital - Target working capital)

Show the formula clearly.

**4.3 — True-up mechanic.**

- **Estimated closing statement.** Seller delivers an estimated statement at closing showing estimated closing cash, closing debt, working capital, and transaction expenses. The estimated adjustment is applied to the purchase price at closing.
- **Final closing statement.** Within a specified period post-close (typically 60–90 days), the buyer delivers a final closing statement. Any difference between estimated and final is trued up in cash.
- **Dispute mechanic.** If the seller disputes the buyer's final statement, dispute-resolution follows a specific process (typically neutral-accountant arbitration limited to the specific line items in dispute).
- **Fees for dispute.** Loser pays, split, or paid by the party whose position was less well-supported?

Draft the true-up clause as it would appear in the SPA (½ page).

### 5. Reconcile with R&W insurance

R&W insurance changes the escrow / indemnification calculus (chapter 4):

- **Traditional structure (no R&W insurance).** Escrow / indemnification is the sole recourse for the buyer on rep breaches. Escrow needs to be sized to cover expected exposure.
- **R&W-insurance structure.** Escrow shrinks (from 8-10% to 0.5-1%, or eliminated); most rep breaches recover from the insurer up to policy limits; the seller has a limited "seller retention" beneath the R&W-policy retention.

For this transaction, the R&W-insurance market signal is a $25M policy limit with $1.5-2M retention and IP-letter exclusion. Design:

- **Escrow with R&W insurance.** A minimal general-indemnity escrow (0.5-1% of purchase price = $1.3-2.6M) to cover the seller's retention *beneath* the R&W policy's retention. This is the "sub-retention" escrow.
- **Specific holdbacks.** For the R&W-excluded IP letter, a specific holdback is essential — the R&W insurer will not cover this, so escrow / indemnification is the buyer's only recourse. Size this against the estimated exposure.
- **Reps that survive R&W policy.** Certain fundamental reps and tax reps may survive the R&W policy or be indemnified separately. Document.
- **R&W-insurance premium allocation.** Who pays — buyer, seller, or split? Typically buyer pays, but seller sometimes contributes as a purchase-price adjustment.

Draft a ½-page R&W-integration memo describing the specific-indemnity holdbacks that fill in the R&W-insurance gaps.

### 6. Model the shareholder impact

Given all of the above, compute:

- **Closing-day cash to shareholders.** Total consideration minus general escrow minus specific holdbacks minus transaction expenses.
- **Escrow / holdback amount** subject to release conditions.
- **Percentage of purchase price** locked up at closing (general + specific).
- **Expected release timing.** When does each escrow / holdback reasonably release?

Show as a table:

| Item | Amount | Held for how long |
|---|---|---|
| Total headline | $260M | |
| Transaction expenses | | at closing |
| Closing cash to shareholders | | at closing |
| General-indemnity escrow | | (target release date) |
| Specific-indemnity: IP holdback | | (target release date) |
| Specific-indemnity: tax holdback | | (target release date) |
| Working-capital true-up | | ~90 days |

### 7. Draft the board memo

Draft a 1-page board memo that:

- States the recommended escrow and holdback structure.
- Benchmarks against ABA Deal Points Study data.
- Shows the closing-day-cash impact to shareholders.
- Names the specific counterparty push-backs you expect and your fallback positions.
- Notes the R&W-insurance economics and who pays.

## Starter guidance

- **Do not oversize the escrow when R&W insurance is in place.** A common negotiation mistake is agreeing to an 8% general escrow in a deal that has R&W insurance — you are paying twice for the same buyer protection. With R&W insurance in place, the general escrow should be minimal (essentially just the sub-retention piece).
- **Deferred revenue is often the biggest single working-capital argument.** For a SaaS target, whether deferred revenue is included in the working-capital calculation can swing the closing-day payout by millions of dollars. The parties should agree in the LOI on the treatment; leaving it to definitive-agreement drafting produces the biggest fights.
- **Specific holdbacks over-inclusive of general escrow are common overkill.** If the IP-infringement risk is separately held back at $8M, the general escrow should not also cover IP-infringement — you get a double-lock. Draft the general escrow to exclude claims subject to specific holdbacks.
- **Working-capital dispute mechanics scope should be narrow.** Neutral-accountant scope for WC disputes should be *limited* to the specific line items in dispute and to accounting-conforming determinations. If the scope opens up broader business-judgment items, the mechanic produces bad outcomes.

## Acceptance criteria

You can demonstrate that:

- General-indemnity escrow is sized and defended against ABA benchmark.
- Specific-indemnity holdbacks are structured for each material diligence risk.
- Survival periods are set for each rep category.
- Working-capital-adjustment mechanic is drafted, including deferred-revenue treatment.
- Closing-cash / closing-debt / transaction-expense treatment is specified.
- R&W-insurance interaction is reconciled with the escrow structure.
- Shareholder-impact table shows closing-day cash and lock-up amounts.
- Board memo is 1 page and would be presentable.

## Reflection

Add a short reflection:

1. If the R&W-insurance market re-priced from 3-4% to 5-6% between LOI and signing, would the economics still favor the R&W-plus-thin-escrow structure over a traditional larger-escrow structure? At what R&W-pricing tipping point would you switch?
2. The IP-infringement letter was flagged in diligence at $2-8M exposure. If it turns out post-close that the actual exposure is $15M (worse than the outside estimate), what recourse would the buyer have under your design? Is that recourse cap consistent with what you would want if you were the buyer?
3. Which specific line in your working-capital definition would you fight hardest to keep against a redline? What does that tell you about the highest-value drafting decision in the WC mechanic?
4. Is there a case where you would prefer a *larger* general-indemnity escrow than the ABA benchmark suggests? Under what conditions?

## Stretch goals

- **Read a recent SRS Acquiom / ABA Deal Points update.** Snapshot the current-year benchmarks for escrow size, survival period, and R&W-uptake in private M&A. Compare against the numbers used in this exercise and note any material shifts.
- **R&W-insurance broker outreach.** If you have any access to an R&W-insurance broker (Marsh, Aon, Willis Towers Watson, Woodruff Sawyer, CAC Specialty), have a 30-minute conversation about how they would price this specific transaction. Note their retention, policy-limit, and premium quote as compared to the assumed values in the exercise.
- **Redline exercise.** Assume the buyer's counsel sends you a draft merger agreement with these specific escrow / holdback / WC terms; identify 5 specific redlines you would insist on from the seller's perspective, and 5 you would defend to the death.
- **Chancery WC dispute case.** Read *Chicago Bridge & Iron Co. N.V. v. Westinghouse Electric Company LLC* (Del. 2017) or another major WC-adjustment dispute case for practical Chancery framing on the boundary between neutral-accountant scope and Chancery adjudication.
