# exercise-01: IRC §1202 QSBS Analysis Drill

**Estimated effort:** 3 hours

## Objective

Produce a specific, tranche-by-tranche IRC §1202 Qualified Small Business Stock analysis of a specific founder (or founder-equivalent) personal fact pattern, culminating in a defensible one-page QSBS position memo you could hand to a private-client tax attorney for review. By the end of the exercise you should know, for each specific tranche of your position, whether the stock is QSBS, which vintage percentage applies, what the per-tranche cap arithmetic looks like, which state-conformity rules apply, what evidence you have (or need to obtain) to support the position, and which specific unresolved questions the attorney should address.

## Background

This exercise covers material from:

- [Chapter 1 — IRC §1202 QSBS Fundamentals](../01-irc-1202-qsbs-fundamentals.md)

It is also the analytic spine for every subsequent exercise in the module. Freeze a specific personal fact pattern here and carry it forward.

## Prerequisites

- A specific personal fact pattern (your own upcoming or recent liquidity event, or a realistic hypothetical you build for this module). You will use the same fact pattern across exercises 01–05.
- Access to primary sources: IRC §1202 (and the related §1045, §1(h)(4)), the Treasury Regulations (where issued), the state-conformity rules for your state of residence, and the issuer's corporate records (incorporation history, Series-A-and-later balance sheets or an attestation letter, business-description documentation).
- Optional but useful: a prior-year personal 1040 and any Form 8949 history reflecting the holdings; a copy of your option exercise or RSU vesting history from the issuer's stock-plan administrator (Carta, Shareworks, E*TRADE Corporate Services, or similar).

## Tasks

### 1. The frozen personal fact-pattern profile

Author a one-page profile at the top of your working document that will be referenced by every subsequent exercise. The profile must specify:

- **State of residence and filing status.** State of domicile, state of residence (if different), filing status (single, married filing jointly, head of household), any state-residency-change plans with specific intended effective dates.
- **Family structure.** Spouse (if applicable); children with specific ages and adult / minor status; grandchildren if applicable; other dependents.
- **Role at the issuer.** Founder (title), early employee (title and employee number if a specific-number cohort applies), angel investor, board director, advisor, or combination. Current employment status at the issuer (active, departed, departing on a specific date).
- **Issuer profile.** C-corp (confirmed) or S-corp-converted-to-C (date of conversion); approximate current gross assets; general line of business (software, biotech, fintech, consumer, etc.); whether the business is on any of the §1202(e)(3) excluded-category boundaries.
- **The transaction event.** Transaction type (M&A cash-out stock sale, M&A §368 reorg, tender offer / structured secondary, IPO + post-lock-up sale, milestone payment on earn-out, no imminent transaction / planning in advance). Specific transaction date or expected date window. For M&A, structure (stock, asset, cash, mixed consideration). For IPO, the lock-up expiry date and release pattern.
- **Prior liquidity events on the same issuer, if any.** Secondary tender participation, prior §1045 rollovers, prior gift transfers.
- **Existing trust and estate structures.** Revocable trust (grantor trust, no QSBS stacking value), existing non-grantor trusts, GRATs, SLATs, existing foundation or DAF.

### 2. The tranche-by-tranche inventory

Build a specific tranche-by-tranche inventory of your position in the issuer. Each tranche is a specific acquisition of specific shares with a specific acquisition date, acquisition manner, consideration paid, and current share count. Example tranche formats:

