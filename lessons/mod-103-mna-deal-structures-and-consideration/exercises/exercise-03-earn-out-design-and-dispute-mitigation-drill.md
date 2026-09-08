# exercise-03: Earn-Out Design and Dispute Mitigation Drill

**Estimated effort:** 4 hours

## Objective

Draft an earn-out for a specific fact pattern from a first-principles design (metric selection, payout curve, control-and-oversight obligations, acceleration-on-breach, dispute resolution). Then stress-test the draft against three specific dispute scenarios and revise until the modal outcome is a clean payout or a clean miss without Chancery litigation. By the end you should be able to defend the earn-out design at the working-group call, know which drafting decisions are load-bearing against known Chancery failure modes, and know which ones you have deliberately traded off.

## Background

This exercise covers material from:

- [Chapter 3 — Earn-Out Design and Dispute Mitigation](../03-earn-out-design-and-dispute-mitigation.md)

Chapter 2 (consideration mix) provides the context — an earn-out is a specific structured-consideration element. Chapter 7 (§409A) governs the payment-timing constraints on any earn-out paid to service providers. Chapter 6 (§280G) applies if a portion of the earn-out is treated as change-of-control compensation.

## Prerequisites

- You have read chapter 3 in full.
- You have skimmed chapter 7 (§409A) enough to know that earn-outs paid to service providers are subject to timing constraints.
- Optional: read *In re Fortis Advisors LLC v. Johnson & Johnson* (Del. Ch. 2020) and *Airborne Health, Inc. v. Squid Soap, LP* (Del. Ch. 2010) for practical Chancery earn-out dispute framing. Cooley / WSGR / Sidley have practitioner memos on earn-out drafting worth skimming.

## The fact pattern

**Target:** Delaware C-corp, developer of a vertical B2B analytics product with $18M ARR, growing 60% YoY at the LOI date. Two founders continue post-close in senior operating roles.

**Acquirer:** Publicly-traded strategic in an adjacent enterprise-software category, $6B market cap. The acquirer intends to integrate the target's product into its existing platform over 12–18 months, then cross-sell to its existing customer base.

**Headline consideration:** $180M — $110M cash at closing, $70M earn-out payable over 24 months post-close.

**Founder concerns:**
- Founders want the earn-out designed so that acquirer post-close conduct cannot arbitrarily reduce the earn-out payout.
- Founders are concerned that a "cross-sell into acquirer's customer base" strategy could route revenue away from the target's revenue-recognition bucket in ways that appear to reduce earn-out attainment.
- Founders want acceleration on specific acquirer breaches (product-integration timeline, sales-support commitments).

**Acquirer concerns:**
- Acquirer wants sole operational control post-close and does not want to be constrained by earn-out-driven veto rights.
- Acquirer wants the metric to reflect the *combined* business performance, not just the standalone target's, since integration is the strategic thesis.
- Acquirer wants a low dispute-resolution cost — no Chancery litigation over accounting choices.

## Tasks

### 1. Design decision 1: metric

