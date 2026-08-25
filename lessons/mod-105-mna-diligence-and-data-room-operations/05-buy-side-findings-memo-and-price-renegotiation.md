# Buy-Side Findings Memo and Price Renegotiation

## Why this matters

Diligence findings only matter to the extent they land inside a document a decision-maker reads and reason about. A findings-log with 400 entries is not a decision artefact; it is raw material. The *diligence-findings memo* is the artefact — the two-to-twenty-page synthesis, structured around a specific analytic architecture, that goes to the buyer's deal team, financing committee, board, and (in a modified form) to the sell-side. It is where diligence work becomes deal action: the findings memo either preserves the LOI headline price, drives a defensible price re-trade, triggers a specific-indemnity carve-out, prompts an escrow increase, or (in the extreme case) collapses the deal. It is also the document the R&W underwriter reads to underwrite the general representations, and the document the deal team hands to the integration-planning team as the input to the first-100-day plan.

Beyond the memo, the buy-side has to *use* the findings — to negotiate. The price-renegotiation conversation between LOI signing and definitive-agreement signing is the single moment in a modern venture-M&A transaction where a mid-sized deal team's negotiation skill visibly moves purchase-price dollars. Handled well, a $50M–$200M deal absorbs a $2M–$20M re-trade or a comparable value shift through indemnity structure while both parties feel the outcome is defensible. Handled badly, the same finding either collapses the deal (the seller walks because the re-trade feels like a bait-and-switch) or extracts nothing (the buyer flinches from the confrontation and closes at the LOI headline while eating the risk uninsured).

This chapter installs the findings-memo architecture and the price-renegotiation choreography. The negotiation-canon frameworks (Freund's *Anatomy of a Merger*, Fisher / Ury / Patton, Voss) referenced in mod-104 chapter 8 apply directly here — the price-renegotiation conversation is one of the specific M&A conversations that canon addresses.

## The finding / evidence / impact / recommendation architecture

The dominant practitioner-preferred structure for a diligence finding is a four-field pattern:

**Finding.** A single sentence naming what was found. Specific, factual, dated. Not evaluative. Not conclusory.

**Evidence.** The specific documents, interviews, or analyses that support the finding, cited to the data-room file or workpaper location. If the finding rests on inference from absence-of-evidence (which is legitimate but weaker), that is stated explicitly.

**Impact.** The quantified or qualified effect of the finding on the transaction. Quantified where possible (a dollar range, a percentage range, an exposure estimate). Qualified where quantification is not defensible (a categorical risk description with the reasoning). Impact is expressed against a specific transaction dimension — purchase-price, working-capital-target, closing-cash / closing-debt bridge, deferred-revenue treatment, specific-indemnity coverage, escrow sizing, R&W policy exclusion, integration-plan cost, post-close operating risk.

**Recommendation.** The specific action the diligence provider recommends. Not "the buyer should consider" — a specific action: reduce purchase price by $X, add a specific-indemnity carve-out for exposure Y, increase escrow by $Z, exclude issue A from R&W coverage and negotiate a specific escrow, defer the finding to post-close integration action.

Example:

> **Finding.** Target's customer contract with CustomerAlpha (representing 14% of ARR) contains a change-of-control provision requiring the customer's written consent to the transfer of the contract in a change-of-control event.
>
> **Evidence.** CustomerAlpha MSA dated 2021-06-15, Section 12.4 (data room reference: 04-01-CUSTOMER_CustomerAlpha-MSA-2021-06-15-EXEC.pdf). Verified in interview with target's VP of Customer Success on 2025-09-10. Consent has not been requested as of the date of this memo.
>
> **Impact.** Absent CustomerAlpha's consent, the transaction may trigger a right for CustomerAlpha to terminate the contract. Termination would remove approximately $2.1M ARR (14% of the target's ARR base of $15M). Applied at the transaction's implied 8× ARR multiple, the exposure is approximately $16.8M of enterprise value.
>
> **Recommendation.** (a) Add a closing condition requiring CustomerAlpha's consent to the change of control. (b) Add a specific-indemnity carve-out covering any loss arising from CustomerAlpha's termination for change-of-control in the first 24 months post-close. (c) Retain $5M of purchase price in a specific escrow for 24 months, releasing on the earlier of CustomerAlpha's positive renewal or the 24-month anniversary.

