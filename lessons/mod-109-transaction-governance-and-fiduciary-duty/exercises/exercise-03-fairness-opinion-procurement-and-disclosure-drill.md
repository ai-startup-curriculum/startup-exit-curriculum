# exercise-03: Fairness Opinion Procurement and Disclosure Drill

**Estimated effort:** 4 hours

## Objective

Take the specific transaction profile from exercise-01 and the committee charter from exercise-02 and author the **fairness-opinion procurement packet** — the engagement letter, the valuation-methodology scope-of-work, the written opinion template, and the proxy-disclosure write-up for the "Opinion of the Financial Advisor" section. By the end you should be able to defend the opinion against a disclosure-based challenge and against a *Rural Metro* aiding-and-abetting challenge, and the proxy write-up should be auditable item-by-item against SEC Item 1015 of Regulation M-A.

## Background

This exercise covers material from:

- [Chapter 4 — Special Committee Construction](../04-special-committee-construction.md)
- [Chapter 5 — Banker Conflicts under Rural Metro, Del Monte, and El Paso](../05-banker-conflicts-rural-metro-del-monte-el-paso.md)
- [Chapter 6 — Fairness Opinion Procurement and Disclosure](../06-fairness-opinion-procurement-and-disclosure.md)

The fairness opinion is a specific SEC-mandated disclosure under Item 1015 of Regulation M-A when a Schedule 13E-3 going-private transaction is involved, and a market-standard disclosure in a Schedule 14A proxy for a strategic sell-side M&A deal governed by Revlon. The opinion is also a specific *Van Gorkom* procedural element — the written record that the board was "informed" of the financial fairness of the transaction. Exercise-04 covers the banker-conflict analysis in depth; this exercise covers the opinion-production workstream itself.

## Prerequisites

