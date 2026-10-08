# exercise-08: EDGAR Filing Choreography Drill

**Estimated effort:** 4 hours

## Objective

Take the frozen pre-IPO company profile you have carried through exercises 01-07 and produce the specific EDGAR filing-choreography package a CFO / GC / IR head would walk into the T-minus-120-day working-group meeting with: a back-solved DRS-to-pricing calendar, a Form ID / credential custody plan, a Section 8(a) acceleration-day script, a Form 8-K item-trigger register, a Regulation FD programme design, a Section 16 reporting infrastructure, a SOX 302 / 906 certification pipeline, an iXBRL tagging-governance plan, a first-year disclosure calendar, and a Rule 477 withdrawal contingency. By the end you should be able to walk the package into a working-group meeting and defend it against a critical IPO-counsel partner, a critical financial-printer managing director, and a critical audit-committee chair with a specific accession-number-level operational grasp.

> Reminder: this module is education, not legal / accounting / tax advice. Every EDGAR filing is executed under supervision of qualified securities counsel and the issuer's PCAOB-registered auditor, with financial-printer support handling submission packaging, iXBRL tagging, and access-code mechanics.

## Background

This exercise covers material from:

- [Chapter 8 — EDGAR Filing Choreography and the Post-IPO Disclosure Regime](../08-edgar-filing-choreography.md)

This is the module's capstone — it closes the loop between the readiness framing of chapter 1, the S-1 drafting of chapter 2, the auditor and audit-history workstream of chapter 3, the SOX programme of chapter 4, the EGC-election decisions of chapter 5, the dual-track structure of chapter 6, and the listing-standard graduation of chapter 7, and the live-filing pipeline the public issuer actually runs on day one. Chapters 1-7 are prerequisites — refer at the boundary, do not re-teach. The specific listing-authorisation letter from the exchange (chapter 7) is a precondition to the Section 8(a) acceleration request; the SOX 302 sub-certification cascade (chapter 4) feeds the certification pipeline below; the EGC filer-class trajectory (chapter 5) sets the 10-K and 10-Q due-date clock; the dual-track structure (chapter 6) sets the Rule 477 contingency; the auditor consent (chapter 3) sits in Exhibit 23 under the acceleration precondition set.

Ownership boundaries called out explicitly:

- **Roadshow / pricing / allocation / greenshoe / lock-up mechanics live in mod-108.** This exercise owns the EDGAR plumbing (the public-flip timing, the 424(b)(4) filing, the acceleration-request choreography); it does not re-teach the roadshow or pricing-meeting content.
- **Transaction-governance and fiduciary-duty depth lives in mod-109.** The specific audit-committee and board governance of the public-filing cycle is covered there; this exercise owns only the filing-mechanic overlay.
- **Transaction-communications strategic / content work lives in mod-110.** Regulation FD intersects — this exercise owns the EDGAR filing mechanics of the FD programme (Form 8-K Item 7.01, pre-designated channels, incident-response filing cadence); mod-110 owns the strategic communications design.
- **Personal 10b5-1 trading-plan design lives in mod-114.** This exercise references 10b5-1 only at the Section 16 and Rule 10b5-1 cooling-off boundary.
- **Security-engineering programme behind Item 106 cybersecurity disclosure defers to security-learning.** This exercise owns the Item 1.05 / Item 106 filing-trigger workflow; the underlying security programme is out of scope.
- **AI-safety-technical content of AI-usage disclosures defers to head-of-ai-governance-learning.** This exercise owns only the Reg S-K / 8-K disclosure plumbing where AI-usage disclosure surfaces.
- **Ongoing-company finance-function design is owned by `startup-finance-fundraising-curriculum` mod-111.** This exercise references the close-cycle discipline that supports the disclosure calendar but does not re-teach it.

## Prerequisites

Carry forward the frozen pre-IPO company profile from exercise-01 (sector, ARR, growth, cap-table, auditor, board, CFO / GC / VP-IR bench, anticipated listing exchange), the Task 2 exchange recommendation and listing-standard build from exercise-07, the EGC election from exercise-05, the dual-track posture from exercise-06, and the auditor engagement and reaudit calendar from exercise-03. Do not re-open those frozen choices. In addition, freeze the following incremental fields at the top of your deliverable — no `TBD` fields in the frozen profile:

