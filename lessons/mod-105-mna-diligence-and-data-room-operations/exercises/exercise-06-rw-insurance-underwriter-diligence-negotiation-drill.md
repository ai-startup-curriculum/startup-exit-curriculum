# exercise-06: R&W insurance underwriter diligence negotiation drill

**Estimated effort:** 4–5 hours

## Objective

Prepare the R&W underwriter-diligence-review call agenda for a specific hypothetical transaction, negotiate the exclusions memo against a specific set of diligence findings, and model the retention / premium / coverage impact of three exclusion-negotiation positions.

The finished artefact is an underwriter-review-preparation package (agenda, workstream-quality summary, driver-of-value memo, findings-map — 6–10 pages), a simulated exclusions memo with draft negotiation responses (4–8 pages), and a retention-premium-coverage-impact model (Excel or Google Sheets) showing three alternative negotiated outcomes.

You should end the exercise able to defend the review-call agenda against the underwriter's likely probes, defend the specific exclusion-narrowing language, defend the choice between accepting an exclusion and negotiating a specific-indemnity carve-out from the seller, and defend the trade-off decisions on retention / premium against coverage breadth.

## Background

This exercise covers material from:

- [Chapter 6 — R&W Insurance Underwriter Diligence Negotiation](../06-rw-underwriter-diligence-negotiation.md) — underwriter-engagement timeline, underwriter's diligence-review call, exclusions memo, typical exclusion categories (cyber, wage-and-hour, tax positions in dispute, FCPA, AI-model-training-data), exclusions negotiation, underwriter-driven diligence expansion, retention / premium / coverage impact of diligence quality, trade-off decisions back to the deal team, coordination with sell-side, seller-side R&W variant.

Supporting references:

- [Chapter 4](../04-buy-side-diligence-workstream-design.md) for the workstream plan that anchors the review.
- [Chapter 5](../05-buy-side-findings-memo-and-price-renegotiation.md) for the findings memo that feeds the underwriter.
- [Chapter 7](../07-ai-model-and-open-source-diligence.md) for the AI-and-OSS specifics.
- [mod-104 chapter 7](../../mod-104-loi-negotiation-and-definitive-agreements/07-rw-insurance-mechanics.md) for R&W insurance mechanics generally.
- [mod-104 exercise 7](../../mod-104-loi-negotiation-and-definitive-agreements/exercises/exercise-07-rw-insurance-vs-traditional-indemnity-analysis.md) for the R&W-vs-traditional analysis that decides the placement question.

## Prerequisites

- The buy-side workstream plan from exercise 4 (or an equivalent).
- The findings memo from exercise 5 (or an equivalent).
- A working understanding of R&W insurance economics — retention, premium (rate on line), coverage limit, exclusions. Review mod-104 chapter 7 if unfamiliar.
- A spreadsheet for the impact model.
- The current-cycle Marsh, Aon, WTW, Lockton, and Woodruff Sawyer R&W market reports for premium ranges, retention levels, and exclusion trends.
- Where possible, an introductory conversation with an R&W-insurance broker — brokers routinely offer indicative-quote conversations at no cost.

## Tasks

### 1. Set the transaction-and-underwriter baseline

Write a 1-page baseline covering:

- Target and acquirer.
- LOI headline economics.
- Expected R&W policy sizing (limit typically 10-20% of enterprise value; defend the specific choice).
- Expected retention (1% dropping to 0.5% at 12 months as standard baseline; defend any variance).
- Expected premium range (rate on line 2%-5% as standard baseline; defend any variance).
- Diligence quality (light / standard / robust) with rationale from exercise 4.
- Broker (Marsh, Aon, WTW, Lockton, Woodruff Sawyer, CAC Specialty, HUB, or mid-tier).

### 2. Prepare the underwriter-review-call agenda

Produce a 2-page agenda covering all workstreams the underwriter will probe. For each workstream, name the buyer-side attendee (workstream owner or provider representative), the deliverable that will be walked, the probable underwriter probe topics, and the buyer-side defensive readiness.

Cover at minimum:

- Financial (buy-side QoE).
- Legal (corporate).
- Tax.
- Commercial.
- Technology / product.
- IP.
- HR / comp.
- Privacy.
- Security.
- AI / model.
- Open source.
- Regulatory.
- Environmental (if applicable).
- Insurance stack.

