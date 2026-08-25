# Escrow, Holdback, and Working-Capital-Adjustment Mechanics

## Why this matters

A private-company M&A transaction almost never closes with 100% of the purchase price paid to shareholders on the closing date. A portion is *escrowed* to backstop indemnification claims for breach of representations and warranties, a portion is *held back* for specific known risks, and a portion is *adjusted* against a closing working-capital target with a subsequent true-up. In aggregate these mechanics can defer or condition 10–20% of the headline purchase price for 12–24 months post-close. For a $400M transaction, that is $40M–$80M of the shareholders' expected consideration that is not, in fact, in the shareholders' hands at closing — and the terms that govern its release are one of the most economically consequential design decisions in the SPA.

The design task is to size the escrow and holdback against the specific risk profile of the target, to separate the escrow's *general-indemnity* function from any *specific-indemnity* holdbacks for known issues, to draft the working-capital-adjustment definition and true-up mechanism so that closing-date operating changes do not become disputes, and to reconcile all of this with the R&W insurance market (which, over the last decade, has changed the modal escrow structure materially). This chapter installs the mechanics, benchmarks them against practitioner data from the ABA Deal Points Studies and SRS Acquiom, and identifies the specific failure modes that produce post-close disputes.

## The escrow / holdback / adjustment stack

Three distinct mechanisms with three distinct purposes:

### General-indemnity escrow

Purpose: backstop the seller's indemnification obligations to the buyer for breach of general representations and warranties in the SPA.