The architecture forces a specific thinking discipline: every finding has to answer "what does this mean for the deal" and "what do we do about it." Findings that cannot answer both are not action-worthy findings; they belong in an appendix or a post-close-integration-action list, not in the primary findings memo.

## Traffic-light coding and prioritisation

Practitioner memos typically apply a traffic-light or risk-tier code to each finding:

- **Red.** Material finding. Warrants deal-team escalation and typically drives a price / indemnity / structure conversation. A red finding is significant enough that the deal-team's decision to close *at all* is affected.
- **Yellow.** Moderate finding. Warrants a disclosure-schedule entry and often a specific-indemnity carve-out or escrow increase, but does not by itself change the decision to close.
- **Green.** Informational finding. Does not change deal terms. Feeds into the disclosure schedule or the integration plan as background.

The traffic-light code is a communication device — the deal team's exec summary shows the count of red / yellow / green findings, the details of every red, a summary of yellows, and an appendix for greens. It is not a substitute for the finding-by-finding analysis; the underlying finding / evidence / impact / recommendation structure remains authoritative.

The code is also *defensible*. The workstream provider — the QoE firm, the M&A counsel, the tech-diligence firm — is standing behind the red / yellow / green assignment. When a finding is coded Red, the deal team engages substantively; when it is coded Green, the deal team can safely deprioritise it. Providers who over-flag every finding as Red exhaust the deal team's attention and dilute the signal; providers who under-flag Red findings can miss items that later become post-close problems.

## Structuring the diligence-findings memo

The typical structure of a diligence-findings memo:

- **Executive summary.** One page. Total findings count by traffic-light. Top-3 to top-5 red findings with headline impact. Overall recommendation on transaction posture (proceed at LOI headline / proceed with adjustments / material issues warrant reconsideration).
- **Transaction context.** Half-page. Transaction overview, LOI headline economics, workstreams covered, workstreams deferred (with reason), material assumptions.
- **Red findings, one per section.** Full finding / evidence / impact / recommendation for each, plus proposed deal-side treatment.
- **Yellow findings, tabular.** One-line per finding: workstream, finding, impact summary, proposed treatment (disclosure schedule, specific-indemnity, escrow, R&W exclusion, integration action).
- **Green findings, appendix.** Reference-only.
- **Workstream summary sections.** One per workstream, summarising the workstream's overall assessment and cross-referencing the findings tagged to that workstream.
- **Cross-cutting themes.** If multiple workstreams surface a common underlying issue (e.g., three workstreams surface issues traceable to a single 2022 leadership departure that left holes in documentation), the theme is called out.
- **Price-adjustment proposal.** The specific proposed adjustment to purchase price, working-capital target, closing-cash / closing-debt bridge, escrow sizing, and indemnity package, presented as an integrated proposal against the LOI economics.
- **R&W-policy considerations.** The findings that will drive R&W-policy exclusions, the findings that will complicate underwriting, the findings the R&W underwriter is likely to require additional diligence on.
- **Integration-plan input.** The findings that translate into post-close integration actions.

For a large or complex deal, the memo can be 20+ pages; for a straightforward mid-market deal, 8–12 pages is typical. Longer is not better — the deal team should be able to read the memo in an hour and make decisions from it.

## Material vs. immaterial — the buyer's discipline

The buyer's practitioner discipline is to distinguish rigorously between findings that are material and findings that are not. Two anti-patterns to guard against:

- **The provider's incentive to over-produce findings.** A diligence provider charging $250K for a workstream has an incentive to produce a large, detailed report showing thorough work. This produces long yellow-and-green sections that consume deal-team attention without moving the deal. The buyer's deal team pushes back — "give us the findings that matter, in the volume they warrant."
- **The buyer's discomfort with confrontation.** The buyer's deal team, particularly at less-experienced acquirers, may flinch from labelling a finding Red because the Red label triggers a price-renegotiation conversation the deal team does not want to have. This is a failure mode that leaves the buyer holding uninsured risk post-close. The counter-discipline is the workstream provider's independent judgment — the QoE firm calls a Red a Red regardless of whether the buyer wants to raise it with the seller.

