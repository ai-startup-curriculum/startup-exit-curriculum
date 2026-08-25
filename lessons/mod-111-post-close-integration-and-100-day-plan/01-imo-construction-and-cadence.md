# Constructing the Integration Management Office (IMO)

## Why this matters

Every closed deal ships with an unstated assumption: that the two operating companies will merge — or that one will absorb the other — through a set of *decisions* that neither company's ordinary-course leadership is currently making. The ordinary-course CFO is closing the quarter; the ordinary-course CTO is shipping the roadmap; the ordinary-course CHRO is running the compensation cycle. None of them has the authority, bandwidth, or explicit mandate to decide *which finance ledger the acquired business closes into next month*, *which identity provider the combined employee base logs in through*, *which comp-and-leveling framework the acquired engineering team is placed on at day 90*. Without a standing venue for those decisions — a specific integration-decision machine, staffed and cadenced and empowered — those decisions get punted, get made informally by whoever happens to be in the room, or (worst) get made twice with contradictory outcomes by different workstream leaders discovering weeks later that their peer decided the same question differently.

The **Integration Management Office** (IMO) is that machine. It is a *temporary* organisational structure — typically dissolved at day 100, day 180, or day 365 depending on integration depth — that sits *above* both companies' ordinary-course leadership for the duration of integration, holds the plan-of-record, tracks execution against milestones, surfaces and resolves cross-workstream risks and issues, and — most importantly — produces a defensible *decision log* of what was decided, by whom, with what alternatives considered, on what date. The decision log is what a day-500 escrow dispute reads, what a day-700 stockholder-litigation defence reads, what the acquirer's board reads when the integration is reviewed at the anniversary. The Sirower / McKinsey / BCG / Bain / Big-Four PMI canon is remarkably consistent on this point: the deals that *have* a functioning IMO create value at roughly the rate deals *without* one destroy it, and the empirical difference is not the sophistication of the IMO's templates but the *discipline* of standing it up on day 1 with named leaders, a defined cadence, and an authoritative charter.

This chapter installs the IMO. The intent is to give the acquirer-side executive sponsor, the acquiree-side executive sponsor, the integration lead, and the CFO / GC / CHRO / CTO who staff its workstreams a specific playbook they can execute in the two-week window between signing and closing (or, more commonly, the two-week window between close and day 1 of integration where signing-to-close was compressed).

> Reminder: this module is education, not legal / management-consulting / audit advice. Every live integration engages a specific set of advisors — often the same Big-Four firm or strategy consultancy already used for buy-side diligence — to help stand up the IMO and staff the workstream leads. The structure below is the operational discipline that sits underneath their advisory overlay.

## What the IMO is — and what it is not

The IMO is a *coordination-and-decision venue*, not an operating team. It does not close the finance books; the acquirer's controller does. It does not merge the identity systems; the acquirer's IT security team does. It does not run the retention conversations; the acquiree's CHRO does (with acquirer-side coordination). What the IMO does is:

- **Hold the integration plan-of-record.** The single source of truth for what is being integrated, on what timeline, by whom, at what dependency-chain.
- **Track execution against the plan.** Weekly status against each milestone, with named owners and dated commitments.
- **Surface and resolve cross-workstream risks and issues.** The pattern where "the HR-workstream lead did not know that the finance-workstream lead was committing the acquired business to the acquirer's monthly-close cadence, which requires the acquired-business timesheet system to feed the acquirer's payroll six weeks earlier than currently planned" — this is what the IMO surfaces and resolves.
- **Produce and maintain the decision log.** Every consequential decision — architecture, org, comp, systems, retention, brand, product-portfolio, customer-contract disposition — is captured with date, decision, decision-maker, alternatives considered, and rationale.
- **Escalate to executive sponsors when workstream leads cannot resolve.** The escalation path is explicit: workstream-lead disagreement → integration lead → executive sponsors (paired) → CEO of acquirer (if required).

