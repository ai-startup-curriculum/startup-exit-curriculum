# Post-Lockup Diversification — Concentration-Risk Quantification and the Sale-vs-Hedge Toolkit

## Why this matters

A founder who has ridden the company from incorporation through IPO holds a position that is, by any reasonable measure, *concentrated*. The single position is typically 60–95% of the founder's investable net worth, sits in the same issuer whose operational risks the founder is intimately familiar with, and is correlated with the founder's human capital (career, salary, reputation) at the same issuer. Modern portfolio theory says almost nothing about the founder's *pre-IPO* concentration — the position was illiquid and the operating leverage of ownership had to sit somewhere — but everything about the *post-lockup* concentration. Once the position is liquid, the concentration is a *choice*, and it is a choice that is expensive to make wrong.

The academic and practitioner literature is unambiguous about the tail risk. A single-issuer position representing more than roughly 20–25% of a portfolio is a first-order determinant of the portfolio's return distribution — the position's idiosyncratic risk dominates diversifiable market risk, and drawdown outcomes are dominated by the tail behaviour of the single stock. Meta's post-IPO trajectory (2012 IPO at $38, trough at $17.73 in September 2012, recovery over the following years) is a widely-cited example: a founder or early employee who held the entire position through the trough saw the paper wealth drop by 53% at the low, taking a real cost in the form of foregone diversification-adjusted return and psychological pressure to sell into weakness. The counter-example — a founder who diversified 40% of the position in the first six months post-lockup and then held the remainder — captured most of the eventual recovery upside while surviving the trough with a materially smaller pain.

Diversification comes at a tax cost. Every share sold triggers capital-gains tax (unless it is offset by losses, sheltered by §1202 within the founder's cap, gifted to a non-grantor trust before sale, contributed to a CRT or DAF, or otherwise structured to avoid current recognition). The tax cost is not zero; for a 100%-vintage QSBS position within cap it is close to zero for the excluded portion, and for the non-excluded portion it is roughly 23.8% federal plus state. The *hedge* alternatives — exchange funds, options collars, prepaid variable forward contracts — reduce the concentration risk without triggering current-year capital gains, but they carry their own costs: illiquidity, counterparty risk, opportunity cost on upside above defined ranges, and (for exchange funds) a 7-year holding-period lock. This chapter installs the analytic framework for quantifying the concentration risk, the sale-vs-hedge toolkit, and the trade-off matrix that lets a founder (with the founder's wealth manager and tax advisor) author a defensible post-lockup diversification plan.

> **Reminder: this is education, not investment or tax advice.** Every diversification tool discussed here has counterparties, fees, tax consequences, and suitability conditions that vary by fact pattern. Exchange funds and prepaid variable forward contracts are private-placement securities available only to accredited investors and typically only to qualified purchasers; options collars require options-approved brokerage accounts and margin arrangements; option strategies produce tax consequences that depend on the specific option treatment (§1234, §1256, §1259 constructive sales, wash-sale rule interaction) and require CPA review. A live plan requires a wealth manager (ideally a fiduciary registered investment advisor, not a commission-based broker), a CPA, and — for the private-placement structures — counsel review of the specific offering documents. This chapter is what you read *before* you engage them so their time goes to judgment, not education.

## Quantifying the concentration risk

The first analytic step is quantifying the concentration. The specific measures a wealth manager or the founder's own analysis should produce:

### Position size relative to total net worth

The most direct measure. Compute:

- **Concentrated position value** — number of shares × current market price.
- **Total investable net worth** — concentrated position value + all other liquid investments (public-market portfolios, mutual funds, cash) + illiquid financial assets (private-fund LP interests, angel positions) + real estate net of mortgages + other tangible net worth.
- **Concentration ratio** — concentrated position value / total investable net worth.

A concentration ratio above 50% is aggressive by any standard portfolio theory measure and is where most post-IPO founders start. Above 80% (which is common for founders whose personal balance sheet was built entirely by the IPO) the position dominates the founder's return distribution.

