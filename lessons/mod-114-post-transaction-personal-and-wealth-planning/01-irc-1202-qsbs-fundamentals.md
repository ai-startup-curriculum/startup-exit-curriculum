# IRC §1202 QSBS Fundamentals — the Statutory Anatomy for the Post-Transaction Founder

## Why this matters

IRC §1202 is, in dollar terms, the single largest personal-tax benefit a US founder or early-employee shareholder can access on an exit. When it works, it lets a non-corporate shareholder exclude from federal income tax **the greater of $10 million or 10 times the shareholder's aggregate adjusted basis** in qualifying stock — per issuer per shareholder — with the exclusion percentage set by the *acquisition-date vintage* of the stock (100% for stock acquired after September 27, 2010; 75% for stock acquired between February 18, 2009 and September 27, 2010; 50% for earlier vintages). Applied to a $10M gain on 100%-exclusion stock in a state that conforms to §1202, the federal capital-gains tax owed is *zero* rather than roughly $2.38M (the combined 20% top long-term capital-gains rate plus the 3.8% net-investment-income tax). Applied incorrectly — because one of the qualifying-stock requirements is not satisfied and the taxpayer discovers this in an audit rather than in pre-close planning — the result is the full tax bill plus interest plus (in aggravated cases) accuracy-related penalties.

