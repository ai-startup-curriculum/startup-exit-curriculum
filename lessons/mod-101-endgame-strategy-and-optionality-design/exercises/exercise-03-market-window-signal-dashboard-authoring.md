# exercise-03: Market-Window Signal Dashboard Authoring

**Estimated effort:** 3 hours

## Objective

Author the first version of a quarterly market-window signal dashboard for the same company you profiled in exercise-01. The output is a one-page dashboard that turns readings from the canonical public and industry sources into a directional read across the four macro-signal categories and an explicit statement of how the current read updates the endgame ranking. By the end you should be able to produce the same page next quarter in under two hours, using the same sources, and see the direction of change.

## Background

This exercise covers material from:

- [Chapter 4 — Market-Window Signals](../04-market-window-signals.md)

Exercises 01 and 02 are supporting inputs — the endgame ranking (exercise-01) and buyer map (exercise-02) tell you which signals matter most to *your* frame.

## Prerequisites

- Completed exercises 01 and 02.
- Working access to at least a subset of the canonical public sources: SEC EDGAR (free), Meritech public-comparables page (free), Bessemer Cloud Index (free), Renaissance Capital IPO Center (free). Subscription sources (PitchBook, Capital IQ, Mergermarket, LSEG) are useful if you have them; substitute publicly-available proxies if you don't.
- The willingness to actually read a small number of primary sources rather than relying on secondary summaries.

## Tasks

### 1. Decide on the sector-index anchor

Every dashboard needs one primary sector-index anchor — the one number you will track over time as the fastest read on the market. Pick the closest fit for your company:

- SaaS / cloud software: Bessemer Cloud Index (NQCLOUD) as the primary anchor, cross-checked against Meritech's public-comparables median multiple for your sub-segment.
- Biotech / life sciences: XBI (S&P Biotech ETF) or an equivalent.
- Fintech: FINX (Global X FinTech ETF) or an equivalent.
- Consumer / marketplaces: a curated basket you define, or a subset of an ETF.
- Any other sector: name the index you will track and defend the choice in a one-line note.

Freeze the anchor at the top of the dashboard. Do not switch anchors quarter-to-quarter without a documented reason.

### 2. Build the dashboard skeleton (one page)

Create a one-page dashboard with four sections and a footer:

```
=============================================================
QX YYYY  — Market-Window Signal Dashboard — [Company codename]
=============================================================

1. IPO WINDOW
   Anchor index: [name]  Current: __  90-day high: __  90-day low: __
   Direction: [Rising / Stable / Compressing]  vs. prior quarter
   Meritech sector median multiple: __  Direction: __
   Recent-cohort proof (3 recent IPOs in sector): [names + status]
   >> Direction call: OPEN / NARROWING / CLOSED / REOPENING
   >> One-sentence justification.

2. M&A MARKET
   Sector M&A dollar volume, TTM: $__  vs. prior TTM: __%
   Deal-size mix (mega-deal share of dollar volume): __%
   Announced-multiple direction (sector, past 4 quarters): [Compressing / Stable / Expanding]
   >> Direction call: BUYERS ACTIVE / SELECTIVE / COMPRESSED / QUIET
   >> One-sentence justification.

3. STRATEGIC-BUYER APPETITE
   Top-tier buyers from buyer map who reported this quarter: [n of m]
   M&A-language classification (net-acquisitive / opportunistic / cost-focused / returning capital):
      [tally with names]
   Executive changes at tier-1 entrants: [list]
   Any adjacent-category M&A that changes the map: [1-2 items]
   >> Direction call: NET ACQUISITIVE / MIXED / COST-FOCUSED
   >> One-sentence justification.

4. WHAT THIS MEANS FOR THE FRAME
   Impact on ranking of each endgame outcome:
   - Acquisition: [Up / Down / Unchanged] because ...
   - IPO: [Up / Down / Unchanged] because ...
   - Secondary: [Up / Down / Unchanged] because ...
   - Stay-independent: [Up / Down / Unchanged] because ...
   - Responsible shutdown: [Up / Down / Unchanged] because ...
   Operating implication for next quarter (1-2 sentences).

Sources consulted (list URLs + date of read).
Version: __  Prior version: __  Owner: __
=============================================================
```

Adapt the format — Markdown, spreadsheet, slide, whatever your team uses. The four sections and the direction calls are the load-bearing structure; do not drop them.

### 3. Populate section 1 (IPO window)

- Read the current level of your anchor index and its 90-day range. Note the direction.
- Pull the Meritech sector-median multiple for your closest sub-segment. Note the direction from prior quarter.
- Identify 3 recent (last 12 months) IPOs in your sector. Note their current price vs. issue price and any broken-issue signal.
- Make the direction call: OPEN / NARROWING / CLOSED / REOPENING. Justify in one sentence.

### 4. Populate section 2 (M&A market)

