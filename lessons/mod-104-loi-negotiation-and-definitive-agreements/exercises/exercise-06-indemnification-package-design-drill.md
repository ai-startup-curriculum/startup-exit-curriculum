# exercise-06: Indemnification package design drill

**Estimated effort:** 3–4 hours

## Objective

Design a complete indemnification package for a specific hypothetical transaction — every one of the six components (survival, cap, basket, de-minimis, sole-and-exclusive-remedy, carve-outs) plus the sandbagging language, the special-indemnity items, the escrow-and-holdback funding, and the interaction with any planned R&W insurance. Benchmark every specific number and structural choice against the ABA Private Target Deal Points Study and the SRS Acquiom deal-terms study.

The finished artefact is a redlined Article IX (Indemnification and Survival) plus a 3–4 page indemnification-package design memo that a General Counsel or a partner-level M&A lawyer would use as the negotiating position sheet in the definitive-agreement redline.

By the end you should be able to defend every component of the package with a specific benchmark reference, walk a board through the trade-offs, and negotiate the package against a sophisticated counterparty.

## Background

This exercise covers material from:

- [Chapter 6 — Indemnification Package Design](../06-indemnification-package-design.md) as the primary reference — the six components, sandbagging language, escrow / holdback funding, special indemnities.
- [Chapter 4 — Definitive-Agreement Architecture and the Reps-and-Warranties Layering](../04-definitive-agreement-architecture-and-reps-layering.md) — the seven-layer rep stack that the indemnification package attaches to.
- [Chapter 7 — R&W Insurance](../07-rw-insurance-mechanics.md) — for the trade-off between traditional indemnification and R&W-insurance-supported indemnification (exercise 7 develops the trade-off analysis in detail; this exercise assumes a choice and designs against it).
- [Chapter 8 — Deal-Scale Negotiation Canon](../08-deal-scale-negotiation-canon.md).

## Prerequisites

- The hypothetical transaction one-pager from earlier exercises.
- The definitive-agreement rep package from exercise 4.
- Access to the most-recent ABA Private Target Deal Points Study and SRS Acquiom deal-terms study for benchmark data on survival periods, caps, baskets, de-minimis thresholds, and specific carve-out treatment.
- If your transaction contemplates R&W insurance (typical for transactions above ~$50M enterprise value), the R&W insurance market conditions from chapter 7 and the current-cycle Marsh / Aon / Lockton market reports.

## Tasks

### 1. Set the seat and the transaction-facts overlay

Declare your seat — buy-side or sell-side — and write a 1-page transaction-facts overlay that shapes every component of the package:

- **Transaction size.** Enterprise value, equity purchase price, cash / stock / structured split.
- **Buyer profile.** Strategic vs. financial, first-time-acquirer vs. serial-acquirer, insurance-market-supported vs. self-insured.
- **Target risk profile.** Sector-specific risk (medical device, financial services, health data, AI-first, etc.), specific diligence-surfaced items that will become special indemnities, cap-table dispersion (concentrated founder + investor vs. widely-dispersed employee stockholder base).
- **R&W insurance decision.** Buyer-side policy planned? Seller-side policy? Traditional indemnification only? (Exercise 7 develops the decision; state your assumption.)
- **Escrow / holdback funding.** Available escrow-agent options (SRS Acquiom, banks). Escrow sizing constraint from mod-103 chapter 4.

### 2. Design the survival periods (component 1)

Layer the survival periods against the seven-layer rep stack from chapter 4. For each layer, name the specific survival period, the ABA / SRS Acquiom benchmark that supports it, and the specific transaction-fact-driven adjustment (if any):

- **Fundamental reps** — target 3–7 years or statute of limitations. Buy-side aim: extended. Sell-side aim: statute of limitations only.
- **Tax reps** — statute of limitations (typically 3–7 years for federal income tax, longer for specific issues).
- **General reps** — target 12–24 months. Modal ABA median approximately 18 months in recent cycles.
- **Compliance / environmental / IP / privacy reps** — modal 24 months, sometimes extended to 36 months for AI / privacy given regulatory-timeline uncertainty.
- **AI-model reps** — no established modal; propose a specific position with defence.
- **Pre-closing covenants** — typically survive per the corresponding rep period.
- **Post-closing covenants** — survive per their terms.

