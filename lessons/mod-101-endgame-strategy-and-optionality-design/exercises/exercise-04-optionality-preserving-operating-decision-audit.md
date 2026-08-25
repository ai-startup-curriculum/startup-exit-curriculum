# exercise-04: Optionality-Preserving Operating-Decision Audit

**Estimated effort:** 3 hours

## Objective

Run the four-surface operating-decision audit against the same company you profiled in exercise-01. Produce a written audit that names — for financing, cap-table structure, board composition, and contract terms — what current decisions have pre-closed which endgame options, and what specific operating changes (with owners and target dates) would preserve or reopen the top-ranked endgame paths from your exercise-01 ranking. By the end you should have an operating punch-list the board can act on.

## Background

This exercise covers material from:

- [Chapter 5 — Optionality-Preserving Operating Decisions](../05-optionality-preserving-operating-decisions.md)

Chapters 1–4 (frame, trade-offs, buyer map, market-window read) are all supporting inputs. This exercise is where the frame becomes an *operating* audit rather than an analytic ranking.

## Prerequisites

- Completed exercises 01, 02, and 03.
- Access to the company's cap table, term-sheet history, current commercial contract inventory (or a representative subset), current board composition, and any outstanding facility documentation (venture debt, convertible notes, SAFEs, warrants).
- If you are using a hypothetical company: build a *realistic* set of the above artefacts from public precedent (NVCA model documents, Cooley GO templates, published venture-debt facility form terms). Note the source of each item so a reviewer can see where the audit inputs came from.

## Tasks

### 1. Financing audit

For each outstanding financing instrument, produce a row in a small table:

| Instrument | Principal / notional | Change-of-control terms | Covenants | Warrant coverage | Prepayment penalty | Endgame impact |
|---|---|---|---|---|---|---|

Include:

- Every priced-round preferred class.
- Every convertible instrument (notes, SAFEs) still outstanding.
- Every venture-debt facility (drawn and undrawn).
- Every credit line, revolver, or asset-backed facility.

For each row, the "endgame impact" column names which endgame path this instrument constrains and how. Example:

- "Venture debt facility, $30M drawn, requires 6-month make-whole on prepayment and lender consent for change of control. Impact: acquisition path effectively costs $1.2M in make-whole; IPO path requires facility refinance in advance of S-1 filing."

At the end of the table, note **findings**: the two or three items in the table that most materially foreclose top-ranked endgame paths and would benefit from renegotiation or restructuring.

### 2. Cap-table audit

Produce four artefacts.

**(a) Preference-stack overhang analysis.** Building on exercise-01's rough waterfall, produce a more thorough waterfall at five price points across your plausible range. Compute what common holders (founders and employees) net at each price. Table format:

| Price | Preferred payout | Common payout | Common per share | Common as % of total |
|---|---|---|---|---|

Note the price at which common breaks through (crosses a threshold you consider "meaningful") and the price at which common share matches the preferred share.

**(b) ROFR / co-sale audit.** For each shareholder class:

- Which ROFRs / co-sale rights attach?
- Which trigger on founder secondary?
- Which trigger on employee tender?
- Which trigger on change of control?

Format is a small matrix. Note which of the top-ranked endgame paths from exercise-01 would require a ROFR / co-sale waiver from a specific set of parties.

**(c) Drag-along audit.** Name the current drag-along coverage:

- Percentage of preferred required.
- Percentage of common required.
- Any per-class or per-tranche protective carve-outs.
- Whether the current cap-table shape makes the drag actually achievable, or whether it would be blocked by a dissenter.

**(d) Protective-provisions audit.** List every material action requiring preferred consent (change of control, wind-down, IPO, charter amendment, new senior class issuance, share repurchase over a threshold, etc.) with the required threshold and the current distribution of preferred votes.

### 3. Board audit

Write a short (½–1 page) board assessment covering:

- **Composition.** Current board size, seat-by-seat classification: founder / management / investor / independent. Include observer seats.
- **Independent-director count and transaction experience.** How many directors would qualify as independent for a proximate transaction under Delaware standards (no material relationship with the company, its investors, or a plausible counterparty)? Of those, how many have prior operating experience with a change-of-control transaction, an IPO, or a special-committee process?
- **Transaction-committee readiness.** If a change-of-control became proximate this quarter, could a transaction committee (or special committee under Delaware fiduciary framework) be constituted from current directors? If not, what is the gap?
- **Board size / cadence trade-off.** Is the current board size and quorum-requirement fast enough to run a proximate transaction, or does the current shape create decision-latency risk?
- **Independent-director pipeline.** Is there a rolling short-list (3–5 named candidates) for future independent-director seats, and does the founder-CEO have the network / advisor relationships to source them at reasonable notice?

