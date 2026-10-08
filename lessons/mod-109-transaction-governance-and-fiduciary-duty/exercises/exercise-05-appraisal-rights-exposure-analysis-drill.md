# exercise-05: Appraisal Rights Exposure Analysis Drill

**Estimated effort:** 3 hours

## Objective

Produce the **appraisal-exposure analysis** for the specific transaction — the DGCL §262 statutory analysis, the class-of-stockholder entitlement, the specific dissent-arbitrage economics, the drag-along / voting-agreement pre-emption analysis at private-company scale, and the specific reserves / financial-close-planning memo for the CFO. By the end you should be able to tell the board (a) which stockholders can dissent, (b) what the realistic range of appraisal exposure is, (c) what the drag-along / voting-agreement mechanics eliminate at private-company scale, and (d) what reserves and cash-availability discipline the close requires.

## Background

This exercise covers material from:

- [Chapter 7 — Appraisal Rights and DGCL §262 Exposure](../07-appraisal-rights-and-dgcl-262.md)

Appraisal is the right of a dissenting stockholder — one who refuses to accept the merger consideration and demands judicial determination of "fair value" — to a Chancery proceeding in which the court sets the per-share value independently of the deal price. The right flows from DGCL §262 for Delaware-incorporated targets; comparable statutory analogues exist in other states. The *Aruba Networks* / *DFC Global* / *Dell* trilogy of 2018–2019 Delaware Supreme Court appraisal opinions repositioned the "deal price" as the strongly presumptive fair value in a competitive arms-length process, which reshaped the appraisal-arbitrage calculus — but the statutory right remains, and the specific class-of-stockholder entitlement, dissent-notice choreography, and reserves discipline are still live.

## Prerequisites

