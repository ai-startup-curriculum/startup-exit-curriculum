# exercise-01: Endgame Outcome Comparison Under a Specific Context

**Estimated effort:** 2 hours

## Objective

Take one specific growth-stage startup — real or a realistic hypothetical you build for this module — and produce a defensible endgame outcome comparison across the five candidate outcomes and the six trade-off axes. The output is the *analytic core* that the capstone endgame-optionality memo (exercise-05) will sit on top of. By the end you should be able to defend a ranking of the outcomes to a critical reader and name the specific conditions under which the ranking would flip.

## Background

This exercise covers material from:

- [Chapter 1 — Framing the Endgame Decision](../01-framing-the-endgame-decision.md)
- [Chapter 2 — Trade-offs and Operating-Decision Consequences](../02-tradeoffs-and-operating-consequences.md)

You do not yet need the buyer map (chapter 3), the market-window dashboard (chapter 4), the operating audit (chapter 5), or the memo template (chapter 6). Those come in later exercises. The point of this exercise is to install the discipline of *ranking the outcomes* against a *specific context* rather than reasoning about them in the abstract.

## Prerequisites

- A specific company profile to reason against. If you have a real company (yours, a portfolio company, a client), use it and redact where sensitive. If not, build a *realistic* hypothetical using the profile schema below — no cartoon numbers. Freeze it at the start; do not let it drift as you work.
- Comfort reading a cap-table waterfall at rough scale. If preference-stack math is unfamiliar, review `startup-finance-fundraising-curriculum` mod-104 / mod-106 first — this exercise assumes the mechanic is installed.

## The company profile

Fill in this profile at the top of your deliverable. If any field does not apply, note *why* rather than skipping.

- Company name (or codename): _____
- Sector / product one-liner: _____
- Stage: SEED / SERIES-A / SERIES-B / SERIES-C / GROWTH / MATURE
- ARR (or MRR × 12): $_____
- YoY growth rate: _____%
- Net dollar retention: _____%
- Gross margin: _____%
- Cash on hand: $_____
- Monthly burn (net): $_____
- Runway at current burn: _____ months
- Cumulative capital raised: $_____
- Cumulative liquidation-preference stack: $_____ (with a one-line note on participation / non-participation and any caps)
- Last 409A common per share: $_____
- Last-round preferred per share: $_____
- Top-1 customer as % of ARR: _____%
- Top-10 customer concentration as % of ARR: _____%
- Team size: _____
- Notable single-person dependencies (dual-founder split, sole-CTO, key sales leader): _____

## Tasks

### 1. Name the five candidate outcomes for this specific company

For each of the five outcomes (acquisition, IPO, secondary liquidity, stay-independent, responsible shutdown), write one paragraph naming what that outcome would *actually look like* for this specific company. Do not describe the outcome in the abstract — describe the shape it would take given the profile above.

- If an outcome is not realistically live for this company, say so and defend why. (E.g., "IPO is not live within the 18-month planning horizon because ARR is $6M and the sector-typical IPO threshold is $200M.")
- If an outcome has sub-shapes worth distinguishing (e.g., cash-heavy vs. stock-heavy acquisition, direct listing vs. bookbuilt IPO), name the sub-shape you think most likely.

### 2. Score each outcome on the six axes

Build a matrix with the outcomes as rows and the six axes as columns:

| Outcome | Control | Capital | Time-to-outcome | Employee outcomes | Personal-brand | Investor-return distribution |
|---|---|---|---|---|---|---|
| ... | ... | ... | ... | ... | ... | ... |

Each cell contains:

- A short qualitative score (Low / Medium / High, or 1–5), *and*
- A one-line justification anchored to a *specific fact from the profile* (e.g., "Low — post-close founder role is a negotiated term, and 42% preferred concentration in two funds means their preferences drive the sale process").

Cells without a fact anchor are not defensible. Rewrite until every cell has one.

