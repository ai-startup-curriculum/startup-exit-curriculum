# exercise-04: SOX Readiness Scoping and ICFR Testing Drill

**Estimated effort:** 5 hours

## Objective

Stand up a defensible SOX 404 programme design for the frozen pre-IPO company you carried out of exercise-01 — from the Rule 12b-2 filer-status projection through the top-down risk-based scoping, control-matrix design, testing plan, deficiency-classification framework, remediation programme, integrated-audit coordination, sub-certification protocol, close-cadence readiness gate, and programme-resourcing decision. The deliverable is the packet you would walk into the audit committee — a scoping memo, a control matrix outline, a testing plan, a deficiency-triage worksheet, a remediation-tracking template, and a resourcing recommendation. A critical audit-committee chair, an engagement-partner from the PCAOB-registered auditor (see chapter 3 / exercise-03), and a Big Four SOX advisory partner should be able to read the packet and either sign off or challenge on specific and evidenced grounds.

> Reminder: this module is education, not legal / accounting / tax / audit advice. Every specific scoping, sample-size, and deficiency-classification decision on a live SOX programme is made with the PCAOB-registered auditor, a qualified SOX advisor, securities counsel, and the audit committee.

## Background

This exercise covers material from:

- [Chapter 4 — SOX 404 Internal-Control Programme Design and ICFR Testing](../04-sox-404-icfr-programme-design.md)