- The exercise-01 output (transaction profile) and the exercise-02 output (committee structure).
- The target's current cap table — specific classes outstanding, specific holder-concentration, specific institutional-vs-individual breakdown.
- The target's current charter and bylaws — specific drag-along provisions, specific voting-agreement obligations, specific class-vote rights. For a venture-backed-C-corp target, the NVCA-model preferred-stock-financing documents are the typical starting point; the specific drag-along in the current charter / voting agreement may differ.
- Access to DGCL §262 (<https://delcode.delaware.gov/title8/c001/sc09/>) and the *Dell*, *DFC Global*, and *Aruba Networks* opinions.

## Tasks

### 1. Class-of-stockholder entitlement analysis

For each class / series of stock outstanding, determine specifically:

- **Statutory appraisal entitlement.** Under DGCL §262(b), which classes are entitled to appraisal in a merger. The default is that holders of stock entitled to vote on the merger have appraisal rights, subject to specific carve-outs — the "market-out" exception (§262(b)(1)) excludes stock listed on a national securities exchange or held of record by more than 2,000 holders, except for mergers where the consideration is anything other than stock of the surviving entity, stock listed / held by more than 2,000 holders, cash in lieu of fractional shares, or any combination. For a cash-merger of a public target, appraisal applies even to listed stock. For an all-stock merger of a public target where the consideration is listed stock, appraisal is typically eliminated under the market-out.
- **Short-form §253 merger entitlement.** DGCL §253 short-form mergers (parent owning ≥90% of each class, cashing out the minority) specifically preserve appraisal rights for the minority. *Glassman v. Unocal Exploration Corp.*, 777 A.2d 242 (Del. 2001) is the specific precedent that §253 short-form mergers are exclusive-remedy-appraisal transactions — fair-value appraisal is the stockholder's sole remedy; entire-fairness challenge is not available.
- **Medium-form §251(h) merger entitlement.** DGCL §251(h) two-step tender-offer-plus-back-end-merger specifically preserves appraisal rights for stockholders who did not tender into the top-up tender offer.
- **Private-company class entitlement.** For a non-listed target with ≤2,000 record holders, appraisal applies to all stock entitled to vote on the merger regardless of consideration. Common stock holders, preferred stock holders, specific-series holders all have specific entitlement.
- **Specific stockholder exclusion.** DGCL §262(d) requires specific procedural compliance to perfect appraisal — a specific written demand before the stockholder vote, a specific "no" vote (or abstention) rather than "yes," specific abstention from accepting the merger consideration. Stockholders who vote "yes" or accept the consideration waive the right.

For each class, produce a specific one-line finding: "Series X has / does not have appraisal rights because [specific statutory basis]."

### 2. Dissent-choreography map

Draft the specific sign-to-close choreography of the appraisal process:

- **T-20 to T-10 (approximately): Notice of appraisal rights.** DGCL §262(d) requires the target to notify stockholders of their appraisal rights specifically — the notice must be delivered no less than 20 days before the stockholder meeting (for a long-form merger), or the specific comparable period for other merger types. Draft the specific DGCL §262 notice. For a §251(h) two-step, specific notice is delivered with the tender-offer materials.
- **Pre-vote demand.** Dissenting stockholders must deliver a specific written demand for appraisal before the stockholder vote (or, for a §253 / §251(h) merger, before the specific effective date).
- **Vote.** Dissenting stockholders must specifically not vote "for" the merger. Specific abstention or "no" vote is required.
- **Post-vote petition.** Within 120 days after the effective date, the dissenting stockholder or the surviving corporation may file an appraisal petition in Chancery (§262(e)).
- **Specific interest.** The Chancery court sets fair value as of the effective date, with interest from the effective date (§262(h)) at the Federal Reserve discount rate plus 5% (post-2016 amendment), compounded quarterly. The surviving corporation may pre-pay a specific amount under §262(h) to cap the interest accrual on that portion.

### 3. Realistic appraisal-exposure quantification

For the specific transaction, build a specific exposure model:

- **Specific potentially-dissenting-stockholder set.** From the cap table, identify specific holders by name / institutional-type / investment-strategy-fit who are plausible dissenters. Hedge-fund appraisal-arbitrage holders have a specific profile — Verition Partners, Merion Capital, Houlihan Lokey (as an arbitrage holder, not as the fairness-opinion firm), Magnetar, and a specific set of specialists. Index funds and most mutual funds specifically do not pursue appraisal.
- **Specific plausible-dissent percentage.** For a public-target cash merger, specific historical dissenter rates range from 0% to 10%+ depending on specific case facts. In the post-*Aruba* / *Dell* / *DFC Global* era, specific plausible-dissenter rates have fallen materially from 2014-era peaks.
- **Specific "fair value" scenarios.** Scenario (a) — deal price is the presumptive fair value under *Dell* / *DFC Global* / *Aruba*; the dissent-exposure is capped at the specific interest-rate accrual on the §262(h)-not-prepaid portion. Scenario (b) — Chancery court finds a specific premium above deal price (as in specific pre-*Dell* appraisal awards); the dissent-exposure is the specific premium times the specific dissenting-share count plus interest. Scenario (c) — Chancery court finds a specific discount below deal price (as in *Verition Partners Master Fund Ltd. v. Aruba Networks, Inc.*, 210 A.3d 128 (Del. 2019), where the court found 30-day pre-signing unaffected trading price was fair value, below the deal price); the surviving corporation benefits but still pays the specific interest accrual.
- **Specific interest-arbitrage economics.** The Federal Reserve discount rate plus 5% is the specific interest rate on the appraisal-pending period. Pre-2016, this was unambiguously an attractive specific interest rate; post-2016, the specific economic attractiveness is sensitive to the specific prevailing Fed discount rate and the specific duration of the appraisal proceeding (typically 2-4 years from effective date to award). The surviving corporation's prepayment under §262(h) specifically limits this exposure.

Produce a specific exposure range in dollars: low-case / base-case / high-case.

### 4. Drag-along and voting-agreement pre-emption analysis (private-company scale)

For a venture-backed-C-corp target or any private-company target where the stockholder base is not public, the drag-along and voting-agreement mechanics in the current corporate documents can specifically eliminate individual-stockholder appraisal / dissent rights. Walk the specific analysis:

- **Drag-along provision in the stockholders' / voting agreement.** The specific drag-along requires specific stockholders (typically common holders and all preferred below a specific threshold) to vote with the dragging-stockholders (typically the preferred majority or the board). The specific drag-along's effect on appraisal rights depends on specific drafting — a specifically well-drafted drag-along contractually requires the dragged stockholder to vote "yes" and specifically waive appraisal rights, which (if enforceable) eliminates individual dissent. *Halpin v. Riverstone National, Inc.*, 2015 WL 854724 (Del. Ch. Feb. 26, 2015) is the specific Delaware precedent on drag-along enforcement; specific drag-along provisions that specifically require "yes" voting and that specifically waive appraisal rights have been enforced.
- **Voting-agreement specific terms.** Specific voting agreements require specific stockholders to vote in specific ways; a specifically drafted voting agreement that specifically requires "yes" voting on a board-approved sale specifically preempts dissent.
- **Specific class-vote carve-outs.** Specific preferred-stock protective provisions (NVCA-model §B.3.3) may require a specific preferred-majority vote on specific transaction types; the specific voting-agreement and drag-along specifically interact with the specific protective provision structure.
- **Enforcement.** Walk the specific plaintiff pathway if a specific stockholder refuses to be dragged — specific specific-performance remedy, specific damages for breach of the drag.

For the specific transaction, map specifically: (a) which stockholders are specifically dragged by specific provisions; (b) which stockholders are not; (c) which specific appraisal-rights are specifically waived; (d) which specific appraisal-rights specifically survive the drag.

### 5. Reserves and cash-availability close memo

Draft a short (1-2 page) memo for the CFO on the specific close-cash discipline required to absorb the appraisal exposure:

- **Specific escrow / holdback.** The merger agreement typically includes a specific escrow or holdback mechanism for appraisal-dissent exposure. Specific sizing — tied to the specific exposure range from task 3.
- **Specific §262(h) prepayment plan.** If appraisal is pursued by specific holders, the surviving corporation can prepay a specific portion to specifically limit the interest accrual. Specific prepayment strategy — prepay deal price, prepay less than deal price, prepay nothing. The *Dell* / *Aruba* post-award pattern specifically favours prepayment of deal price to cap interest.
- **Specific accounting treatment.** The appraisal-dissent reserve on the acquirer's post-close balance sheet; the specific contingency-reserve under ASC 450 / 805; the specific disclosure in the acquirer's quarterly / annual filings.
- **Specific insurance.** Specific R&W insurance generally does not cover appraisal-related damages (appraisal is a statutory right, not a breach of a representation). Specific transaction-cost / contingent-liability insurance may be considered for specifically-high-exposure deals. Specific "no-dissent-above-X%" closing-conditions in the merger agreement are the specific contractual protection, not an insurance product.
- **Specific communication plan.** If specifically-known appraisal-arbitrage holders are expected to appear in the specific record-date snapshot, the specific CFO's communication plan — specifically no direct engagement with specific dissenters (counsel-only), specific press-release restraint, specific analyst-call treatment, specific proxy-advisor engagement (chapter 8 exercise-06).

### 6. Dissenter-list monitoring plan

Draft the specific record-date-monitoring plan:

- **Record date.** Specific setting of the record date, specific vote-tabulation agent (Broadridge / Computershare / specific transfer agent).
- **Dissent-watch calendar.** Specific daily reports from the vote-tabulation agent on specific dissent-notice filings. Specific DTC-held-stock mechanics — specific "street name" holders dissent through specific brokers' back-office systems, specific identification challenges.
- **Specific litigation-strategy decision tree.** Specific threshold at which the surviving corporation specifically prepays under §262(h), specifically negotiates with specific dissenters, specifically defends through to a full appraisal trial.

## Starter guidance

Three anti-patterns to avoid:

- **The "the market-out exception means we have no appraisal exposure".** The market-out specifically applies to listed stock receiving listed-stock consideration. A cash-merger of a listed target specifically preserves appraisal. A specific mix-of-cash-and-stock may or may not preserve appraisal depending on specific structure. The analysis is specific to the specific transaction consideration mix.
- **The "appraisal is dead post-*Aruba*".** *Aruba* and the *Dell* / *DFC Global* trilogy specifically reduced the economic attractiveness of appraisal arbitrage in deal-price-is-fair-value scenarios, but appraisal remains a specifically-exercised statutory right. Specific transactions with specifically-questionable processes (non-arms-length, controller, specifically-coerced vote) specifically remain exposed to specifically-above-deal-price fair-value findings.
- **The "the drag-along handles it".** A specific drag-along is enforceable only to the extent the specific drafting specifically covers both the specific vote and the specific appraisal-rights waiver. Specific drag-alongs that specifically require "yes" voting but do not specifically waive appraisal preserve appraisal; a specific stockholder could vote "yes" (as required by the drag) and still perfect appraisal (not having been contractually waived). The specific drafting of the drag-along is the dispositive point.

## Acceptance criteria

You can demonstrate that:

- Each class / series has a specific appraisal-rights finding tied to the specific DGCL §262 statutory basis.
- The dissent-choreography map specifies the specific timing, specific demands, specific vote treatment, specific petition timeline, specific interest-rate calculation.
- The exposure quantification has specific numbers (not placeholder values) in low / base / high scenarios.
- The drag-along pre-emption analysis specifically maps each stockholder to specifically dragged / not-dragged status with specific supporting document reference.
- The reserves / cash memo is operational — a CFO could use it to plan close-cash.
- The dissenter-list monitoring plan has a specific record-date / tabulation-agent / daily-report workflow.
- A critical reader (Delaware specialist counsel, in-house CFO, peer general counsel) could stress-test a specific assumption and see the specific evidence you used.

## Reflection

Add a short reflection (½ page):

1. Which specific stockholder on the cap table has the highest probability of pursuing appraisal and why?
2. If the Chancery court applied the *Verition Partners v. Aruba Networks* unaffected-trading-price methodology to your transaction, what would the specific implied fair value be and how does it compare to the specific deal price?
3. If you had to pay down the specific interest-rate accrual under §262(h), what is the specific prepayment amount you would recommend and why?

## Stretch goals

- **Appraisal-arbitrage holder monitoring.** Specifically research the specific 13F / Form 4 filings of Verition Partners, Merion Capital, and other known appraisal-arbitrage funds to identify specifically whether any specifically hold a position in your target. Produce a specific one-line finding for each.
- **Comparable appraisal case study.** Pick a specific recent Delaware appraisal opinion (*In re Appraisal of Columbia Pipeline Group, Inc.*, 2019 WL 3778370 (Del. Ch. Aug. 12, 2019); *In re Appraisal of Jarden Corp.*, 236 A.3d 313 (Del. 2020); *In re Appraisal of Panera Bread Co.*, 2020 WL 506684 (Del. Ch. Jan. 31, 2020)) and write a 1-page "what would the Chancellor do with my transaction" memo.
- **Non-Delaware comparison.** If the target is Delaware but has significant subsidiaries incorporated in another jurisdiction (California, Washington, New York), outline the specific comparable-statutory analysis in that jurisdiction. For California, specifically address Cal. Corp. Code §1300 "dissenters' rights" and the specific differences from DGCL §262.