The gap between "works" and "does not work" is entirely statutory. §1202 does not accept the taxpayer's assertion that stock is QSBS; it requires the stock, the issuer, and the shareholder to satisfy a specific list of statutory tests at specific times, and the burden of proof sits with the taxpayer. A founder who does not know which of these tests apply to their specific tranche of stock cannot ask counsel the right questions before the sale, and cannot organise the *evidence* the position depends on before the acquirer's diligence process (or the IRS's examination years later) demands it. This chapter installs the statutory anatomy — the tests, the caps, the vintages, the state-conformity variation, and the AMT / net-investment-income-tax coordination — so that the exercise-01 QSBS audit and the chapter-02 stacking analysis can run against a specific personal fact pattern with the right level of detail.

> **Reminder: this is education, not tax advice.** §1202 has been amended repeatedly, has technical requirements where practitioner opinion divides, and has state-conformity rules that change year to year. A live QSBS analysis for a specific shareholder in a specific transaction requires qualified tax counsel (private-client tax attorney with §1202 experience) and, for the individual-planning layer, a personal CPA. This chapter installs the vocabulary and the framework; the specific-facts application belongs with counsel.

## The five qualifying-stock requirements

For stock to be QSBS under §1202(c) and the related provisions, all of the following must be true. Each is a distinct trap; skipping any one of them can invalidate the position for that tranche.

### 1. The issuer must be a domestic C-corporation

The issuer must be a **domestic C-corporation** — organised under US law (or DC / a US territory), and taxed as a C-corp for federal income-tax purposes. This excludes:

- **S-corporations.** S-corp stock is *never* QSBS regardless of holding period, basis, or exit form. This is one of the most common surprises for founders who ran an early-stage S-corp before converting to C-corp for VC financing; the pre-conversion holding period does not count, and the post-conversion clock restarts on the C-corp side.
- **LLCs and partnerships** (including LLCs taxed as partnerships or as disregarded entities). If the LLC later converts to a C-corp (or elects to be taxed as a C-corp), the stock issued at or after the conversion begins its §1202 clock; pre-conversion equity does not count.
- **Foreign corporations** (a corporation organised outside the US), regardless of business activity.
- **REITs, RICs, DISCs, cooperatives, and certain other specialised entities.** §1202(c)(4) excludes specific corporate categories. These are rare in the venture-backed startup world but worth knowing exist.

The issuer must be a C-corp *at the time of the stock's issuance* and must remain a C-corp *during substantially all of the shareholder's holding period*. If the issuer converts to an S-corp mid-way through, the §1202 status of the stock is compromised for the periods in which the corporation was not a C-corp.

### 2. The stock must be acquired at original issuance

The shareholder must have acquired the stock **directly from the corporation** (or through an underwriter in the corporation's securities offering) in exchange for money, property (other than stock), or as compensation for services. Stock acquired from another shareholder in a *secondary* transaction is **not** QSBS — the original-issuance requirement is satisfied only by the *first* recipient of the stock from the corporation.

There are two important nuances:

- **Stock received in a §368 tax-free reorg in exchange for QSBS carries over QSBS characteristics under §1202(h)(4).** This preserves QSBS treatment through a stock-for-stock M&A transaction and through certain other corporate reorganisations. The acquirer stock is treated as if the shareholder had acquired it at the original acquisition date of the target stock (subject to specific rules, especially around the acquirer's own qualifying-issuer status).
- **Stock received by gift or bequest carries over QSBS characteristics under §1202(h)(2).** This is the linchpin of the stacking strategy in chapter 2 — a founder can gift QSBS to a non-grantor trust or to a family member, and the recipient's holding period tacks onto the donor's, preserving the QSBS characteristics and unlocking an *independent* $10M cap in the recipient's hands.

Common failure modes on the original-issuance requirement:

- **Option-holders.** An early employee holding an unexercised option does *not* hold QSBS — options are not stock. The employee holds QSBS only after exercising the option (and only if all other tests are met at the exercise date). The 5-year clock starts at *exercise*, not at grant.
- **RSUs.** RSU holders acquire stock at *vesting-plus-delivery*, not at grant. The 5-year clock starts at delivery. RSUs granted after the corporation's gross assets exceed $50M produce stock that does not satisfy the gross-asset test at issuance (see requirement 4), regardless of when the RSU vests.
- **Convertible-note conversion.** Stock received on conversion of a convertible note is generally treated as issued at the time of *conversion*, not at the time of the original note purchase. The 5-year clock starts at conversion, and the corporation's gross-asset status is measured at conversion.
- **SAFEs.** Similar treatment to convertible notes in most practitioner analysis, though the specific tax treatment of SAFEs remains an area where practitioner opinion is not fully settled. Tax counsel should confirm the treatment for any specific SAFE conversion.
- **Secondary-purchase stock.** Stock a founder or employee acquired by buying it from another shareholder (a common-stock secondary from an earlier employee, a repurchase from a departed founder) is not QSBS in the buyer's hands, regardless of whether it was QSBS in the seller's hands.

### 3. The $50M gross-asset test at issuance

At the time the stock is issued (and immediately after, taking into account amounts received from the issuance), the corporation's **aggregate gross assets must not exceed $50 million**. Gross assets are measured at the corporation's *adjusted basis* (with certain modifications), not at fair market value. Cash contributed for the stock counts toward the $50M ceiling after the issuance.

Three important nuances:

- **The test is measured at issuance and immediately after — not at sale.** If the corporation's gross assets grow beyond $50M *after* the stock was issued, that does not disqualify the previously-issued stock. The $50M test is a one-shot test at each issuance date. This is why a founder's founding-shares tranche can remain QSBS even after the corporation has raised hundreds of millions of dollars: the shares were issued when the corporation had essentially zero assets, and the $50M test was easily satisfied.
- **Aggregation rules apply.** §1202(d)(3) and the related aggregation rules under §1563 mean that gross assets of a parent-subsidiary controlled group are aggregated for the $50M test. A corporation cannot escape the $50M ceiling by holding assets in a subsidiary; the subsidiary's assets count.
- **A tranche of stock issued after the corporation crosses $50M is not QSBS.** RSUs granted after a Series C that pushed the corporation over $50M vest into non-QSBS stock. Options granted after that Series C exercise into non-QSBS stock. Late employees are usually the population most affected by this — their equity is likely non-QSBS regardless of how long they hold it, because the corporation had already crossed the $50M ceiling before their stock was issued.

### 4. The active-business requirement

During **substantially all** of the shareholder's holding period, the corporation must have been engaged in a **qualified trade or business** — i.e., an active trade or business whose primary activity is *not* one of the excluded categories in §1202(e)(3). The excluded categories are:

- Any trade or business involving the *performance of services* in the fields of health, law, engineering, architecture, accounting, actuarial science, performing arts, consulting, athletics, financial services, or brokerage services.
- Any banking, insurance, financing, leasing, investing, or similar business.
- Any farming business (including the business of raising or harvesting trees).
- Any business involving the production or extraction of products for which a percentage-depletion deduction is allowed.
- Any hotel, motel, restaurant, or similar business.

The corporation must also meet the **active-business asset test**: at least 80% (by value) of the corporation's assets must be used in the active conduct of one or more qualified trades or businesses. Cash and cash-like assets held for working-capital purposes count as used in the active business for a limited window (subject to specific rules on the working-capital-safe-harbour period, which practitioner opinion has debated in the ambiguous edge cases). Cash accumulated as pure investment does not count.

Application to venture-backed startups:

- **Pure-software SaaS, developer tools, marketplaces, e-commerce, cybersecurity, and most B2B software** are typically qualified trades or businesses. They are not in the excluded categories, and their active-business asset ratios typically satisfy the 80% test easily.
- **AI startups whose primary business is *custom AI implementation services*** — i.e., the business model is fundamentally consulting-with-AI-tools rather than a productised offering — sit near the excluded-category boundary. Tax counsel makes the specific call, but a business that looks like a professional-services shop dressed as an AI company can fail the active-business test.
- **Fintech startups** whose business is fundamentally banking, lending, insurance, brokerage, or similar can fail the active-business test on a categorical basis. The specifics matter: a fintech that operates a *software platform* used by banks (a B2B software business) is usually qualified; a fintech that *is* a bank or a broker-dealer typically is not.
- **Healthtech startups** are on a spectrum: a software-and-data-analytics business selling to hospitals is typically qualified; a business that *performs health services* (a telemedicine practice, a lab, a clinic) is typically not.
- **Biotech and pharma** face a nuanced analysis — the exclusion for businesses whose "principal asset is the reputation or skill of one or more of its employees" (part of the consulting category under §1202(e)(3)(A)) applies to some, but not all, biotech businesses. Tax counsel and the specific facts matter.

The active-business test runs across "substantially all" of the shareholder's holding period. Practitioner interpretation of "substantially all" varies; a conservative reading is 90–95% of the holding period, but the statute does not define the term precisely. A corporation that transitions from a qualifying business to a non-qualifying one (e.g., a startup that pivots into pure financial services) can compromise QSBS status for the holding period after the transition.

### 5. The shareholder must be a non-corporate taxpayer

The §1202 exclusion is available only to **non-corporate shareholders** — individuals, and certain pass-through entities (partnerships and S-corps that pass §1202 gain through to non-corporate partners / shareholders, and certain trusts). C-corp shareholders do not benefit from §1202.

- **Individuals** (US taxpayers filing as individuals or married-filing-jointly) are the primary intended beneficiaries and the primary population served by this module.
- **Grantor trusts** (revocable trusts, and irrevocable grantor trusts under §§671–679) are treated as owned by the grantor for income-tax purposes; §1202 flows through to the grantor's individual return.
- **Non-grantor trusts** (irrevocable trusts that are not grantor trusts) are separate taxpayers for income-tax purposes; §1202 applies at the trust level, with the trust having its own $10M cap. This is the mechanism behind the stacking strategy in chapter 2.
- **Partnerships and S-corps** pass §1202 through to their non-corporate partners / shareholders under §1202(g), subject to the partner / shareholder having held their partnership / S-corp interest during the entire QSBS holding period.

## The exclusion cap — the greater of $10M or 10x basis, per issuer per shareholder

§1202(b) sets the exclusion cap as the *greater* of:

- **$10 million**, reduced by the aggregate gain previously excluded from that same issuer's QSBS in prior tax years by the same shareholder; **or**
- **10 times the shareholder's aggregate adjusted basis** in QSBS of that issuer disposed of during the tax year.

The cap is *per issuer per shareholder*. A shareholder holding QSBS in multiple qualifying corporations has a separate $10M / 10x-basis cap for each. This is the arithmetic reason a founder who has co-founded (or angel-invested in) multiple qualifying startups can have multiple stacked $10M caps at the *founder* level, in addition to the trust-stacking and family-gifting patterns of chapter 2.

Practical arithmetic:

- **Founder with $10M gain on stock with $10K basis.** The exclusion cap is greater of ($10M) or (10 × $10K = $100K). Because $10M > $100K, the cap is $10M — the entire gain is excluded (assuming 100%-vintage stock). Federal capital-gains tax owed: $0.
- **Founder with $15M gain on stock with $10K basis.** The cap is still $10M. The first $10M is excluded; the remaining $5M is taxable at capital-gains rates. Federal tax on the taxable portion: approximately $5M × 23.8% = $1.19M (combined top capital-gains rate 20% + NIIT 3.8%).
- **Founder with $50M gain on stock with $6M basis** (perhaps because the founder exercised options at a materially non-zero strike price, or acquired the QSBS position by an intra-family purchase at fair market value). The cap is greater of ($10M) or (10 × $6M = $60M). Because $60M > $10M, the cap is $60M — the entire $50M gain is excluded (assuming 100%-vintage stock). This is the 10x-basis pathway and is rarely relevant for founders but can be relevant for angels who acquired stock at a materially non-zero purchase price.
- **Founder with $30M gain on stock with $50K basis.** The cap is greater of ($10M) or ($500K). Cap is $10M. First $10M excluded; $20M taxable at approximately 23.8% = $4.76M federal tax. Chapter 2's stacking strategies address how to expand the cap for a fact pattern like this.

The cap runs *cumulatively per issuer per shareholder across tax years*, not per-year. A shareholder who excluded $6M in year 1 and sells more of the same issuer's QSBS in year 2 has $4M of $10M-pathway cap remaining. The 10x-basis pathway can produce additional cap in year 2 if the year-2 basis is different.

## The vintage-dependent exclusion percentage

The percentage of §1202-eligible gain that is *excluded* from federal income tax depends on when the stock was **acquired**, not when it was sold. §1202 has been amended repeatedly, and the exclusion percentage is a step-function of the acquisition date:

- **Stock acquired *after* September 27, 2010** — **100% excluded**. This is the modern rule, made permanent by the PATH Act of 2015 for stock acquired after September 27, 2010. Federal capital-gains tax on the excluded portion: $0. AMT: not a preference item (the AMT-preference add-back was eliminated for post-September-27-2010 stock).
- **Stock acquired between February 18, 2009 and September 27, 2010** — **75% excluded** (with 25% taxable at capital-gains rates). AMT: 7% of the excluded portion is treated as an AMT preference item under §57(a)(7).
- **Stock acquired between August 11, 1993 and February 17, 2009** — **50% excluded** (with 50% taxable, plus the 50% taxable portion subject to a maximum 28% capital-gains rate under §1(h)(4)(A)(ii)). AMT: 7% of the excluded portion is treated as an AMT preference item.
- **Stock acquired before August 11, 1993** — §1202 did not exist; no exclusion is available.

Practical consequence: nearly all founder QSBS in the current market is 100%-vintage (acquired after September 27, 2010). The 75% and 50% vintages are relevant only for founders or angels whose acquisition dates predate September 27, 2010 — a small population, but not zero. A founder who received founding shares in 2008 and is now exiting in a 2026 transaction holds *75%-vintage* stock, not 100%-vintage.

The vintage rule can produce a mixed position within a single shareholder's holdings — some shares acquired at 2008 vintage, some acquired at 2012 vintage — and each tranche is analysed on its own vintage. This is one of the many reasons a QSBS-position audit (exercise-01) walks tranche by tranche rather than at the shareholder aggregate.

## The state-conformity variation

The §1202 exclusion is a *federal* rule. State income-tax conformity varies materially, and for a founder whose primary residence and tax domicile is in a non-conforming state, the state-level tax on the *federally-excluded* gain can be material.

- **California — does not conform.** California specifically does not conform to §1202 and imposes state income tax on the *entire* gain at up to 13.3% (the top California marginal rate as of the 2026 tax year; verify current rate at <https://www.ftb.ca.gov/>). A California-resident founder with a $10M federally-excluded QSBS gain still owes approximately $1.33M in California state tax on that gain. This is one of the largest personal-tax-planning drivers for California founders considering pre-close state residency changes — though state residency changes are complex, require actual physical relocation and severance of California ties, and are aggressively audited by California's Franchise Tax Board.
- **Pennsylvania — does not conform.** Pennsylvania does not conform to §1202 for the state personal income tax. Pennsylvania's flat 3.07% rate applies to the full gain.
- **Massachusetts — conforms** (subject to specific Massachusetts rules on qualifying property that are stricter than the federal rules in some respects; consult Massachusetts DOR guidance). Massachusetts recognises §1202 with modifications.
- **New York — conforms** to §1202 for personal income tax. A New York-resident founder whose federal §1202 exclusion applies also has the exclusion at the New York state level; New York City tax is a separate consideration.
- **Texas, Florida, Washington, Nevada, South Dakota, Wyoming, Alaska, New Hampshire (interest-and-dividends only), Tennessee** — no state personal income tax, so §1202 conformity is a non-issue at the state level. These are frequently-considered relocation destinations for high-value liquidity events, though as noted above the mechanics of a defensible residency change are complex.

<!-- needs-research: precise state-by-state §1202 conformity table for the 2026 tax year, ideally sourced from the CCH State Tax Guide or an authoritative state-by-state study. States other than CA, PA, MA, NY, and the no-tax states above should be individually verified before being cited in a plan. -->

The state-conformity analysis interacts with the residency-and-domicile rules. A founder who moves residence from California to Texas *before* the QSBS sale can potentially avoid California tax on the gain, but California's residency-audit standards are aggressive — the FTB looks at physical days, family location, home ownership, driver's license, vehicle registration, voter registration, and business ties. A cursory move immediately before a sale is not a defensible residency change. Tax counsel and (for large positions) a specific California residency-change advisor are required.

## AMT and net-investment-income-tax coordination

Two federal tax overlays interact with §1202:

- **Alternative Minimum Tax (AMT).** For 100%-vintage QSBS (post-September-27-2010), the §1202 exclusion is *not* an AMT preference item — the excluded gain is excluded for both regular tax and AMT purposes. For 75% and 50% vintages, 7% of the excluded portion is an AMT preference item under §57(a)(7), which can trigger AMT for high-basis or high-gain positions. For most current-generation founders, this is not a live consideration; for pre-2010 vintages it is.
- **Net investment income tax (NIIT) — §1411.** The NIIT imposes a 3.8% tax on net investment income (including capital gains) for taxpayers above the applicable income thresholds ($200K single / $250K joint as of the 2026 tax year; verify current thresholds at <https://www.irs.gov/individuals/net-investment-income-tax>). *Excluded* §1202 gain is excluded from NIIT as well — the exclusion applies for both regular tax and NIIT purposes. Non-excluded gain (i.e., gain above the $10M / 10x cap, or gain on non-QSBS stock) is subject to NIIT if the taxpayer's income exceeds the threshold.

The practical effect: for a 100%-vintage QSBS position within the cap, the federal tax owed on the excluded portion is *zero* — no capital-gains tax, no AMT, no NIIT. This is what makes §1202 the largest personal-tax planning consideration in a founder exit; the effective rate on the excluded portion is 0%, compared to roughly 23.8% for non-QSBS long-term capital gains (20% top rate + 3.8% NIIT) or roughly 37% for short-term gains (top ordinary rate + NIIT).

## Coordination with §1045 rollover

If a shareholder sells QSBS held for more than 6 months but *less than* 5 years — i.e., not yet eligible for the §1202 exclusion because the holding period is not met — §1045 provides a deferral mechanism. The shareholder can reinvest the sale proceeds in *replacement QSBS* within 60 days of the sale; the gain is deferred (not eliminated), with the shareholder's basis in the replacement stock reduced by the deferred gain, and the shareholder's holding period in the replacement stock tacks onto the holding period of the original stock. When the replacement stock is later sold, the deferred gain plus any additional gain on the replacement stock is recognised at that time and, if the 5-year holding period (including the tacked period) has been met, is potentially eligible for §1202 exclusion.

§1045 mechanics are covered in chapter 2 with the stacking strategies. The interaction to flag here is that a founder whose stock has *not* reached the 5-year holding period at the transaction close is not without options — §1045 can preserve the eventual §1202 opportunity if the founder is willing to reinvest the proceeds in a new qualifying startup within 60 days.

## Documentation and evidence — what to keep, and why

§1202 audits — whether by the IRS or by the acquirer's tax diligence process — turn on documentation. A founder claiming §1202 must be able to prove, at the time of the audit, that the stock was QSBS at the time of the sale. The evidence needed:

- **Stock certificates or ledger entries** documenting the acquisition date and the acquisition consideration (cash paid, services rendered, property contributed).
- **Corporate charter documents** at the time of each acquisition, demonstrating C-corp status.
- **Gross-asset balance sheets** at the time of each stock issuance, demonstrating that gross assets did not exceed $50M immediately before and after the issuance. Practitioners commonly recommend obtaining a **QSBS attestation letter** from the corporation's CFO or tax advisor at the time of each material stock issuance — a short letter stating that, as of the issuance date, the corporation was a C-corp, gross assets did not exceed $50M immediately after issuance, and the corporation was engaged in a qualifying active trade or business. Absent this letter, reconstructing the evidence years later — after the corporation may have been acquired, dissolved, or otherwise become unavailable — can be difficult or impossible.
- **Business-purpose documentation** demonstrating that the corporation was engaged in a qualifying active trade or business throughout substantially all of the holding period. In practice this is often satisfied by the corporation's ordinary operating documents (board minutes, product roadmaps, financial statements, revenue reporting) — but the founder should confirm during pre-transaction planning that the documentation supports the position.
- **Option exercise notices** and **stock-plan-administrator records** for stock acquired via option exercise, RSU vesting, or convertible-note conversion, documenting the acquisition date and the specific circumstances.

The QSBS position is only as good as the evidence that supports it. A founder who intends to claim §1202 on an exit should confirm with the corporation's finance function that the evidence chain is intact — ideally through a periodic (annual or biennial) QSBS attestation letter — long before the exit is on the horizon.

## Common failure modes — what to watch for

- **The 5-year holding period trap.** The most common single failure. A founder or early employee whose 5-year holding date falls a few months *after* the transaction close cannot claim §1202 on that sale. §1045 rollover is the fallback; delaying the transaction is rarely commercially viable. Pre-close planning (walking the acquisition dates tranche by tranche) surfaces this in time to structure around it (e.g., seller notes with deferred delivery to push part of the consideration past the 5-year date).
- **The RSU-vesting-post-$50M trap.** Late-stage RSUs vest into non-QSBS stock if the corporation's gross assets exceeded $50M when the RSU was granted (or when the underlying stock was issued into a subsidiary that later delivered on the RSU). A senior hire in year 4 whose stock package is entirely RSUs granted after the Series C typically holds *zero* QSBS despite holding meaningful equity.
- **The S-corp-early-days trap.** A corporation that ran as an S-corp for its early years and converted to C-corp only at Series A has *no* QSBS in the pre-conversion equity, and the C-corp clock starts at conversion. A founder with a 2018 S-corp incorporation and a 2020 C-corp conversion holds C-corp stock with a 2020 acquisition date, not a 2018 one.
- **The active-business-boundary trap.** A business that started as a software-and-tools company and pivoted into a consulting-with-AI-tools shop may cross the excluded-category boundary. §1202 requires "substantially all" of the holding period to be in a qualified trade or business; a mid-holding-period pivot into an excluded category can compromise the position.
- **The state-conformity surprise.** A California-based founder who assumed federal §1202 exclusion also meant no state tax discovers, in the accountant's post-close spreadsheet, that California's 13.3% top rate applies to the entire gain. Pre-close planning around state residency (only defensible if genuinely executed) or state-conforming trust structures (a topic for chapter 2 and for estate counsel) can address this before it becomes an assumption.
- **The gross-asset-test-at-issuance surprise.** A founder whose stock was issued after the corporation had already crossed $50M in gross assets (e.g., stock issued in a Series D under a top-up equity refresh) is *not* QSBS regardless of holding period. The $50M test is a hard cutoff at issuance.
- **The secondary-purchase surprise.** A founder who bought back stock from a departing co-founder, or an early employee who bought stock from another employee in a secondary, holds *non-QSBS* stock for the portion they acquired secondarily — even if the seller's original stock was QSBS. The original-issuance requirement is not transferable through a secondary sale (though it *is* transferable through a gift or bequest under §1202(h)(2), which is the mechanism chapter 2 uses).

## Summary

IRC §1202 provides a 100% federal-tax exclusion — with no AMT preference and no NIIT — for gain on qualifying small business stock, up to the greater of $10M or 10x basis per issuer per shareholder, subject to a specific list of qualifying-stock requirements (C-corp issuer at issuance, original-issuance acquisition, $50M gross-asset test at issuance, active-business test throughout the holding period, non-corporate shareholder) and a 5-year holding period. The exclusion percentage is vintage-dependent (100% for post-September-27-2010 stock, 75% for the 2009–2010 window, 50% for earlier). State conformity varies (California and Pennsylvania are notable non-conformers; Massachusetts and New York conform). The §1202 position depends on evidence — corporate documentation, gross-asset records, active-business documentation — that is much easier to gather during the corporation's active life than to reconstruct after an exit. Chapter 2 develops the stacking strategies that multiply the per-shareholder cap through non-grantor trusts, family gifting, spousal planning, GST coordination, and the §1045 rollover for pre-5-year sales.
