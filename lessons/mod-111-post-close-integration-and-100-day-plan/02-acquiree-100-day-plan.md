# The Acquired-Company First-100-Day Plan — Day-1 → Day-30 → Day-90 → Day-100

## Why this matters

The first 100 days after close is when the acquired company either becomes an operationally-legible part of the acquirer's ongoing-business envelope, or drifts into a purgatory state where it is neither the standalone company it used to be nor the integrated business the deal thesis promised. The specific determinant of which outcome you get is not the sophistication of the deal thesis or the calibre of the acquirer's leadership — it is *whether the plan-of-record for the first 100 days is specific, dated, owned, and executed*. The PMI canon (Sirower, McKinsey, BCG, Bain, and the Big-Four PMI groups) is consistent on this: the deals that stand up a specific 100-day plan with dated milestones and named owners for each hit a materially higher fraction of their day-100 targets than deals that run on general "we'll integrate as we go" intent — the compounding effect over 12 months is the difference between a deal that realises its thesis and one that quietly does not.

The 100 days is *not* the full integration. Some workstreams (product-portfolio consolidation, brand transition, deep engineering-org merge) extend over multiple quarters or years. The 100-day plan is the *first operational spine* — the milestones that must be true by day 100 for the deeper integration to have a runway, and the day-100 review that produces the explicit go / no-go decision on deeper integration. It is intentionally short and intentionally over-specified — a plan-of-record that is too general is not a plan.

This chapter installs the day-1, day-30, day-90, and day-100 milestones that anchor most 100-day plans, and the specific pattern for the day-100 go / no-go review. The specific milestones below are typical for a mid-size ($20M–$200M ARR) private-target acquisition by a larger strategic — a specific tuck-in, a specific PE take-private, or a specific mega-cap-buying-a-mid-cap will shift the emphasis of specific milestones but the overall structure is stable across deal sizes.

> Reminder: this module is education, not legal / tax / accounting / employment / systems-integration advice. Every specific milestone below engages specific counsel and specific vendors — payroll providers, benefits brokers, IT-consolidation vendors, identity-provider consultants, controller-and-audit teams — whose specific requirements shape the day-1 execution. Follow the counsel-and-vendor-imposed regime; the plan below is the operational discipline that sits underneath it.

## Day-1 readiness checklist — the "employees show up to a working company on Monday" bar

**Day 1** is the first business day after closing. The bar the day-1 plan clears is: *every acquired-company employee shows up on Monday morning and is able to work.* That means: they can log in, they get paid, they know who their manager is, they know which town-hall to attend, they know what benefits apply to them, they know what has changed and what has not. The day-1 plan is not the day the deep integration decisions get made — it is the day the acquired-business's operational continuity is preserved *while the integration happens*.

The specific components:

### Payroll cutover

**The decision.** Does payroll run on the acquiree's existing payroll provider (Gusto, ADP, Rippling, TriNet, Paychex, Namely, a specific PEO) through the next pay period, or does it cut over to the acquirer's provider on day 1?

**The default answer.** In almost every case, payroll continues on the acquiree's existing provider for at least 30–90 days post-close and cuts over on a specific date with a specific true-up (typically at a pay-period boundary and typically after the acquirer's payroll team has completed the specific onboarding of the acquired-employee data). Cutting payroll over on day 1 without a specific parallel-run pattern is the single most common cause of specific day-1 payroll failures (missed paychecks, missed direct-deposit routing, missed tax-withholding elections) that turn into a specific retention crisis in the first pay period.

**The specific day-1 requirements.**

- The acquiree's payroll provider is contracted through the transition period. If the payroll contract includes an assignment-on-change-of-control clause that would terminate it on close, the acquirer's transition-services agreement (TSA) or a specific side-agreement provides for continued service.
- Every employee's specific employment status is confirmed by close — that the acquirer is the new employer of record (or that the acquiree remains the employer of record for a specific transition period), that specific work authorisations transfer, that specific state-and-local employment registrations are in place.
- Specific pay-period messaging goes to employees confirming the next scheduled payday and the specific mechanism by which they will be paid.
- A specific escalation contact is named for payroll issues — typically the acquiree's Head of People or a specific payroll administrator who has been retained through transition.

### Email and identity cutover

**The decision.** Does email transition on day 1 to the acquirer's domain (name@acquirer.com), or does the acquiree's domain (name@acquiree.com) persist through a specific transition window?

