# exercise-05: Diligence findings memo and price renegotiation

**Estimated effort:** 4–5 hours

## Objective

Turn a set of raw buy-side diligence outputs into a findings memo, propose specific price-adjustment mechanics against each material finding, and draft the negotiation script that delivers the re-trade without collapsing the deal.

The finished artefact is a diligence-findings memo (10–18 pages) in the internal-deal-team version, a sell-side extract (3–6 pages) with proposed treatments for negotiation, and a negotiation-playbook document (2–4 pages) that a corp-dev VP would use to run the negotiation call with the sell-side lead.

You should end the exercise able to defend every red / yellow / green code, every proposed treatment against alternative treatments, every choice between the four price-adjustment mechanics, and the specific choreography of the sell-side conversation.

## Background

This exercise covers material from:

- [Chapter 5 — Buy-Side Findings Memo and Price Renegotiation](../05-buy-side-findings-memo-and-price-renegotiation.md) — finding / evidence / impact / recommendation architecture, traffic-light coding, memo structure, material-vs-immaterial discipline, escalation-to-deal-team, four price-adjustment mechanics, negotiation choreography, deal-certainty vs. re-trade discipline.

Supporting references:

- [Chapter 4](../04-buy-side-diligence-workstream-design.md) for the workstream plan that produces the findings.
- [Chapter 3](../03-sell-side-diligence-response-management.md) for the confidential-channel choreography the buyer uses to sequence the sell-side conversation.
- [Chapter 6](../06-rw-underwriter-diligence-negotiation.md) for the R&W-considerations feedback loop.
- [mod-104 chapter 6](../../mod-104-loi-negotiation-and-definitive-agreements/06-indemnification-package-design.md) for the indemnification-package mechanics the findings memo's proposed treatments will land in.
- [mod-104 chapter 8](../../mod-104-loi-negotiation-and-definitive-agreements/08-deal-scale-negotiation-canon.md) for the negotiation-canon overlay.

## Prerequisites

- The buy-side workstream plan from exercise 4 (or an equivalent).
- Some raw diligence-output material to draw findings from. Options:
  - Continue with your hypothetical target and construct plausible findings from each workstream. This is the modal approach.
  - Use publicly-available disclosure schedules from a real merger-agreement filing (SEC EDGAR search for merger agreements with exhibit-filed disclosure schedules) as inspiration for finding types.
  - Draw on your own past-transaction experience where authorised.

## Tasks

### 1. Set the transaction context

Write a half-page context paragraph:

- Target and acquirer.
- LOI headline economics.
- Workstreams covered (from exercise 4).
- Timeline position (typically week 5 or 6 of an 8-week diligence period).
- Any specific-issues context from earlier proactive-disclosure by seller (chapter 3).

### 2. Construct the findings-log

Produce a findings-log of 15-to-30 findings across at least eight workstreams. For each finding:

- Workstream tag.
- One-sentence finding.
- One-sentence evidence pointer.
- One-sentence impact.
- Rough magnitude (bucketed: <$500K, $500K-$2M, $2M-$10M, $10M+).
- Preliminary traffic-light code (Red, Yellow, Green).

Cover a realistic mix — most findings should be Yellow or Green; 3-to-6 should be Red. Include at least one finding from each of:

- **Financial** — an EBITDA-adjustment dispute, a working-capital-target dispute, or a debt-like-item.
- **Legal / corporate** — a change-of-control-consent-requiring contract, an assignment-of-inventions chain-of-title gap, or a cap-table discrepancy.
- **Tax** — a sales-tax nexus exposure, a §174 R&D-capitalisation posture issue, or a §280G exposure warranting mitigation.
- **Commercial** — a customer-concentration risk, a churn signal, or a cohort-retention discrepancy against the sell-side view.
- **Technology** — a technical-debt finding, a key-person concentration, or an architecture concern.
- **HR / comp** — an executive change-of-control exposure, a wage-and-hour risk, or a contractor-classification concern.
- **Privacy / security** — a prior breach, an unremediated critical vulnerability, or a GDPR cross-border-transfer mechanism concern.
- **AI / model or OSS** — a training-data-provenance gap, a foundation-model-provider-terms concern, or an AGPLv3-in-SaaS-service finding.

### 3. Author 4-to-6 red findings in full finding / evidence / impact / recommendation format

For 4-to-6 of your red findings, draft the full four-field structure:

- **Finding.** Specific, factual, dated. Not evaluative.
- **Evidence.** Cite the specific data-room reference, interview date, or workpaper location. If inference from absence, state so explicitly.
- **Impact.** Quantified in dollars or percentages against the specific transaction dimension (purchase price, working-capital target, closing-cash / closing-debt, deferred-revenue treatment, specific-indemnity, escrow, R&W policy, integration cost, post-close operating risk).
- **Recommendation.** Specific action — purchase-price reduction of $X, specific-indemnity carve-out of $Y for exposure Z, escrow increase of $A held for B months, R&W-exclusion expectation, integration-plan action.

