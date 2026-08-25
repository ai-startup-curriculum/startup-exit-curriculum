# Employee Tender Offer — Pricing, Eligibility, Participation Caps, and Operational Choreography

## Why this matters

An **employee tender offer** is a company-organised liquidity event that lets a defined portion of the employee population sell a bounded portion of their vested equity to a defined buyer (or pool of buyers) at a defined price. Two decades ago, employees at private venture-backed companies had essentially no path to liquidity until the company was sold or went public — vested equity might be theoretically valuable but practically unrealisable. Today, the employee tender is one of the most consequential pieces of pre-exit workforce infrastructure a growth-stage company operates. Employees who joined at Series B, held stock for six or eight years, watched the valuation compound, and now hold seven-figure paper positions can convert some fraction of that into cash without having to wait for an exit that may still be years away. For companies at Series C and later, running a tender every 12 to 18 months has become close to standard practice — Stripe, Instacart, Discord, Databricks, Notion, and dozens of others have run structured tenders as recurring workforce infrastructure rather than one-off events.

The transaction is far more complicated than a founder secondary. A founder secondary is one seller. A tender offer is potentially several hundred sellers, each with a different equity instrument (ISO-exercised common, NSO-exercised common, RSU-settled common, unexercised options, unsettled RSUs), a different tenure profile, a different tax posture, a different holding period, and a different relationship to the company that shapes what the company can and cannot offer them. It carries **securities-law** implications (the tender is an offer to buy securities subject to SEC Rule 13e-4-analogous requirements even where the target is private, and the tender documentation is drafted to satisfy those requirements), **employment-law** implications (a tender excluded from certain employees can be read as discriminatory if the exclusion is not defensible), **tax-withholding** implications (ISO-exercised shares are treated differently than NSO-exercised shares and differently again from RSU-settled shares), and **409A-refresh** implications (a tender at a price materially different from the current 409A is a material event that triggers a 409A refresh — chapter 8).

This chapter covers the *design* discipline of an employee tender: pricing methodology, eligibility rules, participation caps, and operational choreography. Chapter 3 covers the waterfall-and-tax layer that a well-designed tender must respect. Together they form the practitioner apparatus for running a tender that clears smoothly, does not create workforce-morale disruption, does not create disproportionate tax bills, and does not create governance exposure.

> **Reminder: education, not legal, tax, or securities-law advice.** A live employee tender requires securities counsel (the tender documentation must satisfy the applicable exemption or registration requirement), tax counsel (withholding is highly instrument-dependent), and — typically — a specialist tender-offer administrator (Carta, Nasdaq Private Market, Shareworks). The material below installs the design vocabulary; the specifics come from qualified counsel.

## What a tender offer *is* — and is not