**The default answer.** Email addresses typically persist on the acquiree's domain through the transition window (often 90–180 days) with a specific redirect strategy — inbound mail to the acquiree domain is delivered to the new acquirer-domain mailbox, outbound mail is sent from either address at the employee's choice. Domain-transition on day 1 is expensive (customer-facing email addresses in flight, integrations with third-party SaaS that whitelist the acquiree's domain, personal networks that route to the acquiree's domain) and provides no immediate integration benefit.

**The specific day-1 identity requirements.**

- Every employee has a working credential to access the systems they need on day 1 — either the acquiree's existing IdP with continued access to acquiree systems, or a new acquirer-domain credential with access to a specific subset of acquirer systems required for day-1 work, or (most commonly) both in parallel through the transition.
- MFA is preserved — the employee's existing MFA tokens (Yubikeys, Authy, Google Authenticator entries) continue to work; new tokens are provisioned during the transition rather than on day 1.
- SSO into third-party SaaS is preserved — no third-party SaaS integrations that break on day 1 because a specific OAuth grant was tied to an acquiree-domain identity.
- Slack / Teams / video-conferencing continuity — employees can continue to communicate with each other and with customers on the tools they used pre-close.

The identity-cutover decision is one of the most consequential day-30 through day-90 decisions (see chapter 4); the day-1 bar is *no break in access*.

### Benefits transition

**The decision.** Do benefits (health, dental, vision, 401(k), disability, life, mental health, fertility, parental leave, etc.) transition on day 1 to the acquirer's plans, or do they continue on the acquiree's plans through a specific transition window?

**The default answer.** Benefits typically continue on the acquiree's plans through a specific transition window that aligns with the acquirer's plan-year start (typically January 1) or a specific mid-year transition date that gives the benefits-workstream time to enrol every employee in the acquirer's plans. The default is *no benefits-change on day 1* — benefits change is the single most-worried-about topic for the average employee, and messaging that "your benefits do not change until [specific date]" is a specific retention-through-benefits-stability lever.

**The specific day-1 requirements.**