For each layer, add a margin comment (1–2 sentences) explaining the position.

### 3. Design the cap structure (component 2)

Layer the cap against the seven-layer rep stack:

- **Fundamental reps** — target full purchase price. Buy-side aim: full price. Sell-side aim: full price (typically no dispute at fundamental level).
- **Tax reps** — target full purchase price (given "fundamental" treatment). Some sell-side pushback for a lower cap; buy-side hold.
- **General reps** — target 10–20% of purchase price. ABA modal ~10%; higher for R&W-insurance-supported deals given the insurance-supported structure.
- **Compliance / environmental / IP / privacy reps** — target 10–20% (typically same as general reps); elevated for IP reps (15–30%) given IP-infringement claim magnitudes.
- **AI-model reps** — propose a specific position. Consider IP-infringement-claim precedent from AI-training-data litigation.

For each cap position, benchmark against ABA / SRS Acquiom distributions and note the specific transaction-fact-driven adjustment.

### 4. Design the basket (component 3)

Decide the basket type (deductible vs. tipping / first-dollar) and the basket size:

- **Basket type.** Deductible baskets are more seller-favourable; tipping baskets are more buyer-favourable. ABA data shows modal deductible-basket-preference in traditional-indemnification deals; R&W-insurance-supported deals use the retention as the effective basket. From your seat, defend the type choice.
- **Basket size.** Target 0.5–1.5% of purchase price, ABA modal approximately 0.75–1%. For a large enterprise-value transaction, the basket in absolute dollars becomes material — a 0.75% basket on a $500M transaction is $3.75M, which changes the claim-frequency dynamics.

Draft the specific basket language.

### 5. Design the de-minimis threshold (component 4)

Set the per-claim de-minimis threshold. Typical range $25K–$100K for transactions in the $100M–$500M range, scaled with transaction size. Some transactions use tiered de-minimis (higher for specific rep categories).

Consider the specific claim-frequency profile — a target with many low-value contracts has a higher-frequency low-value claim risk; a target with concentrated high-value contracts has a lower-frequency high-value claim risk. Calibrate the de-minimis to the profile.

Draft the specific de-minimis language and its interaction with the basket (claims below de-minimis do not aggregate to reach the basket).

### 6. Design the sole-and-exclusive-remedy language (component 5)

Draft the specific sole-and-exclusive-remedy language. Two positions to consider:

- **Broad sole-and-exclusive-remedy.** All post-closing claims are channelled through the indemnification package; no common-law tort or contract claims outside. Seller-favourable; caps the seller's exposure at the indemnification cap.
- **Narrow sole-and-exclusive-remedy.** Specific carve-outs for fraud, IP infringement, tax, and other specifically-named categories. Buyer-favourable; preserves the buyer's ability to pursue uncapped claims for the carve-out categories.

Draft the specific language, including the carve-out list. Consider whether each carve-out is defensible from the opposite seat.

### 7. Design the specific carve-outs (component 6)

Draft the specific carve-outs from the sole-and-exclusive-remedy and from the caps, baskets, and survival periods:

- **Fraud.** Draft the specific fraud definition — common-law fraud (intentional misrepresentation with intent to deceive) vs. broader (including negligent or constructive fraud). Buy-side aim: broad. Sell-side aim: narrow. Defend the position.
- **IP infringement.** Separate cap treatment? Separate survival? Specific IP-indemnity mechanic?
- **Tax exposure.** Uncapped survival to statute of limitations. Specific tax-indemnity mechanic.
- **Specific diligence-surfaced items.** Special indemnities for specifically-identified diligence findings — draft the specific list per section 9 below.
- **Environmental exposure (if applicable).** Extended survival and (potentially) uncapped exposure for known contamination sites.
- **Cybersecurity / privacy incidents.** Consider a specific carve-out for incidents that were unknown at signing but surface post-closing.

