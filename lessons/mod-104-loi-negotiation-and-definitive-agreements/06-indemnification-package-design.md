# Indemnification Package Design

## Why this matters

The reps and warranties in Article III (chapter 4) are statements of fact; they only have value if they can be enforced. The indemnification package is the enforcement mechanism — the contractual apparatus that lets the buyer recover from the seller if a rep turns out to be inaccurate or if a covenant is breached. Every substantive dispute about "who bears the risk of X" — undisclosed tax liability, historical environmental exposure, IP-infringement claim, misrepresented ARR — ultimately gets resolved by reference to the indemnification package.

The package has six interlocking components: survival period, overall cap, basket (with basket type and basket size), de-minimis threshold, sole-and-exclusive-remedy language, and specific carve-outs (fraud, IP, tax, etc.). Each component is negotiated against ABA / SRS Acquiom benchmarks and against the specific risk profile of the transaction. The dollar amounts and specific mechanics change dramatically between a traditional-indemnification deal and an R&W-insurance-supported deal (chapter 7 develops the R&W alternative), so this chapter first covers the traditional package and then notes how R&W insurance changes the calculus.

## The six components

### Component 1 — Survival period

The **survival period** is the length of time after closing during which the buyer can bring an indemnification claim. If a claim is not brought within the survival period, the claim is barred.

Survival periods are layered against the rep-layers stack from chapter 4:

- **Fundamental reps** (corporate organisation, capitalisation, authorisation, title) — typically 3–7 years, or the applicable statute of limitations, or indefinitely. Fundamental reps go to the essence of the transaction, and buyers want extended survival to catch breaches that may not surface for years (a title dispute, a capitalisation error that emerges when a former stockholder appears).
- **Tax reps** — typically the applicable tax-law statute of limitations (typically 3–7 years for federal income tax; longer for specific issues like fraud, understatement of income over 25%, or foreign asset reporting). Tax reps are often given "fundamental" treatment.
- **General reps** (financial statements, absence of undisclosed liabilities, contracts, employment, etc.) — typically 12–24 months. The ABA Private Target Deal Points Study distributions typically show a median of ~18 months for general reps in recent cycles.
- **Compliance / environmental / IP / privacy reps** — sometimes given general-rep treatment (12–24 months); sometimes given extended treatment (24–36 months, or up to statute of limitations for specific regulatory contexts) reflecting the longer discovery timeline for these types of exposures.
- **Covenants** — pre-closing covenants typically survive for the period specified for the corresponding rep; post-closing covenants survive per their terms.

<!-- needs-research: refresh survival-period distributions from the current-cycle ABA Private Target Deal Points Study and SRS Acquiom deal-terms study before citing to a live matter. -->

### Component 2 — Overall cap

The **cap** is the maximum aggregate liability of the seller under the indemnification package. Once the cap is reached, additional claims are barred (subject to fraud and other carve-outs).

Caps are also layered:

- **Fundamental reps** — typically capped at the full purchase price. The theory: if a fundamental rep is materially wrong, the buyer got a different transaction than they paid for, and full-price recovery is appropriate.
- **Tax reps** — typically capped at the full purchase price (given "fundamental" treatment).
- **General reps** — typically capped at 10–20% of purchase price. The 10% level is buyer-favourable; the 20% level is common in R&W-insurance-supported transactions. The ABA study distributions typically show a median of ~10% for general-rep caps in recent cycles.
- **Compliance / environmental / IP / privacy reps** — typically given general-rep treatment (10–20% cap), sometimes elevated for specific reps (IP reps often given 15–30% cap given IP-infringement risk magnitudes).

Caps are typically expressed as a specific dollar amount or as a percentage of purchase price, with the actual dollar cap frozen at signing based on the estimated purchase price.

### Component 3 — Basket

The **basket** is the threshold below which the buyer cannot bring an indemnification claim. It exists to prevent the buyer from bringing many small claims that individually may reflect ordinary transactional noise rather than meaningful breaches.

Baskets come in two types:

- **Deductible basket.** Claims below the basket are barred; claims above the basket are recoverable *only for the amount above the basket* (like an insurance deductible). E.g., a $1M deductible basket on a $1.5M claim recovers $500K.
- **Tipping basket (first-dollar recovery).** Claims below the basket are barred; once the basket is exceeded, the buyer recovers *the full amount of the claim from the first dollar*, not just the amount above the basket. E.g., a $1M tipping basket exceeded by a $1.5M claim recovers the full $1.5M.