What the IMO is *not*:

- Not a synergy-tracking spreadsheet with no operational teeth. The empirical failure mode of "PMI theatre" is a Big-Four-authored 40-tab spreadsheet that no one updates after week 3.
- Not the acquirer's ordinary-course executive team by another name. It is *paired* leadership — acquirer-side and acquiree-side co-equal — with dedicated bandwidth.
- Not a permanent structure. It has a specific sunset date built into its charter (typically day-100, day-180, day-365, or a specific milestone gate).
- Not a substitute for either company's ordinary-course leadership. The acquiree's CEO does not become the integration lead; the acquirer's COO does not become the executive sponsor as an add-on to their day job.

## Executive-sponsor pairing — acquirer-side and acquiree-side co-leads

The specific structural choice that most defines whether the IMO functions is the **executive-sponsor pairing**: two named executives, one from each side, co-equal in authority, jointly accountable for the integration's success. The paired structure is what prevents the acquired team from feeling colonised (an acquirer-only sponsor signals "we are here to absorb you") and what prevents the acquiring team from feeling that the acquired business has a special political channel (an acquiree-only sponsor signals "your business is out of scope"). It also creates a specific channel for cross-cultural translation — the acquiree-side sponsor speaks the acquired team's language, the acquirer-side sponsor speaks the acquirer's, and together they translate.

**Who staffs the acquirer-side sponsor seat.** Typically a specific executive with the seniority and time-availability to be present and empowered. Common patterns:

- **A specific senior executive with adjacent P&L ownership** — the SVP or GM of the business unit that will absorb the acquired business, if there is one. This person has direct interest in the integration succeeding.
- **The acquirer's COO or Chief of Staff** — if there is no clear business-unit-owner match, or if the deal is large enough to warrant CEO-adjacent attention.
- **The acquirer's Head of Corporate Development / SVP-Corp-Dev** — if the deal is one of several the corp-dev team is integrating in parallel, and the corp-dev leader has a track record of integration execution. This is the most common pattern for serial acquirers (Google, Meta, Cisco, Salesforce, Adobe historically).
- **A dedicated Chief Integration Officer** — for the very largest acquirers (Berkshire Hathaway operationally, the historical Cisco M&A machine, large PE platforms) a specific executive whose full-time role is integration across a portfolio of deals.

The acquirer-side sponsor is *not* the acquirer's CEO in most cases — the CEO is the escalation point, not the operational sponsor. It is also not, by default, the acquirer-side deal team's lead corporate-development analyst; the corp-dev analyst who ran the deal typically hands off to the integration lead at close.

**Who staffs the acquiree-side sponsor seat.** Typically the acquiree's CEO or a specific senior acquiree executive with the credibility and mandate to speak for the acquired team. Common patterns:

- **The founder-CEO of the acquired company** — if the founder is staying in a substantive role post-close (see chapter 3). The founder's credibility with the acquired team is a specific asset the IMO needs.
- **The acquiree's President, COO, or Chief of Staff** — if the founder-CEO is departing at close or is not the right operational sponsor (some founders are visionary but not operational; the President often is).
- **A specific acquiree functional leader** — the CTO, CRO, or CFO — if the deal is a technology-tuck-in or a specific-function-driven acquisition where one leader is the acquired-business's operational spine.

The acquiree-side sponsor is not by default the acquirer's newly-appointed leader of the acquired business (if that person is an acquirer-side transplant). Even where the acquirer intends to install its own leader over the acquired business, the *integration-period* sponsor should be an acquiree-side executive who carries acquired-team credibility.

**The paired-sponsor working model.** The two sponsors:

- Co-chair the weekly steering committee (see cadence section below).
- Jointly own the escalation resolution — no workstream escalation resolves without both sponsors weighing in.
- Meet 1:1 at least weekly outside the formal cadence to align on cross-workstream issues and to build the working relationship that the integration will lean on.
- Co-author the monthly board update (or the acquirer-CEO update if the deal is not board-level material at the acquirer).
- Jointly own the day-100 review and the go / no-go on deeper integration.