Do not re-teach chapter 4 in your deliverable — refer to it. In particular, the framework tour (Sarbanes-Oxley Sections 302 / 404(a) / 404(b) / 906 / 407, 18 U.S.C. §1350, Exchange Act Rules 13a-14(a) / 13a-15 / 15d-15, Reg S-K Item 308(a), PCAOB AS 2201, COSO 2013, the 2007 SEC Commission Guidance on Management's ICFR Assessment, and Rule 12b-2 filer-status definitions) is already installed; your job is to *apply* those to the frozen company.

Chapter 3 (PCAOB auditor engagement) and chapter 5 (EGC election) are load-bearing prerequisites: the integrated-audit coordination in Task 7 depends on the auditor you selected in exercise-03, and the 404(b) applicability analysis in Task 1 depends on the EGC-status projection from chapter 5.

**Boundary to `startup-finance-fundraising-curriculum` mod-111.** The ongoing-company finance-function build — month-end close design, controller / accounting-manager / staff-accountant staffing, account-reconciliation tooling, journal-entry workflow, treasury and tax operations, sub-ledger cadence — is owned by mod-111 and is *not* re-taught here. This module owns the SOX-readiness gate that sits on top of a functioning finance function: whether the close cadence, reconciliation discipline, and staffing bench can carry the control activities designed here. Task 9 handles the hand-off explicitly.

## Prerequisites

Carry the frozen pre-IPO company profile from exercise-01. Add the following SOX-specific fields at the top of your deliverable, frozen at the start of this exercise:

- Current close-cycle length (calendar days from period end to books closed / trial balance final): _____
- Current controller name / years public-company experience: _____
- Current CAO name (if separate) / years public-company experience: _____
- Current internal-audit staffing: FTE count _____; leader title _____; prior public-company experience _____
- Core financial ERP / GL system (NetSuite / SAP / Oracle EBS / Workday Financials / Dynamics / Intacct / other): _____
- Sub-ledger and revenue systems (Zuora / Stripe Billing / Salesforce Revenue Cloud / RevPro / homegrown): _____
- CRM / quoting / billing stack (Salesforce / HubSpot / Dynamics / CPQ tool / homegrown): _____
- HRIS and payroll (Workday HCM / ADP / Rippling / Gusto / other): _____
- Equity administration (Carta / Shareworks / Pulley / other): _____
- Consolidation / close-management tool (BlackLine / FloQast / OneStream / Oracle EPM / spreadsheets): _____
- Treasury / tax provision tooling (Kyriba / GTreasury / Corptax / OneSource / other): _____
- IT infrastructure vendor list (AWS / Azure / GCP / on-prem colo / SaaS enumeration for financially-significant apps): _____
- Current SOX advisor engaged (Big Four SOX advisory / specialist boutique / none): _____
- Planned first fiscal year subject to Section 404(a) management assessment (state fiscal year end and 10-K filing quarter): _____
- Projected public float at the second-fiscal-quarter measurement in each of the first 3 post-IPO fiscal years: Year 1 $_____; Year 2 $_____; Year 3 $_____
- Projected annual revenue in each of the first 3 post-IPO fiscal years: Year 1 $_____; Year 2 $_____; Year 3 $_____
- Multi-entity / multi-geography footprint: legal entities _____; countries of operation _____; material foreign statutory audits _____

## Tasks

### 1. Filer-status projection and 404(a) / 404(b) applicability calendar

Run the **Rule 12b-2** filer-status analysis for each of the first 3 post-IPO fiscal years. For each year produce a **non-accelerated / accelerated / large accelerated** call, cross-checked against **SRC** status under Item 10(f) of Reg S-K, using the projected second-fiscal-quarter public-float measurement date and the projected annual revenue.

- Map the 2020-amendment revenue-based SRC carve-out from Section 404(b) — where the intersection with accelerated-filer status leaves the company exempt from auditor attestation despite exceeding the $75M float bar.
- Overlay the EGC-status projection from chapter 5 (five-year anniversary, annual-revenue trigger, non-affiliate-common-equity trigger, and non-convertible-debt trigger) and mark the first fiscal year the company is *not* an EGC.
- Identify the specific first-10-K in which (a) Section 404(a) management assessment first applies under the SEC's initial-registration transition rule (typically the second post-IPO 10-K) and (b) Section 404(b) auditor attestation first applies given EGC status and filer-status. State the filing quarter and the fiscal year covered.
- State the practitioner posture the CFO should adopt: run the programme at 404(b) quality during the EGC / non-accelerated years so the transition year is not a scramble.

Produce a one-page calendar exhibit showing S-1 filing, first 10-K, first 404(a) 10-K, first 404(b) 10-K, and the EGC-status loss triggers overlaid.

### 2. Top-down risk-based scoping

Under the **2007 SEC Commission Guidance on Management's Report on Internal Control Over Financial Reporting** and **COSO 2013**, run the top-down risk-based scoping exercise.

- Set **planning materiality** (a specific percentage of pre-tax income or a specific audit-planning benchmark — state the benchmark and the percentage — with the specific dollar figure derived from the profile) and **tolerable-misstatement / performance-materiality** thresholds at the account level. Use general practitioner ranges rather than inventing statistics; flag <!-- needs-research: ... --> where you need auditor input to finalise.
- Identify **significant accounts and disclosures** from the projected pre-IPO trial balance against both quantitative and qualitative factors (complex judgement, related parties, misstatement history, regulator or investor attention).
- Map **in-scope significant processes**: revenue-to-cash, procure-to-pay, hire-to-retire (including payroll and stock-based-compensation), financial close and reporting, treasury, tax provision, and business combinations (if applicable to the frozen profile).
- Apply **materiality-by-location** for the multi-entity / multi-geography footprint — full-scope, specific-scope, and out-of-scope locations under a documented coverage rationale.
- Document **risks of material misstatement at the assertion level** for each significant account — existence / occurrence, completeness, accuracy, cutoff, classification, valuation, and rights and obligations — with the specific process and control point that addresses each.

### 3. Control matrix design (entity, ITGC, and process-level)

Design the **risk-and-control matrix (RACM)** across the three layers.

- **Entity-level controls (ELCs)** mapped to the five COSO components (control environment, risk assessment, information and communication, monitoring, control activities) and the 17 principles — tone at the top, audit-committee oversight, whistleblower programme, code of conduct, disclosure committee, internal audit, period-end financial-reporting review controls.
- **IT general controls (ITGCs)** across the four domains — change management, logical access provisioning / periodic access reviews / privileged access / segregation-of-duties, computer operations (job scheduling, backup, incident management), and system development and acquisition — for each in-scope financially-significant system named in the prerequisites.
- **Process-level controls** for each in-scope significant process from Task 2, classified as preventative vs. detective, manual vs. automated, and key vs. non-key.

For every control specify: control ID, control description, owner (name / title), frequency (daily / weekly / monthly / quarterly / annual), preventative-vs-detective, manual-vs-automated, assertion(s) addressed, testing approach (**inquiry / observation / inspection / re-performance** — inquiry alone is insufficient for a key control), planned **sample size** (frequency-scaled per AS 2201 guidance and audit-committee-approved practitioner convention — general ranges only; flag <!-- needs-research: ... --> for anything you would only settle with the auditor), and evidence-retention approach (system-generated log / signed workflow record / retained email / physical artefact) with the retention location.

### 4. Testing plan

Design the year-one testing plan running the two phases in sequence.

- **Design effectiveness (TOD).** Schedule a walk-through of each in-scope significant process end-to-end, tracing at least one live transaction through initiation, recording, and reporting, confirming control-design adequacy and documenting design gaps for remediation before TOE begins.
- **Operating effectiveness (TOE).** Schedule sample selection and testing across an interim phase (typically Q2–Q3) and a year-end roll-forward, sized to give year-end coverage under the frequency-scaled sample-size convention documented in Task 3.
- Show the calendar overlay: fiscal-year quarters, close cadence, walk-through dates, interim testing window, roll-forward testing window, audit-committee reporting checkpoints, and the auditor's own AS 2201 walk-through and testing schedule (from Task 7).

Include a section describing how in-year process changes (ERP go-live, new revenue-model launch, acquisition integration) trigger walk-through refreshes, RACM updates, and re-scoping — a change-log discipline the auditor will expect to see.

### 5. Deficiency taxonomy and mock triage

Draft the **deficiency-classification framework** distinguishing **control deficiency / significant deficiency / material weakness** under **PCAOB AS 2201** and parallel SEC guidance. Show the two-gate analysis — **likelihood** (reasonable possibility of misstatement — more-than-remote drawing from ASC 450 terminology) and **magnitude** (maximum potential misstatement, quantitative plus qualitative) — with an explicit treatment of compensating controls, interaction with other deficiencies, and **aggregation** across the same account, assertion, or process.

Perform a **mock triage on 6–10 hypothetical deficiencies** drawn from the recurring first-year post-IPO weakness patterns from chapter 4 (ASC 606 revenue judgements without documented management-review, ASC 718 stock-based-compensation grant-date fair-value modelling, ASC 740 income-tax provision and deferred-tax-asset valuation, ASC 805 business-combination accounting relying on undocumented national-office consultations, user-access provisioning and segregation-of-duties failures, close-critical spreadsheet end-user-computing gaps). For each hypothetical:

- State the observed deficiency in one sentence.
- Apply the likelihood gate with a specific rationale.
- Apply the magnitude gate with a specific rationale (quantitative and qualitative).
- Consider compensating controls and aggregation.
- Land a specific classification (control deficiency / significant deficiency / material weakness) with the defence you would present to the audit committee and the engagement partner.

### 6. Remediation programme

For each significant deficiency and material weakness identified in Task 5 (and any you anticipate uncovering in the dry run in Task 4), build the remediation record.

- Owner (name / title) and executive sponsor (typically the CFO or the process-owning SVP).
- Remediation plan (redesign the control, deploy new tooling, adjust process, hire, train).
- Target remediation date, with the calendar overlay showing whether the remediated control has **sufficient time** operating between deployment and the fiscal-year-end assessment date to demonstrate operating effectiveness (facts-and-circumstances — typically at least a quarter for monthly controls, several months for quarterly controls).
- Re-testing plan (fresh sample from the post-remediation period sized to the frequency convention).
- Audit-committee reporting cadence — quarterly at minimum, more frequent for open material weaknesses.
- Disclosure implications — the S-1 risk-factor drafting hook (chapter 2), the 10-K Item 9A material-weakness disclosure under Item 308, the Item 308(c) material-change disclosure in the quarter of remediation, and the 8-K Item 4.02 trigger if remediation coincides with a restatement.

### 7. Coordination with the AS 2201 integrated audit

Design the coordination workstream with the PCAOB-registered auditor selected in exercise-03.

- Sequence the auditor's AS 2201 walk-throughs alongside management's walk-throughs so the auditor is not re-walking a process a month after management. Identify the specific processes where joint walk-throughs are practical vs. where independent walk-throughs are required.
- Plan **work-paper access** — the tool (Workiva / AuditBoard / the auditor's platform), the review cadence, the response-to-inquiry cadence, and the escalation path when the auditor's request queue exceeds management's response bandwidth.
- Plan the **shared-testing (management's-work-reliance) discussion** with the engagement partner under AS 2201's provisions on the auditor's use of the work of others, framed by an audit-committee-approved integrated-audit approach.
- Set the deficiency-classification alignment cadence — monthly through interim, weekly through year-end — so a disagreement surfaces before the reporting deadline rather than at the sign-off meeting.
- Set the expected incremental integrated-audit fee band relative to the base financial-statement audit (general practitioner range; flag <!-- needs-research: ... --> if you would only fix the number with the engagement partner during scoping).

### 8. Sub-certification protocol for the Section 302 / 906 certifications

Design the **disclosure-committee workflow** that feeds the CEO / CFO certifications on every 10-K and 10-Q.

- **Section 302 civil certification** filed as Exhibit 31.1 (CEO) and Exhibit 31.2 (CFO) under **Exchange Act Rule 13a-14(a)** — the prescribed text on report review, absence of untrue statements or material omissions, fair presentation, disclosure-controls-and-ICFR responsibility, disclosure to the auditor and audit committee of significant deficiencies and material weaknesses, and disclosure of any material change in ICFR.
- **Section 906 criminal certification** filed as Exhibit 32.1 (CEO) and Exhibit 32.2 (CFO) under **18 U.S.C. §1350** — the fair-presentation and full-compliance certification with the criminal-penalty regime.
- **Process-owner sub-certification questionnaires** — the specific questionnaire distributed to significant-account and significant-process owners each quarter, covering completeness of disclosures, awareness of any known control deficiencies, changes since the prior period, and known or suspected fraud involving management or ICFR-role employees.
- **Disclosure-committee charter and minutes template** — membership (CFO chair, GC, controller, CAO, VP-IR, VP-Legal, head of internal audit), meeting cadence (at least once per quarter ahead of each 10-Q / 10-K filing), agenda template, documented conclusion memo funnelling up to the CEO / CFO certification.

### 9. Close-cadence acceleration readiness gate

Diagnose whether the current close cycle in calendar days from the prerequisites can support the accelerated-filer **40-day 10-Q** and **60-day (large accelerated) or 75-day (accelerated) 10-K** deadlines under Rule 12b-2 filer-status projections from Task 1. Practitioner benchmark for a public company is WD5 or better with mature companies operating at WD3.

- Identify the specific close-acceleration workstreams that report to **`startup-finance-fundraising-curriculum` mod-111** for execution (account-reconciliation automation via BlackLine / FloQast / native ERP tooling, journal-entry approval-workflow discipline, cutoff discipline for AR / AP / accruals, month-end sub-ledger closes, intercompany eliminations, foreign-subsidiary submission-package cadence). Do not re-teach mod-111 — refer.
- State the **readiness gate this module owns**: the sign-off criteria the SOX programme lead and CFO apply to determine that the close cadence, reconciliation discipline, and evidence-generation cadence can carry the SOX control activities within the reporting window. Include the specific dry-run test — running a full mock close-plus-SOX-testing cycle in the fiscal year before the first 404(a) year — and the pass criteria.
- Flag the specific close-cycle scenarios (e.g., a 15-business-day close, a spreadsheet-heavy consolidation, a per-entry manual revenue-adjustment control) that make the readiness gate a hard fail and cannot be papered over with a control-design workaround.

### 10. Programme resourcing and audit-committee approval memo

Draft the resourcing plan and the memo requesting audit-committee approval.

- **Internal audit hire plan** — internal-audit leader (typically titled VP / Director of Internal Audit or Head of SOX / Internal Controls), staff level, reporting line (dotted line to the audit-committee chair per Rule 10A-3 and chapter 7 governance framework), and hiring timeline against the Task 1 SOX calendar.
- **External SOX advisory scope** — engage a Big Four SOX advisory practice (or a specialist boutique such as Protiviti, RSM, BDO) for scoping support, RACM build, testing execution, and deficiency-remediation. Distinguish clearly from the PCAOB-registered auditor's engagement (independence rules under **Regulation S-X Article 2** prohibit the auditor from doing management's ICFR work).
- **Technology tooling** — the SOX-management / GRC platform decision (Workiva, AuditBoard, SAP GRC, or an alternative) with a specific selection rationale tied to the ERP and consolidation stack from the prerequisites.
- **Audit-committee approval memo** — a 3–5-page memo to the audit-committee chair covering the filer-status calendar (Task 1), scoping (Task 2), control-matrix design and testing plan (Tasks 3–4), deficiency framework (Task 5), remediation and integrated-audit coordination (Tasks 6–7), sub-certification protocol (Task 8), close-cadence readiness gate (Task 9), and this resourcing plan, with the specific approval requested and the reporting cadence back to the audit committee.

## Starter guidance

Four anti-patterns to avoid:

- **The document-every-control programme.** A RACM with 400 controls in year one is a RACM the auditor will insist you cut back to the top-down risk-based scope. The 2007 SEC Commission Guidance is explicit: scope is driven from significant accounts through relevant assertions to specific controls, not from a comprehensive walk of every process in the company. Over-scoping burns first-year testing capacity, produces false deficiency signals, and gives the audit committee the wrong picture of programme maturity.
- **The inquiry-and-observation TOE.** A key control tested by inquiry alone (asking the owner whether the control operated) is not evidence under AS 2201, and an auditor will not rely on it. Every key control needs at least inspection and — for automated controls, reconciliations, and high-risk processes — re-performance.
- **The material-weakness-is-what-the-auditor-says-it-is posture.** Management performs the classification first, documents the two-gate analysis in the assessment memo, and defends it to the auditor. A programme that outsources the classification call to the auditor forfeits the opportunity to build the evidence trail the audit committee needs to defend the ICFR conclusion.
- **The close-then-SOX sequencing.** A finance function that runs the close first and the SOX controls afterward — as a compliance check on the completed close — cannot execute within the accelerated-filer window. SOX controls must operate concurrently with the close, with the SOX evidence generated as a by-product of the close activity, not layered on top.

## Acceptance criteria

You can demonstrate that:

- The filer-status calendar names the specific first 10-K subject to Section 404(a) and Section 404(b) for the frozen company, with the EGC-status trigger overlay.
- The scoping memo lists significant accounts, in-scope processes, and materiality-by-location decisions with specific quantitative and qualitative rationale (no "all revenue" placeholders).
- The RACM outline covers ELCs mapped to the 17 COSO principles, ITGCs across the four domains for each named financially-significant system, and process-level controls for each in-scope significant process, with owner / frequency / testing approach / sample size / evidence for every control.
- The testing plan schedules walk-throughs, interim TOE, and year-end roll-forward against a specific fiscal calendar with audit-committee reporting checkpoints.
- The deficiency-classification framework applies the two-gate test and aggregation explicitly; the 6–10 mock-triage examples land specific classifications with defended rationale.
- The remediation programme names an owner, target date, re-testing plan, and disclosure implication for every significant deficiency and material weakness.
- The integrated-audit coordination plan sequences the auditor's walk-throughs and TOE against management's, and sets the deficiency-alignment cadence.
- The sub-certification protocol produces the disclosure-committee minutes and process-owner questionnaires that give the CEO / CFO a reasonable basis for the Section 302 and Section 906 certifications on every 10-K and 10-Q.
- The close-cadence readiness gate names the sign-off criteria this module owns and hands the close-acceleration workstream to mod-111 without re-teaching it.
- The audit-committee approval memo carries a specific resourcing recommendation the reader can accept or specifically disagree with.

## Reflection

Add a short reflection (½ page):

1. Which specific significant account or process produced the largest scoping call — the one where you had to defend inclusion or exclusion to a hypothetical engagement partner — and what evidence would tip the call the other way?
2. If the frozen company's projected public float crosses the $75M accelerated-filer threshold a year earlier than planned, which specific programme elements accelerate and which are already in place under the "run at 404(b) quality throughout EGC status" posture?
3. Which specific hypothetical deficiency in the Task 5 triage was the hardest to classify, and what specific piece of evidence (compensating control, aggregation, magnitude quantification) would move it up or down a tier?

## Stretch goals

- **Two-scenario alternate scoping memo.** Draft an alternate scoping memo assuming the company completes a material business combination (ASC 805) during the fiscal year subject to the first 404(a) assessment. Which specific in-scope processes and controls change, and what specific integration-risk controls does the acquisition trigger under Item 308 disclosure implications?
- **Restatement war-game.** War-game a hypothetical revenue-recognition error surfaced in the fiscal Q3 close of the first 404(a) year. Sequence the specific 8-K Item 4.02 disclosure, the audit-committee investigation charter, the ICFR-effect analysis, the 10-Q amendment (or 10-K/A), and the 302 / 906 re-certifications — with a specific timeline from discovery to disclosure.
- **Dry-run readout deck.** Build the 6–8-slide dry-run readout deck the SOX programme lead presents to the audit committee at the end of the year *before* the first 404(a) year, covering testing coverage, deficiencies identified and remediated, deficiencies open, integrated-audit-coordination status, close-cadence readiness gate status, and the specific go / hold recommendation on the first 404(a) assessment.
- **Big-Four SOX advisor RFP.** Draft the specific RFP you would issue to three Big Four SOX advisory practices (excluding the practice affiliated with your PCAOB-registered auditor under Reg S-X Article 2 independence rules), covering scope, staffing, tooling, deliverables, fee structure, and the specific selection criteria the audit committee will apply.
