# exercise-03: Buyer-Map Authoring with Scoring Methodology

**Estimated effort:** 4 hours

## Objective

Extend the buyer map from mod-101 exercise-02 to sell-side execution depth. Add evidence sub-diligences for every score on every top-tier and second-tier entry, organise the map into ranked tiers (top / second / long-tail) that map to distinct process treatments, add banker-coordination fields if a banker is engaged (or will be), and produce the board-visible one-page summary. By the end, you should have a buyer map that could be handed to a lead banker as the sell-side execution shortlist without embarrassment.

## Background

This exercise covers material from:

- [Chapter 3 — Buyer Mapping at Sell-Side Depth](../03-buyer-mapping-at-sell-side-depth.md)

Chapter 1 (acquirer sub-type) and chapter 4 (banker engagement) are supporting inputs — the sub-type classification you did in exercise-01 feeds this exercise's evidence sub-diligences, and the banker-engagement view (whether you have one, and if so which firm) shapes the banker-coordination fields.

## Prerequisites

- Completed mod-101 exercise-02 (rolling buyer map first cut) — you are extending that artefact.
- Completed exercise-01 in this module (acquirer sub-type classification).
- Access to SEC EDGAR (10-Q balance sheets for public acquirers, 10-K risk / capital-return disclosures), acquirer investor-relations sites, PitchBook or comparable for private-acquirer and financial-acquirer intelligence, and — critically — your own network for the ex-employee, banker, and prior-transactor conversations that back the process-behaviour and cultural-fit scores.
- The spreadsheet or database tool you set up in mod-101 exercise-02.

## Tasks

### 1. Add evidence sub-diligence columns to the schema

Extend the mod-101 schema to include:

| Column | Purpose |
|---|---|
| Sub-type (from exercise-01) | The chapter 1 sub-type classification |
| Strategic-fit evidence | Cited source (earnings call excerpt with date, investor-day slide URL, 8-K link, product-announcement URL) |
| Ability-to-pay model | For public strategics: cash + short-term investments, revolver, market-cap; for financials: fund size, vintage, dry powder estimate; with source and as-of date |
| Integration-appetite evidence | The prior-deal pattern that supports the integration-appetite score (up to 5 recent deals with observed integration outcomes) |
| Process-behaviour evidence | Cited sources for the speed / diligence-style / certainty-of-close / behaviour-under-pressure / post-signing categorisation — bankers, founders, ex-corp-dev alumni |
| Cultural-fit evidence | Named ex-employee / former-target-founder conversations (or notes that these are still pending) supporting the cultural-fit score |
| Relationship counterpart | Named counterpart on the acquirer side, title, last-contact date |
| Tier | Top / second / long-tail |
| Banker coverage | If a banker is engaged: whether the banker owns the primary outreach, you own it, or it is shared |
| Pre-marketing plan | Named plan (see task 5) |

Keep the mod-101 columns (Company, Category, Relationship depth, Strategic fit, Ability to pay, Integration appetite, Process behaviour, Cultural fit, Owner, Last contact, Next planned touch, Thesis note, Trigger note); the new columns are additive.

### 2. Populate the evidence sub-diligences for the top-tier

For your top 5–8 entries — the ones you would want in the first round of a formal process — populate every evidence column with real, cited sources. Enforce the following minimum evidence standards:

- **Strategic-fit ≥4** requires a specific piece of public evidence within the last 12 months (earnings-call excerpt with date, investor-day slide, category-specific 8-K action).
- **Ability-to-pay ≥4** requires a modelled capacity estimate anchored to the latest 10-Q balance sheet (public) or fund-size / vintage / deployment analysis (financial), with the source noted and dated.
- **Integration-appetite ≥3** requires at least 3 observed prior-deal integration outcomes.
- **Process-behaviour categorisation** requires at least one named external source (banker, founder, ex-corp-dev alum) — LinkedIn-network-only classifications count but should be marked as such.
- **Cultural-fit ≥3** requires either scheduled or completed ex-employee / former-target-founder conversations. If neither is realistic, lower the score.

If any top-tier score cannot meet its evidence standard, lower the score to what the evidence supports. The point of the exercise is to build a map that is defensible against interrogation, not to protect prior scores.

