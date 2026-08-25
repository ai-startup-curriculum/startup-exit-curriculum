# Term-Sheet Architecture — IOI, LOI, and the Path to Definitive

## Why this matters

At the moment a sell-side process hands a written offer over to the target's board, the transaction changes shape in ways the founding team almost never appreciates in advance. Up to that point the process has been a marketing exercise — teaser, CIM, management presentations, one-on-one meetings — and the target's counsel has been reviewing NDAs, not drafting contracts. Once a written offer is in hand, three questions decide what happens next: **what portion of this document is binding**, **what portion of it locks the target into an exclusive negotiation**, and **which round of the sale process is this**. The wrong answer to any of the three loses the target hundreds of basis points of negotiating leverage or, in the worst case, exposes the board to a fiduciary-duty challenge that later blocks the deal or triggers stockholder litigation.

Practitioners handle this with a two-round pattern that separates *interest* from *commitment*. Round 1 produces a set of **nonbinding indications of interest** — IOIs — that let the target compare bidders on price, structure, and process posture without committing to any of them. Round 2 produces a **binding LOI** (also called a *term sheet*, an *exclusivity letter*, or a *letter of intent* — the labels vary; the substance is what matters) from the winning bidder that names purchase price, structure, and consideration and creates a small set of binding obligations — most importantly exclusivity — while leaving the remainder of the transaction to be negotiated in the definitive agreement over the following 30 to 90 days. This chapter installs that architecture: what each document actually is, what portion of each is binding, what an LOI locks in, and the drafting sequence that flows into the definitive agreement.