### 8. Design the sandbagging / anti-sandbagging language

Draft the specific sandbagging or anti-sandbagging language. From your seat:

- **Buy-side.** Pro-sandbagging — the buyer's indemnification rights are not affected by the buyer's pre-closing knowledge. Standard pro-sandbagging language is drafted in chapter 6.
- **Sell-side.** Anti-sandbagging — the buyer's indemnification rights are barred for breaches the buyer knew of pre-closing. Standard anti-sandbagging language is drafted in chapter 6.

Consider the interaction with the fraud carve-out — a seller-favourable anti-sandbagging provision may bar the buyer from claiming fraud on the basis of pre-closing knowledge, which is a subtle point.

Consider the R&W insurance interaction — R&W policies have their own knowledge exclusions, and the traditional sandbagging debate is subsumed into the insurance-policy negotiation for R&W-insurance-supported deals.

### 9. Design the special indemnities

List the specific diligence-surfaced items that would become special indemnities in your transaction. For each item, draft:

- The specific matter (e.g., "State-tax nexus exposure in California related to the 2023 SaaS-transition and the specific $X potential liability").
- The specific indemnity language.
- The specific funding source (separate special-indemnity escrow vs. general escrow vs. buyer's self-insurance vs. R&W-insurance-carved-out).
- The specific survival period (typically statute of limitations for the specific matter).
- The specific cap (typically uncapped for known specific matters; sometimes capped at a specific dollar amount for higher-risk items).

Aim for 3–5 special-indemnity items. Realistic candidates for a technology target: state-tax nexus, specific customer contract dispute, specific IP-infringement claim, specific privacy-incident aftermath, specific employment-litigation matter, specific AI-model-training-data licensing exposure.

### 10. Design the escrow-and-holdback funding

Draft the specific escrow-and-holdback structure:

- **General escrow.** For traditional-indemnification: 5–15% of purchase price, held 12–24 months. For R&W-insurance-supported: 0.5–1% for retention gap, held 12–18 months.
- **Special-indemnity escrows.** Separate escrows for each specific-indemnity item, sized to the specific-indemnity dollar exposure, held for the specific-indemnity survival period.
- **Escrow-agent selection.** SRS Acquiom is the modal choice for private-target M&A; banks (SunTrust, JPMorgan) are alternatives.
- **Escrow release choreography.** The specific claim-notice-and-release mechanic — how does the escrow agent decide to release funds vs. hold pending claim resolution?
- **Direct seller recourse.** For amounts above the escrow, direct seller recourse against target stockholders. Draft the joint-and-several vs. several-only mechanic. Consider the practical limitations of collecting from dispersed stockholders.

### 11. Draft the indemnification-package design memo

Write a 3–4 page indemnification-package design memo that walks a General Counsel or partner-level M&A lawyer through the entire package:

- The transaction-facts overlay that shapes each component.
- The specific survival / cap / basket / de-minimis / sole-and-exclusive-remedy / carve-out choices with ABA / SRS Acquiom benchmark defence.
- The sandbagging / anti-sandbagging position and its interaction with the fraud carve-out.
- The special-indemnity items with specific funding and specific survival.
- The escrow-and-holdback structure with the specific release choreography.
- The R&W insurance interaction (if applicable).
- The 3–5 open issues that will be the primary negotiating fights and the specific first-round and fallback positions on each.

### 12. Chapter-8 negotiation-canon overlay

For each of the primary indemnification-fight zones (cap size, basket type, sandbagging, fraud definition, IP carve-out), name:

- The Freund sequencing frame — when in the definitive-agreement negotiation does this fight happen?
- The Harvard frame — what is the buyer's underlying interest vs. position? Where is the interest-based middle ground?
- The Voss frame — what calibrated questions surface the other side's underlying concerns?

## Starter guidance

Common indemnification-package errors to avoid:

- **The under-collateralised cap.** A $50M general-rep cap backed by a $5M escrow provides theoretical protection but limited practical protection. For traditional-indemnification deals, the escrow-to-cap ratio matters; R&W insurance fills this gap.
- **The over-carved-out sole-and-exclusive-remedy.** Excessive carve-outs from sole-and-exclusive-remedy dilute the seller's cap protection. Buyers should push for specific carve-outs (fraud, IP, tax); sellers should push for narrower carve-outs.
- **The silent sandbagging.** Leaving the sandbagging position to state default rules creates uncertainty. Explicit language is safer.
- **The undersized de-minimis.** A too-low de-minimis creates claim-management burden. A too-high de-minimis lets the seller escape material aggregated exposure.
- **The dispersed-stockholder-recourse pathology.** For a widely-dispersed employee stockholder base, direct seller recourse for amounts above the escrow is often uncollectible in practice. R&W insurance or expanded escrow addresses.
- **The fraud-definition drift.** A broad fraud definition (including negligent or constructive fraud) effectively eliminates the cap for many claims. Sellers should push for the narrower common-law-fraud definition.

## Acceptance criteria

You can demonstrate that:

- The seat and transaction-facts overlay are declared.
- Survival periods are designed layer by layer against the seven-layer rep stack with ABA benchmark defence.
- Cap structure is designed with layered treatment (fundamental / tax / general / specific-carve-outs) and benchmarked.
- Basket type and size are chosen and defended.
- De-minimis threshold is set and calibrated to the target's claim-frequency profile.
- Sole-and-exclusive-remedy language is drafted with defended carve-out list.
- Specific carve-outs (fraud, IP, tax, environmental, cybersecurity/privacy) are drafted with defended positions.
- Sandbagging / anti-sandbagging language is drafted with defended position.
- Special indemnities cover 3–5 diligence-surfaced items with specific funding and survival.
- Escrow-and-holdback structure is drafted with specific escrow-agent selection and release choreography.
- Indemnification-package design memo is drafted at 3–4 page depth.
- Chapter-8 negotiation-canon overlay identifies frames for each primary fight zone.

## Reflection

Add a short reflection:

1. Which single component of the package is the one you are most likely to lose in the negotiation from your seat? What is the specific reason (leverage, benchmark, counterparty posture)?
2. If you are on the sell-side and the buyer refuses R&W insurance and insists on traditional indemnification with a 20% cap and 30-month survival, what is your negotiating response? Where do you land?
3. The special-indemnity items you identified — are any of them large enough that they should have driven the price down at LOI stage rather than being resolved through indemnification? What does that tell you about the diligence-and-LOI sequencing?
4. For an AI-first target: how does the AI-model-training-data-licensing exposure change the indemnification-package design? Which of the standard six components does it stretch?

## Stretch goals

- **R&W-insurance-parallel design.** Design the same package under two scenarios — traditional-indemnification-only and R&W-insurance-supported — and compare. Where are the largest dollar differences? Where are the largest structural differences?
- **Historical-transaction diagnostic.** Retrieve a specific publicly-filed indemnification-package (from an SEC-filed merger-agreement exhibit). Compare against your package. Where does the public transaction's package differ, and can you infer the specific negotiation that produced the difference?
- **AI-model-training-data-indemnity deep dive.** For an AI-first target, draft a specific AI-model-training-data indemnity that covers the specific known and unknown risks (training-data license breach, copyright infringement claims, foundation-model-provider terms-of-service breach, EU AI Act compliance). Consider the specific funding challenge — R&W insurance often excludes AI-training-data exposure.
- **Escrow-release-choreography drill.** For each special-indemnity item, walk through a specific post-close scenario where a claim is asserted. What documentation is required? What is the escrow-agent decision-mechanic? How is the claim-vs-release timing handled?
- **Cap-vs-collateral analysis.** For your traditional-indemnification package (if applicable), plot the effective collateral coverage as a function of claim size — where does the collateral run out relative to the cap? Is the gap acceptable to a sophisticated buyer?