- Every employee has continuous coverage on the acquiree's benefits plans through the transition. The plan documents are reviewed for change-of-control triggers; specific renewal or termination notifications are managed appropriately.
- A specific benefits-transition FAQ (drafted per chapter 2 of mod-110 pre-signing and finalised post-signing) is available on day 1 and answers: what benefits continue as-is through transition, what changes and when, what specific decisions the employee needs to make (typically: none on day 1), what open enrolment during transition looks like.
- A specific named contact — typically the acquiree's benefits administrator or a specific transition-team member — is available for benefits questions on day 1 with specific office-hours and a specific email inbox.
- 401(k) plan disposition is communicated (typically: plan continues in place through a specific decision-date, at which point it will either terminate with distribution, merge into the acquirer's plan, or continue as a separate plan under the acquirer).

### Org-chart publication

**The decision.** What is the day-1 org chart, and does it reflect the pre-close acquiree structure, the target integrated structure, or something in between?

**The default answer.** The day-1 org chart is *typically the pre-close acquiree structure with a specific reporting-line change at the top* — the acquiree CEO (if staying) reports to a specific acquirer-side executive; the acquiree's executive team continues to report to the acquiree CEO. Deeper org-restructuring (functional-integration, elimination of duplicate roles) is a day-90 or later decision.

**The specific day-1 requirements.**

- A specific one-page day-1 org chart is published to every acquired employee showing: their manager, their manager's manager, the acquirer-side executive sponsor, the acquiree-side executive sponsor, the integration lead, and named workstream leads.
- The chart is *specifically annotated* with what has changed (typically: the acquiree CEO's reporting line, integration-team roles) and what has not changed (typically: everything else).
- Named escalation contacts for the specific concerns of the first week are surfaced — HR for benefits and payroll, IT for access issues, integration lead for integration questions, executive sponsors for specific escalations.

### Town-hall calendar

**The specific day-1 requirement.** A specific calendar of the first-30-days communications events is published to every acquired employee at the day-1 all-hands. Typical contents:

- Day-1 all-hands (typically held at close-morning or first-Monday-post-close, joint with acquirer leadership per mod-110 chapter 2 handoff).
- Week-1 team-level all-hands (each function meets separately with its acquirer-side counterparts).
- Week-2 integration-planning all-hands (the IMO presents the 100-day plan-of-record to the acquired workforce).
- Week-3 through week-4 workstream-specific deep-dives (systems cutover plan, benefits transition plan, comp-and-leveling harmonisation timeline).
- Day-30 progress-check all-hands.
- Day-60 midpoint all-hands.
- Day-90 organisational-integration all-hands (typically where the comp-and-leveling changes are communicated, if the decision is at day 90 rather than deferred).
- Day-100 review all-hands.

The town-hall calendar is a specific retention signal — it demonstrates that the integration has a plan, that specific decisions will be communicated on specific dates, and that the acquired employees are not being left in ambiguity.

### Other day-1 checklist items

- **Physical-office continuity** — badges, desk assignments, parking access, mail delivery continue without interruption. If the acquirer is closing the acquiree's office, that decision is *not* announced on day 1 (unless already public); typical office-consolidation decisions are day-90 or later.
- **Corporate credit cards and expense system** — continue on the acquiree's system through transition; a specific expense-system cutover date is named.
- **Corporate travel** — continues under existing arrangements; a specific policy-alignment date is named.
- **Communications tools** — Slack / Teams / Zoom / Google Workspace / Microsoft 365 continue as-is on day 1; consolidation is a day-30-through-day-90 decision (see chapter 4).
- **Customer-facing systems** — CRM, support ticketing, product-usage-analytics continue as-is; consolidation is a day-90-and-later product-workstream decision.

## Day-30 systems-cutover milestones

**Day 30** is when the systems-and-financial-close infrastructure of the acquired business must be legible to the acquirer's finance and IT functions. Three specific milestones anchor the day-30 gate:

### Finance close in the acquirer's ledger

**The specific milestone.** The acquired business's month-1-post-close financials are closed in the acquirer's ledger — that is, the acquired-business's revenue, expense, headcount, and balance-sheet items are recorded in the acquirer's financial system in the acquirer's chart of accounts, closed on the acquirer's close calendar, and consolidatable into the acquirer's group financials.

**The specific work required.**

- **Chart-of-accounts mapping.** Every acquiree account is mapped to an acquirer account. Where the acquirer has account-taxonomy the acquiree does not (e.g., specific product-line revenue segmentation), a specific mapping decision is made about whether to backfit the acquiree's history or to segment only prospectively.
- **Ledger population.** The acquiree's transactional activity for the post-close period is entered into the acquirer's ledger — either through a batch upload from the acquiree's system, through a specific ETL pipeline, or through re-entry (typically for lower-volume acquisitions).
- **Sub-ledger reconciliation.** AR, AP, payroll, fixed-assets, and inventory sub-ledgers are reconciled against the acquirer's structures. This is the specific work where the acquirer's controllers spend most of their day-30 hours.
- **Revenue-recognition alignment.** The acquiree's revenue-recognition policies (ASC 606 / IFRS 15 application, contract-modification treatment, standalone-selling-price allocation) are reconciled with the acquirer's — differences that would produce different revenue-recognition timing under the acquirer's policies are identified and either aligned or explicitly disclosed as policy differences.
- **Purchase accounting.** Opening-balance-sheet fair-value adjustments (from the acquirer's purchase-price allocation / PPA work) are recorded — goodwill, intangible-asset value, inventory step-up, deferred-revenue haircut, contingent-consideration valuation. This is typically Big-Four-supported work that continues through the first 90 days but must have specific interim positions at day 30.
- **Intercompany-elimination setup.** If the acquired business will trade with the acquirer's other business units (product resale, service allocation, cost sharing), the intercompany-elimination framework is set up so consolidated financials are correct.

**The specific artefact.** A specific closed month-1 P&L and balance sheet for the acquired business in the acquirer's ledger, with a specific reconciliation to the acquiree's pre-close-basis close, signed off by the acquirer's controller and the acquiree's CFO or VP-Finance.

### HR system (HRIS) cutover

**The specific milestone.** Every acquired employee's specific employment record — identity, role, manager, comp, benefits election, work location, time-off balance, immigration status, direct-deposit routing — is in the acquirer's HRIS (Workday, Rippling, ADP Workforce Now, UKG, Namely, or the specific acquirer HRIS).

**The specific work required.**

- **Data migration.** Employee records from the acquiree's HRIS are exported, transformed, and loaded into the acquirer's HRIS with specific data-mapping decisions (job-title normalisation, level assignment, cost-centre coding, manager-relationships preserved).
- **Access provisioning.** Each employee is provisioned in the acquirer's HRIS with appropriate self-service access.
- **Time-off balance transition.** Accrued PTO, sick leave, vacation balances are carried over with specific decisions on unit conversion (if the acquiree's plan was in days and the acquirer's is in hours) and on how to handle any specific balance-caps.
- **Immigration-record preservation.** For employees on visas (H-1B, L-1, TN, O-1, and international equivalents), the specific work-authorisation record is preserved with a specific plan for successor-employer processing (which for H-1B and L-1 requires specific USCIS filings within a specific window — most commonly triggering a rolling schedule of amended-petition filings in the first 90 days post-close).
- **Manager-hierarchy population.** The manager relationships from the day-1 org chart are populated so specific approval workflows (time-off, expense, promotion, comp-change) route correctly.

The HRIS cutover is the specific pre-requisite for the day-90 comp-and-leveling harmonisation — without it, the acquirer's People team cannot run the comp analysis on the acquired employees.

### Security-perimeter integration

**The specific milestone.** The acquired business's security perimeter is measurably as-strong as the acquirer's baseline — meaning that specific security-tool coverage, specific identity-and-access-management posture, specific endpoint-security coverage, and specific data-classification posture is at parity or on a specific short-term path to parity.

**The specific work required.**

- **Identity federation.** The acquiree's identity provider (Okta, Azure AD, Google Workspace, or a specific homegrown) is federated with the acquirer's IdP so that specific access decisions can be centrally administered even before full consolidation.
- **Endpoint-management extension.** The acquirer's MDM (Jamf, Intune, Kandji, JumpCloud, or specific) is extended to acquired-employee laptops through a specific rollout — either by remote-enrolment or by scheduled laptop-refresh. Where the acquirer's endpoint-management is materially stricter than the acquiree's, a specific transition-support programme (help-desk, office-hours, guided-enrolment) is required to prevent day-30 employee disruption.
- **VPN / network-access integration.** Acquired employees are given access to the specific acquirer systems they need through the acquirer's network-access mechanism (VPN, ZTNA, direct access).
- **Data-classification survey.** A specific inventory of acquired-business data with sensitive classification (customer PII, employee data, source code, financial data) is completed with specific classification, storage-location, and access-control documentation.
- **Security-tool coverage.** The acquirer's specific security tools (EDR, DLP, SIEM, secrets-scanner, container-security, cloud-security-posture) are extended to acquired-business systems. Where the acquiree had different tools, specific decisions are made about consolidation vs. dual-run.
- **Incident-response integration.** The acquired business's incident-response process is integrated with the acquirer's — specific on-call handoffs, specific escalation paths, specific run-books for security incidents involving acquired-business systems.
- **Vulnerability-and-patch management alignment.** The acquiree's patch cadence is aligned with the acquirer's (or explicit deviation is documented with rationale).

Chapter 4 goes deeper on the strategic technology-and-systems integration choices; the day-30 milestone above is the *operational* security baseline that must be true regardless of the deeper strategic choices.

## Day-90 organisational-integration milestones

**Day 90** is when the organisational and people-side integration decisions land — the specific comp-and-leveling harmonisation, promotion-cycle alignment, and performance-management alignment that turns the acquired employees from *people paid on the acquiree's system* into *people paid on the acquirer's system in the acquirer's leveling framework*. These are the decisions that create the most day-90 discontent (see chapter 5) and require the most preparation.

### Comp-and-leveling harmonisation

**The specific milestone.** Every acquired employee is placed on the acquirer's leveling framework (e.g., L3 / L4 / L5 / L6 / L7, or IC1–IC7 / M1–M4, or the acquirer's specific banding) with a specific comp-package that is on the acquirer's comp bands for that level.

**The specific work required.**

- **Leveling calibration.** Each acquired role is mapped to the acquirer's leveling framework by the acquirer's Head of People, the acquirer-side executive of the function, and (critically) the acquiree-side manager who knows the specific person's specific work-level. Calibration sessions typically run for 2–3 weeks with all acquired employees reviewed.
- **Comp-band placement.** Once level is set, each employee's specific comp (base + variable + equity) is compared to the acquirer's comp-band for that level. Where the acquired-employee is above the band (a specific pattern for acquired-companies that were paying above-market to compete), a specific decision is made about above-band placement, red-circling (frozen comp until the band catches up), or specific step-down (rarely used and typically only with retention-package offset). Where the acquired employee is below the band, a specific merit adjustment brings them into band (this is a specific retention-through-fairness lever and is typically funded by a specific integration-comp reserve).
- **Equity harmonisation.** Acquired employees' equity treatment — how their pre-close equity (rolled equity, cash-outs, retention grants) interacts with the acquirer's ongoing-equity-programme (annual grants, promotion grants, milestone grants) — is specified. The specific pattern varies widely by deal structure (see mod-110 chapter 2 for the pre-close equity-treatment mechanics that this workstream picks up on).
- **Communication.** Each acquired employee receives a specific personalised communication naming their level, their band placement, their comp change (if any), their equity treatment, and their specific manager relationship. This is typically the most emotionally-charged single communication of the integration.

**The specific pattern to preserve day-90 morale.** The comp-and-leveling communication is designed with a specific principle: *no employee is made worse off in cash*. Where the acquirer's comp band is materially lower than what the acquired-employee is currently paid, the specific mitigation is a **red-circle** (comp is frozen until market catches up, no cash reduction) or a **retention supplement** (an additional cash retention paid over the integration window to bridge). The reason: the day-90 comp letter is the specific artefact that either preserves or destroys the retention thesis — an acquired employee who reads a cash-reduction letter typically resigns within 60 days, and the specific downstream retention cost of that resignation exceeds the specific saving of the band-alignment cut.

### Promotion-cycle alignment

**The specific milestone.** The acquired business's promotion cycle is aligned with the acquirer's — either integrated into the acquirer's specific annual or bi-annual cycle, or held in a specific parallel cycle for one iteration with a stated integration date.

**The specific work required.**

- **Alignment of promotion criteria.** The acquiree's promotion criteria are compared to the acquirer's; specific translation is done for where the criteria differ.
- **Pending-promotion honouring.** Acquired employees who were on specific promotion-tracks pre-close with specific manager-committed timing are honoured at that timing (or with specific negotiated adjustment) — the specific pattern of "your pre-close promotion is off because we haven't finished integrating" is a specific retention-loss trigger.
- **First combined-cycle timing.** The first combined promotion cycle is dated (typically the acquirer's next-scheduled cycle, or a specific mid-year off-cycle for the acquired business) so acquired managers can plan.

### Performance-management alignment

**The specific milestone.** Acquired employees are integrated into the acquirer's performance-management framework — the specific review cadence, the specific rating framework, the specific calibration process, the specific manager-employee 1:1 rhythm.

**The specific work required.**

- **Review-cycle alignment.** If the acquiree's review cycle is on a different rhythm than the acquirer's, a specific transition plan aligns them — typically with a specific abbreviated review at day 90 to establish baseline, then integration into the acquirer's next full cycle.
- **Manager-training on the acquirer's framework.** Acquired managers are trained on the acquirer's specific rating framework (e.g., "exceeds / meets / develops," or a specific numerical scale, or a specific narrative-based framework), specific calibration expectations, and specific documentation requirements.
- **Performance-related manager tools.** Acquired managers are given access to the acquirer's performance-management tooling (Workday reviews, Lattice, Culture Amp, or the specific acquirer platform).

## Day-100 review — the explicit go / no-go on deeper integration

**Day 100** is the *first structured review* of the integration and the specific gate at which deeper integration decisions get made or deferred. It is not the moment integration ends — most integrations extend materially beyond day 100 — but it is the moment the plan-of-record either graduates into the deeper integration or is explicitly re-planned.

**Who runs the day-100 review.** The two executive sponsors, the integration lead, and all workstream leads. Typically presented to the acquirer's CEO / senior leadership team, and to the acquirer's board (if the deal is board-material). The acquiree-side executive team and the acquired-workforce receive a specific tailored version of the review.

**What the review covers.**

- **Milestone completion status.** Which day-1, day-30, and day-90 milestones were hit; which were missed and by how much; which were re-scoped.
- **Deal-thesis realisation status.** Is the integration on track to realise the specific synergy story the deal was signed on? Revenue synergies, cost synergies, technology synergies, talent synergies — each with a specific status.
- **Retention status.** Actual acquired-employee headcount vs. plan; top-quartile retention vs. plan (see chapter 6); named departures vs. plan.
- **Customer and revenue status.** Top-N customer retention through integration; gross retention vs. plan; net retention vs. plan; new-business bookings vs. plan.
- **Financial status.** Integration-spend vs. budget; acquired-business P&L vs. plan; combined-business synergy realisation vs. plan.
- **Risk-and-issue status.** Highest-risk items on the RAID log; unresolved cross-workstream issues; specific escalations needed.

**The specific decisions the day-100 review makes.**

- **Deeper technology-and-systems integration.** Are the day-30 systems-cutover milestones stable enough to proceed with deeper integration (product-consolidation, engineering-org merge, data-migration)? Or does the systems-workstream need another 60 days of stabilisation before deeper integration is safe? (Chapter 4 depth.)
- **Deeper organisational integration.** Are the day-90 comp-and-leveling / performance-management milestones landed? Do the acquired-employee retention numbers justify pushing deeper into functional integration (reporting-line merges, duplicate-role eliminations), or does the org stay in its day-90 shape for another quarter?
- **Deeper brand integration.** Does the acquiree's brand transition to the acquirer's brand at day-100 (or day-180, or a longer date), remain as a sub-brand of the acquirer, or persist as an independent brand indefinitely?
- **Deeper product-portfolio integration.** Does the acquiree's product remain standalone, consolidate into the acquirer's, or run a phased-sunset? (Chapter 4 depth.)
- **IMO sunset or extension.** Does the IMO dissolve at day 100 (unusual — the plan usually extends to day 180 or day 365), or extend with specific revised scope and cadence? Which workstreams have completed and can dissolve their integration workstream; which continue?
- **Second-order integration priorities.** What are the next-quarter integration priorities and their specific owners.

**The specific pattern for a defensible day-100 review.** Every milestone status is claimed with a specific evidence-anchor — not "systems-cutover complete" but "systems-cutover: month-1 finance close in acquirer's ledger completed on [date] with [name] sign-off; HRIS-cutover completed on [date] with [count] acquired-employee records in acquirer's HRIS; security-perimeter at parity per [specific security-checklist] as of [date]." The day-100 review is the specific artefact that the day-500 escrow claim or the year-2 board review will read to reconstruct whether integration went as planned.

**The specific pattern for a defensible go / no-go decision.** Deeper-integration decisions at day 100 are made with the following framework:

- If the day-30 and day-90 milestones for the specific workstream are green, deeper integration proceeds on the plan-of-record.
- If any day-30 or day-90 milestone for the specific workstream is red, deeper integration in that specific area is *paused* with a specific re-plan.
- If the retention or customer metrics are materially below plan, the entire deeper-integration timeline is reviewed for pace — over-integrating too fast against a fragile acquired-business is a specific value-destruction pattern.
- The specific go / no-go is captured to the decision log with specific rationale, alternatives considered, and named decision-makers.

## Summary

The acquired-company 100-day plan is the specific operational spine that turns a signed deal into a working acquired business inside the acquirer's ongoing-operations envelope. The **day-1 readiness checklist** clears the "employees show up to a working company on Monday" bar — payroll continuity through the acquiree's provider, email-and-identity continuity through no-break-in-access, benefits continuity through the acquiree's plans, day-1 org-chart publication with the specific reporting-line change at the top, town-hall calendar for the first 100 days. The **day-30 systems-cutover milestones** land the finance close in the acquirer's ledger, the HRIS cutover with every employee record in the acquirer's system, and the security-perimeter integration at parity with the acquirer's baseline. The **day-90 organisational-integration milestones** land the comp-and-leveling harmonisation (with a "no employee worse off in cash" preservation principle), the promotion-cycle alignment (with pre-close-committed promotions honoured), and the performance-management alignment (with manager training on the acquirer's framework). The **day-100 review** produces the explicit go / no-go decision on deeper integration — deeper technology-and-systems integration, deeper organisational integration, brand integration, product-portfolio integration, IMO sunset-or-extension — each captured to the decision log with specific rationale.

The chapter that follows turns to the *founder-inside-acquirer* 100-day plan — the specific overlay that sits on top of the acquiree 100-day plan for the founder-CEO who is staying inside the acquirer post-close, including the honest-signal pattern for a founder who realises the seat is not working.
