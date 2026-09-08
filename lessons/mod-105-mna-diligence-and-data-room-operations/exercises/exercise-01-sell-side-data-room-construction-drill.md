# exercise-01: Sell-side data room construction drill

**Estimated effort:** 4–5 hours

## Objective

Construct a full sell-side data-room architecture for a specific hypothetical target — a fifteen-workstream folder hierarchy, a file-naming standard, a redaction protocol, a clean-team subroom design, and a defended VDR-vendor selection. The finished artefact is a data-room-plan document (8–14 pages) plus a folder-hierarchy tree (in the format a workstream owner could hand to an intern to build out in a live VDR) that the target's General Counsel or M&A counsel would put in front of the target's CFO and board for sign-off before pre-marketing launches.

You should end the exercise able to defend every workstream boundary (why does this document sit in Corporate vs. IP?), every naming choice (why ISO-8601 dates, why prefix numbering), every redaction call (why redact this field, why not that one), every clean-team designation, and the specific VDR-vendor selection against a comparison of two rejected alternatives.

## Background

This exercise covers material from:

- [Chapter 1 — Sell-Side Data-Room Architecture — Workstreams, Naming, Redaction, Clean Teams, VDRs](../01-sell-side-data-room-architecture.md) — the fifteen-workstream taxonomy, file-naming standard, folder-hierarchy discipline, redaction protocols, clean-team protocols, VDR-vendor selection matrix, and access-controls / audit-log configuration.

Supporting references:

- [mod-103](../../mod-103-mna-deal-structures-and-consideration/README.md) for the deal-structure inputs that shape which workstreams matter most.
- [mod-104 chapter 4](../../mod-104-loi-negotiation-and-definitive-agreements/04-definitive-agreement-architecture-and-reps-layering.md) for the reps-and-disclosure-schedule architecture the room ultimately serves.

## Prerequisites

- The hypothetical transaction one-pager from mod-101 and mod-102. If you have not carried a target through those modules, freeze a plausible growth-stage AI-and-SaaS profile before starting — sector, ARR ($15M–$100M range), employee headcount (75–400), geography (US-primary with at most one meaningful foreign subsidiary), cap-table shape (founder + 3–5 institutional investors + employee pool).
- Familiarity with one or more VDR platforms — Intralinks, Datasite, Firmex, Ansarada, DealRoom. Vendor websites publish product documentation; free trials or demo requests give the interactive view.
- Access to the current-cycle ABA Private Target Deal Points Study or SRS Acquiom market report for anchor data on data-room-related deal timing.
- If possible, a conversation with an M&A associate or paralegal who has recently built a sell-side data room — the operational realities of file ingestion and naming enforcement are hard to appreciate without them.

## Tasks

### 1. Set the target-facts baseline

Write a 1-page target-facts baseline covering:

- Target legal name, jurisdiction, sector, product summary.
- Financial profile — ARR, growth, gross margin, cash burn, cash position.
- Employee headcount by function (engineering, product, sales, customer success, marketing, G&A) and geography.
- Cap-table shape at a summary level.
- Foreign-subsidiary presence.
- Sector-specific regulatory footprint (HIPAA, SOC 2, ISO 27001, FedRAMP, PCI, GDPR/CCPA, sector regulators).
- AI posture (foundation-model dependency, in-house model training, in-scope for EU AI Act GPAI or high-risk classifications).
- Any known transactional-history complications (prior acquisition, prior aborted transaction, prior secondary transactions, restatement, historical outages, litigation).
- Bidder profile — strategic vs. financial, direct competitor risk (drives clean-team scoping).

### 2. Build the fifteen-workstream folder hierarchy

Produce the complete folder hierarchy for the target's data room. Format is a numbered outline:

```
01-Corporate/
  01-Formation-Documents/
    ...
  02-Board-Minutes-and-Consents/
    ...
```

Cover all fifteen workstreams from chapter 1 (corporate, financial, tax, commercial, product-and-technology, IP, HR-and-comp, real-estate, privacy, security, AI-and-model, open-source, environmental, regulatory, litigation). For each workstream, produce at least two levels of hierarchy (workstream → subfolder → sub-subfolder where useful). Where the target's sector affects the hierarchy (e.g., a fintech target's Regulatory workstream needs licensed-entity subfolders; a biotech target's Regulatory workstream needs clinical-and-FDA), note the sector-specific adaptation.

For each workstream, name the workstream owner (a specific role: GC, CFO, CTO, CISO, CPO, etc.), the backup owner, and any specialist support (Q of E provider, tax advisor, IP counsel).

### 3. Author the file-naming standard

Adopt (with any modifications you can defend) the chapter 1 naming standard:

`<workstream>-<subfolder>-<entity/counterparty>-<document-type>-<date>-<status>-<amendment-tag>.<ext>`

Produce:

- A one-page naming-standard document that a workstream owner or paralegal could apply mechanically to any incoming file. Include the standardised document-type labels (MSA, SOW, OrderForm, Amendment, DPA, Consent, Minutes, Charter, Bylaws, Return, Study, etc.).
- 10 concrete example filenames across at least six workstreams, including at least one amendment-chain example, at least one dated-status example (DRAFT vs. EXEC), and at least one clean-team-restricted example.
- The re-naming-on-ingestion rule and the "no drafts in the room" rule from chapter 1.

### 4. Draft the redaction protocol

Produce a redaction protocol document (2–3 pages) covering:

- The categories of information to redact (PII of non-transaction individuals, PCI, PHI, customer-confidential terms, MFN-triggering terms, competitively-sensitive trade secrets).
- The categories of information NOT to redact (analytically-load-bearing terms — price, term, change-of-control provisions, exclusivity clauses, indemnity terms).
- The tools to use (Adobe Acrobat Pro redaction, Foxit, or equivalent — with the explicit prohibition on black-rectangle overlays).
- The workstream-owner-level (not upload-level) redaction call.
- The redaction log — the fields to capture per redacted file (filename, date, redactor, redacted field, reason, sign-off).
- The clean-team-vs-redaction decision rule (when to redact, when to move to clean team).

### 5. Design the clean-team subroom

For the specific transaction, design the clean-team subroom:

- The clean-team-agreement essentials — parties (target, buyer, individual reviewer), key covenants (non-disclosure, stand-down period, no-use-in-competitive-decisions).
- The subroom access controls — who is in, who is out, invitation choreography.
- What documents go into the clean team (customer-by-customer pricing, full customer list, account-level pipeline, unit-cost data, engineering-roadmap detail, vendor-cost detail).
- The cleansed-memo workflow — how the buyer's internal team gets analytical output without raw data.
- The Day-1 stand-up plan (not Day-14).
- If the buyer is a competitor, the additional aggressiveness (more items in the clean team, more restrictive stand-down).

### 6. Design the source-code-review protocol

Produce a source-code-review protocol document covering:

- Where the code lives during review (target's GitHub Enterprise / GitLab / Bitbucket with time-boxed, read-only, IP-restricted access), NOT the VDR.
- The scope-of-review options (full-repository / specific-package / intermediary-firm review) and the criteria for each.
- The scan-vs-read decision (Black Duck / Snyk / Fossa / TruffleHog / GitGuardian for automated scan; human review for architectural or IP-critical questions).
- The audit-log expectation.
- The expire-on-close or expire-on-termination access-revocation rule.

### 7. Select the VDR vendor

Select a specific VDR vendor for the transaction from among Intralinks, Datasite, Firmex, Ansarada, DealRoom, iDeals, ShareVault. Defend the choice against at least two rejected alternatives.

Cover:

- Deal size and complexity fit.
- Cross-border / financing complexity if any.
- Buyer-competitor risk (drives permissioning and clean-team aggressiveness).
- Q&A-workflow requirements (Ansarada / DealRoom advantage) vs. pure-document-repository needs (Firmex advantage).
- Sector fit (ShareVault for life-sciences; Datasite for volume; Intralinks for cross-border).
- Budget considerations, but with the caveat from chapter 1 that $20K vendor-price deltas are trivial against total transaction cost.

### 8. Configure the access-controls and audit-log posture

Produce the VDR configuration plan:

- The role-based permission tiers (Deal Team, Sell-Side Advisors, Buyer Deal Team, Buyer Specialist Advisors, Clean Team) with the specific read/download/print/print-to-PDF/view-in-browser permission profile per tier per workstream.
- The invitation choreography — who gets invited in which tranche (Day 0, Day 1, week-1, on-demand).
- The watermarking configuration (dynamic reviewer-name-and-timestamp watermarks on every page).
- The download and print controls per workstream (typically open for standard workstreams; blocked for high-sensitivity customer contracts, HR files, source-code outputs).
- The audit-log-review cadence (weekly) and the alert triggers (bulk-download patterns, off-hours access, unexpected-geography access, post-public-event spikes).
- The revocation drill schedule and the exclusivity-lapse / deal-close revocation windows.

### 9. Author the data-room rolling-process plan

Chapter 1 makes the "room as process, not artefact" point. Produce a rolling-process plan:

- Pre-marketing build — the 3-to-9-month window before formal process launch, with a specific milestone plan (which workstreams populate first, gating dependencies, who signs off on readiness).
- Pre-LOI room — the round-1-bidder subset that opens at CIM delivery. Which workstreams, at what depth.
- Post-LOI full room — the winning-bidder full open at LOI signing, subject to permissioning tiers.
- Rolling updates — the discipline that keeps the room current-to-last-close-plus-one-week during diligence.
- Signing snapshot — the preserved-copy-at-signing that anchors disclosure-schedule verification and any downstream indemnity dispute.

### 10. Draft the executive summary

Write a 1-page executive summary that would sit at the front of the data-room plan for CFO / GC / board review. Cover:

- Transaction overview (target, expected bidder profile, timeline).
- Workstream architecture summary.
- VDR-vendor selection with headline cost.
- Sensitivity treatment (redaction, clean team, source-code protocol).
- Key risks addressed (competitor bidder, customer-concentration confidentiality, source-code leak, pre-close information exfiltration).
- Timeline to readiness.

## Starter guidance

Common data-room construction errors to avoid:

- **Under-populating the "small" workstreams.** Real Estate, Environmental, and Regulatory are often the first workstreams to be treated as "we don't really have anything here." That is often wrong — a lease is a lease; a Phase I might not be needed but should be actively noted as not-needed rather than absent-with-no-explanation; sector-specific regulatory exposures the target has forgotten about surface in diligence questions.
- **Naming standard without enforcement.** A published naming standard that nobody enforces produces the mixed-naming mess it was meant to prevent. Assign the workstream owner explicitly and audit weekly.
- **Redaction as caution.** Redacting more than the protocol requires reads as concealment and slows diligence. Redact what the protocol calls for, not more.
- **Clean team as afterthought.** Standing up the clean team on Day 14 means the buyer has already asked for the clean-team-designated information and been told "no" — friction the Day-1 stand-up avoids.
- **VDR selection by banker's default.** Ask the banker who ran the last three deals on the platform and reach out to a prior seller for a reference call. The banker's platform-of-record may or may not fit your specific transaction profile.
- **Audit-log configured but never reviewed.** An audit log that is turned on but never reviewed is telemetry without action. Weekly review by the workstream owner is what makes it useful.
- **Assuming the room is done at LOI-signing.** The room continues to update through diligence; the failure mode is a room whose last update was 45 days ago while the buyer's counsel is checking for last-close month-end reporting.

## Acceptance criteria

You can demonstrate that:

- Target-facts baseline is written and includes sector-specific regulatory footprint plus bidder profile.
- Fifteen-workstream folder hierarchy is produced with at least two levels of depth per workstream and workstream-owner assignment per workstream.
- File-naming standard is documented with at least 10 concrete example filenames.
- Redaction protocol distinguishes redact-vs-do-not-redact categories, names the redaction tooling, and documents the redaction-log fields.
- Clean-team subroom is designed with agreement essentials, access controls, in-scope documents, and cleansed-memo workflow.
- Source-code-review protocol names the access channel (target's VCS, not VDR), scope options, scan-vs-read decision, and access-expiration mechanism.
- VDR vendor is selected with a defence against at least two rejected alternatives.
- Access-controls and audit-log configuration is planned with role-based tiers, invitation choreography, watermarking, download/print controls, and audit-log review cadence.
- Rolling-process plan covers pre-marketing, pre-LOI, post-LOI, rolling updates, and signing snapshot.
- Executive summary is drafted at 1-page depth suitable for CFO / GC / board review.

## Reflection

Add a short reflection:

1. Which single workstream absorbed the largest fraction of your design effort, and what does that tell you about where the target's diligence exposure concentrates?
2. If the winning bidder turned out to be a direct competitor, which specific documents would you move from the general room to the clean team, and why?
3. What is the single naming-standard exception you would defend if a workstream owner pushed back on the standard's rigidity?
4. If your VDR selection turned out to be over-scoped (you selected Intralinks or Datasite for a small transaction), what is the incremental cost of the over-scope, and does the marginal-cost trade off cleanly against the incremental capability?

## Stretch goals

- **Live VDR demo.** Sign up for a free trial or demo of your selected VDR vendor and build a scaffold of the folder hierarchy inside the actual platform. Note the operational realities that differ from your plan.
- **Naming-standard automation.** Write a short script (Python, bash, or spreadsheet formula) that generates a compliant filename from a set of metadata inputs. Automating the standard is a real-life ergonomic improvement.
- **Redaction-tool proof.** Redact a sample document using both Adobe Acrobat Pro's redaction tool and a naive black-rectangle overlay. Demonstrate that the black rectangle can be defeated by copy-and-paste while the redaction cannot.
- **Clean-team-agreement drafting.** Draft the full clean-team agreement (typically 4–8 pages) for the specific individual reviewer scenario, including the stand-down period, the specific-competitive-activities restrictions, and the enforcement mechanism.
- **Sector variant.** Rebuild the folder hierarchy for a target in a different sector (biotech, fintech, hardware, or industrial). Note the workstream additions and adaptations.
- **Comparative VDR feature matrix.** Build a feature-comparison matrix across five VDR vendors on ten specific dimensions (permissioning granularity, redaction tooling, Q&A workflow, audit-log detail, mobile access, on-premise option, pricing model, sector fit, integrations, watermarking capability). Use this to defend a data-driven selection.
