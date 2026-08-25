# Earn-Out Design and Dispute Mitigation

## Why this matters

Earn-outs are the M&A structural tool most often praised in the LOI and cursed in year two. They exist because buyers and sellers disagree about the future value of the target and the earn-out defers a portion of the purchase price to when that disagreement can be resolved by observed operating performance. In principle, this is a reasonable way to bridge a valuation gap. In practice, an earn-out places the seller's economics under the buyer's operational control for a multi-year period during which the buyer has both the ability and — often — the incentive to affect the outcome. The result is a body of Delaware Chancery Court case law measured in hundreds of opinions on earn-out disputes: whether the acquirer used "commercially reasonable efforts" to achieve the milestone; whether the acquirer's post-close changes to the acquired business breached implied covenants of good faith; whether the acquirer's accounting choices on the earn-out metric were consistent with the SPA's definitions; whether the acquirer's failure to reach the milestone was foreseeable at signing and therefore ought to be treated as a constructive achievement.

The design task is not to make disputes impossible — that is not achievable — but to design the earn-out so that the modal outcome is a clean payout (or a clean miss) and that when disputes arise, the mechanics are clear enough that the resolution does not require Chancery litigation. This chapter installs the earn-out design toolkit, the specific failure modes that recur, and the drafting mechanics that mitigate them.

## The earn-out design surface

An earn-out is defined by five design decisions, each of which has to be negotiated and drafted in the merger agreement. Missing any one of the five produces a structural weakness that becomes a dispute vector post-close.

### Design decision 1: What is the metric?

The metric is what the earn-out payout is computed against. The common choices:

- **Revenue.** Straightforward to measure and hard for the buyer to manipulate (customer transactions are external observables). Vulnerable to *strategic revenue-mix shifts* if the buyer redirects the acquired product's sales through a channel where the revenue is booked to a different entity in the buyer's group.
- **Gross profit.** Revenue less cost-of-goods-sold. More aligned with contribution to the buyer's bottom line than pure revenue. Vulnerable to *cost allocation manipulation* — the buyer's post-close COGS accounting may include or exclude specific overhead components differently than the target's pre-close accounting did.
- **EBITDA or Adjusted EBITDA.** Higher up the P&L, closer to bottom-line contribution. Extensive definitional overhead is required — every non-cash and one-time adjustment has to be specified in the SPA, and the *quality-of-earnings* (Q-of-E) process that mod-105 develops for diligence becomes the reference framework for post-close EBITDA disputes. Highly vulnerable to buyer post-close spending decisions (a new marketing initiative funded from acquired-business revenues reduces EBITDA).
- **Product milestones.** Non-financial gates such as regulatory approval, product launch, customer count, feature-completion. Common in biotech / pharma (regulatory approval CVRs — chapter 2), and in transactions where a specific commercialisation event materially changes the target's value.
- **Mixed.** Some combination — often revenue-plus-milestone (a milestone earn-out plus a revenue-based earn-out running in parallel, or a milestone earn-out that unlocks a revenue-based earn-out that then measures over a subsequent period).

Metric selection is where the buyer-vs-seller tension is most visible. Sellers want revenue (harder to manipulate, more aligned with what they built). Buyers want EBITDA or Adjusted EBITDA (more aligned with what they paid for). The negotiation typically settles at revenue for smaller earn-outs and mixed / EBITDA for larger ones.

### Design decision 2: What is the payout curve?

The payout curve is the mapping from metric performance to earn-out payout. Common shapes:

- **Cliff.** All-or-nothing at a specified target level. Simplest to draft and understand; produces the worst incentive misalignment near the cliff (buyer's incentive to make the last 5% is different from their incentive above target).
- **Graduated / linear.** Payout scales linearly with performance between a minimum threshold and a maximum threshold. Reduces the cliff-effect distortion but produces payouts even when performance is well below target.
- **Accelerated.** Payout scales more than linearly with performance, often with a "kicker" if performance exceeds a stretch threshold. Aligns strongly with over-performance; can be gamed if the metric is manipulable near the kicker threshold.
- **Multi-tranche.** Separate earn-out tranches for separate targets, each with its own cliff or graduated payout. A common variant: a "base" tranche with a graduated payout up to target, plus a "stretch" tranche with a cliff payout for exceeding a specific over-performance level.
- **Extension / catch-up.** If the earn-out fails to meet its target in the primary period, an extension period offers a second chance to achieve, possibly with a modified target or a discounted payout.

Payout curve choice interacts with the metric choice: a cliff payout on a revenue metric is materially different from a cliff payout on a product-milestone metric.

### Design decision 3: What is the measurement period?

- **Short (12 months).** Reduces the buyer's post-close operational-control leverage but constrains what can plausibly be measured (many revenue-based earn-outs need at least a full year to have meaning).
- **Standard (24 months).** The modal earn-out period. Long enough to measure meaningful performance; short enough that post-close operational drift is bounded.
- **Long (36+ months).** More time for the buyer to affect the outcome; more time for post-close integration to distort the metric; more time for market conditions to change materially. Extended earn-outs are typically confined to product-milestone situations (regulatory approval CVRs) where the underlying event genuinely takes years to resolve.
- **Multi-year with annual measurement.** An earn-out that measures each year independently, with separate payouts for each year's performance. Reduces the acquirer's incentive to shift performance between years; increases administrative overhead.

### Design decision 4: What acquirer obligations attach to the earn-out?

This is where the "commercially reasonable efforts" question meets the drafting practice. The acquirer's post-close operating discretion is inherently in tension with the earn-out's economic dependence on that operating performance. Standard drafting choices:

- **Best efforts / commercially reasonable efforts covenant.** The acquirer agrees to use *commercially reasonable efforts* to operate the acquired business in a way that supports achievement of the earn-out. The strength of this covenant is contentious — sellers want "best efforts" or "the efforts a reasonable business would use to achieve the earn-out"; buyers want either no efforts covenant at all or a very deferential one (which Delaware courts have sometimes read as adding little to the implied covenant of good faith). The doctrine is unsettled enough that drafting the specific covenant is important.
- **Operating covenants.** Specific commitments — the acquirer will not shift the acquired product's revenue to a different entity in the group; will not increase COGS allocation to the acquired business above a specified baseline; will not terminate customer contracts without cause; will not lay off more than a specified number of employees without seller consent; will fund a specified minimum operating budget.
- **Preservation covenants.** The acquirer will not fundamentally change the business, sell it to a third party, or wind it down during the earn-out period without triggering acceleration (see design decision 5).
- **Reporting obligations.** The acquirer will provide monthly / quarterly reporting to a designated seller representative on the earn-out metric, with agreed-upon report format and cadence.
- **Information rights.** The seller (through the representative) has audit rights on the earn-out calculation, access to the underlying books and records for the acquired business, and the right to engage independent accountants at seller expense.
- **Non-solicitation / non-hire restrictions on key personnel.** Specifically for talent-consolidating acquisitions (mod-102 chapter 1) where personnel departure would affect the earn-out.

The acquirer wants minimal obligations; the seller wants maximal obligations. The balance is drafted as a specific list, and the specific list matters. Every earn-out dispute in Delaware Chancery revolves around what the acquirer was or was not obligated to do.

### Design decision 5: What are the acceleration and dispute-resolution mechanics?

- **Acceleration on breach.** If the acquirer breaches a specific operating covenant, or if the acquirer sells / winds down the acquired business, the earn-out accelerates and pays out at a specified level (often the full maximum, or a formula-based amount).
- **Acceleration on change-of-control.** If the acquirer itself is acquired during the earn-out period, the earn-out accelerates.
- **Acceleration on adverse-modification.** If the acquirer materially changes the acquired business in a way that would prejudice the earn-out (a broader "change" trigger than a specific-covenant breach).
- **Dispute-resolution mechanism.** The mechanism for resolving disputes about the earn-out calculation. The modal structure: an independent accountant is engaged to resolve calculation disputes on a *binding* basis, with the parties splitting the accountant's fees. Legal disputes (whether the acquirer breached a covenant, whether the acquirer used commercially reasonable efforts) typically go to arbitration or to the Delaware Chancery Court (or the court of the SPA's chosen forum).
- **Escalation clock.** A specific timeline for the earn-out calculation (typically the acquirer produces a proposed calculation within X days of period end), the seller's review period (Y days after receipt), the negotiation period, and the escalation to the independent accountant if unresolved.

Well-drafted earn-outs specify all five design decisions explicitly. Poorly-drafted earn-outs leave one or more open, which becomes a dispute vector.

## The failure modes that produce Delaware Chancery litigation

