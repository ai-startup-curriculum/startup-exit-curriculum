# Regulatory-Filing Assessment — HSR, CFIUS, Foreign Antitrust

## Why this matters

By the time a transaction gets to signing, three separate regulatory-filing exposures have to have been assessed and — where applicable — filed:

1. **US premerger antitrust notification** under the Hart-Scott-Rodino (HSR) Act.
2. **CFIUS review** for transactions involving a foreign acquirer of a US business with any national-security dimension (technology, infrastructure, sensitive data).
3. **Foreign-antitrust filings** in any jurisdiction where the parties' combined activities meet the local premerger-notification thresholds — European Union, United Kingdom, China, and a growing list of other jurisdictions.

None of these filings is optional when its thresholds are met, and none can be structured away by clever drafting once the underlying facts are set. Each carries a **waiting period** — a statutory minimum time during which the transaction cannot close — and each carries the risk of an *investigation* that can extend that waiting period from weeks to months or, in rare cases, produce a challenge that forces the parties to divest assets, accept behavioural commitments, or abandon the transaction.

For a well-managed sell-side process, the regulatory-filing assessment happens in parallel with the diligence and definitive-agreement workstreams so that the closing-condition risk allocation, the reverse-termination fee, the "outside date" beyond which either party can walk, and the interim-operating covenants that govern the parties' conduct between signing and closing are all calibrated to the specific filing exposure. A transaction that requires HSR + EU Merger Regulation + China SAMR filings will have a materially different closing timeline (and materially different closing-condition risk) than a transaction that requires only HSR.

This chapter installs the filing frameworks at the depth a CFO / GC / senior corp-dev owner needs to (a) know when each filing is required, (b) understand the mechanics and timing of each, and (c) translate filing exposure into deal-timing and negotiating-leverage implications. Detailed filing preparation is the province of specialist antitrust and CFIUS counsel — this chapter installs the vocabulary and decision framework so that the founder / CFO / GC can meaningfully engage with those specialists.

> **Numeric thresholds move.** Every filing regime in this chapter has thresholds that are adjusted periodically (HSR annually, EU indexed to consumer price levels, others on ad-hoc political cycles). The specific numbers cited below are the values in effect at authoring. **Before relying on any of them in a live transaction, snapshot the current threshold from the primary source cited in [resources.md](resources.md).** Do not use secondary write-ups (including this one) for the live number.

## Hart-Scott-Rodino (HSR) — the US premerger-notification regime

### The statutory framework

The Hart-Scott-Rodino Antitrust Improvements Act of 1976 requires premerger notification to the Federal Trade Commission (FTC) and the Antitrust Division of the Department of Justice (DOJ) for transactions that meet specified size thresholds. The regime is administered by the FTC's Premerger Notification Office (PNO) and the Antitrust Division's Premerger Notification Unit.

The HSR requirements are set out in Section 7A of the Clayton Act (15 U.S.C. § 18a) and implemented by regulations at 16 C.F.R. Parts 801–803. The FTC updates the numeric thresholds annually based on changes in gross national product; the updated thresholds take effect in late February or early March each year and apply to transactions that close after the effective date.

### Thresholds

Two threshold tests apply. A transaction must satisfy **the size-of-transaction test** (and, for smaller transactions, also the size-of-person test) to be reportable.