Choose a metric or metric mix from:
- Standalone target revenue.
- Standalone target gross profit.
- Standalone target Adjusted EBITDA.
- Integrated-product revenue (target product SKUs, however sold, including via acquirer channels).
- Bookings for target-product SKUs (billings + committed contract value).
- Product milestone (e.g., successful integration into acquirer's platform by month 12) alone or combined with a financial metric.
- Mixed — two metrics running in parallel, or a milestone that unlocks a financial metric.

Write a **1-page metric-selection memo**:

- Which metric(s) did you choose and why?
- What specific behaviour by the acquirer would this metric protect against manipulation? What behaviour would it NOT protect against?
- If your metric is revenue: what is the specific definition (recognised revenue, billed revenue, contracted revenue, ARR at a point in time)? Under what accounting standard (US GAAP as consistently applied, or a specific carved-out standard)?
- If your metric is gross profit or EBITDA: what specific adjustments are in / out? Which allocations of shared costs post-integration are captured?
- If your metric is a product milestone: what is the specific definition of "achievement"? Who determines achievement? What is the tolerance on partial achievement?

### 2. Design decision 2: payout curve

Choose a shape from:
- Cliff (all-or-nothing at target).
- Graduated / linear (payout scales linearly between a threshold and a cap).
- Accelerated (steeper payout above target).
- Tiered / stepped (discrete tiers).

Then specify:

- **Threshold.** Below what performance level does the earn-out pay zero?
- **Target.** At what performance level does the earn-out pay 100%?
- **Cap.** At what performance level does the earn-out cap out (if applicable)?
- **Measurement period.** Single period ending at month 24, quarterly measurements with cumulative true-up, or year 1 / year 2 split?
- **Currency.** Cash vs. acquirer stock; if stock, fixed-ratio or fixed-value?

Draft the payout formula as a specific set of equations, and produce a small table showing payout at 8+ representative performance levels (e.g., threshold, threshold + 25%, threshold + 50%, target, target + 25%, cap, cap + 25%).

### 3. Design decision 3: control-and-oversight obligations

This is the most drafting-heavy portion. Draft the specific covenants the acquirer accepts. Consider each of the following and take a specific position (include; include with limits; exclude; leave to acquirer's discretion):

- **Operating the target's business.** Continue to operate the target's business in a manner consistent with pre-close operations for the earn-out period? To what standard — "consistent with past practice," "reasonable best efforts," "ordinary course," "commercially reasonable efforts"? Chapter 3 discusses the meaning-in-practice of each.
- **Product roadmap.** Maintain the product on a specific development trajectory? Any specific product-integration milestones that constrain acquirer choices?
- **Sales support.** Maintain sales-and-marketing spend at a specific level (percentage of target revenue, or dollar floor)? Maintain sales headcount?
- **Personnel.** Retain specific key personnel (founders) in specific roles? Non-terminate-without-cause provisions? Non-transfer to unrelated business units?
- **Customer conduct.** Not to specifically re-price or discount the target's product below a specified floor? Not to bundle the target's product into acquirer products at zero incremental revenue?
- **Reporting.** Provide founders with periodic (monthly / quarterly) reporting on the earn-out metric with reasonable back-up data? Access to underlying books and records?
- **Non-compete.** Not to launch a competing product line during the earn-out period? (This is a strong covenant; acquirers resist it.)
- **Sole discretion vs. reasonable efforts.** For every management decision — pricing, marketing, R&D, hiring — where is the line between acquirer's business judgment and covenanted obligation?

Draft each covenant as one specific sentence you would put in the merger agreement. Then note the specific *dispute vector* the covenant addresses.

### 4. Design decision 4: acceleration on breach

Draft the acceleration provisions:

- **What acquirer conduct triggers acceleration?** Material breach of a specific covenant? Material breach as measured how — objectively, or subject to acquirer's cure right?
- **What is the acceleration amount?** Immediate payout of the full earn-out (100% deemed achievement)? Payout at a specific fraction (e.g., 75%)? Payout at the run-rate implied by trailing performance?
- **What is the cure right?** Some period (30 / 60 / 90 days) for the acquirer to cure? Automatic cure if a specific milestone is subsequently met?
- **Change-of-control of the acquirer.** If the acquirer itself is sold during the earn-out period, does the earn-out accelerate? At what value?

Draft each acceleration trigger as a specific SPA provision with the amount and cure mechanics.

### 5. Design decision 5: dispute resolution mechanics

Draft the specific dispute-resolution structure:

- **Initial notice.** How does the founder representative dispute the acquirer's earn-out calculation? Within what window?
- **Response period.** How long does the acquirer have to respond?
- **Escalation.** After the response, if the parties still disagree, does the dispute go to a neutral accountant, mediation, arbitration, or Chancery Court?
- **Neutral accountant scope.** If a neutral accountant is engaged, what is their scope? *Only* to determine whether the metric calculation followed the SPA's definitions, or *also* to make substantive judgments about disputed adjustments? Baseball arbitration (pick one party's number) or normal-mode (make an independent finding)?
- **Fees.** Who pays the neutral accountant / arbitrator? Loser pays, split, or paid by the party whose position was less well-supported?
- **Confidentiality.** Is the dispute-resolution process confidential?
- **Chancery reserved.** For what specific matters, if any, is Chancery Court reserved (fraud, wilful misconduct, injunctive relief)?

Draft the dispute clause as it would appear in the SPA (½–1 page of specific language).

### 6. Stress-test the draft against three dispute scenarios

Now imagine the earn-out playing out under three specific failure scenarios and analyse whether your draft holds up.

**Scenario A: Cross-sell displacement.**
The acquirer aggressively cross-sells the target's product to its own existing customer base. Post-close year 1 sees strong integrated adoption but the acquirer books much of that revenue against a repackaged combined-product SKU that does not clearly map to the target's earn-out revenue definition. Founders claim the earn-out is being displaced by an accounting choice; acquirer claims the SKU reflects genuine product transformation.

- Does your metric definition (task 1) resolve this cleanly?
- If not, what specific covenant (task 3) or dispute mechanic (task 5) addresses it?
- Would you revise your draft based on this scenario?

**Scenario B: Sales-force reallocation.**
The acquirer reassigns 40% of the target's pre-close sales team to non-target-product territories 6 months post-close. Target-product sales flatten. Founders claim breach of sales-support obligation; acquirer claims reallocation reflects sound business judgment.

- Does your sales-support covenant (task 3) constrain this?
- Does your acceleration provision (task 4) trigger?
- What would a Chancery Court likely find on a "commercially reasonable efforts" standard versus a "consistent with pre-close practice" standard?

**Scenario C: Founder departure.**
One of the two founders resigns 8 months post-close, citing acquirer-culture reasons. Target-product growth softens materially in the subsequent quarters. Acquirer argues the earn-out shortfall is founder-caused and refuses to pay. Founders argue the departure was acquirer-provoked (constructive termination) and that the earn-out should still be paid.

- Does your draft address founder departure?
- If yes, how? (Constructive termination clause? Automatic acceleration if a founder is terminated other than for cause? No provision — earn-out simply plays out?)
- What is the dispute-resolution outcome most likely to be?

For each scenario, revise your earn-out draft as needed. Track your revisions with a version comment (e.g., "v2: added Section 3.4 constructive-termination provision after Scenario C").

### 7. §409A and §280G interaction check

- **§409A compliance.** Chapter 7's framework: is the earn-out structured to fall within the short-term-deferral exception, or does it require formal §409A compliance? For a 24-month earn-out with substantial risk of forfeiture through year 2, the design typically fits within the short-term-deferral exception if payment is made within 2.5 months after the end of year 2. Verify your draft's payment timing against this test. If you have the earn-out payable in installments over years 1 and 2 with a final true-up at year 2, does each installment separately qualify for short-term deferral?
- **§280G interaction.** Chapter 6's framework: earn-out payments contingent on continued service can be treated as parachute payments under §280G (specifically, if payment is contingent on a change of control combined with continued service, the payment may be a parachute payment). Does the earn-out increase the §280G parachute-payment computation for the two founders? Verify that either (a) the founders' aggregate parachute payments remain below the 3x-base-amount threshold, or (b) the design accommodates a §280G(b)(5) shareholder-vote cleanse.

Write a ½ page compliance check summarising both.

### 8. Write the memo

Draft a **2-page earn-out design memo** that:

- Names the metric, payout curve, control-and-oversight covenants, acceleration triggers, and dispute mechanics you selected.
- Explains the buyer-vs-seller trade-off resolved by each choice.
- Notes the specific Chancery-litigation failure modes (from chapter 3) that your design mitigates and the failure modes it does not.
- Includes the §409A / §280G compliance summary (task 7).
- Would be shareable with sell-side counsel as your working design position.

## Starter guidance

- **Metric definition is where most disputes are born.** A revenue definition that says "recognised revenue from the target's products under US GAAP as consistently applied" is a starting point; the acquirer's accounting choices under GAAP have wide latitude and can produce disputes in year 2 that the draft is silent on. Consider adding specific carve-outs for revenue-recognition changes, price-book changes, and revenue attribution rules for bundled products.
- **"Commercially reasonable efforts" is a very weak covenant.** Delaware case law generally interprets this as requiring the acquirer to do what a reasonable person would do to achieve the milestone, which is a low bar and produces litigation. Where a stronger covenant matters ("consistent with past practice," "in accordance with the acquired business's historical practice as of the closing date"), draft it that way.
- **Small acceleration payments are worse than clean ones.** An acceleration provision that pays 40% of the earn-out on breach is a compromise that satisfies neither side and produces disputes about what constitutes breach. Cleaner: an acceleration provision that pays 100% on clearly-defined material breach (with a defined cure right), and no acceleration otherwise.
- **Dispute-resolution scope should match dispute nature.** Neutral-accountant arbitration is appropriate for GAAP / calculation disputes; Chancery is appropriate for breach-of-covenant disputes. Mixing them (sending covenant disputes to a neutral accountant) produces bad outcomes.

## Acceptance criteria

You can demonstrate that:

- All five design decisions (metric, payout curve, control-and-oversight, acceleration, dispute-resolution) are drafted specifically and defensibly.
- The three stress-test scenarios have been worked through and the draft has been revised where the scenarios revealed weaknesses.
- The §409A and §280G compliance check has been performed and documented.
- The earn-out design memo (task 8) is complete and would be shareable.

## Reflection

Add a short reflection:

1. Which design decision was hardest to make? Where did buyer-preference and seller-preference feel most irreconcilable?
2. Under Scenario A (cross-sell displacement), if you were the founder representative and the acquirer refused to concede, at what point would you initiate a Chancery lawsuit? What is the cost / benefit of doing so?
3. If the founder-CEO's post-close employment agreement includes a §280G-driven cutback provision (chapter 6), how does that interact with the earn-out design? Would you sequence the §280G shareholder vote (chapter 6) to include or exclude the earn-out?
4. Which single line in your merger-agreement earn-out draft, if the buyer's counsel asked to strike it, would you fight hardest to keep?

## Stretch goals

- **Read a real earn-out dispute opinion.** *In re Fortis Advisors LLC v. Johnson & Johnson* (Del. Ch. 2020), *Airborne Health, Inc. v. Squid Soap, LP* (Del. Ch. 2010), or *Winshall v. Viacom International* (Del. Ch. 2013). Note 3–5 specific drafting decisions in the underlying merger agreement that the court found determinative. How would you incorporate those lessons into your draft?
- **CVR alternative.** Redraft the earn-out as a CVR (contingent value right) instead of an earn-out — a security that pays out on a milestone rather than a compensation-linked payment. What changes in the §409A analysis? What changes in the §280G analysis? Would the CVR structure be better or worse for founders in this fact pattern?
- **Neutral-accountant selection.** Draft a short-list of three specific neutral-accountant candidates the parties could pre-agree in the merger agreement. Who has M&A dispute experience — Alvarez & Marsal, PwC, Deloitte, KPMG, Grant Thornton, or others? Note their published qualifications.
- **Founder-side counter-draft.** Assume you have drafted the earn-out from the acquirer's perspective. Now redraft it from the founder representative's perspective. What are the 5–8 lines you would most want changed, and what specific language would you insert?