Tipping baskets are more buyer-favourable; deductible baskets are more seller-favourable. The modal choice varies by transaction:

- **In traditional-indemnification deals**, deductible baskets are more common (perhaps 60/40 in recent cycles, per ABA data).
- **In R&W-insurance-supported deals**, the "basket" is effectively the R&W insurance retention, which functions more like a deductible.

Basket size typically ranges from 0.5% to 1.5% of purchase price. ABA distributions show ~0.75%–1% as the modal range in recent cycles.

<!-- needs-research: pull basket type (deductible vs. tipping) and basket size distributions from the current-cycle ABA Private Target Deal Points Study. -->

### Component 4 — De-minimis threshold

The **de-minimis threshold** (also called a "mini-basket" or "per-claim threshold") is the minimum size of an individual claim that can be brought. Claims below the de-minimis are not just below the basket — they are barred entirely and do not count toward the basket.

De-minimis exists to prevent trivial claims from being aggregated to reach the basket. Without a de-minimis, the buyer could bring 100 claims of $5,000 each ($500K total) that would count toward a $1M basket; with a $25K de-minimis, each $5,000 claim is barred and does not aggregate.

De-minimis thresholds typically range from $25K to $100K for transactions in the $100M–$500M range, scaled roughly with transaction size. The specific level is negotiated as part of the basket-and-de-minimis package.

### Component 5 — Sole-and-exclusive-remedy

The **sole-and-exclusive-remedy** provision states that the indemnification package is the buyer's exclusive remedy for breach of reps and covenants — the buyer cannot pursue common-law tort or contract claims for the same underlying facts. This provision, if drafted broadly, converts the entire post-closing risk-allocation into the indemnification mechanic; the buyer cannot go around the cap by suing in tort.

Standard language:

> "Except for claims of Fraud, IP Infringement, or Tax [as specifically carved out], the parties acknowledge and agree that from and after the Closing, the sole and exclusive remedy of any Indemnified Party for any breach of any representation, warranty, covenant, or agreement contained in this Agreement or any certificate delivered hereunder shall be the indemnification obligations of the Indemnifying Party set forth in this Article IX."

The sole-and-exclusive-remedy provision is heavily negotiated because it defines the *outer boundary* of post-closing risk. Buyers want carve-outs (fraud, IP, tax); sellers want no carve-outs.

### Component 6 — Carve-outs

The specific carve-outs from the sole-and-exclusive-remedy provision — and from the caps, baskets, and survival periods generally — define what the buyer can still pursue outside the standard indemnification package. Standard carve-outs:

- **Fraud.** Fraud claims are typically not subject to any cap, basket, de-minimis, or survival period — they can be pursued for the full amount of damages, for as long as the applicable statute of limitations allows. The definition of "fraud" is heavily negotiated (see below).
- **Specific carve-out categories.** IP infringement, tax exposure, and specifically-identified diligence-surfaced items are sometimes given separate cap and survival treatment — often uncapped survival to the statute of limitations, and sometimes uncapped dollar exposure (especially for specific-liability categories like environmental cleanup at a known contamination site).
- **Specific indemnities.** For specifically-identified diligence findings, the seller often provides a specific indemnity — a dollar-uncapped, timescale-uncapped commitment to indemnify the buyer for specific identified matters. Specific indemnities are usually funded through separate escrow or holdback funds.

### The "fraud" definition

The definition of fraud is a specifically-negotiated point. Two doctrinal positions:

- **Common-law fraud** — requires proof of intentional misrepresentation with intent to deceive, and reliance by the buyer. This is the buyer's minimal position.
- **Common-law fraud plus "constructive fraud" or "equitable fraud"** — includes not just intentional misrepresentation but also negligent misrepresentation or recklessly-made misrepresentation. This is the buyer's expansive position.
- **Fraud limited to specific reps** — some agreements limit the fraud carve-out to fraud in specifically-listed fundamental reps. This is the seller's protective position.

