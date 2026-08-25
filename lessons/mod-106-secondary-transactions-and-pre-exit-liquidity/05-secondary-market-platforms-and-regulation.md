# Secondary-Market Platforms and the FINRA / Rule 144 / Section 4(a)(7) Regulatory Framework

## Why this matters

Founder secondaries (chapter 1) and employee tenders (chapters 2–3) are transactions the target company itself organises. Structured secondaries (chapter 4) run through specialist bilateral counterparties. But there is a fourth category: **secondary-market platforms** that connect private-company shareholders with third-party buyers on a standing basis, outside any specific tender or company-organised event. Forge Global (formerly SharesPost), EquityZen, Nasdaq Private Market (NPM), Carta's Carta X, and PARAGON Prime, along with FINRA-registered broker-dealer participants like Rainmaker Securities, together run the electronic and negotiated infrastructure through which billions of dollars of private-company stock changes hands each year without the target's active organisation.

For a target company, these platforms are not neutral. They introduce a market for the company's common stock that may or may not correlate with the target's own 409A view, they generate transaction data that becomes part of the target's disclosure footprint in future M&A or IPO diligence, and they create ongoing ROFR / co-sale mechanics the target must operate. For a shareholder, they represent a class of counterparties and mechanics distinct from the company-organised paths — sometimes the only path available when the company is not running a tender.

Both audiences must understand the **regulatory framework** that governs private-company-security resales in the United States. The framework is a specific stack: **Section 4(a)(7)** of the Securities Act as an exemption from Section 5 registration for private-company resales; **Rule 144** as a longer-established exemption path with holding-period and volume-limitation mechanics; **Rule 144A** as an exemption for resales to qualified institutional buyers; **FINRA Notice 09-05** as the regulatory guidance that shapes private-company-security broker-dealer conduct; and the blue-sky rules of each state where the transaction touches. Without a valid exemption for each specific resale, a private-company-security transfer can be an illegal offer or sale of unregistered securities, exposing the seller, the buyer, and the platform to Section 5 liability.

This chapter installs the platform landscape and the regulatory framework as a practitioner would use them — the specific platforms and their differences, the specific exemption mechanics and their interactions, and the specific compliance work the target company and its counsel must perform to keep the resale mechanics defensible.

> **Reminder: education, not legal or securities-law advice.** Every private-company-security resale requires a specific exemption analysis by securities counsel. This chapter installs the vocabulary for evaluating platforms and structuring the target's response to platform activity; the specific compliance analysis for any transaction requires qualified counsel.

## The regulatory framework — Section 5 and the exemption stack

Section 5 of the Securities Act of 1933 (15 U.S.C. §77e) prohibits the offer or sale of a security unless the offering is registered with the SEC or an exemption from registration applies. A private-company share, held by a founder, employee, or investor, is a security. Every resale of that share is either registered or exempt. Because private-company shares are essentially never registered (the target has not filed an S-1 with the SEC), every resale must fit within an exemption.

The exemptions that apply to private-company-security resales:

- **Section 4(a)(1)** — exempts *transactions* by any person other than an issuer, underwriter, or dealer. Historically the default resale exemption; but a resale by an *affiliate* (a control person of the target, or a person acting in concert with one) does not qualify because affiliates are treated as underwriters. Non-affiliates can generally rely on 4(a)(1), but the *purchaser*'s status as an underwriter (if they will resell shortly) becomes the practical concern.
- **Rule 144** — the SEC's safe-harbour for resales that satisfy holding-period, current-information, and volume-limitation requirements. Provides a compliant resale path for both affiliates and non-affiliates.
- **Section 4(a)(7)** — enacted in 2015 as part of the FAST Act. Exempts resales that meet specific accredited-investor-buyer, information-delivery, and non-public-offering conditions. Designed specifically to accommodate private-company-security secondary trading.
- **Rule 144A** — exempts resales to qualified institutional buyers (QIBs — institutions with $100M+ in securities under management). Used primarily in fixed-income and public-side offerings but occasionally in private-company secondaries where the buyer qualifies.
- **Section 4(a)(2)** — exempts *transactions* not involving a *public offering*. Historically the general private-placement exemption used for primary issuances, but occasionally used by counsel for resales in specific fact patterns.