Excluded from investable net worth: primary residence (if the founder has no intention of selling), retirement accounts (401(k), IRA — these have their own tax treatment and are typically diversified via the plan-fund allocation), specific illiquid assets the founder has no intention of monetising (art, collectibles).

### Human-capital correlation

The founder's *human capital* — their career, salary, reputation, and future earning power — is highly correlated with the concentrated position's issuer. A founder still employed at the issuer whose stock they hold has essentially all their income and their principal wealth exposed to the same issuer's operational and market risk. The correlation is close to 1.

The practical implication: for a founder still employed at the issuer, the *portfolio-level* concentration is materially worse than the shares-only concentration measure suggests. A founder whose shares are 60% of investable net worth *and* who earns $600K salary from the issuer has close to 80–85% of their true economic exposure to the single issuer once salary NPV is included. Diversification decisions for a founder still at the company should account for this human-capital exposure.

For a founder who has departed the company (as many founders do after IPO within 1–3 years), the human-capital correlation drops — the founder's income no longer comes from the issuer. But reputation and network correlation persist longer (the founder's identity is tied to the issuer's story for years post-departure), and if the founder maintains a large residual position, the exposure remains.

### Realistic drawdown scenarios

A rigorous quantification looks at drawdown scenarios rather than just point-in-time concentration:

- **Sector-comparable drawdowns.** For a founder in a SaaS company, look at the peak-to-trough drawdowns in the 2022 SaaS-multiple compression (many high-growth SaaS names dropped 60–80% from November 2021 highs to October 2022 lows). For a founder in a biotech, look at the XBI drawdown patterns. For a founder in a fintech, look at the FINX drawdown patterns.
- **Idiosyncratic drawdown.** In addition to sector drawdowns, single-issuer drawdowns tied to company-specific events (missed earnings, product failure, regulatory action, executive departure, competitive disruption) can be much deeper than sector drawdowns. Estimating the tail of the single-issuer drawdown is inherently uncertain — but noting that a 50% single-stock drawdown is a realistic worst-case scenario for any individual issuer over a multi-year horizon is a defensible starting point.
- **Wealth impact.** Multiply the concentrated position value by the drawdown percentage to compute the dollar wealth at risk. Compare to (i) the founder's living expenses for a defined horizon (5 years, 10 years, indefinite) and (ii) the founder's stated financial goals (retirement funding, house purchase, education funding, philanthropic goals).

The quantification produces a specific number: "in a 50% drawdown scenario, the founder loses $Xm of wealth, which is Y% of the amount required to satisfy the founder's stated non-negotiable financial goals." That number is what the diversification decision reasons against.

## The sale-based toolkit — direct diversification through liquidation

### Staged sale under a 10b5-1 plan

The most common and most conceptually simple diversification tool: sell shares over a defined horizon under a 10b5-1 plan (chapter 3). Design considerations:

- **Sale horizon.** Typical horizons are 12–36 months. Shorter horizons (12 months or less) minimise concentration-risk exposure but concentrate market-timing risk (if the stock trades near the low during the sale window, the founder captures the low). Longer horizons (24–36 months) spread the market-timing risk but leave more concentration in place for longer.
- **Sale target.** The plan can target a specific dollar amount (e.g., "sell $50M over 24 months"), a specific share count (e.g., "sell 500,000 shares over 24 months"), or a specific reduction in concentration (e.g., "sell until concentration is below 25% of net worth"). The dollar-target and share-target designs are simpler; the concentration-target requires ongoing monitoring and periodic plan modification.
- **Sale cadence.** Fixed monthly sales (equal-share or equal-dollar amounts) are the simplest. Volume-participation formulas (tied to daily reported trading volume) reduce market impact for very large positions. Price-condition triggers can capture upside above defined levels.

### Tax-loss harvesting and offset

For founders with any *unrealised losses* in other positions (private-market angel investments, other public-market holdings), realising those losses in the same year as the concentrated-position sales can offset the gains for tax purposes. §1211 caps net capital losses at $3,000 per year for offset against ordinary income, but capital losses can offset capital gains without limit.

