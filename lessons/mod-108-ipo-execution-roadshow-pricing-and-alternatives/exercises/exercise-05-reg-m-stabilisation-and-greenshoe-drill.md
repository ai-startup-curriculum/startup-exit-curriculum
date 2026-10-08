# exercise-05: Reg M Stabilisation and Greenshoe Drill

**Estimated effort:** 3 hours

## Objective

Simulate the first-30-day aftermarket for your frozen company across three price-trajectory scenarios (hot, well-priced, soft) and author the specific syndicate-manager playbook that the lead-left would run — the stabilisation decisions, the syndicate-short cover-vs-exercise decision, the naked-short decision, the specific daily syndicate-desk report the CFO should expect, and the specific issuer-side Reg M compliance discipline. By the end of the exercise you should be able to read a syndicate-desk report in real time, anticipate the specific aftermarket dynamics the lead-left is managing, and answer the specific board question "why did the stock drop from $22 to $19 in the second week."

## Background

This exercise covers material from:

- [Chapter 5 — Regulation M and the Greenshoe Over-Allotment Option](../05-reg-m-and-greenshoe.md)

It builds on the specific pricing / allocation decisions from exercise-04 — the specific first-day-pop forecast, the composition / quality analysis, and the greenshoe sizing all become inputs here.

## Prerequisites

- Frozen company profile from exercise-01.
- Final pricing / size / greenshoe / allocation decisions from exercise-04 (both the hot-deal and soft-deal scenarios).
- Access to Regulation M (17 CFR §§ 242.100–242.105) rule text on the eCFR.
- Access to SEC EDGAR 8-K filings reporting specific greenshoe-exercise disclosures by recent comparable issuers (shape-reference).

## Tasks

### 1. The restricted-period calendar

Produce a specific day-by-day calendar for the Reg M restricted period on your deal:

- Restricted-period start date (one or five business days before pricing — justify which applies to your IPO given there is no pre-existing average daily trading volume).
- Pricing date (T).
- First day of trading (T+1).
- Specific milestones through T+30: the specific research-quiet-period expiry under FINRA Rule 2242 (10 days for lead managers; confirm the specific current period), the specific index-inclusion signal windows, and the specific stabilisation-window close.
- Restricted-period end (specific distribution-completion event under Reg M).

For each day, specify what the syndicate manager is doing — stabilising, covering, holding, exercising the greenshoe, closing the stabilisation window — and what the issuer is doing (executive-trading blackout, no issuer share repurchases, specific ESPP timing considerations).

### 2. The three-scenario aftermarket simulation

Simulate the first-30-day price-trajectory and the specific syndicate-manager response under three scenarios. For each scenario, produce a day-by-day table with (a) stock price open/close/VWAP/volume, (b) current syndicate short position, (c) stabilisation activity (none / stab-bid / syndicate-covering purchases), (d) greenshoe status, (e) specific institutional flow signals (which accounts are buying / selling).

**Scenario A — Hot Deal.**

- Pricing: top of range or priced-above-range from exercise-04's hot-scenario.
- T+1 open: offering × 1.25 to 1.40.
- First week: stock trades up through the first week; limited stabilisation activity needed; the syndicate manager considers a naked-short.
- Decide: Does the syndicate manager take a naked short? If yes, specify the specific size and the specific aftermarket-buying-pressure benefit; if no, justify.
- Decide: When does the syndicate exercise the greenshoe? Full exercise or partial?
- Decide: Specific-timing (days 5-10 is typical for hot deals).
- Document the specific 8-K disclosure of the greenshoe exercise.

**Scenario B — Well-Priced Deal.**

- Pricing: range midpoint from exercise-04's well-priced scenario (model this as a middle-case even if exercise-04 only ran hot and soft).
- T+1 open: offering × 1.10 to 1.20.
- First week: stock trades in a specific band around offering + 15%; some stabilisation activity on the first down-day; syndicate covering through specific aftermarket purchases.
- Decide: When does the syndicate exercise the greenshoe? Partial or full? Specify the specific signal (specific index-inclusion window, specific research-initiation, specific analyst-day event).
- Decide: Does the syndicate use stabilising bids, or rely exclusively on syndicate covering?

**Scenario C — Soft Deal.**

