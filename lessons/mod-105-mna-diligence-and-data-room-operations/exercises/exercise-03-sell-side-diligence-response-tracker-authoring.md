# exercise-03: Sell-side diligence response tracker authoring

**Estimated effort:** 3–4 hours

## Objective

Design the sell-side diligence-response operating system for a specific hypothetical transaction — the workstream-owner map, the SLA discipline, the Q&A tracker schema, the escalation-to-executive rules, and the proactive-disclosure posture — and simulate three days of live buyer-question flow through the system.

The finished artefact is a diligence-response operating-plan document (5–8 pages) plus a working Q&A tracker (spreadsheet, Airtable base, or Notion database) populated with a simulated 20-to-30-question exchange across at least six workstreams over three days.

You should end the exercise able to defend the workstream-owner assignments, the SLA calibrations, the tracker field structure, the escalation rules, the confidential-channel choreography, and the proactive-disclosure decisions on at least two specific material items.

## Background

This exercise covers material from:

- [Chapter 3 — Sell-Side Diligence Response Management — Owners, SLAs, Trackers, Proactive Disclosure](../03-sell-side-diligence-response-management.md) — the workstream-owner map, SLA discipline, Q&A tracker, confidential-communication channel, escalation-to-executive rules, proactive-disclosure vs. answer-only-what-is-asked, scope-creep management, management-interview and reference-call choreography.

Supporting references:

- [Chapter 1](../01-sell-side-data-room-architecture.md) for the fifteen-workstream taxonomy.
- [Chapter 2](../02-sell-side-quality-of-earnings.md) for the QoE workstream's specific SLA and proactive-disclosure patterns.

## Prerequisites

- The target-facts baseline from exercise 1 or the mod-101 / mod-102 target.
- The data-room folder hierarchy from exercise 1.
- Access to a spreadsheet, Airtable, or Notion for the tracker.
- Familiarity with at least one VDR-platform Q&A module (Ansarada, Datasite Diligence, Intralinks) is helpful for comparing your bespoke tracker to the VDR-native alternative.

## Tasks

### 1. Author the workstream-owner map

Produce a table with one row per workstream (all fifteen from chapter 1). For each row:

- Workstream name.
- Primary owner (specific role — GC, CFO, CTO, CISO, CPO, etc. — and, if role is ambiguous or a small target uses one person for multiple functions, the specific individual by function).
- Backup owner.
- Specialist support (Q of E provider, tax advisor, IP counsel, HR consultant, security-diligence firm, etc.).
- Estimated weekly time allocation during peak diligence (5–10 hours for light workstreams; 15–30 hours for heavy — Financial, Commercial, Product/Technology, HR/Comp).
- Any specific hand-offs to the specialist (e.g., "for §280G analysis the workstream hands to Big Four tax advisor").

Then produce a supplementary section documenting:

- **The diligence coordinator role** — who this is on the target's team or banker team; the day-to-day intake / routing / tracker-maintenance responsibilities.
- **The sell-side lead** — typically CFO or GC; the confidential-channel counterparty and the escalation filter.
- **The banker's diligence liaison** — the interface role between the sell-side and the buyer for question screening and scope-creep management.

### 2. Author the SLA discipline document

Produce a 1-page SLA document covering:

- **Straightforward requests** — 24-to-48-hour SLA. Include 3 example requests that fall in this category.
- **Moderate-complexity requests** — 72-hour-to-5-business-day SLA. Include 3 examples.
- **Complex requests** — 5-to-10-business-day SLA. Include 3 examples.
- **Executive interviews and reference calls** — scheduled within 5-to-10 business days.
- The SLA-publication commitment — the document is shared with the buyer's diligence lead at LOI signing so both sides have shared expectations.
- The overdue-response escalation ladder (day 1 = nudge, day 3 = sell-side lead, day 5 = CEO / CFO direct call).
- The push-back mechanism for unreasonable buyer requests — a sample script for a common overreach ("please provide full source code by tomorrow").

### 3. Design the Q&A tracker schema

Produce the tracker schema as a table specification. Include all fields from chapter 3's minimum list:

- Question ID.
- Received date.
- Received via (email, VDR Q&A module, verbal, buyer-diligence-request-list).
- Received from (individual + institutional affiliation).
- Workstream (one of the 15).
- Owner (sell-side workstream owner).
- Question text (verbatim).
- Status (Open, In Progress, Pending Response Review, Answered, Deferred, Closed).
- Priority (Standard, High, Escalated).
- Committed response date.
- Response text.
- Supporting documents (pointers into the data room).
- Sent date.
- Sent to (buyer-side recipient).
- Notes.