- **Size-of-transaction test.** As of 2025, the threshold is approximately **$126.4 million** — a transaction where the acquiring person will hold voting securities, non-corporate interests, or assets of the acquired person valued in excess of this amount is potentially reportable. Verify the current threshold at the FTC's Premerger Notification Program page (see resources).
- **Size-of-person test.** For transactions valued at or below a higher threshold (approximately $505.8 million in 2025), the parties must also meet size-of-person requirements — one party must have annual net sales or total assets of at least the higher threshold (approximately $252.9 million in 2025), and the other party must have annual net sales or total assets of at least a lower threshold (approximately $25.3 million in 2025). Above the higher threshold, the size-of-person test does not apply (i.e., transactions above that value are reportable regardless of the parties' size).
- **Filing-fee tiers.** HSR filing fees are structured as a graduated set of tiers based on the size of the transaction, updated annually by the FTC. As of 2025, the tiers range from a lower-tier fee (in the tens of thousands of dollars) for smaller transactions to substantially higher fees (in the multi-hundred-thousand-dollar range) for very large transactions. The specific tier structure is set out on the FTC's Premerger Notification Program page. The **filing fee is a real transaction cost** and is typically allocated between the parties in the SPA (the buyer pays, or the parties split, subject to negotiation).

### Waiting period

Once both parties file HSR, a **30-day initial waiting period** begins (15 days for cash tender offers and bankruptcy transactions). During this period the transaction cannot close.

- **Early termination.** The FTC and DOJ can grant early termination, allowing the parties to close before the end of the waiting period. Early termination has been suspended and reinstated at various points; verify current PNO policy before assuming it is available.
- **Expiration or grant.** If the initial waiting period expires without further action from the agencies, the parties are free to close. This is the modal outcome for the great majority of HSR filings — most transactions produce no substantive agency action.
- **Second Request.** If either the FTC or DOJ determines that further investigation is warranted, the reviewing agency can issue a **Second Request** — a broad demand for additional documents and information. The Second Request *stops the clock* on the waiting period. The waiting period resumes only after the parties have "substantially complied" with the Second Request, and even then there is an additional 30-day post-substantial-compliance waiting period (10 days for cash tender offers).

The Second Request is the pivotal risk in HSR planning. Substantial compliance with a broad Second Request commonly takes 3–6 months, sometimes longer, and produces a Second Request response that can span millions of pages of documents and tens of employee-months of internal effort. A transaction that receives a Second Request is materially delayed and materially more expensive to close.

### Reportable and non-reportable transactions

Not every transaction above the size thresholds is reportable — the HSR rules include an extensive set of exemptions and exclusions. Common issues:

- **Acquisitions of voting securities vs. non-corporate interests.** Different rules apply to acquisitions of voting securities of corporations vs. non-corporate interests (LLC memberships, LP interests). Both can be reportable if the applicable thresholds are met.
- **Aggregation across successive acquisitions.** An acquirer that increases its ownership above a specified threshold (e.g., 25% or 50% of a target's voting securities) is treated as making a new acquisition of the incremental securities, which can trigger a new HSR filing.
- **Investment-only exemption.** An acquisition of not more than 10% of voting securities where the acquirer has no intention of participating in the target's business decisions (the "solely for the purpose of investment" exemption) can be exempt. The exemption is narrowly construed.
- **Ordinary-course-of-business exemptions.** Certain asset acquisitions in the ordinary course of business are exempt.
- **Intra-corporate transfers, executor / trustee acquisitions.** Various technical exemptions apply.

The determination of whether a specific transaction is reportable requires specialist antitrust counsel — the exemptions and aggregation rules are technical and the cost of a filing error (either failing to file when required, or filing when not required and burning weeks of unnecessary delay) is real.

### Substantive antitrust review

HSR is a *procedural* notification obligation. The substantive antitrust review is conducted under Section 7 of the Clayton Act, which prohibits mergers that "may substantially lessen competition or tend to create a monopoly" in a relevant market. The FTC and DOJ apply the Horizontal Merger Guidelines (2023 revision, updated periodically) to their analysis of transactions between competitors, and the Vertical Merger Guidelines to transactions between suppliers and customers.

- **Horizontal transactions.** Transactions between competitors receive the most scrutiny. The Herfindahl-Hirschman Index (HHI) is one screening metric — high HHI in the relevant market and a material HHI increase are red flags. Recent enforcement has focused on markets with fewer than 5 remaining competitors post-merger, "roll-up" strategies in fragmented industries, and horizontal transactions in specific sensitive sectors (pharmaceuticals, health-insurance, tech-platform, agri-tech).
- **Vertical transactions.** Historically less scrutinised, but recent DOJ / FTC enforcement (2020s) has shown increased willingness to challenge vertical deals — particularly in tech-platform and health-care markets where foreclosure of downstream competitors is at issue.
- **"Killer acquisitions."** Recent academic and enforcement attention on acquisitions of small competitors by dominant firms in tech and pharma has produced a specific enforcement discipline around transactions where the target is a plausible future competitor that the acquirer might be buying to neutralise. This is a live area of enforcement policy, and its practical implications for tech-sector M&A involving large-platform acquirers should be tracked.
- **Tech-sector specific.** The FTC has publicly signaled focus on acquisitions by large tech platforms and has (in the 2020s) challenged specific transactions on both horizontal and non-traditional theories. A sell-side to a top-4 tech platform is a transaction that should be assumed to face substantive HSR scrutiny; the specific enforcement posture at signing dictates the risk allocation.

### Interaction with deal timing and negotiating leverage

The HSR framework shapes deal timing and leverage in specific ways:

- **Signing-to-closing gap.** A cash deal with clear HSR profile might close 30–45 days after signing. A deal with substantive antitrust risk might have a signing-to-closing gap of 6–12 months contemplated in the agreement.
- **"Hell or high water" covenants.** The buyer's obligation to obtain antitrust clearance is negotiated in the SPA. Options range from "commercially reasonable efforts" (buyer must try, but not required to divest) to "reasonable best efforts" to full "hell or high water" (buyer must accept any divestiture, behavioural remedy, or condition to obtain clearance). Sellers push for stronger buyer commitments; buyers push for weaker ones. This negotiation is *the* central substantive antitrust risk allocation in the SPA and is developed further in mod-104.
- **Reverse termination fee.** For deals with material antitrust risk, the buyer often owes a reverse termination fee if the transaction is blocked by antitrust — typically 4–8% of the transaction value in high-antitrust-risk deals, and higher in specific historical high-risk transactions. The fee is a substitute for the seller's expectation damages in a failure scenario.
- **Ticking fees / interim-financing fees.** If the buyer's financing depends on closing by a certain date, seller-side fees that compensate for a delayed close can appear.
- **Outside date and drop-dead date.** The date by which the transaction must close or either party can walk. For a deal with substantive HSR risk, the outside date is set with a buffer over expected regulatory-clearance timing (typically 9–12 months, sometimes longer).
- **Interim-operating covenants.** The seller's obligations to run the business in the ordinary course between signing and closing are more restrictive in a long-close-window deal. The tension: the seller cannot be effectively hostage to the buyer's operational veto for a year while HSR is investigated.

### The HSR filing preparation

Filing preparation typically involves:

- **Item 4(c) and 4(d) documents.** The HSR form requires production of certain internal documents (strategic plans, board materials, deal-analysis memos) prepared in connection with the transaction. **This is a specific and important discipline**: any board deck, internal analysis, or third-party consultant document created about the deal that discusses market share, competitive positioning, competitor identification, or price effects will need to be produced. The choice of language in these documents affects the antitrust risk profile — a memo describing the acquisition as "eliminating our biggest competitive threat" produces a very different Second Request outcome than one describing "capability acquisition." Antitrust counsel should be engaged early in the sell-side process and consulted before internal deal materials are drafted.
- **Revenues by NAICS code.** The form requires the parties to categorise revenues by North American Industry Classification System code. Overlaps at the NAICS-6 level trigger closer scrutiny.
- **Filing timeline.** The parties file after signing. Filings can be made simultaneously by both parties or by the acquiring party alone (with the acquired party then filing separately). The waiting period starts on the last-filed party's filing.

## CFIUS — Committee on Foreign Investment in the United States

### The statutory framework

CFIUS is a US inter-agency committee chaired by the Treasury Secretary that reviews certain transactions involving foreign investment in the United States for national-security implications. The authority derives from Section 721 of the Defense Production Act of 1950, amended by the Foreign Investment Risk Review Modernization Act of 2018 (FIRRMA). CFIUS regulations are at 31 C.F.R. Parts 800 and 802.

CFIUS's scope was materially expanded by FIRRMA. Pre-FIRRMA, CFIUS reviewed only "covered transactions" that resulted in foreign control of a US business. FIRRMA expanded CFIUS jurisdiction to certain non-controlling investments in specific categories of US businesses and to certain real-estate transactions.

### Covered transactions

CFIUS jurisdiction covers three broad categories:

- **Covered control transactions.** Any transaction that results in **foreign control** of a US business — regardless of what the US business does. "Control" is broadly defined and includes not only majority equity ownership but also board representation, veto rights, and other governance arrangements that could give a foreign party the ability to determine, direct, or decide important matters affecting the US business.
- **Covered investments in TID US businesses.** Post-FIRRMA, certain **non-controlling** foreign investments in a **TID US business** (Technology, Infrastructure, or Data) are within CFIUS jurisdiction if the investment gives the foreign investor any of: access to material non-public technical information, membership or observer rights on the board, or involvement in substantive decision-making regarding sensitive personal data / critical technologies / critical infrastructure.
  - **T — Critical Technology.** US businesses that produce, design, test, manufacture, or develop specific "critical technologies" — items subject to US export controls (ITAR / EAR), items on the Commerce Control List, emerging and foundational technologies designated under the Export Control Reform Act. AI, semiconductors, biotechnology, robotics, quantum computing, and advanced materials are common flags.
  - **I — Critical Infrastructure.** US businesses involved in specific critical-infrastructure sectors — energy, transportation, telecom, financial services, defense, water, healthcare / public health, and others enumerated in Appendix A to 31 C.F.R. Part 800.
  - **D — Sensitive Personal Data.** US businesses that maintain or collect sensitive personal data on US citizens, including genetic data, financial account data, health data, biometric data, and geolocation data at defined thresholds. AI companies training on user data and consumer-facing platforms with large user bases are common flags.
- **Covered real-estate transactions.** Certain foreign real-estate transactions involving property in proximity to military installations or other sensitive government facilities are within CFIUS jurisdiction under 31 C.F.R. Part 802.

### Mandatory vs. voluntary filings

CFIUS filings can be either mandatory or voluntary depending on the transaction type:

- **Mandatory filings.** Certain transactions are subject to *mandatory* CFIUS notification, including:
  - Certain transactions involving foreign-government investment (25% or more foreign-government interest in the investor) in TID US businesses.
  - Certain transactions involving specific critical technologies subject to export controls (the specific mandatory-filing categories are defined in 31 C.F.R. § 800.401).
  - Failure to make a required mandatory filing exposes the parties to civil penalties up to the value of the transaction.
- **Voluntary filings.** Transactions outside the mandatory categories can be voluntarily notified. The primary reason to voluntarily notify is to obtain CFIUS clearance and thereby foreclose the risk of CFIUS post-close intervention (which can occur *up to any time after closing* for un-notified transactions in CFIUS's jurisdiction — there is no statute of limitations on CFIUS's ability to reach back and unwind a transaction it did not clear).

The decision whether to file voluntarily (when not mandatory) is a specific analysis: CFIUS counsel weighs the transaction-specific risk of post-close intervention against the burden of the filing process. For transactions involving foreign acquirers with any national-security nexus, voluntary notification is often the safer path.

### Declaration vs. notice — the two filing types

CFIUS filings come in two forms:

- **Short-form declaration.** A 5-page filing that permits CFIUS to complete review in a 30-day assessment period. Suitable for transactions where the parties expect a clean review. If CFIUS clears the declaration, the parties are done. If CFIUS cannot clear based on the declaration (either because of specific concerns or because the transaction is complex enough that a full review is needed), the parties may be invited to file a full notice.
- **Full notice.** A more detailed filing. The initial review is 45 days, potentially extended by an additional 45-day investigation period, potentially further extended by up to 15 days by the President for extraordinary circumstances. Total review can be up to 105 days.

For transactions with material CFIUS complexity, parties often skip the declaration and go directly to notice.

### The review process

- **Review period.** 45 days for the initial review of a full notice.
- **Investigation period.** If CFIUS identifies unresolved national-security concerns during review, the transaction moves to a 45-day investigation.
- **Mitigation agreements.** If CFIUS identifies concerns but believes they can be mitigated through specific commitments (board-composition restrictions, information-access limits, security protocols, US-person-management requirements, ongoing-reporting obligations), the parties can enter a mitigation agreement that resolves CFIUS's concerns. Mitigation agreements can be operationally intrusive — restrictions on which employees can access certain systems, requirements to segregate US operations, ongoing compliance-reporting obligations to CFIUS.
- **Presidential decision.** If CFIUS cannot clear the transaction and cannot resolve concerns through mitigation, the matter can go to the President for a decision to prohibit the transaction. Presidential prohibition is rare in aggregate but has occurred in specific cases (e.g., Broadcom / Qualcomm 2018).

### Interaction with deal timing and negotiating leverage

- **Signing-to-closing timeline.** CFIUS review can extend the signing-to-closing window materially. A declaration cleared without issue adds 30 days; a full notice with investigation and mitigation negotiation can add 4–6 months.
- **Buyer-side CFIUS-clearance covenant.** As with HSR, the SPA allocates the risk of CFIUS non-clearance. The buyer's obligation to obtain CFIUS clearance is negotiated (from "commercially reasonable efforts" through "hell or high water"); the seller's remedies if CFIUS blocks are negotiated (reverse termination fee, outside-date walk-away).
- **CFIUS-conditioned deals.** For deals with material CFIUS exposure, the closing is conditioned on CFIUS clearance. The interim period between signing and CFIUS clearance is treated similarly to HSR — with interim-operating covenants, no-shop obligations, and outside-date protections.
- **Cross-border buyers.** For sell-side transactions to non-US buyers, the CFIUS analysis is a specific gating item at buyer-selection time. A Chinese acquirer bidding for a US AI startup with material critical-technology exposure faces a materially higher CFIUS risk than a UK acquirer bidding for the same target. This exposure affects both the *probability* of clearance and the *timeline*, and should be weighed at the buyer-map stage (mod-102 chapter 3).

## Foreign-antitrust filings

Antitrust regimes exist in most major jurisdictions and impose independent premerger-notification requirements based on the parties' activities in that jurisdiction.

### European Union — EU Merger Regulation (EUMR)

Council Regulation (EC) No 139/2004 governs mergers with an EU dimension. A concentration is reportable to the European Commission if:

- The combined aggregate worldwide turnover of all the undertakings concerned exceeds €5 billion, and
- The aggregate EU-wide turnover of each of at least two of the undertakings concerned exceeds €250 million, unless
- Each of the undertakings concerned achieves more than two-thirds of its aggregate EU-wide turnover within one and the same Member State.

There is a second set of alternative thresholds involving a €2.5 billion / €100 million turnover test with additional Member-State-specific requirements. Verify the specific applicable thresholds against the EUMR text and Commission guidance.

- **Phase I review.** 25 working days (extended to 35 working days in certain cases).
- **Phase II investigation.** If Phase I raises "serious doubts," the Commission opens a Phase II investigation lasting an additional 90 working days (extendable by 20 working days).
- **Suspensory effect.** Notifiable concentrations cannot be implemented before Commission clearance ("stand-still obligation").
- **One-stop shop.** A concentration that meets the EUMR thresholds is reviewed exclusively by the European Commission — Member State competition authorities do not review in parallel. However, transactions below EUMR thresholds can be subject to individual Member State premerger notification obligations (Germany, France, Austria, Italy, etc., each have their own regimes with separate thresholds).

### United Kingdom — CMA merger control

Post-Brexit, the UK Competition and Markets Authority (CMA) has jurisdiction over transactions affecting the UK independently of any EU review. UK merger control is technically **voluntary** — there is no mandatory pre-notification obligation — but the CMA can review transactions post-close and can order divestment or unwinding, so parties commonly notify voluntarily for large or sensitive transactions.

- **Jurisdictional thresholds.** Turnover test (UK turnover of the target exceeding £70 million) or share-of-supply test (parties together supply at least 25% of a UK market and the merger increases that share).
- **Timeline.** 40 working days Phase 1, plus 24 weeks Phase 2 if the CMA opens a full investigation.

### China — SAMR (State Administration for Market Regulation)

China's Anti-Monopoly Law requires premerger notification to SAMR when the parties' combined worldwide turnover exceeds RMB 10 billion (or Chinese turnover exceeds RMB 2 billion), and at least two parties each have Chinese turnover exceeding RMB 400 million (thresholds updated periodically, most recently in 2024).

- **Timeline.** 30-day Phase I, potentially extended by a 90-day Phase II and further 60-day Phase III.
- **Suspensory effect.** Transactions cannot close before SAMR clearance.
- **Practical timeline.** SAMR review commonly takes materially longer than the statutory timeline for larger or politically-sensitive transactions.

### Other foreign filings

Additional foreign filings that recur in cross-border transactions:

- **Germany — Federal Cartel Office (Bundeskartellamt).** German-specific thresholds; potentially applicable even when EUMR applies (for the specific transaction-value threshold under German law).
- **India — Competition Commission of India (CCI).** Threshold-based mandatory notification.
- **Brazil — CADE.** Threshold-based mandatory notification.
- **Japan — JFTC.** Threshold-based mandatory notification.
- **South Korea — KFTC.** Threshold-based mandatory notification.
- **Canada — Competition Bureau.** Threshold-based mandatory notification.
- **Mexico — COFECE.** Threshold-based mandatory notification.
- **Australia — ACCC.** Voluntary notification regime.

For each jurisdiction where either party has revenue, employees, assets, or significant customer relationships above the applicable threshold, a specific filing assessment is required. Global antitrust counsel typically manages the multi-jurisdictional filing matrix.

### Interaction with deal timing

- **Multi-jurisdictional filings.** A transaction requiring filings in 6+ jurisdictions has a filing-project-management dimension that dominates the closing timeline. Filings are typically made in parallel, but clearances arrive on different schedules; the closing is conditioned on the *last* clearance.
- **Sequencing.** Some regimes have translation and localisation requirements that affect filing preparation timing. Chinese SAMR filings require Mandarin translation of substantial materials; German filings require German-language filings.
- **Coordination with HSR.** Some transactions have HSR clearance before foreign clearances (US being faster than certain jurisdictions); others have foreign clearances before HSR (particularly if a US Second Request is issued). The interim-operating covenants and closing-condition drafting must accommodate whichever clearance is last.

## Translating filing exposure into deal-timing and negotiating leverage

The filing exposure is not just a procedural item — it is a specific transaction-design input that affects the SPA structure. Key implications:

### For the seller

- **Signing-to-closing gap.** Longer with more filings. Interim-operating covenants restrict business-decision authority for that period; the seller loses operational optionality.
- **Deal-certainty risk.** The longer the gap, the greater the risk of market conditions changing, a competing offer emerging, a MAC / MAE event materialising, or the buyer walking. Sellers price this into the headline number and into the reverse-termination-fee structure.
- **Employee-retention risk.** Employees learning of a pending sale face uncertainty for the entire gap. A 12-month gap is materially worse for employee retention than a 2-month gap.
- **Customer-and-partner risk.** Customers may hold new orders and partners may delay renewals during the gap.
- **Cash-vs-stock consideration.** For an all-stock deal, the seller's shareholders are exposed to acquirer-stock-price movement during the gap; collar mechanics (chapter 2) partially mitigate this exposure.

### For the buyer

- **Filing costs.** Direct filing fees (HSR alone can be a large filing fee at the top tier) plus specialist-counsel fees for filings in multiple jurisdictions can add materially to transaction expense.
- **Business-integration delay.** The buyer cannot integrate the target before closing. Longer gaps delay synergy realisation.
- **Regulatory-clearance-obligation covenants.** Sellers push buyers to accept stronger clearance-obligation covenants — potentially "hell or high water" for high-risk deals. This is a material buyer-side risk allocation.
- **Divestiture risk.** In the highest-risk deals, the buyer may need to commit to divesting specific assets to obtain clearance. This changes the buyer's net-of-divestiture economics.

### For the sale-process design

The buyer-map / pre-marketing / LOI-management workstreams from mod-101 and mod-102 should assess filing exposure as a specific dimension of buyer selection:

- **A buyer with high antitrust risk in the target's core market** requires stronger SPA protections (hell-or-high-water, larger reverse-termination fee, longer outside date). This can be priced into the LOI, but it also affects deal-certainty — a high-antitrust-risk buyer offering a 5% premium may be a worse expected outcome than a low-risk buyer offering the same price.
- **A cross-border buyer with CFIUS exposure** faces both antitrust and CFIUS timelines. A 6–12 month combined regulatory timeline is not uncommon.
- **A buyer's antitrust history** — including prior Second Requests, prior divestiture commitments, and prior blocked transactions in the target's sector — is a material input to the sale-process risk assessment. This is one of the buyer-map research inputs from mod-102 chapter 3.

## Common pitfalls and practitioner notes

- **Filing analysis started too late.** The HSR / CFIUS / foreign filing assessment should begin at the LOI stage, not at the definitive-agreement stage. Waiting until definitive negotiations means the parties have already made structural commitments that may not reflect the actual regulatory-clearance risk.
- **HSR Item 4(c) discipline missed.** Board decks and internal deal-analysis memos are producible under Item 4(c) and set the tone for substantive antitrust review. If the sell-side team has been producing high-competitive-tension memos without antitrust-counsel calibration, the Second Request risk is elevated.
- **CFIUS jurisdiction assumed to require Chinese-buyer or defense-related target.** Post-FIRRMA, CFIUS reaches far broader — any foreign acquirer of a TID US business is in-scope. Genetic-data companies, AI-training-on-user-data companies, telematics providers, and other consumer-tech companies routinely have CFIUS exposure that would have been unimaginable pre-FIRRMA. The scope should be assessed against the current regulations, not against prior intuitions.
- **Foreign-antitrust thresholds not systematically screened.** Cross-border transactions require a systematic multi-jurisdictional filing screen. Skipping a required filing because the parties did not realise they had revenue over the threshold in a specific jurisdiction produces post-close enforcement risk and potential fines.
- **Reverse termination fee under-negotiated.** For a high-regulatory-risk deal, the reverse-termination fee is the seller's substitute for expectation damages. Under-negotiating this leaves the seller exposed to the buyer walking with no material downside for the buyer.
- **Interim-operating covenants over- or under-drafted.** For a long-close deal, the seller's ability to run the business between signing and closing is a substantive negotiating point. Over-restrictive covenants hostage the business to the buyer; under-restrictive covenants expose the buyer to seller conduct that changes the value of what they are buying. Both extremes recur in poorly-negotiated SPAs.
- **Failure to plan for outside-date extensions.** Even a well-planned deal can face regulatory extensions the parties did not anticipate. The SPA should include mechanics for extending the outside date on specified conditions (e.g., if a Second Request is still active, if a CFIUS mitigation-agreement is in active negotiation). Without extension mechanics, either party can be forced to walk from an otherwise closing-worthy transaction because of an arbitrary date.

## Summary

Regulatory-filing exposure is a specific and consequential dimension of transaction design. HSR premerger notification applies at defined US thresholds (approximately $126.4M size-of-transaction in 2025, verify at FTC.gov), imposes a 30-day initial waiting period, and carries Second Request risk that can extend closing by 3–6 months for substantive review. CFIUS reviews foreign investment in US businesses with national-security dimensions — expanded post-FIRRMA to reach TID US businesses (Technology, Infrastructure, Data) even in non-controlling investments — and can require mitigation agreements or block the transaction outright. Foreign antitrust regimes in the EU, UK, China, and other major jurisdictions impose independent premerger-notification obligations with their own thresholds and timelines. The filing exposure translates into signing-to-closing gap, reverse-termination-fee structure, interim-operating covenants, and buyer-side clearance-obligation commitments. For a cross-border transaction with multiple filings, the closing timeline can extend to 9–12 months, and the SPA design must accommodate that reality. Detailed filing preparation is the province of specialist antitrust and CFIUS counsel — this chapter installs the vocabulary and decision framework so that founders / CFOs / GCs can meaningfully engage. Numeric thresholds change frequently; always verify against primary sources before relying on a specific number.