The practitioner default for private-company secondary transactions is generally either **Section 4(a)(7)** (for post-2015 accredited-investor-buyer resales, which is where most platform activity lives) or **Rule 144** (for resales that satisfy the specific holding period and volume rules). Each exemption has specific requirements the transaction must satisfy.

### Section 4(a)(7) mechanics

Section 4(a)(7) is the modern practitioner's workhorse for private-company secondary transactions. Its requirements:

- **The purchaser is an accredited investor** (as defined in Rule 501 of Regulation D). This is the buyer-side eligibility filter.
- **Neither the seller nor a person acting on the seller's behalf engages in general solicitation or general advertising** of the offer.
- **The issuer is not a shell company, blank-check company, or subject to certain disqualifying conditions** (an issue in some SPAC-related fact patterns but usually not for operating growth-stage companies).
- **The issuer is not a Section 15(d) reporting or Exchange Act reporting company, or if it is, the target complies with periodic reporting.**
- **The seller and any broker-dealer involved delivers specific information about the issuer to the buyer** — the target's most-recent balance sheet, income statement, cash-flow statement; the issuer's identity and business overview; certain information about the seller's ownership; and (typically) a "reasonable inquiry" attestation from the seller as to their non-affiliate status if applicable.

Section 4(a)(7) is intentionally designed to be usable by secondary-market platforms — the accredited-investor and information-delivery mechanics can be operationalised through platform workflow, and the platforms (Forge, EquityZen, Carta X) all administer 4(a)(7) transactions as part of their standard flow.

### Rule 144 mechanics

Rule 144 is the older, more well-established safe-harbour. It applies differently to non-affiliates and affiliates.

- **Non-affiliate resales**: after a **6-month** holding period (for reporting-company shares) or a **12-month** holding period (for non-reporting-company shares — the private-company case), non-affiliates can resell without any volume, manner-of-sale, or current-information restrictions. This is the cleanest resale path for a long-tenured private-company shareholder who is not an affiliate.
- **Affiliate resales**: even after the holding period, affiliates are subject to *ongoing* Rule 144 restrictions — volume limitation (in any three-month period, cannot exceed the greater of 1% of the issuer's outstanding shares or the average weekly trading volume for the four preceding weeks), manner-of-sale requirements (typically brokers' transactions), current-information availability, and Form 144 filing for large transactions.

For a private-company target with employees and founders who are technically "affiliates" (holding board seats, executive officer positions, or controlling shareholder positions), Rule 144 does not provide a clean resale path — the ongoing restrictions apply. This is why Section 4(a)(7) has become the practitioner default for founder / executive secondaries: it does not distinguish affiliate from non-affiliate.

### Rule 144A mechanics

Rule 144A is a more limited exemption that applies only to resales to **qualified institutional buyers (QIBs)** — institutions with $100M+ in securities under management. It carries no holding-period requirement, no volume limitation, and no manner-of-sale restriction, but it is limited to the specific QIB-buyer universe.

Rule 144A is used primarily in fixed-income secondary trading and in specific institutional-only private-company secondary transactions. It rarely appears in individual-shareholder secondary transactions because the buyer universe is much smaller than the accredited-investor pool addressable under Section 4(a)(7).

## FINRA Notice 09-05 and the broker-dealer disclosure discipline

FINRA Regulatory Notice 09-05, issued in 2009, addresses the regulatory obligations of FINRA-member broker-dealers participating in private-company secondary transactions. The Notice was the industry's first coherent regulatory framework for private-secondary-market broker-dealers and set the practitioner discipline that persists today.

The Notice's core requirements:

- **Suitability and reasonable-basis due diligence.** A broker-dealer facilitating a private-company-security purchase for a customer must conduct reasonable-basis due diligence on the target company and its securities before recommending or facilitating the transaction. This is not equivalent to an S-1's diligence depth, but requires the broker-dealer to obtain basic information about the target's business, financial condition, and management.
- **Customer-specific suitability.** The broker-dealer must reasonably believe the transaction is suitable for the specific customer given the customer's investment objectives, financial situation, and other relevant facts.
- **Information delivery.** The broker-dealer must deliver material information about the target to the customer, calibrated to what the target has been willing to disclose.
- **Fair dealing and best execution.** The broker-dealer's pricing, commissions, and mark-ups must be reasonable relative to the transaction, and best-execution obligations apply.
- **Anti-manipulation.** The broker-dealer must not engage in market manipulation of the private-company security's price through coordinated trading, false or misleading marketing, or other manipulative conduct.

