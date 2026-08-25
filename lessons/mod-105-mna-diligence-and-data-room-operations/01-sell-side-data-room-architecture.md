# Sell-Side Data-Room Architecture — Workstreams, Naming, Redaction, Clean Teams, VDRs

## Why this matters

Between the moment an LOI is signed and the moment a definitive agreement is executed, roughly ninety percent of what the acquirer *learns* about the target flows through the data room. The bidder's counsel, financial advisor, tax advisor, Q of E provider, technology diligence firm, HR and comp consultant, R&W underwriter and its counsel, environmental consultant (where applicable), and antitrust counsel all read from the same virtual-data-room instance, and each one of them writes findings back into memos that either preserve the LOI price or drive a re-trade. A data room that is disorganised, incomplete, over-redacted, missing the customer-contract corpus, or so badly named that a diligence attorney cannot locate the third-amendment-to-the-2019-services-agreement in under sixty seconds is not a neutral inconvenience — it is a material transaction-execution risk. Deals slip because the data room slips. Exclusivity lapses because the buyer's counsel cannot find the corporate records. Price re-trades happen because the buyer's Q of E provider concludes from the absence of a monthly close package that the target lacks a controllership function. In more than one practitioner case study, the target discovered a signed but unamended change-of-control provision in a top-customer contract *while the buyer's counsel was reading it in the data room* — a "we already know" would have been far cheaper than the "we just found this" that surfaced.