For each, name the two-to-three key questions the underwriter is most likely to press.

### 3. Draft the workstream-quality summary

Underwriters underwrite diligence quality, not just diligence existence. Produce a 1-page workstream-quality summary:

- Provider name and reputation per workstream.
- Scope and depth summary per workstream (a materiality-threshold statement, a "top-N by ARR" or "top-N by contract-value" cut, coverage assertion).
- Personnel-level per workstream (partner-level, senior-manager-level, sector-specialist).
- Any workstream that under-scoped (with rationale — cost, timeline, targeted risk-tolerance).

### 4. Draft the driver-of-value memo

Produce a short driver-of-value memo (1-2 pages) mapping the target's key value drivers to the workstreams that inspected them:

- Value driver (e.g., customer base, technology stack, IP portfolio, AI-model capability, sales-team capacity).
- Workstream(s) that inspected the driver.
- Coverage assertion (fully inspected / partially inspected / not inspected — with rationale for any gap).

### 5. Draft the findings-map for the underwriter

Produce a findings-map derived from your exercise-5 findings memo, sanitised for the underwriter view:

- Red findings by workstream with brief characterisation and proposed deal-side treatment.
- Yellow findings summary count.
- Green findings summary count.
- Any findings the buyer expects to drive an exclusion.

### 6. Simulate the underwriter's exclusions memo

Produce a simulated exclusions memo that a typical underwriter would issue after reviewing your prepared materials:

- **Standard policy exclusions.** Fraud (with the mod-104 chapter 7 buyer-preserved carve-out for seller-side fraud), forward-looking statements, purchase-price-adjustment mechanics, breach-of-covenant, specific-jurisdiction restrictions, no-claims-known-at-signing.
- **Specific-issue exclusions.** Draw 4-to-8 specific exclusions from your findings memo — the $2.3M sales-tax nexus exposure, the AGPLv3-in-shipped-product finding, the pending customer litigation, the training-data-provenance gap, the pre-close breach event, the wage-and-hour PAGA exposure.
- **Category exclusions.** Wage-and-hour PAGA broad exclusion, IRC §280G excise-tax exposure, tax positions in dispute broadly, cyber prior-breach broadly (with sub-limit alternatives), AI-model IP claims broadly.
- **Conditional exclusions.** 1-to-3 items where coverage is contingent on additional-diligence completion.
- **Sub-limits.** 1-to-3 items where coverage is offered at a lower limit than the aggregate.
- **Territorial exclusions.** Any jurisdiction-specific exclusions (e.g., Russia, Iran, other current-cycle sanctioned jurisdictions).

The simulated exclusions memo should be realistic — a underwriter's opening position, not a final one.

### 7. Draft the exclusions-negotiation response

For each specific-issue exclusion and each category exclusion, draft the buyer-broker's negotiation response:

- **Narrowing language.** Propose specific tightening of the "arising from or related to" language.
- **Sub-limits as alternative.** Where full exclusion is proposed, counter with a sub-limit at a specific dollar level.
- **Additional-diligence commitment.** Propose the specific additional-diligence work that would bring the item within coverage (with rough cost and timeline).
- **Elevated-retention alternative.** For categories where a full exclusion is not warranted, propose an elevated retention on the specific category as an alternative.
- **Coverage-exception carve-out.** Propose specific carve-outs within the broader exclusion (e.g., excluding AI-model IP claims *other than* copyright-in-training-data specifically).
- **Seller-side specific-indemnity fallback.** Where the exclusion holds, name the specific-indemnity ask the buyer will bring back to the seller.

For each response, note the underwriter's likely counter and the buyer-side follow-up.

### 8. Draft the additional-diligence commitments

For each conditional exclusion that the buyer is willing to accept the additional-diligence work to unlock:

- **Wage-and-hour audit.** Scope (California employees; specific-issue focus areas — meal-and-rest-break, overtime, exempt / non-exempt); provider; timeline; cost.
- **State-tax nexus study.** Scope (states where target has activity threshold); provider; timeline; cost.
- **Anti-corruption programme audit.** Scope (third-party-due-diligence sample; training records; code and policy review); provider; timeline; cost.
- **AI-model-training-data audit.** Scope (in-scope models; training-data-source review; foundation-model-vendor-terms review); provider; timeline; cost. See chapter 7.
- **Cyber deep-dive.** Scope (red team; specific pen-test); provider; timeline; cost.