## Integration lead selection — dedicated full-time integration executive vs. business-line owner

The **integration lead** is the operational spine of the IMO. This person owns the plan-of-record, runs the daily standup, chases the workstream leads, maintains the RAID log and the decision log, and drafts the weekly steering-committee materials. The single most consequential staffing choice in the entire integration is who takes this seat — and specifically, whether it is a *dedicated full-time integration executive* or a *business-line owner with integration added to their existing responsibilities*.

**The dedicated full-time integration executive pattern.** A specific individual — often an experienced M&A-integration professional from the acquirer (or, for the first few deals, an external integration-consultant embedded on a specific contract) — whose *only* job for the integration period is running the IMO. Advantages:

- Full bandwidth for the workstream-chase, the escalation-drive, the plan-maintenance work that a business-line owner would deprioritise against ordinary-course delivery.
- Neutral standing across the workstreams — not personally invested in one workstream over another.
- Repeatable across deals for a serial acquirer, building institutional integration muscle.

Disadvantages:

- Cost — a full-time senior integration executive is a $250k–$500k / year burden per deal for a 3–12-month window.
- Lack of business context — the integration executive who has not run a P&L can miss operational nuance.
- Perceived remove from execution — the workstream leads may under-respond to a "corporate integration" role vs. a business-line peer.

**The business-line owner pattern.** The acquirer-side executive who will own the acquired business post-integration takes the integration-lead seat in parallel with their business-line responsibilities. Advantages:

- Direct alignment of integration success with post-integration operational success — the person running the integration is the person who will live with its outcomes.
- Deep business context and credibility with the workstream leads.
- No add-cost — the executive is already on payroll.

Disadvantages:

- Bandwidth conflict — the integration will be de-prioritised against the ordinary-course business, especially in the first 30 days when the ordinary-course business demands attention regardless.
- Political conflict — the business-line owner may push integration decisions toward their preferred outcome rather than the objectively best outcome for the combined company.
- No cross-deal muscle-building — each deal starts from scratch.

**The pattern most serial acquirers converge on.** The empirically-common pattern for a company doing more than 2–3 deals per year is a *hybrid*: a dedicated Chief Integration Officer or integration-team-of-record at the acquirer level who partners with a *business-line integration lead* on each specific deal, splitting responsibilities. The Chief Integration Officer owns the plan-of-record, the templates, the escalation, and the institutional-memory of what worked in prior deals; the business-line lead owns the specific-deal decisions and the workstream-lead relationships.

**A specific anti-pattern.** The single most predictable integration failure is the acquirer's SVP-Corp-Dev taking the integration-lead seat as an add-on to their ordinary-course role. The corp-dev leader is drowning in the *next* deal 60 days after close and stops running the integration; the workstream leads notice, the cadence collapses, and the decisions get made informally in Slack DMs. This is why serial acquirers separate the corp-dev function from the integration function.

## Workstream-lead roster — the specific functions that need named leaders

The IMO's operational work is done by **workstream leads** — one named individual (typically paired: one acquirer-side, one acquiree-side, for the same reasons the sponsors are paired) per specific function. The specific workstreams that appear in almost every mid-to-large integration:

- **Finance.** Owned by the acquirer-side controller and the acquiree-side CFO / VP-Finance. Scope: chart-of-accounts mapping, ledger consolidation, close-cycle alignment, accounts-payable transition, revenue-recognition alignment, tax-integration (SUT, income, transfer-pricing), banking transition. The day-30 finance-close milestone is this workstream's proof point.
- **People (HR).** Owned by the acquirer-side CHRO or VP-People and the acquiree-side CHRO / Head of People. Scope: HRIS cutover, benefits transition, payroll cutover, comp-and-leveling harmonisation, org-chart publication, immigration-and-visa continuity, retention-plan execution. The day-1 payroll-and-benefits milestone and the day-90 comp-and-leveling milestone are this workstream's proof points.
- **Systems / IT.** Owned by the acquirer-side CIO or Head of IT and the acquiree-side Head of IT (which in a smaller acquiree is often a specific senior engineer or the CTO). Scope: identity-provider (IdP) consolidation, email-and-collaboration cutover, endpoint-management, network integration, VPN and remote-access, MDM, laptop and equipment provisioning, physical-office IT. The day-1 email-and-identity cutover is this workstream's proof point.
- **Product.** Owned by the acquirer-side CPO or Head of Product and the acquiree-side CPO / Head of Product. Scope: product-portfolio decisions (consolidate, preserve, phased-sunset — see chapter 4), roadmap-integration, feature-parity-and-migration, pricing alignment, packaging alignment, product-brand transition. This workstream has the longest tail — most product-integration decisions play out over quarters, not days — but the day-100 review must have named the day-1 direction.
- **Engineering.** Owned by the acquirer-side CTO or VP-Engineering and the acquiree-side CTO / VP-Engineering. Scope: engineering-org merge-or-preserve, tech-stack decisions, code-repository consolidation, CI/CD alignment, on-call cadence, incident-response alignment. Chapter 4 covers the depth here.
- **GTM (Sales, Marketing, CS).** Owned by the acquirer-side CRO and the acquiree-side CRO / VP-Sales / VP-Marketing. Scope: sales-territory alignment, quota-and-comp-plan alignment, brand transition, customer-communications-cadence, sales-training-on-combined-portfolio, cross-sell-motion enablement, marketing-website-and-brand transition, customer-success-model alignment.
- **Legal.** Owned by the acquirer-side GC and the acquiree-side GC / Head of Legal. Scope: entity-consolidation, IP-assignment-and-registration, contract-assignment or change-of-control-notice execution, corporate-governance-integration, license-and-regulatory-registration transition, dispute-inventory transition, escrow-release-and-earn-out-execution coordination (see chapter 7).
- **Brand and communications.** Owned by the acquirer-side Head of Comms / CMO and the acquiree-side Head of Comms / CMO. Scope: internal-communications cadence, external-brand transition (co-brand, sub-brand, absorbed brand), press-and-analyst engagement, customer-facing communications, employee-facing communications through integration.
- **Customer success.** Owned by the acquirer-side VP-CS or Head of CS and the acquiree-side VP-CS / Head of CS. Scope: customer-account-mapping, top-account-executive-sponsor pairing, renewal-choreography-through-integration, health-score-monitoring, escalation-path integration. This workstream is often surfaced separately from GTM because top-account retention through integration is a specific board-level concern.
- **Partner and ecosystem.** Owned by the acquirer-side Head of Partnerships and the acquiree-side Head of Partnerships. Scope: partner-agreement disposition, channel-conflict resolution, referral-relationship-continuity, developer-ecosystem transition (for platform-companies). Often small in scope but consequential in some deals.

**Not every workstream fires on every deal.** A small tuck-in may not have a partner-ecosystem workstream; a talent-acquisition ("aqui-hire") may compress the product / engineering / GTM workstreams into a single "engineering-team-absorption" workstream; a cross-border deal adds a specific *jurisdictional-integration* workstream for local-entity setup, works-council consultation, and tax-registration alignment. The IMO charter names the specific workstreams that fire for the specific deal and explicitly notes which do not, so the omission is intentional rather than accidental.

**Workstream-lead accountability.** Each workstream lead has:

- A dated milestone list for the 100-day window.
- A named point-of-contact on the paired side (acquirer ↔ acquiree lead pairing).
- A specific reporting cadence into the IMO (daily standup for the first 30 days, weekly workstream review with the integration lead after).
- An explicit RACI for the workstream's decisions — which decisions the workstream lead makes unilaterally, which require paired-lead consensus, which require integration-lead approval, which require sponsor-level or CEO-level escalation.