A useful test: for a finding to be Red, the finding has to either (a) materially change the intrinsic value of the target (a customer that would churn on change-of-control representing 14% of ARR), (b) create a material risk that cannot be managed through disclosure schedules and general reps (a specific IP claim, an unremediated critical security vulnerability, an open regulatory investigation), or (c) reveal a systemic issue in the target's operations that raises broader concerns (a controllership gap that suggests the financials themselves are unreliable, an HR-management gap that suggests a coming wave of employment claims).

## Escalation to the deal team

The findings memo is not the first time the buyer's deal team hears about a red finding. Practitioner discipline is *early escalation* — the moment a workstream provider identifies a likely red finding, they escalate to the buyer-side deal-team lead within 24 hours, without waiting for the formal memo. This lets the deal team:

- **Initiate the confidential-channel conversation with the sell-side lead** (chapter 3) to test the sell-side's view of the finding before it hits the formal memo.
- **Request additional diligence** where the finding is preliminary and further investigation could change the assessment (e.g., "the finding rests on absence of evidence for the assignment-of-inventions agreement of the co-founder; can we go find the agreement before we call this Red?").
- **Begin thinking about the price-adjustment or indemnity proposal** so the memo lands with a proposed treatment rather than an open question.
- **Escalate to the acquisition committee or board** if the finding is potentially deal-collapsing.

Early escalation does *not* mean the workstream provider commits to a specific characterisation before completing the analysis; it means the provider gives the deal team a heads-up on emerging concerns so the deal team is not surprised by the memo.

## The four price-adjustment mechanics

When a finding warrants a deal-side response, the buyer has four primary mechanics for addressing it. Choosing the right mechanic is the negotiation heart of the price-renegotiation conversation.

### 1. Purchase-price reduction

The most direct mechanic — reduce the enterprise value or equity purchase price by an amount corresponding to the finding's economic impact. Applied when the finding reduces the *intrinsic value* of the target — the QoE identifies EBITDA adjustments that reduce run-rate EBITDA by $X, and the buyer proposes a purchase-price reduction equal to $X times the LOI multiple; a commercial-diligence finding identifies a specific customer whose imminent churn will reduce ARR, and the buyer proposes a purchase-price reduction equal to the lost ARR times the LOI multiple.

**Advantages.** Clean, immediately-in-effect at closing, no ongoing management overhead, no dispute risk.

**Disadvantages.** Fully absorbed by the seller — every dollar comes out of seller proceeds. Larger reductions are harder for the seller to accept.

**Typical size.** For a mid-market deal, a purchase-price reduction is often in the $1M–$10M range for a specific finding; larger reductions imply either a very material finding or a re-trade that fundamentally alters the deal-value narrative and may trigger deal-collapse dynamics.

### 2. Specific-indemnity carve-out

The seller (typically through the seller-representative structure and the escrow) provides a specific indemnity for the identified issue — the seller bears the loss if the specific risk materialises post-close, up to a specific cap and for a specific duration. Applied when the finding is a *contingent* risk — the customer may or may not churn on change-of-control; the IP claim may or may not succeed; the tax position may or may not be sustained on examination.

**Advantages.** Aligns risk with the party best positioned to know whether the risk materialises. Preserves LOI headline price and the seller's headline economics. Does not require the buyer to price a probability-weighted expected loss (which the buyer would inevitably discount conservatively).

**Disadvantages.** Requires the seller to leave money at risk post-close. Creates ongoing dispute-risk about whether the specific loss falls within the carve-out. Requires the seller-representative structure to support the ongoing management (see mod-104 chapter 6 for the indemnification-package mechanics).

**Typical size.** Specific-indemnity carve-outs are typically capped at the specific exposure (or a multiple of it) with a specific survival period (often longer than general-rep survival). Uncapped specific-indemnities are unusual and typically reserved for fundamental issues (tax, pre-close-taxes, IP-chain-of-title, environmental).

### 3. Escrow increase

The buyer retains a larger portion of the purchase price in escrow (or extends the escrow duration) to cover the specific-indemnity exposure. Applied in combination with the specific-indemnity carve-out when the buyer wants the specific indemnity backed by escrow rather than by the seller's unsupported credit.

**Advantages.** Provides direct cash backing for the specific-indemnity, removes seller-credit risk from the buyer's calculus, avoids the more-contentious "top-up" mechanic where a seller who has already dispersed proceeds is asked to pay from personal funds.