Practitioner discipline treats the data room as a *product* the target builds and ships to the buyer. It has an architecture (the fifteen-workstream taxonomy below), a naming standard (so anything can be located in seconds), a redaction protocol (so PII / PCI / customer-confidential information is scrubbed without destroying diligence value), a clean-team protocol (so competitively sensitive information can be reviewed without exposing it to the target's competitor if the buyer happens to be one), and an operations layer (VDR platform selection, access-controls-and-audit-log configuration, invitation choreography, watermarking, revocation drills). This chapter installs that architecture end-to-end.

Two vocabulary points before we start. First, the term *data room* today almost universally means a *virtual data room* (VDR) hosted by a specialist vendor (Intralinks, Datasite, Firmex, Ansarada, DealRoom) — the physical-data-room era of the 1990s and early 2000s is over except for a small number of highly-regulated or classified transactions. Second, *sell-side data room* refers to the room the target builds and populates for buyer-side diligence review; *buy-side data room* (sometimes) refers to the room a buyer maintains for its own diligence-workstream deliverables. This chapter is about the sell-side data room.

## The fifteen-workstream taxonomy

A modern venture-backed private-company data room is organised around fifteen top-level workstreams. The exact list varies by sector (a biotech target adds regulatory-and-clinical; a hardware target adds supply-chain-and-manufacturing; a fintech target adds licensed-entities-and-BSA-AML), but the fifteen below are the modal set for a growth-stage AI-and-SaaS company acquisition. Each workstream is a top-level folder in the VDR and has a workstream owner on the sell-side team.

### 01 — Corporate

The corporate-existence-and-authority record. Enables the buyer to verify that the entity exists, is properly organised, has the authority to sell itself, and has clean governance actions on the change of control.

- Certificate of incorporation (and every amendment and restatement, in the order they were filed).
- Bylaws (current, and each amendment).
- Certificate of good standing from every jurisdiction the target is qualified in.
- Board minutes and consents from company formation forward, chronologically ordered.
- Stockholder minutes and consents.
- Committee charters and committee minutes (audit, compensation, and any other standing or ad-hoc committee).
- The current, fully-diluted capitalisation table with sources (each round's board and stockholder consents; each individual option grant's board consent).
- Stock-purchase agreements (SPAs), stockholder agreements, investor-rights agreements, voting agreements, ROFR / co-sale agreements, and drag-along agreements for every financing round.
- Equity-incentive-plan documents, plan amendments, and Rule 701 aggregate-value-limit tracking documentation.
- Convertible notes and SAFE agreements outstanding, with their conversion mechanics.
- Warrants outstanding (venture-debt warrants, commercial-partner warrants, warrant coverage on lines of credit).
- Foreign-subsidiary corporate documents (each subsidiary's local incorporation documents, board records, and local counsel opinions on the target's authority to sell).

### 02 — Financial

The historical financial record that anchors the quality-of-earnings analysis (chapter 2).

- Audited (or reviewed) financial statements for the last three fiscal years, with the auditor's opinion letter.
- Trial balances, month-end close packages, and monthly management-reporting decks for the last twenty-four to thirty-six months.
- Chart of accounts.
- Revenue-recognition policy documentation and ASC 606 posture memo.
- Deferred-revenue rollforwards.
- Accounts-receivable ageing and bad-debt-reserve methodology.
- Accounts-payable ageing.
- Fixed-asset register and depreciation schedules.
- Capitalised-software-development-cost schedules (ASC 350-40).
- Lease accounting under ASC 842 (right-of-use asset and lease-liability schedules).
- Historical budget-to-actual variance analyses.
- The current-year budget and any subsequent forecast updates.
- The three-statement operating model (used for the target's own board reporting; buyers will build their own).
- Historical bank statements and reconciliations.
- Cash-management and treasury-policy documentation.

### 03 — Tax

The tax-position record that anchors the tax-diligence workstream (chapter 4).

- Federal, state, and local (foreign, provincial, national) tax returns for the last three to five years.
- Tax-provision workpapers.
- Uncertain-tax-position (ASC 740) memos.
- Sales-tax nexus study (or its absence — an absence is itself a diligence finding).
- Use-tax accruals and any prior sales-tax audit correspondence.
- R&D tax-credit studies and supporting workpapers (IRC §41).
- IRC §174 R&D-capitalisation posture memo (the post-TCJA capitalisation regime).
- International-tax posture: transfer-pricing studies, intercompany agreements, Country-by-Country Reporting (BEPS Action 13), Pillar Two posture (if applicable at scale).
- Section 382 NOL-limitation analysis (the ownership-change study anchoring NOL usability post-transaction).
- IRC §280G analysis (see mod-103 chapter 6).
- IRC §1202 QSBS analysis at the founder and early-employee level (see mod-103 chapter 8).
- Tax-authority correspondence and any open examinations, protests, or appeals.
- Property-tax records for real property and heavy-personal-property.

### 04 — Commercial

The commercial-contract-and-revenue-record apparatus. Anchors the commercial and customer diligence workstreams.

- Master service agreements, subscription agreements, purchase orders, and statements of work for the top-twenty customers (or a customer-concentration-defensible cut — top-N by ARR, plus every customer above 1% concentration).
- Order forms and amendments for the customer set covered above.
- Change-of-control review of each material customer contract (see below on how to prepare this).
- Reseller agreements, channel-partner agreements, and referral-partner agreements.
- Distribution agreements and OEM agreements.
- Vendor and supplier agreements (top by spend).
- Software-licence-in agreements (the target's inbound-licence stack — SaaS vendors, on-prem software).
- Cloud-infrastructure agreements (AWS EA, GCP commitments, Azure enterprise agreements, Cloudflare, Fastly, CDN, DNS providers).
- AI-vendor agreements (foundation-model API contracts, embedding-model contracts, vector-database contracts, AI-observability contracts — see chapter 7).
- Data-processing agreements (DPAs) as data controller and as data processor.
- Business-associate agreements (HIPAA BAAs, if applicable).
- Marketing partnerships and co-marketing agreements.

### 05 — Product and Technology

The product-and-technology architecture record that anchors the technology-diligence workstream (chapter 4).

- Architecture diagrams (system-level, service-level, data-flow diagrams).
- Technology-stack inventory (languages, frameworks, databases, message queues, cache layers, observability, deployment tooling).
- Repository inventory (source-code repositories with brief descriptions; access is granted separately, typically not into the VDR itself — see below on source-code-review protocol).
- Product roadmap for the next twelve to eighteen months.
- Uptime / SLA history for the last twenty-four months.
- Incident-response records and post-mortems for material incidents.
- Software development lifecycle documentation (change-management, code-review, release-approval, deployment gating).
- Third-party-technology-dependency map (SaaS vendors, open-source components, foundation-model APIs, embedded devices).
- AI / ML architecture (models in production, model lifecycle documentation, evaluation harnesses — the detailed AI-model diligence lives in chapter 7).

### 06 — Intellectual Property

The intellectual-property record. Anchors the IP-diligence workstream and the IP reps in the definitive agreement (mod-104 chapter 4).

- Registered IP: issued patents, pending patent applications, registered trademarks, pending trademark applications, registered copyrights, domain names.
- Prosecution files and correspondence for material patent applications.
- Assignment-of-inventions agreements (from founders, employees, contractors, and any third-party contributors — the IP-chain-of-title record).
- Third-party IP licences in (licences the target holds).
- Third-party IP licences out (licences the target grants).
- Freedom-to-operate analyses (if any have been performed).
- IP-related litigation, cease-and-desist correspondence, or DMCA notices.
- Open-source-software licence inventory (with attribution, copyleft posture, and any material findings — the depth is in chapter 7).
- Trade-secret protection posture (which materials are marked confidential, which are shared, employee training on trade-secret handling).

### 07 — HR and Compensation

The workforce-and-comp record. Anchors the HR / comp diligence workstream, the 280G analysis, the retention-pool sizing, and the MIP design (mod-103 chapter 6 and mod-110).

- Employee census with role, level, department, hire date, comp (base / bonus / equity), and location.
- Job descriptions for material roles.
- Offer letters and employment agreements (executive-level fully executed; standard-form for the non-executive population).
- Executive-level: change-of-control agreements, single-vs-double-trigger acceleration provisions, non-competes, non-solicits, confidentiality agreements.
- The equity-incentive plan (with the current-outstanding grant schedule pulled from a system of record like Carta or Pulley).
- Bonus plans (annual, project-based, sales-commission plans).
- Benefits plans (health, dental, vision, 401(k), and any deferred-comp arrangements — the last are diligence-hot because IRC §409A applies).
- HR-policy handbook and code of conduct.
- Contractor / consultant agreements (a distinct category — misclassification risk is a diligence finding in its own right).
- Immigration file (H-1B, L-1, TN, O-1 employees and any pending green-card sponsorships).
- Historical layoffs, terminations, and severance arrangements.
- Prior EEOC or state-employment-agency correspondence.
- Compensation-benchmarking studies (Radford, Pave, Option Impact — the compensation-market-data providers).
- Diversity, equity, and inclusion policies and any EEO-1 filings.
- Union / works-council situation (typically none in a US-headquartered venture target, but material in European subsidiaries).

### 08 — Real Estate

The real-property-and-lease record.

- The office-lease inventory (each active lease with landlord, term, rent, expansion / termination options, personal-guarantee status).
- Any owned real property (rare in venture-backed companies but material when present).
- Sublease arrangements as sublessor and as sublessee.
- Environmental site assessments (Phase I ESA on any leased or owned property that could carry contamination exposure).

### 09 — Privacy

The data-privacy posture record. Anchors the privacy-diligence workstream.

- Privacy notice (as published on the target's website, and internal-facing privacy policies).
- Data-processing-inventory (data-map, records-of-processing-activity under GDPR Article 30, CCPA data-inventory).
- Data-processing agreements (DPAs) as data controller and as data processor (also indexed under Commercial for the reciprocal reason).
- Sub-processor list with the notification / consent mechanic.
- International-data-transfer mechanisms (Standard Contractual Clauses under the 2021 EU Commission Decision, Data Privacy Framework certification for EU-US transfers, UK IDTA / addendum, cross-border assessment memos).
- Data-subject-request (access, deletion, portability) handling records.
- Historical privacy incidents and breach-notification records (if any).
- Privacy-by-design and Data Protection Impact Assessment (DPIA / PIA) records for higher-risk processing activities.
- Cookie-consent-management posture (the ePrivacy Directive / GDPR overlap).
- Children's-data posture (COPPA, if applicable).
- State-level privacy-law posture (CCPA / CPRA, Virginia CDPA, Colorado CPA, Connecticut CTDPA, Utah CPA, Texas TDPSA, and the wave of successor state laws).

### 10 — Security

The security-posture record. Anchors the security-diligence workstream (see chapter 4 on the boundary to `security-learning`).

- SOC 2 Type II report (most recent, plus prior periods if available).
- ISO 27001 certificate and Statement of Applicability (if the target is certified).
- HIPAA-security-rule attestation (if applicable).
- PCI-DSS AoC (if applicable — most SaaS targets outsource card-processing to Stripe / Adyen and are only SAQ-A-eligible; larger targets doing their own processing carry a full AoC).
- FedRAMP ATO or JAB P-ATO (if applicable to public-sector-oriented targets).
- Penetration-test reports for the last twenty-four to thirty-six months and remediation evidence.
- Vulnerability-scanning cadence documentation.
- Incident-response plan and post-mortems for any material security incident.
- Security-awareness training records.
- Access-management and privileged-access-management (PAM) posture documentation.
- Encryption posture (at-rest, in-transit, key-management).
- Third-party security assessments (of vendors), vendor-risk-management (VRM) programme documentation.
- Cyber-insurance policy declarations.
- Breach-notification history (if any).

The depth of what a security-diligence firm actually inspects here is in `security-learning`; this module is about *what belongs in the data room* and how it is presented for review.

### 11 — AI and Model

The AI-and-model diligence record. Anchors chapter 7 and a growing wedge of definitive-agreement rep language.

- Model inventory (each model in production, its purpose, its inputs, its outputs).
- Model-card documentation for each model (the Google model-cards template or a comparable structure — intended use, training-data description, evaluation results, known limitations, ethical considerations).
- Training-data provenance (source, licence terms, opt-out records, PII scrubbing, data-lineage documentation).
- Foundation-model-usage inventory (which foundation models the target calls, with what usage-policy posture — OpenAI, Anthropic, Google, AWS Bedrock, Azure OpenAI, self-hosted open-weight models).
- Evaluation harnesses and evaluation results (accuracy, hallucination-rate, safety-eval, jailbreak-resistance, red-team findings).
- AI-vendor contracts (indexed here and under Commercial).
- GPAI-provider posture (EU AI Act Article 53 obligations, systemic-risk assessment under Article 55 if applicable — see chapter 7).
- NIST AI RMF alignment documentation (if the target has adopted the framework — see chapter 7).
- Copyright-training-data litigation exposure (any subpoenas or claims received, any known use of protected-material-in-training).
- AI-content-labelling posture (C2PA, watermarking, synthetic-media disclosure).

The AI-safety-technical depth is in `chief-ai-officer-learning` and `head-of-ai-governance-learning`; this module is about what belongs in the data room and how the deal team reads it.

### 12 — Open Source

The open-source-licence-obligation record. Distinguished from the security-of-OSS-dependencies posture (which lives under Security) — this workstream is about *licence obligations* the target has taken on by embedding OSS code.

- SBOM (software bill of materials) — the machine-readable inventory of every OSS component in the target's shipped code and infrastructure. SPDX or CycloneDX format preferred.
- Licence-obligation summary by licence type (permissive: MIT / BSD / Apache-2.0; weak-copyleft: LGPL / MPL; strong-copyleft: GPLv2 / GPLv3 / AGPLv3; other: SSPL / BSL / Elastic License 2.0 / Commons Clause; unlicenced / licence-unknown).
- Attribution notices and NOTICE files as shipped to customers.
- Copyleft-exposure memo (any AGPLv3 code in a customer-facing service is the canonical diligence finding — see chapter 7).
- Patent-grant-back inventory (Apache-2.0 §3, GPLv3 §11 — patents the target has implicitly granted to the OSS community).
- OSS-contribution-policy documentation (rules the target's engineers follow when contributing back to OSS projects).
- CLA / DCO records for any OSS projects the target maintains.

### 13 — Environmental, Health, Safety

Typically light for a pure-software venture target; material for hardware, industrial-technology, biotech, and any target with meaningful physical operations.

- EPA / OSHA correspondence and audit records.
- Hazardous-materials inventory and disposal records.
- Environmental-permit inventory.
- Phase I / Phase II ESAs on any property with contamination potential.
- Product-take-back and e-waste programmes.
- Sustainability / ESG reporting (SASB, GRI, ISSB, or CSRD-scoped disclosures, if applicable — the CSRD is a diligence-hot topic for European-subsidiary-carrying targets).

### 14 — Regulatory and Compliance

The regulatory-posture record. Sector-specific — the taxonomy below is the modal AI-and-SaaS set.

- Sector-specific licences and registrations (BitLicense for a NY-crypto-adjacent target; money-transmitter licences for a fintech; FINRA registration for a broker-dealer-adjacent target; state professional-services licences).
- Export-control posture (EAR, ITAR classification of the product; encryption-classification requests; export-licence history — a diligence finding for any target selling into sanctioned or partially-sanctioned jurisdictions).
- Sanctions-compliance posture (OFAC screening, PEP screening, customer- and vendor-KYC).
- Anti-corruption / anti-bribery programme (FCPA, UK Bribery Act, French Sapin II if applicable) — code of conduct, third-party-due-diligence records, training records, whistleblower channel documentation.
- Anti-money-laundering programme (BSA / AML if applicable — most software targets are out of scope; fintech and crypto-adjacent targets are in scope).
- Consumer-protection regulator posture (FTC posture, state AG posture, EU consumer-protection posture).
- AI-specific regulatory posture (EU AI Act — see chapter 7; state-level algorithmic-decision-making laws; NYC Local Law 144 for automated employment-decision tools).

### 15 — Litigation and Disputes

The claims record.

- Active litigation matters (each with a case-summary memo — parties, allegations, procedural posture, exposure estimate, insurance-coverage posture).
- Threatened litigation (cease-and-desist letters, demand letters, pre-litigation correspondence with material claim potential).
- Settled matters over the last five to seven years (typically only material settlements — the "every parking ticket" cut is not useful; a defensible threshold is any settlement over some dollar figure, plus every settlement with an ongoing obligation regardless of dollar figure).
- Regulatory investigations and enforcement matters (SEC, FTC, DOJ, state AG, sector regulators).
- Employment-related claims (EEOC, state agencies, wage-and-hour class or PAGA representative actions, sexual-harassment claims).
- IP disputes (indexed here and under IP).
- Customer disputes and material warranty / SLA disputes.

## File-naming discipline

The single largest ergonomic difference between a good and a bad data room is the file-naming standard. A file named `services_agreement_v3_FINAL_signed_2019.pdf` is a data-room failure — the reader has to open it to know which customer it belongs to, whether it is executed, and how it fits into the amendment stack. A file named `04-01-CUSTOMER_Acme-Corp-MSA-2019-04-15-EXEC-with-amendments-A1-A2-A3.pdf` tells the reader everything they need without opening it.

A workable naming standard is:

`<workstream>-<subfolder>-<entity/counterparty>-<document-type>-<date>-<status>-<amendment-tag>.<ext>`

Where:

- `<workstream>` is the two-digit workstream number (01–15 above).
- `<subfolder>` is the two-digit subfolder number within the workstream (e.g., under 01-Corporate, 01-Formation-Documents, 02-Board-Minutes, 03-Cap-Table, ...).
- `<entity/counterparty>` is the target-side entity (for corporate documents) or the counterparty (for contracts) — hyphens, no spaces, no punctuation.
- `<document-type>` is a short standardised label — `MSA`, `SOW`, `OrderForm`, `Amendment`, `DPA`, `Consent`, `Minutes`, `Charter`, `Bylaws`, `Return`, `Study`.
- `<date>` is the ISO-8601 date of the document (`YYYY-MM-DD`).
- `<status>` is one of `DRAFT`, `EXEC` (fully executed), `PARTIAL` (partially signed), `UNSIGNED`.
- `<amendment-tag>` is optional; used for amendment chains (`with-A1`, `with-A1-A2`, `A3-only`).
- `<ext>` is the file extension.

Examples:

- `01-01-DELAWARE-Certificate-of-Incorporation-2018-03-12-EXEC.pdf`
- `01-02-BOARD-Consent-Series-B-Financing-2022-05-04-EXEC.pdf`
- `04-01-CUSTOMER_Acme-Corp-MSA-2019-04-15-EXEC-with-A1-A2-A3.pdf`
- `04-01-CUSTOMER_Acme-Corp-Amendment-A3-2023-09-01-EXEC.pdf`
- `07-04-EXEC_Smith-J-Change-of-Control-Agreement-2021-06-01-EXEC.pdf`
- `10-03-SOC2-Type-II-Report-2024-Q4-EXEC.pdf`

Two operating rules make this stick:

1. **The workstream owner enforces naming on ingestion.** Every file uploaded to the workstream folder is renamed to the standard before it is filed. This is boring, mechanical work; assign it explicitly rather than assuming it will happen.
2. **Nothing gets uploaded that isn't the final artefact.** The data room is not the target's shared drive. Drafts, working copies, "final v3", and "reviewed by legal" versions stay out. If the buyer needs the drafting history of a specific document, the workstream owner produces it on request; the room shows only the operative version.

A related discipline: the folder-hierarchy structure should be readable by a diligence attorney *without a guide*. A buyer's corporate counsel arriving at the room should be able to navigate to "certificate of incorporation as most recently amended and restated" in under thirty seconds. This means:

- The workstream folders are numbered (01-Corporate, 02-Financial, ...) so the sort order matches the taxonomy.
- Subfolders within a workstream are numbered and named descriptively (`01-Formation-Documents`, `02-Board-Minutes-and-Consents`, `03-Cap-Table-and-Equity-Records`, `04-Financing-Round-Documents`, `05-Foreign-Subsidiary-Records`).
- Amendment chains sit inside the parent document's folder, not scattered across a "miscellaneous amendments" pile.
- Every folder has an `00-INDEX.md` (or `00-README.txt`) written by the workstream owner that names the sub-folders and calls out anything nonobvious (a missing document with a reason, an amendment where the original is lost, a document whose relevance is not immediately obvious).

## Redaction discipline

Some documents in the data room contain information the target cannot expose in raw form. The categories:

- **PII of individuals not party to the transaction** — employee census with SSNs, customer-user PII in a contract exhibit, HR-file scans with driver's-licence numbers. Redact the identifiers; keep the analytically-relevant fields (title, comp, hire date, department).
- **Payment card information (PCI)** — full PAN, CVV, cardholder name paired with PAN. Redact in every instance; nothing about the diligence answer requires seeing raw card data.
- **Protected health information (PHI)** — patient identifiers combined with health information. Redact per HIPAA de-identification standards.
- **Customer-confidential information** — pricing terms specific to a named customer that the target's contract requires be kept confidential, customer trade secrets shared under NDA, customer-side security posture disclosed under NDA. Handle in one of three ways: (a) redact the customer name and other identifying information (leave the analytically-relevant deal-terms); (b) obtain the customer's consent to disclosure (rarely feasible in the compressed diligence timeframe); (c) move the document into the clean-team subroom (see below).
- **Contract terms the disclosure of which would trigger a most-favoured-nation clause with another customer** — same treatment options as customer-confidential.
- **Trade secrets that would be lost by disclosure to a competitor** — the source code, the training-data corpus, specific model weights, the proprietary customer-scoring algorithm, the pricing algorithm. Clean-team subroom is the default; source code has its own special protocol below.

The redaction operating discipline:

1. **Use redaction software, not black rectangles in a PDF editor.** Software like Adobe Acrobat Pro's redaction tool or Foxit's redaction tool actually removes the underlying text; a black rectangle overlay can be moved or deleted to reveal the text underneath. The buyer's counsel will test at least a sample of your redactions.
2. **Redact at the workstream-owner level, not at the document-upload level.** The redaction call is *analytical* — what information is confidential, what is analytically necessary. Junior staff running the upload should not be making that call.
3. **Log every redaction.** The workstream owner keeps a redaction log for every document — file name, reason for redaction, redacted fields, sign-off. This log serves two purposes: it lets the buyer's counsel ask "why is this redacted" and get an answer, and it lets the target's counsel demonstrate a defensible redaction process if a downstream dispute questions what was disclosed.
4. **Never redact the analytically-load-bearing text.** Redaction is for identifiers, not for terms the buyer needs to evaluate. Redacting the price in a customer contract because it is "sensitive" is a diligence-blocker; redact the customer name if concentration disclosure is a concern.
5. **Prefer clean-team review over over-redaction.** If a document is analytically important and redaction would destroy its diligence value, put it in the clean-team subroom rather than shipping a hollowed-out version.

## Clean-team protocols

The clean-team protocol handles a specific transaction risk: the buyer is (or might be) a competitor of the target, and specific information in the data room — pricing to the target's largest customer, customer-list detail, unit-cost data, the sales pipeline — would give the buyer a competitive advantage in the market if the deal does not close. Sharing that information in the general data room exposes the target to competitive harm if exclusivity lapses and the buyer walks. The clean-team protocol solves this by segregating the sensitive information into a subroom with restricted access and by binding the reviewers with a clean-team agreement that legally separates their diligence review from their day-to-day operational role.

The mechanics:

- **A clean-team agreement is executed by the target, the buyer, and each individual clean-team member** (not the buyer's institutional counterparts — each individual reviewer). The clean-team member acknowledges the sensitive-information categorisation, agrees not to disclose the clean-team-designated information to any person on the buyer's operational team, and typically agrees to a stand-down period (they will not participate in specified competitive activities against the target for a defined period after transaction-non-consummation). This is enforced by the individual's employer (the buyer or its advisor) and by the individual personally.
- **The clean-team subroom is a separately-permissioned VDR folder** — access is granted only to named clean-team members; every access is logged; downloads are blocked or watermarked; screenshots on the review device are typically restricted (the VDR platform can enforce dynamic watermarks that put the reviewer's name on every rendered page). The clean-team subroom is invisible to unfrocked reviewers — it does not show up in their folder tree.
- **Clean-team members are typically outside advisors** (financial, legal, or consulting) rather than the buyer's internal employees, precisely because the outside advisor has no operational role to bring the information back to. When the buyer's internal team needs to read specific clean-team information, the outside advisor writes a *cleansed memo* — the analysis and conclusions without the raw sensitive data — that is then shared into the general data room. The buyer's internal team reads the cleansed memo, not the raw data.
- **The clean-team is typically stood up on Day 1 of buyer-side diligence**, not two weeks in. Standing it up later means the buyer has already asked for the clean-team-designated information and is annoyed that they cannot see it; standing it up on Day 1 lets the buyer's counsel identify the clean-team members and execute the agreement before the underlying documents are needed.

What typically goes into the clean-team subroom:

- Customer-by-customer pricing detail beyond a top-level average or a bucketed distribution.
- Customer-list detail below a defensible aggregation (e.g., top-20 customers by name and ARR is the general room; the full 5,000-customer list with pricing is clean team).
- Sales-pipeline detail at the account level (bucketed pipeline by stage in the general room; account-by-account pipeline in the clean team).
- Unit-cost data by product / SKU.
- Detailed engineering roadmap beyond the twelve-to-eighteen-month product roadmap in the general room.
- Detailed cost of specific vendor arrangements where the vendor is also selling to the buyer under different pricing.

A well-run clean team is one of the most-important, least-visible sell-side disciplines in a competitor-bidder transaction. Neglect it and the target hands the buyer a competitive-intelligence report; over-do it and the deal team cannot get through diligence because everything is behind the clean-team wall.

## Source-code review — its own protocol

Source code is a special case. Buyers routinely ask for source-code review as part of technology diligence, and equally routinely the target cannot upload the full source-code repository to a VDR (it is too large, the security implications of a leak are too severe, and repository access is typically instrumented for the target's own engineering team). The modal practitioner protocol:

1. **Source code stays in the target's version-control system** (GitHub Enterprise, GitLab, Bitbucket). The buyer's diligence team is granted a read-only, time-boxed, IP-restricted account with audit logging enabled. Downloads are blocked. Watermarking is typically not feasible in a raw code checkout but the version-control system's audit log captures every read.
2. **The scope of code review is negotiated up-front** — full-repository read vs. specific-package read vs. read via a diligence-firm intermediary (Anchore, Fossa, and larger tech-diligence firms like Crosslake, West Monroe, and RSM's technology-diligence practice all offer intermediary code-review services). An intermediary review is preferred when the buyer's own engineering team is a competitive risk; the intermediary produces a memo describing what they found without ever exposing the code to the buyer's engineers.
3. **A source-code scan is preferable to a source-code read for most diligence questions.** The typical questions are: (a) is there GPL-family or AGPL code in the shipped codebase (OSS-licence-scan tools: Black Duck, Snyk Open Source, Fossa, Scancode); (b) are there known-vulnerable OSS components (SCA tools: Snyk, Mend, Sonatype); (c) is there hardcoded credential material or secrets (secret-scanning tools: GitGuardian, TruffleHog); (d) is there evidence of prior developer-account compromise or a supply-chain-attack fingerprint. Most of these are answerable by scan output rather than by a human code read.
4. **The source-code-review environment expires at close or on transaction termination.** The workstream owner keeps the calendar and revokes access as soon as the review window closes or the exclusivity period lapses.

## VDR vendor selection

Five VDR vendors dominate practitioner deal work in the private-company M&A market. Each has strengths that match specific deal profiles.

- **Intralinks** — the oldest of the modern VDR vendors. Strong in cross-border and complex-financing deal work. Deep permissioning granularity. The most mature audit-log and reporting functionality. Preferred by tier-1 investment banks and top corporate-law firms. Pricing is on the higher end; per-project or per-page-served, or by data-storage-and-user tier.
- **Datasite** (formerly Merrill Corporation's Datasite Diligence) — the volume leader in North American M&A. Strong AI-powered redaction and document-classification tooling that materially accelerates room setup. Preferred by mid-market bankers and larger corporate-law firms. Pricing similar to Intralinks; per-project.
- **Firmex** — the mid-market workhorse. Simple pricing, straightforward permissioning, less bespoke functionality than Intralinks or Datasite. Preferred for straightforward diligence pipelines without exotic clean-team or bespoke redaction requirements. Pricing typically flat monthly or annual per-room.
- **Ansarada** — differentiator is the deal-management functionality wrapped around the VDR (diligence-checklist scaffolding, Q&A workflow with SLA tracking, "deal readiness" scoring). Preferred by sellers running a bilateral or limited-round process who want workflow tooling on top of the pure document repository. Pricing per-project.
- **DealRoom** — the newer entrant with modern UX and integrated project-management tooling (pipeline management, diligence tracker, integration planning). Preferred by corp-dev teams running many small transactions or by financial sponsors managing a portfolio of processes. Pricing per-user-per-month or per-project.

Ancillary vendors sometimes seen: **iDeals** (European emphasis), **Onehub** (light-weight document rooms for very small transactions or non-transactional B2B document exchange), **ShareVault** (life-sciences focus), **Digify** (single-document tracking rather than full-room capability).

Selection matrix — a workable rubric:

| Question | If yes, favours |
|---|---|
| Cross-border or complex-financing deal? | Intralinks |
| Buyer set may include competitors requiring aggressive clean-team? | Intralinks or Datasite |
| Volume of documents > 10,000? | Datasite or Intralinks (redaction tooling matters at volume) |
| Wanting deal-workflow + Q&A tooling wrapped around the room? | Ansarada or DealRoom |
| Mid-market transaction with straightforward diligence? | Firmex |
| Tight budget or first-time seller? | Firmex |
| Life-sciences with FDA / EMA-workflow expectations? | ShareVault |
| Buyer-side corp-dev running many concurrent processes? | DealRoom |

Two selection anti-patterns to avoid: choosing based on cost alone (a $20K pricing difference between vendors is trivial against a $10M+ transaction expense line and $250K+ in banker and legal fees); and choosing based on the banker's preference without verifying the banker's specific team has run recent deals on the platform. Ask the banker who ran the last three deals on the platform and reach out to their prior sellers for a five-minute reference call.

## Access controls, invitation choreography, and audit logs

A well-configured VDR is a mechanic on top of a well-designed process. The specific configuration decisions:

**Role-based permission tiers.** Typical roles: Deal Team (target's exec and counsel, full access); Sell-Side Advisors (banker, target's counsel, target's Q of E provider, full access); Buyer Deal Team (buyer's corp-dev, buyer's counsel, buyer's Q of E provider); Buyer Specialist Advisors (buyer's tax counsel, tech-diligence firm, HR consultant, R&W underwriter — access to specific workstreams only); Clean Team (named individuals, clean-team subroom only). Each role has a permission profile that controls read, download, print, and view-in-browser access at the workstream and folder level.

**Invitation choreography.** Buyer-side reviewers are invited into the room in tranches — the buyer's corp-dev on Day 0, buyer's counsel on Day 1, specialist advisors as their workstreams start. Each invitation confirms the individual's institutional affiliation, their permissions tier, and the NDA / clean-team-agreement they are bound by. Every invitation is logged.

**Watermarking.** Every document rendered in the VDR viewer carries a dynamic watermark with the reviewer's name, institutional affiliation, and timestamp. This is not a technical barrier to information exfiltration — a determined bad actor with a phone camera can defeat it — but it does raise the psychological cost of screen-capture and it provides post-hoc forensic detail if a leaked document surfaces publicly.

**Download and print controls.** For most workstreams, downloads are permitted with watermarking; for high-sensitivity workstreams (customer contracts, HR files, source-code-review outputs), download is blocked and view is limited to in-browser rendering. Print is typically blocked for high-sensitivity workstreams.

**Audit-log configuration.** Every access, every view, every download, every search query is logged. The workstream owner reviews the audit log weekly during the diligence period — patterns of a specific reviewer downloading every customer contract in a single session, or a reviewer accessing the room from an unexpected geography, or a spike in access after a public event, all warrant follow-up. The audit log is also the evidence the target's counsel will produce in a downstream dispute over whether a specific piece of information was disclosed.

**Revocation drills.** The workstream owner runs a scheduled revocation drill — quarterly during a long process, or at every major milestone. Access for individuals who have departed from the buyer's deal team, advisors whose engagement has ended, or clean-team members whose review is complete is revoked promptly. When exclusivity lapses (deal died, deal signed and closed, deal moved into integration), all buyer-side access is revoked within a defined window (typically 30 days), and the target retains a full-copy archive of what was disclosed for record-keeping.

## The data room as a *process*, not an artefact

The single most common mistake in sell-side data-room construction is treating it as a one-time build. In practice, a well-run data room is a *rolling* process:

- **Pre-marketing build** — the target and its counsel spend three to nine months before a formal process constructing the base room. This is where most of the workstream population happens.
- **Pre-LOI room** — a subset of the room is opened to the round-1 bidders at CIM delivery (typically corporate, financial, high-level commercial, high-level product-and-technology — enough for a bidder to price at IOI stage but not enough to give away competitive intelligence).
- **Post-LOI room** — the full room is opened to the winning bidder at LOI signing, subject to permissioning tiers.
- **Rolling updates** — during the diligence period, the workstream owners continuously update the room — new customer contracts signed, new board consents, month-end close package for each new month, updated cap table after any option grants or exercises. The buyer's counsel expects the room to be current as of last-close-plus-one-week.
- **Signing snapshot** — at definitive-agreement signing, a snapshot of the room is taken and preserved. This snapshot is the reference for disclosure-schedule verification and, in a downstream indemnification dispute, the evidence of what was disclosed vs. what the seller failed to disclose.

## Summary

The sell-side data room is a *product* the target builds and ships to the buyer. Its architecture is the fifteen-workstream taxonomy (corporate / financial / tax / commercial / product-and-technology / IP / HR-and-comp / real-estate / privacy / security / AI-and-model / open-source / environmental / regulatory / litigation). Its ergonomics are a strict file-naming standard and a folder hierarchy a diligence attorney can navigate without a guide. Its confidentiality guardrails are a redaction protocol for PII / PCI / PHI / customer-confidential information and a clean-team subroom for competitively sensitive information. Its operations are a VDR platform (Intralinks / Datasite / Firmex / Ansarada / DealRoom) with role-based permissioning, watermarking, download-and-print controls, weekly audit-log review, and periodic revocation drills. The room is a rolling process, not a one-time build — the pre-marketing setup, the round-1-bidder subset, the winning-bidder full open, the continuous updates through the diligence period, and the signing snapshot are all distinct choreography stages.

Chapter 2 turns to the sell-side quality-of-earnings — the pre-transaction QoE that pre-empts the buyer's finding and speeds diligence. Chapter 3 covers the sell-side diligence-response management discipline that runs alongside the room throughout the diligence period.
