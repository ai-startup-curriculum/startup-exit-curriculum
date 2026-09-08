# exercise-02: Employee Tender Offer Design and Waterfall Drill

**Estimated effort:** 5–6 hours

## Objective

Design a defensible employee tender offer for a specific hypothetical target — pricing methodology, eligibility rules, participation caps, waterfall analysis, per-category tax withholding, and operational choreography — and produce two deliverables: (a) a tender-design memo (10–14 pages) that a compensation committee and board could approve, and (b) a participant-education pack (4–6 pages plus a per-participant estimated-outcome worksheet template) that lets a rank-and-file employee understand their after-tax result *before* they submit an election. At the end you should be able to defend the tender's pricing to the lead investor, its eligibility rules to the workforce, its withholding mechanics to the finance function, and its clearing choreography to Carta / NPM / Shareworks.

## Background

This exercise covers material from:

- [Chapter 2 — Employee Tender Offer — Pricing, Eligibility, Participation Caps, and Operational Choreography](../02-employee-tender-offer-design.md) — the three pricing methodologies, the eligibility ruleset, the participation caps, the operational choreography.
- [Chapter 3 — Tender Waterfall Analysis and Tax Treatment — Preference Stack, ISO vs. NSO vs. RSU](../03-tender-waterfall-and-tax-treatment.md) — the waterfall analysis that anchors a defensible common price, the four tax-treatment categories, and the withholding operational discipline.

Supporting references:

- [Chapter 6 — ROFR and Co-Sale Choreography](../06-rofr-and-co-sale-choreography.md) — the tender's overall approval package folds in the ROFR / co-sale waivers.
- [Chapter 8 — 409A Refresh Cycles, Rule 701 Interaction, and the Ownership Boundary](../08-409a-refresh-and-ownership-boundary.md) — the tender's pricing decision may trigger a 409A refresh and consumes Rule 701 capacity through same-day exercises and RSU settlements.

## Prerequisites

