# IRC §1202 QSBS Preservation Through the Transaction

## Why this matters

IRC §1202 provides one of the largest personal-tax benefits available in the US tax code: for **qualified small business stock (QSBS)** acquired at original issuance and held for at least **5 years**, a non-corporate shareholder can **exclude from federal income tax** up to the greater of **$10 million** or **10 times the shareholder's aggregate adjusted basis** in the stock — potentially eliminating tens of millions of dollars of capital gain from federal taxation.

For founders who hold original-issuance stock in a qualifying C-corp startup and have held it for at least five years by the time of a transaction, the §1202 exclusion is often the single largest tax-planning consideration in the deal. A founder with $12M of gain on qualifying stock who is eligible for the full $10M exclusion pays federal capital-gains tax on only $2M rather than $12M — a savings of roughly $2.4M at the top federal long-term capital-gains rate (23.8% including net investment income tax), plus potentially avoiding state tax if the state conforms to §1202 (some, like Pennsylvania, do not; California specifically does not conform and imposes state tax on the entire gain).

The transaction structure determines whether §1202 treatment is *preserved* through the transaction or *forfeit*. A **stock-form** sale (whether all-cash, all-stock §368 reorg, or mixed) generally preserves QSBS eligibility for the qualifying shareholders — they are selling their qualifying stock, and the §1202 exclusion applies (subject to the specific 5-year holding, original-issuance, and other requirements). An **asset deal** does *not* — the target corporation sells its assets and distributes proceeds; the shareholders' stock is not sold in a §1202-eligible transaction. This is one of the largest reasons founders push back hard on asset-deal structures.

This chapter installs the §1202 QSBS framework as it applies to M&A transactions, the preservation criteria that govern which transactions preserve QSBS treatment, the §1045 rollover option for shareholders who fail to reach the 5-year holding period at transaction time, and the interaction with §368 tax-free reorg treatment for stock consideration.

> **Reminder: education, not tax advice.** §1202 has many technical requirements, ambiguities where practitioner opinion divides, and state-conformity variations. A live §1202 analysis for a specific shareholder in a specific transaction requires qualified tax counsel and, for the details of individual planning, personal tax and estate-planning advisors. This chapter installs the M&A-structuring vocabulary and framework.

## The §1202 qualifying-stock requirements

For stock to be QSBS, all of the following must be true (§1202(c) and related provisions):

- **Issuer requirements.** The issuing corporation must be a **domestic C-corporation** (not S-corp, LLC, partnership, or foreign entity). The corporation must be an **eligible trade or business** — a specific list of *excluded* businesses (health, law, engineering, architecture, accounting, actuarial, consulting, financial services, brokerage, farming, extraction, hotels and restaurants, and other categories under §1202(e)(3)) do not qualify, meaning the corporation's business must not be *substantially* in those categories.
- **Gross-asset test.** At the time of the stock's issuance (and immediately after), the corporation's aggregate gross assets must not exceed **$50 million** (measured at basis, not fair market value). If the corporation's assets grow beyond $50M *after* issuance, that does not disqualify the previously-issued stock; the test is measured at issuance.
- **Original-issuance requirement.** The stock must have been acquired by the shareholder **directly from the corporation** (or through an underwriter) in exchange for money, property (other than stock), or as compensation for services. Stock acquired from another shareholder in a secondary transaction is *not* QSBS (though some limited exceptions apply under §1202(h) for stock received in a tax-free transaction that carries over from qualifying stock).
- **5-year holding period.** The shareholder must have held the qualifying stock for at least **5 years** before the sale. This is the single most consequential requirement in the M&A context, because it fixes an operational timeline on when a founder or early employee can exit with QSBS treatment.
- **Non-corporate shareholder.** The §1202 exclusion is available to non-corporate shareholders (individuals, and certain pass-through entities including certain partnerships and trusts). C-corp shareholders do not benefit from §1202.

The exclusion caps at the greater of $10 million per issuer per shareholder or 10 times the shareholder's aggregate adjusted basis in the QSBS of that issuer. For a founder whose adjusted basis is minimal (as is typical when founders acquired stock at a low par value at incorporation), the cap is effectively $10M per issuer per shareholder. Note the *per issuer* language — a founder holding QSBS in multiple qualifying companies has separate $10M / 10x-basis caps for each.

## The stock-vs-asset transaction distinction

The single most consequential §1202 M&A structuring question: **is the transaction a sale of stock or a sale of assets?**