## Cadence design — daily standup, weekly steering, monthly board update

The IMO runs on a specific cadence — a rhythm that keeps the workstreams aligned, surfaces issues fast enough to resolve them before they compound, and produces the artefacts (weekly status, monthly board update, quarterly integration-review) that the executive layer needs.

**Daily standup — first 30 days.** A 20-minute daily call, video-first, at a specific time (typically first-thing in the primary time zone). Every workstream lead attends. Structure: (a) what did we accomplish yesterday, (b) what are we doing today, (c) what is blocking us. The integration lead facilitates; the daily is *not* a decision meeting — decisions get taken offline or in the weekly steering. The purpose is *coordination velocity* — the discovery that the finance workstream needs the systems workstream to spin up SSO to the new ERP by Friday, surfaced on Monday, resolved by Tuesday.

The daily standup typically compresses to three-times-a-week at day 30, weekly at day 60, and dissolves entirely by day 100 as workstreams reach steady state.

**Weekly steering committee.** A 60-minute meeting weekly for the duration of integration, co-chaired by the two executive sponsors, with the integration lead running the agenda and all workstream leads attending. Structure:

- 5 minutes — integration lead's summary of the week's status (RAG per workstream: red / amber / green).
- 20 minutes — workstream lead status reports (2–3 minutes each, focused on milestones-hit-and-missed and specific decisions requested).
- 20 minutes — cross-workstream escalation resolution (issues that could not be resolved between workstream leads bilaterally are surfaced and either resolved in the room or escalated up).
- 10 minutes — decisions of record captured to the decision log with named owner.
- 5 minutes — next-week look-ahead and specific commitments.

The weekly steering committee is where the integration's actual work of *paired-sponsor decision-making* happens. Its cadence must be respected — a missed weekly steering committee is a specific signal that the integration is off the rails.

**Monthly board update / acquirer-CEO update.** A specific written document delivered monthly to the acquirer's board (if the deal is board-material) or to the acquirer's CEO (always). Structure typically:

- Deal thesis reminder (one paragraph — the synergy story the deal was signed on).
- Overall RAG-rating for the integration.
- Milestone status vs. plan (day-1, day-30, day-90, day-100 milestones by workstream).
- Financial-integration status (revenue vs. plan for the acquired business, cost-synergy realisation vs. plan, integration-spend vs. budget).
- Retention status vs. plan (headcount vs. plan, top-quartile retention vs. plan, unplanned attrition list).
- Customer and revenue status vs. plan (top-N customer renewals through integration, gross retention vs. plan, cross-sell realisation).
- Key decisions of the month.
- Key risks and mitigations.
- Asks of the acquirer's board / CEO.

The monthly update is the artefact that keeps the acquirer's board aligned and is the primary defence against the "the integration is not going well" surprise at month 5 or month 8.

**Quarterly integration review.** At quarter-marks (day 90, day 180, day 270, day 365), a specific longer-form review — typically 90 minutes to half a day — that steps back from milestone execution to reassess the deal thesis: are the synergies materialising, is the retention holding, are the top customers renewing, are the earn-out targets on track. The quarterly review is where integration-scope adjustment decisions get made (e.g., "the technology-consolidation workstream is materially behind — we are extending the sunset of the acquired product's separate stack from day-180 to day-540 with a specific plan").

**A specific anti-pattern.** The most common cadence failure is the paired-sponsor missed-standup pattern — the executive sponsors treat the daily standup as optional because "the workstream leads know what to do." Within two weeks, the daily standup is a three-workstream-lead meeting where nothing gets escalated because there is no sponsor in the room to escalate to; within four weeks, the RAID log has stopped updating; within eight weeks, the first missed milestone reveals that no one was tracking. The defence is a specific sponsor commitment at IMO chartering: the sponsors are on the daily for the first 30 days, period, and if a sponsor cannot be there they send a specific named delegate.

