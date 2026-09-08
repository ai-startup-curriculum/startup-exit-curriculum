# exercise-04: Buy-side diligence workstream plan authoring

**Estimated effort:** 5–6 hours

## Objective

Author a complete buy-side diligence workstream plan for a specific hypothetical target — the ten-to-fifteen-workstream inventory with scope, provider, deliverable, timeline, cross-workstream dependencies, and explicit read-across to the definitive agreement and the R&W policy for each workstream.

The finished artefact is a workstream-plan document (12–20 pages) plus a workstream-timeline Gantt (Excel, Google Sheets, or an equivalent) that a corp-dev VP or M&A partner would put in front of the acquisition committee at LOI signing to secure sign-off on the diligence budget, timeline, and provider stack.

You should end the exercise able to defend the workstream count and scope for your specific target, the specific provider selections against at least one rejected alternative per material workstream, the sequencing, the escalation rules, and the reporting cadence.

## Background

This exercise covers material from:

- [Chapter 4 — Buy-Side Diligence Workstream Design](../04-buy-side-diligence-workstream-design.md) — the ten-to-fifteen-workstream taxonomy, per-workstream scope / provider / deliverable / read-across, workstream sequencing, workstream-plan document architecture, buy-side operating discipline.

Supporting references:

- [mod-104 chapter 4](../../mod-104-loi-negotiation-and-definitive-agreements/04-definitive-agreement-architecture-and-reps-layering.md) for the reps-and-warranties framework the workstream plan feeds.
- Chapter 6 for the R&W underwriter's diligence coordination.
- Chapter 7 for the AI-model and OSS-licence workstream specifics.

## Prerequisites

- The hypothetical target you have been carrying through mod-101–104 (or the target-facts baseline from exercise 1 of this module). If flipping seats to buy-side, also freeze:
  - The acquirer profile — strategic vs. financial, public vs. private, sector fit, prior acquisition history, in-house corp-dev / M&A team capacity.
  - The LOI headline economics and any structural specifics (asset vs. stock vs. reverse-triangular; consideration mix; any earn-out).
  - The buyer's M&A counsel and preferred provider stack (Big Four QoE relationship, tech-diligence firm preference, HR-comp consultant relationship).
- Familiarity with the modern buy-side provider ecosystem (Big Four accounting firms, QoE-specialist firms, tech-diligence firms, HR-comp consultants, security-diligence firms, IP counsel, specialist regulatory counsel, insurance brokers, antitrust counsel).
- A spreadsheet or project-management tool for the timeline / Gantt.
- The current-cycle ABA Private Target Deal Points Study and SRS Acquiom study for anchor data on workstream prevalence and deal-cycle timing.

## Tasks

### 1. Set the transaction-and-target baseline

Write a 1-page baseline covering:

- Target profile (sector, ARR, growth, headcount, geography, cap-table shape, AI posture, sector-regulatory footprint).
- Acquirer profile (strategic / financial, public / private, prior-acquisition history, corp-dev / M&A team capacity, financing source).
- LOI headline economics (enterprise value, purchase-price mix, escrow / holdback, R&W-insurance placement expectation, expected close timeline).
- Deal-specific risk hot-spots (customer concentration, key-person dependency, prior aborted transaction, regulatory-hot sector, AI-training-data exposure).
- Exclusivity window and target signing date.

### 2. Author the workstream inventory

Produce the workstream inventory as a table with one row per workstream. For each row:

- Workstream number and name.
- In-scope / out-of-scope for this transaction (with rationale — e.g., Environmental typically out-of-scope for pure software; Antitrust may or may not be in-scope depending on target size vs. HSR threshold).
- Provider (specific firm name where you would name one — Deloitte / EY / KPMG / PwC for financial, Crosslake / West Monroe / RSM for tech, Radford / WTW / Aon for HR-comp, specific IP counsel, specific sector regulatory counsel).
- Provider-selection rationale (why this provider against one rejected alternative).
- Estimated duration (from launch to final deliverable).
- Estimated cost (rough magnitude — often $50K–$500K per workstream).
- Deliverable format.
- Workstream owner on buyer's deal team.

Cover the full ten-to-fifteen list from chapter 4:
1. Financial (buy-side QoE).
2. Legal (corporate).
3. Tax.
4. Commercial.
5. Technology / Product.
6. Intellectual Property.
7. HR / Compensation.
8. Privacy.
9. Security.
10. AI / Model.
11. Open Source.
12. Regulatory.
13. Environmental (in-scope or out-of-scope with rationale).
14. Insurance.
15. Antitrust.

### 3. Author per-workstream detail sheets

For each in-scope workstream, produce a detail sheet covering:

- **Scope.** The specific inspection scope for this target (customised, not generic).
- **Provider.** As above.
- **Key personnel.** The specific engagement-level personnel from the provider (partner, senior manager, senior associate, sector specialist).
- **Start / deliverable / final-report dates.**
- **Dependencies on other workstreams.** E.g., privacy needs the customer-contract stack from legal; security needs the tech-stack overview from tech.
- **Key questions to answer.** The 5-to-10 specific questions the workstream must answer.
- **Read-across to the definitive agreement.** The specific reps, disclosure schedules, and indemnity structures the workstream feeds.
- **Read-across to the R&W policy.** The specific coverage areas the workstream underpins and the specific exclusion risks.
- **Read-across to the integration plan.** The specific integration actions the workstream is likely to surface.

The detail sheets should differ from workstream to workstream in scope and depth — a Financial detail sheet has different key questions than a Regulatory detail sheet.

### 4. Draft the Gantt / sequencing timeline

Produce the workstream Gantt with:

- Day-0 (LOI signing) as the anchor.
- Day-45 or Day-60 (target signing date) as the terminal.
- Each workstream's launch-to-final-deliverable bar on the timeline.
- Cross-workstream dependency arrows (where workstream B depends on workstream A's outputs).
- Milestones — the buyer-deal-team weekly meeting, the R&W underwriter's diligence-review call, the findings-memo delivery, the disclosure-schedule delivery, the signing-package finalisation.

Sequence following chapter 4's guidance:

- Financial and Legal (corporate) launch Day 1.
- Tax and IP launch Day 3-to-5.
- Tech, Commercial, HR launch Day 5-to-10.
- Privacy, Security, AI, OSS launch Day 5-to-15.
- Regulatory, Environmental, Insurance, Antitrust launch as needed.

### 5. Draft the cross-workstream dependencies

Produce a dependency matrix — which workstreams need outputs from which other workstreams. Common examples:

- Privacy needs the contract stack from Legal (DPAs, sub-processor agreements).
- Security needs the tech-stack overview from Tech.
- HR needs the cap-table verification from Legal.
- Tax needs the 280G analysis inputs from HR.
- AI needs the model inventory from Tech.
- OSS needs the SBOM (or scan output) from Tech.
- Insurance coordinates directly with the R&W underwriter (chapter 6).
- Antitrust needs the market-sizing inputs from Commercial.

For each dependency, note the specific artefact and the delivery timing that makes the dependency work.

### 6. Draft the escalation rules

Produce the escalation-to-deal-team rules:

- **Standard workstream question or issue** — stays with the workstream provider and workstream owner.
- **Emerging red finding** — the workstream provider escalates to deal-team lead within 24 hours.
- **Material finding warranting price / indemnity conversation** — deal-team lead escalates to acquisition committee.
- **Deal-collapse-risk finding** — deal-team lead escalates immediately to acquisition committee and, for public acquirers, to CEO / board.
- **Cross-workstream inconsistency** — deal-team lead's job to detect and reconcile.
- **Sell-side heads-up on a proactive-disclosure item** (chapter 3) — deal-team lead's job to route to the affected workstream provider for reactive analysis.

### 7. Draft the reporting cadence

Produce the reporting-cadence document:

- **Daily stand-up** — during peak weeks (typically weeks 2–5). Diligence coordinator plus workstream owners; 15–20 minutes; status, blockers, cross-workstream coordination.
- **Weekly deal-team meeting** — deal-team lead, M&A counsel, workstream owners, banker. 60–90 minutes; workstream status, material findings, escalation, scope adjustments.
- **Bi-weekly acquisition-committee update** — deal-team lead to acquisition committee. 30 minutes; summary status, material findings, key decisions.
- **Continuous board briefing** (where applicable) — the deal-team lead maintains continuous board awareness so no surprises at the signing meeting.

### 8. Draft the R&W-underwriter coordination plan

Chapter 6 will develop this in exercise 6. Here, name:

- **The broker engagement timing** — at LOI signing.
- **The NBI (non-binding indication) target date** — 5-to-10 business days post broker-market.
- **The underwriter-selection target date** — 10-to-15 business days post broker-market.
- **The underwriter-diligence-review call target date** — target week 4 of buy-side diligence.
- **The exclusions-memo negotiation timeline** — target 2-to-3 weeks pre-signing.
- **The R&W-considerations feedback loop** — each workstream's findings-memo section includes explicit R&W-exclusion expectations.

### 9. Draft the integration-planning hand-off plan

Chapter 5's findings memo has an Integration-Plan-Input section. Here, name:

- **The integration-planning-team engagement timing** — deal-team routes findings to integration team weekly during diligence, not once at signing.
- **The integration-workstream categories** — finance, HR, security, engineering, sales, legal.
- **The findings-to-integration-action translation** — the diligence findings that translate into integration actions (controllership under-staffing, SOC 2 unremediated exception, OSS attribution gap, HR-file completeness gap).
- **The first-100-day-plan input timing** — the integration team's plan draft is expected by signing, not by closing.

### 10. Draft the workstream-plan executive summary

Produce a 1–2 page executive summary suitable for acquisition-committee review at LOI signing. Cover:

- Transaction context.
- Workstream count and in-scope / out-of-scope decisions.
- Provider stack summary.
- Timeline.
- Budget (roll-up of per-workstream cost estimates).
- Key risks the plan is designed to address.
- Escalation and reporting cadence summary.

## Starter guidance

Common buy-side workstream-plan errors to avoid:

- **Copy-paste of a generic workstream list.** The workstream plan should be customised to the target. A biotech target's plan looks materially different from a SaaS target's plan; a hardware target adds supply-chain. Copy-paste produces coverage gaps.
- **Provider selection without provider-selection rationale.** "Deloitte for financial" is not a plan; "Deloitte for financial, chosen over EY because Deloitte's tech-and-media QoE practice has audited three of the acquirer's prior three acquisitions in this sector" is.
- **Under-scoping the AI and OSS workstreams.** These workstreams' importance has grown faster than the workstream-plan templates have. A five-year-old workstream template does not adequately scope AI-and-OSS for a modern venture-backed target.
- **Sequential rather than parallel R&W underwriting.** Running underwriter-diligence-review after buy-side diligence completes wastes weeks. Running it in parallel means exclusions land in time to be worked into the definitive-agreement negotiation.
- **No integration-planning hand-off during diligence.** Handing integration-planning the findings only at signing means the integration team rediscovers findings post-close. The hand-off happens weekly during diligence.
- **Missing dependency arrows.** Privacy launched before Legal has produced the contract stack, or Security launched before Tech has produced the tech-stack overview — both produce workstream stalls that eat calendar days.
- **Cost estimates that come in only at final invoice.** The workstream-plan budget should be a controlled forecast, not a surprise at final invoice. Engagement letters should cap fees where feasible.

## Acceptance criteria

You can demonstrate that:

- Transaction-and-target baseline is written.
- Workstream inventory covers all ten-to-fifteen workstreams with in-scope / out-of-scope, provider, provider-selection rationale, duration, cost, deliverable, and buyer-side owner.
- Per-workstream detail sheets are produced for each in-scope workstream with scope, key personnel, dates, dependencies, key questions, and three read-across (definitive-agreement, R&W policy, integration plan).
- Gantt / sequencing timeline is drafted with cross-workstream dependency arrows.
- Cross-workstream dependency matrix is produced with specific artefact and timing per dependency.
- Escalation rules are documented at three levels (workstream, deal-team, acquisition-committee).
- Reporting cadence is documented (daily stand-up, weekly deal-team, bi-weekly acquisition-committee, continuous board).
- R&W-underwriter coordination plan names broker engagement timing, NBI, selection, review-call, exclusions-memo negotiation, and R&W-considerations feedback loop.
- Integration-planning hand-off plan is drafted with weekly-during-diligence rhythm.
- Executive summary is drafted at 1–2 page depth suitable for acquisition-committee review.

## Reflection

Add a short reflection:

1. Which single workstream in your plan has the highest deal-decision leverage — i.e., its findings could most reshape the price, structure, or decision-to-close?
2. If the acquirer's board pushed back on the diligence budget by 30%, which workstream would you cut or de-scope, and what would the residual coverage-gap risk be?
3. Which cross-workstream dependency is most likely to cause a stall in your timeline, and what pre-emptive coordination could prevent it?
4. If the R&W underwriter came back with a broad AI-training-data exclusion (chapter 6 / chapter 7), which workstream in your plan would need to expand to address it, and what would the timing impact be?

## Stretch goals

- **Provider engagement-letter drafting.** Draft an engagement letter for one of your key workstream providers, with attention to scope definition, fee structure, deliverable timing, reliance-letter mechanism, and confidentiality.
- **Provider RFP process.** Instead of naming providers directly, run a simulated RFP process — draft the RFP for one workstream (e.g., tech diligence), evaluate two-to-three providers against defined criteria, and defend the selection.
- **Multi-transaction resource-planning.** For an acquirer running multiple concurrent processes, adapt your workstream plan to a multi-transaction resource-allocation model — which providers can be shared across transactions, which cannot, how the corp-dev team's capacity constrains the plan.
- **Post-close diligence-effectiveness retrospective template.** Draft the retrospective template the corp-dev team would use post-close to evaluate the workstream plan's effectiveness — which workstreams surfaced material findings, which did not, which added value, which did not, which provider performed above / below expectations. Feed this into future workstream-plan templates.
- **Underwriter-perspective simulation.** Take your workstream plan and, from the R&W underwriter's chair, identify the specific coverage-gap workstreams (under-scoping, missing workstream, missing evidence). What specific exclusions would result?
- **Cross-border expansion.** For a target with meaningful foreign-subsidiary presence (Germany, UK, India, or other jurisdictions), extend the workstream plan to cover the jurisdiction-specific diligence — local counsel, foreign-antitrust filing, local tax and privacy, foreign employment counsel.
