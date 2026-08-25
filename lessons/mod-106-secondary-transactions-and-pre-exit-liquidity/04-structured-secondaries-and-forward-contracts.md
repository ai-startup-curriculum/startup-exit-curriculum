# Structured Secondaries — Forward Contracts, Collateralised Loans, and Counterparty-Credit Risk

## Why this matters

The founder-secondary (chapter 1) and the employee tender (chapters 2–3) both share one structural feature: the *sale* is real. Ownership of the shares transfers from the seller to the buyer at settlement; the seller receives cash and no longer holds the shares. That is the simplest, cleanest structure, but it is not the only one. For a founder, executive, or long-tenured employee whose specific-lot §1202 qualifying stock is not yet at the 5-year holding-period mark, whose personal cash-flow needs are urgent enough to make a bounded loan attractive, or whose situation calls for cash today without triggering an immediate taxable event, a family of **structured secondary** instruments has emerged over the last decade to fill that space.

The two dominant instruments are the **collateralised loan against private-company shares** — the seller borrows against their shares at a haircut without transferring ownership, using the shares as collateral — and the **forward-contract structured secondary** — the seller enters a fixed-price sale contract that settles at a future date, receiving a discounted upfront advance and retaining record ownership until settlement. Both instruments have specialist counterparties (Setter Capital, ClearList, Rainmaker Securities, DBO Partners, and specialist private-company-securities lending arms of large financial-services firms), both introduce **counterparty-credit risk** the direct-sale mechanics do not, and both interact with the target's ROFR / co-sale ruleset, its 409A refresh cadence, and — in ways that require careful counsel — the seller's tax posture.

This chapter installs the structured-secondary framework: what the collateralised loan and forward-contract instruments actually are, when each is appropriate, who the counterparty landscape is, and what the counterparty-credit-risk and tax-timing considerations look like. Practitioner discipline demands that founders and executives evaluating a structured secondary understand what they are signing — the instruments are not simple, the fee structures are opaque relative to primary financings, and the failure modes when the counterparty fails or when the eventual exit yields less than the forward price are consequential.

> **Reminder: education, not legal, tax, or investment advice.** Structured secondaries carry material personal-tax, personal-financial, and securities-law implications that require personal counsel. This chapter installs the vocabulary for evaluating instruments and counterparties; the specific decision for any founder or executive requires their own advisors.

## Collateralised loan against private-company shares

The **collateralised loan** — sometimes called a **stock-secured loan** or **private-company-stock lending facility** — is a loan advance to a shareholder that uses the shareholder's illiquid private-company shares as pledged collateral, without transferring ownership of the shares to the lender until (and unless) the shareholder defaults.

### The mechanic

The shareholder pledges a defined block of shares to the lender under a security-interest-in-securities agreement (UCC Article 9 in the US context). The lender extends a loan advance calibrated to a percentage of the shares' fair-market value at loan closing — the **advance rate**. Typical advance rates are 20% to 50% of the shares' current 409A common value, sometimes higher for very-late-stage companies with strong IPO or M&A visibility. The remainder is the lender's **haircut** — the discount to fair value that provides the lender with protection against a decline in the shares' value or against inability to realise the collateral on default.

