# R&W Insurance Underwriter Diligence Negotiation

## Why this matters

Sitting on top of the buy-side workstream plan (chapter 4) and the findings memo (chapter 5) is a third audience whose diligence-review posture reshapes what the buyer actually needs to inspect: the representations-and-warranties (R&W) insurance underwriter. On a modern mid-market venture-M&A transaction, R&W insurance is the primary post-close indemnification vehicle — the buyer's recourse for a rep breach runs to the R&W insurer, not to the seller-representative escrow, for anything beyond a modest retention (mod-104 chapter 7). That means the underwriter is not a passive observer of the diligence process; the underwriter is an active reviewer whose exclusions decisions determine what the *buyer* is actually covered for, and — by direct implication — what the seller has to backstop through specific-indemnity carve-outs, escrows, and price adjustments in the definitive agreement.

Practitioner practice around the R&W underwriter's diligence review has stabilised into a specific choreography: an initial underwriter engagement at LOI signing, a diligence-review call once the buyer-side workstream deliverables are in draft, an exclusions memo from the underwriter, a negotiation over the exclusions, and a bound policy at signing (with the policy incepting at closing). Along the way, the underwriter typically drives the buyer to *expand* diligence in specific areas — cyber, tax, wage-and-hour, AI-model-training-data, FCPA — because coverage for those areas is contingent on the diligence work having been done to a level the underwriter can underwrite against. And the retention / premium / coverage terms move as diligence quality moves; a well-diligenced target commands better terms.

This chapter installs the underwriter-diligence choreography. It is a companion to mod-104 chapter 7 (which installs R&W insurance mechanics generally) and a sibling to chapters 4 and 5 above (which install the buy-side workstream design and the findings memo). It does not re-teach how a policy is priced or how the retention drops from 1% to 0.5% at the 12-month mark; that lives in mod-104. It teaches the *diligence-side* interaction with the underwriter — the review call, the exclusions negotiation, and the feedback loop into the buyer-side workstream plan.

## The underwriter-engagement timeline

The R&W underwriter's engagement runs in five stages across the LOI-to-closing window:

