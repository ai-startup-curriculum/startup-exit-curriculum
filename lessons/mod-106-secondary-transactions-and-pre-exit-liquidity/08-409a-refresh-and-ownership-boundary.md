# 409A Refresh Cycles, Rule 701 Interaction, and the Ownership Boundary

## Why this matters

Every secondary transaction covered in the previous seven chapters interacts with two specific compliance frameworks that operate continuously in the target's finance function: the **IRC §409A fair-market-value discipline** for common stock (which drives every ISO / NSO grant's strike price and every RSU grant's fair-value determination) and the **IRC §701 aggregate-value monitoring** for equity issued under compensatory arrangements exempt from Securities Act registration. A well-run secondary transaction respects both frameworks. A poorly-run secondary transaction can trigger a 409A refresh at inconvenient timing (driving ISO strike prices materially higher for subsequent grants), can exceed a Rule 701 aggregate-value cap (creating disclosure or registration obligations the target had not planned for), or can misalign the transaction paper with the target's disclosure history in ways that show up as material findings in future M&A or IPO diligence.

This chapter installs the 409A refresh cycle discipline as it applies to secondary transactions, the Rule 701 aggregate-value monitoring interaction, and — crucially — the **ownership boundary** between this module and the adjacent tracks. The distinction matters because a founder-CEO / CFO / GC / SVP-Corp-Dev seat approaching a secondary transaction needs to know which apparatus they own the transaction-execution mechanics for (this module) and which apparatus they defer to for equity policy and equity economics (the neighbouring tracks). Ownership confusion is a specific failure mode — a compensation-committee decision made in isolation from the transaction's 409A implications, or a transaction structured without regard to the underlying grant-guidelines-and-refresh cadence, produces expensive coordination failures.

> **Reminder: education, not tax or securities-law advice.** §409A and Rule 701 both carry material penalty exposure for non-compliance and require specific counsel for a live transaction. This chapter installs the practitioner vocabulary for the transaction-execution seat; the specifics of 409A appraisal methodology and Rule 701 aggregate-value monitoring live in the target's finance and legal functions with support from qualified counsel and third-party appraisers.

## IRC §409A and the fair-market-value discipline

IRC §409A (enacted as part of the American Jobs Creation Act of 2004) is the tax regime governing nonqualified deferred compensation. Its most-consequential application in the startup context is the requirement that stock options and other stock-based compensation instruments must be granted at a **fair market value (FMV)** strike price, established by an **independent valuation**. A grant made at a below-FMV strike price is treated as deferred compensation subject to §409A, with material adverse tax consequences to the grantee (immediate ordinary-income taxation on the vested value plus a 20% additional tax plus interest).

