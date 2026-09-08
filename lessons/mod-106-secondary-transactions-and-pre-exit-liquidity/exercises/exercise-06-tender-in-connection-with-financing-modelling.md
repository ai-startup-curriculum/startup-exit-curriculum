# exercise-06: Tender in Connection with Financing Modelling

**Estimated effort:** 4–5 hours

## Objective

Model a combined primary-plus-secondary transaction for a growth-stage target — a Series [X] preferred round with an embedded secondary tender that clears alongside the primary close. Defend the primary-vs-secondary pricing spread against a waterfall analysis; size the tender's participation caps against the round's committed capital; model the post-round cap-table and the buyer's blended cost basis; and coordinate the approval and close sequence across the primary and secondary components. Produce (a) a combined-transaction memo (10–14 pages) suitable for board approval, (b) a cap-table model with pre-round / post-round states and a waterfall across a distribution of exit valuations, and (c) a coordinated-timeline document that sequences primary and secondary approvals and closes.

## Background

This exercise covers material from:

- [Chapter 7 — Tender-in-Connection-with-Financing — The Primary-plus-Secondary Pattern](../07-tender-in-connection-with-financing.md) — the three-component structural pattern, the pricing negotiation, the participation-cap and waterfall analysis, the interaction with the primary-round cap-table shuffle, and the coordinated approval and close choreography.

Supporting references:

- [Chapter 2 — Employee Tender Offer](../02-employee-tender-offer-design.md) and [Chapter 3 — Tender Waterfall Analysis and Tax Treatment](../03-tender-waterfall-and-tax-treatment.md) — the base tender-offer apparatus this chapter builds on.
- [Chapter 6 — ROFR and Co-Sale Choreography](../06-rofr-and-co-sale-choreography.md) — the ROFR / co-sale mechanics fold into the round's overall approval package.
- [Chapter 8 — 409A Refresh Cycles, Rule 701 Interaction, and the Ownership Boundary](../08-409a-refresh-and-ownership-boundary.md) — the combined transaction almost always triggers a 409A refresh at the new primary price and a Rule 701 impact analysis.
- [`startup-finance-fundraising-curriculum` mod-104](https://github.com/ai-startup-curriculum/startup-finance-fundraising-curriculum) — the primary-round cap-table shuffle discipline this exercise composes with.

## Prerequisites

- The hypothetical target you carried through the prior exercises. For this exercise the target should be at a stage where a primary-plus-secondary combined transaction is plausible — Series D or later, $500M+ implied valuation, meaningful pool of long-tenured founder / employee / early-investor common shareholders eligible to sell.
- Cap table with full detail: common outstanding by holder (founders, early employees with vested positions, early investors), each preferred series (share count, per-share issue price, liquidation preference, participation posture, dividend accrual), option pool, current 409A common price.
- Spreadsheet or notebook environment with waterfall-modelling capability.
- Familiarity with the primary-round cap-table shuffle discipline from `startup-finance-fundraising-curriculum` mod-104 (pre-emptive rights, option-pool refresh, pro-forma post-money cap-table).

## Tasks

### 1. Set the target-and-round baseline

Write a 1-page baseline covering:

- **Target profile** — sector, ARR, growth, headcount, most-recent primary round (Series [X-1], date, per-share price, headline valuation), lead investor and existing preferred syndicate.
- **Round motivation** — why the target is raising the round (working-capital, growth investment, market-position defence, specific strategic initiative), the specific dollar amount the target's finance function needs (the primary capital requirement).
- **Round context** — the committed lead investor and the total committed capital, the gap between committed capital and the target's primary capital requirement (this gap is what the secondary component absorbs), and the target's willingness to accept the round's dilution vs. the alternative of shrinking the round.
- **Seller pool** — the identifiable pool of founders, early employees, and early investors with meaningful vested common positions who are potential tender participants, with aggregate share count and estimated per-holder participation appetite.
- **Prior tender history** — has the target previously run tenders? What was the pricing, participation, and workforce reception?
- **409A cadence** — current 409A common price, last-refresh date, and the appraiser's known posture on primary-plus-secondary transactions.

### 2. Structure the three components

Draft the specific structural pattern of the combined transaction covering:

- **Component 1 — Primary preferred round** — the new preferred series' terms (share count, per-share price, headline valuation implied, liquidation preference, dividend rights, protective provisions, board-seat additions or changes).
- **Component 2 — Secondary tender** — the buyer identity (same lead as primary; a co-investor; a separate secondary-market buyer participating alongside), the aggregate secondary commitment, the pricing methodology.
- **Component 3 — Tender documentation, eligibility, and cap layer** — the tender eligibility rules (typically similar to a standalone tender but potentially with different executive-participation rules given the coordinated-transaction context), the per-participant and aggregate caps, the ROFR / co-sale integration.

### 3. Choose the primary-vs-secondary pricing spread and defend the choice

From chapter 7's three approaches:

- **Approach A** — secondary at the primary preferred price.
- **Approach B** — secondary at a defined discount to primary (15–40% typical; 20–30% modal).
- **Approach C** — secondary priced independently.

Choose the approach and defend it in a 1-page memo covering:

- The buyer's economics under each approach and the negotiation dynamic.
- The seller-pool reception under each approach.
- The waterfall defence of the chosen secondary price against the target's preference stack.
- The 409A refresh implication — how likely is a fresh 409A at what common price under the chosen spread?
- The alternative approaches you rejected and why.

### 4. Build the primary-plus-secondary waterfall model

Produce a waterfall model that captures both the pre-round and post-round states covering:

- **Pre-round cap table** — full detail before the transaction.
- **Primary round issuance** — new preferred shares issued at the primary price, resulting cap-table update.
- **Secondary transfer** — common shares transferred from sellers to the lead (or the secondary buyer), typically as common (retained by the lead as a distinct common position) or as-converted-to-preferred (converted at the lead's option under the SPA's specific provisions).
- **Option-pool refresh (if any)** — the primary-round-triggered option-pool top-up, typically at the pre-money cap table (dilutive to existing holders, not to the new lead), sized against a defined post-money option-pool percentage.
- **Post-round cap table** — full detail after the transaction, showing every holder's post-round position.

Compute:

- The lead's blended cost basis across primary and secondary — total dollars committed ÷ total shares (converted to a common-equivalent basis). Compare against the pure-preferred cost basis to quantify the secondary discount's economic value to the lead.
- The seller pool's aggregate cash proceeds — total dollars distributed across the participating sellers, per-participant estimated proceeds.
- The target's dilution — pre-money and post-money percentages, and the specific dilution to each existing holder (founder, employee, existing preferred series).

Run the waterfall across a distribution of exit valuations (0.5×, 1×, 2×, 3×, 5× current implied valuation) and produce:

- The lead's return per exit valuation (as-if-hold-to-exit assumption on both primary and secondary components).
- Each existing preferred series' return per exit valuation.
- The common (founder + employee) return per exit valuation.
- The lead's break-even exit valuation across the blended primary-plus-secondary position.

### 5. Size the participation caps

Draft the tender's cap structure covering:

- **Aggregate cap** — the secondary component's total dollar amount, driven by the buyer's committed capital minus the primary component. Anchor to the specific committed-capital gap.
- **Per-participant cap** — the maximum per-participant tender, potentially level-based (executive vs. senior IC vs. rank-and-file). Cross-reference exercise-02's cap-structure analysis for the base methodology.
- **Executive-participation policy** — whether the executive team is eligible for the tender and, if so, at what specific cap. In a tender-in-connection-with-financing, the executive-participation question is often a specific negotiation with the incoming lead (who may or may not want to see the executives sell).
- **Founder-participation policy** — same question, plus the alignment-of-interest analysis from chapter 1.
- **Early-investor-participation policy** — some tenders-in-connection-with-financing include early-investor participation (e.g., seed investors selling in the tender to make room for new-round investors); others limit the tender to employees. Defend the choice.
- **Proration mechanics** — if aggregate participant demand exceeds the aggregate cap, how the buy is prorated.

### 6. Coordinate the approval and close timeline

Produce a specific coordinated timeline covering:

- **Pre-signing phase** — parallel term-sheet negotiation on primary and secondary components; parallel diligence workstreams; parallel legal-document drafting (SPA for primary; tender documentation or secondary SPA for secondary); coordinated board deliberation.
- **Signing** — coordinated signing of the primary SPA and the secondary tender documentation. Typical practice: same-day sign, or secondary signing pushed 1–3 days later to accommodate ROFR / co-sale mechanics on the secondary component.
- **ROFR / co-sale on the secondary component** — the specific notice-and-waiver process, folded into the round's overall approval package. Some rounds structure the ROFR waiver as a blanket transaction-approval mechanic across primary and secondary; others run the ROFR on the secondary component separately.
- **Tender-open window** — the tender's open period after signing, running for 20+ business days typically. During this window the buyer is committed but the specific secondary allocation across participating sellers is not yet finalised.
- **Tender close** — the specific date at which participant elections are aggregated, proration (if any) is applied, and the specific per-participant secondary allocation is finalised.
- **Primary and secondary close** — the coordinated close where the primary round's closing conditions are satisfied and the secondary component's participant-specific allocations settle. Typically a single close event with coordinated funds flows.
- **Post-close** — the 409A refresh (typically triggered by the transaction's primary price and any material secondary volume at a materially different price), the Rule 701 aggregate-value update, the cap-table update, and the workforce-communication follow-through.

### 7. Analyse the 409A refresh and Rule 701 implications

Produce a 1–2 page analysis covering:

- **409A refresh** — whether the primary round alone triggers a refresh (typically yes for any primary round at a materially different valuation), what the likely fresh common price will be, and whether the secondary pricing spread affects the refresh common price. Quantify the impact on subsequent ISO strike prices.
- **Rule 701 aggregate-value impact** — the same-day exercises and RSU settlements in the tender consume Rule 701 capacity. Compute the projected aggregate-value consumption and confirm it stays within the applicable cap.
- **Appraiser-coordination timing** — when and how the target's 409A appraiser is engaged for the refresh, and how the transaction's specific data (primary price, secondary price, participation volume) is delivered to the appraiser.

### 8. Draft the board-and-committee approval package

Draft a 3–5 page approval package for the board and compensation committee covering:

- The combined-transaction overview.
- The primary-plus-secondary structure.
- The pricing-spread analysis with waterfall defence.
- The tender's eligibility and cap structure.
- The ROFR / co-sale integration.
- The 409A refresh and Rule 701 implications.
- The board resolutions required (approve the primary SPA, approve the secondary tender, waive the company's ROFR on the secondary component, approve the option-pool refresh, authorise officer signing authority, approve any board-composition changes).
- The compensation-committee resolutions required (approve the tender's compensation-related design decisions — executive-participation policy, level-based caps, participant-education pack).

### 9. Draft the participant-facing tender pack

Draft a 4–6 page participant-facing tender pack that layers on top of the exercise-02 pack, covering:

- The combined-transaction context (this is a tender running alongside a primary round; here is what that means for participants).
- The pricing (per-share tender price, and the pricing-spread explanation from the primary round).
- The eligibility rules.
- The per-participant cap and the proration mechanics.
- The four tax-treatment categories (cross-reference exercise-02).
- The per-participant estimated-outcome worksheet template.
- The election window and mechanics.
- The disclaimer and personal-tax-advisor referral.

## Starter guidance

Common tender-in-connection-with-financing errors to avoid:

- **Pricing the secondary at primary preferred without a 409A conversation.** Triggers a fresh 409A at or near the primary price, materially increasing subsequent ISO strike prices, and constrains the target's future-hiring economics. The 409A cost of the pricing choice should be quantified before the decision is made.
- **Committing to an aggregate secondary cap without an eligibility-and-demand analysis.** The buyer's committed capital determines the buy-side cap; the eligible-participant pool's aggregate appetite determines the demand. If demand materially exceeds the cap, the proration reduces participant excitement; if demand materially falls short, the buyer is left with unallocated capital.
- **Skipping the coordinated board deliberation.** The primary and secondary components run through a single board process; splitting them into separate deliberations introduces coordination failures and can create alignment-of-interest issues if the board is asked to approve the primary knowing the secondary component's specific structure only later.
- **Ignoring the executive-and-founder participation politics.** The incoming lead may have specific views on whether the executives and founders should participate in the tender; those views must be negotiated in during term-sheet, not after signing.
- **Under-communicating the pricing spread to participants.** Participants who see a $100 preferred price and a $60 secondary price without an explanation read the 40% discount as company-side undervaluation. The participant-education pack must explain the waterfall analysis and the common-vs-preferred distinction.
- **Ignoring the option-pool refresh implication.** A primary-round option-pool refresh is typically dilutive to pre-money holders (including participating tender sellers on the shares they retain). The pre-money option-pool cost is often a significant piece of the round's economics and must be modelled explicitly.
- **Assuming the target's 409A appraiser will handle the transaction's impact at the next scheduled refresh.** The appraiser should be engaged at design phase to confirm the refresh timing and the specific-transaction impact analysis; running the transaction and then hoping the appraiser accommodates it at the next refresh is a governance failure.

## Acceptance criteria

You can demonstrate that:

- Target-and-round baseline covers the round motivation, the committed-capital gap, and the seller pool.
- Three-component structural pattern is drafted with primary, secondary, and tender-layer components.
- Primary-vs-secondary pricing spread is chosen with a defended rationale and a waterfall defence.
- Primary-plus-secondary waterfall model is built with pre-round / post-round cap-table states, lead blended cost basis, seller pool proceeds, and return distributions across a range of exit valuations.
- Participation caps are sized with aggregate cap, per-participant cap, executive / founder / early-investor participation policies, and proration mechanics.
- Coordinated timeline sequences primary and secondary approvals and closes.
- 409A refresh and Rule 701 implications are analysed with quantified impact on subsequent ISO strike prices and aggregate-value consumption.
- Board-and-committee approval package is drafted with the specific resolutions the board must pass.
- Participant-facing tender pack layers on top of the standalone tender pack from exercise-02.

## Reflection

Add a short reflection:

1. Which of the three pricing-spread approaches produced the most defensible economics for the target across all four stakeholder groups (lead, existing preferred, founders, participating employees), and what does that tell you about the negotiation strategy?
2. If the buyer's committed capital exceeded the target's primary capital requirement by 3× (a very large secondary sleeve), how would you reshape the tender's eligibility and cap structure to accommodate the excess without diluting the alignment-of-interest posture on the founder / executive positions?
3. If the target's 409A appraiser flagged that a refresh at the primary price would drive subsequent ISO strike prices to a level that would materially impair the target's hiring economics, would you negotiate the primary price down, structure the secondary at a larger discount, or accept the higher strike prices and adjust the grant-guideline share counts? Which trade-off wins?
4. How does the ROFR / co-sale process on the secondary component change when the buyer is already the primary-round lead (and therefore an existing preferred holder) vs. a separate secondary-market buyer? What specific waiver-and-consent mechanics differ?

## Stretch goals

- **Comparable-transaction benchmarking.** Assemble 3–5 publicly-observable primary-plus-secondary transactions from the last 24 months (Stripe's 2023 $6.5B, Databricks' 2023 $500M, Discord's 2021 $500M, Notion's 2021, and others) and compare their pricing spread, participation structure, and closing timelines against your model.
- **Full cap-table model with pre-emptive-rights layer.** Extend the model with the primary round's pre-emptive-rights mechanic — existing preferred holders' pro-rata participation right, which reshapes the actual round-participant mix. Model three scenarios: all existing preferred waive, all exercise, mixed exercise / waive.
- **Option-pool refresh optimisation.** For the round's option-pool refresh, model the specific size decision under a defined target-post-money-option-pool percentage. Compute the specific dilution to each pre-money holder and identify the negotiation points on the pool-refresh sizing.
- **Multi-buyer secondary syndicate.** Structure the secondary component as a syndicate across the primary lead, one co-investor, and one specific secondary-market buyer; model the specific-buyer allocation mechanics and the syndicate-formation choreography.
- **Coordinated M&A / IPO branching analysis.** If the target had a live sell-side conversation in parallel with the primary-plus-secondary transaction, work through the specific disclosure, fiduciary-duty, and process-integrity choreography that would keep the two transactions from cross-contaminating.
- **International-participant handling.** For a target with a distributed workforce spanning multiple countries, identify the specific per-country tax-withholding and securities-law adjustments the tender documentation must handle, and estimate the additional operational lift.