## Risk-and-issue register (RAID log)

The **RAID log** — Risks, Assumptions, Issues, Decisions — is the specific document that tracks what is uncertain, what is being counted on, what is currently broken, and what has been decided. It is maintained by the integration lead, reviewed at every weekly steering committee, and — in most integrations — is the single artefact the IMO refers to most frequently.

**Risks.** Things that *might* go wrong. Each risk has: a specific description, a probability rating, an impact rating, a named owner, a mitigation plan, and a review-date. Example: "Risk: acquiree's top-10 customer, TargetCo #1, has a specific change-of-control clause that grants them a 90-day right to terminate. Probability: medium (customer is in a competitive-review with a competitor of the acquirer). Impact: high (represents 12% of acquired-business ARR). Owner: CS-workstream lead. Mitigation: CEO-to-CEO relationship-call in first 30 days, executive-sponsor commitment for named-account manager, contract-restructuring offer with 12-month price-lock. Review: weekly through day 90."

**Assumptions.** Things being *counted on* without confirmation. Assumptions must be surfaced explicitly because they are the source of most cross-workstream failures. Example: "Assumption: acquired-business's 401(k) plan can be terminated at close with distribution to employees within 12 months. Confirmed by: acquirer-side benefits-counsel review pending. If wrong: plan-termination timeline extends and benefits-cutover slips 90 days. Owner: People-workstream lead."

**Issues.** Things that *have* gone wrong and need resolution. Each issue: description, severity, named owner, resolution-plan, target date. Example: "Issue: acquired-business's identity provider (Okta on a legacy contract) cannot be consolidated into acquirer's IdP (Azure AD) without a specific 60-day parallel-run to avoid breaking third-party SaaS SSO integrations. Severity: medium (does not block day-1 but extends systems-cutover milestone). Owner: Systems-workstream lead. Resolution: 60-day parallel-run beginning day 30, cutover at day 90. Target: day 90."

**Decisions.** The decision log — see the next section.

The RAID log is a *living document* — the point is not to have a perfect log at day 1 but to have one that reflects reality week-over-week. The integration lead's core job is keeping the RAID log honest.

## Decision-log discipline — the day-500 defensibility asset

The **decision log** is the most durable artefact the IMO produces. Every consequential integration decision — architecture choice, org-structure decision, comp-harmonisation decision, systems-consolidation decision, customer-contract disposition, product-portfolio choice, retention-package escalation — is captured with:

- Date of decision.
- Decision statement (what was decided, in one sentence).
- Decision-maker (named individual).
- Alternatives considered (typically 2–4 alternatives with a one-line assessment of each).
- Rationale (why this alternative was chosen).
- Consequences committed to (what this decision commits the integration to).
- Review date (if the decision is revisitable, when).

**Why this matters.** Three specific downstream uses:

1. **Escrow-release and earn-out disputes.** When a specific escrow claim or earn-out dispute arises at day 500, the arbitrator or dispute-resolution mechanism looks at the specific decisions made during integration to assess whether the acquirer's post-close conduct was consistent with the SPA's obligations (particularly earn-out control-and-oversight rights — see chapter 7). A missing or unclear decision-log entry is the specific evidentiary gap that makes an earn-out dispute much more expensive to resolve.
2. **Stockholder-litigation defence.** In a public-acquirer deal, a stockholder challenge to the deal decision itself (owned by mod-109) may extend into questioning the acquirer's post-close conduct as evidence of the deal's underlying merit. A defensible decision log is what the acquirer's litigation counsel wants to hand to the plaintiff's counsel in discovery.
3. **Institutional-memory preservation.** The acquirer's next integration (and the integration lead's departure two years hence) benefit from a specific record of "we tried the phased-sunset approach on this deal because [specific rationale] and the outcome was [specific outcome]." The decision log is the raw material for institutional-memory-building at a serial acquirer.