The Notice's most consequential practical implication: broker-dealer platforms cannot facilitate trading in private-company securities where the target's information posture is opaque. If the target refuses to provide the platform with the basic information a broker-dealer must convey to its customer, the broker-dealer cannot proceed. This creates a specific negotiation between target companies (who often want to control the information flow about their securities) and platforms (who need the information to run their business).

The practitioner-observable pattern: target companies at growth stage typically negotiate specific **information-provision agreements** with the major secondary-market platforms — a defined set of quarterly or annual information that the target agrees to provide to the platform's broker-dealer arm, in exchange for the platform's agreement to route transactions through specific mechanics that align with the target's ROFR / co-sale ruleset. The target's finance and legal functions typically own the platform-relationship discipline.

## Blue-sky compliance across state jurisdictions

Beyond federal exemptions, every private-company secondary transaction is potentially subject to the **blue-sky securities laws** of every state where the transaction touches (typically the seller's residence, the buyer's residence, and any state where the transaction is offered or advertised).

Historically, blue-sky compliance was a significant administrative burden — each state had its own registration or exemption requirements, and multi-state transactions required specific per-state analysis. The **National Securities Markets Improvement Act of 1996 (NSMIA)** preempted state registration for **covered securities** (a defined category that includes securities listed on national exchanges and certain other categories), reducing the blue-sky burden for public-company transactions. But **private-company shares are not covered securities**, so state-level blue-sky compliance continues to apply to private-company secondary transactions.

The state-level exemption most commonly used for private-company secondary transactions parallels the federal Section 4(a)(2) or Rule 506 exemptions and requires filing notices in specific states (California in particular). Some states offer their own Section 4(a)(7)-analogue exemptions; others rely on general "isolated transaction" exemptions available to non-issuer resales.

The practitioner discipline for a target company is straightforward: engage securities counsel with a private-secondary-transactions practice, obtain a specific state-by-state exemption analysis for the states relevant to the target's shareholder base, and confirm that the platforms the target agrees to work with maintain compliant state-registration or exemption posture. Some platforms (Forge, EquityZen, NPM) have institutionalised the blue-sky analysis as part of their platform workflow; using their infrastructure typically satisfies the blue-sky compliance obligation without the target's counsel needing to run its own state-by-state analysis.

## The five dominant secondary-market platforms

Five platforms dominate the current secondary-market landscape for private-company shares, plus a set of specialist broker-dealers that run negotiated bilateral transactions.

### Nasdaq Private Market (NPM)

Nasdaq's private-company-securities platform. NPM is best-known for administering **issuer-organised tender offers** — the company runs a tender through NPM's platform, using NPM's tender-offer execution infrastructure, blue-sky administration, and post-close settlement. NPM has been the platform of choice for many of the largest late-stage tenders in the last decade (WeWork, Lyft, Airbnb, Palantir, Coinbase, and others in the pre-IPO period).

NPM's tender-offer administration is highly institutional. It runs the tender-offer paper administration, the participant-election workflow, the aggregate-cap and proration mechanics, and the post-close cap-table update. For a target company running a large tender, NPM's platform reduces the operational lift on the target's own finance and legal teams significantly.

Beyond the tender-offer product, NPM has (at times, with varying commitment) offered a **secondary-market venue** for standing private-company-share trading — buyers and sellers matched on the platform with NPM as the broker-dealer intermediary. The venue's activity has varied over time; NPM's flagship product is the tender-offer administration.

### Forge Global (formerly SharesPost)

Forge Global is the leading pure-play private-company secondary marketplace. Forge operates as a **secondary-market clearing venue** — buyers and sellers post interests, transactions clear on the Forge platform, and Forge acts as the FINRA-registered broker-dealer intermediary. Forge's platform runs standing transactions across a broad universe of pre-IPO companies (typically growth-stage venture-backed companies with a plausible 24–36-month liquidity path).