- **Stock sale.** The shareholder sells their qualifying stock. If the 5-year holding, original-issuance, and other requirements are satisfied at the sale date, the §1202 exclusion applies to the gain (up to the cap). This is true whether the sale is all-cash, all-stock (§368 reorg on the stock portion), or mixed.
- **Asset sale.** The target corporation sells its assets. The corporation recognises gain on the sale (subject to corporate tax). The shareholder does not sell their qualifying stock — they receive a distribution from the corporation (in liquidation or as a dividend). The distribution is taxed at ordinary dividend rates or, if in liquidation, as a stock sale with the *distribution* as the amount received in exchange for the stock. But the transaction itself does not qualify as a §1202 sale — the shareholder's stock is not the object of a qualifying sale of QSBS in an asset-deal structure.

**Practical consequence.** A founder with $15M of gain on qualifying §1202 stock and eligibility for the $10M exclusion pays roughly $2.4M less federal tax in a stock deal than in an asset deal, all else equal. Multiply across a founding team of 3-4 founders with meaningful QSBS positions plus early employees who acquired stock in the first few years of the company, and the seller-side QSBS forfeiture from an asset deal can be $10M-$30M or more in aggregate tax cost.

This is why asset deals produce such strong seller-side push-back for C-corp startup targets with material QSBS. If the buyer insists on asset structure (typically because of specific undisclosed-liability concerns or because §338(h)(10) is desired for step-up), the seller expects the headline number to compensate for the QSBS forfeiture — often 10-15% or more of the aggregate purchase price. Chapter 1's fact-pattern discussion revisits this tension.

## Preservation through §368 reorg treatment

If a transaction qualifies as a §368 tax-free reorg on the stock consideration (chapter 5), the shareholder's exchange of qualifying target stock for acquirer stock is treated as a tax-free exchange under §368 — no current gain, and the shareholder takes the acquirer stock with a carryover basis.

Under §1202(h), stock received in a §368 tax-free reorg in exchange for QSBS *carries over the QSBS characteristics* — the acquirer stock (assuming the acquirer is itself a qualifying issuer, or subject to specific rules under §1202(h)(4) for corporate reorganisations) is treated as QSBS with the original holding period carrying over from the target stock. This preserves the §1202 treatment for a future sale of the acquirer stock, subject to the applicable requirements.

**Practical consequence.** A founder who holds §1202-qualifying target stock and exchanges it for acquirer stock in a §368 reorg does not have a current QSBS sale (no §1202 exclusion in this year), but the acquirer stock retains QSBS characteristics for a future sale — the founder can sell the acquirer stock in a later year and claim the §1202 exclusion (subject to the cap and other requirements at that time).

There are technical complications — the acquirer's own qualification as a §1202 issuer at the time of the future sale may differ from the target's qualification; the acquirer's gross assets may exceed $50M at the reorg date and thereafter (but per §1202(k), the QSBS-eligibility test is measured at the time of the *original* issuance of the stock, which for carried-over stock traces back to the target's original issuance date). Tax counsel is essential for the specific analysis.

## The §1045 rollover for pre-5-year sales

IRC §1045 provides a limited rollover option: if a shareholder sells QSBS held for **more than 6 months** but *less than 5 years* (i.e., not eligible for the §1202 exclusion because the 5-year holding period is not met), the shareholder can defer the gain by *rolling it over* into replacement QSBS purchased within 60 days of the sale.

- **Mechanics.** The shareholder sells QSBS with gain, then reinvests the sale proceeds in newly-issued QSBS of a different qualifying corporation within 60 days. The gain is deferred (not eliminated), with the shareholder's basis in the replacement stock reduced by the deferred gain. When the replacement stock is later sold, the deferred gain is recognised at that time (subject to potential §1202 treatment on the replacement stock if the 5-year holding, tacking the original holding period, is satisfied).
- **§1045 tacking.** The shareholder's holding period in the replacement stock includes the holding period in the original stock — so a shareholder who held original QSBS for 4 years, sold, rolled over into replacement QSBS, and holds the replacement for 1 more year has satisfied the 5-year holding period on the replacement stock.
- **Practical use in M&A.** For founders / early employees whose qualifying stock has not yet reached the 5-year threshold at transaction close, §1045 rollover is a mechanism to defer the current-year tax and preserve a future §1202 opportunity by reinvesting the sale proceeds in a new qualifying startup. In practice, this requires the founder / employee to actively invest in a new qualifying startup within 60 days of the sale — the mechanics of the reinvestment (finding an eligible corporation, receiving qualifying stock at original issuance, meeting the specific §1045 requirements) are non-trivial and require pre-planning.