- Pricing: low end of range or priced-below-range from exercise-04's soft-scenario.
- T+1 open: offering × 0.95 to 1.05.
- First week: stock trades flat-to-down; heavy stabilisation activity through syndicate covering.
- Decide: The syndicate does NOT exercise the greenshoe (covers short in aftermarket). Specify the specific daily-covering pattern.
- Decide: Does the syndicate use stabilising bids on specific down-days?
- Decide: How does the syndicate manager communicate the specific soft-deal dynamic to the CFO / IR team, and what specific IR-messaging strategy follows?

### 3. The syndicate-desk report template

Author the specific daily syndicate-desk report template that the lead-left syndicate desk would send to the CFO / IR team each day for the first 30 days post-pricing. The template should capture:

- **Aftermarket price.** Open, close, high, low, VWAP, volume (vs. 10-day benchmark for recent-comparable IPOs).
- **Syndicate position.** Current short (shares and % of offering); greenshoe status (not exercised / partially exercised / fully exercised); specific-exercise-date and specific-partial-exercise-amount if applicable.
- **Syndicate activity.** Stabilising bids entered (price, size, time); syndicate-covering purchases (shares, average price); penalty bids imposed (if any — rare).
- **Institutional-account activity.** Named accounts buying (top-5); named accounts selling (top-5); specific-known-flipping flags for accounts that received allocations and are now selling.
- **Research signals.** Pre-initiation activity signals; specific comparable-issuer signals; specific research-quiet-period expiry events.
- **Index / ETF flow signals.** Specific index-inclusion signals (Russell 2000, Russell 1000, S&P 500 inclusion windows), ETF-flow (specific sector ETF rebalance signals).
- **Narrative summary.** 3-5 sentences of the lead-left's read on the day's aftermarket dynamics.

Design the template so the CFO can pattern-recognise across the first 30 days — specifically, so the Day 5 report has a format directly comparable to the Day 20 report.

### 4. The issuer-side Reg M compliance discipline

Author the specific issuer-side Reg M compliance programme covering the restricted period:

- **Executive-and-director trading blackout.** Written notice to all Section 16 reporting persons, specific blackout-period start and end, specific-exception-handling for Rule 10b5-1 trading plans adopted before the IPO (specific JOBS-Act / Rule-10b5-1 interaction).
- **Issuer share repurchases.** Policy that the issuer does not repurchase its own shares during the restricted period; specific exception-handling for any pre-existing authorisation.
- **ESPP mechanics.** Specific ESPP-timing adjustment during the restricted period (if the issuer has an ESPP — most pre-IPO companies do not, but post-IPO plans may be in design).
- **Selling-stockholder discipline.** If secondary selling-stockholders participate in the offering, specific Rule 102 discipline for the restricted period; specific blackout-tracking for selling-stockholder accounts.
- **Communications-perimeter extension.** The specific extension of the chapter-2 publicity-policy discipline through the restricted period — specifically, the IR team's communications perimeter, Reg FD discipline, and the specific pre-first-earnings-call-communications discipline.

### 5. The specific board / audit-committee communication

Draft the specific CFO communication to the board or audit committee at Day 15 and Day 30 explaining the aftermarket. Each communication should cover:

- Specific aftermarket performance (price, volume, aftermarket-signal).
- Specific syndicate activity and the specific interpretation of stabilisation and greenshoe-exercise decisions.
- Specific institutional-account activity (which allocations are holding, which are flipping, specific-flip-rate numbers).
- Specific-research-coverage status (which analysts have initiated, specific price targets, specific aggregate-sell-side signal).
- Specific-ongoing-concerns (if any — soft-deal dynamics, specific-first-earnings-call pressure build).
- Specific-lock-up-expiry-outlook preview (preview of exercise-06; what the specific 180-day expiry looks like given current price dynamics).

The Day 15 communication is interim; the Day 30 communication is specific closure on the restricted-period-and-stabilisation window.

### 6. The specific board question drill

Draft the specific CFO response to each of these specific board questions, assuming the specific aftermarket scenario is **Scenario C — Soft Deal**:

- "Why did we price here if the aftermarket is this soft?"
- "Should we have waited for a better market window?"
- "What's the syndicate doing to support the price?"
- "Why isn't the stock recovering if the syndicate is actively buying?"
- "What does this mean for our ability to do follow-on offerings or convertible-debt in the next 24 months?"
- "What should we tell employees? The 180-day lock-up is coming and the stock is below the offering price."

Each answer: specific, S-1 and syndicate-report-grounded, defensible, and sized to the actual context the specific board would have.

### 7. The research-quiet-period choreography

Author the specific choreography around the FINRA Rule 2242 research quiet period expiry:

- Specific syndicate-member research analysts and the specific quiet-period expiry date per analyst (confirm current rule period on each deal).
- Specific-pre-expiry communications discipline — no analyst-side marketing, no analyst-to-institutional-sales-force marketing of the specific issuer.
- Specific day-of-expiry initiation choreography — expected initiations at Buy with specific price targets, specific aggregate-price-target distribution.
- Specific issuer-side preparation — specific analyst-model-briefing-materials (consistent with the S-1 and the roadshow deck), specific analyst-day-of-initiation availability for specific-model-clarification questions.
- Specific aftermarket-dynamic reading — the specific aggregate signal from specific initiations (if a lead-left analyst initiates with a Hold or an Underperform, specific aftermarket-damage; if the three co-managers all initiate at Buy with price targets 20-30% above offering, specific-aftermarket-support).

## Starter guidance

Three anti-patterns to avoid:

- **The "stabilisation-equals-manipulation" conflation.** Rule 104 stabilising bids and syndicate covering are specific-permitted activities under Reg M; they are not manipulation. The specific distinction is codified in the SEC's safe-harbour framework. The CFO who asks "is this legal" is asking the wrong question — the right question is "is the syndicate activity consistent with the specific Rule 104 framework and the specific-disclosure obligations."
- **The "greenshoe-is-a-free-option" misunderstanding.** The greenshoe is covered by a specific syndicate short — the syndicate has a liability it needs to cover one way or the other. The economics are specific and symmetric: hot deal → syndicate exercises greenshoe, company issues additional shares, syndicate pays offering price for shares worth more in the market; soft deal → syndicate covers in market at below-offering prices, syndicate closes short at a profit, company does not issue additional shares. The specific economics are a specific function of the aftermarket.
- **The "silent syndicate desk" assumption.** The CFO who assumes the lead-left syndicate desk will self-report every important aftermarket dynamic without specific-asking is a CFO who misses specific signals. The specific discipline is to receive and read the specific daily report, ask specific questions ("why did we sell X shares at the open today?"), and build the specific-practitioner-interpretation discipline over the first 30 days.

## Acceptance criteria

You can demonstrate that:

- The restricted-period calendar is specific day-by-day and tied to the specific Reg M distribution-completion event.
- Each of the three aftermarket scenarios is simulated with specific daily entries for 30 days.
- The syndicate-desk report template is specific and usable across the entire restricted period.
- The issuer-side Reg M compliance programme covers blackout, repurchases, ESPP, selling-stockholders, and communications-perimeter extension.
- The Day 15 and Day 30 board communications are specific, grounded, and defensible.
- The specific-board-question drill answers address each specific question in context.
- The research-quiet-period choreography is specific analyst-by-analyst.
- A critical reader (lead-left syndicate head, underwriter counsel, specific-FINRA-retrospective-auditor-simulator) can test each decision and find it defensible under Reg M.

## Reflection

Add a short reflection (½ page):

1. In the hot-deal scenario, what specific signal would push you to recommend the lead-left take a naked short (above the greenshoe), and what specific-risk-tolerance does that imply?
2. In the soft-deal scenario, at what specific aftermarket-price does the stabilisation activity become economically-futile (the stabilisation does not materially slow the decline), and what alternative support discipline does the IR function then run?
3. Which specific board question would you expect to be the hardest to answer in the soft-deal scenario, and what is your specific-rehearsal strategy?

## Stretch goals

- **Specific-recent-IPO back-test.** Pick 2-3 recent IPOs in your sector that broke issue in the first 30 days. From the SEC 8-K filings and the specific Bloomberg / Nasdaq / NYSE aftermarket data, reconstruct the specific syndicate-manager playbook (greenshoe exercise timing, stabilisation signals, specific aftermarket-support patterns). What specific lessons apply to your deal?
- **The specific-naked-short-decision deep dive.** For the hot-deal scenario, model the economic consequence of a 10% naked short, a 15% naked short, and a 20% naked short across three sub-scenarios (aftermarket closes 20% above offering, 50% above offering, 100% above offering). What is the specific economic cost to the syndicate under each path, and what is the specific aftermarket-support benefit?
- **Follow-on-offering readiness.** Based on the first-30-day aftermarket in each scenario, author the specific follow-on-offering readiness assessment for a hypothetical 6-month-post-IPO follow-on. What specific aftermarket signal would make a 6-month follow-on viable, and what specific IR / cap-markets prep is required?
