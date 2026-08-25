# exercise-02: Rolling Buyer Map Authoring

**Estimated effort:** 3 hours

## Objective

Author the first cut of a rolling buyer map for the same company you profiled in exercise-01. The output is a maintainable document — spreadsheet or database — that categorises every plausible acquirer, scores each on the six dimensions, records where the relationship currently stands, and defines a maintenance cadence you can defend. By the end you should have a buyer map that can be dropped into a board pack next quarter and reviewed as a standing item.

## Background

This exercise covers material from:

- [Chapter 3 — The Rolling Buyer Map](../03-rolling-buyer-map.md)

Chapter 2 (trade-offs) is a supporting input — the ranking of endgame paths from exercise-01 tells you where to concentrate the buyer-map depth.

## Prerequisites

- Completed exercise-01 (the company profile and endgame ranking).
- Working access to public sources: SEC EDGAR, target-acquirer investor-relations sites, PitchBook or an equivalent if you have it (public info is fine if not).
- Any spreadsheet or database tool. Google Sheets, Excel, Notion, Airtable, Coda all work.

## Tasks

### 1. Set up the schema

Create the buyer-map document with at least these columns:

| Column | Purpose |
|---|---|
| Company | The acquirer name |
| Category | strategic / financial / market-structure |
| Sub-type | Category-adjacency / defensive / distribution / talent (strategics); buyout PE / growth equity / take-private / family office (financial); trigger-note (market-structure) |
| Relationship depth (0–4) | 0 cold → 4 deep |
| Strategic fit (1–5) | With one-line note |
| Ability to pay (1–5) | With one-line note anchoring to balance sheet / dry powder |
| Integration appetite (1–5) | With one-line note |
| Process behaviour | Fast / medium / slow, with note |
| Cultural fit (1–5) | With one-line note |
| Owner (internal) | The person on your team who maintains this relationship |
| Last contact | Date |
| Next planned touch | Date + planned channel |
| Thesis note | One-line "why on the map" |
| Trigger note | The condition that would light this acquirer up |

You may add columns (source-of-signal, notes on prior deals with your board members, etc.) but do not drop these.

### 2. Populate the strategic-acquirer section (target 15–25 entries)

Populate the section with the plausible strategic acquirers for your company. Sources you can draw on:

- Adjacent-category competitors and their public product-line M&A history (EDGAR 8-K search for Item 2.01 / 1.01 filings).
- Companies whose earnings calls in the last 4 quarters mentioned M&A appetite in your segment.
- Companies where a board member or investor has a strong existing relationship.
- Companies where an existing customer / partner relationship has surfaced strategic interest.

For each entry, fill *at least*:

- Category = strategic, sub-type from the taxonomy.
- Relationship depth (be honest — most entries are 0 or 1 for a first-cut map).
- Strategic fit with a fact-anchored justification (e.g., "5 — their Q3 2025 earnings call named data-integration as a category priority; three recent acquisitions in the space").
- Ability to pay anchored to public balance-sheet or market-cap data.
- Thesis note.

The remaining columns can be lighter on a first cut but should be populated with placeholders you commit to filling in over the next 30 days.

### 3. Populate the financial-acquirer section (target 8–15 entries)

Financial acquirers relevant to your company's stage and shape.

For each entry, fill *at least*:

- Category = financial, sub-type.
- Fund size and fund vintage (year of last close, current year in the fund).
- Sector mandate.
- Deal-size band typically written.
- Ability to pay — anchored to dry powder if known, or "estimated based on fund size" otherwise.
- Thesis note — why this fund would look at you (typical hold thesis, comparable investments).
- Trigger note — what would need to be true (typically the company's revenue and profitability profile).

The financial-acquirer section is often where founders have the least intuition. If you find yourself with fewer than 5 entries, either you have not looked at the sector broadly enough or your company is in a shape that legitimately does not attract financial buyers yet — in which case *say so* in a note at the top of the section.

### 4. Populate the market-structure-players section (5–15 entries)

Companies not currently in your space but whose stated strategy points them into it, or companies whose own corporate structure suggests they might enter the space via acquisition.

For each entry, fill:

- Category = market-structure, sub-type = trigger-note.
- Trigger note — the specific event that would make this entrant light up as an acquirer.
- Thesis note.

Keep this section modest — the value is having the map in your head, not building an exhaustive list.

### 5. Assign internal owners

For every entry — not just the top-tier ones — name the internal owner. Most entries will be owned by the CEO by default. Distribute owners realistically:

- CEO — top-tier strategics and any entry where the primary relationship is peer-CEO to peer-CEO.
- CFO — financial acquirers (where the primary relationship is CFO-to-partner).
- SVP-Corp-Dev (if you have that seat) — the majority of the map on a working-owner basis.
- Board members — entries where the director has a specific prior relationship (name the director explicitly).
- Business-unit executives — entries where the primary relationship is via a product-integration or joint-customer motion.

An entry without an owner is an entry that will not be maintained. Prefer under-owning a few entries (and marking them "unowned — deprioritise") over pretending they are covered.

### 6. Define the maintenance cadence

Write a short (½–1 page) section at the top of the map that names:

- **Quarterly refresh** — what gets updated, who leads, what one-page summary makes it into the board pack.
- **Semi-annual deeper refresh** — who participates, what changes.
- **Annual full rebuild** — cadence, board involvement.
- **Event-driven updates** — what triggers a same-week update (earnings call, executive turnover, adjacent M&A, inbound).

The cadence should be honest — a company with no corp-dev seat cannot maintain quarterly refreshes across 40 entries. Scale the cadence to the team you actually have.

### 7. Identify the top-tier and specify the relationship-depth investment

From your populated map, name the top-5 to top-8 entries by combination of (strategic fit × ability to pay). For each of those, write a paragraph on:

- Current relationship depth.
- The specific investment (a defined market-intelligence conversation cadence, a product-collaboration relationship, a joint-customer motion, an executive-team-to-executive-team touch) that would raise depth by one level in the next 12 months.
- Who owns the investment.
- What board involvement would help.

## Starter guidance

Two anti-patterns to watch out for:

- **Confirmation-biased scoring.** You will be tempted to score higher on strategic fit for companies you already have warm relationships with. Cross-check by consulting the acquirer's *public evidence* — their earnings calls, their M&A history — before scoring. If the folklore says one thing and the public evidence says another, note the tension.
- **Cold-map bias.** You will look at your first-cut map, notice that most entries are level 0 or 1, and feel like the exercise failed. It did not. A cold map is exactly what most founders have when they run this exercise honestly for the first time. The value of the exercise is in the *plan to warm the top 5–8 entries over the next 12–36 months*, which is the deliverable in task 7.

## Acceptance criteria

You can demonstrate that:

- The schema is set up with at least the columns above and is captured in a tool that will support quarterly updates (spreadsheet, Notion, Airtable, etc.).
- The strategic section has ≥15 entries; the financial section has ≥8 entries; the market-structure section has ≥5 entries. (Or, the map has a *documented reason* why any section has fewer.)
- Every entry has category, sub-type, relationship depth, strategic-fit score with fact anchor, ability-to-pay score with fact anchor, an internal owner, and a thesis note.
- The maintenance cadence is written down and specifies quarterly / semi-annual / annual / event-driven rhythms.
- The top-5-to-top-8 have a written relationship-depth investment plan with owners.
- A critical reviewer could challenge any specific entry's scoring and see the evidence you used.

## Reflection

At the end, add a short reflection:

1. Which of the five endgame-frame outcomes from exercise-01 does the buyer map materially update? (E.g., "the map surfaced three plausible strategics I had not considered; the ranking of cash-heavy acquisition rises accordingly.")
2. Which relationship, if invested in over the next 12 months, would produce the largest change in optionality?
3. What information is currently *missing* that would let you score more confidently? (Often: internal folklore about a specific acquirer's process, a director's actual read on a target CEO, an ex-employee's read on cultural fit.)

## Stretch goals

- **Buyer-map board pack extract.** Produce the one-page board-pack summary of the map: top entries with relationship depth, direction of change, key movements this quarter. Use it in your next board meeting.
- **Adjacent-M&A watch list.** Set up a small automated / manual watch (Google Alerts, EDGAR filings feed) for M&A announcements in your and adjacent categories. Each announcement should trigger a same-week review of whether the map changes.
- **Cross-portfolio comparison.** If you have access to a VC's buyer-map for a comparable company, compare structures. Note which categories they include and how their scoring differs — often instructive.