**Stage 1 — Broker engagement and NBI (non-binding indication).** Immediately after LOI signing (sometimes before, on the buyer's expected-winning-bidder shortlist), the buyer's broker (Marsh, Aon, WTW, Lockton, Woodruff Sawyer, CAC Specialty, HUB, or a mid-tier specialist) markets the transaction to two-to-four underwriters. Underwriters return an NBI within 5-to-10 business days — indicative retention, indicative premium (rate on line), indicative coverage limit, indicative exclusions specific to the sector and the target's disclosed risk profile. The NBI is the buyer's read on likely policy economics and shapes the LOI-headline conversation with the seller about how R&W-insurance-supported the indemnification package will be.

**Stage 2 — Underwriter selection and engagement letter.** The buyer selects one underwriter (occasionally two — a primary and an excess layer) based on the NBIs. An engagement letter is signed. The engagement letter typically commits the underwriter to complete underwriting on a defined timeline (2-to-4 weeks) in exchange for an underwriting fee (typically $30K–$75K depending on complexity) that is non-refundable if the buyer walks away from the underwriter for a competitor.

**Stage 3 — Underwriter-diligence review.** The underwriter's counsel and technical team review the buyer's diligence-workstream deliverables. This is the substantive diligence-review event that this chapter is about.

**Stage 4 — Underwriter-diligence-review call.** A dedicated call (typically two-to-four hours; sometimes multiple calls) with the buyer, buyer's M&A counsel, buyer's workstream providers, the broker, the underwriter's counsel, and the underwriter's technical staff. The buyer walks the underwriter through the diligence work; the underwriter probes; specific findings and specific coverage concerns are worked in real time.

**Stage 5 — Exclusions memo, negotiation, and bind.** Post-call the underwriter issues a *no-claims declaration and exclusions memo* — the specific matters the underwriter will not cover, together with any additional-diligence conditions the underwriter is imposing. The buyer and its broker negotiate the exclusions. The policy binds at signing; coverage incepts at closing.

The whole choreography compresses into three-to-six weeks in a typical mid-market transaction, running concurrent with (not sequential to) the buy-side diligence workstreams. Running the underwriter review *after* buy-side diligence completes wastes weeks; running it *in parallel* means the underwriter's exclusions land in time to be worked into the definitive-agreement negotiation before signing.

## The underwriter's diligence-review call

The diligence-review call is the underwriter's opportunity to test the depth and reliability of the buyer's diligence work. It is not a courtesy walk-through. The underwriter has been through hundreds of these calls and knows exactly where the weak spots typically are.

**What the underwriter asks about, by workstream:**

- **Financial (buy-side Q of E).** Scope of the QoE. Materiality thresholds applied. Depth of testing on revenue-recognition. Reconciliation of buy-side to sell-side adjusted EBITDA and where disagreements landed. Working-capital and closing-cash / closing-debt bridges. Debt-like-item inventory completeness. Any known control weaknesses.
- **Legal (corporate).** Cap-table verification methodology and any discrepancies. Material-contracts review coverage (top-N by ARR? by contract-value?). Change-of-control provisions and consent-solicitation status. Litigation review including threatened matters. Compliance-with-laws review at the corporate level.
- **Tax.** Coverage across federal, state, local, international. Nexus-study depth (sales tax, income tax). §280G analysis. §382 NOL analysis. Uncertain-tax-position review. Any open examinations or protests. §174 R&D capitalisation posture. Transfer-pricing analysis for cross-border.
- **Commercial.** Customer-reference call count and mix (happy / neutral / churned). Cohort-retention verification methodology. Pipeline audit depth. Customer-concentration analysis. Any specific-customer risks flagged.
- **Technology / product.** Architecture-review depth. Source-code-review or scan scope. Technical-debt assessment. Third-party-dependency coverage. AI-model coverage (see chapter 7).
- **IP.** Registered-IP inventory verification. Assignment-of-inventions chain-of-title verification. OSS-licence review methodology (scan tool, human review, both). Freedom-to-operate concerns.
- **HR / comp.** Employee-census verification. Comp-benchmarking. Executive-agreement review. §280G analysis. Contractor / consultant classification review. Any pending EEOC or state-agency matters.
- **Privacy.** Applicable-law scope. GDPR / CCPA compliance depth. Cross-border-transfer mechanisms. Breach history and notification records.
- **Security.** SOC 2 or ISO 27001 status and any exceptions. Pen-test scope and remediation of critical / high findings. Prior incidents. Incident-response maturity.
- **AI / model.** Training-data provenance. Model-card documentation. GPAI-provider posture. Foundation-model-usage compliance. Copyright-training-data exposure. (Chapter 7 goes deep.)
- **Open source.** SBOM completeness. Copyleft-exposure analysis. Attribution completeness.
- **Regulatory.** Sector-specific licence verification. Export-control classification. Sanctions compliance. Anti-corruption programme review including third-party-due-diligence.
- **Environmental.** Phase I ESA if applicable. Historical spills or enforcement.
- **Insurance.** Coverage adequacy. D&O tail plans.

**What the underwriter probes:**

- **The gap between scope and depth.** "You reviewed the top-20 customer contracts — is that top-20-by-ARR? Does it cover any customer above 5% concentration? What about the recently-signed enterprise customer that came in above the threshold?" A reviewer that has scoped narrowly has not covered material risk; the underwriter identifies the gap and either requires scope expansion or excludes coverage for the un-diligenced area.
- **The known-issue treatment.** "Your buy-side QoE flags a $2.3M sales-tax nexus exposure across five states. What is the specific-indemnity treatment in the SPA? Is this an exclusion?" A known issue that is not backed by a specific-indemnity carve-out or an escrow is a known issue the underwriter will exclude by name.
- **The absence-of-evidence patterns.** "Your legal-diligence memo does not mention the target's Delaware annual reports for the last three years — did you verify good standing?" A gap in the diligence work is treated as *not diligenced*, and the underwriter either requires the diligence to be done or excludes the area from coverage.
- **The provider quality.** For a technology-diligence workstream conducted by a first-time provider or a provider with a thin track record, the underwriter may push back — "we typically see this workstream conducted by Crosslake or West Monroe; who is on your team and what is their prior underwriting-relevant experience?" Underwriters have relationships with the diligence-provider ecosystem and know which firms produce underwriting-quality deliverables.

**What the buyer prepares for the call:**

- **The workstream-plan document** (chapter 4).
- **The findings memo** (chapter 5), typically in a version that shows the underwriter the red / yellow / green code and the proposed deal-side treatment for each red.
- **Each workstream's underlying deliverable** (buy-side QoE, legal memo, tax memo, tech memo, HR memo, security memo, privacy memo, AI memo, OSS memo, regulatory memo, environmental report, insurance memo).
- **A driver-of-value memo** — a short document mapping the target's key value drivers to the workstreams that inspected them, showing coverage.
- **A workstream-quality summary** — the specific providers per workstream, the specific personnel, the specific scope and depth. This is what the underwriter uses to underwrite the *quality* of the diligence (not just its existence).

## The exclusions memo

Post-call the underwriter issues the exclusions memo. Its typical structure:

- **Standard policy exclusions.** The exclusions that appear in every R&W policy — fraud (except for buyer-side loss caused by seller-side fraud, which is typically preserved outside the policy), forward-looking statements, purchase-price-adjustment mechanics, breach-of-covenant, specific-jurisdiction restrictions (e.g., certain sanctioned countries), any matter of which the buyer had actual knowledge at signing (the "no-claims-known-at-signing" carve-out).
- **Specific-issue exclusions.** Matters surfaced in diligence that the underwriter will not cover because they are known and quantifiable — the $2.3M sales-tax nexus exposure, the AGPLv3-code-in-shipped-product finding, the specific pending customer litigation, the model-training-data-provenance gap.
- **Category exclusions.** Broader categories the underwriter will not cover regardless of specific findings — cyber breach-notification liability in some markets, wage-and-hour class exposure in California, PAGA claims, IRC §280G excise-tax exposure, foreign-corrupt-practices-act violations, prior-period tax positions, AI-model-related IP claims.
- **Conditional exclusions.** Coverage contingent on additional diligence being completed — "we will cover wage-and-hour exposure conditional on a wage-and-hour audit of California employees; we will cover AI-training-data-related IP exposure conditional on a third-party training-data-provenance audit."
- **Sub-limits.** Areas where the underwriter will provide coverage but at a lower limit than the general policy — cyber at 25% of the aggregate limit, tax at 50%.
- **Territorial and jurisdictional exclusions.** Losses arising from claims in specific jurisdictions the underwriter cannot underwrite.

The exclusions memo is *the* central artefact of the R&W diligence process. It translates the diligence findings into insurance economics: what the buyer is covered for, what the buyer bears itself, and what the buyer has to negotiate specific-indemnity coverage for from the seller.

## Categories the underwriter typically excludes

Some categories appear as exclusions or sub-limits with high frequency across underwriters:

**Cyber.** Prior data breaches (both known and unknown). Notification liabilities in jurisdictions with strict breach-notification regimes. Coverage for known unremediated critical vulnerabilities. In sectors with heightened cyber exposure (healthcare, financial services, consumer platforms with PII at scale), broader cyber exclusions or sub-limits are common. A separate cyber-insurance placement typically covers what R&W excludes.

**Wage-and-hour.** California PAGA (Private Attorneys General Act) representative-action exposure is the paradigmatic example — a known high-frequency claim category with unpredictable exposure that underwriters routinely exclude. Off-the-clock work, meal-and-rest-break, misclassification of independent contractors, exempt / non-exempt misclassification all surface here. Employment-practices liability insurance (EPLI) typically fills the gap where available.

**Tax positions in dispute.** Any tax position subject to an open examination, audit, or protest is typically excluded — the position is known, the exposure is quantifiable, and the underwriter will not cover a known contingent liability. A tax position that has not yet been challenged but is aggressive (e.g., a §174 R&D-capitalisation position that departs from the majority practitioner reading) may be excluded on the underwriter's judgment.

**FCPA and anti-corruption.** FCPA violations, UK Bribery Act violations, and Sapin II violations are frequently excluded, particularly where the target does business in high-corruption-index jurisdictions or through third-party intermediaries. A robust anti-corruption programme (code, training, third-party-due-diligence, whistleblower channel) supports narrowing the exclusion; the absence of a programme guarantees the exclusion.

**AI-model-training-data provenance.** A newer exclusion category, driven by the wave of copyright-in-training-data litigation (New York Times v. OpenAI, Getty Images v. Stability AI, Andersen v. Stability AI, and the numerous class actions filed against foundation-model providers and downstream users). Underwriters increasingly exclude "any claim arising from the training data used in the target's AI models" or specifically exclude copyright-in-training-data claims. Chapter 7 develops the negotiation of this exclusion.

**ESG / environmental.** Contamination on any owned or leased property (typically handled through a separate environmental-insurance placement). CSRD reporting failures for European-subsidiary-carrying targets. Sustainability-claim greenwashing exposure.

**Section 280G.** The excise-tax exposure under IRC §280G (mod-103 chapter 6) is often excluded — this is a known, quantifiable exposure that the buyer and seller manage through the pre-closing shareholder-vote cleanse and the 280G-mitigation strategy, not through insurance.

**Certain territorial exposures.** Business in certain jurisdictions (Russia, Iran, North Korea, and depending on the underwriter and current sanctions posture, other high-sanctions-risk jurisdictions).

Categorising an exclusion matters. A standard-policy exclusion is baseline — the buyer knows what to expect and negotiates only at the margins. A specific-issue exclusion is negotiable — the buyer works with the underwriter to narrow the exclusion, add additional diligence to bring the issue within coverage, or trade the exclusion for a specific-indemnity carve-out from the seller. A category exclusion is often not negotiable at the underwriter — the buyer either accepts it, prices it separately with an EPLI or cyber placement, or brings it back to the seller as a specific-indemnity ask.

## Negotiating the exclusions

The buyer's broker leads the exclusions negotiation with the underwriter; the buyer's M&A counsel, the buyer's deal team, and the specialist workstream providers all participate on specific items.

**Narrowing the exclusion language.** Underwriters draft exclusions broadly ("any claim arising from or related to..."). Broker practice tightens this ("any claim first made by a Third Party arising from Named Matter X, but excluding any claim otherwise covered under Section 4 of this Policy"). Every word matters; a broad "related to" can swallow a substantial portion of otherwise-covered claims.

**Trading additional diligence for narrower exclusions.** "You want to exclude wage-and-hour in California; we will commission a specific wage-and-hour audit of California employees before signing. Will that bring wage-and-hour within coverage subject to a sub-limit?" The underwriter's calculus is that additional diligence reduces the underwriter's information asymmetry; more diligence, more coverage.

**Sub-limits instead of full exclusions.** "You want to exclude cyber; will you provide $10M sub-limit coverage against the $50M policy limit, so that the buyer has some coverage even if cyber is capped?" The underwriter's calculus is that a sub-limit contains their exposure while still providing some coverage.

**Retentions specific to the exclusion.** "You want to exclude tax positions in dispute; will you cover tax positions not in dispute subject to a separate $500K tax retention above the policy retention?" This is an elevated-retention approach — the buyer bears more first-loss on the specific category in exchange for coverage.

**Coverage exceptions to broad exclusions.** "You want to exclude AI-model claims; will you cover AI-model claims *other than* copyright-in-training-data claims (which we'll exclude specifically)?" The negotiation isolates the underwriter's actual concern and preserves coverage for the balance.

**Seller-side specific-indemnity carve-outs for excluded matters.** When the underwriter will not cover an item, the buyer often turns to the seller for a specific-indemnity carve-out backed by a specific escrow. The seller may resist; the buyer's leverage is "we will bear the risk uninsured, but our deal-team appetite for that is limited; if you want the deal to close at LOI headline, you back the exclusion."

The negotiation is iterative. A typical mid-market deal produces two-to-four exclusions-memo rounds before final bind.

## The underwriter-driven expansion of buy-side diligence

The underwriter's diligence-review posture routinely drives *expansion* of the buyer's diligence work — the underwriter names an area where coverage is contingent on additional diligence, and the buyer commissions the work to bring the area within coverage. Common patterns:

**Wage-and-hour audit.** For a target with meaningful California workforce (or, increasingly, meaningful workforce in any state with strong employee-litigation exposure), the underwriter conditions wage-and-hour coverage on a specific-scope wage-and-hour audit. The audit typically runs $30K–$100K and takes 2-to-4 weeks.

**State-tax nexus study.** For a target that has expanded rapidly across states without formal nexus analysis, the underwriter conditions state-tax coverage on a nexus study. Study cost $30K–$100K; timeline 3-to-6 weeks.

**Anti-corruption programme audit.** For a target with material international operations or third-party intermediary exposure, the underwriter conditions FCPA coverage on a specific-scope anti-corruption programme audit including a sample of third-party due diligence.

**AI-model-training-data audit.** For an AI-first target, the underwriter increasingly conditions AI-model coverage on a training-data-provenance audit — see chapter 7. Cost and timeline vary widely with the target's data-source complexity.

**Cyber deep-dive.** For a target with sensitive-data exposure, the underwriter may condition cyber coverage on a red-team assessment or a specific penetration-test with the underwriter's technical staff observing.

**Historical-financial audit or restatement.** For a target with unaudited financials or a material change in accounting policy in the diligence period, the underwriter may condition financial-rep coverage on additional audit work.

**Environmental Phase I / Phase II.** For a target with any real-property exposure, the underwriter may condition environmental coverage on Phase I completion (and Phase II if Phase I identifies concerns).

The buyer's calculus on whether to commission the additional work is straightforward: the cost of the additional diligence versus the value of the resulting coverage. For a $100K wage-and-hour audit that unlocks $10M of coverage sub-limit, the ROI is clear. For a $500K training-data-provenance audit that unlocks $5M of coverage sub-limit, the calculus depends on the underlying risk assessment.

The buyer's timeline calculus matters too. Additional diligence that pushes the transaction timeline by two-to-four weeks may or may not fit inside the exclusivity window. If it does not fit, the buyer either extends exclusivity (which requires seller cooperation and is a small ask if the buyer has been performing on the LOI) or accepts the exclusion and moves to seller-side specific-indemnity.

## Retention, premium, and coverage — how diligence quality moves them

The economics of the policy are not independent of the diligence work. A well-diligenced target commands better terms; a lightly-diligenced target commands worse terms or narrower coverage.

**Retention.** Standard retention is typically 1% of enterprise value dropping to 0.5% at 12 months (mod-104 chapter 7 details). A well-diligenced target with a robust findings memo and a comprehensive workstream plan may see retention lower to 0.75%/0.5% or 0.5%/0.25%. A lightly-diligenced target may see retention hold at 1% and stay there, or go higher — 1.5% initial dropping to 1%, for example.

**Premium (rate on line).** Standard premium is 2%–5% of the policy limit. A well-diligenced target with clean workstream deliverables and modest exclusions may see rate-on-line at the lower end of the range (2%–3%). A lightly-diligenced target with substantial exclusions may see rate-on-line at the upper end (4%–5%) or above.

**Coverage limit.** Standard coverage is 10%–20% of enterprise value. A well-diligenced target with a sophisticated buyer with clear risk-transfer objectives may go higher (15%–20%). A lightly-diligenced target may see the underwriter cap at 10% or require an excess layer from a second underwriter.

**Exclusions volume and scope.** The most-important axis. A well-diligenced target may see the exclusions memo hold to a small number of specific-issue exclusions plus the standard categories. A lightly-diligenced target may see the exclusions memo balloon with category exclusions across workstreams the buyer did not diligence adequately.

**Underwriting-fee timing.** In competitive markets, some underwriters absorb the underwriting fee into the premium. In tight markets, the underwriting fee is charged whether or not the transaction closes. The buyer's broker negotiates this at the NBI stage.

The feedback loop back into the buy-side workstream plan is important: a workstream that the buyer is tempted to under-scope for cost reasons may re-appear on the R&W-exclusions side, either as an exclusion (buyer bears the risk) or as a required additional diligence spend (buyer pays anyway, without the earlier scoping-decision leverage). The buyer's discipline is to design the workstream plan with the R&W underwriter's expected scope in mind — front-loading diligence work that the underwriter will otherwise require.

## The trade-off decisions that come back onto the deal team

Every underwriter exclusion becomes a deal-team decision. The three primary decision paths:

**Path A — buyer bears the risk uninsured.** The exclusion is accepted; the buyer holds the risk on its balance sheet. This is the modal path for small-frequency, low-severity risks and for risks the buyer's own risk-management can absorb.

**Path B — seller-side specific-indemnity carve-out.** The exclusion is passed to the seller through a specific-indemnity carve-out with a specific escrow. The seller resists (specific-indemnity carve-outs claw back the value R&W insurance is supposed to preserve); the buyer's leverage is the exclusion itself ("either you back this or we bear it — one of us bears it either way; we prefer you"). Modal outcomes for material-exclusion items: the seller accepts, typically with an escrow of 100%–150% of the exposure held for 18–36 months.

**Path C — separate specialty insurance.** For specific exclusion categories, a standalone policy fills the gap. Cyber-insurance policies cover breach notification, incident response, and forensics. Environmental insurance covers historical contamination. EPLI covers wage-and-hour and employment-practices claims. Pollution-legal-liability covers historical release. Each has its own underwriting, retention, premium, and coverage architecture. The buyer's insurance broker coordinates the specialty placements alongside the R&W policy.

The choice among the three paths is driven by risk severity, seller willingness, and market availability. For a $2M sales-tax nexus exposure, a seller-side specific-indemnity backed by a $2M escrow is often the modal choice. For a $10M+ known-cyber-breach exposure, a standalone cyber policy is often the modal choice. For a $500K wage-and-hour PAGA exposure, buyer self-insurance is often the modal choice.

The findings memo (chapter 5) anticipates the trade-off — each red finding's Recommendation names the expected R&W treatment and, if excluded, the proposed deal-side treatment. This ensures the buyer's negotiation opens with a coherent risk-allocation position rather than an ad-hoc reaction to each exclusion as it surfaces.

## Coordination with the sell-side

The R&W underwriter's exclusions negotiation is a buyer-side conversation with the underwriter. The seller is typically not in the room. But the outcomes affect the seller directly — a broadly-excluded R&W policy pushes risk back onto the seller through specific-indemnity carve-outs and escrows the seller would not otherwise have agreed to.

Practitioner discipline:

- **The buyer keeps the sell-side lead informed** of the underwriter's exclusions trajectory (through the confidential channel, chapter 3). The sell-side is not surprised at signing by a specific-indemnity ask driven by a R&W exclusion.
- **The buyer shares specific findings that will drive exclusions** so the seller can prepare a response before the buyer opens the negotiation. "The underwriter is going to exclude the sales-tax nexus exposure; we'll be back to you with a specific-indemnity proposal; you should have your tax counsel ready with a view."
- **The sell-side's Q of E provider (chapter 2), tax counsel, and IP counsel** may be asked to prepare specific defensive materials that the buyer can share with the underwriter to narrow an exclusion.
- **In some transactions, the sell-side is present at the underwriter-diligence-review call** for specific workstreams — particularly Q of E and tax. The seller's provider walks the underwriter through the sell-side's analysis; the underwriter probes; the resulting conversation is more efficient than a two-step "seller explains to buyer, buyer explains to underwriter" pattern.

## The seller-side R&W policy variant

Most modern R&W insurance is buyer-side placement — the buyer is the named insured; the buyer's broker leads; the buyer's counsel negotiates the exclusions. Sell-side R&W placement (the seller is the named insured) is less common and appears in specific contexts: controlled-company transactions, seller-driven marketing where the seller wants to present the transaction with insurance pre-placed, certain family-office or private-founder-controlled targets, transactions where the seller has specific broker relationships.

Where seller-side R&W is placed, the diligence-review posture is different:

- The seller's diligence work (the sell-side data room, the sell-side Q of E, the sell-side response management from chapters 1–3) is the underwriter's primary evidence base, plus whatever buy-side diligence the eventual buyer performs.
- The exclusions negotiation is between the seller and the underwriter directly.
- The buyer's protection depends on the seller having the policy in force at closing; the buyer typically has no direct rights against the insurer.
- The buyer's own diligence still occurs (the buyer will not accept the seller's R&W policy as substitute for buyer diligence), but the buyer's workstream plan may compress in areas where the underwriter has already reviewed.