At the end, state **findings**: the specific board-composition changes (add an independent director, retire an observer seat, formalise a transaction-committee-ready subset, etc.) that would materially improve endgame readiness.

### 4. Contract terms audit

Run a survey against the commercial-contract inventory. If the company is real and you have a CLM, this is a query; if not, use a representative sample of top-10-by-value contracts.

For each contract in the sample, categorise:

- **Change-of-control clause** — none / consent-required / auto-terminate / anti-assignment / notice-only.
- **MFN clause** — present / absent; if present, what does it apply to (pricing / features / terms)?
- **Reference / most-favoured-customer status** — is this customer implicitly a reference or lead-adopter whose expectations extend beyond the contract?
- **Value-at-risk under acquisition** — an estimate of what percentage of the contract's value would be at risk if the counterparty exercised any change-of-control right on assignment.

Aggregate:

- Percentage of top-10 contract value with restrictive change-of-control clauses.
- Percentage of top-10 contracts with MFN clauses.
- Number of top-10 relationships that depend materially on non-contractual expectations.

Findings: the two or three contracts most in need of renegotiation at renewal, and the top-tier reference relationships that need explicit engagement about how the top-ranked endgame paths would affect them.

### 5. Roll up the findings into an operating punch-list

Consolidate the findings from tasks 1–4 into a single punch-list. Format:

| # | Finding | Endgame path preserved | Owner | Target date | Notes |
|---|---|---|---|---|---|

Aim for 5–12 items total. If you have more than 12, the punch-list is unusable; if you have fewer than 3, the audit is probably under-run. Each item should be:

- Specific enough that a reasonable observer could tell whether it has been done.
- Ownable by a named person or role.
- Time-bounded (within the next four quarters for most items).

### 6. Write the "we are stuck" scenario (optional but recommended)

Write a short (½ page) counter-factual: given the audit findings, what does the "we're stuck" scenario look like for this company? What is the earliest plausible moment where the current stack of pre-closed options starts materially constraining a real decision? Naming this concretely is the strongest incentive for actually working the punch-list.

## Starter guidance

Three anti-patterns to watch for:

- **The "we'll deal with it later" reflex.** Founders and CFOs sometimes read the audit and mentally file every finding as "someday." The punch-list format defeats this — every item has an owner and a date. If a finding has no plausible owner and no plausible date, either it is not actually a finding or the current team cannot address it and needs external support (advisor, banker, corporate counsel).
- **The single-issue focus.** Audits sometimes get dominated by one big finding (usually the preference stack). Run all four surfaces even if one is dominant, because the small findings in the other surfaces are often what tip a deal from "hard" to "impossible."
- **The audit-as-blame exercise.** The audit is not about who made bad decisions. Every pre-closed option is the product of a defensible decision that was optimising for something else at the time. The audit surfaces the current cost of those trade-offs; it does not pass judgement on the choices.

## Acceptance criteria

You can demonstrate that:

- All four surfaces have been audited and each has a written findings section.
- The financing audit table covers every outstanding instrument, not just the biggest.
- The cap-table audit includes a five-point waterfall, ROFR / co-sale mapping, drag-along assessment, and protective-provisions list.
- The board audit names current-vs-needed independent-director count and transaction-committee readiness.
- The contract audit is anchored on top-10-by-value contracts and produces aggregate percentages.
- The punch-list has 5–12 items each with owner and target date.
- A reasonable board member could read the audit, ask a challenging question about any item, and see the evidence you used.

## Reflection

Add a short reflection:

1. Which of the four surfaces surfaced the biggest surprise? Why was it not visible before you ran the audit?
2. Which single audit finding, if resolved this year, would most materially improve the top-ranked endgame path from exercise-01?
3. Which finding will be the hardest to resolve, and what is the plausible cost (time, cash, relationship) of resolving it?

## Stretch goals

- **Historical retro.** For any single audit finding that was decided in a specific past board meeting or specific past term sheet, write a short retro: what was being optimised for at the time, what the counter-argument would have been, and what the operating cost of the decision has turned out to be.
- **Advisor engagement.** Take the punch-list to your outside corporate counsel and get their read on which items are legally straightforward to address (contract renegotiations at renewal, board recruits) vs. which will require material investor engagement (protective-provisions modifications, preference-stack restructuring).
- **Peer comparison.** If you have access to a peer company's cap table or board composition, compare specific findings. Note where your company is above / below peer norms.