Forge's pricing model is transaction-fee-based (typically a few percent of transaction value). Forge maintains information-provision relationships with a large number of target companies; where the target participates in the Forge information-sharing programme, Forge can facilitate transactions in the target's stock. Where the target does not, Forge does not facilitate transactions.

Forge acquired SharesPost in 2020 and went public (via SPAC merger with Motive Capital Corp) in 2022, trading on the NYSE under FRGE. Forge's public-company financial reporting provides an unusual public window into the secondary-market activity across a broad set of private targets.

### EquityZen

EquityZen is a **buyer-and-seller matching platform** focused on the accredited-investor buyer segment. EquityZen structures transactions predominantly as **special-purpose-vehicle (SPV) purchases** — a group of accredited-investor buyers pool capital into an EquityZen-organised SPV, and the SPV purchases shares directly from the seller. The SPV structure lets EquityZen aggregate small individual-investor commitments (a $10K accredited-investor commitment can participate in the SPV's larger transaction) into transaction sizes meaningful to sellers.

EquityZen's fee structure includes both seller-side and buyer-side fees (typically 5% seller-side, 5% buyer-side). The SPV structure means the ultimate buyer is the SPV rather than the individual accredited investors; from the target's cap-table perspective, the transaction adds one holder (the SPV), not multiple individual holders. This can be attractive to targets managing shareholder count against the 2000-shareholder threshold that triggers Exchange Act reporting obligations under Section 12(g).

### Carta X (Carta's secondary-market venue)

Carta's own secondary-market venue, launched to leverage Carta's position as cap-table platform of record for a large fraction of venture-backed companies. Carta X integrates directly with the target's Carta cap-table record, offering issuer-organised secondary programmes and (in some configurations) a broader marketplace function.

Carta X has been repositioned and rescoped several times as the company's business strategy has evolved. Its current product mix emphasises **issuer-organised programmes** (Carta's tender-offer administration and issuer-controlled secondary programmes) rather than a pure secondary-market venue.

For target companies already using Carta as their cap-table platform, Carta's tender-offer and issuer-programme products offer the tightest integration between the transaction and the cap-table record.

### PARAGON Prime

PARAGON Prime is a specialist secondary-market broker platform focused on late-stage growth-company secondaries with an institutional-buyer focus. PARAGON has historically been active in the largest single-block transactions — where an executive or founder is selling a nine-figure block to an institutional buyer — and in structured secondary transactions.

PARAGON's operational profile is more bilateral-negotiated than the standing-marketplace platforms; a large fraction of PARAGON's activity involves specific buyer-seller matching with negotiated pricing rather than an order-book venue.

### FINRA-registered broker-dealer participants

Beyond the named platforms, a set of FINRA-registered broker-dealers participate in private-company secondaries under their broker-dealer registrations. **Rainmaker Securities** (noted in chapter 4) is one of the most active. **Zanbato** operates a broker-dealer-run bilateral-transaction platform for institutional participants. Numerous smaller broker-dealer boutiques serve the founder-and-executive-scale secondary space.

The FINRA-registration status of a broker-dealer participant materially affects the transaction's regulatory posture. FINRA-registered broker-dealers are subject to FINRA Notice 09-05's obligations (suitability, disclosure, best execution); unregistered principals or intermediaries are not, though they must still avoid engaging in broker-dealer activity that requires registration.

## The target company's platform-relationship posture

A growth-stage target company approaches the secondary-market platform landscape from three angles:

### Angle 1 — Passive posture ("we don't participate")

The target refuses to provide information to platforms, refuses to permit direct transfers of its shares outside its ROFR / co-sale ruleset, and does not engage with the platform ecosystem. This posture is defensible at earlier stages but becomes increasingly costly as the company scales — employees who cannot access secondary liquidity accumulate paper positions they cannot realise, and the company's inability to run its own tender offers (which typically require the same platform infrastructure) becomes a workforce-compensation issue.

### Angle 2 — Selective posture ("information-provision to specific platforms, ROFR discipline on all transfers")