The modal outcome for a well-negotiated agreement: fraud is defined as common-law fraud (intentional misrepresentation with intent to deceive), the fraud carve-out is unlimited (no cap, no basket, no survival period), but the definition excludes constructive / negligent fraud.

The interaction between the fraud carve-out and the "sandbagging" provision (below) is subtle — a seller-favourable "anti-sandbagging" provision may bar the buyer from claiming fraud on the basis of pre-closing knowledge.

## Sandbagging and anti-sandbagging

**Sandbagging** — sometimes called the "pro-sandbagging" or "buyer-friendly" position — allows the buyer to bring an indemnification claim for a breach of rep *even if the buyer knew of the breach before closing*. The rationale: the buyer paid for the rep to be true; if the rep is not true, the buyer is entitled to indemnification regardless of whether the buyer knew.

**Anti-sandbagging** — the seller-friendly position — bars the buyer from bringing an indemnification claim for a breach the buyer knew of before closing. The rationale: if the buyer knew the rep was inaccurate and closed anyway, the buyer waived the breach.

Sandbagging language in a definitive agreement typically reads approximately:

> "The right of any Indemnified Party to indemnification pursuant to this Article IX shall not be affected by any investigation conducted by such Indemnified Party at any time, or by any knowledge acquired (or capable of being acquired) at any time, whether before or after the execution and delivery of this Agreement or the Closing Date, with respect to the accuracy or inaccuracy of any representation or warranty made by any party in this Agreement."

Anti-sandbagging language reads approximately:

> "No Indemnified Party shall be entitled to indemnification pursuant to this Article IX for any Loss to the extent such Indemnified Party had actual knowledge of the facts giving rise to such Loss prior to the Closing Date."

The default rule (in the absence of specific language) varies by state — Delaware traditionally follows a pro-sandbagging default (permitting sandbagging), while New York and some other jurisdictions may follow an anti-sandbagging default (barring sandbagging).

In modern R&W-insurance-supported deals, sandbagging is typically silent — the R&W insurance policy has its own knowledge exclusions, and the traditional sandbagging debate is subsumed into the insurance-policy negotiation.

## Escrow and holdback funding

The indemnification obligation is only as valuable as the seller's ability (or willingness) to pay. In practice, indemnification obligations are typically funded through one or more of:

- **Escrow** — a portion of the purchase price is deposited with an escrow agent (often SRS Acquiom, or a bank) at closing and released to the seller over the survival period, subject to reduction for indemnification claims. Escrow sizing typically ranges from 5% to 15% of purchase price, held for 12–24 months. See mod-103 chapter 4 for the escrow design mechanics.
- **Holdback** — similar to escrow, but the funds are held by the buyer rather than by an escrow agent. Less common than escrow because the seller has less certainty of eventual release.
- **Direct seller recourse** — for indemnification amounts above the escrow, the buyer has direct recourse against the sellers (typically the target's stockholders, joint and several). This has practical limitations — collecting from dispersed stockholders is expensive and slow; some stockholders may have spent their proceeds and be judgment-proof.
- **R&W insurance** — the R&W insurance policy provides an insurance-backed source of indemnification recovery. See chapter 7.

The escrow-to-cap ratio matters. If the escrow is $10M and the general-rep cap is $50M, the buyer has "cap" of $50M but only "collateral" of $10M — for claims above $10M, the buyer relies on direct seller recourse. This is a specific weakness of traditional-indemnification structures for widely-dispersed stockholder bases.

R&W insurance addresses this by providing an insurance-backed source of recovery that does not depend on collecting from individual sellers.

## Special indemnities

For specific diligence-identified issues, the seller often provides a **special indemnity** — a specific commitment to indemnify the buyer for a named matter, typically outside the general survival / cap / basket structure. Common special-indemnity examples:

- Known tax exposure (specific audit item, specific state-tax matter, transfer-pricing exposure).
- Known regulatory matter (specific pending investigation, specific known non-compliance).
- Known environmental matter (specific contamination site, specific historical cleanup obligation).
- Known litigation matter.
- Known IP matter (specific pending infringement claim).
- Known privacy matter (specific pending breach investigation).

Special indemnities are typically funded through a specific special-indemnity escrow (separate from the general escrow) and have their own survival period (often the statute of limitations for the specific matter). They convert an *unknown* rep-breach risk into a *known* specific-liability allocation.

## Interaction with R&W insurance

R&W insurance changes the indemnification package materially. In a typical R&W-insurance-supported transaction:

- **Reduced or eliminated escrow.** With R&W insurance covering most indemnification claims, the escrow is reduced (often to 0.5%–1% of purchase price, sometimes eliminated for the general-rep category) or eliminated entirely.
- **Reduced or eliminated seller-side indemnification.** With R&W insurance covering claims up to the policy limit, seller-side indemnification (beyond specific carve-outs and special indemnities) is often reduced or eliminated. Some deals have "walk-away" indemnification structures where the seller has no post-closing indemnification obligation for general reps.
- **The R&W insurance retention becomes the effective basket.** The retention (typically 1% of enterprise value dropping to 0.5% after 12 months) functions like a basket — the buyer bears the retention before insurance coverage attaches.
- **Fraud, IP, tax, and specific-carve-out exposure remains seller-side.** R&W policies typically exclude fraud, and some specific-carve-out categories may remain outside the policy. Chapter 7 develops.

The trade-off analysis — traditional-indemnification vs. R&W-insurance-supported — is developed in chapter 7 and is the subject of exercise 7.

## Common indemnification-negotiation moves

- **Buyer's draft has 30-month general-rep survival; seller pushes for 12–18 months.** Standard resolution: 18 months, or 12–24 months tiered.
- **Buyer's draft has 20% general-rep cap with tipping basket; seller pushes for 10% cap with deductible basket.** Standard resolution varies by transaction; benchmarking against ABA / SRS Acquiom distributions anchors the negotiation.
- **Buyer's draft has broad "fraud" definition including negligent misrepresentation; seller pushes for common-law-fraud-only.** Standard resolution: common-law fraud (intentional).
- **Buyer's draft has pro-sandbagging language; seller pushes for anti-sandbagging.** Standard resolution varies — for R&W-insurance-supported deals often silent; for traditional deals often depends on the specific negotiating leverage and jurisdiction.
- **Buyer's draft has no IP-specific carve-out; seller pushes to include IP within general-rep cap.** IP is buyer-favourable if separately capped (elevated cap for IP); seller-favourable if within general cap.
- **Buyer's draft has specific indemnity for identified diligence issue funded from general escrow; seller pushes for separate special-indemnity escrow.** Standard resolution: separate special-indemnity escrow with defined release triggers.

## Common indemnification-drafting mistakes

- **Silent on sandbagging.** Leaves the default rule to govern, which may not be what either party expects. Explicit language is safer.
- **Broad "fraud" definition.** A fraud definition that includes negligence or constructive fraud effectively eliminates the cap on many claims; sellers should push for the narrower common-law-fraud definition.
- **No de-minimis threshold.** Without a de-minimis, dozens of small claims can aggregate to reach the basket, creating claim-management burden.
- **Inconsistent survival between rep and corresponding closing condition.** If the closing condition tests the rep at "true and correct in all material respects" and the indemnification cap is broader, the buyer may be able to close with knowledge of a breach and then indemnify for the same breach. Well-drafted agreements coordinate closing conditions and indemnification.
- **Undercollateralised cap.** A large indemnification cap that is only backed by a small escrow provides theoretical protection with limited practical protection. R&W insurance fills this gap.

## Summary

The indemnification package has six interlocking components: survival period (12–24 months for general reps; longer for fundamental / tax reps), overall cap (10–20% of purchase price for general reps; up to full purchase price for fundamental / tax reps), basket (deductible or tipping, 0.5–1.5% of purchase price), de-minimis threshold, sole-and-exclusive-remedy language, and specific carve-outs (fraud, IP, tax, specific indemnities). The package is funded through escrow, holdback, direct seller recourse, and — increasingly — R&W insurance. Sandbagging / anti-sandbagging language allocates the risk of pre-closing knowledge. Special indemnities carve out specifically-identified diligence issues from the general structure. ABA / SRS Acquiom benchmarks anchor the negotiation of each component. The traditional-indemnification package is materially different from an R&W-insurance-supported package, and the choice between the two is developed in chapter 7.

Chapter 7 covers R&W insurance in detail — market conditions, underwriting mechanics, retention economics, buyer-side vs. seller-side placement decisions, and the trade-off analysis against traditional indemnification.