For QSBS-qualifying positions within cap, this is largely moot (the excluded gain is not taxable and does not need offset). For non-QSBS or above-cap gains, tax-loss harvesting can reduce the current-year tax by 20–37 cents per dollar of loss realised (depending on the character of the gain).

The **wash-sale rule** (§1091) prevents claiming a loss on a security if the taxpayer purchases substantially identical securities within 30 days before or after the sale. The wash-sale rule applies to the loss position, not the gain position — a founder harvesting losses on unrelated stock while selling concentrated-position gain does not run afoul of the wash-sale rule.

### Charitable-vehicle contribution before sale

Contributing appreciated stock to a CRT, DAF, or private foundation *before* the sale (chapter 5) allows the vehicle to sell the stock without triggering current-year capital-gains tax to the founder. The founder receives a charitable deduction for the fair-market-value of the contribution (subject to the §170 percentage-of-AGI limits), and the sale proceeds — inside the tax-exempt vehicle — support future charitable distributions or the founder's charitable commitments.

The mechanics require pre-close planning; contributing stock after the sale (or after the sale has become effectively certain) can be challenged as "anticipatory-assignment-of-income" and reversed for tax purposes. Chapter 5 develops the pre-close-contribution discipline.

## The hedge-based toolkit — reducing concentration without triggering current-year tax

For founders who want to reduce their economic exposure to the concentrated position without triggering current-year capital-gains tax, the hedge-based tools provide alternatives. Each tool has structural costs and specific tax and regulatory nuances.

### Exchange funds (Cache, Long Angle, Eaton Vance, Ithan Creek, and others)

An **exchange fund** (also called a "swap fund") is a private-placement investment vehicle organised under §721 of the Internal Revenue Code that allows accredited investors to contribute their individual concentrated positions into a diversified fund in exchange for a pro-rata interest in the fund. The contribution is treated as a *tax-free exchange* — the contributor does not recognise gain at contribution — and the contributor's basis in the fund interest is the basis of the contributed stock.

**Mechanics:**

- **Diversification.** The fund holds a diversified portfolio of contributed stocks from many contributors (typically 40+ different single-issuer positions). No single position dominates the fund.
- **7-year holding period.** The tax-free treatment under §721 depends on the fund's structure and on the contributor holding the fund interest for a minimum period (traditionally 7 years). Withdrawal before the 7-year mark can trigger recognition of the deferred gain plus penalties defined by the fund's operating agreement.
- **Portfolio composition requirement.** §721 requires the fund to hold a specific percentage of "qualified assets" — traditionally 20% or more in non-stock investments (real estate, or investments in partnerships that hold real-estate assets). This is the historical structural feature that let exchange funds qualify for §721 non-recognition treatment. The specific composition requirement is defined in the fund's operating agreement and is a structural consideration to review.
- **Distribution on withdrawal.** After the 7-year holding period, the contributor can withdraw a diversified basket of the fund's holdings (proportional to the fund's composition) with the *original basis* carrying over. The contributor now holds a diversified portfolio with the same aggregate basis they started with; capital-gains tax on future sales is measured against that original basis.

**Providers:**

- **Cache Financial (formerly Cache.Funds)** — a modern exchange-fund provider that has focused on venture-backed founders and executives with concentrated positions. <https://cache.co/>
- **Long Angle** — a community-and-exchange-fund provider serving high-net-worth families and founders. <https://longangle.com/>
- **Eaton Vance (now part of Morgan Stanley Investment Management) — Eaton Vance Exchange Funds** — long-established institutional exchange-fund manager. <https://www.eatonvance.com/>
- **Ithan Creek Capital Partners (Wellington Management)** — institutional exchange fund. <https://www.wellington.com/>
- **BNY Mellon Wealth Management (Lockwood exchange fund products)** and other traditional wealth managers.

**Trade-offs:**

