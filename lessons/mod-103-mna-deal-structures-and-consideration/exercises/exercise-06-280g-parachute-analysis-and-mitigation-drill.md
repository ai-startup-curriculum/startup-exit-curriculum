# exercise-06: §280G Parachute Analysis and Mitigation Drill

**Estimated effort:** 3.5 hours

## Objective

For a hypothetical executive team, identify the disqualified individuals under §280G, compute each individual's base amount, identify their parachute payments, apply the 3x threshold, model the 20% excise-tax and lost-corporate-deduction impact, and design a mitigation package. Then decide whether a §280G(b)(5) shareholder vote is appropriate and, if so, draft the sequencing. By the end you should be able to advise the founder-CEO on their personal §280G exposure, present the corporation's aggregate §280G-cost picture to the board, and draft the mitigation package that reconciles executive-retention economics with §280G-clean transaction structure.

## Background

This exercise covers material from:

- [Chapter 6 — IRC §280G Golden-Parachute Analysis and Mitigation](../06-280g-parachute-analysis-and-mitigation.md)

Chapter 7 (§409A) governs the payment-timing constraints on parachute payments to service providers. Chapter 3 (earn-out) is relevant because earn-out payments to service providers can be parachute payments under §280G. Chapter 2 (consideration mix) provides the transaction context.

> **Education, not tax advice.** §280G analysis requires qualified tax counsel; the base-amount and parachute-payment calculations involve technical judgment and complex regulations. This exercise builds the framework — a live analysis is done with counsel.

## Prerequisites

- You have read chapter 6 in full.
- Familiarity with the §280G regulations (Treas. Reg. §1.280G-1) at a general level; specific Q&A citations are useful.
- Optional: a practitioner §280G primer from Cooley, Latham, WSGR, or Fenwick.

## The fact pattern

**Target:** Delaware C-corp being acquired by a publicly-traded strategic. Transaction closes at year-end. Target is a **private company** (not publicly traded), so §280G(b)(5) shareholder-vote cleanse is available.

**Transaction consideration:** $520M total; approximately 60% cash / 40% acquirer stock (as in exercise-02).

**Executive team subject to §280G analysis:**

| Executive | Role | Ownership | 5-year historical W-2 avg | Vested equity value at COC | Unvested equity value at COC (accelerated) | Cash severance | Transaction bonus |
|---|---|---|---|---|---|---|---|
| Founder A (CEO) | 6.5% | | $520,000 | $22M | $5M | $600k | $300k |
| Founder B (CTO) | 6.5% | | $460,000 | $22M | $3M | $500k | $200k |
| Founder C (Chief Product) | 5.0% | | $420,000 | $18M | $3M | $400k | $150k |
| Founder D (Chief Revenue) | 4.0% | | $450,000 | $15M | $4M | $500k | $200k |
| Head of Engineering (non-founder) | 1.3% | | $380,000 | $4.5M | $2.5M | $400k | $150k |
| Head of Sales (non-founder) | 0.8% (below 1%) | | $350,000 | $3M | $1.5M | $300k | $100k |
| Head of Finance (non-founder, CFO) | 1.1% | | $340,000 | $4M | $2M | $300k | $100k |
| Head of People | 0.4% (below 1%) | | $290,000 | $1.5M | $0.8M | $250k | $75k |

**Notes on the fact pattern:**
- "COC" = change of control. Values are what each executive receives due to the transaction.
- Vested equity value at COC reflects §280G's treatment: for equity vested before COC, the "acceleration of payment" (the moving up of the sale event) is a parachute payment only to the extent of the acceleration-time-value; for equity that vests *because* of COC, the full vested-at-COC value is generally a parachute payment.
- Cash severance is paid if the executive is terminated post-close without cause during a specified severance-eligibility period.
- Transaction bonus is paid at closing.
- Post-close retention: assume each executive has a 2-year retention agreement with additional equity grants; these are outside the §280G analysis (they represent reasonable comp for post-close services) but note where they could be problematic.

## Tasks

### 1. Identify disqualified individuals

Apply the §280G(c) definitions to each of the 8 executives:

- **Officers.** With 100+ employees, the officer count is capped at 50 or 10% of the workforce; assume 3-15 officers depending on cap. Which executives are officers?
- **Shareholders.** Any individual holding more than 1% of the corporation's stock (direct + indirect ownership under §318 attribution). Which of the 8 executives exceed 1%?
- **Highly-compensated individuals.** The lesser of the top 250 compensated employees or 1% of employees, with an income threshold (verify the current threshold from IRS guidance). Which executives qualify?

Produce a table:

| Executive | Officer? | Shareholder (>1%)? | Highly-compensated? | Disqualified individual? |
|---|---|---|---|---|
| Founder A (CEO) | | | | |
| ... | | | | |

### 2. Compute the base amount for each disqualified individual

Base amount = average of W-2 income (Box 1 wages, or as adjusted per §280G) for the 5 taxable years ending before the year of the change of control.