For most venture-M&A transactions in the current market, buyer-side placement is the modal choice. Seller-side and hybrid structures are exceptions worth naming but not dwelling on.

## Common failure modes

- **The underwriter engaged too late.** The buyer engages the underwriter at week six of diligence expecting a policy to bind at signing three weeks later. The underwriter cannot complete the review in the time available; the exclusions memo lands unpolished with broad category exclusions the buyer has no time to negotiate. The remedy is to engage at LOI signing and run underwriter-diligence review concurrent with buy-side diligence.
- **The buy-side workstream plan designed without R&W in mind.** The buyer scopes diligence to answer buyer questions and ignores the underwriter's coverage-driving diligence requirements. When the exclusions memo lands, the buyer discovers substantial coverage gaps in workstreams that were under-scoped. The remedy is to design the workstream plan with the underwriter's expected scope in mind from the start (chapter 4 references this).
- **The findings memo without an R&W-considerations section.** The buyer's findings memo (chapter 5) treats red findings as deal-side items without naming the R&W-exclusion implications. The underwriter surfaces the exclusion as a surprise. The remedy is the R&W-considerations section in the memo.
- **The exclusion accepted without deal-team escalation.** A junior broker or associate accepts an underwriter exclusion the deal team should have negotiated. Wage-and-hour is a common example — accepting a broad PAGA exclusion at signing without escalating to the deal team can leave $5M+ of exposure uninsured. The remedy is a specific-exclusions-review by the buyer's deal-team lead and M&A counsel before the exclusions memo is finalised.
- **The seller-side broadside on the R&W-driven specific-indemnity ask.** The seller reads a R&W-driven specific-indemnity ask as buyer bait-and-switch and pushes back reflexively. The remedy is the buyer's proactive communication of the underwriter's exclusions trajectory to the sell-side lead through the confidential channel.
- **The multiple-round exclusions-memo drift.** Each round of the exclusions memo lengthens as the underwriter's counsel adds items. The remedy is to hold the underwriter's counsel to a defined negotiation timeline and to escalate to the underwriter directly (past the counsel) if the counsel is adding items without underwriting basis.
- **The specialty-insurance placement forgotten.** The buyer accepts an R&W exclusion for cyber and forgets to place a cyber policy; six months post-close a breach surfaces and the buyer discovers there is no coverage. The remedy is the coordinated buyer-side insurance stack — R&W plus cyber plus EPLI plus environmental plus D&O tail — all designed together against the exclusions memo.