- **Illiquidity.** The 7-year lock is a hard constraint. A founder who may need liquidity within 7 years of contribution should not use an exchange fund for the portion of the position they may need to access.
- **Diversification benefits.** The diversification is real but is bounded — the fund typically holds 40–100 large-single-stock positions, primarily in large-cap US public equities. It is not a broadly-diversified index-like exposure; it is a diversified basket of single-stock positions from other contributors.
- **Fees.** Exchange funds charge management fees (typically 0.5–1.5% annually) plus, in some cases, participation fees or performance fees. Model these into any comparison with the direct-sale alternative.
- **Basis carryover.** The contributor still holds the same aggregate basis. On eventual withdrawal, sales of the withdrawn diversified portfolio will trigger capital-gains tax on the deferred gain plus any post-contribution appreciation. Exchange funds *defer* gain, they do not *eliminate* it.
- **QSBS interaction.** Contributing QSBS to an exchange fund typically *forfeits* the §1202 exclusion — the contributor no longer holds the qualifying stock, the fund does, and the §721 non-recognition transfers away the QSBS characteristics. For a founder whose QSBS is within the $10M cap, direct sale under §1202 exclusion is materially better than exchange-fund contribution (the founder pays $0 federal tax on direct sale of excluded gain, vs. deferring and eventually paying full capital-gains rates through the exchange fund). For a founder whose gain exceeds the cap, exchange fund contribution of the above-cap portion may be attractive; below-cap portion should be sold direct.

### Options collars

A **collar** is a combined option position that brackets the return of a single stock within a defined range: the investor buys **protective puts** (which pay off if the stock falls below the put strike) and sells **covered calls** (which cap upside if the stock rises above the call strike). The premium received from selling the calls offsets (fully or partially) the premium paid for the puts, potentially producing a *zero-cost collar* (put premium = call premium) or a *low-cost collar* (put premium slightly higher than call premium, with the founder paying the difference).

**Mechanics:**

- **The put** provides downside protection — if the stock falls below the put strike (typically 5–15% below current market), the founder can either exercise the put and sell the stock at the put strike, or (more commonly for a founder who wants to hedge without triggering a sale) hold both the put and the stock and benefit from the increase in put value as the stock declines.
- **The call** caps upside — if the stock rises above the call strike (typically 15–35% above current market), the counterparty exercises the call and the founder must deliver stock at the call strike, forgoing the upside above that level.
- **The premium economics** balance the two. Zero-cost collars are structured so put and call premiums approximately offset.

**Tax considerations:**

- **§1259 constructive-sale rule.** A collar can trigger a constructive-sale event under §1259 if the combined position eliminates substantially all the founder's upside and downside risk. §1259(c)(2) provides safe harbours (specific relationships between the put and call strikes and the current price) that allow properly-structured collars to avoid constructive-sale treatment. Tax counsel and the specific collar structure matter — a collar with put and call strikes very close to current market may be constructive-sale; a collar with wider strikes (e.g., 90% put and 110% call) typically is not.
- **Option premium tax treatment.** Premium received from selling calls is generally treated as short-term capital gain (or as part of the sales price of the underlying if the call is exercised) under §1234. Premium paid for puts is a capital expenditure that adjusts the position basis.
- **Long-term-capital-gain-holding-period interruption.** §1092 straddle rules and the identified-straddle rules can affect the holding period of the underlying stock while the collar is in place. Careful structuring is required to avoid restart of the holding period for §1202 or long-term-capital-gain purposes.

**Trade-offs:**

- **Upside cap.** The founder forgoes upside above the call strike. For a founder whose thesis is that the stock has substantial further upside, the cap is a real cost.
- **Downside protection.** The collar limits downside to the put strike. This is the primary benefit — the collar converts the tail exposure of the concentrated position into a defined range.
- **Counterparty risk.** Options are typically written through a broker or an over-the-counter derivatives counterparty. For very large positions, the counterparty may need to hedge its own exposure, and the counterparty's creditworthiness matters.
- **Liquidity.** Exchange-listed options are liquid; OTC collars are less liquid. Rolling a collar (extending it to a later expiration) can produce meaningful transaction costs and rebalancing complexity.