- Anticipated pricing date: ____ (specific target business day).
- Anticipated roadshow start: ____ (target business day; typically T-10 to T-14 from pricing).
- Anticipated initial-DRS submission date: ____ (back-solved from pricing).
- Fiscal year-end: ____ (determines filer-class due-date math).
- Anticipated public float at listing (shares × low-end of pricing range): $____.
- Anticipated public float at the last business day of the second fiscal quarter post-listing (sensitivity: pricing × typical aftermarket drift): $____.
- Rule 12b-2 filer-class projection at IPO: large accelerated / accelerated / non-accelerated / smaller reporting company (with the specific public-float calculation).
- EGC status at IPO (Yes / No under JOBS Act Section 2(a)(19) — carry forward from exercise-05).
- Financial-printer selection: DFIN / Toppan Merrill / Workiva / other (with rationale).
- Current EDGAR filer status (CIK already assigned, Yes / No; if No, Form ID target submission date).
- Section 16 insider population at effectiveness: directors (count), designated Section 16 officers (count), 10% beneficial owners (list).
- Anticipated 180-day lock-up expiry date (carry forward from exercise-06 / mod-108 preview).
- First post-effective fiscal quarter-end (target first 10-Q filing anchor).

Access requirements for the exercise:

- SEC EDGAR for the historical filing timelines of 5-10 recent comparable IPOs in the same sub-sector — initial DRS submission date, number of DRS/A cycles, flip date, S-1 effectiveness date, 424(b)(4) date, Form 8-A date, first 10-Q date. The practitioner move is to reconstruct the specific choreography that cleared staff review on comparable deals.
- The SEC's **EDGAR Filer Manual** (Volumes I, II, III) and the **Division of Corporation Finance Financial Reporting Manual** for the specific procedural guidance cited across the tasks.
- The current PCAOB / SEC fee-rate advisory for Section 6(b) registration fees (needs-research marker required where the current rate is uncertain).
- Printer-published filing-calendar templates (DFIN, Toppan Merrill, Workiva all publish IPO-cycle timing references).

## Tasks

### 1. EDGAR filer-credential and filing-agent build

Design the credential and filing-authorisation stack and sequence it against the initial-DRS target.

- **Form ID submission.** Confirm the issuer has (or will apply for) a CIK via Form ID at least **two weeks before** the first anticipated filing; schedule the specific submission date giving at least a three-week cushion to absorb notarisation and SEC-processing failure modes. Where the issuer already has a CIK (prior unregistered-securities Form D filings, for example), skip Form ID and confirm the credential set is current.
- **Credential custody plan.** For the CIK, CCC, PMAC, and EDGAR access codes, specify: who holds each credential (CFO / GC / Corporate Secretary / Treasurer); where it is stored (named password-vault with specific access control, printed physical copy under what custody); who at the financial printer has operational access; the specific PMAC-reset drill the GC can run on 24-hour notice if the CCC is compromised.
- **Financial-printer-as-filing-agent engagement.** Choose among DFIN / Toppan Merrill / Workiva (carry forward from the prerequisites) with a one-paragraph rationale covering: sector bench on comparable IPOs, iXBRL tagging capability, 24-hour operational coverage during pricing week, Section 16 service offering, and vendor-concentration risk. Specify the written filing-authorisation scope (which printer personnel are authorised to submit filings on behalf of the issuer, and the specific out-of-scope filings the issuer retains direct control over).
- **EDGAR Next transition posture.** Note the EDGAR Next modernisation programme and the obligation to track SEC filer-manual updates so the credential model in use is current. <!-- needs-research: specific 2024/2025 EDGAR Next transition milestone dates, individual-user-account adoption deadlines, and legacy-credential deprecation timing --> Assign a specific internal owner to monitor filer-manual updates quarterly.

Deliver a specific one-page credential-and-filing-agent brief with the Form ID date, the credential-custody matrix, the printer selection, and the EDGAR Next monitoring owner.

### 2. DRS-to-pricing calendar back-solve

Back-solve the full confidential-DRS-through-pricing calendar from the anticipated pricing date.

- **Pricing date** → anchor.
- **Section 8(a) acceleration-request effectiveness target.** 4:00 PM Eastern the day before pricing (T-1 at market close) under the standard practitioner pattern.
- **Roadshow start.** Typically T-10 to T-14 business days from pricing (specific window from exercise-06 / mod-108 preview).
- **Public S-1 flip.** At least **15 days before the first roadshow meeting** under **JOBS Act Section 6(e)** (EGC) or SEC staff guidance mirroring the 15-day rule for non-EGC confidential filers. Specify the exact flip date.
- **Clean amendment (final DRS/A or S-1/A).** Submitted at or shortly before the flip, reflecting all cleared comments; staff signal of readiness via the "Bedford Falls" or equivalent clearance communication precedes.
- **Amendment cycle.** 3-5 DRS/A amendments over **4-8 months** between initial DRS and clean amendment. Map the typical staff comment-letter cadence: first letter approximately 30 days after initial DRS; subsequent letters 10-20 days after each amendment response.
- **Initial DRS submission.** Back-solved from the clean amendment: 4-8 months earlier. Specify the specific target date and confirm it aligns with the audit-history reissuance / reaudit completion date from exercise-03, the SOX 404 readiness milestones from exercise-04, and the EGC and dual-track decisions from exercises 05 and 06.
- **Response-letter cadence.** For each anticipated DRS/A, draft the specific working-group response-letter cadence: who drafts (outside counsel, with auditor input on financial-statement comments), who reviews (CFO, GC, audit-committee chair), what the specific target turn-around is per comment letter (typically 2-4 weeks).

