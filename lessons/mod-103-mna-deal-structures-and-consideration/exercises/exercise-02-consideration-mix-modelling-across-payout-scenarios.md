# exercise-02: Consideration-Mix Modelling Across Payout Scenarios

**Estimated effort:** 4 hours

## Objective

Fix a specific cap-table waterfall and headline transaction value, then model three consideration structures (all-cash, mixed cash-and-stock, structured-consideration with rollover equity and a CVR) against that fixed waterfall. Derive the winners and losers across the four shareholder cohorts (founders, early employees, later employees, preferred investors) under each structure. By the end you should be able to (a) show the specific cell where a founder is meaningfully worse off under structure B than structure A, (b) name which shareholder cohort has veto-shaped incentives against which structure, and (c) present the three structures to a board as a "here is what each cohort receives" table that makes the trade-offs visible rather than latent.

## Background

This exercise covers material from:

- [Chapter 2 — Consideration-Mix Design Against the Cap-Table Waterfall](../02-consideration-mix-design.md)

Chapter 1 (form choice) constrains which consideration structures are available (an §368 tax-free stock reorg requires specific consideration-mix ratios). Chapter 8 (QSBS) determines the tax treatment of the cash and stock components at the shareholder cohort level.

> **Ownership boundary.** The cap-table maintenance and waterfall-computation *mechanics* are `startup-finance-fundraising-curriculum` mod-104. This exercise uses a pre-built waterfall as a transaction-input; if you are unfamiliar with how a preference-stack waterfall is constructed, spend an hour with mod-104's chapter 3 before starting this exercise.

## Prerequisites

- You have read chapter 2 in full.
- Familiarity with preference-stack waterfall computation, including 1x non-participating vs. participating preferred, conversion thresholds, and pari-passu vs. seniority-ordered preferred stacks.
- A spreadsheet tool (Google Sheets, Excel) — this exercise is a modelling exercise, not a memo-drafting one.

## The fixed cap-table waterfall

Use this fixed cap-table for the exercise:

**Company:** SaaS Co., Delaware C-corporation.

**Preferred stack** (junior to senior; each 1x non-participating with a converts-if-better provision):

| Series | Investment | Preference amount | Fully-diluted equity share |
|---|---|---|---|
| Series D | $80M | $80M | 22% |
| Series C | $50M | $50M | 15% |
| Series B | $30M | $30M | 12% |
| Series A | $15M | $15M | 10% |
| **Preferred subtotal** | **$175M** | **$175M** | **59%** |

**Common equivalents:**

| Cohort | Fully-diluted equity share | Notes |
|---|---|---|
| Founders (4 co-founders combined) | 22% | Each holds ~5.5%; all §1202 QSBS with >5-year holding, minimal basis |
| Early employees (first 15 employees) | 8% | Options exercised, held >5 years, some §1202 QSBS |
| Later employees (~40 employees, options mostly unexercised) | 8% | Options; if exercised at transaction, no QSBS on later grants |
| Option-pool overhang (unallocated) | 3% | Unallocated pool |
| **Common subtotal** | **41%** | |

**Total fully-diluted:** 100%.

**Headline transaction value:** $520 million (as in exercise-01 fact pattern 1).

**Fixed additional numbers:**
- Escrow: 8% of consideration to be held for 18 months (chapter 4).
- Working-capital adjustment: assume closing WC hits the target, so no adjustment.
- Transaction expenses (banker, legal, accounting): $12M paid at closing off the top before shareholder distribution.
- No management-incentive plan (MIP) / retention pool assumed for this exercise — assume any retention is handled outside the consideration (chapter 6 addresses §280G-driven retention design separately).

## The three consideration structures to model

Build a spreadsheet with three sheets, one per structure. Each sheet computes the payout per cohort under identical waterfall inputs but different consideration mixes.

### Structure A: All-cash