## Summary

The R&W insurance underwriter's diligence review is a substantive workstream that runs in parallel with the buyer's own diligence and reshapes both the buy-side workstream plan (chapter 4) and the definitive-agreement risk-allocation package (mod-104). Its five-stage choreography — broker engagement and NBI, underwriter selection and engagement letter, underwriter-diligence review, underwriter-diligence-review call, exclusions memo and bind — compresses into three-to-six weeks and produces a specific artefact (the exclusions memo) that determines what the buyer is actually covered for. Common exclusion categories — cyber, wage-and-hour, tax positions in dispute, FCPA, AI-model-training-data provenance, §280G, certain territorial exposures — reflect underwriter risk appetite as much as target-specific findings. The negotiation of the exclusions — narrowing language, trading additional diligence for narrower exclusions, sub-limits, elevated retentions, coverage exceptions — is led by the buyer's broker and involves the buyer's counsel, deal team, and workstream providers. The underwriter routinely drives expansion of the buyer's diligence in specific areas (wage-and-hour audit, state-tax nexus study, anti-corruption audit, training-data-provenance audit). The retention, premium, and coverage terms move with diligence quality — well-diligenced targets get better terms. Every exclusion becomes a deal-team decision: bear it, pass it to the seller through specific-indemnity, or place separate specialty insurance. The findings memo (chapter 5) anticipates this by naming R&W-considerations in each red finding's Recommendation, so the deal team's negotiation opens with a coherent risk-allocation position.

Chapter 7 turns to the AI-model and open-source-licence diligence that has become table-stakes in the last three years and drives an increasing share of R&W exclusions and specific-indemnity carve-outs.