The safe-harbour mechanism the market has settled into is the **independent 409A valuation**: an appraisal by a qualified independent appraiser (in practice, specialised firms like Carta's 409A team, Aranca, Preferred Return, Redwood Valuation Partners, Scalar, and the private-company-valuation practices of Big Four firms) that establishes the FMV of common stock as of a specific valuation date. Grants made at or above the 409A-established FMV during the valuation's applicable period are presumed reasonable under §409A.

### The 12-month presumption window

The standard practitioner cadence is a 409A valuation on a **12-month rolling window**. A valuation dated 2024-03-15 provides the safe-harbour presumption for grants made from that date through 2025-03-15, provided no **material event** has occurred in the interim that would invalidate the earlier valuation.

The 12-month window is not a rule of law — it is a practitioner convention that has emerged from the specific safe-harbour language in the Treasury regulations. The regulations require that the valuation be reasonable and that the grant be based on a valuation that "takes into account all available information material to the value of the corporation." A valuation older than 12 months is presumed unreasonable in most practitioner readings; a valuation newer than 12 months, absent a material event, is presumed reasonable.

### The material-event trigger

A **material event** is an event that materially changes the target's fair value and that a reasonable appraiser would consider in a fresh valuation. The standard practitioner list of material events that trigger a fresh 409A:

- **A priced financing round** (Series [X] Preferred) closing at a materially different valuation than the prior 409A implied.
- **A material secondary transaction** at a materially different price than the prior 409A implied — including tender offers, founder secondaries above a specific size threshold, and platform-cleared secondary volume that reaches material significance.
- **A material acquisition or divestiture** by the target.
- **A material change in business prospects** — the loss of a large customer, the announcement of a strategic pivot, a material regulatory action.
- **Material public-market movement in sector comparables** (though this is typically absorbed at the next scheduled refresh rather than triggering an immediate refresh, unless movement is extreme).
- **Time passing** (the 12-month window is itself a trigger — a refresh is required at or before the 12-month anniversary regardless of events).

For the purposes of this chapter, the specific trigger that matters is **a material secondary transaction at a materially different price** — every secondary transaction discussed in chapters 1–7 is potentially a §409A material event.

### The materiality threshold for a secondary transaction

A secondary transaction is a §409A material event if its price is materially different from the prior 409A common-price and if the transaction volume is significant enough to be considered representative of a market for the target's shares. "Materially different" is not defined with mathematical precision; practitioner reads:

- A **founder secondary of $2M at 25% above the prior 409A common** is probably not material by itself — it's a single transaction at a modest premium.
- A **tender offer of $50M at 40% above the prior 409A common** almost certainly is material — significant volume at a materially different price.
- A **platform-cleared secondary transaction of 1M shares at 60% above prior 409A** is probably material — the observable transaction volume at a substantially higher price should be reflected in the next 409A.
- A **secondary at or below the prior 409A common** may or may not be material — the appraiser will consider whether the transaction reflects diminished value or reflects a specific buyer's willingness-to-pay.

The specific materiality determination is made by the target's 409A appraiser. Practitioner discipline: at the design phase of any significant secondary, coordinate with the appraiser in advance to confirm whether a refresh will be triggered and on what timeline.

### The appraiser-selection decision

The 409A appraiser is engaged under a specific scope-of-work at the target's initiation. The market has consolidated around several classes of appraiser:

- **Platform-integrated appraisers** — Carta's 409A team is the largest single provider by transaction volume; Carta customers can order a 409A refresh directly through the Carta platform and receive a valuation prepared by Carta's internal team with typical turnaround of 2–4 weeks. Attractive for smaller companies with straightforward capital structures; some concern about independence (the appraiser is affiliated with the platform holding the cap-table data).
- **Specialist independent appraisers** — Aranca, Redwood Valuation Partners, Preferred Return, Scalar, VRC (Valuation Research Corporation), and dozens of smaller boutiques. Each has a specific methodology emphasis and practitioner reputation. Typically preferred at growth stage and above for the independent-third-party rigour.
- **Big Four private-company-valuation practices** — PwC, EY, Deloitte, KPMG each have private-company valuation practices that will perform 409A appraisals, typically at the higher end of the fee scale, for later-stage targets with complex capital structures or specific pre-IPO 409A discipline requirements.
- **Sector-specialist appraisers** — for targets in specific sectors (biotech, deep-tech, AI infrastructure), there are appraisers with sector-specific methodology strength. Sometimes worth the premium at growth-stage targets in sectors where the appraiser's sector expertise materially reduces the risk of an adverse audit outcome.

The appraiser-selection decision typically sits with the CFO or the equivalent finance function and is confirmed by the audit committee at growth-stage and later. Once selected, the appraiser typically continues on a rolling engagement across multiple refresh cycles.

### The methodology-selection decision

Every 409A valuation uses a specific methodology — most commonly a combination of two:

- **Option Pricing Method (OPM)** — treats the common as a call option on the enterprise value, struck at the preference-stack conversion point. Standard for early-and-growth-stage targets with a large expected-value uncertainty; the option-pricing framework captures the common's optionality against the preference stack.
- **Probability-Weighted Expected Return Method (PWERM)** — models specific outcome scenarios (IPO, strategic sale, wind-down) with probabilities and computes the probability-weighted expected common value. Standard for late-stage targets with more specific liquidity visibility; less appropriate at earlier stages where scenarios are highly uncertain.

Some appraisers use a **hybrid method** — OPM for near-term uncertainty combined with PWERM-weighted scenarios for specific longer-term outcomes. The methodology choice is discussed with the target's CFO and audit committee at the appraisal's initiation.

For secondary-transaction interactions specifically, the appraiser will typically:

- **Consider the secondary transaction as an observable data point.** A secondary at $50/common is an observable transaction that the appraiser will weight into the common valuation, along with the OPM-derived value from the preference stack.
- **Weight the secondary against other data.** A single secondary may be weighted less than the OPM-derived value; a large-volume secondary or repeated observable transactions typically weigh more heavily.
- **Discount for illiquidity and marketability.** Even where secondary transactions clear at a specific price, the appraiser typically applies a discount for the illiquidity of the target's common relative to a truly liquid market.

### The impact on ISO strike prices

Once a fresh 409A is issued at a higher common valuation, subsequent option grants must use the new (higher) strike price. This has specific workforce-compensation consequences:

- **Existing option grants are not affected.** A grant made at $18/strike under the prior 409A does not increase because the 409A refreshes to $28. The existing grant retains its $18 strike.
- **New option grants use the new strike price.** A grant made after the refresh to $28 has a $28 strike. For subsequent hires, the higher strike means less immediate upside (they're now paying $28 rather than $18 to acquire the same share).
- **Refresh-grant timing becomes strategic.** Some companies deliberately schedule refresh grants immediately before the 409A refresh to lock in the older, lower strike; others avoid the timing question entirely by treating refresh cadence as fixed regardless of 409A cycles.

The compensation committee typically discusses the 409A refresh implications at each refresh cycle and adjusts the grant guidelines (which are typically owned by `startup-operations-governance-curriculum`) accordingly.

## Rule 701 aggregate-value monitoring

Rule 701 under the Securities Act provides an exemption from Section 5 registration for securities issued to employees, directors, general partners, trustees, officers, consultants, and advisors under compensatory arrangements. The rule permits growth-stage private companies to issue meaningful equity compensation without SEC registration, subject to specific aggregate-value limits and disclosure obligations.

### The aggregate-value cap

Rule 701 limits the aggregate value of securities issued under the exemption in any consecutive 12-month period to the greater of:

- $1M, or
- 15% of the total assets of the issuer as of the most recent balance-sheet date, or
- 15% of the outstanding amount of the class of securities being offered (measured at the date of the sale).

For most growth-stage targets, the 15% test is the binding constraint. The aggregate-value calculation is at the time of grant based on the exercise price or fair value at grant.

### The disclosure trigger

If in any 12-month period the aggregate value of securities issued under Rule 701 exceeds $10M (raised from $5M in 2018), the issuer must provide detailed disclosure to the recipients — including specific business, financial, and risk-factor disclosures approximating the level of an S-1 (though scaled). This disclosure obligation is a significant administrative burden and typically requires securities counsel to prepare.

### The interaction with secondary transactions

Secondary transactions do not typically count against Rule 701 aggregate-value limits because they are not *issuances* by the company — they are transfers of already-outstanding shares between holders. However, several transaction structures create Rule 701 interactions:

- **Same-day cashless exercise in a tender.** The employee's exercise of NSO / ISO options in the tender is an issuance by the company (of the shares underlying the option), and the exercise value counts against Rule 701's aggregate-value cap for the exercise year. A large tender that triggers many same-day exercises can materially consume Rule 701 capacity.
- **RSU settlement in a tender.** RSU settlement is an issuance of common shares; the value at settlement counts against Rule 701's aggregate-value cap.
- **New equity grants made in connection with a secondary transaction.** Any new option or RSU grants made in connection with the secondary (e.g., executive-retention grants, employee-refresh grants) count against Rule 701.
- **Compensation-related transactions.** If any portion of the secondary transaction is treated as compensation (e.g., a founder secondary at a premium to fair value with the excess treated as ordinary compensation), the ordinary-compensation portion may be considered a Rule 701 issuance for aggregate-value purposes.

Practitioner discipline: at the design phase of any tender that will trigger significant same-day exercises or RSU settlements, the target's counsel calculates the projected Rule 701 impact and confirms that the aggregate value stays within the cap. Where the aggregate value approaches the $10M disclosure threshold, the target either scales the tender's participation cap or prepares the Rule 701 disclosure package.

## The ownership boundary — this module vs. the adjacent tracks

The final piece of this chapter, and the module, is a specific declaration of what this module owns and where it defers to adjacent tracks. Ownership confusion produces coordination failures; a clean ownership statement prevents them.

### What this module owns

- **The transaction-execution mechanics of a secondary event** — the design, negotiation, approval, and closing of founder secondaries, employee tender offers, structured secondaries, and secondary-market-platform transactions.
- **The pre-and-post-transaction choreography** — the ROFR / co-sale process, the board resolutions, the participant education, the tender documentation, the settlement mechanics.
- **The transaction-specific coordination with 409A refresh and Rule 701 compliance** — flagging when a transaction is a 409A material event, coordinating the refresh timing, monitoring Rule 701 aggregate-value impact, escalating to the finance and legal functions when compliance action is required.
- **The transaction-specific communications discipline** — how a secondary is communicated to the workforce, to the market, and to future acquirers or underwriters.
- **The transaction-specific tax analysis at the M&A-transaction seat** — waterfall analysis, withholding categories, §1202 QSBS interaction at the transaction-execution level, sequencing considerations for holding-period discipline.

### What `startup-operations-governance-curriculum` owns

- **Equity-compensation *policy*** — grant guidelines (how much equity a level-5 engineer receives), refresh cadence (annual, biannual, event-driven), promotion-refresh discipline, new-hire-grant standards.
- **The compensation-committee governance** — committee charter, committee composition, committee meeting cadence, committee decision-making protocols.
- **The equity-plan document itself** — the target's equity-incentive plan, the plan amendments, the shareholder consents for plan increases.
- **The ongoing-workforce equity administration** — the recruiter's job-description equity representation, the offer-letter equity language, the vesting schedules embedded in offer letters.

The boundary: `startup-operations-governance-curriculum` owns *policy*; this module owns *transaction execution*. When a tender's design decisions cross into policy territory (should executives be excluded? what's the tender's cadence?), those questions defer to the compensation-committee governance owned by the operations-governance track.

### What `startup-finance-fundraising-curriculum` mod-104 owns

- **Equity *economics*** — waterfall math at scale (the general framework, not the specific transaction's application), preference-stack modelling under different scenarios, dilution modelling under primary-round financings.
- **409A methodology** — the technical methodology-selection discussion (OPM vs. PWERM vs. hybrid), the appraiser-selection framework, the audit-committee review of 409A methodology.
- **Rule 701 aggregate-value monitoring** — the ongoing monitoring discipline, the aggregate-value calculation, the coordination with securities counsel on the disclosure threshold.
- **Cap-table maintenance at ongoing-company scale** — Carta / Pulley / Shareworks configuration, cap-table integrity, waterfall-modelling tools, per-employee equity dashboards.

The boundary: `startup-finance-fundraising-curriculum` mod-104 owns *equity economics* — the general mathematical apparatus and the ongoing compliance monitoring. This module owns the *transaction-execution* application — how a specific tender or secondary interacts with the waterfall in a specific fact pattern, how the 409A refresh timing coordinates with the transaction, how Rule 701 aggregate-value monitoring flags whether the transaction can proceed within existing capacity.

### The coordination discipline in practice

A secondary transaction well-run under this module coordinates across the three tracks:

- **Design phase** — this module's transaction seat leads the design decisions (pricing, eligibility, participation cap). The finance function (equity economics track) models the waterfall implications and confirms 409A refresh trigger. The operations-governance track's compensation committee approves the design decisions that intersect with policy.
- **Approval phase** — this module's transaction seat drives the board resolutions and ROFR / co-sale process. The finance function coordinates with the 409A appraiser on the refresh cadence. The operations-governance track's committee confirms the compensation-committee approvals.
- **Execution phase** — this module's transaction seat runs the tender launch, employee education, and settlement. The finance function processes the withholding and coordinates the payroll integration. The operations-governance track updates the equity administration to reflect the post-transaction state.
- **Post-transaction phase** — this module's transaction seat closes the transaction paperwork and files the disclosure trail. The finance function completes the 409A refresh and updates the Rule 701 aggregate-value tracker. The operations-governance track updates the equity-plan documentation as needed.

Each track's owner has clear responsibility for their piece; the transaction proceeds cleanly. Where the tracks are not clearly delineated — where policy and transaction execution and finance-technical work are all bundled onto a single overloaded owner — coordination failures cascade.

## Summary and the module close

The §409A fair-market-value discipline drives every equity grant's strike price and is materially affected by the pricing observed in secondary transactions — a material tender or a series of platform-cleared secondaries at prices materially different from the prior 409A common triggers a fresh 409A that resets subsequent ISO strike prices. The Rule 701 aggregate-value monitoring is generally not affected by pure share transfers but is affected by same-day exercises and RSU settlements that occur in connection with a tender. The transaction-execution seat owned by this module coordinates with the equity-policy work owned by `startup-operations-governance-curriculum` and the equity-economics-and-appraisal work owned by `startup-finance-fundraising-curriculum` mod-104. Clean coordination across the tracks produces transactions that close on time, within compliance, without workforce-morale disruption, and without disclosure surprises in future M&A or IPO diligence.

This chapter closes the module. The apparatus is complete: the founder-secondary framework of chapter 1, the tender-offer design of chapter 2, the tender-waterfall-and-tax analysis of chapter 3, the structured-secondary and forward-contract instruments of chapter 4, the secondary-market-platform-and-regulation framework of chapter 5, the ROFR / co-sale choreography of chapter 6, the tender-in-connection-with-financing pattern of chapter 7, and the 409A refresh / Rule 701 / ownership-boundary discipline of this chapter. The exercises operationalise each piece against a specific hypothetical target — ideally the transaction context you have been carrying forward from mod-101 through mod-105. The module hands off to mod-107 for the IPO-readiness apparatus, which turns the endgame arc toward the going-public path.