- The hypothetical target you carried through the prior exercises (or a comparable growth-stage venture-backed profile with a multi-series preference stack).
- A cap table with (at minimum): common share count, each preferred series' share count and per-share issue price with liquidation preference, the current option pool with outstanding ISO / NSO grants and RSU grants, and the current 409A common price.
- Access to a spreadsheet (Excel, Google Sheets, or a Python notebook with `pandas` / `numpy`) that can model a waterfall analysis across a range of exit valuations.
- Familiarity with the SEC Rule 13e-4 tender-offer mechanics (as an analogue for the private-company tender's structural discipline) and IRS tax-withholding categories for equity compensation.

## Tasks

### 1. Set the target-and-cap-table baseline

Write a 1-page target baseline covering:

- **Target profile** — sector, ARR, growth, headcount (with breakdown by function and by tenure), most-recent primary round (date, per-share preferred price, headline valuation, lead investor), current cash position.
- **Cap-table shape** — total common outstanding, each preferred series (shares, per-share issue price, liquidation preference, participation vs. non-participation, dividend-accrual posture), option pool outstanding (ISO share count with average strike, NSO share count with average strike, RSU share count granted-but-not-settled).
- **409A cadence** — the current 409A common price and the last-appraisal date.
- **Tender context** — is this a standalone routine tender (self-funded or existing-investor-funded), a tender-in-connection-with-financing (tender funded by the primary-round lead — cross-reference exercise-06), or a specific-secondary-buyer-funded tender? What is the transaction's proximate trigger and what is the target buyer identity?

### 2. Choose the pricing methodology and defend the choice

From chapter 2's three approaches:

- **Approach 1** — last-round preferred price.
- **Approach 2** — common-share equivalent (preferred with a discount).
- **Approach 3** — secondary-market-clearing price.

Choose the approach that fits the fact pattern and write a 1-page defence covering:

- Why this approach fits the tender's context and buyer identity.
- The specific per-share tender price under the chosen approach.
- The economic argument for the price (waterfall-derived defence, secondary-market comparable, buyer's negotiated willingness-to-pay).
- The 409A refresh implication (chapter 8) — whether the tender price is materially different from the current 409A and whether a refresh will be triggered.
- The employee-communications implication — how the pricing relationship to the last-round preferred will be explained to participating employees.

### 3. Build the waterfall model

Produce a waterfall model in your chosen spreadsheet or notebook environment covering:

- **Preference-stack payout at each exit valuation** — for each preferred series, compute the greater of (a) preference payout at that series' preference amount, or (b) as-converted common payout at that valuation. Model the series-by-series conversion decision.
- **Common payout at each exit valuation** — after preferred takes preference or converts (whichever yields more per series), compute the residual proceeds distributed pro-rata across common (including converted preferred at those series that convert).
- **The common-per-share curve** — plot common's per-share payout as a function of exit valuation across a range from below the preference stack (common receives ~$0) through 5× current implied valuation (common approaches the converted-per-share ceiling).
- **The tender-price defensibility check** — identify the exit valuation at which common's per-share equals the tender price. Comment on whether that valuation is a plausible exit for the target.

Include the model file (or a clear specification of it) as a deliverable of the exercise.

### 4. Design the eligibility ruleset

Draft the tender's eligibility rules covering:

- **Employment status** — current employees included, treatment of recent former employees (within a defined window), treatment of advisors / consultants / contractors, treatment of board members and non-employee investors.
- **Tenure requirement** — minimum months of continuous employment (12 or 24 typical), treatment of employees hired-and-re-hired, treatment of acqui-hire employees whose tenure clock resets vs. carries over.
- **Executive exclusion** — whether the tender is available to the executive team, and if so with what specific per-executive cap or with a separate executive tranche.
- **Pre-vest exclusion** — the tender operates on vested shares only; the mechanics for confirming vesting as of the record date.
- **Share-class eligibility** — which share classes participate (typically common only; explicit exclusion of preferred).
- **Record date and cutoff mechanics** — the specific date at which eligibility is checked.

For each rule, note the securities-law and employment-law defence — why the rule is defensible, and what alternative rule you rejected.

### 5. Size the participation caps

Draft the tender's participation cap structure covering:

- **Per-employee cap** — the maximum shares (or dollars) a single employee can tender. Options: fixed dollar cap (e.g., $500K per employee), fixed percentage of vested holdings (e.g., 25% of vested), or level-based cap (e.g., different cap for individual contributor vs. senior IC vs. management vs. director+). Choose and defend.
- **Aggregate-round cap** — the maximum total dollars the buyer will commit to the tender. Anchored to the buyer's committed capital.
- **Proration mechanics** — if the aggregate demand from participating employees exceeds the aggregate cap, how the buy is prorated back. Standard practice: pro-rata by requested amount.
- **Rounding** — how fractional shares are handled at proration.

Compute the projected aggregate tender demand under the eligibility ruleset and the projected cap-hit ratio. Where the demand is likely to exceed the aggregate cap, model the proration.

### 6. Work the four tax-treatment categories

For four representative participant profiles, produce a specific per-participant estimated-outcome worksheet:

- **Profile A — Already-held common shares (long-term).** An employee holding 5,000 shares of common acquired more than one year ago via early-exercised ISO at $2/share basis. LTCG treatment; §1202 QSBS analysis (assume the founding grant is §1202-qualifying if held from founding; the employee's shares are §1202-qualifying if they were exercised early during the QSBS holding period).
- **Profile B — Same-day cashless NSO exercise.** An employee tendering 3,000 same-day-exercised NSOs at $12/strike. Ordinary compensation treatment on the spread; federal supplemental withholding (22% up to $1M, 37% above), FICA (SS wage base + Medicare 1.45% + additional Medicare 0.9% above $200K), state withholding.
- **Profile C — ISO qualifying disposition.** An employee tendering 4,000 ISO-exercised shares held more than 2 years since grant and more than 1 year since exercise. LTCG treatment on the entire spread from strike to tender price; AMT considerations at the earlier exercise year.
- **Profile D — RSU settle-and-tender.** An employee tendering 2,000 RSUs settled at the tender window. Ordinary compensation treatment on the settlement value; supplemental withholding at the settlement; capital-gain treatment on the settle-to-tender delta (usually zero because settlement and tender are same-day).

For each profile, compute: gross tender proceeds, exercise cost (if applicable), federal withholding, FICA withholding, state withholding, net cash to participant, and W-2 reporting. Include the specific arithmetic (do not just cite the rules).

Produce a per-participant worksheet template that a tender administrator (Carta / NPM / Shareworks) could populate mechanically for each employee's specific position and residence.

### 7. Design the operational choreography

Draft the tender's operational choreography covering:

- **Administrator selection** — Carta vs. Nasdaq Private Market vs. Shareworks vs. transfer-agent-in-house. Defend the choice against the tender's size, complexity, buyer identity, and target's existing cap-table infrastructure.
- **Timeline** — a 60–90 day timeline from board-approval through close, with specific milestones: board approval, tender documentation drafted, securities-counsel review, tender open, participant elections, close, settlement, post-close cap-table update.
- **Documentation package** — the tender-offer document itself, the participant-education pack, the per-participant estimated-outcome worksheet, the election form, the FAQ document.
- **Tender-open window** — at least 20 business days (matching SEC Rule 14e-1 minimum even where not technically required for a private-company tender).
- **Communications plan** — how the tender is announced to the workforce, the participant-education sessions (all-hands, small-group sessions, 1:1 sessions for large positions), the escalation channels for questions.
- **Settlement mechanics** — how the buyer's funds move into the settlement account, how the withholding is remitted to tax authorities, how the net cash reaches each participant's account, and how the cap table is updated post-close.

### 8. Draft the participant-education pack

Author a 4–6 page participant-education pack suitable for delivery to the workforce, covering:

- **What the tender is** — a bounded liquidity event with defined terms.
- **Who is eligible** — the eligibility rules in plain language.
- **The price and how it was set** — the pricing methodology and the waterfall context that anchors it.
- **The four tax-treatment categories** — what each category means and which one applies to which type of holding.
- **The per-participant worksheet** — how to use the estimated-outcome worksheet to see your specific after-tax result before you elect.
- **The election window and mechanics** — how to submit an election, the deadline, and how to withdraw before deadline.
- **What happens at close** — settlement timing, the net cash you receive, the W-2 impact if applicable, and where to direct questions.
- **A clear disclaimer** — the company does not provide personal tax advice; participants should consult their personal tax advisors, and the pack references the tender-administrator's participant portal for the specific arithmetic.

### 9. Draft the board-and-compensation-committee approval package

Draft a 3–5 page approval package for the board and compensation committee covering:

- The tender's overall design (pricing, eligibility, cap, timeline, administrator).
- The waterfall defence of the pricing.
- The eligibility ruleset's defence.
- The 409A refresh implication and the coordination with the appraiser.
- The Rule 701 aggregate-value impact from same-day exercises and RSU settlements.
- The compensation-committee decisions required (executive-exclusion policy, executive-participation cap if any, per-employee cap).
- The board resolutions required (approve the tender, waive the company's ROFR, authorise the administrator engagement, authorise the officer signing authority).

## Starter guidance

Common tender-design errors to avoid:

- **Pricing at last-round preferred without a waterfall defence.** Overpays for common relative to preference-stack-adjusted common value, triggers a 409A refresh at inconvenient timing, and communicates to participants a paper number that does not reflect the security's actual worth.
- **Skipping the pre-election per-participant worksheet.** Participants elect expecting one net number and receive a materially different amount at close; the compensation committee gets a stream of individual complaints. The worksheet is the participant-education pack's most important artefact.
- **Eligibility rules that read as arbitrary.** Excluding a specific team or level without a defensible rationale creates employment-law and morale exposure. Every exclusion should have a plain-language defence.
- **Under-sizing the per-employee cap for high-tenure ICs.** A 25%-of-vested cap that lets a director-level IC tender $2M while a senior IC with the same vested position can only tender $500K reads as level-based bias rather than genuine cap discipline.
- **Ignoring Rule 701 aggregate-value impact.** A large tender with many same-day exercises and RSU settlements can consume the target's Rule 701 capacity for the year and force the target to defer other equity grants. The finance function should be coordinating with securities counsel on the aggregate-value calculation.
- **Assuming the administrator will drive the design.** Carta / NPM / Shareworks administer the tender; they do not design it. The design decisions (pricing, eligibility, cap) belong to the target's finance, legal, and compensation-committee functions.
- **Timing the tender-open window against a fundraising or M&A milestone.** A tender open during a live sell-side, or during the SEC's IPO quiet period, is a governance problem the target does not want to run.

## Acceptance criteria

You can demonstrate that:

- Target-and-cap-table baseline is written with the multi-series preference stack modelled.
- Pricing methodology is chosen from the three approaches with a defended rationale and a specific per-share price.
- Waterfall model is built and produces the common-per-share curve as a function of exit valuation; the tender-price defensibility check identifies the break-even exit valuation.
- Eligibility ruleset covers employment status, tenure, executive exclusion, pre-vest exclusion, share-class eligibility, and record-date mechanics.
- Participation caps are sized with a per-employee cap, an aggregate cap, and proration mechanics.
- Four tax-treatment categories are worked with specific arithmetic on four representative participant profiles.
- Per-participant worksheet template is produced that a tender administrator could populate mechanically.
- Operational choreography names the administrator, the 60–90 day timeline, the documentation package, and the settlement mechanics.
- Participant-education pack is drafted at 4–6 pages, plain-language.
- Board-and-compensation-committee approval package is drafted at 3–5 pages with the specific resolutions the board must pass.

## Reflection

Add a short reflection:

1. Which of the three pricing methodologies produced the most difficult communications problem, and how would you handle the participant-facing explanation?
2. If the aggregate demand at the participation cap exceeded the aggregate cap by 3×, what proration mechanics would you use, and would you consider a second tender in 6–12 months to satisfy the residual demand?
3. Which of the four tax-treatment categories is likely to produce the highest volume of participant confusion, and what specific participant-education intervention (video, worksheet, 1:1 session) would you deploy to reduce the confusion?
4. If the tender's Rule 701 aggregate-value impact came within 10% of the disclosure threshold, would you scale the tender back or prepare the Rule 701 disclosure package, and why?

## Stretch goals

- **Full waterfall model with Monte Carlo overlay.** Extend the waterfall model with a Monte Carlo simulation over a distribution of exit valuations and timings, producing a probability-weighted common-per-share distribution. Compare against the OPM-derived 409A common price.
- **Per-participant worksheet automation.** Build the per-participant estimated-outcome worksheet as an executable spreadsheet or notebook that takes participant-specific inputs (share count, grant type, strike, tenure, state) and produces the full after-tax result deterministically.
- **Comparable-tender benchmarking.** Assemble 3–5 publicly-observable tender offers from the last 24 months (Stripe, Databricks, Discord, Notion, and others) and compare their pricing methodology, eligibility ruleset, and cap structure against your design.
- **§1202 stacking analysis.** For a specific participant with a mix of §1202-qualifying and non-qualifying shares, model the sequencing that maximises the §1202 exclusion across multiple tender cycles.
- **Live administrator-portal walkthrough.** Sign up for a Carta or NPM demo (or use existing access) and walk through the tender-administration workflow end-to-end. Note the operational realities that differ from the paper design.
- **Communications-plan role-play.** Draft the specific script for the all-hands announcement, the small-group sessions, and the 1:1 sessions for large positions. Test the script against three plausible workforce reactions (skepticism, over-enthusiasm, tax-confusion).