**Disadvantages.** Ties up seller proceeds for the escrow period. The seller pays a real time-value cost. For selling stockholders who are individuals with personal-tax deadlines, the escrow-holding period can create tax-timing mismatches.

**Typical mechanics.** For a finding driving a $5M specific-indemnity, a corresponding $5M specific-escrow (separate from the general-indemnity escrow) held for 24–36 months (longer than general-rep survival) is a modal structure.

### 4. Deal-collapse trigger

The rare-but-real fourth mechanic — the buyer walks. Applied when a finding reveals a material issue that changes the underlying deal thesis, exceeds the buyer's risk-tolerance envelope, or reveals seller-misconduct in the LOI representations that undermines trust in the entire process.

**When it happens.** Discovery of previously-undisclosed material litigation. Discovery of previously-undisclosed material financial-statement misstatement. Discovery of a fundamental IP-ownership defect. Discovery of a regulatory violation with material forward exposure. Discovery of a security incident with material data-loss during the diligence period. Discovery of seller-side misrepresentation in the CIM or the LOI reps.

**Choreography.** Deal-collapse is rarely announced abruptly; it typically starts as a "we need to have a fundamental conversation about whether this deal proceeds" from the buyer's lead to the sell-side lead, followed by an escalation to founder-CEO and board on the sell-side. The seller sometimes has an opportunity to change the deal terms (a very substantial price reduction, a much larger specific-indemnity structure, additional escrow) to keep the deal alive; sometimes the buyer's decision is made and the deal-collapse conversation is a courtesy notification.

**Consequences.** The exclusivity period lapses (or the seller terminates the LOI for the buyer's material breach if the deal-collapse is on the buyer's side). The seller returns to the market — with a stale bidder set, a truncated timeline, and a story to tell about why the prior deal collapsed. Reputational damage on both sides. This is why deal-collapse is the mechanic of last resort; the specific-indemnity + escrow + purchase-price-reduction stack is preferable in almost every case where it can accommodate the finding.

## The negotiation choreography

The price-renegotiation conversation is a specific set of moves that has stabilised in practitioner practice:

**Step 1: Sell-side heads-up through the confidential channel.** The buyer's lead calls the sell-side lead (chapter 3): "we're going to be sending you a set of diligence findings tomorrow. Two of them are Red. We'll want to have a conversation about the deal-side implications. Nothing to react to yet — we wanted to give you a heads-up." This preserves the sell-side's dignity and prevents the "I was blindsided" narrative.

**Step 2: Written findings package delivered.** The buyer sends the findings-memo excerpt (typically the red findings only, plus a summary of yellows) to the sell-side lead. Format is a written memo, not a phone call — the seller needs to read, digest, and respond deliberately. The buyer includes a *proposed deal-side treatment* for each finding — the specific price adjustment, indemnity carve-out, escrow increase, or R&W exclusion the buyer is proposing.

**Step 3: Sell-side internal review.** The sell-side lead reviews with M&A counsel, the CFO, the founder-CEO, and (for material items) the board. The sell-side develops a response — accept, counter-propose, dispute.

**Step 4: The negotiation call.** A dedicated call (or a series) with the buyer's deal-team lead, the buyer's M&A counsel, the sell-side lead, and the sell-side's M&A counsel. Bankers on both sides typically attend. The founder-CEO is *sometimes* on the call for material items but more often is briefed before-and-after and stays off the tactical negotiation.

**Step 5: The negotiation itself.** Each finding is worked through against the proposed treatment. The negotiation typically breaks into three patterns:
- **The finding itself is disputed.** The sell-side provides additional evidence or a re-characterisation that changes the finding. The buyer's provider re-evaluates. The finding is either withdrawn, re-scoped, or confirmed.
- **The finding is accepted, the treatment is disputed.** The sell-side agrees the finding is real but disputes the buyer's proposed treatment — "the finding is real; the exposure isn't $16.8M, it's $4M because CustomerAlpha's contract has a 12-month notice period; the appropriate treatment is a $4M specific escrow for 24 months, not the $16.8M price reduction the memo proposes."
- **The finding and treatment are accepted, the *aggregation* is disputed.** The seller looks at the total of all proposed treatments — $8M price reduction, $12M specific escrow, three specific-indemnity carve-outs, an R&W exclusion — and pushes back on the aggregate: "individually each is defensible; in aggregate this is a re-trade that changes the deal thesis. We need to look at the whole package."