### 3. Run a rough waterfall at three price points

For the two acquisition sub-shapes you named in task 1, compute a rough waterfall at three plausible acquisition prices:

- **Low anchor** — approximately the cumulative preference stack.
- **Medium anchor** — approximately 2× the cumulative preference stack.
- **High anchor** — approximately 3–5× the cumulative preference stack (whatever is the plausible-optimistic anchor for your company).

Compute what common shareholders (founders + employees) net at each price. Round math is fine — this is an endgame frame, not a distribution schedule. The output is a small table: price × preferred payout × common payout × common-per-share.

You are looking for one specific signal: *at which price does the acquisition path start being interesting for common holders*, and how does that compare to plausible acquirer offers? Note the finding at the end of the table.

### 4. Rank the outcomes with justification

Produce an explicit 1st / 2nd / 3rd / 4th / 5th ranking of the outcomes for this company today. For each rank:

- One sentence naming the outcome.
- Two-to-three sentences justifying the rank against the axes and the waterfall.
- One sentence naming the single most important condition that would demote or promote this outcome.

If the current cap-table structure forces a specific ordering (as it often does), name that explicitly rather than pretending the ordering is a free choice.

### 5. State the flip conditions

Write a short "what would flip the ranking" section:

- What specific event or trend would flip #1 → #2?
- What specific event or trend would flip #2 → #1?
- What condition, if it occurred, would remove one of the outcomes from the ranking entirely?

Each flip condition is a specific, testable statement. "The market gets worse" is not a flip condition; "the Bessemer Cloud Index compresses another 20% from current levels sustained for two quarters" is.

## Starter guidance

A defensible deliverable is 4–6 pages including the profile, the six-axis matrix, the waterfall table, the ranked list with justifications, and the flip-condition section. If it is longer, you are over-writing; if it is shorter, you are under-reasoning.

Two anti-patterns to watch out for:

- **The optimistic-outcome bias.** You will be tempted to score IPO or high-price acquisition favourably on control, capital, and personal-brand because those are the outcomes you'd prefer. Score against *facts*, not preferences. If the preference stack forecloses a common-friendly outcome below $Y, say so.
- **The "we don't need shutdown" bias.** Some learners skip or dismiss the responsible-shutdown row. Fill it in even if it is not currently live — the analytic value is in seeing what would need to be true for it to become live.

## Acceptance criteria

You can demonstrate that:

- The company profile is filled in with specific numbers, not placeholders.
- Each of the five outcomes has a paragraph anchored to the profile — not a generic description.
- The six-axis matrix has every cell filled with a score *and* a fact-anchored one-liner.
- The waterfall table shows what common holders net at three price points, with the finding named.
- The ranking is explicit (numbered 1–5) with two-to-three sentences of justification per outcome.
- The flip-condition section names at least three specific, testable conditions.
- A critical reader could disagree with a specific cell or rank and point to *what fact would need to change* to move it.

## Reflection

At the end of your deliverable, add a short reflection (½ page) answering:

1. Which outcome surprised you in its ranking — either higher or lower than your intuition before you did the axis scoring?
2. Which single fact from the profile most heavily constrains the ranking? (Often: cumulative preference stack, or customer concentration, or founder-personal situation.)
3. What operating change, if made this quarter, would most materially improve the ranking of your #2 outcome relative to #1?

Carry the reflection forward into exercises 04 and 05.

## Stretch goals

- **Sensitivity analysis.** Rerun the six-axis matrix under a scenario where ARR growth compresses to 40% YoY for two quarters (the market-window-compression sensitivity). Does the ranking flip?
- **Second company comparison.** Repeat the exercise for a second company with a materially different cap-table shape (e.g., much lower preference stack) and note which of the frame's outputs depend on the cap table vs. on the operating story.
- **Adversarial red-team.** Have a peer or advisor read the deliverable and try to break the ranking. Update the flip-condition section with any conditions their challenge exposes.