Certain patterns recur in earn-out disputes. Recognising them at the design stage — and drafting explicitly against them — is what separates a defensible earn-out from one that becomes a multi-year legal exposure.

### Failure mode 1: Buyer post-close operational changes affect the metric

The buyer's post-close operational discretion is real. If the buyer redirects the acquired product's sales to a different distribution channel, changes the pricing model, shifts customer-service resources, integrates the product into a bundled offering, or reallocates engineering to a different priority, the earn-out metric is affected. When the earn-out then misses, the seller alleges the buyer's operational changes caused the miss; the buyer responds that the changes were within the ordinary course of business.

**Design mitigation:** operating covenants that specifically restrict the buyer's changes to the acquired business during the earn-out period. Preservation covenants on distribution, pricing, and product integration. Reporting obligations that surface changes as they happen. The tighter these covenants, the harder it is for the buyer to make legitimate operating decisions post-close — the trade-off between earn-out protection and acquirer operational flexibility is real.

### Failure mode 2: Metric-definition ambiguity

The earn-out metric — whether revenue, gross profit, EBITDA, or a product milestone — has to be defined precisely in the SPA. Ambiguity in the definition (which customer contracts count; how deferred revenue is treated; what expenses are subtracted; how transfer pricing between the acquired business and the acquirer's group is computed for allocated costs; how a milestone is deemed achieved) becomes a dispute vector.

**Design mitigation:** define the metric with reference to a specific accounting standard (GAAP as applied by the acquirer's audited financial statements, or GAAP as historically applied by the target with a defined transition), enumerate specific adjustments and exclusions, specify a reference period baseline for any allocated costs, and include worked examples in a schedule to the SPA where the metric definition is complex. The Q-of-E process (mod-105 depth) is the reference framework — the earn-out metric should be defined with the specificity of a Q-of-E-quality accounting.

### Failure mode 3: The "commercially reasonable efforts" ambiguity

Delaware courts have wrestled repeatedly with what "commercially reasonable efforts" means in an earn-out context. Standards range from "use the same efforts a reasonably prudent company would use to achieve the milestone" (relatively stringent) to "use the same efforts the acquirer uses on its comparably-situated products" (relatively deferential). The specific language matters, and the case law is not settled. The Aveta v. Cavallieri (Del. Ch. 2010), Fortis Advisors LLC v. Dialog Semiconductor (Del. Ch. 2015), Winshall v. Viacom (Del. Ch. 2013), and Menn v. ConMed (Del. Ch. 2022) opinions all address different aspects of the standard, and each opinion adds nuance without fully resolving the doctrine.

**Design mitigation:** specify the standard precisely in the SPA. "Best efforts to achieve the milestone, without regard to the effect on the acquirer's other businesses" is stringent (sellers prefer). "Same level of efforts as the acquirer applies to comparable programs in its own business" is deferential (buyers prefer). If the parties cannot agree, the compromise is often a specific covenant list (design decision 4) that operates as a "specific-performance-standard" replacement for the general "efforts" language.

### Failure mode 4: The implied covenant of good faith

Delaware imposes an *implied covenant of good faith and fair dealing* on every contract, including SPAs and earn-out provisions. The covenant fills gaps — actions the parties did not specifically address in the contract — with a good-faith standard. In earn-out disputes, the seller frequently alleges that the acquirer's actions, though not violating any specific covenant, violated the implied covenant. See Winshall v. Viacom Int'l Inc. (Del. Ch. 2013) and its progeny for the doctrine.

**Design mitigation:** the implied covenant is not disclaimable in Delaware (unlike some other jurisdictions where a "no-implied-covenant" clause has force). The mitigation is to draft the SPA specifically enough that most disputes fall within the *express* covenant list rather than the implied-covenant residual — every operational lever the acquirer might pull that could affect the earn-out is a candidate for a specific covenant.

### Failure mode 5: Milestone-definition ambiguity

For milestone-based earn-outs (product launches, regulatory approvals, customer counts), the definition of "achievement" is a dispute vector. Does the milestone require a specific date? A specific customer? A specific regulatory-approval type? What constitutes "launch" — general availability, limited availability, an internal alpha? What if the milestone is partially achieved?

**Design mitigation:** define milestones with legal-diligence-level precision. "Regulatory approval" means "receipt of a specific approval type from a named regulatory body," not "any form of regulatory clearance." "Product launch" means "commercial availability to at least [N] customers with contractual revenue commitments of at least [$X] in aggregate," not "the product being made available."

### Failure mode 6: Acquirer accounting choices under the earn-out metric

For EBITDA or gross-profit earn-outs, the acquirer's post-close accounting choices affect the metric. Cost allocation, transfer pricing, revenue recognition timing, capitalisation policy — each is a lever. In the *Chicago Bridge & Iron Company v. Westinghouse Electric* line of cases (though not an earn-out case per se, the principle applies), Delaware has stressed the importance of specific accounting-standard drafting.

**Design mitigation:** the SPA should specify the accounting standards applicable to the earn-out metric, and whether the buyer's or the target's historical accounting practices govern. The independent-accountant dispute-resolution mechanism should be reserved for disputes about *calculation* under the specified standards, not for disputes about which standards apply (the latter has to go to legal dispute resolution).

### Failure mode 7: The buyer's incentive to make the earn-out miss

The most fundamental failure mode: the buyer, post-close, has an economic incentive to *not* pay the earn-out. Every dollar not paid is a dollar retained. If the buyer's cost of "reasonable efforts" to achieve the milestone exceeds the marginal buyer benefit of the milestone's achievement (which for many milestones is nearly all upside to the buyer, minus the earn-out payment), the buyer's rational action can be to *not* try hard.

**Design mitigation:** the entire earn-out design framework exists to constrain this incentive. Operating covenants, reporting obligations, dispute-resolution mechanics, and acceleration triggers all serve to raise the buyer's cost of missing the earn-out beyond the payment saved. But the incentive is structural and cannot be fully eliminated — which is why earn-outs are used sparingly by sophisticated sellers, and why alternative structures (headline number with less earn-out, seller notes, rollover equity, escrow) are often preferred over large earn-outs.

## Practical drafting checklist

For each earn-out included in an SPA, verify:

- **Metric.** Is it precisely defined? Are the specific accounting standards (or milestone-verification standards) specified? Are cost allocations, transfer pricing, and other buyer-discretion points addressed?
- **Payout curve.** Is it clear? Are thresholds, cliffs, kickers, and interpolations specified?
- **Measurement period.** Are dates precise? Is the calculation methodology for partial periods specified? Are extensions or catch-up periods defined?
- **Operating covenants.** Is there a specific list of buyer obligations? Do the covenants address the *specific* levers the buyer might pull to affect the metric? Is the covenant list defensible against real post-close operating flexibility?
- **Reporting obligations.** Does the seller (through a representative) receive regular reporting on the metric? Is the format specified? Are audit rights specified?
- **Acceleration triggers.** Is acceleration specified for buyer sale, buyer wind-down, buyer breach, and other events?
- **Dispute-resolution mechanics.** Is there a specific mechanism for calculation disputes (independent accountant)? A specific mechanism for legal disputes (arbitration or court forum)? Is the escalation clock defined?
- **Seller representative.** Is a specific person or entity named as the seller representative empowered to enforce the earn-out on behalf of the shareholders? Are the representative's powers, indemnities, and expenses specified?
- **Tax treatment.** Is the earn-out treated as installment sale under §453, compensation, or contingent consideration? The classification affects both the seller's tax treatment and the buyer's deduction treatment.
- **§409A compliance.** For earn-outs paid to employees / service providers, does the earn-out qualify for the short-term-deferral exception under §409A, or is it structured to be §409A-compliant deferred comp? Chapter 7 develops the mechanics.
- **§280G exposure.** For earn-outs to disqualified individuals, is the earn-out included in the §280G parachute-payment analysis? Chapter 6 develops the mechanics.

## Summary

Earn-outs are one of the most-negotiated and most-litigated structural mechanisms in M&A. The design surface — metric, payout curve, measurement period, operating covenants, and dispute-resolution mechanics — has to be filled in explicitly at drafting; ambiguities become dispute vectors. The failure modes that produce Delaware Chancery litigation recur predictably (buyer post-close operational changes, metric-definition ambiguity, the "commercially reasonable efforts" question, the implied covenant of good faith, milestone-definition ambiguity, accounting-choice disputes, and the buyer's structural incentive to miss). Well-drafted earn-outs mitigate each of these through specific covenants, precise metric definitions, and clear escalation mechanics. The most reliable earn-out mitigation, however, is to use earn-outs sparingly — for the specific valuation-bridge situations where they are the least-bad structural tool, rather than as a default technique.