Two vocabulary points before we start. First, the term *term sheet* is used in two distinct ways in the startup world — the priced Series A / B / C / D term sheet a founder negotiates with a lead investor (owned by [`startup-finance-fundraising-curriculum`](https://github.com/ai-startup-curriculum/startup-finance-fundraising-curriculum) mod-108) and the transaction-side term sheet a target signs with an acquirer. This chapter — and this module — is about the *transaction-side* term sheet. If you find yourself thinking about protective provisions, board seats, and 1x-non-participating preferred, you are in the wrong module. Second, LOI, term sheet, memorandum of understanding (MOU), heads of terms, and exclusivity letter are used somewhat interchangeably in practice; the specific label matters less than the binding-vs-nonbinding architecture inside the document.

## The two-round pattern

A well-run sell-side process — whether the target is running a formal auction (see chapter 3) or a bilateral negotiation with a single strategic — moves through two written rounds before the parties reach a definitive agreement.

### Round 1 — the indication of interest (IOI)

At round 1, the sell-side banker delivers the CIM and the management-presentation record to the invited bidder set and requests written IOIs by a stated deadline (typically two to four weeks after the CIM goes out for a limited-round auction; longer for a broad auction). An IOI is a **nonbinding** letter that answers a small number of specific questions:

- **Indicative price range** — usually a range, not a point (e.g., "$450–$525M enterprise value"), sometimes framed as an EBITDA or revenue multiple, sometimes as an outright headline number.
- **Form of consideration** — cash, acquirer stock, mixed, or structured (CVR / seller-note / rollover).
- **Sources of financing** — cash on balance sheet, committed debt financing, equity commitment from a sponsor (for a PE bidder), acquirer stock (for a strategic).
- **Assumptions the price is based on** — pro-forma financial expectations, synergy assumptions (for a strategic), specific diligence workstreams the bidder wants to complete before making a binding offer.
- **Key conditions** — regulatory clearances the bidder anticipates (HSR, CFIUS if applicable), board approvals required, financing conditions.
- **Bidder background and rationale** — who the bidder is, why they want to acquire the target, and (for a PE bidder) what platform they intend to build around it.
- **Requested exclusivity** — most bidders do *not* ask for exclusivity at IOI (the target is running a competitive process and cannot grant exclusivity to any one bidder before the process concludes); a bidder who asks for exclusivity at IOI is announcing they want to short-circuit the auction.

The IOI is nonbinding except (typically) for a confidentiality provision and a limited standstill (see chapter 2). The purpose of an IOI is *information* — the target's board and banker use the IOI package to select the round-2 shortlist, and each individual IOI helps the bidder position for the next round without committing them to a specific number.

Because the IOI is nonbinding, the bidder has the latitude to price aggressively (to secure a round-2 invitation) and later revise the price downward at LOI once diligence has surfaced specific issues. This is a *feature* of the two-round pattern, not a bug — it lets bidders express real interest without over-committing early. But it also means the target's banker should read an IOI headline number with a discount that reflects the historical pattern of *IOI-to-LOI compression* in the sector.

### Round 2 — the binding letter of intent (LOI)

The target selects a shortlist from the IOI set — often two to four bidders for a limited-round auction — and invites them to a management presentation, a Q&A round, a limited diligence workstream, and a **best-and-final round** that produces LOIs. The LOI is a materially different document from the IOI:

- **Purchase price is a specific number**, not a range (though it may be subject to specified adjustments — working-capital adjustment, closing-cash adjustment, closing-debt adjustment, transaction-expense adjustment; these are the "purchase-price mechanics" negotiated in the definitive agreement per mod-103 chapter 4).
- **Deal structure is named** — asset vs. stock vs. reverse-triangular merger, and any specific tax elections proposed (§338(h)(10) for an S-corp target, F-reorg drop-down for an LLC target); see mod-103 chapter 1 for the corporate-form vocabulary.
- **Consideration mix is specified** — cash portion, stock portion, structured portion (CVR / seller-note / rollover), and the mechanics for each.
- **Financing is confirmed** — cash on balance sheet, executed debt commitment letters (from lending banks), equity commitment letters (from PE sponsors), or acquirer-stock issuance.
- **Exclusivity is requested and typically granted** — this is the single most important binding provision in the LOI; chapter 2 develops the mechanics.
- **A diligence completion timeline is proposed** — typically 30–60 days from LOI signing to definitive-agreement signing, with a hard end date after which exclusivity lapses if the parties have not signed a definitive agreement.
- **A definitive-agreement drafting responsibility is assigned** — the buyer's counsel usually delivers the first draft of the definitive agreement (SPA / Merger Agreement / APA), on an agreed timeline after LOI signing.
- **Employee-and-management arrangements are outlined** — retention pool sizing, management continuity, non-compete / non-solicit expectations. These are outlines, not binding, but they signal what the buyer expects.
- **Regulatory-filing responsibilities are assigned** — who prepares and files HSR (typically both parties file, at $$ specific tiered fees), CFIUS if applicable, foreign antitrust if applicable.

The LOI is **partially binding**. Specific provisions are binding — exclusivity, confidentiality, expense-reimbursement / break-up-fee (where applicable), publicity restrictions, choice of law, sometimes a standstill on the target's other transaction activity. The rest — price, structure, consideration mix, definitive-agreement terms — is nonbinding, contingent on the definitive-agreement negotiation reaching agreement. This binding-vs-nonbinding split is *the* central architectural point of the LOI and the source of most drafting mistakes.

## What is binding, what is nonbinding, and how the document says so

The binding-vs-nonbinding architecture is typically implemented in one of two ways:

### The "binding provisions" section pattern

The LOI is organised into two parts. Part I contains the substantive economic and structural terms of the proposed transaction (price, structure, consideration, timeline, employee arrangements, regulatory strategy). Part II is titled something like "Binding Provisions" or "Binding Obligations" and enumerates the specific provisions that are legally binding — exclusivity, confidentiality, expense-reimbursement, publicity, choice of law and forum, and (in some patterns) a break-up fee.

The document then contains an explicit statement — typically at the end of Part I or the beginning of Part II — that reads approximately: *"Except for the provisions expressly set forth in [Section X: Binding Provisions], this Letter of Intent is intended to be an expression of the parties' mutual intent to proceed toward a definitive Agreement and does not constitute a binding agreement to consummate the transaction described herein. Neither party shall have any legal obligation to the other with respect to the transaction until such time as a definitive Agreement is executed."*

This structure is the modal pattern in venture-backed private-company M&A and is what most practitioner counsel drafts by default.

### The "letter agreement plus separate side letter" pattern

An older pattern separates the nonbinding term sheet (the exchange of proposed economic terms) from a separate binding side letter that governs exclusivity, expense reimbursement, and standstill. This is drafting-cleaner in some respects — there is no ambiguity about whether the exclusivity provision inside the term sheet is binding — but it is procedurally clunkier and less common in modern practice. Some UK / European transactions still use it.

### Why the binding-vs-nonbinding line matters

A significant body of case law addresses whether an LOI or term sheet gives rise to enforceable obligations even when the parties intended it to be nonbinding. The specific hazard is a **"duty to negotiate in good faith"** implied from the LOI even where the LOI does not by its terms create a binding agreement to consummate the transaction. Delaware, New York, and other commercial jurisdictions have developed doctrines around this — the *SIGA Technologies v. PharmAthene* line of cases in Delaware is the most-cited practitioner reference, where a term sheet with a "proposed" set of terms was held to create an enforceable duty to negotiate in good faith and where the party that walked away was held liable for expectation damages.

<!-- needs-research: verify current standing of SIGA v. PharmAthene and any subsequent Delaware Supreme Court holdings shaping the enforceability of "type II" preliminary agreements; the *Empro Manufacturing v. Ball-Co Manufacturing* Seventh Circuit case and the *Teachers Insurance and Annuity Association v. Tribune Co.* case are the classic doctrinal anchors and should be double-checked before citing to a live matter. -->

Two implications for drafting:

1. **Say what you mean.** If the parties intend the LOI to be nonbinding except for enumerated provisions, the document must state that clearly and unambiguously, in language a court will not read against the drafter. Vague or optimistic language ("the parties will use their best efforts to negotiate a definitive agreement") can be interpreted as creating enforceable obligations.
2. **Do not include material terms that a court could later find create a binding agreement.** An LOI that specifies every material term of a transaction and adds "subject to definitive documentation" is closer to a binding agreement than one that specifies the headline structure and defers the mechanics. In particular, LOIs that specify indemnification terms, closing conditions, and MAC / MAE definitions can drift into "type II" preliminary-agreement territory where the parties are held to have agreed on material terms.

The practitioner discipline is to keep the LOI *tight* — the substantive terms are named at the headline level (price, structure, consideration, timeline) rather than at the definitive-agreement level (indemnification survival, cap, basket, MAC / MAE definition), and the binding provisions are limited to exclusivity, confidentiality, expense-reimbursement, and publicity. Anything more granular belongs in the definitive-agreement negotiation.

## What an LOI actually locks in

Even a well-drafted LOI, with only enumerated binding provisions, materially reshapes the transaction dynamic. The specific things it locks in:

### Price and structure as an anchor

The LOI's headline price becomes the *anchor* for the definitive-agreement negotiation. Diligence findings can adjust the price downward — this is the primary source of *price re-trades* — but the LOI headline is the ceiling from which negotiation moves; it is very hard for the seller to argue for a *higher* price after LOI signing without a substantive change in circumstances. This is why the sell-side banker's job at the best-and-final round is to extract the highest defensible headline number: whatever the LOI says is what the transaction will approximately be worth, subject to diligence adjustment.

### Exclusivity — the leverage inversion

Exclusivity is the mechanical inversion of the sell-side leverage position. Before LOI signing, the target has multiple bidders competing on price and terms; the sell-side banker uses that competition to extract the highest price and the most favourable non-price terms. At LOI signing, the target grants exclusivity to the winning bidder, which means the target *contractually cannot* continue to negotiate with the other bidders during the exclusivity period. From the buyer's perspective, this is exactly what they are paying for — the buyer will not commit legal-and-financial-diligence resources (typically $500K to several million dollars for a mid-market transaction) unless they have contractual assurance that the target cannot flip to another bidder mid-diligence. From the target's perspective, this is a major concession: for the duration of exclusivity, the target has only one negotiating counterparty, and if diligence reveals that the buyer wants to re-trade the price by 10–15%, the target's alternative is to walk away and start the process over with the other bidders (who may or may not still be at the table). Chapter 2 develops the mechanics.

### Process obligations

The LOI creates a small set of *process* obligations that shape the next 30–90 days:

- **Diligence access** — the target commits to making a data room and management team available for the buyer's diligence workstreams.
- **Definitive-agreement drafting timeline** — the LOI sometimes commits the buyer to deliver a first draft of the SPA within a specified number of days (typically 10–15 days), which creates a benchmark that lets the target's counsel monitor whether the buyer is prosecuting the deal on schedule.
- **Regulatory-filing preparation** — for transactions with anticipated HSR / CFIUS / foreign-antitrust filings, the LOI commits both parties to prepare their filings in parallel with the definitive-agreement negotiation so that filing can happen promptly after signing.
- **Publicity restrictions** — the LOI restricts both parties from disclosing the transaction, subject to specific carve-outs (SEC-mandated disclosure for a public acquirer, employee communications, etc.). See mod-110 for the transaction-communications discipline.

### Expense reimbursement and (occasionally) a break-up fee

Some LOIs include an **expense-reimbursement** provision — if the target walks away for a reason other than the buyer's material breach, the target owes the buyer's transaction expenses up to a specified cap (typically several hundred thousand to a few million dollars for a mid-market transaction). This is the buyer's insurance policy against a target that uses the exclusivity period as a lever to shop the deal to other bidders without a genuine intent to close with the buyer. Chapter 2 develops the ladder from expense reimbursement (small) to break-up fee (larger, typically 1–4% of transaction value in public-target M&A) to reverse termination fees.

### What the LOI does *not* lock in

The LOI does not lock in the definitive-agreement terms. Reps and warranties, closing conditions, MAC / MAE definition, indemnification package, R&W-insurance structure, non-compete covenants, retention arrangements — all of these are negotiated in the definitive agreement over the 30–90 days after LOI signing. The LOI names the headline shape; the definitive agreement fills in the mechanics.

This is why practitioners refer to the LOI as the *starting whistle* for the deal, not the finish line. The LOI is a milestone that changes what everyone is working on — from a market-making process to a bilateral drafting-and-diligence exercise — but the substantive fights (see chapters 4, 5, 6) are still ahead.

## The drafting sequence from LOI to definitive agreement

Once an LOI is signed, the transaction moves through a defined sequence. The specific timeline varies with deal complexity, buyer type, and regulatory-filing requirements, but the modal shape is:

- **Day 0.** LOI signed. Exclusivity clock starts.
- **Days 0–5.** Buyer's counsel confirms diligence-workstream leads and workstream scope. Sell-side counsel prepares the data room for buyer-side diligence (or grants access to the existing sell-side data room; see mod-105).
- **Days 5–15.** Buyer's counsel delivers first draft of the definitive agreement (SPA / Merger Agreement / APA). See chapter 4.
- **Days 5–30.** Buyer-side diligence workstreams run in parallel — financial (Q of E), legal, tax, commercial, technology, IP, HR, privacy, security, AI-model. See mod-105.
- **Days 15–30.** Sell-side counsel returns a marked-up first draft of the definitive agreement. First round of red-line and negotiation.
- **Days 20–35.** R&W insurance broker (typically Marsh / Aon / Lockton) begins the underwriting process for a buyer-side R&W policy. See chapter 7.
- **Days 25–45.** Disclosure schedules drafted and delivered by sell-side counsel; this is the actual risk-allocation artefact — the reps in the SPA are *general* statements, and the schedules are where the seller discloses the specific exceptions. See chapter 4 for the schedule discipline.
- **Days 30–60.** Second and third rounds of red-line negotiation on the definitive agreement; MAC / MAE definition and indemnification package are the primary fight zones. R&W insurance policy finalised and bound. Regulatory filings prepared.
- **Days 60–90.** Signing. Definitive agreement is executed. HSR / CFIUS / foreign-antitrust filings submitted (unless "sign and file" was done at signing).
- **Signing → Closing.** Interim period (see chapter 5 covenants) — target operates in ordinary course, HSR waiting period runs, third-party consents are obtained, closing conditions are satisfied. Typical duration: 30–90 days from signing to closing for a HSR-only transaction; longer for CFIUS / foreign-antitrust review or for transactions requiring lengthy consent processes.
- **Closing.** Purchase price is paid, target's stock or assets transfer, escrow is funded, R&W insurance policy incepts.
- **Post-Closing.** Integration begins (mod-111). Escrow release choreography, earn-out achievement operations, working-capital true-up execution. Indemnification claims can be brought within the survival period of the reps (typically 12–24 months for general reps; longer for fundamental / tax reps). R&W insurance policy runs for its full term (typically 6 years for fundamental reps, 3 years for general reps).

The exclusivity period must be long enough to accommodate the definitive-agreement drafting, the R&W insurance underwriting, and the regulatory-filing preparation. Typical exclusivity is 45 days for a straightforward transaction, 60 days for a more complex one, with the option to extend by mutual agreement (or unilaterally by the target if the buyer is prosecuting the deal in good faith — see chapter 2 for the standard extension language).

## The letter as a document — what actually goes in it

A typical LOI in a venture-backed C-corp target acquisition is 8–15 pages. The typical section order:

1. **Background / recitals** — one paragraph naming the parties and the general nature of the proposed transaction.
2. **Transaction structure** — form (asset / stock / reverse-triangular merger / etc.), consideration mix, treatment of vested and unvested equity, treatment of the ESOP / option pool, treatment of any warrants or convertible notes on the balance sheet.
3. **Purchase price** — enterprise value or equity-purchase price, adjustment mechanics (working-capital, closing-cash, closing-debt, transaction-expenses), escrow and holdback sizing.
4. **Financing** — sources of funds, financing contingencies (or the absence thereof).
5. **Management-and-employee arrangements** — retention pool sizing, key-executive employment agreements, non-competes and non-solicits, treatment of the option pool.
6. **Diligence** — scope of the buyer's diligence workstreams, target's cooperation commitment, timing.
7. **Definitive agreement** — commitment to negotiate and enter into a definitive agreement, form of the definitive agreement (SPA / Merger Agreement / APA), drafting responsibility, timeline commitment.
8. **Regulatory approvals** — HSR / CFIUS / foreign-antitrust anticipated filings, allocation of filing fees, cooperation commitment.
9. **Closing conditions** — outline of the closing conditions the buyer expects (typically limited at LOI stage — details in the definitive agreement).
10. **Binding provisions** — exclusivity, confidentiality, expense-reimbursement, publicity, choice of law and forum, jurisdiction, notice, counterparts.
11. **Nonbinding acknowledgment** — the explicit statement that everything except the binding provisions is nonbinding until the definitive agreement is executed.
12. **Signature blocks** — target's officers, buyer's officers, sometimes selling stockholders (for very small transactions where the target's stockholders are joined at LOI stage; unusual for anything larger than a small tuck-in).

The specific content of each section is negotiated; the drafting exercises in this module (exercises 1 and 2) walk through a sell-side and a buy-side LOI at that level of granularity.

## Common LOI-drafting mistakes

Some patterns to avoid:

- **Silence on structure.** An LOI that says "purchase of Target for $X" without naming asset vs. stock vs. reverse-triangular vs. §338(h)(10) leaves 30% of the tax and consent structure unresolved and sets up weeks of post-signing argument. mod-103 chapter 1 develops the reason this matters.
- **Silence on adjustments.** An LOI that names a headline number without naming the adjustment mechanics (working-capital, closing-cash, closing-debt, transaction-expenses) leaves the seller exposed to a definitive-agreement negotiation where the buyer proposes aggressive adjustment mechanics that reduce the effective purchase price by 5–15%.
- **Silence on financing certainty.** An LOI from a PE bidder that does not confirm equity-commitment letters is worth less than one that does; a sell-side counsel who allows this to slide is not doing the target's job.
- **Silence on treatment of vested-and-unvested equity.** The treatment of vested options (cashed out at closing net of exercise price), unvested options (cancelled, rolled, accelerated), the ESPP (typically terminated with a final purchase), and RSUs (single- vs. double-trigger acceleration) has material dollar value to employees. An LOI that punts these to the definitive agreement is fine; an LOI that is silent on them altogether is a signal the buyer has not thought about them and will propose an employee-unfriendly structure in the definitive-agreement negotiation.
- **Silence on retention pool.** For a target where employee retention is a material transaction-success factor (essentially every venture-backed acquisition), the LOI should name the retention-pool size. Typical retention pools are 2–6% of purchase price, sourced either from the buyer's transaction budget or by a cut-off from the seller's proceeds; the LOI should specify. Otherwise the retention discussion becomes a proxy for a price re-trade.
- **Optimistic language on the nonbinding provisions.** "The parties will negotiate in good faith and use commercially reasonable efforts to enter into a definitive agreement." Delaware courts have interpreted language like this as creating an enforceable duty to negotiate in good faith. If the parties do not intend such an obligation, the language should be dropped or explicitly disclaimed.
- **Missing publicity restrictions.** An LOI without publicity restrictions gives either party the ability to disclose the transaction publicly, which can trigger customer / employee / competitor responses that materially damage the target if the deal does not close. This is a low-cost drafting fix that is sometimes missed.

## Summary

The transaction-side term-sheet-and-LOI architecture is a two-round pattern. Round 1 produces nonbinding IOIs that let the target compare bidders on price, structure, and process posture. Round 2 produces a binding LOI from the winning bidder that names purchase price, structure, and consideration and creates a small set of binding obligations — most importantly exclusivity — while leaving the definitive-agreement terms to be negotiated over the following 30–90 days. The binding-vs-nonbinding split is the central architectural point of the LOI and the source of most drafting mistakes; well-drafted LOIs enumerate the binding provisions explicitly and use clear, unambiguous language for the nonbinding portion. An LOI locks in the price as an anchor, grants exclusivity that inverts the sell-side leverage position, creates process obligations for the 30–90-day drafting sequence, and sometimes includes expense-reimbursement or break-up-fee mechanics. It does not lock in the definitive-agreement terms — reps and warranties, closing conditions, MAC / MAE definition, indemnification package are all negotiated in the definitive agreement.

Chapter 2 goes deep on the specific mechanics of the exclusivity / no-shop / standstill / expense-reimbursement / break-up-fee package that shapes the negotiating environment after LOI signing. Chapter 3 covers the auction choreography that produced the IOI and best-and-final rounds. Chapters 4–6 cover the definitive-agreement drafting that flows from LOI signing.