A tender offer, in the private-company context, is a **structured invitation** made by the company (or by a buyer or a buyer syndicate on the company's behalf) to a defined class of holders to sell some or all of their qualifying shares at a defined price on a defined date. It differs from a series of one-off secondary sales in three respects:

1. It is **collective** — a defined class of holders is invited on identical terms, and each holder independently decides whether to participate up to a defined cap.
2. It is **fixed-price** — every participating holder sells at the same per-share price, computed from a methodology chosen at design time, rather than at individually negotiated prices.
3. It is **time-boxed** — the tender opens on a specific date, is open for a defined window (typically 20 business days minimum, matching the SEC Rule 14e-1 minimum for public tender offers, even though private-company tenders are not literally subject to Rule 14e-1), and closes on a defined date, after which no further participation is permitted.

What a tender offer is *not*: it is not a secondary-market listing. Employees are not free to sell to any buyer at any time at any price. They are participating (or not) in a specific transaction on specific terms, and the sale is only cleared through the tender itself.

## Pricing methodology — three canonical approaches

The single most consequential design decision in a tender is the **price**. Three practitioner-canonical pricing approaches:

### Approach 1 — Preferred-share price ("last-round pref")

The tender price is set at the same per-share price paid by the buyer of the target's most-recent preferred-share financing round. In a company whose Series D closed at $85.00 per Series D Preferred, the tender price is set at $85.00 per share of common tendered.

Attractive because: simple to justify, aligned with the most recent third-party market price, and directly compares to the round on the fully-diluted cap table.

Problematic because: the preferred-share price reflects the value of preferred stock, which carries a liquidation preference, dividend rights, protective provisions, and (in most rounds) a valuation-defensible per-share valuation reflecting those preferences. Common stock does not carry those rights. Pricing common at the preferred-share price is *overpaying* for common relative to the theoretical common-share equivalent. This is not necessarily fatal — a strategic buyer looking to acquire common for future stock ownership may knowingly overpay — but it has 409A implications (chapter 8): if the common is being sold at the preferred price, the current 409A common price is stale and a refresh at closer to preferred is likely required.

### Approach 2 — Common-share equivalent price ("preferred with a discount")

The tender price is set at the preferred price minus a discount that reflects the difference between preferred and common — the same fundamental analysis a 409A valuation performs. Typical discounts range from 15% to 40% depending on the size of the preference stack, the number of preferred series, and the sector. In the Series D at $85.00 example, a 25% discount produces a tender price of $63.75 per common share.

Attractive because: economically defensible (common is worth less than preferred, and pricing it at that discount is honest), avoids the 409A cliff (the tender price is close to the current 409A common price), and reduces the tax cost to the seller (a lower per-share sale price at the same volume of shares tendered produces less taxable gain).

Problematic because: employees compare the tender price to the preferred round headline and read the discount as "the company is undervaluing us." Communication discipline matters — the tender documentation must explain the common-vs-preferred value distinction clearly.

### Approach 3 — Secondary-market-clearing price

The tender price is set to reflect what an arms-length secondary-market buyer would pay for the common in an open transaction — typically observed on a platform like Forge Global, EquityZen, or Nasdaq Private Market, or negotiated with a specific secondary-market buyer serving as the tender's counterparty.

Attractive because: reflects actual third-party willingness-to-pay for the common, not derived from the preferred price, and can be higher or lower than either preferred or common-equivalent depending on the market's current appetite for the sector.

Problematic because: secondary-market pricing is thin and noisy; a single recent secondary transaction can drive the read-through price higher or lower than the "true" clearing level. Where the tender counterparty is a specific secondary-market buyer, that buyer's willingness-to-pay drives the price, and the price becomes a negotiation rather than an observation. The tender-offer administrator (Carta, NPM) can facilitate the pricing discovery but does not itself set the price.

### The pricing-approach decision framework

The choice among the three approaches turns on the buyer identity and the intent of the tender.

- **Tender funded by the primary-round lead (Shape A tender-in-connection-with-financing, chapter 7).** Typically preferred price or preferred-with-small-discount — the lead is coming in at the preferred price for primary and often offers to buy secondary at the same or slightly discounted price to keep pricing simple.
- **Tender funded by existing investor(s) at a routine liquidity event.** Typically common-share equivalent — the investors are being pragmatic about common vs. preferred value and want the tender price to align with the current 409A.
- **Tender funded by a specific secondary-market buyer or buyer syndicate.** Typically secondary-market-clearing price — the buyer's willingness-to-pay drives the price, negotiated against comparable transactions.
- **Tender funded by the company itself (self-tender / share-repurchase).** Typically common-share equivalent — the company is buying back its own stock at fair-market value; anything above fair-market value implicates ordinary-compensation treatment on the excess.

The choice becomes a specific board decision at the tender's design phase, defended against the buyer's willingness-to-pay, the current 409A, and the employee-communications implications.

## Eligibility rules — who is invited

The tender's eligibility ruleset is a specific board-and-management decision that carries both securities-law and employment-law implications. The typical eligibility dimensions:

### Dimension 1 — Employment status

- **Current employees** — almost always included, subject to further rules below.
- **Recent former employees** — sometimes included where the tender is designed as a broad-based liquidity event (a departed employee who exercised their vested options during the post-termination exercise window and holds common shares as of the tender record date can be eligible). More typical is to include former employees within a defined window (e.g., departed within 12 months of the tender opening).
- **Advisors, consultants, contractors** — typically excluded unless they were converted to common stockholders through specific advisor equity grants and hold vested shares.
- **Board members and non-employee investors** — typically excluded from the "employee tender" but sometimes eligible for a parallel executive or investor tranche with different terms.

### Dimension 2 — Tenure requirement

A tender typically requires a minimum tenure at the company before an employee is eligible. Common thresholds:

- **Minimum 12 months of continuous employment.** Ensures the tender is not a first-day sign-on benefit and that participants have had time to build meaningful equity.
- **Minimum 24 months.** More common at earlier-stage tenders where the company wants to reward long-tenured employees specifically.
- **Employed as of the tender record date.** A specific cutoff date (typically shortly before the tender documentation is filed) at which the employee's employment status is checked.

The tenure requirement is a specific ruleset the tender documentation discloses, and the record date is a specific date the tender's administrator computes eligibility against.

### Dimension 3 — Executive-team exclusion or separate tranche

- **Full executive exclusion.** The C-suite and (typically) VP-and-above executive population is *excluded* from participation. Rationale: executives receive separate compensation-committee-managed liquidity (via specific executive secondary programmes, mod-103 chapter 6 MIPs, or via founder-secondary shape C in chapter 1), and the tender is designed for the rank-and-file. This is the most common structure.
- **Reduced participation cap for executives.** Executives are included but with a per-executive cap that is a fraction (often 25–50%) of the highest employee cap. Rationale: the tender is a broad-based workforce event, and executive participation at rank-and-file levels is acceptable but not disproportionate.
- **Separate executive tranche with different terms.** Executives participate in a companion transaction at a similar (or same) price but with different documentation, disclosure, and cap structure. This is the most common structure at the very largest companies with complex executive-liquidity governance.

The exclusion decision has legal implications: if executive exclusion is not defensible on a business-purpose ground (e.g., executive-liquidity governance is a separate compensation-committee matter, or the executives already have separate liquidity), the exclusion could be read as compensation discrimination. Standard practice is to document the business purpose at the board's tender-approval resolution.

### Dimension 4 — Share-eligibility rules

The tender defines which specific shares an eligible employee can tender.

- **Vested shares only.** Unvested shares (unexercised options, unsettled RSUs, unvested restricted stock) are almost universally excluded. A tender on unvested shares does not make sense — the employee does not yet own them.
- **Exercised shares (common shares actually held) only** vs. **vested-but-unexercised options with a same-day exercise-and-tender mechanic.** The first is simpler but limits participation to employees who have already exercised (and paid the exercise cost and the tax); the second (with a *cashless* exercise-then-tender mechanic) is more inclusive but adds operational complexity. Most modern tenders offer the cashless-exercise mechanic — the employee's exercise cost and their withholding is netted from the tender proceeds, and the employee receives net cash.
- **RSU-settled shares.** RSUs at private companies are typically double-trigger (vest at the earlier of a specified date and a liquidity event). An RSU whose service-based vesting has been met but whose liquidity-event trigger has not fired is *not yet settled* and cannot be tendered. A tender is often structured to satisfy the RSU liquidity-event trigger, converting service-vested RSUs into common at the tender record date and permitting participation.
- **Pre-2018 vs. post-2018 grant treatment.** For historical reasons — the pre-Tax-Cuts-and-Jobs-Act rules on RSU taxation — some companies distinguish RSUs granted before and after specific dates in eligibility rules. Historical baggage; usually resolved by the tender administrator with the tax counsel's assistance.

### Dimension 5 — Insider-trading and material-information gating

Employees who are in possession of material non-public information (MNPI) about the company — a pending large customer contract not yet announced, a pending M&A discussion, pending litigation not yet disclosed to the tender participants — are effectively barred from participating even where they are otherwise eligible. The tender documentation typically requires each participating employee to represent that they are not aware of any MNPI at the time of tender participation.

The company's legal function typically applies an **insider list** discipline — the specific employees who are aware of any MNPI as of the tender window are identified and either excluded from participation or the tender window is delayed until the MNPI is disclosed to the participant population. This is not literal Rule 10b-5 exposure (the company is private), but the state-law and contractual analogue of insider-trading discipline applies.

## Participation caps — three layers

The tender's participation-cap ruleset controls how much any individual employee can sell and how much the tender purchases in aggregate. Three canonical cap layers, applied together.

### Layer 1 — Per-employee cap

The cap on any individual employee's participation. Typical structures:

- **Percentage-of-vested cap.** Each eligible employee can tender up to a defined percentage of their vested-and-eligible shares — typical range is 10–25%. A 20% per-employee cap on a $2M vested position permits the employee to sell up to $400K.
- **Absolute-dollar cap.** Each eligible employee can tender up to a defined dollar amount — typical range is $50K–$500K, sometimes higher at very large companies. The dollar cap is set to align the tender with a "meaningful but not full liquidation" outcome for each employee.
- **Combined cap.** The lesser of the percentage cap and the dollar cap — a 20% cap subject to a $500K maximum, for example. Common in mid-market tenders where a small number of long-tenured employees would otherwise be able to tender disproportionately.

### Layer 2 — Level-based cap

A tender that offers different caps at different employee levels. Typical patterns:

- **Higher percentage cap for lower levels.** Rank-and-file employees have a 25% per-employee cap; managers have a 20% cap; directors have a 15% cap; VPs have a 10% cap; executives are excluded or capped at 5%.
- **Higher absolute cap for lower levels adjusted for equity holdings.** A specific dollar cap that increases with tenure or level, ensuring the cap is roughly proportional to holdings.

The rationale for level-based caps is workforce-morale — a broader-participation, lower-per-executive cap tender is read as a workforce-liquidity event rather than an executive-liquidity event. Some tenders skip level-based caps in favor of a single flat cap for all participants below the executive-exclusion line.

### Layer 3 — Aggregate-round cap

The buyer's total commitment to the tender is a fixed number — typically expressed in dollars ("the buyer will purchase up to $50M of common shares at the tender price") or shares. If the sum of all employee tenders exceeds the aggregate-round cap, the tender proration mechanic kicks in.

**Proration mechanics.** When over-subscribed, the tender's proration rule allocates the buyer's available capital among the participating employees. Common structures:

- **Pro-rata by tendered amount.** Each participant's tender is scaled down by the same factor. If total tenders are $60M against a $50M cap, each participant's tender is scaled to 83% (50/60) of what they requested.
- **Equal-per-employee floor.** Each participant is guaranteed to sell up to some floor amount (e.g., the first $25K of their tender), and any remaining buyer capital after the floor is prorated across incremental tenders above the floor. This structure ensures every participant gets a meaningful cash-out even in a heavily over-subscribed tender.
- **Priority tiers.** Participants at specific eligibility tiers (e.g., long-tenured, or below a specific level) have priority allocation, and other participants are prorated only after priority tiers are fully filled.

The proration ruleset is a specific design decision that the tender documentation discloses in advance — participants must know how their tender will be scaled if the tender is over-subscribed.

## Operational choreography — how a tender actually runs

The operational side of a tender is a specific, sequenced process that runs over roughly six to eight weeks from design lock to closing. The typical stages:

### Stage 1 — Design and board approval (Weeks -8 to -4)

- Board and management define the tender's design parameters: pricing methodology, eligibility rules, participation caps, buyer identity, tender window.
- Securities counsel drafts the tender documentation: the offer letter to eligible employees, the offer-to-purchase document, the schedule of participating shares, the eligibility-and-cap explanation, the tax-withholding disclosures, the ROFR / co-sale mechanics disclosure.
- Tax counsel confirms the withholding treatment for each equity-instrument category.
- The company's 409A appraiser is engaged to prepare a fresh 409A that reflects (or does not reflect, depending on the transaction structure) the tender's pricing (chapter 8).
- The board approves the tender at a formal meeting: adopts the tender resolutions, approves the tender-offer documentation, and waives (or exercises) the company's ROFR for the tender window.
- The tender-offer administrator (Carta, Nasdaq Private Market, or an independent transfer agent like Computershare / EQ Shareowner / Continental) is engaged to run the operational execution.

### Stage 2 — Tender launch (Week -3)

- Tender documentation is distributed to eligible employees. This is typically a portal-based distribution through the tender administrator's platform (Carta CartaX Tender, NPM Tender, Shareworks Tender), plus an email announcement, plus (often) an all-hands presentation from the CEO or CFO.
- The tender window officially opens. Under SEC Rule 14e-1 (which private-company tenders imitate by market convention even though not literally subject), the window is at least 20 business days.
- Each eligible employee receives a per-employee packet: their eligibility summary, their per-employee cap, their current vested holdings, the tender-price calculation, a personalised tax-withholding estimate, and the participation election form.

### Stage 3 — Employee education and Q&A (Weeks -3 to -1)

- The company holds multiple tender-education sessions covering the mechanics, the price, the tax implications, and the participation-cap ruleset. Standard practice is to have the CFO or a tender-offer specialist available for one-on-one questions.
- Employees consult their personal financial advisors (some companies bring in a fee-based financial advisor as a resource for the tender window). Note: the *company* does not provide personal financial advice; the employee is on their own for personal-tax and personal-financial analysis.
- Participation elections are submitted through the tender administrator's platform. Elections can typically be revised until the tender window closes.

### Stage 4 — Tender close and settlement (Week 0)

- The tender window closes. No further elections or revisions are permitted.
- The tender administrator computes the total participation, applies the aggregate-round cap and proration if applicable, and confirms per-employee allocations.
- The buyer(s) fund the tender to the tender-offer escrow (Computershare, Continental, or the tender administrator's escrow function).
- Shares are transferred from the participating employees' holdings to the buyer(s), with the tax-withholding component of the tender proceeds remitted to the applicable taxing authorities and the net cash-out remitted to the participating employees.
- The cap table is updated to reflect the transferred shares.

### Stage 5 — Post-tender cleanup (Weeks +1 to +4)

- Tax reporting: 1099 forms are issued to participating employees (for the NSO / RSU / ISO categories with taxable events); the company's payroll system captures the withholding for W-2 reporting.
- The company's next 409A refresh (chapter 8) is completed if the tender was priced at a materially different level from the pre-tender 409A.
- Investor-report and cap-table updates are distributed to the round.
- The tender-offer documentation and administrator's confirmation report are filed in the company's corporate records.

## Rolling vs. one-off tender programmes

Some companies run a single tender in a specific window; others run **rolling** tender programmes on a defined cadence — annually or every 18 months. The rolling programme has three advantages: (a) employees can plan personal-liquidity around a predictable window rather than making an all-in decision each time; (b) the company builds durable tender-execution infrastructure (Carta or NPM or Shareworks configured, tax counsel engaged, 409A refresh cadence aligned) rather than reinventing each event; (c) the market's read of a rolling tender is much less signalling-material than a one-off tender (a rolling programme reads as "workforce infrastructure"; a one-off tender reads as "specific event").

The counterargument to rolling tenders: they encourage employees to lightening their positions on a schedule rather than holding for the eventual exit. Companies whose long-term compensation philosophy emphasises upside participation sometimes deliberately run only occasional tenders, or run them only alongside specific primary-round financings.

## Carta-administered vs. transfer-agent-administered execution

Two operational-execution paths dominate current practice.

**Carta-administered tender (Carta X Tender, or Carta's tender-offer product).** Carta manages the tender end-to-end within its cap-table platform. Eligibility is computed against the Carta record, elections are made through the Carta portal, settlement flows through Carta's fund-administration infrastructure, and the cap-table update is automatic. Attractive for companies already using Carta as their cap-table platform of record.

**Transfer-agent-administered tender (Computershare, Continental Stock Transfer, EQ Shareowner, or Nasdaq Private Market's tender-offer function).** An independent transfer agent runs the tender under a separate engagement, with the company's cap table synchronised to the transfer agent's records before the tender opens. Preferred at the largest late-stage tenders where the tender is on a scale (thousands of participants, hundreds of millions of dollars) that a specialist independent administrator is better-suited to handle. Nasdaq Private Market's tender platform is a common choice for tenders in the $50M+ range.

The choice among administrators is operational, not strategic — but the choice's timing matters. Administrator selection is typically locked in by the design phase (Stage 1) because the operational documentation and portal setup depend on it.

## Summary

An employee tender offer is a company-organised, collective, fixed-price, time-boxed liquidity event that lets a defined class of holders sell a bounded portion of their vested equity to a defined buyer. The pricing methodology (last-round pref, common-share equivalent, secondary-market clearing) is the single most consequential design decision and is dictated by the buyer identity and the tender's intent. Eligibility is defined across employment status, tenure, executive-team treatment, share-eligibility, and MNPI gating; participation caps operate at three layers — per-employee, level-based, and aggregate-round — with a specific proration mechanic for over-subscription. Operational choreography runs on a six-to-eight-week timeline through design-and-approval, launch, education, close-and-settlement, and post-tender cleanup. The administrative execution path — Carta-administered vs. transfer-agent-administered — determines the operational tooling but not the transaction's substantive terms. Some companies run occasional one-off tenders; others operate rolling programmes that make workforce-liquidity a durable piece of infrastructure.

Chapter 3 turns to the waterfall-and-tax layer that a well-designed tender must respect — how the preference stack shapes the equivalent per-share economics across common holders, option holders, and RSU holders; how tax withholding differs across ISO, NSO, and RSU categories; and how the tender's mechanics interact with the target's holding-period discipline.