### 3. Populate the evidence sub-diligences for the second-tier

For the second-tier (roughly 10–20 entries), populate the evidence columns at a somewhat lighter standard:

- Strategic-fit evidence should still be cited but can be less recent.
- Ability-to-pay can use a rough estimate rather than a fully-modelled capacity.
- Process-behaviour and cultural-fit can rely on inferred / secondary sources; note the confidence level.
- Relationship counterpart is populated but the last-contact discipline is more relaxed.

The point of the second-tier is that entries there enter the formal process at a slightly delayed / batched schedule and do not receive the top-tier's pre-marketing investment; the evidence bar is calibrated to that role.

### 4. Assign tiers, then defend the assignments

Assign each entry to top / second / long-tail with the following logic:

- **Top-tier (5–10 entries):** the acquirers you want in the first-round bidding. Strategic fit ≥4, ability to pay ≥4 at your price band, relationship depth ≥2 (or a specific plan to reach 2 within the pre-marketing window), integration appetite compatible with your team's preferences, cultural fit ≥3, process behaviour compatible with your process timing.
- **Second-tier (10–20 entries):** plausible bidders whose fit, capacity, relationship depth, or process behaviour makes them less certain top-of-the-list.
- **Long-tail (20+ entries, optional):** acquirers included to maintain competitive pressure but not staffed with dedicated owners.

For each top-tier entry, write a 1–2 paragraph *tier-assignment defense* naming: (a) why this entry is top-tier rather than second-tier, (b) which of the six scores tipped it in, (c) the specific pre-marketing plan (see task 5) that will bring the relationship-depth score to the required level by process launch.

For each second-tier entry, a 3–4 sentence defense is enough.

### 5. Author a pre-marketing plan for each top-tier entry

For each of the 5–8 top-tier entries, write a specific pre-marketing plan for the 12–24 weeks before formal launch. The plan should name:

- **Which of the chapter 6 patterns will be used** — market-intelligence conversation, strategic-partnership-first, or discovery meeting — and why that pattern fits this specific acquirer.
- **Who owns the specific outreach** — CEO, CFO, SVP-Corp-Dev, banker, or a board member with a prior relationship.
- **What the specific first-touch is** — a specific meeting request, a specific referral to a specific person, a specific event around which to build a natural encounter.
- **What the escalation path looks like** — how the first touch leads to a second, the second to a third, and so on, over 12–24 weeks.
- **What the expected relationship-depth outcome is** — moving the score from its current level to the target level by process launch.
- **The failure mode to watch out for.** For example, "if they interpret our approach as shopping, we abort and revert to stage-0 standing" or "if their business-unit lead moves on before the second touch, we need a replacement counterpart plan."

Keep each plan to one page. Ten plans is a lot of writing; the discipline is in the plan being *specific enough to execute*.

### 6. Coordinate with the banker (or the eventual banker)

If you have already engaged a banker (per exercise-04), add a banker-coordination workstream:

- The banker's own buyer map is compared against yours. Note convergences and divergences.
- For each top-tier entry, name the primary owner (banker or founder-CEO / CFO) and the sequence-of-touches choreography (banker warms first, then CEO takes second meeting; or CEO opens with peer meeting, banker follows up on process details).
- The banker's process-behaviour intelligence updates your process-behaviour rows for entries where the banker has direct prior-transaction experience.

If you have not yet engaged a banker but plan to (per exercise-04), leave the banker-coordination fields as placeholders and note that they will be populated when the banker mandate is signed.

If you are running a no-banker process (per exercise-04), name for each top-tier entry what alternative machinery (personal network intros, board-member relationships, specialist advisor engagements) replaces the banker's warming and buyer-network functions.

### 7. Produce the board-visible one-page summary

Draft a single-page summary of the map for the next board meeting:

- Top-tier count and their aggregate scores (with change-since-last-quarter indicators).
- Second-tier and long-tail counts.
- Highlights: entries that moved tiers, new inbound signals, buyer-map changes driven by the market (new competitor exit, new adjacent M&A action, new executive appointment at a top-tier acquirer).
- Ongoing pre-marketing activity: which top-tier plans are on track, which are behind, which have surfaced signal, which have hit obstacles.
- One or two board-decision items: relationships where a board member's personal engagement would help, or process choices where the board's view is needed.