**Step 6: Iterative rounds.** Rarely does the price-renegotiation resolve in one call. Typically two-to-four rounds of exchange between LOI signing and definitive-agreement signing, with each round narrowing the differences.

**Step 7: The final package.** The negotiated adjustments are documented — in an amended LOI, in a specific "adjustments" side letter, or in the disclosure schedules and indemnity provisions of the definitive agreement. The final package is presented to both sides' boards for approval.

## Fine art — using diligence to preserve deal certainty rather than kill the deal

Practitioner discipline distinguishes the buyer that *uses* diligence to allocate risk from the buyer that *uses* diligence to re-trade the price. Both are legitimate; the second is more contentious and can damage trust to the point of collapsing the deal.

The disciplines that preserve deal certainty:

- **Distinguish findings from re-trade positioning.** A finding that reveals a real risk warrants a proposed treatment. A finding manufactured or amplified to re-negotiate the price to a level the buyer prefers is not a diligence finding; it is a negotiation tactic dressed as one. The seller can typically tell the difference, and reacts differently.
- **Aggregate the impact before the negotiation opens.** The buyer's deal team should know its total ask before it starts working individual findings with the seller. A negotiation that adds one demand at a time as each finding is worked reads as bad-faith; a negotiation that presents an integrated package and works down from there reads as principled.
- **Anchor to the objectively-verifiable adjustments before working the subjective ones.** QoE-driven EBITDA adjustments that both parties' QoE firms confirm are the easiest to close; commercial-diligence-driven "customer risk" arguments are the most contentious. Working the objective first builds negotiating capital for the subjective conversations.
- **Trade concessions.** The buyer wants a $5M purchase-price reduction; the seller counters with a $5M specific escrow for 18 months. The buyer accepts the escrow (which preserves seller headline economics) in exchange for something else the seller can give (e.g., extended survival on tax reps, a stronger seller-cooperation covenant on the customer-consent solicitation). The negotiation is multi-dimensional; the price is one dimension.
- **Preserve the exclusivity clock.** A negotiation that drags into and past the exclusivity deadline gives the seller the option to re-open the process. Neither side benefits from that outcome. The buyer's deal team drives to close the negotiation with a defined timeline, and if the negotiation is stalling, escalates rather than dragging.
- **Trigger deal-collapse only when the underlying issue is genuine.** A buyer that threatens deal-collapse tactically to extract a price re-trade will, over time, be characterised in the practitioner community as a bad actor; sellers and bankers will price this into future dealings.

## The failure modes that collapse deals unnecessarily

Some deals collapse when they should not have. The common patterns:

- **The buyer's inexperienced deal-team lead escalates too aggressively.** A red finding surfaces, and the buyer's lead — often without adequate deal-team backing — presents the finding to the seller with a purchase-price-reduction demand at the top of a plausible range. The seller reacts as if the buyer is walking, escalates internally, and the negotiation becomes an all-or-nothing showdown. A more-experienced lead would have opened with the middle of the range and left room for negotiation.
- **The seller's inexperienced deal-team lead reads any re-trade as bad-faith.** The seller's team may not have priced any re-trade into their expectations. Any adjustment feels like a bait-and-switch. The response is to reject all adjustments and threaten to walk. The buyer's team hears this as an unreasonable seller and dials back its deal-team's willingness to close.
- **The founder-CEO takes the price-renegotiation personally.** For founder-led targets, the purchase price is proxy for personal validation. A $2M price reduction against a $50M deal is 4% — objectively trivial as a proportion of value — but reads as "the buyer thinks I'm worth 4% less than the LOI." Founder-CEOs who are directly involved in the tactical negotiation without adequate coaching often escalate the personal dynamic to a deal-collapsing level. The banker and M&A counsel's job is to keep the founder-CEO briefed but out of the tactical negotiation.
- **The buyer's board or acquisition committee gets involved late and re-scopes the deal.** The buyer's board reviews the findings memo two days before signing, decides the deal profile has changed materially, and demands additional concessions the deal team had not been pursuing. The negotiation reopens under time pressure; the seller reacts as bait-and-switch. The counter-discipline is to keep the buyer's board briefed continuously through diligence — no surprises at the signing meeting.
- **The R&W underwriter changes the picture late.** The R&W underwriter's diligence-review call surfaces exclusions the buyer had not planned for (chapter 6). The buyer suddenly needs specific-indemnity coverage from the seller that had not been on the table. The seller reads this as the buyer trying to shift risk. The counter-discipline is to run the R&W underwriter's review in parallel with the buyer's own diligence, not sequentially — the buyer knows the exclusions picture before the negotiation opens.
- **The disclosure-schedule authoring is left too late.** The disclosure schedules (mod-104 chapter 4) are where the diligence findings actually land in the definitive agreement. Sellers who leave the disclosure-schedule authoring to the last week of the deal end up in a compressed negotiation over what belongs on the schedule vs. what belongs in a specific-indemnity — under time pressure this negotiation often produces poor outcomes for both sides. The buyer's discipline is to hold the seller to a disclosure-schedule delivery timeline that leaves room for negotiation before signing.