The loan carries an interest rate — typically 10% to 15% annually, with some structures using a payment-in-kind (PIK) accrual where the interest compounds into principal rather than being paid in cash. The loan matures at a defined term (typically 3 to 7 years) or on a triggering event (the target's IPO, sale, or a specific liquidity date), whichever comes first.

At maturity or trigger:

- If the target has had a liquidity event and the shares have been sold at a per-share price at or above the loan basis (principal plus accrued interest), the loan is repaid from sale proceeds and the shareholder retains any residual equity value.
- If the shares are worth less than the loan basis, the lender takes the shares (or is left with a deficiency claim against the shareholder, depending on whether the loan is *recourse* or *non-recourse*).
- If no liquidity event has occurred by the loan's maturity, the loan is either refinanced, extended, or repaid from other assets of the shareholder.

### The non-recourse variant — economically equivalent to a forward contract

Some collateralised loans are structured **non-recourse** — the lender's sole remedy on default is to take the pledged shares; the lender has no claim against the shareholder's other assets. A non-recourse loan is economically similar to a **forward contract** (below) because the shareholder's downside is capped at forfeiture of the pledged shares. Tax authorities may treat a non-recourse loan on shares — particularly where the advance rate is a large fraction of fair value and the lender's recovery is limited to the shares — as an effective sale for tax purposes, under the "sale or exchange" doctrine of IRC §1001. This is a specialist tax analysis and turns on the specific loan documents, the advance rate, the interest rate, and the borrower's ability to unwind the transaction.

The IRS's historic posture on the "constructive sale" of appreciated financial positions under IRC §1259 — enacted in 1997 to shut down aggressive forward-sale planning — restricts the ability of shareholders holding appreciated positions to enter forward sales that "eliminate substantially all of the risk of loss and opportunity for gain" without recognising gain at the transaction date. Non-recourse loans with high advance rates may fall on the wrong side of the §1259 line and be treated as constructive sales at execution. Practitioner discipline requires a specific tax opinion for any structured-secondary instrument that pushes advance rates above (roughly) 60% of fair value on a non-recourse basis.

### The advance rate as the driving variable

For a shareholder evaluating a collateralised loan, the advance rate is the central negotiation. Higher advance rates deliver more cash today but introduce more §1259 constructive-sale exposure and higher counterparty risk. Lower advance rates deliver less cash but preserve more of the future upside for the shareholder and reduce the §1259 exposure.

Illustrative table for a 100,000-share position at $30/share fair value ($3M total):

| Advance rate | Cash today | Retained upside on later exit at $80 | §1259 risk read |
|---|---|---|---|
| 25% | $750K | $8M − loan principal + interest ≈ $6.7M | Very low (traditional lending) |
| 40% | $1.2M | $8M − $1.2M − interest ≈ $6.4M | Low |
| 55% | $1.65M | $8M − $1.65M − interest ≈ $5.9M | Moderate — request tax opinion |
| 70% | $2.1M | $8M − $2.1M − interest ≈ $5.4M | Elevated — likely §1259 constructive-sale exposure |
| 85% non-recourse | $2.55M | $8M − $2.55M − interest ≈ $4.7M | High — near-certain §1259 exposure without offsetting structure |

The trade-off between cash today, retained upside, and tax-timing exposure is the shareholder's specific decision to make in consultation with their advisors.

## Forward-contract structured secondaries

The **forward contract** structured secondary is a fixed-price sale contract in which the shareholder agrees today to sell a defined block of shares at a defined future date at a defined price, typically with a discounted upfront advance and with the balance paid at settlement.

### The mechanic

Typical structure:

- The shareholder enters a forward-sale agreement with the counterparty (Setter Capital, DBO Partners, a specialist private-securities-market-maker, or a purpose-built forward-contract fund).
- The shareholder receives an upfront advance at execution — typically 50% to 80% of the forward-contract price.
- The shareholder retains **record ownership** of the shares until the contract's settlement date. This preserves the shareholder's voting rights (where applicable), continues the shareholder's holding-period clock (for §1202 QSBS and long-term-capital-gains purposes), and keeps the shares off the counterparty's balance sheet until settlement.
- The contract settles either on a specific date (typically 12–36 months out) or on the target's liquidity event (IPO or M&A), whichever comes first.
- At settlement:
  - The shareholder delivers the shares to the counterparty.
  - The counterparty pays the remainder of the forward price (contract price minus upfront advance minus any interim fees or accrued economics).
  - The shareholder's tax event is recognised at settlement (subject to the same §1259 constructive-sale analysis above — if the forward eliminates substantially all risk-of-loss and opportunity-for-gain, gain may be recognised at execution rather than settlement).

### Prepaid variable forward contracts — the Reg-M-adjacent variant

A specific well-established forward structure used in the public-company post-lockup context (mod-114 chapter 3) is the **prepaid variable forward contract (PVFC)**. In the PVFC:

- The shareholder receives a large upfront cash advance (typically 75–90% of the current stock price × pledged shares).
- The number of shares delivered at settlement varies within a defined collar: if the stock price appreciates, the shareholder delivers fewer shares; if it declines below a floor, the shareholder delivers the full pledged block.
- The variable-delivery mechanism protects the shareholder from §1259 constructive-sale treatment because they retain both risk-of-loss (on shares delivered above the floor) and opportunity-for-gain (fewer shares delivered on appreciation).

The private-company version of the PVFC is uncommon but not unknown. It requires the counterparty to accept significant valuation uncertainty at settlement, which most private-company forward counterparties will not absorb.

### The tax-timing question — when does the gain recognise?

The single most important tax question for a forward-contract structured secondary is **when the taxable event occurs**. Two scenarios:

- **Fixed-share forward with no §1259 constructive-sale character.** The contract is structured with sufficient shareholder-retained risk and opportunity that it is treated as an executory contract at execution. The taxable event occurs at settlement — cash and gain are recognised in the settlement year. This is the shareholder's preferred outcome (deferring the taxable event to a later year with better tax posture or timing).
- **Fixed-share forward with §1259 constructive-sale character.** The contract "eliminates substantially all of the risk of loss and opportunity for gain" and is treated as a constructive sale at execution. The taxable event occurs in the execution year — the shareholder recognises gain on the pledged shares as if sold at execution.

The line between the two is technical, fact-specific, and requires a specific tax opinion. In practice, most non-PVFC private-company forward contracts with fixed shares and a high upfront advance (>60%) are treated as constructive sales under §1259 at execution. The tax deferral that shareholders often hope to achieve does not survive scrutiny in most fixed-share, high-advance structures.

### Interaction with §1202 QSBS

For a shareholder holding §1202-qualifying stock that has *not yet* reached the 5-year holding-period mark, a forward contract that is *not* a constructive sale under §1259 can preserve the holding-period discipline — the shares are not sold at execution, and the holding period continues to accrue. If the shares reach the 5-year mark before settlement, the §1202 exclusion becomes available at settlement.

Conversely, a forward contract that *is* a constructive sale under §1259 recognises gain at execution — and if the 5-year mark has not been reached at that date, the §1202 exclusion is forfeited. The tax analysis is critical, and the shareholder's tax counsel drives it.

## The counterparty landscape

The specialist counterparties in structured secondaries fall into a small set of practitioner-familiar categories. Each carries different economics, different counterparty-credit-risk profiles, and different relationships with the target company.

### Setter Capital

Toronto-headquartered secondary-market intermediary and (through its Setter Capital Group entities) a principal in structured secondaries. Setter runs bilateral negotiated transactions across public and private secondaries. In the private-company forward-contract and collateralised-loan space, Setter has been a longstanding counterparty for founder-and-executive secondaries in the growth-stage venture market. Setter's pricing is typically negotiated bilaterally rather than published; the shareholder's advisor negotiates advance rates, interest rates (for collateralised loans), and forward prices against comparable transactions.

### ClearList

A US-based private-company secondary platform and, for structured secondaries, a market participant with a mixed role — some transactions run as ClearList-brokered forwards or collateralised loans; others run as pure secondary-market transactions on the ClearList platform. ClearList's platform provides some transaction-workflow standardisation that reduces friction relative to a purely bilateral negotiation.

### Rainmaker Securities

FINRA-registered broker-dealer specialising in private-company secondaries. Rainmaker acts as broker and, in some cases, market-maker for structured secondaries. Rainmaker's regulatory status as a FINRA-registered broker-dealer means transactions run through Rainmaker are held to specific broker-dealer suitability, best-execution, and disclosure standards under FINRA rules. This is a material distinction from unregistered principal counterparties.

### DBO Partners

Boutique investment bank that includes private-company secondaries and structured secondaries in its practice, particularly in the growth-stage AI, SaaS, and consumer-technology sectors. DBO's structured-secondary product has historically been tailored for large individual sellers (founders, senior executives) rather than for tender-offer scale.

### Purpose-built structured-secondary funds

Beyond the named intermediaries, a set of specialised structured-secondary funds — some run by traditional secondary-fund investors (Industry Ventures, Coller, StepStone), some by purpose-built entities focused specifically on structured private-company transactions — participate as principals. These funds may buy collateralised-loan exposure, buy forward contracts, or participate in tender-offer secondary purchases. Their pricing and terms are typically negotiated bilaterally.

### Bank-affiliated private-securities lending arms

Some large financial-services firms operate private-securities lending desks (JPMorgan Private Bank, Morgan Stanley Private Bank, Goldman Sachs Private Wealth Management, Bank of America Private Bank, and others) that will extend collateralised loans against qualifying private-company shares for the firm's private-wealth clients. These lending arms are typically the most cost-efficient counterparties for founder-and-executive collateralised loans — the loans are treated as normal private-banking credit relationships with the shareholder — but access is limited to the firm's existing clients, and the shares must meet the firm's collateral-eligibility criteria (typically confined to well-known growth-stage venture-backed companies with plausible 24–36-month liquidity paths).

## Counterparty-credit risk — the structural exposure the direct-sale mechanics avoid

Every structured secondary introduces **counterparty-credit risk** the direct-sale mechanics of a founder secondary or tender offer do not carry. In a direct sale, the transaction settles at close — cash is exchanged for shares, and neither party has ongoing exposure to the other's creditworthiness. In a structured secondary, the shareholder has continuing exposure to the counterparty:

- In a **collateralised loan**, the shareholder is a borrower and the lender's failure between loan closing and maturity typically results in the lender's assignee taking over the loan and continuing to hold the collateral. Ordinary consumer-and-commercial credit-workout mechanics apply; the shareholder retains the shares (subject to the security interest) and can potentially refinance at maturity.
- In a **forward contract**, the shareholder has extended contract exposure to the counterparty. If the counterparty fails between execution and settlement, the shareholder is left with an unsecured claim against a failed entity for the balance of the forward price. The upfront advance is not refundable; the shares (if not yet delivered) may or may not be reclaimed depending on the specific security-interest terms. This is the most significant counterparty-credit-risk exposure in the structured-secondary category.

The counterparty-credit-risk mitigation levers:

- **Counterparty selection.** Well-capitalised, established counterparties with strong credit ratings and a history of consummating transactions are lower risk than newer or thinly-capitalised entities. Bank-affiliated lending arms (JPMorgan Private Bank, Morgan Stanley, etc.) have the strongest credit profiles.
- **Collateral segregation and custody.** Structured-secondary contracts should specify how the pledged shares are held during the contract term. Held in a custodial account at a bank or trust company (Northern Trust, Wells Fargo, State Street) with clear segregation, the shares are protected from the counterparty's bankruptcy estate. Held on the counterparty's balance sheet without segregation, they are at risk.
- **Escrow of the upfront advance.** For very-high-advance-rate structures, the shareholder can request that a portion of the upfront advance be held in escrow with a third party against specific counterparty-failure triggers. This is uncommon but occasionally negotiable.
- **Insurance and guarantee wrappers.** Rare but non-zero — some structured secondaries carry a specific insurance wrapper (from a specialist insurer) or a parent-company guarantee that provides additional counterparty-failure protection.

For most founder-and-executive-scale structured secondaries at bank-affiliated or well-established counterparties, the counterparty-credit risk is meaningful but manageable. For structured secondaries at newer or thinly-capitalised counterparties, the shareholder's counsel should require enhanced protections.

## Fee structures and cost of capital

Structured secondaries carry material fee structures that materially reduce the shareholder's economic outcome relative to a direct sale. Typical fee categories:

- **Upfront transaction fee.** A percentage of the transaction size paid at execution — typically 1–3% for collateralised loans, 2–5% for forward contracts. Payable from the upfront advance (reducing net proceeds) or separately.
- **Interest or spread.** On collateralised loans, the interest rate applied to the loan balance — typically 10–15% annually. On forward contracts, the implicit spread between the upfront advance and the forward price represents a similar economic cost, expressed as a discount rate.
- **Legal and administrative fees.** The shareholder typically bears their own legal fees (specialist tax counsel required, often specialist securities counsel) and may bear a share of the counterparty's administrative and legal costs — often $50K–$150K for a founder-scale structured secondary.
- **Settlement fees.** At settlement, additional administrative fees may apply, especially where the settlement is complex (a share-delivery-at-IPO forward requires coordinated settlement with the IPO underwriter's DTC-registration mechanics).

The all-in cost of capital for structured secondaries is materially higher than for a direct sale. A shareholder receiving $1M in upfront advance from a forward contract may effectively be paying an economic-cost equivalent of 15–25% annualised, compared to a direct sale that carries only tax cost. The trade-off is against the specific advantages of the structured product — tax deferral (where achievable), holding-period preservation, retained voting rights, and continued upside exposure.

## Interaction with the target company — ROFR, co-sale, and disclosure

Structured secondaries interact with the target company's ROFR / co-sale ruleset (chapter 6) at both execution and settlement. Several patterns:

- **Collateralised loan with security interest only.** The pledge of shares as collateral is *not typically* a transfer that triggers the target's ROFR. However, the pledge is often subject to the *transferability* provisions of the stockholders' agreement — a shareholder may not be able to pledge shares to a lender without company consent. Practitioner discipline: check the specific stockholders' agreement transfer provisions and (if consent is required) obtain it before execution.
- **Forward contract with fixed share delivery.** The forward contract is an agreement to transfer shares in the future — typically read as a *transfer* subject to the target's ROFR, both at execution and at settlement. Practitioner discipline: obtain the ROFR waiver at execution (the ROFR-waiver process is described in chapter 6) and re-confirm at settlement.
- **Non-transfer forward (deliverable at settlement in the target's securities or cash).** Some forward contracts are settled in cash rather than in shares, avoiding the transfer-subject-to-ROFR question. These are rare but structurally cleaner.

Disclosure of a structured secondary in the target's next M&A definitive agreement or S-1 (mod-105 and mod-107) is an additional consideration. A shareholder who has pledged shares as collateral or entered a forward-sale contract has a non-trivial position that may need to be disclosed in future transaction documentation. Practitioner discipline: coordinate structured-secondary planning with the target company's counsel in advance, both to secure necessary consents and to ensure future disclosure obligations are anticipated.

## When a structured secondary is the right instrument

Given the material fee costs, counterparty risk, and complexity, when is a structured secondary actually the right instrument for a shareholder?

The four scenarios where structured secondaries are practitioner-recommended:

**Scenario 1 — Holding-period preservation for §1202.** A founder / executive holding §1202-qualifying stock that will mature at the 5-year mark in 12–24 months, who needs cash now but wants to preserve the §1202 exclusion. A non-§1259 forward contract or a low-advance-rate collateralised loan may preserve the holding-period discipline while providing near-term cash.

**Scenario 2 — Post-IPO lockup with retained-voting need.** A newly-public founder / executive under a lockup restriction who needs cash but wants to retain voting rights during the lockup. Collateralised lending against restricted stock (subject to Rule 144 restrictions on eventual disposition) is a common private-wealth structure.

**Scenario 3 — Cash-flow smoothing across a defined life event.** A shareholder facing a specific near-term cash-flow event (large medical expense, divorce settlement, real-estate purchase, tax bill) with a highly-visible near-term liquidity path (target company's IPO expected in 12–18 months) can bridge the gap with a collateralised loan that repays from IPO proceeds.

**Scenario 4 — Recycling into a new venture.** A departing founder starting a new company can pledge existing-company shares to raise capital for the new company, without triggering an immediate tax event on the existing-company gain. The interaction with §1045 rollover and other tax-planning tools requires specialist counsel.

For most other liquidity needs — routine household diversification, planned lifestyle purchases, non-urgent portfolio rebalancing — a direct sale (founder secondary or tender-offer participation) is a cleaner instrument with lower fee cost and no counterparty risk.

## Summary

Structured secondaries — collateralised loans against private-company shares and forward-contract structured sales — occupy a specific space in the pre-exit liquidity landscape distinct from direct sales. Collateralised loans provide cash today at a haircut against shares held as collateral, with the loan repaid from the eventual liquidity event; forward contracts fix a sale price today with delivery at a future date. Both instruments introduce counterparty-credit risk absent from direct sales and both interact with IRC §1259 constructive-sale rules, IRC §1202 QSBS holding-period discipline, and the target company's ROFR / co-sale ruleset. The counterparty landscape — Setter Capital, ClearList, Rainmaker Securities, DBO Partners, specialist structured-secondary funds, and bank-affiliated private-securities lending arms — has different economics, credit profiles, and relationships with target companies. Fee structures (typically 15–25% annualised all-in cost of capital) are materially higher than for direct sales; the trade-off is against holding-period preservation, tax-timing management, retained voting rights, and continued upside participation. Structured secondaries are the right instrument in a bounded set of scenarios; for most routine pre-exit liquidity needs, the direct-sale mechanics of chapters 1–3 are cleaner. Chapter 5 turns to the secondary-market platform landscape and the FINRA / Rule 144 / Section 4(a)(7) regulatory framework that governs private-company-security resales.