Collars are typically used as a *bridge* — protecting the position from a defined downside during a 6–24 month window while the founder either (i) completes a staged sale, (ii) waits for a strategic reason to remove the collar (a specific corporate event, an earnings announcement), or (iii) rolls the collar into a new structure. Extended-duration collars (multi-year) are possible but structurally more complex.

### Prepaid variable forward contracts (PVFs)

A **prepaid variable forward contract** is a private-placement transaction in which the founder agrees to deliver a defined number of shares to a counterparty at a future date, in exchange for an immediate cash payment (the "prepayment") equal to a discount of the current market value. The number of shares delivered at maturity varies based on the stock's price at maturity — the founder delivers fewer shares if the stock has appreciated, more shares if it has declined, according to a defined formula.

**Mechanics:**

- **Immediate cash.** The founder receives a large upfront cash payment (typically 75–90% of the current market value of the reference shares) at contract signing, without triggering a taxable sale under the tax-treatment analysis below.
- **Variable delivery at maturity.** At the contract's maturity (typically 1–5 years later), the founder delivers a variable number of shares determined by the stock's price at maturity relative to defined thresholds. The formula typically provides upside participation up to a defined ceiling and downside protection to a defined floor — mechanically similar to a collar.
- **Non-recourse.** The prepayment is non-recourse to the founder; if the founder cannot deliver shares at maturity (e.g., the shares have been sold or transferred), the counterparty's remedy is limited to the reference shares themselves (which are typically pledged as collateral for the delivery obligation).

**Tax considerations:**

- **Not a current-year sale.** Under long-standing tax authorities (Rev. Rul. 2003-7 and related), a properly-structured PVF is treated as an *open transaction* — the prepayment is not treated as sale proceeds at signing, but as a loan that is forgiven at maturity in exchange for the share delivery. Capital gain is recognised at maturity, based on the price at which the delivered shares are treated as sold.
- **§1259 constructive-sale interaction.** PVFs are subject to §1259 constructive-sale analysis. Properly-structured PVFs use variable-delivery formulas that leave the founder with material downside exposure (below the floor) or upside exposure (above the cap) to avoid constructive-sale treatment. The specific structure requires tax-counsel review.
- **Holding-period preservation.** A properly-structured PVF preserves the founder's holding period in the underlying shares through the contract's life, preserving the eventual long-term-capital-gain (and, for QSBS, the eventual §1202) treatment on the settlement.

**Trade-offs:**

- **Large upfront cash.** The primary benefit — PVFs unlock 75–90% of the position's value as immediate cash without a current-year taxable event.
- **Upside cap and downside floor.** The economics are similar to a collar: upside above the cap and downside below the floor accrue to the counterparty, not the founder.
- **Long maturity commitment.** The founder commits to a multi-year contract. Early termination is typically expensive or structurally not permitted.
- **Counterparty risk and structural complexity.** PVFs are private-placement transactions with sophisticated counterparties (typically large investment banks — Goldman Sachs, Morgan Stanley, JP Morgan, Citi, Deutsche Bank, UBS have historically offered them to ultra-high-net-worth clients). The counterparty documentation is bespoke, and the structural details (delivery formulas, pledge arrangements, distribution treatment during the term) require careful negotiation.
- **Public disclosure.** For Section 16 officers and directors, the PVF may trigger disclosure on Form 4 (the pledge of shares) and, if the PVF is considered part of a hedging arrangement, may need to be disclosed in the corporation's proxy statement under Item 407(i) of Regulation S-K.
- **Fees.** The discount from current market value (the 10–25% haircut) is effectively the fee — economically, the counterparty is providing cash today, taking on the price risk (subject to the cap and floor), and pricing that risk in the haircut. Model the haircut as an all-in cost of the arrangement.

PVFs are typically used by very-high-value founders (positions of $100M+) whose need is *immediate cash* without triggering current-year tax on the full position. For positions where the founder can staged-sell the required cash over 6–12 months (a common alternative pattern), the PVF's structural complexity and fees often make direct staged sale a better choice.

## The trade-off matrix

The choice among the toolkit is fact-specific. A simplified trade-off matrix:

| Tool | Current-year tax? | Reduces concentration? | Duration commitment | Complexity | Best when |
|---|---|---|---|---|---|
| Staged sale (10b5-1) | Yes (unless QSBS-excluded) | Yes | 12–36 months | Low | QSBS within cap; general default for diversification |
| Charitable-vehicle contribution then sale | No (donor deduction) | Yes | Depends on vehicle | Medium | Founder has philanthropic goals and above-cap gain |
| Exchange fund | No (deferred) | Yes | 7 years | Medium-High | Above-cap gain; founder can lock 7 years; wants diversification without current tax |
| Options collar | No | No (protects, does not diversify) | 6–24 months | Medium | Bridge protection during a defined window; founder wants to retain the position |
| Prepaid variable forward | No (deferred) | Yes (economically) | 1–5 years | High | Very large positions needing immediate cash; sophisticated counterparty engagement acceptable |

The framework in practice:

- **Below the QSBS cap** — direct sale under a 10b5-1 plan. The federal tax on the excluded portion is $0; deferral through an exchange fund or PVF adds cost without benefit.
- **Above the QSBS cap** — the choice is between (i) direct sale at ~23.8% federal blended rate, (ii) charitable-vehicle contribution before sale (which produces a §170 deduction that partially offsets the tax on other sales), (iii) exchange-fund contribution for the above-cap portion (deferring tax), (iv) PVF for the above-cap portion (deferring tax with immediate cash), or (v) some combination. Wealth manager and tax advisor jointly design the specific mix.
- **Bridge protection during the initial 12–24 months post-lockup** — a modest options collar over 10–30% of the position can provide tail-risk protection during the highest-volatility window while the staged sale program is running.

## Sequencing — what to do in what order

A defensible post-lockup sequence:

1. **Pre-IPO (T-6 to T-0 months, and often earlier).** Complete the QSBS stacking (chapter 2) if applicable. Contribute pre-close appreciated stock to CRT / DAF / foundation as planned (chapter 5). Adopt any pre-IPO 10b5-1 plan (though many founders wait until post-IPO given the greater visibility into the public-company earnings cadence).
2. **IPO through first lock-up expiration window (typically T+0 to T+180 days).** Watch price action. Adopt a 10b5-1 plan during the first open window (typically after the first post-IPO earnings release). Set the plan's first-trade date at or after lock-up expiration plus the 90-day cooling-off period. Do *not* execute any hedge structures during the lock-up (the lock-up bars pledges and other derivative arrangements involving the locked-up shares).
3. **First 12 months post-lockup.** Execute the plan's initial sales. Assess whether the position is behaving in line with expectations. If a large drawdown occurs, do not deviate from the plan (the plan's affirmative defence depends on not being modified opportunistically). Consider a modest collar over a portion of the position as bridge protection.
4. **Months 12–24 post-lockup.** Continue the plan. Assess whether the concentration has been reduced to acceptable levels. If yes, consider terminating (or letting expire) the plan and rebalancing into a diversified portfolio. If not, extend or renew the plan with an updated schedule.
5. **Years 2–5 post-lockup.** For the residual position (typically 20–40% of the original after the staged sale), consider longer-duration strategies: exchange-fund contribution, longer-duration collar, or continued slow sales. Coordinate with the CRT / DAF / foundation contributions that occur across this window.
6. **Year 5 and beyond.** For a founder who retains a meaningful residual position (typically a founder-CEO still at the company), the position is now a long-term concentrated holding requiring ongoing management — consideration of estate-planning transfers, philanthropic transfers, and (as retirement approaches) diversification into income-generating assets.

The sequence is stylised; specific fact patterns modify it. A founder whose immediate need is to fund a house purchase, an estate-plan gift, or a philanthropic commitment will have specific liquidity needs that reshape the sequence. A founder who has departed the company has different considerations from a founder still operating.

## Common failure modes — what to watch for