For each, note whether the buyer commits or accepts the exclusion. Justify the cost-benefit trade-off.

### 9. Model the retention / premium / coverage impact of three negotiated outcomes

Produce a 3-scenario model:

**Scenario A — accept-all-exclusions.** The buyer accepts the underwriter's opening exclusions memo without negotiation. Model:

- Retention (baseline).
- Premium (baseline).
- Coverage limit (baseline).
- Effective coverage (baseline coverage minus exclusion exposure).
- Aggregate buyer-side risk exposure across excluded matters (sum of exclusion-exposure estimates).
- Aggregate specific-indemnity ask from seller across excluded matters.

**Scenario B — negotiate-hard.** The buyer runs an aggressive negotiation on every exclusion — narrow language, sub-limit alternatives, additional-diligence commitments, coverage-exceptions. Model:

- Retention (possibly reduced if diligence quality strong).
- Premium (possibly reduced or unchanged; some additional-diligence commitment adds cost).
- Coverage limit.
- Effective coverage.
- Aggregate buyer-side risk exposure across residual exclusions.
- Aggregate specific-indemnity ask from seller across residual exclusions.
- Additional-diligence commitment cost.

**Scenario C — targeted-negotiation.** The buyer negotiates aggressively on the 2-to-3 highest-exposure exclusions and accepts the balance. Model:

- Retention.
- Premium.
- Coverage limit.
- Effective coverage.
- Aggregate buyer-side risk exposure.
- Aggregate specific-indemnity ask from seller.

Present a comparison table across the three scenarios. Recommend the scenario the buyer should pursue with rationale.

### 10. Draft the trade-off-decisions memo

For each residual exclusion (after negotiation), decide the deal-team path (chapter 6):

- **Path A — buyer bears the risk uninsured.**
- **Path B — seller-side specific-indemnity carve-out.**
- **Path C — separate specialty insurance (cyber, EPLI, environmental, pollution-legal-liability).**

For each residual exclusion, name the chosen path with rationale. Aggregate the total specific-indemnity ask that goes back to the seller.

### 11. Draft the sell-side coordination plan

Chapter 6's "coordination with the sell-side" section develops this. Draft:

- **Confidential-channel briefing script.** The specific message the buyer's deal-team lead delivers to the sell-side lead about the underwriter's exclusions trajectory.
- **Specific-finding sharing.** The specific findings the buyer shares with the seller in advance of the specific-indemnity ask.
- **Seller-side provider-preparation ask.** For findings driving specific exclusions (Q of E-driven, tax-driven, IP-driven), the specific defensive materials the seller's provider should prepare that could narrow the exclusion.
- **Sell-side-in-the-room decision.** For which specific workstreams (typically Q of E, tax) would the sell-side attend the underwriter-review call directly?

### 12. Draft the specialty-insurance coordination plan

For any excluded categories the buyer decides to cover through separate specialty insurance, draft the coordination:

- Cyber-insurance policy (retention, coverage, incident-response provisions, breach-notification, prior-acts coverage).
- Environmental-insurance (Pollution Legal Liability policy for property-linked exposure).
- EPLI (Employment Practices Liability Insurance for wage-and-hour and other employment claims).
- D&O tail (mod-104 chapter 7 references this — the tail placed at closing to cover pre-close acts).

## Starter guidance

Common underwriter-diligence-negotiation errors to avoid:

- **Late underwriter engagement.** Engagement at week 6 of diligence with signing at week 9 leaves no room for exclusions negotiation. Engage at LOI signing; run parallel.
- **Under-scoped buy-side diligence exposed at the review call.** Workstreams under-scoped for cost end up as exclusions or conditional exclusions requiring additional diligence — often paying more in additional-diligence cost than the workstream scope-expansion would have cost.
- **Broker running the negotiation without deal-team escalation.** A junior broker or associate accepting a broad PAGA or cyber exclusion without escalating loses coverage the deal team wanted. Deal-team review of every exclusion.
- **Additional-diligence commitment without cost-benefit analysis.** Committing to a $500K training-data-provenance audit to unlock $2M of sub-limit coverage may not be a good ROI trade; run the numbers.
- **Sub-limit-vs-exclusion trade-off unexamined.** Sub-limits are often preferable to exclusions — better to have partial coverage than none — but not always if the sub-limit is set so low it delivers no meaningful coverage against the actual exposure.
- **Seller surprise on specific-indemnity ask.** A specific-indemnity ask driven by an R&W exclusion that the seller has no advance visibility to reads as bad-faith. Confidential-channel coordination pre-empts.
- **Failure to place specialty coverage.** Accepting a cyber exclusion and then forgetting to place a cyber policy leaves the buyer uninsured. Coordinated insurance-stack design.