- **Founding-shares tranche.** 1,000,000 shares acquired on 2017-03-15 at incorporation in exchange for assigned IP and $100 of cash. Adjusted basis: $100. Current share count after any splits: X.
- **Option exercise tranche.** 50,000 shares acquired on 2020-07-12 via exercise of 2018-grant ISOs at strike price $0.15 per share. Adjusted basis: $7,500. Current share count: 50,000 (adjusted for any splits).
- **RSU-vesting tranche.** 10,000 shares delivered on 2022-04-01 upon RSU vesting (grant date 2021-04-01, vesting over 4 years quarterly). Adjusted basis: FMV on delivery = $8.50 × 10,000 = $85,000. Current share count: 10,000.
- **Convertible-note-conversion tranche.** X shares acquired on 2019-05-10 upon conversion of a $500K convertible note purchased on 2018-11-01. Adjusted basis: $500K. Current share count: X.
- **Secondary-purchase tranche.** 5,000 shares acquired on 2021-02-14 by purchase from a departing employee for $12.00 per share. Adjusted basis: $60,000. Current share count: 5,000.

For each tranche also note any specific later events that affect it: splits, consolidations, dividends paid in stock, exchange in a §368 reorg, prior gift transfer out of the tranche, prior sale of a portion.

### 3. The tranche-level QSBS analysis

For each tranche, run the five qualifying-stock requirements from chapter 1:

**Requirement 1 — C-corp issuer at issuance.** Was the issuer a domestic C-corp at the tranche's issuance date? Is there corporate documentation confirming it? If the issuer was ever an S-corp or an LLC, when was the conversion to C-corp? For pre-conversion equity, the clock restarts at conversion; pre-conversion stock is not QSBS.

**Requirement 2 — original issuance.** Was the stock acquired directly from the issuer (founding shares, option exercise, RSU delivery, convertible-note conversion, direct purchase from the issuer), or in a secondary from another shareholder? Secondary-purchase tranches are not QSBS. For option exercises, the clock starts at *exercise*, not at grant; for RSUs, at delivery; for convertibles, at conversion.

**Requirement 3 — $50M gross-asset test at issuance.** Were the issuer's aggregate gross assets $50M or less immediately after the tranche's issuance? Which specific balance sheet or attestation supports the answer? For founding shares and early option exercises, this is typically satisfied easily; for later-stage RSU vestings and option exercises, the issuer's gross assets at the time of the underlying stock's issuance (or at the time of RSU grant, depending on structure) may have been above $50M.

**Requirement 4 — active-business test.** Was the issuer engaged in a qualified trade or business during substantially all of the tranche's holding period? Does the business sit near any of the §1202(e)(3) excluded-category boundaries (consulting-with-AI-tools, pure financial services, performance of health services, hotel/restaurant business)? Is there documentation (business description in corporate filings, revenue reporting, product descriptions) supporting the position?