$520M paid entirely in cash. $12M expenses off the top. $8% escrow ($40.6M) held 18 months. Net cash at closing to shareholders: $520M - $12M - $40.6M = $467.4M. Escrow release assumed to occur cleanly at month 18 in the base case; you should show the payout both including and excluding escrow return.

### Structure B: Mixed cash-and-stock

$520M: 60% cash ($312M) / 40% acquirer stock ($208M at signing VWAP). No CVR. Structure the merger to qualify as a §368(a)(1)(A) reverse-triangular merger with §368(a)(2)(E) tax-free treatment on the stock portion? *Check the consideration-mix requirement in chapter 1 (80% stock for RTM tax-free treatment)* — decide whether this mix qualifies or requires a forward-triangular structure with 50% minimum stock. Document your choice.

Assume acquirer is publicly traded, no lock-up on the stock (or a 6-month lock-up for founders / executives only). Escrow: 8% of the total consideration. You can choose how to allocate escrow between cash and stock components (this is a design choice — document it).

### Structure C: Structured — cash + rollover equity + CVR

$520M: 55% cash ($286M) + 25% rollover equity ($130M into acquirer parent / holding company, structured for §351 or §368 tax-free rollover) + 20% CVR ($104M contingent on product-integration milestone measured 24 months post-close, all-or-nothing).

- **Rollover eligibility.** Founders and top 5 executives are eligible for rollover; other shareholders receive their pro-rata share in cash.
- **CVR.** Payable pro-rata to all shareholders if the milestone is achieved; forfeit if not. Document your assumption about the probability of achievement (base case: 60%).
- **Escrow.** 8% of total consideration; you can carve escrow off either the cash or the rollover portion (document choice).

## Tasks

### 1. Set up the waterfall computation

Compute the waterfall for the aggregate $520M consideration first — before layering on the mix. For each series of preferred, determine whether they take their preference or convert to common (the 1x non-participating "greater of" analysis). Build the per-cohort dollar allocation table.

Show the result as a table:

| Cohort | Dollar allocation | Percentage of total |
|---|---|---|
| Series D preferred | | |
| Series C preferred | | |
| Series B preferred | | |
| Series A preferred | | |
| Founders | | |
| Early employees | | |
| Later employees | | |
| Option-pool overhang | | |
| **Total** | **$520M** | **100%** |

This is your baseline. Structures A, B, C all pay this waterfall in different currencies; the underlying dollar allocation to each cohort is the same at signing (assuming the CVR and rollover are priced at face value at signing — model that assumption and then also model the risk-adjusted values).

### 2. Model Structure A (all-cash)

For each cohort, compute:

- **Cash at closing.** After transaction expenses and escrow.
- **Cash from escrow release at 18 months** (assume 100% return in the base case).
- **Total nominal cash received.**
- **Federal tax paid.**
  - Founders: §1202 exclusion applies up to the greater of $10M or 10x basis (assume $10M cap effectively binds for each founder). Excess taxed at long-term capital gains (23.8% including NIIT).
  - Early employees: §1202 for the qualifying stock portion (assume most of their equity is QSBS-eligible; the remainder is long-term capital-gain).
  - Later employees: Assume options are exercised at closing; the compensation portion of the gain is taxed at ordinary rates (37%+NIIT for high earners), the capital portion at long-term cap gains rates. Simplify — assume 80% is ordinary income for later employees.
  - Preferred investors: assume corporate entities (VC funds are usually LPs distributing to LPs; treat the fund itself as the taxpayer at 21% federal corporate rate; ignore the LP-level pass-through for this exercise). Or treat as tax-neutral to focus on the founder / employee cohorts.
- **After-tax cash per cohort.**

### 3. Model Structure B (mixed cash-and-stock)

For each cohort:

- **Cash portion at closing (60% of allocation, less pro-rata escrow).**
- **Stock portion at closing (40% of allocation).**
- **Tax on the cash portion (§1202 for QSBS holders where applicable; ordinary income for later-employee compensation portion).**
- **Tax on the stock portion.** If the §368 reorg qualifies, no current tax on the stock portion (deferred until later sale). If it doesn't qualify (the mix is 40%, likely below the RTM 80% threshold), the stock portion is boot — currently taxable. Document your reorg-qualification analysis and its consequences.
- **Stock lock-up impact.** If there's a 6-month lock-up on founder / executive stock, note the acquirer-stock-price volatility exposure. Do a sensitivity: what if acquirer stock is down 20% at end of lock-up?
- **After-tax value per cohort at closing.** Then show a *post-lock-up* value under stock-down-20% and stock-up-20% scenarios.

### 4. Model Structure C (cash + rollover + CVR)

For each cohort:

- **Cash portion (55% of allocation, less pro-rata escrow).** For non-rollover-eligible cohorts, this is a larger share of their allocation because rollover-eligible cohorts have their rollover portion redirected. Do the arithmetic carefully.
- **Rollover portion (25% for eligible cohorts; 0 for others).** Tax-deferred if the rollover qualifies as tax-free under §351 / §368 (assume it does; document requirements).
- **CVR portion (20% for all cohorts).** Face value at signing $104M pro-rata across the waterfall. Show:
  - **Face-value value per cohort.**
  - **Risk-adjusted value** at 60% probability of achievement: $62.4M pro-rata across waterfall.
  - **Realised value** if the CVR pays out fully (100% achievement).
  - **Realised value** if the CVR is forfeit (0% achievement).
- **Illiquidity discount on rollover.** Rollover equity in a private (or newly public) acquirer is illiquid until the acquirer itself has a liquidity event or the securities are registered for resale. Apply an illiquidity discount to rollover equity — 20% is a reasonable base-case; some CFOs would argue 15%, others 30%. Document your choice.
- **Total risk-adjusted value per cohort at closing.**

### 5. The winner-loser matrix

Build a summary table comparing all three structures across the four common cohorts (founders, early employees, later employees, preferred investors):

| Cohort | Structure A total after-tax | Structure B after-tax at signing | Structure B after-tax at lock-up (base / down-20 / up-20) | Structure C risk-adjusted after-tax | Structure C worst-case (CVR forfeit, illiquid rollover) | Structure C best-case (CVR paid, rollover appreciates) |
|---|---|---|---|---|---|---|
| Founders | | | | | | |
| Early employees | | | | | | |
| Later employees | | | | | | |
| Preferred (aggregate) | | | | | | |

For each cell that materially diverges (say, > 10%), note the specific driver in the underlying model.

### 6. Cohort-preference analysis

For each of the four cohorts, name their **most-preferred** and **least-preferred** structure among A, B, C, and explain why in 1–2 sentences grounded in the numbers.

Then answer:

- **Which cohort has the strongest structural veto?** In this cap table, could any single cohort block a structure? (E.g., does Series D preferred have a class-vote right that prevents a specific structure? Assume standard NVCA-model charter provisions; if you need to make assumptions, document them.)
- **Where is the deepest founder-vs-preferred tension?** In which structure do founders come out worst relative to preferred? What is driving it?
- **Where is the deepest early-employee-vs-later-employee tension?** Options exercised recently (later employees) may not have QSBS treatment; the same absolute dollar allocation can be taxed very differently. What does this suggest for MIP / retention design?

### 7. The board memo

Draft a 1-page board memo that presents the three structures and recommends one. Include:

- The three structures in one table (nominal, risk-adjusted, and worst-case values by cohort).
- The recommendation and the 3 key reasons.
- The specific cohort dissent you anticipate (which cohort will vote against, and what would move them).
- The negotiation asks you would take back to the buyer to improve the structure (e.g., "lift the stock portion in Structure B to 80% and structure as an RTM §368 tax-free reorg to preserve QSBS treatment on the stock portion").

### 8. Sensitivity: what happens at a lower headline?

Repeat the model at a headline of $360M (30% below the LOI number, as a downside scenario). At $360M:

- Do any preferred series still convert to common under Structure A, or do all take preference?
- How does the founder allocation change across the three structures?
- Does any structure become materially worse under the downside — e.g., a CVR that was 60% likely at $520M might be 20% likely at $360M?
- Does any cohort come out with *nothing* under a specific structure in the downside?

Write a ½ page summary of what the downside reveals.

## Starter guidance

- **Do the math carefully.** The waterfall is where errors happen — a Series C preferred that converts under one structure but takes preference under another is a common transcription mistake. Build the "greater of" test explicitly in a cell.
- **Split QSBS treatment by shareholder, not by series.** A founder's $10M QSBS exclusion caps at $10M; if the founder's allocation is $28M, the $18M excess is fully taxable. Multiple founders each have their own $10M cap (per issuer). Model this per shareholder, not as a pool.
- **Rollover tax treatment.** For rollover equity to be tax-free, the specific mechanics matter — typically a §351 rollover into the acquirer's parent holding-company under a plan-of-reorganisation structure, or a §368(a) reorg. Assume qualifying structure for this exercise but note in your memo that a live transaction confirms this with tax counsel.
- **CVR probability estimation.** Do not spend hours calibrating a probability — 60% base case is fine. What matters is the sensitivity: model at 30%, 60%, and 90% and show what changes.
- **Illiquidity discount defensibility.** 20% is defensible from the practitioner literature. If you use a different number, cite something.

## Acceptance criteria

You can demonstrate that:

- The baseline $520M waterfall is computed correctly by cohort.
- All three consideration structures (A, B, C) are modelled and produce per-cohort dollar allocations, after-tax outcomes, and risk-adjusted values.
- The winner-loser matrix (task 5) is complete and consistent with the underlying model.
- The cohort-preference analysis names most / least preferred structures with numerical justification.
- The board memo (task 7) is 1 page and would be presentable at the next board meeting.
- The downside sensitivity (task 8) at $360M has been modelled and interpreted.

## Reflection

Add a short reflection:

1. Which cohort's preferences did you find most surprising once the numbers came in? Was there a case where a cohort you expected to prefer Structure A actually did better under Structure C, or vice versa?
2. If founders each have a $10M §1202 cap and their gross allocation exceeds $10M under all three structures, what is the marginal tax difference *for the excess*? What does that suggest about the marginal negotiating value of pushing for a §368 reorg on the stock portion?
3. What is the *single* line in your model that, if changed by 10%, moves the recommendation from one structure to another? What does that fragility say about the confidence you should have in the recommendation?
4. If the acquirer counter-proposed a fourth structure — 30% cash / 30% acquirer stock / 30% rollover / 10% CVR — where would that fall against the three you modelled?

## Stretch goals

- **§280G interaction.** Model the retention / MIP layer at $10M for the top 5 executives distributed pro-rata across founders. Run the §280G base-amount analysis (chapter 6) for one founder-CEO with a 5-year historical W-2 average of $500k. Does the parachute-payment threshold trigger? How does the consideration structure interact with the parachute analysis?
- **§409A on the CVR.** For Structure C's CVR, is the CVR §409A-compliant? The short-term-deferral exception (chapter 7) generally requires payment within 2.5 months after the end of the year in which the substantial risk of forfeiture lapses; a 24-month milestone-based CVR is usually structured to fit within §409A but the analysis is specific.
- **Public-acquirer stock volatility model.** For Structure B, pull the last 24 months of the acquirer's stock returns (or the sector index, if the acquirer is anonymised). Compute the historical volatility and use it to construct a collar (chapter 2) that limits founder exposure to acquirer-stock-price moves during the lock-up. What collar (floor, ceiling) would you propose?
- **§1045 rollover for a pre-5-year holder.** Add a fifth cohort: one recent-grant executive who holds §1202-eligible stock with a 4-year holding period at closing. Model the §1045 rollover option (chapter 8) — sale, 60-day reinvestment in a new QSBS issuer, deferral of the gain. Is this operationally plausible for this executive? What would the personal-planning conversation look like?