## The findings memo as input to R&W underwriting

The R&W underwriter's diligence review (chapter 6) reads the buyer-side findings memo as the primary evidence base for underwriting the general representations. The findings-memo authoring anticipates this by:

- **Explicit red / yellow / green coding** that lets the underwriter quickly identify the findings that will drive exclusions.
- **Explicit read-across to R&W-policy considerations** in each finding's Recommendation field — "this finding is anticipated to drive an R&W exclusion for [issue]; buyer should discuss specific-indemnity coverage with seller."
- **A dedicated R&W-considerations section** in the memo summarising the aggregate view — which findings are candidates for exclusion, which will complicate underwriting, which the underwriter is likely to require additional diligence on.
- **Sharing the memo (or a redacted version) with the R&W underwriter's counsel** as part of the underwriter's diligence-review preparation.

The findings memo authored well is a document that lives across three audiences — the buyer's own deal team, the sell-side (in modified form as the negotiation opens), and the R&W underwriter — without being three different documents. Practitioners typically author one memo with three delivery modes: full memo to the internal deal team, red-and-yellow findings extract to the sell-side, workstream summaries + R&W considerations to the R&W underwriter.

## The findings memo as input to the integration plan

Diligence findings that are not addressed through deal-side mechanics (price, indemnity, escrow, R&W exclusion) become post-close integration actions. Examples:

- **The target's controllership function is under-staffed** (a finding surfaced in financial diligence). This is not a purchase-price adjustment; it is an integration action — the buyer's finance function absorbs the target's finance function, and closing controllership gaps is part of the first-100-day plan.
- **The target's SOC 2 has a specific unremediated exception** (a finding surfaced in security diligence). Not a purchase-price adjustment; a specific integration action — the buyer's security team drives remediation within a defined window post-close.
- **The target's OSS-licence inventory has attribution gaps** (a finding surfaced in OSS-licence diligence). Not a purchase-price adjustment; an integration action — the target's engineering team, under the buyer's engineering leadership, ships the attribution updates in the next customer-facing release.
- **The target's HR-file completeness is weak** (a finding surfaced in HR diligence). Not a purchase-price adjustment; an HR-integration action — the buyer's HR function drives file remediation post-close.

The findings memo's Integration-Plan-Input section names these findings, categorises them (finance, security, engineering, HR, legal, sales), and estimates the integration-action cost. The integration-planning team (mod-111) reads this section as the input to the first-100-day plan.

## Summary

The buy-side diligence-findings memo turns raw diligence outputs into deal action. Its architecture — finding / evidence / impact / recommendation — forces every finding to answer "what does this mean for the deal" and "what do we do about it." Findings are coded red / yellow / green to prioritise deal-team attention. Red findings drive the price-renegotiation conversation, worked through four primary mechanics: purchase-price reduction, specific-indemnity carve-out, escrow increase, and (in the extreme) deal-collapse trigger. The choreography — sell-side confidential-channel heads-up, written findings package, iterative negotiation rounds, integrated final package — has stabilised in practitioner practice around a discipline of using diligence to allocate risk rather than to re-trade the price for its own sake. The memo also feeds the R&W underwriter's review and the post-close integration plan; author it once, deliver it in three modes.

Chapter 6 turns to the R&W insurance underwriter's diligence-review negotiation — the process by which the diligence findings become R&W policy exclusions, coverage carve-outs, or retention / premium adjustments.