**Requirement 5 — non-corporate shareholder.** You, personally — or the specific trust that holds the tranche (if applicable, which is unusual at this exercise stage but may apply for pre-existing trust structures) — are the shareholder. Is the shareholder a non-corporate taxpayer? If a trust, is it a grantor trust (flow-through to grantor's cap) or non-grantor trust (separate cap)?

Produce a tranche-by-tranche spreadsheet or table with the five tests marked **PASS**, **FAIL**, or **UNRESOLVED — needs counsel review** for each tranche. For FAIL tranches, note the specific reason (e.g., "pre-conversion S-corp equity"); for UNRESOLVED tranches, note the specific question (e.g., "RSU-grant-date is unknown — need stock-plan-administrator export").

### 4. The vintage and exclusion-percentage analysis

For each PASS tranche, determine the acquisition-date vintage and the applicable exclusion percentage:

- Stock acquired after 2010-09-27: **100% exclusion** (and no AMT preference, no NIIT on excluded portion).
- Stock acquired 2009-02-18 through 2010-09-27: **75% exclusion** (7% of excluded portion as AMT preference under §57(a)(7)).
- Stock acquired 1993-08-11 through 2009-02-17: **50% exclusion** (7% AMT preference; non-excluded portion subject to 28% maximum rate under §1(h)(4)(A)(ii)).
- Stock acquired before 1993-08-11: **not QSBS-eligible**.

Note: the acquisition date for the vintage test is the actual acquisition date of each tranche — the option-exercise date, the RSU-delivery date, the convertible-note-conversion date — not the grant or purchase date.

### 5. The 5-year-holding-period analysis

For each PASS tranche, determine whether the holding period will reach 5 years by the planned transaction date (or by the §1202-election-date for a staged sale). Note tranches that:

- Will reach 5 years before the transaction date (eligible for §1202 at transaction).
- Will *not* reach 5 years before the transaction date (not eligible at transaction; §1045 rollover is the only path to eventual §1202 treatment on these tranches).
- Reach 5 years at some specific intermediate date during a staged-sale schedule (relevant for the 10b5-1 plan design in exercise 03).

### 6. The cap arithmetic — current pre-planning scenario

For each PASS tranche with a 5-year hold at transaction, compute:

- **Gain per tranche.** Expected sale price × shares in tranche − adjusted basis.
- **Aggregate gain across tranches, per issuer.** Sum of per-tranche gains.
- **The §1202(b) cap.** The greater of ($10M, reduced by prior-year-excluded gain on this issuer by this shareholder) or (10 × aggregate adjusted basis across QSBS of this issuer disposed of in the tax year).
- **Excluded portion.** The lesser of the cap or the aggregate gain. Multiply by the vintage percentage (100%, 75%, or 50%) to get the federally-excluded gain.
- **Taxable portion.** Aggregate gain minus excluded portion.
- **Federal tax on taxable portion.** Approximately 23.8% blended rate for 100%-vintage non-excluded portion (long-term capital gains 20% + NIIT 3.8%); 23.8% + AMT consideration for 75% and 50% vintages (consult tax counsel for the specific AMT computation).

### 7. The state-conformity overlay

For your state of residence, document the specific §1202 conformity rule:

- **Non-conforming states** (California, Pennsylvania): the entire gain is subject to state tax at the state marginal rate. Compute the state tax on the full gain at the current state rate.
- **Conforming states** (Massachusetts, New York, and most others): the state follows the federal exclusion. Compute state tax on the taxable (non-excluded) portion only.
- **No-income-tax states** (Texas, Florida, Washington, Nevada, South Dakota, Wyoming, Alaska, Tennessee, and New Hampshire for non-interest-and-dividend income): no state income tax on the gain.
- **State-residency-change scenarios.** If you are considering a pre-close residency change, document the specific plan (physical relocation date, driver-license-and-registration changes, home-purchase-and-sale actions, severance of prior-state ties). Note that this is education, not advice — a defensible residency change requires specific counsel review and is aggressively audited by the Franchise Tax Board in California and by analogous agencies in other states.

### 8. The evidence inventory

For each PASS tranche, catalogue the evidence supporting the §1202 position:

- Corporate charter and/or certificate of incorporation showing C-corp status at the tranche's issuance date.
- Stock certificate, cap-table entry, or stock-plan-administrator record documenting the specific acquisition date and consideration.
- Gross-asset balance sheet or QSBS attestation letter from the issuer's CFO or tax advisor documenting the $50M-test satisfaction at the tranche's issuance date.
- Business-description documentation (board minutes, product roadmaps, business plans, revenue reporting) supporting the active-business test throughout the holding period.
- For optional-exercise tranches: the exercise notice, cheque or payment confirmation, and ISO-vs-NSO documentation.
- For RSU tranches: the grant notice, vesting schedule, and delivery confirmation.
- For convertible-note tranches: the original note purchase documents, the conversion election, and the conversion-event documentation.

Note any missing-or-fragmentary evidence as an action item. Request a current QSBS attestation letter from the issuer's CFO or tax advisor as part of pre-transaction planning if one does not exist.

### 9. The one-page QSBS position memo

Produce a one-page memo you would hand to a private-client tax attorney before the first engagement meeting. The memo should include:

- The frozen personal fact-pattern profile summary (3–5 bullets).
- The tranche inventory summary table (tranche, shares, basis, acquisition date, vintage, pass/fail/unresolved, cap-applicable).
- The pre-planning cap-arithmetic result (aggregate gain, cap, excluded portion, taxable portion, federal tax, state tax).
- The specific unresolved questions for counsel (one bullet per question): e.g., "Confirm active-business test for the 2019–2022 period when the issuer's revenue mix shifted toward consulting services"; "Confirm RSU-delivery-date vs. underlying-stock-issuance-date treatment for the 2022-04-01 RSU tranche when the issuer had already crossed $50M in gross assets at the 2021 grant date"; "Confirm Massachusetts QSBS conformity for the specific holdings — the Massachusetts rules have specific property-qualification variations".
- The evidence-chain gaps (what documentation is missing and needs to be gathered).

## Starter guidance

Three anti-patterns to avoid:

- **Aggregating across tranches.** The analysis runs tranche by tranche, not at the shareholder-aggregate level. A founder with 1M founding shares (QSBS, acquired at incorporation) and 50K RSU shares (not QSBS, delivered after the issuer crossed $50M) has 1M QSBS shares and 50K non-QSBS shares — not 1.05M of "mixed" QSBS. Spreadsheet rigour at the tranche level is the foundation of a defensible position.
- **Assuming all RSUs are QSBS.** The $50M gross-asset test at issuance kills late-stage RSU-vesting tranches. A senior hire in year 4 whose equity is all RSUs granted after the Series C typically holds *zero* QSBS. Walk the gross-asset-at-grant date for every RSU tranche before claiming QSBS.
- **Assuming the state conforms.** The federal §1202 exclusion is the headline number. The California-residence founder who assumes the federal $0 tax means total $0 tax discovers in the April tax filing that California's 13.3% top rate applies to the full gain. Compute state tax explicitly, not implicitly.

## Acceptance criteria

You can demonstrate that:

- The frozen personal fact-pattern profile is specific and complete across state, family, role, issuer, and transaction dimensions.
- The tranche-by-tranche inventory accounts for every specific acquisition of specific shares in the issuer.
- Each tranche has a specific PASS/FAIL/UNRESOLVED determination on each of the five qualifying-stock requirements, with the specific reason noted.
- The vintage, holding-period, and cap-arithmetic computations are specific per tranche.
- The state-conformity overlay produces a specific state-tax number for the pre-planning scenario.
- The evidence inventory identifies specific documentation per tranche and flags specific gaps.
- The one-page memo is specific enough that a private-client tax attorney reviewing it would be able to open a specific first-meeting agenda without requiring preliminary scoping.
- A critical reader (another founder, a CPA, a tax attorney) can test each tranche-level determination and find it defensible or specifically-questioned.

## Reflection

Add a short reflection (½ page):

1. Which tranche is your largest UNRESOLVED-pending-counsel-review item, and what is the specific question?
2. If your transaction were to close one month earlier than planned, how would the 5-year-holding-period analysis change, and which tranches would move from "eligible at transaction" to "needs §1045 rollover"?
3. If your state of residence changes between now and the transaction date, how does the state-conformity overlay change the taxable-outcome calculation? Which specific state-residency-change actions would need to be taken (and when) to defend the change?

## Stretch goals

- **Prior-tax-year reconciliation.** For founders with any prior-year QSBS or §1045 history, reconstruct the per-issuer cumulative-excluded-amount from prior Form 8949 filings. Confirm the available §1202(b) cap remaining per issuer.
- **Pre-conversion S-corp reconstruction.** If the issuer ran as an S-corp before C-corp conversion, model the alternative scenario of C-corp-incorporation-from-inception — what tranche-level QSBS would have been available in that alternative, and what is the cost of the actual S-corp-converted history?
- **Comparable-founder benchmark.** For a specific peer founder situation you know of (or a public account of one — e.g., a published founder exit case), reconstruct the probable QSBS position arithmetic and compare the structural choices they made (or did not make) to your plan.