- Pull sector M&A dollar volume from an available source — PitchBook or Capital IQ if you have them; LSEG press-release league tables or a Mergermarket free snippet if you don't. Note direction TTM vs. prior TTM.
- Estimate deal-size mix — what share of the dollar volume was in mega-deals vs. tuck-ins? A rough estimate is fine.
- Note the direction of announced multiples in your sector. If you cannot find precedent-transaction data, note that and use whatever proxy you have.
- Make the direction call: BUYERS ACTIVE / SELECTIVE / COMPRESSED / QUIET. Justify.

### 5. Populate section 3 (strategic-buyer appetite)

- From your buyer map (exercise-02) top-tier strategic entries, list which ones reported earnings this quarter. Read the earnings-call transcripts (available via investor-relations sites, Seeking Alpha limited-free, or Bloomberg / Motley Fool).
- Classify each into net-acquisitive / opportunistic / cost-focused / returning capital based on management commentary about M&A.
- Note any executive changes at those companies (CEO, CFO, head of corp-dev, president of your target business unit).
- Note any adjacent-category M&A announcements from the quarter that change your buyer map (an announcement might mean a specific acquirer just took themselves out of the market by acquiring a competitor of yours, or might mean a specific parent company just became a plausible acquirer).
- Make the direction call: NET ACQUISITIVE / MIXED / COST-FOCUSED. Justify.

### 6. Populate section 4 (what this means for the frame)

For each of the five candidate endgame outcomes from your exercise-01 ranking, write:

- Direction: [Up / Down / Unchanged] since prior quarter.
- Because: one clause anchored to a specific reading from sections 1–3.

Then write one to two sentences on the operating implication for the coming quarter — what should the company *do* differently as a result of this quarter's dashboard? Examples:

- "Accelerate the auditor-upgrade decision by one quarter — IPO window direction has flipped to OPEN and our readiness gap is narrowing."
- "Slow investment in relationship-warming for [Company X] — their new CFO commentary suggests they are cost-focused for the next 12–18 months, and our capital is better spent elsewhere on the map."
- "No change; direction reads unchanged since last quarter."

The point of this section is to make the dashboard *actionable*. A dashboard that reads unchanged for three consecutive quarters with no operating implication is fine — direction unchanged is a legitimate call. A dashboard that always reads "important" is not calibrated.

### 7. Document the sources and cadence

At the bottom of the dashboard, list:

- Every source you consulted with URL and date of read.
- The intended cadence (quarterly, aligned to your board pack).
- The owner (typically the CFO or head of corp-dev, or the CEO in smaller companies).
- A note on how you will spot-check that the sources have not been retired or moved (an annual "source refresh" review).

## Starter guidance

Two anti-patterns:

- **Reading a single source.** Different providers have different definitions of "sector," different cohort methodologies, and different biases. If you find yourself citing only Meritech (or only Bessemer, or only PitchBook), cross-check with a second source. If they disagree materially, that disagreement is itself a signal worth noting.
- **Confusing volatility with direction.** A single quarter's move is often noise. Look at the 4-quarter trend as well as the current level, and be willing to call "unchanged direction" if the current move is inside recent noise.

An acceptable first-cut dashboard is honest about its data limits. If you cannot get a sector M&A dollar-volume number, say so and use whatever proxy you have. Progress is more important than false precision.

## Acceptance criteria

You can demonstrate that:

- The dashboard is one page (or one screen).
- The four sections (IPO window, M&A market, strategic-buyer appetite, what-this-means-for-the-frame) are all populated with readings from at least one primary source each.
- Every direction call is one of the specified categories (OPEN / NARROWING / etc.) with a one-sentence justification.
- Section 4 names the impact on each of the five endgame outcomes with a one-clause justification.
- The sources list has URLs and dates.
- The dashboard has an owner and a documented cadence.
- The next quarter's version can be produced in ≤2 hours by the same owner using the same sources.

## Reflection

Add a short reflection (½ page):

1. Which section was hardest to populate reliably? Why? (Often M&A market volume for sub-sectors, or strategic-buyer appetite when key strategics did not report this quarter.)
2. Which reading, if it moved materially in the next quarter, would most change your operating recommendations?
3. Which of your endgame outcomes is most sensitive to market-window shifts, and which is least sensitive? (Typically: IPO most; stay-independent least; acquisition somewhere in between depending on the buyer set.)

## Stretch goals

- **Historical backfill.** Populate the dashboard for the previous four quarters (roughly, from available public data). See what the direction calls would have been, and whether they would have changed the operating decisions the company actually made.
- **Alerting.** Set up basic alerts (Google Alerts on target-strategic company names, EDGAR filings feed on 8-K Item 2.01 / 1.01 for your sector, an RSS feed for sector-index level) so that between-quarter signals surface automatically.
- **Board-pack integration.** Add the dashboard as a standing item in the next board pack and observe how the board conversation changes when the dashboard is present vs. absent.