Then choose an implementation (spreadsheet, Airtable, Notion, VDR-native Q&A). Justify the choice against the alternatives given your target's scale and complexity.

Add operational-rule detail:

- Same-business-day-entry rule.
- Daily diligence-coordinator review.
- Weekly sell-side-lead and banker-liaison review.
- Tracker-export-at-signing archive rule.

### 4. Author the confidential-communication-channel operating rules

The sell-side lead and buyer's diligence lead maintain a private communication channel outside the formal tracker. Document:

- The channel medium (typically phone or encrypted messaging; not the formal tracker; not group email).
- The categories of communication that flow through it (buyer's read of a finding before formal memo, sell-side heads-up on a material item, process-check conversations, personnel-and-interpersonal issues).
- The mandatory-cross-over-to-formal-channel rule — anything material (scope change, price, covenant, commitment) gets confirmed in writing.
- The frequency (weekly check-in minimum; on-demand for material items).

### 5. Design the escalation-to-executive rules

Produce the escalation rules:

- **Standard workstream question** — stays with workstream owner.
- **Escalated to sell-side lead** — the specific triggers (SLA breach > 1 day, buyer pushback, cross-workstream inconsistency, clean-team-affecting response, price-renegotiation-adjacent response).
- **Escalated to founder-CEO / board** — the specific triggers (material finding, deal-collapse-risk signal, previously-unknown-issue discovery, LOI-economics-affecting buyer request, price-adjustment / indemnity / escrow proposal from buyer).

Include the "ambiguous escalation is welcomed" posture from chapter 3 — the workstream owner's default in doubt is to escalate.

### 6. Design the proactive-disclosure posture

Produce a 1-page proactive-disclosure policy:

- The three-part filter: material items only, deal-team-review required, integrated-with-proposed-treatment.
- The four rationales (R&W dynamics, disclosure-schedule dynamics, sandbagging law, deal-certainty dynamics).
- The categories of items warranting proactive disclosure (customer-consent-required change-of-control provisions, prior-privacy-incidents, prior-litigation-that-would-surface, prior-regulator-inquiry, prior-aborted-transaction).
- The disclosure choreography (confidential-channel first, then formal tracker entry, then disclosure-schedule input).

### 7. Simulate three days of buyer-question flow

Populate your tracker with a simulated 20–30 questions across at least six workstreams over three days. Cover:

- **Financial** — at least 3 questions (buy-side QoE follow-ups, ASC 606 posture, revenue-by-customer).
- **Legal / Corporate** — at least 3 (cap-table verification, board-consent authority, change-of-control provisions in customer contracts).
- **Commercial** — at least 3 (top-customer contract exhibits, customer-reference-call scheduling, cohort-retention analysis request).
- **Product / Technology** — at least 2 (architecture-diagram walk-through, source-code-review access request).
- **HR / Comp** — at least 3 (executive change-of-control agreements, 280G-scoping analysis, retention-plan proposal).
- **Privacy / Security** — at least 2 (SOC 2 report, GDPR data-transfer mechanisms).
- **Plus 3 or more from other workstreams as fits your target.**

For each question, populate all tracker fields. Include a mix of:

- Simple documents already in the room (24-hour SLA, easily met).
- Moderate cross-workstream analyses (72-hour SLA, requires coordination).
- Complex analyses requiring new work-product (5-to-10-day SLA).
- One or two management-interview requests.
- One or two questions that would trigger escalation to the sell-side lead.
- One question that reveals a material issue warranting proactive disclosure.
- One buyer over-reach request (e.g., "full source code by tomorrow") with the push-back scripted.

Show the state of each question at each of the three days (fresh, in-progress, responded, closed, escalated).

### 8. Draft two proactive-disclosure packages

For your target, identify two specific material items that warrant proactive disclosure. For each, draft:

- The finding as it exists on the sell-side.
- The proactive-disclosure choreography (confidential-channel heads-up → formal tracker entry → disclosure-schedule input).
- The proposed treatment (specific-indemnity carve-out, escrow, purchase-price impact, R&W treatment expectation).
- The internal-review sign-off (M&A counsel, CFO, founder-CEO where material).

### 9. Draft the management-interview and reference-call choreography

Produce a mini-playbook covering:

- **Management interviews.** Bulk-scheduling in a two-day window. Pre-brief per executive. Counsel-present rule. Post-brief with deal team. Commitment-capture-into-tracker rule.
- **Customer-reference calls.** Selection criteria (happy customers with defensible tenure). Advance-briefing and consent. Format negotiation. Findings-review-flow into the buyer's commercial-diligence memo.

### 10. Draft the scope-creep management approach

Produce the scope-creep response document:

- The LOI-reference baseline (the diligence workstreams and scope contemplated in the LOI).
- The banker-liaison-runs-the-pushback rule.
- The formal-ask-for-expansion channel.
- The timeline-tradeoff-explicit rule (does the seller extend exclusivity to accommodate expansion, or does the scope get cut?).
- A sample push-back script for a specific expansion request (e.g., tech-diligence firm asks for a full penetration test beyond the LOI scope).

## Starter guidance

Common sell-side diligence-response failure modes to guard against:

- **Ambiguous ownership.** "The CFO's team" instead of "the CFO by name." A dropped question always traces to an ambiguous owner.
- **SLA-on-paper only.** An SLA that is published but never enforced by daily monitoring is not an SLA.
- **Tracker discipline drift.** A tracker where 30% of questions are entered a day after they arrive, or where 20% of responses lack the supporting-document pointer, is a credibility hit that surfaces in a downstream disclosure-schedule dispute.
- **Confidential-channel scope-creep.** The confidential channel is diagnostic and lubricating; commitments made verbally and never confirmed in writing come back to bite.
- **Over-restrictive redaction bleeding into the response.** A response that says "we cannot share the specific customer name" for the fifth time in a week reads as concealment. The redaction protocol (exercise 1) should have anticipated the customer-list question; the response should reference the clean-team subroom.
- **Founder-CEO in the tactical negotiation.** Escalation to the founder-CEO is for strategic decisions, not for tactical negotiation. Keep the founder briefed but out of the tactical exchange with the buyer's diligence lead.
- **The "we'll get back to you" that never comes.** The tracker's committed-response-date field prevents this — enforced by the daily monitoring.

## Acceptance criteria

You can demonstrate that:

- Workstream-owner map covers all 15 workstreams with primary, backup, and specialist assignments, plus weekly time allocation.
- Diligence-coordinator, sell-side-lead, and banker-liaison roles are defined.
- SLA document distinguishes three tiers with 3 examples each, plus interview-scheduling SLA and push-back-script sample.
- Q&A tracker schema is fully specified and implemented in a chosen tool.
- Confidential-communication-channel operating rules are documented.
- Escalation-to-executive rules are specific about triggers at each level.
- Proactive-disclosure policy is drafted with filter, rationales, categories, and choreography.
- Three-day simulated question flow covers at least 6 workstreams and 20+ questions with realistic mix of SLA tiers, escalations, and one proactive-disclosure item.
- Two proactive-disclosure packages are drafted with proposed treatment.
- Management-interview and reference-call choreography is documented.
- Scope-creep response document names the LOI-reference baseline and includes a specific push-back script.

## Reflection

Add a short reflection:

1. Which single workstream in your simulated flow consumed the largest fraction of sell-side capacity, and what does that suggest about pre-diligence-period preparation?
2. In your simulated flow, did any question surface a cross-workstream inconsistency? If yes, how did the sell-side lead's review catch it (or did it)?
3. For your two proactive-disclosure items, if you had chosen instead to answer-only-when-asked, what would the R&W-policy exclusion or disclosure-schedule outcome have been?
4. If the buyer's diligence lead escalated a specific complaint about response cadence (e.g., "your Financial workstream is slow"), what specific evidence from your tracker would you present in response?

## Stretch goals

- **Airtable / Notion tracker implementation with automations.** Build the tracker in Airtable or Notion with automated SLA-breach alerts, daily-summary email to the diligence coordinator, and weekly-report generation for the sell-side lead.
- **VDR-native Q&A comparison.** Compare your bespoke tracker to the Q&A modules of Ansarada, Datasite, and Intralinks. Note the trade-offs (auditability vs. customisation; vendor-lock-in vs. platform-neutrality).
- **The 200-question stress simulation.** Extend the simulation from 20–30 questions to 200+ questions over a 45-day window, with the workstream mix reflecting real-life diligence workflow (heavy first two weeks; commercial-diligence-driven ramp in weeks 2–3; specialist-driven late-cycle questions in weeks 4–6). Note how the tracker discipline scales.
- **Post-signing archive package.** Draft the post-signing tracker-export and archive package — the specific format, the retention requirements, the access-control transfer to seller-representative for post-close indemnity-dispute defence.
- **Reverse-simulation.** From the buyer's chair, take the specific 20–30-question flow you generated and score the sell-side's response quality. Where would you push back? Where would you press for more? What signals of seller reliability or unreliability do you pick up?
- **Live-transaction interview.** Interview a CFO or GC who has recently run a sell-side process about the specific operational realities of response management. Note what surprised you against your plan.