For founders / early employees who are exiting to a strategic and do not intend to start a new company immediately, §1045 rollover may not be operationally practical. In those cases, the sale of pre-5-year stock is fully taxable at capital-gains rates (or at ordinary rates on the compensation portion, if any).

## The transaction-structure preservation matrix

Combining the §1202 analysis with the transaction-structure taxonomy of chapters 1 and 5:

| Transaction structure | §1202 preservation for target shareholders |
|---|---|
| Asset deal, C-corp target | Forfeit — shareholders receive distribution proceeds, not from QSBS sale |
| Asset deal, S-corp target | N/A — S-corp stock is not §1202-eligible (issuer must be C-corp) |
| Stock deal, C-corp target, all-cash | Preserved — QSBS shareholders sell their qualifying stock; §1202 exclusion applies to gain |
| Stock deal, C-corp target, all-acquirer-stock §368 reorg | Preserved and tacked — no current sale; acquirer stock takes QSBS characteristics under §1202(h) |
| Stock deal, C-corp target, mixed (cash + acquirer stock §368) | Preserved on both — QSBS exclusion applies to cash-boot portion; acquirer stock takes QSBS characteristics |
| Reverse-triangular merger, C-corp target | Same as stock deal — target's shareholders exchange target stock for merger consideration; §1202 analysis parallel to stock deal |
| Forward-triangular merger, C-corp target | Same as reverse-triangular — shareholders exchange target stock for merger consideration |
| Stock deal with §338(h)(10) election, S-corp target | N/A — S-corp targets are not §1202-eligible |
| F-reorg drop-down followed by stock sale of C-corp parent | Preserved on the C-corp stock portion — the shareholders sell C-corp parent stock, which carries over the QSBS characteristics from the original stock (subject to specific §1202(h) analysis) |

The table is a starting reference. Specific fact patterns — a target that has held §1202-ineligible business assets, a shareholder whose original stock was acquired via a secondary transaction rather than original issuance, or a shareholder whose stock was acquired via employee options exercised recently — require specific analysis.

## QSBS preservation as a structuring criterion

For an M&A transaction involving a C-corp target with material §1202 QSBS at the founder / early-employee level, QSBS preservation becomes a specific structuring criterion:

- **Preferred:** stock-form transaction (stock deal, reverse-triangular merger) with §1202-preservation analysis performed for each qualifying shareholder.
- **Acceptable with negotiation:** stock deal with §338(h)(10) election for S-corp targets (§1202 not applicable to S-corp targets, so no forfeiture concern). Or F-reorg drop-down for C-corp targets to enable §338(h)(10)-like buyer step-up while preserving stock-form treatment for the shareholders.
- **Disfavoured:** taxable asset deal for a C-corp target with material QSBS. If unavoidable (buyer refuses to underwrite specific liabilities), the seller expects headline-number compensation for the QSBS forfeiture.

The QSBS-preservation analysis needs to run at the specific-shareholder level, not just at the aggregate. Different shareholders in the same target may have very different QSBS positions:

- **Founders** who acquired stock at incorporation typically have the earliest holding-period start dates and the strongest QSBS positions.
- **Early employees** who exercised options in the first year or two may have QSBS positions if they exercised early enough and the options were exercised (not just vested).
- **Later employees** whose options were granted in year 3 or 4 and are exercised at or near the transaction may not have QSBS positions (insufficient holding period, or option exercise rather than original issuance stock acquisition).
- **Preferred investors** (VC funds) are typically corporate entities (not eligible for §1202) or partnerships (may pass through §1202 in specific circumstances). Their QSBS analysis is separate and typically less relevant to structuring than the founder / early-employee analysis.

The QSBS-preservation structuring criterion primarily protects the *founder and early-employee* cohort. This is often (though not always) the same cohort whose retention and post-close alignment the buyer is most interested in.

## Common pitfalls and practitioner notes