- The exercise-01 output and the exercise-02 output.
- Access to recent `DEFM14A` and `SC 13E3` filings on SEC EDGAR for comparable transactions (freely available), so that you can read actual "Opinion of the Financial Advisor" sections and actual Item 1015 Annex-C style disclosure. A good starting pattern is to pull the two most recent completed take-privates in your sector and the two most recent completed strategic sell-side merger proxies.
- Access to SEC Item 1015 of Regulation M-A (<https://www.ecfr.gov/current/title-17/chapter-II/part-229/subpart-M-A>) and Rule 13e-3 (<https://www.ecfr.gov/current/title-17/chapter-II/part-240/section-240.13e-3>). Reading the actual rules is the point.
- A clear statement of the banker-conflict profile — the advisor's past-and-current relationships with the counterparty, any stapled-financing arrangement, the fee structure, any undisclosed-conflict issues. Exercise-04 produces this; for this exercise, work from a draft version and iterate when exercise-04 produces the final.

## Tasks

### 1. Scope-of-opinion specification

Draft a one-page scope-of-opinion memo that the committee adopts by resolution before the advisor begins its final valuation workstream. Required elements:

- **Addressee.** The committee only, or the committee plus the full board, or the stockholders. The addressee shapes the duty owed; the standard is "the committee / the board" and not the stockholders directly (opinions-to-stockholders are a specific pattern with different liability exposure).
- **Target assertion.** "The consideration is fair, from a financial point of view, to the [stockholders / minority stockholders / public stockholders / holders of common stock other than the controller]." Specify who is included. In a controller take-private, the standard is "to the public stockholders other than the controller and its affiliates." In a strategic merger, "to the holders of common stock." The specific wording is dispositive.
- **Scope limitations.** The opinion does not: (a) opine on the merits of the transaction; (b) opine on alternatives; (c) opine on the specific allocation of consideration among classes; (d) opine on fairness to specific individuals (directors, officers, controllers, affiliates); (e) opine on tax, legal, regulatory, or accounting matters; (f) opine on the price at which the shares will trade post-close.
- **Information relied on.** The specific company-produced management forecasts (critical — the LRP / long-range plan must be board-adopted, management-signed, and the committee has a specific duty to interrogate before relying), the specific publicly-available financial information, the specific industry data, the specific comparable-transaction and trading-comparable data, specific due-diligence information.
- **Valuation methodologies.** The specific methodologies the advisor will apply: discounted-cash-flow (DCF); selected-public-companies (trading comps / multiples); selected-precedent-transactions (deal multiples); premia-paid analysis; sum-of-the-parts (if applicable); other-specific (e.g., leveraged-buyout / "LBO" analysis, net-asset-value for asset-heavy companies, specific-industry — resource-based NAV, biotech risk-adjusted-NPV, insurance embedded value).
- **Information not relied on.** The specific items the advisor has not independently verified (financial statements, management forecasts, specific legal / regulatory assertions). The specific items the advisor has not independently investigated.
- **Date of opinion.** The specific date — typically the date of the committee's recommendation vote; the opinion is "as of" that date and the advisor has no duty to update.

### 2. Valuation-methodology scope and discount-rate work-up

Draft the committee's expectations for the advisor's valuation methodologies. For each methodology, specify the specific expected analysis:

- **Discounted-cash-flow (DCF).**
  - Projection period (typically 5 years for a mature company; longer for a company with a long operating cycle; shorter if a credible terminal reached sooner).
  - Terminal-value approach (perpetuity-growth, exit-multiple on a specific metric — EBITDA, EBIT, revenue — or hybrid). Specific growth-rate or exit-multiple range.
  - Discount-rate derivation: capital-asset-pricing-model (CAPM) build-up with specific risk-free rate (10-year or 20-year Treasury as of the valuation date), specific equity-risk-premium range (sourced to Duff & Phelps / Kroll Cost of Capital Navigator or Damodaran-published values, with the specific published date), specific beta (industry or peer-set median, re-levered to the target's capital structure), specific size-premium (Duff & Phelps / Kroll decile-based or alternative), specific company-specific premium (if any — rare and conservative). Walk the WACC build-up to a specific range.
  - Projected cash flows: operating assumptions, capex / depreciation treatment, net-working-capital investment, taxes (effective tax rate — note TCJA interaction), stock-based-compensation treatment (expense, not add-back, under current practitioner convention post-*In re Appraisal of PetSmart, Inc.*, 2017 WL 2303599 (Del. Ch. May 26, 2017) and *In re Jarden Corp. Appraisal Litigation*, 236 A.3d 313 (Del. 2020)).
  - Sensitivity analysis: specific range of discount rates, specific range of terminal-growth / exit-multiples, specific range of operating-sensitivity (revenue growth, margin, specific KPI).
- **Selected-public-companies / trading comps.**
  - Specific peer set — named companies with specific inclusion rationale (sector, size, growth, margin, business model). Target 5-10 comparables. Exclude obviously-not-comparable even if sector-adjacent.
  - Specific multiples applied: EV/revenue, EV/EBITDA, EV/EBIT, P/E (for mature profitable companies), specific sector-standard (SaaS: EV/ARR, EV/next-twelve-month-ARR; biotech: specific pipeline-adjusted; financial services: P/book, P/tangible-book; retail: EV/sales).
  - Specific trading date / 30-day VWAP / 60-day VWAP.
  - Specific range of implied values from each multiple.
- **Selected-precedent-transactions / deal comps.**
  - Specific transactions — named target, named acquirer, specific announcement date, specific transaction size, specific consideration, specific implied multiples. Target 5-10 transactions. Draw from the past 3-5 years, extending further only for specific-sector comparability.
  - Specific selection rationale (sector, size, strategic / financial buyer, consideration mix).
  - Specific multiple application and implied range.
- **Premia-paid analysis.**
  - Specific premium ranges (10-day, 30-day, 60-day VWAP) across the comparable set.
  - Specific implied-price range at median / mean / interquartile premiums.
- **LBO analysis** (if a private-equity buyer or if the committee is testing a floor).
  - Specific capital-structure assumption (leverage multiple against EBITDA or against total-cap), specific cost-of-debt, specific sponsor return hurdle, specific hold period, specific exit multiple.
- **Sum-of-the-parts** (if applicable to a multi-segment company).

For each methodology produce a specific implied-per-share-value range. The final opinion's reconciliation of the ranges is the single most-litigated element of the opinion in a Delaware appraisal context. State the specific weighting (or specific non-weighting; the modern practice is to show the ranges and not to average them).

### 3. Advisor conflicts disclosure requirement

Before the opinion is delivered, require the advisor to produce a specific conflicts-disclosure letter. Draft the request. The letter must address:

- All current and prior investment-banking and advisory engagements by the firm (and its affiliates) with the counterparty, the controller, any director or executive officer of either side, and any specific stakeholder (sponsor, major holder) in the past 2 years, with specific fee amounts.
- All stapled-financing or financing-related engagements being pursued or discussed in connection with the specific transaction.
- All firm-and-affiliate ownership of securities of either side, both proprietary / principal-investment and client-held.
- Specific personal relationships of the lead banker (and material team members) with specific directors, officers, controllers of either side.
- Specific prior fairness-opinion engagements in similar-structure transactions.
- Any specific past-controversy — specific prior litigation, specific prior Chancery opinion naming the firm or the specific lead banker (Rural Metro, Del Monte, El Paso, Dole, Pattern Energy, Zale).

The disclosure letter is dated as of the opinion date and is retained in the committee's record. Exercise-04 processes the disclosure in depth.

### 4. Opinion-letter template

Draft the full written opinion-letter template. Required elements:

- **Addressee.** The special committee (and / or the full board of directors).
- **Subject.** The specific proposed transaction, with specific definitive agreement citation and specific consideration terms.
- **Scope.** The specific opinion sought ("fair, from a financial point of view, to [specific stockholders]"). The specific "as of" date.
- **Procedures.** The specific analyses performed. A specific recital of (a) review of the merger agreement draft and relevant financial information; (b) discussion with management; (c) consideration of comparable publicly-traded companies; (d) consideration of comparable precedent transactions; (e) DCF analysis; (f) specific other methodologies; (g) specific due diligence on the counterparty.
- **Assumptions.** The specific items relied on without independent verification. Specific carve-out that the opinion does not address specific items (tax, legal, regulatory, specific allocation among classes, going-concern).
- **Scope limitation.** Specific scope-limitation paragraph.
- **Opinion.** The specific statement that "as of the date hereof, the Consideration to be received by the holders of [class] of the Company Common Stock pursuant to the Merger is fair, from a financial point of view, to such holders [other than specific excluded persons]."
- **Fee and conflicts.** Specific recital of the advisor's fee structure (specific retainer / opinion-fee / specific transaction-fee / specific transaction-fee contingency), and specific recital of material relationships with the counterparty, the controller, any director / officer, in the past 2 years. The specific banker-conflict analysis for exercise-04 produces the specific text here.
- **Advisor consent.** The specific consent to inclusion in the proxy / Schedule 14A / Schedule 13E-3.

### 5. "Opinion of the Financial Advisor" proxy write-up

Draft the specific proxy-disclosure section the "Background of the Merger" and "Opinion of the Financial Advisor" sections of the Schedule 14A will contain. Required elements, mapped to SEC Item 1015 of Regulation M-A:

- **Item 1015(a).** Specific identity of the advisor.
- **Item 1015(b)(1).** Specific summary of the opinion, including the specific conclusion.
- **Item 1015(b)(2).** Specific description of the procedures followed, including each specific analysis performed, the specific inputs relied on, the specific scope limitations.
- **Item 1015(b)(3).** Specific summary of each specific valuation methodology — DCF (specific discount-rate range, specific terminal-value method, specific implied-value range), selected-public-companies (specific peer set, specific multiples, specific implied range), selected-precedent-transactions (specific transactions, specific multiples, specific implied range), premia-paid (specific ranges and implied values), any other specific methodology — with the specific per-share range implied by each.
- **Item 1015(b)(4).** Specific instructions, orders, limitations imposed on the advisor by the issuer / counterparty.
- **Item 1015(b)(5).** Specific material relationships that existed in the past two years or that are mutually understood to be contemplated.
- **Item 1015(b)(6).** Specific compensation received or to be received by the advisor.
- **Item 1015(c).** The specific availability of the opinion for stockholder review (filed as an exhibit to the Schedule 14A, available at a specific physical / electronic location).

The proxy write-up must stand up to specific *In re Trulia* / *In re Saba Software* / *City of Fort Myers General Employees' Pension Fund v. Haley*, 235 A.3d 702 (Del. 2020) scrutiny on specific disclosure completeness. In particular, specifically describe (not summarise generically) each valuation methodology's inputs and ranges, and specifically describe the advisor's material financial-interest in the transaction.

### 6. Committee minutes for the opinion-receipt meeting

Draft the specific committee-meeting minutes for the meeting at which the opinion is delivered and the recommendation vote taken. Required elements:

- Specific attendees — committee members, committee counsel, committee financial advisor, specific other invitees. Specific executive-session treatment.
- Specific presentation by the advisor — the specific bank-books-and-decks reviewed, the specific valuation ranges presented, the specific comparable-company and transaction set, the specific DCF build-up (discount rate, terminal value), the specific sensitivity analyses.
- Specific committee discussion — the specific questions asked by committee members on each methodology, the specific advisor responses, the specific challenge of the counter-example analyses.
- Specific advisor-conflict acknowledgement — the specific conflict-disclosure letter is in the committee's record, the specific committee understanding of each relationship, the specific committee determination that the conflicts do not impair the opinion.
- Specific receipt of the written opinion. Specific resolution of the committee (a) accepting the opinion for the record, (b) recommending (or not recommending) the transaction to the full board, (c) resolving on any specific negotiation items that remain.
- Specific record-keeping — the opinion, the advisor's deck, the advisor's conflict-disclosure letter, the committee's minutes, the committee counsel's privileged memo, all retained in the committee's file.

Chapter 8 exercise-08 drills the minute-book discipline in depth; here, draft the opinion-receipt-meeting minutes as a specific instance.

## Starter guidance

Three anti-patterns to avoid:

- **The "we'll figure out the discount rate when the banker gets to it".** The committee has specific duties to interrogate the discount-rate build-up and the terminal-value assumption. Deferring to the banker's output without specific challenge is a *Van Gorkom*-style abdication. The committee should be able to defend each input against a plaintiff's expert.
- **The "we trust the banker; we don't need a conflicts letter".** Even if the committee has run the exercise-04 banker-conflict analysis, the specific written disclosure letter is the piece that ends up in the committee's record and (in excerpted form) in the proxy. A committee without a written conflicts letter in its file has given a plaintiff a specific discovery item.
- **The "the opinion is boilerplate; copy the last one".** The opinion is a specific legal instrument tied to specific facts, specific valuation ranges, specific conflicts, specific scope. Boilerplate opinions are the ones that get challenged — a specific-facts-tailored opinion is harder to attack.

## Acceptance criteria

You can demonstrate that:

- The scope-of-opinion memo specifies addressee, target assertion, scope limitations, information relied on, methodologies, information-not-verified, and date.
- The valuation-methodology scope has specific-range outputs for each methodology.
- The discount-rate build-up has specific sourced components (risk-free, ERP, beta, size-premium, specific-rate) each with a specific published-reference citation and date.
- The advisor-conflicts disclosure requirement is written as a specific request letter.
- The opinion-letter template addresses addressee, subject, scope, procedures, assumptions, scope limitation, opinion, fee / conflicts, consent.
- The proxy write-up is auditable against Item 1015(a)-(c) item by item.
- The committee minutes for the opinion-receipt meeting are drafted and would survive early Chancery discovery.
- A critical reader (Delaware specialist counsel, in-house legal, peer banker) could stress-test a specific valuation range and see the specific input you used.

## Reflection

Add a short reflection (½ page):

1. Which valuation methodology produces the widest range and why? What specific input drove the width?
2. Which specific line in the opinion letter is the one most likely to be challenged in a *In re Appraisal of X* proceeding and what is the defence?
3. If you had to defend the opinion in a *Rural Metro* aiding-and-abetting suit, which specific advisor-conflict disclosure in the opinion is the one you would point to?

## Stretch goals

- **DCF rebuttal exercise.** Pick a specific recent Delaware appraisal opinion that attacked a specific DCF input (*In re Appraisal of PetSmart, Inc.*, 2017 WL 2303599 (Del. Ch. May 26, 2017); *In re Jarden Corp. Appraisal Litigation*, 236 A.3d 313 (Del. 2020); *Verition Partners Master Fund Ltd. v. Aruba Networks, Inc.*, 210 A.3d 128 (Del. 2019)) and write a 1-page memo on how your DCF would hold up against the specific plaintiff-expert attack.
- **Alternative-advisor second-opinion option.** If the committee is in a specific-exposed posture (large banker fee contingency, major past relationships), consider a specific independent-valuation-firm second opinion. Draft the engagement scope — who the firm is, what the scope is, what the fee structure is, how the second opinion is handled in the proxy (second opinion disclosed, or used as internal cross-check only).
- **Item 1015 line-by-line audit.** Pull the two most recent Schedule 13E-3 filings in your sector. Walk your proxy write-up against each one line-by-line. What is the specific disclosure your filing has that the comparables do not, and what is missing from yours that the comparables have?