The target provides information to a defined set of platforms (typically Forge, sometimes EquityZen or NPM) under a specific information-sharing agreement, and runs its own ROFR / co-sale discipline on every transfer whether platform-facilitated or bilateral. This is the modal posture at growth stage — the target participates in the platform ecosystem as a controlled participant, capturing the benefits (employee-liquidity availability, information-flow discipline) while maintaining transaction control.

### Angle 3 — Active posture ("run our own tender programme through NPM / Carta")

The target runs its own tender-offer programme on an annual or 18-month cadence (chapter 2), typically administered through NPM, Carta, or a specialist administrator. The target's information posture with third-party platforms is a secondary consideration — the tender programme is the primary workforce-liquidity mechanism, and third-party platform activity is tolerated or suppressed depending on the target's specific ROFR / co-sale discipline.

Between angles 1 and 3, most growth-stage AI-and-SaaS targets today land at angle 2 with movement toward angle 3 as they approach IPO or pre-IPO scale.

## The information-disclosure trap for target companies

A specific structural risk the target must manage: **information provided to secondary-market platforms becomes a disclosure item in future M&A and IPO diligence**.

The pattern. The target enters an information-sharing agreement with Forge in 2023 to enable secondary-market activity in its stock. The target provides quarterly financials, quarterly business updates, and management-team information to Forge under a specific access-controlled arrangement. In 2025, the target enters M&A discussions and the acquirer's counsel identifies the information-sharing agreement during diligence. The acquirer asks: what information was shared, when, and did that information subsequently become material non-public information relative to a specific event? The target must produce the specific documentation.

Similarly, in an IPO S-1 review, the SEC's Division of Corporation Finance staff may request disclosure of secondary-market activity in the target's stock during the reporting periods, and the specific information provided to platforms during that period may become a disclosure item.

The practitioner discipline: the target maintains a specific **information-sharing record** — every piece of information provided to every platform, dated, with the platform's access-and-distribution terms. The record is maintained as part of the corporate records file and is available for future diligence review. Failure to maintain this record can turn a straightforward diligence request into a full document-recovery exercise.

## The 409A interaction — secondary-market pricing as a 409A input

Section 409A's fair-market-value discipline for common stock (chapter 8) requires the company's 409A appraiser to consider material observable transaction prices for the company's shares. Secondary-market transactions in the target's stock, if visible to the 409A appraiser, become an *input* to the 409A analysis.

The interaction is complex. If a large volume of secondary transactions clears at $50/share and the target's most-recent primary-round preferred was at $85/share, the 409A appraiser must reconcile the two — typically by weighting the observable secondary price alongside the primary-round price in the option-pricing model or PWERM analysis. The result can be a 409A common price higher than a pure preference-stack-adjusted common price would produce, driving subsequent ISO strike prices higher for new grants (a workforce-compensation cost) but potentially aligning better with actual employee-realisable liquidity value (a workforce-communication benefit).

Practitioner discipline: the target's finance function should specifically discuss secondary-market activity with the 409A appraiser at each valuation cycle, and should manage the platform-relationship posture (angles 1-3 above) with an awareness of the 409A implications.

## Summary

The secondary-market platform landscape — Forge Global, Nasdaq Private Market, EquityZen, Carta X, PARAGON Prime, and FINRA-registered broker-dealer participants like Rainmaker Securities — provides ongoing private-company-secondary infrastructure outside company-organised tender offers or bilateral founder secondaries. Every transaction on these platforms requires a valid federal exemption (Section 4(a)(7) as the modern default, Rule 144 for holding-period-based resales, or Rule 144A for QIB-buyer transactions), FINRA-conduct-compliant broker-dealer participation (FINRA Notice 09-05's suitability, disclosure, best-execution obligations), and state-level blue-sky compliance across every relevant jurisdiction. Target companies navigate the ecosystem through a passive / selective / active posture; the modal growth-stage posture is selective — information-provision to specific platforms with ROFR / co-sale discipline on every transfer. The information-provision trap and the 409A-input interaction require deliberate management by the target's finance and legal functions. Chapter 6 turns to the ROFR / co-sale choreography that underlies every private-company-share transfer, whether platform-facilitated, bilateral, or embedded in a tender offer.