## Acceptance criteria

You can demonstrate that:

- Transaction-and-underwriter baseline is written.
- Underwriter-review-call agenda covers all workstreams with attendee, deliverable, probe topics, and defensive readiness.
- Workstream-quality summary names provider, scope, and personnel per workstream.
- Driver-of-value memo maps value drivers to workstreams with coverage assertions.
- Findings-map for the underwriter is drafted from the exercise-5 findings memo.
- Simulated exclusions memo covers standard, specific-issue, category, conditional, sub-limit, and territorial exclusions.
- Exclusions-negotiation response is drafted for each specific-issue and category exclusion with narrowing / sub-limit / additional-diligence / elevated-retention / coverage-exception / seller-side-fallback alternatives.
- Additional-diligence commitments are drafted with scope, provider, timeline, cost, and commit-vs-accept-exclusion decision.
- Retention / premium / coverage impact model covers three scenarios with quantified comparison.
- Trade-off-decisions memo assigns each residual exclusion to path A, B, or C with rationale.
- Sell-side coordination plan includes confidential-channel briefing, specific-finding sharing, seller-side provider-preparation ask, and sell-side-in-the-room decision.
- Specialty-insurance coordination plan covers any excluded categories moved to separate placement.

## Reflection

Add a short reflection:

1. Which single exclusion drove the largest reduction in effective coverage, and how did you close (or accept) the gap?
2. If the underwriter's initial exclusions memo held firm through negotiation with no concessions, what would the deal-team's residual choice look like — proceed and pass the exposure to seller, proceed and bear the exposure, or delay signing to bring in a second underwriter?
3. For the additional-diligence commitments you made, which one was the tightest cost-benefit trade, and how did you decide?
4. If the target were an AI-first company with unresolved training-data-provenance gaps, would the R&W underwriter's exclusion trajectory make the deal untenable for a first-time acquirer, or would it just reshape the seller-side specific-indemnity package?

## Stretch goals

- **Live broker-outreach conversation.** Schedule a 30-minute conversation with a broker at Marsh, Aon, WTW, Lockton, Woodruff Sawyer, or a mid-tier specialist. Request an indicative NBI for your specific transaction facts. Compare the actual quote and exclusion posture to your model.
- **Two-underwriter competitive-bidding simulation.** Model the exclusions and premium under two underwriters competing for the transaction. Note the specific line items each underwriter's culture / posture tends toward.
- **Sub-limit-mathematics deep-dive.** For the categories with sub-limit coverage (typically cyber, tax), model the specific exposure distribution — what portion of the underlying risk does the sub-limit cover? What is the buyer-side risk-transfer efficiency?
- **AI-model-training-data-exclusion negotiation deep-dive.** For an AI-first target, draft the specific coverage-exception negotiation you would run to bring AI-model-training-data risk within coverage. Consider the OpenAI Copyright Shield / Anthropic IP indemnity / Google Generative AI Indemnity as upstream-indemnity-anchoring evidence.
- **Sell-side-in-the-room simulation.** Simulate the specific Q of E section of the underwriter-review call with the sell-side Q of E provider present. What does the exchange look like? How does the underwriter's probe change with the sell-side provider in the room?
- **Historical-transaction R&W-policy binder review.** Retrieve a publicly-filed R&W policy binder (some large public-target M&A files include the R&W policy in the exhibits). Study the specific exclusion language and compare to your simulated exclusions memo.
- **Post-signing exclusion-negotiation retrospective template.** Draft the template the buyer's deal team would use post-signing to evaluate the exclusions-negotiation's effectiveness — which exclusions were successfully narrowed, which held firm, which cost more in additional-diligence than they returned in coverage, which drove sell-side friction. Feed into future underwriter-diligence-negotiation practice.