- For each of the 8 executives, apply the 5-year W-2 average given in the fact pattern.
- If the executive has been employed for fewer than 5 years, use the actual years employed. (Assume all 8 executives have 5+ year histories for this exercise.)
- Note: base amount uses W-2 income, not total compensation including equity gains, unless the equity gains flow through W-2.

Produce a table:

| Executive | Base amount | 3x base amount | 1x base amount |
|---|---|---|---|
| Founder A (CEO) | $520,000 | $1,560,000 | $520,000 |
| ... | | | |

### 3. Compute parachute payments for each disqualified individual

For each disqualified individual, identify all parachute payments — compensation payments *contingent on* the change of control. This includes:

- **Cash severance payable on qualifying termination.** All of it is a parachute payment if the termination occurs within the covered period around the COC.
- **Transaction bonuses paid at closing.** Fully parachute if paid contingent on COC.
- **Accelerated equity vesting.** For equity that vests because of COC, the value at COC time is a parachute payment (unless the equity would have vested independent of the COC — in which case only the acceleration-time-value is a parachute payment).
- **Vested equity payable at COC.** Trickier — for equity already vested before COC, the transaction-related payment is generally *not* a parachute payment for the value portion (the executive would have received it regardless of COC); only the acceleration of payment matters.
- **Continuation payments** (health, welfare) after termination — parachute if contingent on COC.
- **Earn-out payments** to executives who remain in service — potentially parachute payments (chapter 3 interaction).

Apply the "acceleration" rules from Treas. Reg. §1.280G-1 Q&A-24: for pre-COC-vested equity, only the "acceleration-time-value" is a parachute payment (typically a small fraction of the aggregate value); for equity that vests because of COC, the full value is a parachute payment.

Produce a table for each executive showing:

| Payment component | Total value | Parachute-payment portion | Rationale |
|---|---|---|---|
| Cash severance | | | |
| Transaction bonus | | | |
| Accelerated (unvested) equity | | | |
| Vested-before-COC equity — acceleration-of-payment portion | | | |
| Continuation benefits | | | |
| **Total parachute payments** | | | |

Then compute the parachute-payment-to-base-amount ratio:

| Executive | Total parachute payments | Base amount | Ratio (multiple) | Exceeds 3x? |
|---|---|---|---|---|
| Founder A (CEO) | | | | |
| ... | | | | |

### 4. Compute the excise-tax and lost-deduction impact

For each disqualified individual whose parachute payments exceed 3x base amount:

- **Excess parachute payment** = Total parachute payments minus 1x base amount.
- **20% excise tax** = 20% × Excess parachute payment (paid by the recipient under §4999).
- **Lost corporate deduction** = Excess parachute payment × 21% (lost federal corporate tax deduction under §280G(a)).

Produce a summary table:

| Executive | Excess parachute payment | Excise tax to recipient | Lost corporate deduction |
|---|---|---|---|
| ... | | | |
| **Aggregate corporate cost** | | | |

Compute the aggregate cost to the corporation (sum of the "Lost corporate deduction" column). This is the corporate-level economic cost of §280G in this transaction.

### 5. Design the mitigation package

For each disqualified individual whose parachute payments exceed 3x base amount, design a specific mitigation. Options from chapter 6:

- **§280G(b)(5) shareholder-vote cleanse.** Available for private-company targets; requires more than 75% of the target's disinterested shareholders to approve the parachute payments after full disclosure and after the disqualified individual makes their required disclosure and waives right to the payment absent approval. Requires specific procedural steps.
- **Cutback provision.** The parachute payment is automatically reduced to $1 below the 3x threshold, eliminating the excise tax. This preserves the executive's non-parachute payments (up to 3x base minus $1) but loses the incremental value above.
- **Value-shifting to reasonable-comp.** Reclassifying a portion of payments as reasonable compensation for post-close services (not a parachute payment). Requires documentation and defensibility.
- **Pre-close bonus payments outside COC-contingent window.** Payments made materially before the COC that are not contingent on COC can fall outside §280G. Requires timing and documentation.
- **"Best of both" / "modified cutback."** The executive is entitled to whichever produces higher after-tax value — full payment with excise tax, or cut back to 2.99x with no excise tax.

For each executive:

- **Recommended mitigation.** Name the specific approach.
- **After-mitigation cost.** For the corporation and the recipient.
- **Rationale.** Why this specific mitigation for this executive?

### 6. §280G(b)(5) shareholder-vote design

If your mitigation package uses the §280G(b)(5) shareholder-vote cleanse for one or more executives:

- **Which disqualified individuals will require a cleanse vote?**
- **Which shareholders vote?** The "disinterested" shareholders — those who are not themselves disqualified individuals receiving parachute payments. Compute the disinterested-shareholder base for this transaction.
- **Approval threshold.** More than 75% of the disinterested-shareholder vote.
- **Procedural steps.** Written disclosure of parachute payments to shareholders (typically a detailed summary of each disqualified individual's parachute payments), waiver of right to payment by disqualified individuals absent shareholder approval, shareholder vote timing (typically before the closing but after the transaction is announced), and documentation.
- **Timing sequencing.** When does the vote happen relative to signing and closing? Before signing? Between signing and closing? At what point does the disqualified individual waive their right to the payment?

Draft a 1-page **§280G(b)(5) sequencing memo** that would be shared with sell-side counsel to structure the cleanse vote.

### 7. Alternative-mitigation comparison

For one specific executive (e.g., Founder A the CEO) where §280G exposure is highest, model the alternative mitigations against the shareholder-vote cleanse:

| Mitigation | Executive after-tax value | Corporate after-tax cost | Complexity / risk |
|---|---|---|---|
| §280G(b)(5) shareholder vote cleanse | | | |
| Cutback to 2.99x base | | | |
| Value-shifting to reasonable-comp | | | |
| Pre-close bonus outside COC window | | | |
| Do nothing (accept the tax) | | | |

Recommend the specific mitigation and defend the choice.

### 8. Board memo

Draft a **1-page board memo** that:

- Names the disqualified individuals and their §280G exposure aggregate.
- Presents the recommended mitigation package.
- Notes the §280G(b)(5) shareholder-vote sequencing and any specific board-approval steps.
- Quantifies the aggregate corporate-cost savings from mitigation.
- Flags any residual §280G risk (e.g., positions taken that could be challenged on audit).

## Starter guidance

- **W-2 base amount is a technical calculation.** The regulations specify what counts as W-2 wages for the base-amount calculation; if an executive's compensation is heavily equity-based, the W-2 average may be lower than "total compensation" intuition suggests, making 3x base amount lower and more easily exceeded.
- **§280G(b)(5) vote is often the *cleanest* mitigation for private-company targets.** It preserves executive value while eliminating §280G tax. The procedural burden is real but manageable.
- **Cutback provisions can be traps.** A cutback provision that automatically reduces the executive's payment to 2.99x base amount avoids the excise tax but loses the incremental payment value. For executives whose parachute payments significantly exceed 3x, cutback is a big giveaway. The "best of both" / "modified cutback" (executive gets the higher-after-tax-value option) is usually preferred.
- **Value-shifting to reasonable-comp is defensible but requires documentation.** Reclassifying a portion of payments as post-close services requires supporting evidence — the executive has a specific post-close role, the reclassified amount reflects fair value for that role, etc. Casual reclassification without documentation invites IRS challenge.
- **Sequence matters for §280G(b)(5).** The cleanse vote must be held before the disqualified individual receives any parachute payment, and specific waiver / disclosure procedures apply. Getting the sequencing wrong voids the cleanse.

## Acceptance criteria

You can demonstrate that:

- Disqualified-individual analysis is complete for each of the 8 executives.
- Base-amount calculation is completed for each disqualified individual.
- Parachute-payment identification is complete, distinguishing the acceleration-of-payment portion from the full value for pre-COC-vested equity.
- Excise-tax and lost-deduction impacts are quantified per executive and in aggregate.
- Mitigation package is designed with specific approaches per executive.
- If a §280G(b)(5) vote is proposed, the sequencing memo is complete.
- Alternative-mitigation comparison is modelled for one specific executive.
- Board memo is 1 page and would be presentable.

## Reflection

Add a short reflection:

1. Which of the 8 executives has the largest §280G exposure relative to base amount? What drives it? Is it a heavy accelerated-equity component, a large severance, or a combination?
2. If the transaction had been structured so that the Founder-A's equity were fully vested one year before signing (rather than partly unvested), how much would the §280G exposure have changed? What does that suggest about compensation planning at the *founding company* level?
3. Which non-founder executive (Head of Engineering, Head of Sales, Head of Finance, Head of People) has the biggest §280G risk relative to base amount? What is driving it?
4. If the target were *public* instead of private, §280G(b)(5) shareholder cleanse would be unavailable. Which of your mitigations would you fall back on, and how much residual §280G cost would remain?

## Stretch goals

- **Read the Treas. Reg. §1.280G-1 Q&A.** The 44 Q&A of Treas. Reg. §1.280G-1 are the authoritative guide. Focus on Q&A 22-24 (parachute payments), Q&A 34-36 (base amount), and Q&A 6-9 (§280G(b)(5) cleanse mechanics). Cite specific Q&A in your analysis.
- **§280G-clean equity design.** Read Cooley / Latham / WSGR / Fenwick practitioner memos on §280G-clean equity-plan design. What features of an equity plan (double-trigger vesting, "single-trigger" avoidance, etc.) mitigate §280G risk at the design stage? How would you redesign this target's equity plan to reduce §280G exposure in a future transaction?
- **§4999 excise-tax withholding.** Read the withholding rules under §4999 and Treas. Reg. §1.4999-1. What are the corporation's withholding obligations on parachute payments? Note the practical mechanics.
- **Gross-up analysis (advanced).** Some executive employment agreements include a "gross-up" provision — the corporation pays the executive additional compensation to cover the §280G excise tax. This has been out of favor in recent years but persists in some agreements. If Founder A had a §280G gross-up in their employment agreement, what would the aggregate cost to the corporation be? Note that gross-up payments are themselves parachute payments (a recursive computation).