- **Overweighting hedge structures.** Hedges (collars, PVFs, exchange funds) *defer* the tax on the concentrated position; they do not eliminate it. A founder who over-relies on hedges eventually faces the tax bill when the hedge unwinds, often at a less favourable time (during a market drawdown, when the retained position value is lower but the deferred tax basis is the same). The rule of thumb: hedge for a defined purpose (protection during a specific window, immediate cash for a specific need), not as a substitute for eventual diversification.
- **Undervaluing tax-loss harvesting.** Many post-IPO founders have unrelated private-market positions (angel investments in other startups, LP interests in venture funds) that have declined in value. Realising those losses in the same year as concentrated-position gains can materially reduce the tax bill. The wealth manager and CPA should do a full-portfolio tax-loss review annually.
- **Underestimating market-impact.** For very large positions (>1% of daily trading volume in a sale schedule), naive sale schedules can move the stock materially against the founder. Volume-participation formulas, iceberg orders, or block trades through investment-bank sales desks may produce better execution than a mechanical daily-sale schedule.
- **Not coordinating with the philanthropic timing.** For a founder with philanthropic commitments, the tax deduction from a charitable-vehicle contribution is most valuable in a high-income year. Timing the charitable contribution to coincide with the year of the largest concentrated-position sale can maximise the tax benefit. This coordination requires planning across the wealth manager, CPA, and (for the vehicle setup) foundation counsel.
- **Under-attention to the human-capital exposure.** A founder still employed at the issuer has salary, RSU vesting, and reputation all tied to the same issuer. The diversification analysis should consider the *total* exposure, not just the concentrated-position exposure, and may lead to a more aggressive diversification schedule than the shares-only analysis would suggest.
- **Waiting for the "right price."** The most consistent finding in behavioural finance is that concentrated-position holders systematically delay diversification, waiting for a "better price" that never arrives (or arrives after a large drawdown). The 10b5-1 plan's mechanical schedule is a specific commitment device against this bias — once the plan is running, the founder cannot second-guess the market and defer the sales. The commitment is a feature, not a bug.
- **Not planning for the tax bill.** Sales generate large estimated-tax obligations. A founder who sells $20M under a plan in Q1 owes a large estimated payment for Q1. The wealth manager and CPA should coordinate the estimated-tax schedule with the plan's sale cadence.
- **Confusing tax-deferral tools with tax-elimination tools.** Exchange funds and PVFs defer tax; §1202 QSBS and charitable-vehicle contributions can *eliminate* tax on the eligible portion. The distinction matters — a deferred-tax structure is a temporary shift, not a permanent reduction.
- **Not modeling for the founder's specific life goals.** Diversification is a means, not an end. The end is that the founder can fund their stated life goals (retirement, philanthropy, family provision, angel-investing programme) without an unacceptable probability of failure. The diversification plan should be reverse-engineered from those goals, not driven by an abstract "sell X% by Y date" rule.

## Summary

Post-lockup diversification is a personal-financial-planning discipline sitting on top of the concentrated-position risk math. The first step is quantifying the concentration (position value relative to net worth, human-capital correlation, drawdown scenarios). The direct diversification toolkit is the staged sale under a 10b5-1 plan, often combined with tax-loss harvesting and (for founders with philanthropic commitments) pre-sale contributions to CRT / DAF / foundation. The hedge toolkit — exchange funds (7-year §721 vehicles that defer tax through diversified pooling), options collars (put + covered call structures that bracket the return within a defined range), and prepaid variable forward contracts (structured contracts providing immediate cash against future variable-share delivery) — provides mechanisms to reduce economic exposure without triggering current-year tax, at the cost of illiquidity, upside caps, and structural complexity. The specific choice among the tools depends on the founder's QSBS-cap status, philanthropic goals, immediate cash needs, tolerance for structural complexity, and time horizon. A defensible plan sequences the tools across the post-lockup period, coordinates the 10b5-1 plan cadence with the staged sale, and reverse-engineers the diversification schedule from the founder's stated life goals. Live plans are authored by a fiduciary wealth manager and a CPA, with counsel review for any private-placement structures. Chapter 5 develops the charitable-vehicle framework that pairs a founder wealth event with a philanthropic commitment.