Deliver a specific one-page calendar with every milestone and a visible critical-path annotation. Where any date is contingent on a specific external gating event (auditor consent, FINRA 5110 clearance, exchange authorisation), mark the contingency explicitly.

### 3. Section 6(b) registration-fee pay plan

Design the specific registration-fee workflow.

- **Fee calculation.** Register fee at Section 6(b) rate times the aggregate dollar amount of securities registered. <!-- needs-research: confirm current Section 6(b) fee rate per million dollars of registered securities as of filing year, and the specific SEC Fee Rate Advisory effective date --> Compute the specific fee against the anticipated base + greenshoe aggregate offering amount.
- **Treasury wire mechanics.** Who at treasury authorises the wire, who at the printer coordinates the Fedwire or EDGAR fee-processing submission, the specific pre-filing cutoff timing (the fee must be in the SEC's account before the submission is accepted), the specific backup wire-day calendar in case the primary wire fails.
- **Amendment fee top-ups.** If a subsequent amendment increases the registered dollar amount (upsize from pricing-range expansion), the incremental Section 6(b) fee must be paid on the filing date of the amendment. Specify the fee-top-up workflow.
- **Withdrawal fee treatment.** Under **Rule 457**, the Section 6(b) fee is non-refundable upon withdrawal under Rule 477 (Task 10), though limited offset-against-future-filing accommodations exist. <!-- needs-research: confirm current Rule 457 fee-offset accommodations and specific availability for a successor registration statement --> Note the offset posture explicitly.

### 4. Section 8(a) acceleration-request choreography

Draft the specific effectiveness-day acceleration script.

- **Pre-conditions check (effectiveness day minus a few hours).** Confirm each precondition is in place:
  - All substantive SEC staff comments resolved; staff clearance signalled.
  - **FINRA Rule 5110** "no objections" letter on underwriting compensation received.
  - Listing-exchange authorisation letter received from NYSE Regulation or Nasdaq Listing Qualifications (refer at boundary — chapter 7 / exercise-07 owns the listing-authorisation workstream).
  - Auditor consent delivered for Exhibit 23 (refer at boundary — chapter 3 / exercise-03 owns the consent mechanics).
  - Underwriter counsel and issuer counsel opinions and negative-assurance letters delivered.
  - Comfort letter from the auditor delivered (refer at boundary — chapter 3 / exercise-03 owns comfort-letter mechanics).
- **Request submission.** The specific written acceleration request, signed by the issuer and the managing underwriters, requesting effectiveness at a specific date and time — target **4:00 PM Eastern the day before pricing**. Printer transmits via EDGAR; GC confirms receipt and effectiveness order.
- **Clearance communication.** Draft the specific internal communications tree the moment effectiveness is granted: GC → CEO / CFO / board chair → underwriter syndicate desks → printer activates 424(b)(4) workflow → IR activates pricing-meeting materials.
- **Failure modes.** Specify the specific fallback choreography if any precondition slips (comment reopened, FINRA letter delayed, listing authorisation held) — delayed effectiveness, pushed pricing, specific communications discipline with the syndicate and the board.

Deliver a specific hour-by-hour effectiveness-day script from pre-market check through post-close acceleration-order confirmation.

### 5. Rule 424(b)(4) final-prospectus mechanics

Design the pricing-night-to-424(b)(4) workflow.

- **Trigger.** Deal priced the evening after effectiveness. Final prospectus must be filed under **Rule 424(b)(4)** of the Securities Act within **two business days of the earlier of first use or effectiveness**.
- **Content.** Final offering size, final price per share, final use-of-proceeds table, final capitalisation and dilution tables, final syndicate allocation table, final share counts (including greenshoe disclosure).
- **Printer workflow.** Specify the specific overnight workflow — numbers locked at pricing meeting → finance team updates financial tables → counsel updates legal sections → printer formats and tags → GC and CFO sign-off → file via EDGAR before market open or by the T+2 business-day cut-off.
- **Verification gates.** Pre-filing tick-and-tie of every number against the pricing-meeting record; specific QA step on the use-of-proceeds table; verification of the greenshoe disclosure.

### 6. Form 8-A Section 12(b) Exchange Act registration

Specify the Form 8-A choreography contemporaneous with S-1 effectiveness.

- **Timing.** Filed on EDGAR contemporaneously with S-1 effectiveness so the Section 12(b) registration is in place before listing goes live. Specify the specific coordination with the exchange-listing-authorisation letter (refer at boundary — exercise-07 owns the authorisation mechanics).
- **Content.** Short-form registration incorporating by reference the S-1 disclosure (description of securities, exhibits). Draft the specific exhibit list and the incorporation-by-reference language.
- **Downstream consequence.** Section 12(b) registration triggers full Exchange Act regime membership: Section 13(a) periodic reporting, Section 14 proxy rules, Section 16 insider reporting, Regulation FD, and SOX Section 302 / 404 / 906 certifications. Confirm each downstream programme is live by effectiveness.

### 7. Rule 12b-2 filer-class projection and 10-K / 10-Q due-date clock

Project the issuer's **Rule 12b-2** filer class across the first 24-36 months post-IPO.

- **At IPO.** New registrants without a historical public-float measurement are typically **non-accelerated filers** or **smaller reporting companies** depending on the public float at the first measurement date; many IPO issuers remain non-accelerated for the first fiscal year by operation of the measurement-date rule.
- **Second fiscal year.** The public float at the last business day of the second fiscal quarter of the first full fiscal year determines filer class for that year. Project the specific transition — likely to accelerated ($75M-$700M) or large accelerated ($700M+) depending on the frozen float projection.
- **Third fiscal year and beyond.** Continue the public-float trajectory; identify any specific scenario (secondary offering, down-market drift) that would move the class.
- **Due-date impact.** For each projected class, specify the specific 10-K due date (**60 / 75 / 90 days after fiscal year-end** for large accelerated / accelerated / non-accelerated or smaller reporting respectively) and the specific 10-Q due date (**40 / 45 days** respectively). Produce a calendar through fiscal year 3.
- **SOX 404(b) auditor-attestation interlock.** Refer at the boundary — chapter 4 / exercise-04 owns the SOX 404(b) timing. Note the specific accelerated-filer or large-accelerated-filer transition point at which 404(b) becomes mandatory (post-EGC and non-SRC) and link to the exercise-05 EGC-exit projection.

### 8. Form 8-K item-trigger register and triage workflow

Build a live register across the Form 8-K item taxonomy and design the triage workflow for identifying triggers before the four-business-day clock runs.

- **Item register.** For each enumerated item, note the specific trigger definition, the specific operational owner (who first sees the triggering event), and the specific "could this trigger an 8-K?" prompt the owner is trained to run.
  - **Section 1 — Business and Operations.** 1.01 (material definitive agreement — commercial and legal review); 1.02 (termination); 1.03 (bankruptcy); 1.05 (material cybersecurity incident — the 2023 rule; refer at the security-engineering boundary for the underlying programme).
  - **Section 2 — Financial Information.** 2.01 (acquisition / disposition); 2.02 (results of operations — the earnings release item); 2.03 (direct financial obligation / off-balance-sheet arrangement); 2.04 (triggering events accelerating a financial obligation); 2.05 (exit / disposal costs); 2.06 (material impairments).
  - **Section 3 — Securities and Trading Markets.** 3.01 (notice of delisting); 3.02 (unregistered sales); 3.03 (material modification to rights).
  - **Section 4 — Accountants and Financial Statements.** 4.01 (change in certifying accountant); **4.02** (non-reliance on previously issued financials — the restatement item that triggers the **Section 10D clawback** per chapter 4 and opens the securities-class-action window).
  - **Section 5 — Governance and Management.** 5.01 (changes in control); 5.02 (director / officer departures and appointments; compensatory arrangements — the multi-sub-trigger item); 5.03 (amendments to articles or bylaws); 5.05 (code of ethics amendments / waivers); 5.07 (shareholder-vote results — within four business days of the annual meeting); 5.08 (shareholder director nominations).
  - **Section 7 — Regulation FD.** 7.01 (furnished rather than filed; Section 18 liability distinction noted; Rule 10b-5 exposure retained).
  - **Section 8 — Other Events.** 8.01 (discretionary).
  - **Section 9 — Financial Statements and Exhibits.** 9.01 (exhibit index).
- **Triage workflow.** Design the specific weekly (or in high-activity periods, daily) counsel triage against the item taxonomy. Specify the specific executive-team information-flow routing — commercial contracts to legal, finance events to GC via CFO, HR events to GC via CHRO, cyber events to GC via CISO (refer at the security-engineering boundary) — with each owner trained to raise "is this an 8-K?" and the GC making the final call. Specify the specific 8-K drafting pipeline (template library, 48-hour drafting target, counsel review, CEO / CFO signoff, printer filing).
- **Four-business-day clock discipline.** Specify the specific internal escalation when the trigger is identified: the clock starts on the specific business day the trigger occurs (for most items) or the day the materiality determination is made (for Item 1.05). Specify the Item 405 Reg S-K proxy disclosure consequence of a late 8-K and the specific S-3 eligibility consequence.

Deliver a specific register the CFO / GC / IR head can carry into weekly disclosure triage.

### 9. Regulation FD programme design

Design the written FD programme.

- **Written policy.** Draft (or outline with all substantive elements) the Reg FD policy covering: covered persons (broker-dealers, investment advisers, institutional investment managers, holders reasonably expected to trade), presumptively MNPI categories (preliminary quarterly results, specific customer wins / losses, M&A plans, executive departures, cyber incidents under materiality review, pending restatements, significant financing events), authorised spokespersons, and non-authorised speakers.
- **Training cadence.** Specify the training cadence — IR team and executive team at onboarding and annually; broader-exposure functions (sales leadership, product-marketing leadership, investor-conference attendees) at annual refresh. Note the specific pre-earnings and pre-conference re-training touchpoint.
- **Incident-response protocol.** Draft the specific protocol for unintentional disclosure — detection (who hears it first), escalation (to GC within one hour), materiality determination (within specified hours with CFO / audit-committee-chair input), remediation (filed Form 8-K Item 7.01 or publicly disseminated by other broadly accessible channel). The "promptly" backstop is the earlier of **24 hours or the commencement of the next day's trading on NYSE** — specify how the policy handles after-hours slips (Thursday-evening slip corrected by Friday open; Friday-evening slip corrected by Monday open).
- **Pre-designated disclosure channels.** Specify the pre-designated channels — press release through a major wire service, filed Form 8-K Item 7.01, live-streamed public call with advance notice, filing under Item 2.02, website or social-media channel pre-designated with market notification. Reference the **2013 Netflix / Reed Hastings SEC Report of Investigation** guidance on social-media as a Reg FD channel; identify any specific social channel the company proposes to pre-designate and the specific market-notification language.
- **Covered-person contact log.** Specify the IR-maintained log of substantive investor and analyst contacts — date, participants, topics, pre-cleared / post-contact-review classification.

### 10. Section 16 reporting infrastructure

Design the Section 16 reporting pipeline.

- **Form 3 initial filing.** For every director and designated Section 16 officer at effectiveness, draft the Form 3 workflow: filing within **10 days of becoming subject to Section 16** (which for directors and officers at the IPO means 10 days after Section 12(b) registration effective date). Specify the information-gathering workflow (D&O questionnaire-driven), the beneficial-ownership computation (direct and indirect holdings, trust / family-member attribution), and the filing-agent handoff.
- **Form 4 transaction pipeline.** Specify the Form 4 workflow for every reportable transaction — open-market purchases, open-market sales, grants, vestings, option exercises, dispositions to the issuer, gifts — due **within two business days after the transaction date** (not trade-settlement). Specify the pre-trade pre-clearance workflow (from the insider-trading policy, exercise-07) feeding into the post-trade filing workflow; the specific checkbox for trades made pursuant to a Rule 10b5-1 plan (personal plan design lives in mod-114 — refer at boundary).
- **Form 5 annual catch-up.** Specify the Form 5 workflow for transactions not required to be reported on Form 4 — due **within 45 days after fiscal year-end**. Specify the annual D&O questionnaire that captures Form-5-eligible transactions.
- **Section 16(b) short-swing-profit window.** Specify the specific pre-clearance test applied before every proposed trade — matching proposed trade against the insider's prior six-month history to flag any purchase-and-sale (or sale-and-purchase) match that would trigger strict-liability disgorgement under Section 16(b). Note the specific internal responsibility (GC's office or Corporate Secretary) and the specific documentation discipline.
- **Operational owner.** Choose among: printer-managed Section 16 service (DFIN, Toppan Merrill, Workiva all offer one), in-house filing agent, or outside counsel with a dedicated Section 16 practice. Deliver a specific recommendation with rationale (cost, 24-hour responsiveness, D&O-relationship integration, cross-check against the pre-clearance process).

