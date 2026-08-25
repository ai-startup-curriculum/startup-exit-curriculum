# Tender-in-Connection-with-Financing — The Primary-plus-Secondary Pattern

## Why this matters

For most of the last twenty years, a growth-stage priced round and an employee tender were separate transactions. A company would raise a Series D as a primary round; six or twelve months later, if the workforce was accumulating meaningful paper equity, the same company might run a tender that let employees sell. The two were connected in the company's finance function but were separate transactions at separate times, with separate approvals, separate documentation, and separate buyer identities.

The pattern that has emerged, especially since roughly 2018–2020 at growth-stage private-company financings above $100M, is a single **combined transaction** — a primary preferred round with an embedded secondary tender that clears alongside the primary close. Stripe's 2023 $6.5B primary-plus-secondary transaction, Databricks' 2023 $500M primary-plus-tender, Discord's 2021 $500M round with a companion tender, Notion's 2021 round with employee liquidity component, and dozens of other transactions in the growth-stage AI, SaaS, and consumer-technology segments have run this pattern. For target companies at Series D and later, the combined primary-plus-secondary pattern has become close to the default expectation.

The reasons are structural. A single primary round can be $200M–$500M+ in committed capital, but the target's actual capital needs may be materially smaller — perhaps $100M for working capital and growth investment. The remaining committed capital, if the round were purely primary, would be capital the target does not need and dilution it does not want to accept. Restructuring that excess capital as a secondary purchase — of founder / early-employee / early-investor common — lets the round's lead deploy their full commitment while providing pre-exit liquidity to the seller pool and reducing the target's dilution to the round's headline share count. The economics work for everyone: the lead deploys full commitment; the target takes only the primary capital it needs; the seller pool receives liquidity; the target's dilution is a net-positive relative to a pure-primary round of the same headline size.

This chapter installs the tender-in-connection-with-financing pattern: how the primary and secondary components are structured together, how the pricing negotiation typically runs (with the secondary at a discount to the primary), how the participation cap and waterfall analysis interact with the primary-round cap-table shuffle, and what the specific approval and coordination discipline requires.

> **Reminder: education, not legal or tax advice.** The specific structure of any primary-plus-secondary transaction requires securities counsel, tax counsel, and a coordinated diligence-and-approval process across the primary and secondary components. This chapter installs the practitioner vocabulary; the specifics come from qualified counsel.

## The structural pattern

A tender-in-connection-with-financing typically comprises three components executed contemporaneously (or in close-coordinated sequence):

### Component 1 — The primary preferred round

The target issues new preferred shares to the round's lead (and potentially co-investors) at a defined per-share price. This is a standard preferred financing round — chapter 2 through 6 of a NVCA-pattern financing. The primary component:

- Provides new capital to the target (funding the target's operations).
- Adds new preferred stock to the capital structure with new preferred rights (liquidation preference, dividend rights, protective provisions).
- Dilutes the existing capital structure at the primary preferred share price.
- Is documented in a Series [X] Preferred Stock Purchase Agreement (SPA) and related documents.

### Component 2 — The secondary tender

The same lead investor (and often co-investors) purchases existing common shares from founders, employees, and (sometimes) early investors at a defined secondary price. This is the tender component of the combined transaction. The secondary component:

- Provides liquidity to selling shareholders.
- Does not add new capital to the target (the buyer's payment goes to the sellers, not to the company).
- Does not directly dilute the capital structure (existing common shares change hands but the share count does not change).
- Is documented in a Secondary Stock Purchase Agreement or a Tender Offer document.

### Component 3 — The tender documentation, eligibility, and cap layer

The secondary is administered as a tender offer with the eligibility, participation cap, and pricing mechanics described in chapters 2–3, adapted to the round context. The tender:

- Is typically limited to a defined class of employees, founders, and (sometimes) early investors.
- Has per-participant and aggregate caps determined by the buyer's total committed capital and the desired distribution.
- Runs on a coordinated timeline with the primary round's approval and close.

## Pricing negotiation — the primary-vs-secondary spread

The single most consequential specific design decision in a tender-in-connection-with-financing is the **pricing relationship** between the primary preferred and the secondary common. Three canonical approaches:

### Approach A — Secondary at the primary preferred price

The secondary purchase price is set equal to the primary preferred round's per-share price. Simplest to explain, aligns the buyer's willingness-to-pay across both components. Attractive to sellers (highest secondary price), attractive in narrative simplicity. But two consequential implications:

1. **The buyer is overpaying for common relative to a preference-stack-adjusted common value.** Common is worth less than preferred (chapter 3). By pricing common at the preferred price, the buyer is effectively subsidising the secondary.
2. **The 409A refresh implication is significant.** A material volume of common shares changing hands at the preferred price is a strong observable-transaction data point that the target's 409A appraiser will consider. The likely outcome is a substantial 409A refresh with common priced close to preferred, driving subsequent ISO strike prices materially higher (chapter 8).

Companies use this approach when the round's simplicity and pricing-clarity considerations outweigh the 409A / future-grant costs.

### Approach B — Secondary at a discount to primary

The secondary purchase price is set at a defined discount to the primary preferred price — typical discounts range from 15% to 40%. This is the modal approach in practitioner practice.

The rationale:

- Common is worth less than preferred (waterfall analysis, chapter 3). Discounting the secondary reflects that fundamental economic distinction.
- The 409A refresh implication is reduced. A secondary at 25% below preferred may or may not materially move the 409A common price (depending on the volume, the target's specific 409A methodology, and the appraiser's judgment); the target has more control over the 409A implication.
- The buyer's economics improve. The buyer is paying below-preferred for common; assuming eventual conversion to common at exit, the buyer's blended purchase price across primary and secondary is lower than pure-preferred.

The discount is negotiated at the round's design phase — the lead investor typically prefers a larger discount (better secondary economics for the buyer); the target prefers a smaller discount (more attractive to selling shareholders). The negotiated point is typically 20–30% for growth-stage rounds, subject to the specific capital-structure and 409A considerations of the target.

### Approach C — Secondary priced independently

The secondary is priced independently of the primary — sometimes at the current 409A common price, sometimes at a secondary-market clearing price observed on Forge or NPM, sometimes at a purpose-negotiated price. The independence is unusual in a formal tender-in-connection-with-financing because the buyer identity is shared and the transactions are coordinated; but where the target has strong 409A discipline or the secondary is intended to be truly market-clearing, this approach may be used.

### Waterfall implications of the pricing decision

The pricing spread between primary and secondary drives a specific mathematical outcome in the resulting cap table. Consider a simplified example:

- Pre-round cap: 45M common (founder + employee), 25M preferred (existing rounds at cumulative $1B preference).
- Primary round: $300M at $80/preferred (implies pre-round $5B valuation). New preferred issued: 3.75M shares.
- Secondary component: $100M at $60/common (25% discount). Common shares transferred: 1.67M.

Post-round cap:

- Common: 45M − 1.67M = 43.33M
- Preferred: 25M + 3.75M + 1.67M (converted-basis for tender-acquired common held by lead) = but note the lead's secondary purchase is of common, not preferred; it stays as common in the lead's hands (unless the lead converts). Or, more typically, the lead has agreed to take those shares as an equivalent as-converted preferred position for cap-table cleanliness. This depends on the specific SPA and the buyer's negotiation.

Waterfall implications:

- At exit valuations at or above the preference stack + $1.3B ($1B existing + $300M primary), the primary lead sees full-preference payout on preferred plus common upside on the tender-acquired shares.
- The lead's blended cost basis is: ($300M primary + $100M secondary) / (3.75M preferred + 1.67M common-equivalent) = $400M / 5.42M ≈ $73.80/share weighted average, vs. $80/preferred pure. The 25% secondary discount saved the lead ~$6.20/share on average.
- The seller pool receives $100M in liquidity distributed across the participating founders and employees, at $60/common — attractive at the target's typical common valuation of $18–25/common (the tender premium above the 409A is substantial).

## Interaction with the primary-round cap-table shuffle

Mod-104 chapter 3 introduces the concept of the **cap-table shuffle** during a primary round: the mechanics of pre-emptive rights, new-preferred issuance, option-pool refresh (top-up), and the resulting fully-diluted post-round cap. The tender-in-connection-with-financing overlays additional mechanics on top:

### Layer 1 — Pre-emptive rights and the primary round

Existing preferred holders typically have pre-emptive rights to participate in the primary round pro-rata based on their existing preferred ownership. The primary round's actual investor mix depends on which existing preferred holders exercise or waive their pre-emptive rights. If a preferred holder waives, their share of the round is available to the lead or other investors; if they exercise, their share reduces the amount available to the lead.

### Layer 2 — Option-pool refresh (top-up)

The primary round typically includes an option-pool refresh — the option pool is topped up to a target post-round percentage (often 10% of the fully-diluted post-round cap) to support anticipated hiring. The top-up dilutes the existing capital structure and is one of the specific numbers the target negotiates with the lead during the round.

### Layer 3 — The ROFR / co-sale process for the secondary

The secondary component runs through the ROFR / co-sale process (chapter 6). The target's board waives the company ROFR on the tender. The preferred holders' ROFR is typically waived (or, in some structures, exercised in the aggregate — some preferred holders may want to expand their position by taking on the tender-eligible shares themselves). The co-sale rights of the preferred pool are typically waived or determined not to apply.

### Layer 4 — The tender's actual participation

Employees and founders elect to participate (or not) in the tender at the specified terms. Actual participation may exceed the aggregate cap (triggering proration) or fall below it (leaving excess capital that either flows into additional primary or reverts to the buyer).

The interaction across these layers requires specific coordination during the round's approval and close process. The target's counsel and CFO run a coordinated timeline that syncs:

- Primary round documentation (SPA, revised charter, revised stockholders' agreement, revised voting agreement).
- Secondary tender documentation (Secondary SPA or Tender Offer document, participation election materials).
- ROFR / co-sale process for the secondary.
- Board resolutions covering both primary and secondary approvals.
- Preferred-holder consents and waivers.
- Cap-table update encompassing both primary and secondary components.
- 409A refresh triggered by the primary and secondary combined (chapter 8).

The coordination discipline determines whether the transaction closes cleanly in 60–90 days or drags to 120–180 days as coordination failures require re-work.

## Approval discipline — the combined board resolution

The board approval for a tender-in-connection-with-financing typically covers both components in a combined resolution:

- Authorising the primary preferred issuance and the primary round terms.
- Authorising the secondary tender at the specified price and cap structure.
- Waiving the company's ROFR on the specific transferring shareholders' shares up to the tender cap.
- Approving the amended and restated charter, stockholders' agreement, voting agreement, and ROFR / co-sale agreement.
- Approving the option-pool refresh.
- Approving the coordinated closing conditions and mechanics.

The board resolution is typically preceded by a detailed board memo — prepared by counsel and the CFO — walking through the entire round's economics, the primary-vs-secondary spread, the participation cap and expected participation, the ROFR / co-sale process, the 409A implications, and the fiduciary discipline supporting the approvals. The memo becomes part of the corporate records file and provides the durable justification for the board's decision.

## Participation-cap and eligibility discipline in the combined transaction

The tender's participation-cap and eligibility ruleset (chapter 2) applies with additional considerations in the round context:

### Consideration 1 — Executive-participation posture

At a growth-stage round with a $50M+ secondary component, the executive-participation posture becomes a specific board decision. Common patterns:

- **Full executive inclusion at reduced caps.** Executives can participate at, say, 50% of the highest employee cap, reflecting the round's context as broader workforce liquidity.
- **Founder-only additional cap.** Founders can participate at a founder-specific cap (typically the shape A founder secondary of chapter 1) alongside the broader employee tender. The founder's participation is bounded (10–20% of holdings) and formally treated as a founder secondary embedded in the tender documentation.
- **Executive exclusion with separate MIP.** Executives are excluded from the tender but participate in a separate management-incentive-plan or executive-liquidity structure at the same round (or shortly after) — typically at a separate compensation-committee-approved level with different terms.

### Consideration 2 — Investor-eligible seller pool

Some tender-in-connection-with-financing transactions include a defined class of *early investors* — the pre-Series-A angels, the accelerator programs, the friends-and-family investors — as eligible sellers in the tender. This lets a Series D provide liquidity to holders whose original investment was five to seven years ago and who have accumulated meaningful paper positions. Eligibility rules for the investor class typically require:

- Minimum holding period (typically 5+ years).
- Original-issuance requirement (invested directly at the target, not acquired through secondary).
- Non-affiliate status (not a current board member or executive).
- Compliance with the round's ROFR / co-sale mechanics.

### Consideration 3 — Aggregate-cap allocation across the seller pool

The buyer's aggregate committed capital for the tender may be prorated across founder / employee / investor tranches — for example, 40% to founders, 40% to rank-and-file employees, 20% to early investors. Each tranche has its own participation cap and its own proration mechanic within the tranche. The aggregate cap allocation is a specific design decision made at the round's close.

## Communications discipline

A tender-in-connection-with-financing has a specific communications choreography that differs from a pure primary round or a pure standalone tender:

- **Board and investor communication.** The board is fully briefed at the round's negotiation phase; the existing preferred holders are notified of the round (including the secondary component) at the pre-close consent stage.
- **Employee communication.** The tender is announced to the workforce simultaneously with the round's primary announcement. The messaging typically leads with the primary round (fresh capital, growth investment, strategic partnership with the lead) and describes the secondary as "employee liquidity offered in connection with the round" — subordinated to the primary in narrative even where the secondary is a large portion of the round's total.
- **External / market communication.** The primary round is typically the external headline; the secondary component is disclosed in the round announcement but is not the marketing point. Companies typically resist framing the round as "the founder took $X out" and emphasise the growth-and-primary framing.
- **Employee-education content for the tender.** The tender's participation-education content is delivered through the same channels as the tender's own execution (chapter 2) — CFO presentation, one-on-one Q&A, participant-education portal materials, per-participant tax-and-net-cash estimates.

## Failure modes and coordination pitfalls

Several specific failure modes worth naming:

**Failure mode 1 — Primary closes; secondary drags.** The primary round closes cleanly but the secondary component drags past the primary close due to eligibility administration, 409A refresh timing, or ROFR / co-sale friction. Employees who were counting on the tender proceeds by a specific date face cash-flow disruption; the round's overall narrative is diminished. Practitioner discipline: run the primary and secondary on a coordinated timeline with the same closing date; do not allow one to close ahead of the other.

**Failure mode 2 — Over-subscribed tender with insufficient buyer commitment.** The tender's aggregate cap is undersized relative to actual employee interest, and the proration mechanic yields much smaller cash-outs than participants expected. Employees are frustrated; the workforce-morale impact is negative. Practitioner discipline: size the tender's aggregate cap generously (typically at 1.5× to 2× the estimated required buyer commitment) and confirm the buyer's willingness to expand if participation exceeds expectations.

**Failure mode 3 — 409A refresh timing mismatch.** The tender's pricing implies a specific 409A refresh, but the 409A appraiser's timing does not align with the tender close. New option grants immediately after the tender close are made at a stale 409A price, creating potential §409A liability for the grantees. Practitioner discipline: pause new option grants during the tender's closing window and refresh the 409A immediately post-tender.

**Failure mode 4 — Preferred holder blocks secondary via ROFR exercise.** A preferred holder exercises the ROFR on the tender's secondary shares specifically to expand their position. The buyer's tender commitment is redirected in part to the exercising preferred holder rather than to the tender pool; the tender's aggregate cap is reduced. Practitioner discipline: negotiate ROFR / co-sale waivers in advance with the preferred pool at the round's design phase; obtain specific written waivers before the tender is announced to employees.

**Failure mode 5 — Executive-participation optics.** Executive participation in the tender is disclosed to employees who read it as unequal (executives cashing out disproportionately while rank-and-file receive small allocations). Workforce-morale impact is negative. Practitioner discipline: set executive-participation caps well below the highest employee cap; disclose the executive-participation posture in the tender's education materials transparently.

## Interaction with future exits — the disclosure footprint

Every tender-in-connection-with-financing generates a specific disclosure footprint that surfaces in future M&A definitive agreements and IPO S-1 filings:

- The primary round's SPA and the secondary tender's documentation are both filed as material contracts.
- The secondary tender's participants and their aggregate participation are disclosed at some level in the disclosure schedule.
- The 409A refresh that resulted from the tender is documented and available for review.
- The board's approval process for the combined transaction is documented in the corporate minutes.

Practitioner discipline: at the round's close, the target's finance and legal functions should organise the round's documentation package with the future disclosure use in mind — the SPA, the Secondary SPA, the tender documentation, the ROFR / co-sale waivers, the board resolutions, the 409A refresh — all filed in a way that can be handed to future M&A counsel or IPO counsel without a fire drill.

## Summary

The tender-in-connection-with-financing pattern combines a primary preferred round with an embedded secondary tender that clears alongside the primary close, allowing the lead investor to deploy full committed capital while providing pre-exit liquidity to founders, employees, and early investors. Pricing negotiations center on the primary-vs-secondary spread — typically 20–30% secondary discount to primary — with material implications for the 409A refresh and future option-grant strike prices. The primary-round cap-table shuffle (pre-emptive rights, option-pool refresh) combines with the ROFR / co-sale process for the secondary, the tender's participation-cap and eligibility ruleset, and the 409A refresh into a coordinated transaction requiring board resolutions covering both components in a single approval package. Communications discipline emphasises the primary as the headline with the secondary as companion mechanic. Failure modes include timing mismatches between primary and secondary close, under-sized aggregate caps, 409A refresh timing lag, preferred-holder ROFR exercise, and executive-participation optics. The disclosure footprint generated by the combined transaction becomes a specific asset in future M&A or IPO diligence. Chapter 8 turns to the 409A refresh cycle, Rule 701 aggregate-value monitoring, and the ownership boundary between this module and its adjacent tracks.