**How to keep the decision log honest.** The specific discipline is *ratification at the weekly steering committee* — decisions get proposed during the week (in workstream reviews, in daily standups, in sponsor-to-sponsor 1:1s) and are then formally captured in the weekly-steering meeting minutes with the named decision-maker's assent. Decisions not ratified at steering are not durable — they are informal notes that will be re-litigated in three weeks when someone raises the same question.

**A specific anti-pattern.** The most common decision-log failure is the "decisions captured in email threads and Slack DMs" pattern. The result is a decision-log entry that reads "See email thread from Sarah dated week of March 3" — which the day-500 arbitrator cannot verify because Sarah has departed and her email archive has rolled off retention. The defence is the discipline of a single decision-log document (Confluence page, shared Google Doc, dedicated section in the deal-team SharePoint) that is the *only* authoritative source, with per-decision entries linked to but not reliant on the underlying email threads.

## The IMO charter — the founding document

The **IMO charter** is the specific document that constitutes the IMO. It is authored in the two-week window between announcement and close (or between close and day 1 if the signing-to-close gap is compressed) and is signed by both executive sponsors. It is the artefact that answers, in a defensible form, "who does what for how long with what authority."

Typical contents:

- **Purpose statement.** One paragraph on the specific deal thesis and the integration's role in realising it.
- **Sponsor pairing.** Named acquirer-side and acquiree-side executive sponsors, their scope, their escalation path to the acquirer's CEO / board.
- **Integration lead.** Named individual, full-time or business-line-owner, reporting line, tenure.
- **Workstream roster.** Named workstream leads (paired), scope statement per workstream, key milestones per workstream.
- **Cadence.** Daily standup schedule, weekly steering committee schedule, monthly update schedule, quarterly review schedule.
- **Decision-rights RACI.** Per workstream: what decisions workstream-lead makes unilaterally, what requires paired-lead consensus, what requires integration-lead approval, what requires sponsor-level, what requires CEO-level.
- **Milestone plan-of-record.** Day-1 milestones, day-30 milestones, day-90 milestones, day-100 review.
- **RAID and decision-log location.** Specific URL / repository where the RAID log and decision log live and who has access.
- **Sunset criteria.** Specific criteria under which the IMO dissolves — a specific date, a specific milestone, or an explicit trigger (e.g., "IMO dissolves at day 180 or on completion of day-180 review, whichever is later").
- **Budget.** Integration-spend budget for the 100-day window: consulting, systems-integration, retention-bonus reserve, communications, offsite / all-hands.

The charter is signed at day 0 or day 1 and is the reference document for every subsequent integration decision.

## Summary

The IMO is the *coordination-and-decision machine* that converts a signed deal into an executed integration. It is not the ordinary-course leadership of either company — it is a *paired* structure with acquirer-side and acquiree-side co-equal executive sponsors, a full-time or business-line-owner integration lead, a specific roster of paired workstream leads across finance, people, systems, product, engineering, GTM, legal, brand, customer-success, and partner-ecosystem, and a specific cadence: daily standup for the first 30 days, weekly steering committee for the duration, monthly board / CEO update, quarterly integration-review. Its operational spine is the **RAID log** — risks, assumptions, issues, decisions — maintained by the integration lead. Its most durable artefact is the **decision log** — the day-500 defensibility asset that answers what was decided, by whom, with what alternatives considered, on what date. Its founding document is the **IMO charter** — signed by both sponsors at day 0, naming the sponsors, workstream leads, cadence, decision-rights, milestones, and sunset criteria.

The chapter that follows turns to the specific first-100-day plan for the acquired company — the day-1 readiness checklist, the day-30 systems-cutover milestones, the day-90 organisational-integration milestones, and the day-100 review with an explicit go / no-go on deeper integration.