### 11. SOX 302 and 906 certification pipeline

Design the signoff choreography for every 10-K and 10-Q.

- **Sub-certification cascade.** Refer at the boundary — chapter 4 / exercise-04 owns the sub-certification design. Confirm it is live and that each sub-certifier has signed before the CEO / CFO SOX 302 / 906 certification.
- **Section 302 certification mechanics.** The specific civil certification required by SOX Section 302 and **Reg S-K Item 601(b)(31)** — CEO and CFO personally certify specific representations on report review, no material misstatement, fair presentation, disclosure controls, ICFR evaluation, disclosure of significant deficiencies / material weaknesses / fraud to the auditor and audit committee, and (for the 10-K) ICFR changes. Specify who drafts the certification (printer-templated, counsel-reviewed), who reviews, when the certifications are signed (immediately before filing), and the specific document-management workflow (originals held under GC custody; copies filed as exhibits 31.1 and 31.2).
- **Section 906 certification mechanics.** The specific criminal certification required by SOX Section 906 and **18 U.S.C. § 1350** — CEO and CFO personally certify report compliance with Section 13(a) or 15(d) and fair presentation. Knowing violations carry criminal fines and imprisonment. Specify the same drafting / signoff / document-management workflow (originals held under GC custody; copies filed as exhibits 32.1 and 32.2).
- **Personal-liability framing.** Draft the specific CEO / CFO briefing covering the personal nature of each certification (cannot be delegated; signed personally by the principal executive officer and the principal financial officer); the specific legal and professional-reputation exposure; the specific role of the sub-certification cascade in supporting the certifying officer's knowledge basis.
- **First-10-Q and first-10-K rehearsal.** Specify the specific pre-filing rehearsal for the first SOX 302 / 906 exercise — walk-through of the certification language with the certifying officers, the audit committee, and outside counsel, 2-4 weeks before the first-10-Q filing.