Each red-finding write-up should be 1-to-2 pages of concrete material.

### 4. Draft the memo executive summary

Produce a 1-page executive summary:

- Total findings by traffic-light (Red X, Yellow Y, Green Z).
- Top-3-to-top-5 red findings with headline impact (dollars) and proposed treatment (mechanic).
- Overall recommendation on transaction posture — proceed at LOI headline / proceed with adjustments (specify dollar magnitude) / material issues warrant reconsideration.
- Aggregate proposed price-adjustment package (headline number).

### 5. Draft the yellow-findings summary table

One-line per yellow finding:

- Workstream.
- Finding summary.
- Impact summary.
- Proposed treatment (disclosure-schedule entry, specific-indemnity carve-out, escrow increase, R&W exclusion, integration action).

### 6. Draft the green-findings appendix

Reference-only listing of green findings with workstream and one-line summary.

### 7. Draft the workstream-summary sections

One per in-scope workstream, one-half to one page each. Cover:

- Overall assessment (workstream-provider's read).
- Cross-reference to workstream's findings (red / yellow / green counts).
- Any workstream-level cross-cutting theme.

### 8. Draft the cross-cutting-themes section

If multiple workstreams surface a common underlying issue (e.g., three workstreams surface issues traceable to a single 2023 leadership departure that left holes in documentation), draft the theme section. If no cross-cutting theme surfaces, note that explicitly.

### 9. Draft the integrated price-adjustment proposal

Present the aggregate proposed adjustment as an integrated package against the LOI economics:

- Purchase-price reductions (which findings, dollar amounts, running total).
- Specific-indemnity carve-outs (which findings, exposure caps, survival periods).
- Escrow increases (dollar amounts, hold periods).
- R&W-exclusion coverage of specific findings.
- Integration-plan cost estimates (findings that translate into post-close cost).

Show the LOI headline number, the aggregate proposed adjustment, and the resulting adjusted headline.

### 10. Draft the R&W-policy considerations section

For each red finding, name:

- The R&W exclusion the finding is expected to drive.
- The alternative treatment if the underwriter accepts the finding within coverage (subject to sub-limit, elevated retention, or specific coverage-exception).
- The additional-diligence commitment that could bring the finding within coverage (e.g., wage-and-hour audit; state-tax nexus study; training-data-provenance audit).

### 11. Draft the integration-plan-input section

For findings that translate into post-close integration actions:

- Categorise by function (finance, HR, security, engineering, legal, sales).
- Estimate integration-action cost.
- Name the accountable integration workstream owner.

### 12. Author the sell-side extract

Produce a 3-to-6 page sell-side extract:

- The red findings only (in finding / evidence / impact / recommendation format).
- A summary of yellow findings.
- The integrated proposed treatment for each red.

Note what is excluded from the extract — the internal deal-team commentary, the workstream-provider assessments, the R&W-underwriter strategy discussion.

### 13. Author the negotiation playbook

Produce a 2-to-4 page negotiation playbook:

- **Step 1: Sell-side heads-up through the confidential channel.** The specific script for the buyer's lead call to the sell-side lead.
- **Step 2: Written findings package delivery.** The specific delivery-and-cover-note plan.
- **Step 3: Anticipation of sell-side internal review.** What the sell-side is likely to do; how the buyer's team readies for the counter.
- **Step 4: The negotiation call plan.** Attendees on both sides; agenda; time-boxing; role assignments (buyer's counsel, deal-team lead, banker's role).
- **Step 5: The negotiation itself.** For each red finding, the buyer's opening position, the anticipated sell-side counter (finding-disputed / treatment-disputed / aggregation-disputed), and the buyer's contingent response.
- **Step 6: Iterative rounds.** The rhythm of exchanges — expected number of rounds, expected concession pattern.
- **Step 7: The final package.** How the negotiated adjustments land in the definitive agreement — amended LOI, side letter, disclosure schedules, indemnity provisions.

Include the chapter-8 negotiation-canon overlay from mod-104:

- **The Freund frame.** Where in the definitive-agreement negotiation does this specific conversation sit — closing-conversation issue or earlier issue?
- **The Harvard frame.** What is the buyer's underlying interest (risk allocation) vs. position (specific price)? What is the seller's underlying interest (LOI-headline preservation, accelerated distribution) vs. position (specific rejection of adjustments)? Where is the interest-based middle ground?
- **The Voss frame.** What calibrated questions surface the seller's ability-to-absorb-adjustment and the seller's read on which adjustments are defensible vs. which are re-trade positioning?

### 14. Draft the deal-collapse decision framework

For your specific transaction, draft the deal-collapse decision framework:

- What findings, if surfaced, would exceed the buyer's risk-tolerance envelope and warrant deal-collapse?
- What is the specific escalation-to-CEO / board process?
- What would the alternative deal terms (very substantial price reduction, larger specific-indemnity, additional escrow) look like that could keep the deal alive as an alternative to collapse?
- What is the buyer's specific reputational-risk-calibration on invoking deal-collapse tactically?

## Starter guidance

Common findings-memo and price-renegotiation errors to avoid:

- **Over-flagging of red findings.** Every red is a demand for deal-team attention; too many reds exhaust attention and dilute signal. Reserve red for findings that materially change intrinsic value, create a risk that cannot be managed through general reps, or reveal a systemic operational issue.
- **Findings without recommendations.** A finding that answers "what did we find" but not "what do we do about it" is not a decision-actionable finding. Every finding, even yellow, has a proposed treatment.
- **Aggregation surprise.** Presenting findings individually without an aggregate view means the seller sees a Trojan-horse re-trade as each finding lands. Aggregate before the negotiation opens.
- **Aggressive opening position on the price-reduction path.** Opening with the top of a plausible range escalates to all-or-nothing. Open with the middle of the range, leave room to negotiate.
- **Buyer flinches from red-flagging.** The buyer's discomfort with confrontation leaves red findings mislabelled as yellow, which leaves the buyer holding uninsured risk post-close. The workstream provider's independent judgment holds.
- **Findings memo without R&W-considerations section.** Without the R&W-considerations section, the underwriter's exclusions memo lands as a surprise and the seller reads any subsequent specific-indemnity ask as bait-and-switch.
- **Founder-CEO in the tactical negotiation.** For founder-led targets, the price-renegotiation reads as personal validation. Keep the founder-CEO briefed but out of the tactical exchange.
- **Deal-collapse threat used tactically.** Threatening deal-collapse to extract a re-trade damages trust and, over time, damages the buyer's reputation in the practitioner community. Reserve for genuine deal-collapse triggers.

## Acceptance criteria

You can demonstrate that:

- Transaction context is written.
- Findings-log covers at least 15-to-30 findings across at least eight workstreams with realistic red / yellow / green mix.
- 4-to-6 red findings are drafted in full finding / evidence / impact / recommendation format.
- Executive summary is drafted at 1-page depth.
- Yellow-findings summary table is produced.
- Green-findings appendix is produced.
- Workstream-summary sections are drafted for each in-scope workstream.
- Cross-cutting-themes section is drafted (or explicit note that no theme surfaces).
- Integrated price-adjustment proposal shows LOI headline, aggregate adjustment, adjusted headline.
- R&W-policy considerations section names expected exclusions and alternative treatments per red finding.
- Integration-plan-input section categorises findings and estimates integration-action cost.
- Sell-side extract is drafted at 3-to-6 page depth.
- Negotiation playbook is drafted at 2-to-4 page depth with all seven steps and the chapter-8 negotiation-canon overlay.
- Deal-collapse decision framework is drafted for the specific transaction.

## Reflection

Add a short reflection:

1. Which single red finding was the hardest to code — where the material / immaterial line was ambiguous — and how did you resolve it?
2. If your integrated proposed adjustment exceeds 10% of LOI headline enterprise value, does the transaction economics still work for the acquirer? For the seller?
3. Which of the four price-adjustment mechanics (purchase-price reduction, specific-indemnity carve-out, escrow increase, deal-collapse) did you use most, and why?
4. If the sell-side's initial response to your findings package is "we reject all adjustments and threaten to walk," what is your next move?

## Stretch goals

- **Sell-side counter-package draft.** Swap seats — take your buyer-side findings memo and, from the seller's chair, draft the sell-side counter-package. Which findings do you accept? Which do you dispute? Which do you counter-propose on treatment? The exercise reinforces the negotiation-canon disciplines.
- **Two-buyer variant.** For a target with two active buyers (unusual after LOI signing but happens in structured-process endings), how does the negotiation choreography change? Does the seller use the second buyer as leverage against the primary's re-trade? What are the specific risks of doing so?
- **Historical-transaction reconstruction.** Retrieve a specific publicly-filed merger agreement (SEC EDGAR) with a disclosure schedule and any known price-adjustment history. Reconstruct the findings-memo-that-produced-the-adjustments, and compare to your findings-memo authoring approach.
- **Integration-planning cost detail.** For the integration-plan-input section, draft the specific integration-plan-cost detail for the first-100-day plan — the specific hires, contractor engagements, remediation-project costs, and internal-team time allocations. Feed to mod-111 preparation.
- **Post-signing negotiation-effectiveness retrospective.** Draft the template the buyer's deal team would use post-signing to evaluate the negotiation's effectiveness — which findings were accepted at proposed treatment, which were negotiated down, which were withdrawn, which were traded for other concessions. Feed into future findings-memo authoring practice.
- **Multi-language sell-side.** For a target with primary operations in a non-English jurisdiction (Germany, Japan, Israel, India), the negotiation choreography includes translation, cultural-frame differences, and negotiation-canon-variance considerations. Draft the specific adaptations.