The board summary is what actually gets read; the underlying map is the reference. Draft it as if you were presenting to a real board.

### 8. Install the maintenance cadence

Confirm the maintenance cadence from mod-101 exercise-02 and update if the sell-side execution depth changes the rhythm:

- **Weekly during pre-marketing (starting 8–16 weeks before formal launch)** — CEO / CFO / (banker if engaged) sync on the map.
- **Bi-weekly during the formal process** — full sell-side team review.
- **Board update at each stage gate.**
- **Event-driven updates** — earnings-call M&A signal, competitor exit, executive turnover at a target acquirer.

Write down (½ page) how the cadence will actually happen — meeting time on the calendar, owner of the update, format of the update, distribution list.

## Starter guidance

Three anti-patterns to watch out for:

- **Scoring inflation on second tier to feel comprehensive.** The second tier is not "everyone who could conceivably be interested." It is "credible bidders whose participation would meaningfully affect the process." Aggressive tiering upward produces a bloated list that dilutes attention on the real top-tier.
- **Skipping the cultural-fit ex-employee conversations because they are hard to schedule.** These conversations are the highest-signal / lowest-cost intelligence you will collect. Every top-tier entry should have at least one such conversation attempted; entries where you cannot get one after a real effort should have their cultural-fit score lowered accordingly.
- **Wishful-thinking pre-marketing plans.** A pre-marketing plan that reads "we'll build the relationship" is not a plan. A plan that reads "the CFO will ask for a market-intelligence coffee with their VP-of-Corp-Dev in April, followed by a founder-CEO invitation to our customer summit in June, followed by a CEO-to-CEO offsite dinner in September" is a plan. Force specificity.

## Acceptance criteria

You can demonstrate that:

- The schema is extended with the evidence sub-diligence columns above.
- Every top-tier entry has every evidence column populated with cited sources, and any score not backed by evidence has been lowered.
- Every second-tier entry has at least the strategic-fit and ability-to-pay evidence columns populated.
- Tier assignments are defended in writing (1–2 paragraphs top-tier, 3–4 sentences second-tier).
- Every top-tier entry has a one-page pre-marketing plan with named touches, owners, and escalation paths.
- Banker-coordination fields are populated (or explicitly deferred with a plan to populate).
- The board-visible one-page summary is drafted and would be presentable at the next board meeting.
- Maintenance cadence is written down and specifies rhythms, owners, formats, distribution.

## Reflection

Add a short reflection:

1. Which top-tier entry surprised you most in the evidence sub-diligence — either because the evidence was much weaker than you expected (score should come down) or because the evidence was stronger than you expected (relationship investment should escalate)?
2. Which two or three second-tier entries have the most upside — where a modest additional pre-marketing investment could move them to top-tier?
3. What is the biggest map-wide gap — a sub-type or a geography or a specific class of acquirer that is under-represented?
4. What would you most want to know about the top-tier acquirer set that public evidence and your current network cannot tell you?

## Stretch goals

- **Corp-dev bio deep-dive.** For each top-tier entry, produce a one-paragraph bio on the head of corporate development (and, where relevant, the specific business-unit executive who would sponsor an acquisition). Include their tenure, prior deals they publicly led, and their reputation in the deal community.
- **Ex-employee-network scale.** Systematically approach ex-employees from top-tier acquirers in your network for 20-minute conversations. Aim for at least one conversation per top-tier entry within the next 60 days. Update the cultural-fit and process-behaviour rows with what you learn.
- **Banker-map convergence session.** If you have engaged (or are engaging) a banker, dedicate a specific working session to converging their map with yours. Note the delta on both sides — what they added, what you added — and update both artefacts.
- **Adjacent-M&A watch integration.** Build (or refine) an adjacent-M&A watch (Google Alerts, EDGAR filings feed, PitchBook alerts) that triggers a same-week map review on any announcement in your category or adjacent categories. Wire it into the maintenance cadence.