### 12. iXBRL tagging-governance plan

Design the iXBRL tagging and validation plan.

- **Rule 405 applicability.** Confirm **Regulation S-T Rule 405** iXBRL applicability for the specific filings in scope (S-1 financial statements, 10-K, 10-Q, 8-K earnings-release exhibits, cover-page data). <!-- needs-research: confirm current-year iXBRL tagging requirements by filer class and specific effective dates of the most recent FASB Financial Reporting Taxonomy updates --> Note the smaller-reporting-company and non-accelerated-filer tagging posture carried forward from Task 7.
- **Taxonomy and tagging workflow.** Specify the specific taxonomy version (FASB Financial Reporting Taxonomy — current year's release); the specific printer-tagging tool (Workiva Wdesk, DFIN ActiveDisclosure, Toppan tagging tools); the specific pre-submission tagging workflow (financial-reporting team review of tag selection, extension-element use, calculation-relationship review, dimensional-data review).
- **Extension-element discipline.** Specify the governance for extension elements — custom elements created where a concept is not natively in the taxonomy. Overuse of extensions impairs comparability and attracts SEC staff review attention. Specify the specific internal review (controller + outside auditor consultation) before any extension element is adopted.
- **Validation gates.** Specify the pre-submission validation gates — printer-run validators (SEC EDGAR schema, calculation-relationship consistency, dimensional-data consistency), controller sign-off, outside-auditor review on initial filing. Specify the specific blocking criterion: no filing submission without validator-clean output.
- **Printer-tagging-service governance.** Specify the specific SLA with the printer-tagging team — turn-around on 10-Q financial-statement tagging; escalation path on tag-selection disputes; version-control of the tagged submission.

### 13. First-year disclosure calendar

Produce a specific concrete month-by-month calendar from pricing date through 18 months, mapping every scheduled filing.

- **Pricing date → day 1.** 424(b)(4) filing within two business days (Task 5); Form 8-A contemporaneous with effectiveness (Task 6); Form 3 within 10 days of Section 12(b) effectiveness (Task 10).
- **First earnings release.** Approximately **35 days after the first full post-effective quarter-end**, coordinated so the release captures the first clean quarter (not a stub quarter partly pre-IPO) and precedes the first 10-Q.
- **First 10-Q.** Approximately **40 days** (or 45 days depending on projected filer class from Task 7) after the first full post-effective quarter-end — the **first exercise of SOX 302 / 906 certifications** (Task 11) and the first ICFR representation.
- **Subsequent quarterly cadence.** For each subsequent 10-Q, specify the specific trigger date and filing deadline.
- **First annual proxy and DEF 14A.** Approximately **four months after fiscal year-end** — the first proxy season, with the first say-on-pay vote (every one, two, or three years based on the first say-on-frequency vote), the first director-election vote under the public-company voting standard, and the first auditor-ratification vote. Specify the specific PRE 14A / DEF 14A calendar.
- **First annual meeting and Item 5.07 8-K.** Within four business days of the annual meeting (Task 8).
- **First 10-K.** At **60 / 75 / 90 days** after the first full fiscal year-end (Task 7) — the first Part III proxy-incorporation-by-reference exercise and (if applicable, see exercise-04 and exercise-05) the first **SOX 404(b)** auditor-attestation exercise.
- **Lock-up expiry.** At approximately **180 days post-pricing** — specific liquidity-and-trading event with 10b5-1 and Section 16 implications (refer at boundary — mod-108 owns lock-up mechanics; mod-114 owns personal 10b5-1 design).
- **First S-3 shelf eligibility.** After **12 calendar months** of reporting history plus satisfaction of the specific S-3 eligibility criteria (current filings, no late filings, timely 8-Ks, no Item 4.02 restatements, no specific bar). Specify the first-S-3-shelf registration target date and the Rule 415 shelf-registration workstream (refer at boundary — mod-108 owns follow-on offering mechanics).

Deliver a specific one-page month-by-month calendar from pricing date through 18 months, with every filing, every certifying signature, and every blackout window visible.

### 14. Rule 477 withdrawal contingency and dual-track handoff

Design the Rule 477 withdrawal decision tree.

- **Trigger scenarios.** Draft the specific decision tree for scenarios in which the deal does not price: (a) **market-window closure** between effectiveness and pricing (specific signal set from chapter 1 / exercise-01); (b) **pricing failure** — book insufficient at any price in the range; (c) **dual-track flip to M&A** under the chapter 6 / exercise-06 structure where the M&A path is selected over the IPO.
- **Rule 477 mechanics.** Specify the EDGAR submission type **RW** (application to withdraw); the specific SEC-consent process; the specific confidential-treatment-preservation posture for any DRS submission never publicly filed; the specific subsequent-filing disclosure obligation and diligence tax if the issuer re-attempts a filing. <!-- needs-research: confirm current Rule 457 fee-offset accommodations for a subsequent registration statement following a Rule 477 withdrawal -->
- **Dual-track handoff.** Where the trigger is dual-track flip to M&A (refer at the boundary — exercise-06 owns the dual-track decision architecture), specify the specific communications discipline across the working group (bankers, counsel, auditor, printer, exchange) and the specific board / audit-committee / transaction-committee decision minute capturing the pivot rationale.
- **Market-closure resumption plan.** Where the trigger is market-window closure with intent to re-attempt, specify the specific preservation workstream — printer archive, auditor-consent re-request cadence, counsel-opinion re-letter cadence, financial-statement staleness clock from Reg S-X Rule 3-12 (refer at boundary — chapter 3 owns financial-statement staleness). Specify the resumption trigger criteria.

Deliver a specific one-page withdrawal decision tree with every branch owner-labelled.

## Starter guidance

Five anti-patterns to avoid:

- **The printer-owns-it fallacy.** Treating EDGAR filing mechanics as entirely delegable to the financial printer is a document-of-record error that surfaces during the first restatement, the first missed Form 4, or the first FD slip. The CFO / GC must know where the credentials live, who at the printer has authority, and what the specific override is when the primary filing path breaks. The printer runs the pipeline; the issuer owns the filings.
- **The flip-calendar wishful-thinking.** Back-solving the DRS-to-pricing calendar from an aspirational pricing date without stress-testing the 4-8 month amendment cycle or the specific external-gating-event dependencies (auditor consent, FINRA 5110, exchange authorisation) produces a calendar that the first comment letter blows up. The specific practitioner discipline is a calendar with every contingency surfaced and a specific slip-protocol for each.
- **The 8-K catch-up filing.** Discovering an 8-K trigger on business day five is a specific Item 405 disclosure item in the next proxy and a specific question for S-3 eligibility. The specific practitioner discipline is a live register with weekly triage, trained operational owners across commercial / finance / HR / cyber, and a template library the GC can activate in hours not days.
- **The paper SOX certification.** Treating the SOX 302 / 906 certification as a signature block the CEO / CFO sign at the back of the 10-Q is a career-and-liberty-threatening mis-posture. The specific practitioner discipline is a sub-certification cascade that supports the certifying officer's knowledge basis, a specific pre-filing rehearsal, and a specific personal-liability briefing with outside counsel.
- **The FD programme as paper policy.** A written policy no sales leader has read, no executive has rehearsed against, and no incident-response drill has tested is a Rule 10b-5 exposure dressed as a compliance programme. The specific practitioner discipline is training, pre-earnings and pre-conference touch-points, a live covered-person contact log, and a drilled incident-response protocol that can execute inside the 24-hour / next-NYSE-open backstop.

## Acceptance criteria

You can demonstrate that:

- The frozen incremental profile is filled in with specific values (no `TBD` fields) and carries forward exercises 01-07 without re-opening frozen choices.
- The credential-and-filing-agent brief specifies the Form ID submission date (at least two weeks before first filing), a specific credential-custody matrix, a specific printer selection with rationale, and a specific EDGAR Next monitoring owner.
- The DRS-to-pricing calendar is back-solved from the pricing date through the initial DRS submission with every milestone (acceleration-day target, roadshow start, flip, clean amendment, 3-5 DRS/A cycles, response-letter cadence) and every external-gating-event contingency surfaced.
- The Section 6(b) registration-fee pay plan specifies calculation, treasury-wire mechanics, amendment-top-up workflow, and Rule 457 withdrawal-offset posture (with needs-research markers where current rates / offsets are uncertain).
- The acceleration-request script covers all pre-conditions (FINRA 5110, exchange authorisation, auditor consent, counsel opinions, comfort letter), the submission mechanics, the clearance communications tree, and the failure-mode fallbacks, with a target 4:00 PM ET effectiveness the day before pricing.
- The Rule 424(b)(4) workflow covers trigger, content, overnight workflow, and the two-business-day filing cut-off.
- The Form 8-A workflow is contemporaneous with S-1 effectiveness and the downstream Exchange Act regime membership is confirmed.
- The Rule 12b-2 filer-class projection covers the first 24-36 months with specific 10-K and 10-Q due-date impact and the SOX 404(b) interlock.
- The Form 8-K item-trigger register covers the full item taxonomy with operational owners and a specific weekly triage workflow; the four-business-day clock and the specific Item 405 / S-3 eligibility consequences are visible.
- The Reg FD programme covers written policy, covered persons, training cadence, incident-response protocol with the 24-hour / next-NYSE-open backstop, pre-designated disclosure channels (including the Netflix 2013 guidance), and a covered-person contact log.
- The Section 16 infrastructure covers Form 3 (10 days from Section 12(b) effectiveness), Form 4 (2 business days), Form 5 (45 days after FYE), the Section 16(b) short-swing-profit pre-clearance test, and an operational-owner recommendation.
- The SOX 302 / 906 pipeline specifies the signoff choreography on every 10-K and 10-Q, the personal-liability framing, and the first-10-Q and first-10-K rehearsal.
- The iXBRL tagging plan covers Rule 405 applicability, taxonomy and tagging workflow, extension-element discipline, validation gates, and printer-tagging-service governance.
- The first-year disclosure calendar maps every scheduled filing from pricing date through 18 months.
- The Rule 477 withdrawal contingency produces a specific decision tree across market-closure, pricing-failure, and dual-track-flip triggers.
- A critical outside reader (an IPO-counsel partner, a financial-printer managing director, an audit-committee chair) could challenge each element of the package and see the specific evidence and specific rule citations behind every element.

## Reflection

Add a short reflection (½ page):

1. Which specific external-gating-event dependency in the DRS-to-pricing calendar is most likely to slip for your specific company, and what specific hedge in your calendar (buffer days, parallel workstream, pre-landed clearance) absorbs the slip without pushing the pricing date?
2. If the Rule 12b-2 filer-class projection moves the company from accelerated to large accelerated earlier than expected (e.g., aftermarket strength pushes public float above $700M at the second-quarter measurement), which specific element of your disclosure calendar is most exposed and how do you remediate inside the compressed 60-day 10-K deadline?
3. Which specific Form 8-K item in your trigger register is the one most likely to miss the four-business-day clock in your specific operating context, and what specific operational-ownership change (training, routing, triage frequency) closes the gap?

## Stretch goals

- **Comparable-issuer timeline reconstruction.** Pull the full EDGAR filing timeline (initial DRS, each DRS/A, flip date, S-1 effectiveness, 424(b)(4), Form 8-A, first 10-Q, first 10-K) for three specific recent IPOs in your sub-sector. Reconstruct the specific calendar for each. Which patterns emerge in the amendment-cycle length, the comment-letter cadence, and the clean-amendment-to-flip spacing, and how does your specific calendar compare?
- **8-K tabletop drill.** Run a specific tabletop: on business day 1, the CFO identifies that a historically disclosed revenue number for the most recent quarter was computed using a methodology that may not comply with ASC 606. Walk the specific 48-hour workflow through the GC / audit-committee-chair / outside auditor / outside counsel decision tree. Produce the specific Item 4.02 non-reliance determination memo (or, if non-reliance is not warranted, the specific written analysis defending that conclusion), the specific Form 8-K Item 4.02 draft with the specific filing date, and the specific Section 10D clawback and class-action window pre-briefing for the CEO and board.
- **FD incident-response drill.** Run a specific tabletop: at 4:30 PM ET on a Thursday, the CFO discloses in a one-on-one with a specific sell-side analyst that quarterly revenue will land above the top end of previously issued guidance. Walk the specific incident-response workflow through the 24-hour / Friday-open backstop — detection, escalation to GC, materiality determination, Form 8-K Item 7.01 drafting and filing, press-release coordination, broad dissemination verification. Produce the specific 8-K text and the specific internal post-mortem memo.
- **First-year disclosure calendar simulation.** Simulate the first fiscal year post-IPO month-by-month, overlaying every scheduled filing, every blackout window, every audit-committee meeting, every earnings call, and the lock-up expiry. Identify the specific two or three weeks in the year where filing-cadence density is highest and the specific resource-allocation and personnel-coverage plan the CFO / GC / IR head would put in place to absorb the load.