- **The 5-year holding period trap.** A founder / early employee whose qualifying stock reaches the 5-year holding date only *after* the transaction closes has not satisfied §1202 at the sale date. Transaction timing can be a §1202 planning consideration — a transaction that closes a few months later can be worth substantially more in personal tax to a founder who was two months short of the 5-year date at signing. In practice, delaying a transaction for QSBS reasons is rarely commercially viable, but the analysis is worth running for individual planning purposes.
- **The gross-asset-test trap.** If the corporation's gross assets exceeded $50M *at the time of original issuance*, the stock issued at that time (and afterward) is not QSBS. A founder holding stock that was issued when the corporation had $60M of gross assets does not have QSBS regardless of when the stock is sold. This is a common surprise for founders whose stock was granted or issued in later years after significant fundraising.
- **The excluded-business trap.** If the corporation's business is substantially in an excluded category (health, law, consulting, financial services, etc.), the stock is not QSBS. This is a live question for AI startups whose core business is "consulting-like" (custom AI implementation services), or for fintech startups whose business is "financial services." Tax counsel makes the specific call, and the analysis can be surprising.
- **The state-conformity trap.** Federal §1202 exclusion does not automatically apply at the state level. California specifically *does not conform* to §1202 and imposes state tax on the full gain. Pennsylvania does not conform. Other states have specific conformity rules. A founder based in California has ~13% state tax on the gain that federal §1202 excludes; this is a substantial personal-tax consideration that state-tax planning may address (state residency changes, though these are complex and beyond the scope of an M&A analysis).
- **The §1202(h) reorg-carryover trap.** Stock received in a §368 reorg in exchange for QSBS carries QSBS characteristics *only if* the specific §1202(h) requirements are satisfied. The specific analysis is technical (in particular, whether the acquirer meets the qualifying-issuer requirements). Tax counsel should confirm the carryover treatment for each specific transaction.
- **The QSBS stacking pattern.** Advanced planning uses gifting to family members and non-grantor trusts to *stack* multiple $10M exclusions across multiple related shareholders (mod-114 depth). This is an ongoing planning discipline, not a transaction-window one — it must be done in advance of the transaction (typically 12+ months in advance to satisfy specific timing rules), and it is a specific personal-tax planning topic that hands off to personal tax counsel.

## Interaction with the other tax provisions

- **§368 reorg treatment (chapter 5).** §1202 QSBS preservation and §368 tax-free treatment on stock consideration are complementary — a §368 reorg on stock consideration preserves QSBS characteristics on the acquirer stock received. The two are typically achieved together in a well-structured stock-form transaction.
- **§338(h)(10) election (chapter 5).** For S-corp targets, the §338(h)(10) election does not affect §1202 (which does not apply to S-corp stock). For C-corp targets, §338(h)(10) is not directly available; the F-reorg drop-down pattern may enable a §338(h)(10)-like structure while preserving §1202-eligible stock-form treatment for the shareholders.
- **§280G parachute (chapter 6).** §280G excise-tax and lost-deduction consequences are separate from §1202 exclusion. §280G payments to a founder do not reduce the founder's §1202 exclusion; they are treated as compensation, taxed at ordinary rates, and separately subject to §280G analysis.
- **§409A timing (chapter 7).** §409A applies to compensation timing; §1202 applies to gain on qualifying stock. A payment that is compensation (subject to §409A) is not part of the §1202-eligible stock sale; a payment that is purchase-price consideration for QSBS may be §1202-eligible. The characterisation matters and is a specific tax analysis.

## Summary

IRC §1202 provides a substantial personal-tax benefit for founders and early employees who hold qualifying stock in a C-corp startup for at least 5 years — up to $10M or 10x-basis per issuer per shareholder excluded from federal income tax. The transaction structure determines preservation: a stock-form sale (all-cash, all-stock §368 reorg, or mixed) preserves QSBS treatment; an asset deal forfeits it. §368 tax-free reorg treatment on the stock portion allows QSBS characteristics to carry over to the acquirer stock under §1202(h). The §1045 rollover offers a deferral option for shareholders whose stock has not yet reached the 5-year holding period at transaction close, allowing reinvestment in replacement QSBS within 60 days. QSBS preservation is one of the largest personal-tax considerations in a founder-and-early-employee-heavy C-corp target transaction and is a specific structuring criterion — often driving the seller's push-back on asset-deal structures. State conformity varies (California and Pennsylvania are notable non-conforming states); the state-level analysis is separate from the federal analysis. The QSBS analysis interacts with §368 reorg treatment and, in narrow cases, with §338(h)(10) election patterns. Live analysis for specific shareholders in specific transactions requires qualified tax counsel, with personal tax and estate-planning counsel involved for individual planning. Post-transaction personal-wealth planning around QSBS is covered in mod-114.