- **Mechanics:** at closing, a portion of the purchase price (denominated in cash or in acquirer stock, depending on the consideration structure) is deposited with an independent third-party escrow agent (typically SRS Acquiom, Wilmington Trust, JPMorgan, or Citi in the middle-market range). The escrow agent holds the funds under the escrow agreement, releasing them per its terms — typically at the end of the survival period, less any amounts subject to unresolved indemnification claims that were noticed during the survival period.
- **Sizing:** the ABA Business Law Section's Private Target M&A Deal Points Studies (published biennially, most recent editions covering deals with values above $30M) report a **long-run median general-indemnity escrow of approximately 5–10% of purchase price**, with a range of 2.5–15% across the population. SRS Acquiom's annual M&A Deal Terms Study reports similar ranges with year-over-year variation as R&W insurance uptake has shifted the underlying distribution. See [resources.md](resources.md) for the specific study links.
- **Survival period:** the ABA Deal Points Study reports a long-run **median survival period of 12–18 months** for general reps, with a range typically 9–24 months. Fundamental reps (organisation, capitalisation, authority, brokers' fees, taxes to some extent) commonly survive indefinitely or for the applicable statute-of-limitations period; specific reps (financial statements, contracts, IP, employee benefits) survive for the general survival period.
- **Release mechanics:** at the end of the survival period, any escrow not subject to a pending indemnification claim is released to the shareholders (through the shareholders' representative — see below). Escrow subject to a pending claim is retained until the claim is resolved.

### Specific-indemnity escrow / holdback

Purpose: backstop indemnification obligations for a *specific known risk* identified in diligence, held separately from the general-indemnity escrow.

- **Mechanics:** if diligence surfaces a specific known risk (an IP-infringement claim, a tax exposure identified in Q-of-E, a pending regulatory investigation, a customer-dispute risk), the buyer and seller may agree to a specific holdback earmarked for that risk. The holdback may be structured as a separate escrow account, as a specific reserve within the general escrow, or as a deferred-payment obligation tied to the specific risk's resolution.
- **Sizing:** driven by the specific risk's estimated exposure, not by a percentage-of-purchase-price benchmark. If diligence identifies a specific $5M IP-infringement risk, the holdback is sized around that estimate — potentially higher for uncertainty, potentially lower if the parties agree the risk is capped.
- **Survival period:** typically tied to the specific risk's resolution timeline. An IP-infringement holdback survives until the underlying litigation is resolved or the statute of limitations runs. A tax holdback survives until the specific tax period's audit-limitation period expires.
- **Release mechanics:** on resolution of the specific risk (or expiry of the associated period), the specific-indemnity holdback is released, less any amounts absorbed by the specific-risk realisation.

The distinction from the general escrow matters: general-indemnity claims come out of the general escrow (with the buyer's baskets and caps applying); specific-indemnity claims come out of the specific holdback (typically without the general basket-and-cap constraints, because the specific risk was priced into the specific holdback).

### R&W insurance and the modern escrow paradigm

Representations and warranties insurance ("R&W insurance") has substantially reshaped the escrow landscape over the last decade. An R&W policy is a third-party insurance policy — issued by a specialty carrier (AIG, Berkshire, Beazley, Euclid, RiverStone, Concord Specialty, and others) — that covers the buyer for losses arising from breaches of the seller's representations and warranties in the SPA, subject to a retention (equivalent to a deductible), a coverage limit, and specific policy exclusions.

- **Modern paradigm:** a substantial fraction of middle-market and upper-middle-market transactions now use R&W insurance as the *primary* recourse for breach of general reps, with a smaller escrow (or no escrow at all beyond the R&W retention) holding as backup. SRS Acquiom's annual deal-terms studies report the year-by-year percentage of transactions using R&W insurance, which has trended sharply upward from the early 2010s.
- **Retention structure:** the R&W policy typically has a retention (deductible) of 0.5–1.0% of enterprise value, with the buyer and seller often splitting the retention 50/50 or the seller bearing the full retention as a "sole-recourse" mechanism. Above the retention, the policy pays.
- **Coverage limit:** the policy limit is typically 10% of enterprise value (though the specific limit is negotiated), so R&W insurance is a *first-dollar-above-retention* mechanism up to the policy limit, and does not eliminate the seller's exposure entirely.
- **Exclusions:** R&W policies exclude a defined list of items — typically known matters disclosed in the diligence process (the "known-matters" exclusion), specific-indemnity items already backstopped by a specific holdback, certain tax matters, and specific specialised areas (cybersecurity, IP infringement, tax positions) that may require rider coverage or excluded coverage.
- **Underwriting process:** the R&W carrier conducts its own underwriting of the SPA reps and the diligence, which can take 3–6 weeks and can affect the SPA drafting (reps the carrier will not underwrite may need to be softened or excluded from coverage). The R&W underwriting call and diligence review are a specific workstream in mod-105.
- **Impact on the general escrow:** with R&W insurance in place, the general escrow can be materially smaller (often 0.5% of enterprise value or less, matching the R&W retention) or eliminated entirely, replaced with sole-recourse-to-insurance structures.

The tradeoff: R&W insurance shifts risk from the seller's post-close escrow to a third-party insurer at a premium cost (typically 2.5–4% of the policy limit, sometimes higher). For a $400M deal with a $40M policy limit, the premium is $1M–$1.6M plus retention. This cost is typically split between buyer and seller or borne by the buyer alone; the specific allocation is a negotiation point.

### Working-capital adjustment

Purpose: normalise the target's working-capital position at closing so that the seller delivers a business with a "normal" amount of working capital, not a business with working capital that has been depleted (or accumulated) in advance of closing.

- **Mechanics:** the SPA specifies a **working-capital target** — a specified dollar amount of working capital that the target is required to deliver at closing. At closing, the buyer pays a preliminary purchase price computed using an estimated closing working capital (from the target's pre-closing forecast). After closing, a **true-up** period runs: the buyer prepares a final closing working-capital statement (typically within 60–90 days post-close), the seller reviews (typically 30–45 day review period), and the parties reconcile. If actual closing working capital exceeded the target, the buyer pays additional purchase price to the seller; if actual closing working capital fell short, the seller refunds the shortfall (typically out of the escrow or a specific working-capital-adjustment holdback).
- **Target-setting:** the working-capital target is typically set based on the target's historical average working capital over the trailing 12 months (adjusted for seasonality), computed on a specific formula agreed in the SPA. The specific formula matters — it determines which balance-sheet line items are included and how they are computed.
- **Cash and debt handling.** Related to but distinct from working-capital adjustment: the SPA typically defines a **cash target** (usually zero — the deal is "cash-free"), meaning cash on the balance sheet at closing goes to the seller (in addition to the purchase price) but does not reduce the purchase price. And it defines a **debt target** (usually the full amount of the target's indebtedness at closing is deducted from the purchase price — the deal is "debt-free"), meaning the seller uses closing proceeds to pay off the target's debt. The specific definitions of "cash" and "debt" — what counts as debt vs. accrued liability, whether prepaid expenses count as cash equivalent — are drafted specifically.
- **Deferred revenue.** Deferred revenue (customer prepayments not yet earned) is a specific item that gets debated. Sellers want deferred revenue treated as working capital (which raises the working-capital position and reduces the true-up-shortfall risk); buyers want deferred revenue treated as debt-like (which reduces the purchase price for it, on the theory that deferred revenue is an obligation to deliver future services). The economics are meaningful for subscription businesses with material deferred revenue.

### The purchase-price stack

Put together, the effective purchase price to the seller looks like:

- **Headline purchase price** (the number the LOI and press release cite)
- Minus **debt** at closing (repayment of target's indebtedness)
- Plus **cash** at closing (target's cash on hand)
- Plus / minus **working-capital adjustment** (post-closing true-up against target)
- Minus **general-indemnity escrow** (10–20% of headline, held for 12–18 months)
- Minus **specific-indemnity holdbacks** (specific to known risks)
- Minus **R&W insurance premium** (if buyer pays; sometimes seller-paid or split)
- Minus **transaction expenses** (banker fees, legal fees, D&O tail insurance)
- Minus **change-of-control payments** (severance to departing executives, transaction bonuses per §280G-compliant structure — chapter 6)
- Equals **net closing proceeds to shareholders** (paid at closing)

Each of these deductions is drafted specifically in the SPA and models materially at the shareholder level. A "$400M sale" can produce net closing proceeds of $310M–$330M depending on the specific structure — the balance in escrow, adjustment, and expenses. The waterfall model that computes shareholder outcomes has to work with the *net* number, not the headline.

## Sizing the escrow — the fact-pattern-driven decision

Escrow sizing is not a formulaic exercise. The percentage of the ABA Deal Points Study is a *starting point*; the specific size on a specific deal is driven by fact-pattern considerations:

- **Rep-and-warranty risk profile.** How likely are the reps to have been inaccurate? A target with a clean diligence file, audited financials, well-organised IP, and no pending disputes has lower rep-and-warranty risk than a target with a messy history. Higher risk → larger escrow (or higher R&W policy limit).
- **Financial-statement quality.** A target with recent audited financials and a clean Q-of-E supports a smaller escrow than one with unaudited financials and open Q-of-E questions. Quality of earnings drives quality of reps.
- **Specific-risk identification.** Diligence-identified specific risks get specific-indemnity holdbacks; the general escrow can then be sized against residual unknown risk.
- **R&W insurance availability and price.** If R&W insurance is available and the buyer will use it, the general escrow can be small (matching the retention). If R&W insurance is unavailable (some sectors, some geographies, some target sizes) or the premium is high, the general escrow has to be larger.
- **Fundamental-vs-general rep split.** Fundamental reps (organisation, capitalisation, authority, taxes) can be covered by a separate cap or excluded from the general basket / cap; the general escrow sizes primarily to the general reps.
- **Basket and cap structure.** The basket (deductible below which indemnification does not apply) and the cap (maximum indemnification obligation, typically the general-indemnity cap is 10–15% of enterprise value) shape what the escrow is exposed to. A tipping basket (where crossing the basket unlocks indemnification from the first dollar) is different from a true deductible (only losses above the basket are recoverable). ABA Deal Points Studies report the modal basket structures.
- **Survival period.** A longer survival period supports a smaller escrow because more time for post-close discoveries offsets the smaller pool; a shorter survival period supports a larger escrow.
- **Seller creditworthiness.** If the sellers are individual founders and early employees (who have no meaningful post-close credit to backstop indemnification claims), the escrow is the *primary* recourse and needs to be sized larger than if the seller is a large corporate parent that could satisfy an indemnification claim from its own resources.

The ABA Deal Points Study and SRS Acquiom Deal Terms Study report population statistics that anchor the negotiation; the specific deal's escrow size is driven by the fact pattern within the population's range.

## The working-capital-adjustment failure modes

Working-capital adjustments are one of the most common sources of post-close dispute. The specific patterns that recur:

### Failure mode 1: Working-capital target is set incorrectly

If the working-capital target is set based on a historical average that is not reflective of the business's current position, the closing true-up will produce a large adjustment. A common cause: the target's business has grown between the historical measurement period and the closing date, and working-capital needs have grown proportionally; the historical-average target is now too low, and the closing working-capital position exceeds the target, requiring a buyer refund to the seller.

**Design mitigation:** the working-capital target should be set with reference to a recent measurement window (e.g., trailing 3 or 6 months rather than trailing 12 months for a fast-growing business), or should be structured with an explicit growth adjustment. The target-setting formula should be drafted in the SPA rather than left to the closing statement.

### Failure mode 2: Working-capital definition is ambiguous

If the SPA does not specify which balance-sheet line items count as working capital, the parties can compute working capital very differently. Deferred revenue is the most common ambiguity (as discussed above). Prepaid expenses, accrued vacation, accrued bonuses, and tax accruals are others.

**Design mitigation:** the SPA should include a *specific line-item list* of what counts as working capital, computed consistent with the target's historical accounting practices. A worked example calculation (as of the most recent month-end before signing) should be attached as a schedule.

### Failure mode 3: Accounting-methodology disputes

Even with a specific line-item definition, the parties can dispute the accounting *methodology* — how a specific accrual is computed, how a specific reserve is set, how revenue recognition timing works for a specific customer contract. Post-close, the buyer has the target's books and records and can push for aggressive methodology (higher reserves, more conservative revenue recognition) that reduces closing working capital.

**Design mitigation:** the SPA should specify that closing working capital is computed *consistently with the target's historical accounting practices*, and that any dispute about methodology is subject to the independent-accountant dispute-resolution mechanism (typically the same accountant used for earn-out disputes — chapter 3).

### Failure mode 4: Timing of the true-up statement

If the SPA gives the buyer 90 days to prepare the closing statement and the seller 30 days to review, but the buyer takes 120 days or the seller takes 60 days, the escalation clock is ambiguous.

**Design mitigation:** the SPA should specify the escalation clock, the consequences of missing deadlines, and the mechanism for continuing to accrue positions during any dispute period.

## The shareholders' representative

Post-close, someone has to enforce the escrow-release mechanics, negotiate the working-capital true-up, respond to indemnification claims, and (if applicable) enforce the earn-out. The shareholders' representative is the person or entity empowered to do this on behalf of the shareholder group.

- **Selection:** commonly a professional shareholder-representative service (SRS Acquiom is a large one; Fortis Advisors, Shareholder Representative Services, and others compete). Alternatively, an individual — often the former CFO of the target or an outside advisor.
- **Powers:** the SPA specifies the representative's authority — to negotiate, to enforce, to release funds, to hire counsel, to settle claims within specified authority.
- **Indemnification:** the representative is indemnified by the shareholder group (typically funded from a small representative-expense escrow held for representative expenses) against claims arising from the representative's conduct in good faith.
- **Communication with shareholders:** the SPA specifies the representative's reporting obligations to the shareholders (typically annual or on major events).

Selecting a good representative is a meaningful decision — a representative who is under-resourced, unfamiliar with the deal, or slow to respond can materially cost the shareholders in post-close outcomes.

## Practical drafting and design checklist

For the escrow / holdback / working-capital-adjustment stack in a specific SPA, verify:

- **General-indemnity escrow.** Is the amount sized against the ABA / SRS Acquiom benchmarks and adjusted for the fact-pattern-specific factors? Is the survival period specified? Is the release mechanism clear?
- **Fundamental reps handling.** Are fundamental reps carved out from the general cap? Is the survival period for fundamental reps specified separately?
- **Specific-indemnity holdbacks.** For each diligence-identified specific risk, is a specific holdback sized and structured? Are release mechanics tied to the specific risk's resolution?
- **R&W insurance.** Is R&W insurance being used? What is the retention structure? Who pays the premium? What are the specific exclusions and is the general escrow sized to cover the exclusions?
- **Basket and cap.** Is the basket structure clear (deductible vs. tipping)? Is the cap defined and consistent with the escrow / R&W policy structure?
- **Working-capital target.** Is the target set based on an appropriate historical measurement window? Is a specific line-item definition included as a schedule? Are accounting-methodology conventions specified?
- **Cash-and-debt definitions.** Are "cash" and "debt" specifically defined? Is deferred revenue treatment specified? Are transaction-expense deductions clearly enumerated?
- **True-up mechanics.** Is the timeline specified? The dispute-resolution mechanism? The consequences of missed deadlines?
- **Shareholders' representative.** Is the representative named or the selection mechanism specified? Are the representative's authority and indemnification clearly drafted? Is a representative-expense escrow funded?
- **Interaction with earn-out.** If the deal has an earn-out (chapter 3), are the earn-out and escrow-release mechanics coordinated in timing? Does the same shareholders' representative enforce both?

## Summary

The escrow / holdback / working-capital-adjustment stack governs the deferred portion of the purchase price — the 10–20% of headline that does not reach the shareholders at closing. Escrow sizing is anchored to ABA Deal Points Study and SRS Acquiom benchmarks but is driven fundamentally by the specific target's rep-and-warranty risk profile and by whether R&W insurance is in the structure. Specific-indemnity holdbacks separate known-risk backstops from the general-rep-backstop escrow. The working-capital adjustment normalises closing working-capital position against a defined target and produces post-close true-ups that are among the most frequent sources of post-close disputes; the target-setting, line-item-definition, and dispute-resolution mechanics all have to be drafted with specificity. The shareholders' representative is the mechanism by which the shareholder group's rights are enforced post-close. Chapters 5–8 return to the tax layer that sits alongside all of these mechanics; chapter 9 addresses the regulatory-filing layer that shapes the deal timeline that all of the survival periods and true-up windows are running against.
