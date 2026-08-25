# QSBS Stacking — Multiplying the $10M Cap With Non-Grantor Trusts, Family Gifts, and §1045 Rollovers

## Why this matters

The chapter-1 §1202 cap is $10 million (or 10 times basis, whichever is greater) *per issuer per shareholder*. A founder with $30M of gain on a single-issuer QSBS position who has done no pre-transaction planning has $20M of gain sitting above the cap and paying roughly $4.76M in federal tax (23.8% blended rate) — plus state tax where the state does not conform. The stacking pattern lets a founder who plans well in advance of the transaction multiply the number of *separate $10M caps* that apply to the same underlying stock, potentially bringing the effective cap from $10M to $30M, $50M, or higher depending on the family structure and the willingness to commit stock permanently (or effectively permanently) to trust vehicles the founder cannot later reclaim.

The mechanism is entirely statutory: §1202(h)(2) provides that stock acquired by *gift* takes the same holding period and QSBS characteristics as the donor's stock, and each *recipient* (as a separate taxpayer) has their own $10M / 10x-basis cap. A gift to a non-grantor trust — a specific trust structure that is a separate taxpayer for income-tax purposes — creates a new $10M cap in the trust's hands. A gift to an adult family member creates a new $10M cap in that family member's hands. Repeated across several trusts and several family members, the cap arithmetic can compound quickly.

Stacking is not free. It requires (i) plausible non-tax purposes for the trusts and gifts (a purely-for-tax structure is more likely to face IRS challenge under substance-over-form and step-transaction doctrines), (ii) actual completed gifts with the founder giving up dominion and control of the transferred stock (the founder cannot later reclaim it), (iii) careful coordination with the federal gift-and-estate tax rules (lifetime exemption, GST tax, annual exclusion), and (iv) plausible advance timing — a stacking structure implemented one week before signing an LOI is much more vulnerable to challenge than one implemented 12–24 months in advance. This chapter installs the statutory anatomy of stacking; the specific fact-pattern application belongs with a private-client tax attorney and (for trust drafting) an estate attorney.

> **Reminder: this is education, not tax, legal, or estate advice.** Stacking involves irrevocable gifts of appreciated stock to trusts or family members. The founder gives up control of the transferred stock and cannot reclaim it. The federal gift-tax and GST-tax rules interact in ways that can produce unintended consequences if not authored by counsel. A live stacking plan requires a private-client tax attorney, an estate attorney (for the trust drafting), and — for large positions — potentially a trust company or independent trustee to serve as the non-grantor trust's fiduciary. This chapter is what you read *before* you engage them so their time goes to judgment, not education.

## The mechanic — §1202(h)(2) gift-carryover treatment

§1202(h)(2) provides that if stock is transferred by *gift* (as distinct from a sale), the recipient's holding period tacks onto the donor's, and the recipient is treated as having acquired the stock in the same manner and at the same time as the donor. The result: the gifted stock retains its QSBS characteristics in the recipient's hands, and the recipient — as a separate taxpayer — has their *own* $10M / 10x-basis cap under §1202(b).

Consider a founder with a QSBS position that would produce $30M of gain on sale. Without planning:

- Founder sells the entire position. Cap is $10M. First $10M excluded; $20M taxable at ~23.8% = $4.76M federal tax owed.

With a properly-structured pre-transaction gift of one-third of the position to a non-grantor trust for the benefit of Child A, and another one-third to a non-grantor trust for the benefit of Child B:

- Founder retains one-third of the position; sells; $10M gain; $10M cap; $0 federal tax on the excluded portion.
- Trust A holds one-third of the position; sells; $10M gain; $10M cap (in the trust's separate taxpayer capacity); $0 federal tax on the excluded portion.
- Trust B holds one-third of the position; sells; $10M gain; $10M cap; $0 federal tax on the excluded portion.

Total federal tax owed on the $30M of aggregate gain: $0 (versus $4.76M without stacking).

The example is stylised — real stacking runs into gift-tax rules, trust-drafting complexity, and the §643(f) and step-transaction limitations discussed below — but the arithmetic is real. Founders with $20M+ of gain on a single-issuer QSBS position who plan 12–24 months in advance routinely deliver substantial post-tax uplift through stacking.

## The non-grantor trust — the workhorse vehicle

A **non-grantor trust** is an irrevocable trust that is *not* a grantor trust under §§671–679. The distinction matters because:

- A **grantor trust** is treated as owned by the grantor for income-tax purposes. Income earned by a grantor trust is reported on the grantor's individual tax return; the trust is not a separate taxpayer. §1202 flows through to the grantor's cap — no additional cap is unlocked.
- A **non-grantor trust** is a separate taxpayer for income-tax purposes. Income earned by the trust is reported on the trust's own return (Form 1041). §1202 applies at the trust level, and the trust has its *own* $10M / 10x-basis cap.

The mechanical requirement is that the trust must not have any of the "grantor trust triggers" under §§671–679:

- **§673 — reversionary interests.** The grantor cannot retain a reversionary interest exceeding 5% of the trust's value.
- **§674 — power to control beneficial enjoyment.** The grantor (and non-adverse parties acting without adverse-party consent) cannot control the beneficial enjoyment of the trust corpus or income.
- **§675 — administrative powers.** The grantor cannot retain certain administrative powers (e.g., the power to borrow trust corpus without adequate security).
- **§676 — power to revoke.** The trust must be irrevocable — the grantor cannot have the power to revoke.
- **§677 — income for the benefit of the grantor.** Trust income cannot be distributable to (or held for the benefit of) the grantor or the grantor's spouse.
- **§678 — persons other than the grantor treated as substantial owner.** No non-grantor party may hold a power to withdraw trust corpus that would cause them to be treated as owner.
- **§679 — foreign trusts with US beneficiaries.** Special rules for foreign trusts.

A non-grantor trust that avoids these triggers is a separate taxpayer and can hold QSBS with its own $10M cap.

Practical vehicle choices:

- **Intentionally Defective Grantor Trust (IDGT)** — a specific structure that is a *grantor trust* for income-tax purposes but is *outside the grantor's estate* for estate-tax purposes. IDGTs are useful for estate planning but do *not* stack QSBS — they are grantor trusts by design, so the $10M cap does not multiply.
- **Non-Grantor Trust (typically irrevocable, third-party trustee, discretionary beneficiary provisions)** — the workhorse for QSBS stacking. Trust drafting matters: the trust must be genuinely non-grantor (avoiding all the §§671–679 triggers), have a plausible non-tax purpose (typically providing for the beneficiaries' education, health, maintenance, and support — "HEMS" provisions), and be properly administered as a separate entity.
- **Delaware or South Dakota Non-Grantor Trust** — the two states most commonly chosen for the *situs* of a non-grantor trust for high-value planning. Delaware's Directed Trust Statute and South Dakota's trust-friendly laws (perpetual trusts, favourable creditor protection, no state income tax on non-resident-beneficiary trust income) make them the standard destinations. Trust situs matters because it determines which state's income-tax rules apply to the trust; a Delaware or South Dakota non-grantor trust with no in-state beneficiaries typically pays no state income tax on the trust's income, which is a material additional benefit for a California-resident founder.
- **NING (Nevada Incomplete-gift Non-Grantor Trust) / DING (Delaware Incomplete-gift Non-Grantor Trust)** — a specialised structure designed to be non-grantor for income-tax purposes but *incomplete* for gift-tax purposes (i.e., no gift-tax consequence at contribution). The specific mechanics are complex and are the subject of ongoing IRS guidance and litigation. Not the primary QSBS stacking vehicle (the complete-gift non-grantor trust is), but relevant for founders whose lifetime gift-tax exemption is already largely consumed.

## The §643(f) multiple-trust rule — the arithmetic constraint

The obvious question when the stacking arithmetic is presented: why not create 10 non-grantor trusts and stack 10 × $10M = $100M of exclusion?

Two structural constraints answer this:

1. **§643(f) — the multiple-trust aggregation rule.** If two or more trusts have (i) substantially the same grantor(s) *and* substantially the same primary beneficiaries, and (ii) the trusts have a principal purpose of tax avoidance, the trusts can be aggregated and treated as a single trust for income-tax purposes. Aggregation would collapse the multiple $10M caps into one.

2. **The step-transaction doctrine and substance-over-form.** Even absent §643(f) aggregation, the IRS can attack a stacking structure that has no plausible non-tax purpose and was implemented in a compressed timeline immediately before a known transaction. The Kimbell (5th Cir. 2004) and related cases in the family-limited-partnership context provide the doctrinal framework; §1202 stacking has not been the subject of extensive published litigation, but practitioners assume the same doctrines apply.

The practitioner response to these constraints is to structure the trusts with:

- **Distinct primary beneficiaries** — Trust A for Child 1, Trust B for Child 2, Trust C for grandchildren, Trust D for a sibling, etc. Each trust has a distinct primary-beneficiary designation. §643(f) aggregation requires *substantially the same* primary beneficiaries, and distinct designations defeat that condition.
- **Distinct grantor(s)** — one spouse contributes to Trust A, the other spouse contributes to Trust B, non-spouse family members contribute to their own trusts. Distinct grantors defeat the "substantially the same grantor(s)" test.
- **Plausible non-tax purposes** — HEMS provisions for the beneficiaries, distinct distribution schedules, distinct trustee-oversight provisions. The trust needs to look like a genuine estate-planning vehicle, not a §1202-only tax structure.
- **Advance timing** — the trust is created and the QSBS is transferred *long before* the transaction is contemplated. A trust set up 3 weeks before signing an LOI is qualitatively different from a trust set up 18 months before, when the transaction was not on the horizon. Advance timing supports the "no principal purpose of tax avoidance" defence.
- **Independent trustees** — the trust has a professional or independent trustee (a trust company, a family friend not otherwise involved in the family's affairs) rather than a related-party trustee, and the trustee exercises genuine discretion.

The stacking-arithmetic ceiling is not "as many trusts as possible" but "as many trusts as can be justified by distinct primary beneficiaries and plausible non-tax purposes, with advance timing." For a founder with two children, four grandchildren, a spouse, and a couple of adult siblings, a stacking design might support 4–6 trusts without triggering aggregation risk. For a founder with a smaller family and less pre-existing estate-planning infrastructure, 1–2 trusts may be the defensible ceiling.

## The gift-tax and lifetime-exemption interaction

A completed gift of QSBS to a non-grantor trust is a *taxable gift* under the federal gift tax. The transfer is measured at *fair market value* on the gift date — which, for pre-transaction QSBS, requires a valuation that may be significantly higher than the founder's basis in the stock.

The federal gift-and-estate tax has three coordinated mechanics:

- **Annual exclusion** — $19,000 per donee per year for 2026 (up from $18,000 in 2024; verify at <https://www.irs.gov/businesses/small-businesses-self-employed/frequently-asked-questions-on-gift-taxes>). Gifts within the annual exclusion do not consume lifetime exemption and do not require a gift-tax return. For a large QSBS position, the annual exclusion is small relative to the transfer value; most stacking transfers are far larger.
- **Lifetime unified exemption** — approximately $13.99 million per individual for 2026 (up from $13.61M in 2024; verify current amount at <https://www.irs.gov/businesses/small-businesses-self-employed/estate-and-gift-tax-faqs>). The lifetime exemption covers both lifetime taxable gifts and testamentary transfers at death. Gifts up to the lifetime exemption pay no gift tax at the time of transfer but consume the exemption available at death.
- **Above-exemption gifts pay gift tax at 40%.** Gifts that exceed the lifetime exemption pay gift tax at 40% at the time of the gift.

A founder with $13M of lifetime exemption remaining who gifts $13M of QSBS to non-grantor trusts consumes the exemption but pays no gift tax. A founder who has consumed the exemption faces a 40% gift tax on the transferred fair market value — often a much larger cost than the §1202 savings.

**The sunset consideration.** The lifetime exemption is scheduled to sunset at the end of 2025 back to a pre-TCJA level (approximately $7 million per individual, indexed) unless Congress acts. <!-- needs-research: verify the current status of the TCJA sunset for the 2026 tax year and any extensions or modifications enacted through 2026. --> Founders whose stacking plans depend on the higher exemption face timing pressure to complete the gifts before the sunset. This has been a material driver of stacking activity in the 2023–2025 window.

**Spousal considerations.** Gift-splitting (each spouse consenting to treat gifts as half from each) can double the annual exclusion and combine the spouses' lifetime exemptions for a single gift. Spousal considerations also interact with community-property rules in community-property states (California, Texas, Nevada, Washington, Arizona, Idaho, Louisiana, New Mexico, Wisconsin) — QSBS held as community property may already have specific spousal-share considerations.

**GST tax coordination.** Gifts to non-grantor trusts whose beneficiaries include *skip persons* (grandchildren, or trusts of which the primary beneficiary is a grandchild or more remote descendant) can trigger the *generation-skipping transfer tax* (GST) at a 40% flat rate on transfers above the GST exemption (which mirrors the lifetime unified exemption). The GST exemption must be *allocated* on the gift-tax return (Form 709) or via automatic allocation; if the allocation is missed, the transfer can be subject to GST tax on distribution or termination of the trust. GST planning is a specialised discipline; estate counsel should draft any trust with grandchild-generation beneficiaries.

## Gifting to family members with independent QSBS caps

A parallel stacking mechanism is gifting QSBS directly to *adult family members* (children over the age of majority, siblings, parents) rather than to trusts. Each recipient family member has their own $10M / 10x-basis cap. The mechanics:

- Founder gifts (say) $10M of QSBS to an adult child.
- The child holds the QSBS; §1202(h)(2) applies, so the child's holding period tacks and QSBS characteristics carry over.
- When the child sells, the child has their *own* $10M cap.

The tradeoff versus trust stacking:

- **Simpler** — no trust to draft, no trustee to appoint, no §643(f) aggregation analysis.
- **Less control** — the child is an adult and controls the stock outright. Once gifted, the founder cannot direct how the child uses the sale proceeds. If the child is a minor, an UTMA / UGMA custodial account or a specific minor's trust structure is needed, which reintroduces trust considerations.
- **Same gift-tax and lifetime-exemption consumption** — the transfer is a taxable gift, consuming lifetime exemption at the fair market value of the transferred stock.
- **Kiddie-tax considerations** — if the child is under age 24 and a full-time student (or under 19 more generally), the kiddie tax may apply to some of the child's unearned income; this affects the child's tax rates on any *non-excluded* gain but does not eliminate the child's separate §1202 cap.

For founders with adult children, direct gifting is often the simplest addition to a stacking design. For founders with minor children, non-grantor trusts (structured to satisfy the §643(f) and §§671–679 requirements) are typically the vehicle of choice.

## Spousal planning and the joint-return cap

The §1202 cap is per shareholder. For a married couple filing jointly, the question of whether the couple has one $10M cap or two depends on how the QSBS is held:

- **QSBS held by one spouse only** — the couple has one $10M cap available (the shareholding spouse's). The non-shareholding spouse has no §1202 gain to exclude because they hold no QSBS.
- **QSBS held jointly (as joint tenants, tenants in common, or community property)** — each spouse is treated as a §1202 shareholder for their share; each has a $10M cap. Careful attention to how the QSBS was acquired and titled determines whether the "joint" holding satisfies the original-issuance requirement on both spouses' shares.
- **QSBS gifted from one spouse to the other during the holding period** — under §1041, inter-spousal transfers are generally treated as gifts with carryover basis. §1202(h)(2) preserves QSBS characteristics through the gift. This allows a founder to divide a QSBS position between spouses to unlock two $10M caps at a stacking level equivalent to one gift-to-trust plus one retained position.

The interaction with community-property regimes deserves specific attention: in California, Texas, and the other community-property states, stock acquired during the marriage using community resources is community property, and each spouse is treated as owning one-half. The §1202 analysis in those states already treats the QSBS as jointly-held between the spouses in most cases.

Estate-planning counsel should draft any spousal-transfer plan around QSBS — the interactions with community-property rules, the §1041 basis carryover, and the §1202 characteristics carryover are not obvious and can produce unintended consequences if not carefully structured.

## The §1045 rollover — deferring the sale of pre-5-year QSBS

Not every founder reaches the 5-year holding period by the transaction close date. §1045 provides a deferral mechanism for pre-5-year QSBS:

- **The mechanic.** The shareholder sells QSBS held for more than 6 months but less than 5 years. Within 60 days of the sale, the shareholder purchases *replacement QSBS* — newly-issued stock of a different qualifying corporation. The gain on the original sale is *deferred* (not eliminated), and the shareholder's basis in the replacement stock is reduced by the deferred gain. The shareholder's holding period in the replacement stock tacks onto the holding period in the original stock.
- **Election.** The shareholder must elect §1045 treatment on the tax return for the year of the original sale. The election is typically made on Form 8949 with a specific §1045 designation. Missing the election window forecloses the deferral.
- **The 60-day window.** The 60-day window is measured from the *sale date* of the original stock. In practice, this is a very tight window for identifying and completing an investment in newly-issued QSBS of a qualifying corporation. Pre-planning — identifying candidate replacement investments *before* the sale — is essential.
- **Partial rollover.** The shareholder can roll over less than the full sale proceeds; the deferral applies only to the portion reinvested in replacement QSBS. The unreinvested portion is taxable in the year of sale.
- **Replacement-stock QSBS requirements.** The replacement stock must itself be QSBS — the replacement corporation must be a C-corp, must meet the $50M gross-asset test at the time of the replacement stock's issuance, must be in a qualifying active trade or business, and the replacement stock must be acquired at original issuance. All the requirements of chapter 1 apply to the replacement stock.
- **Eventual §1202 treatment on the replacement stock.** When the replacement stock is later sold, the deferred gain plus any additional gain on the replacement stock is recognised at that time. If the aggregate holding period (original + replacement) is at least 5 years, the gain is potentially eligible for §1202 exclusion. If less than 5 years at the second sale, another §1045 rollover is potentially available.

Practical use cases:

- **Founder exiting to a strategic before reaching 5 years.** Founder sells QSBS with 4-year hold; rolls over into replacement QSBS in a new startup the founder is joining (or investing in as an angel). One year later, the aggregate holding period reaches 5 years, and the replacement stock qualifies for §1202 treatment on eventual sale.
- **Serial founder pattern.** A founder who exits one qualifying startup and immediately founds or angel-invests in another can use §1045 to defer the gain and preserve the eventual §1202 opportunity.
- **§1045 into partnership interests.** §1045 can also apply to partnerships (with specific rules under §1045(b)(5)). Practitioner interpretation of partnership §1045 mechanics has been the subject of IRS guidance; qualified counsel should confirm the specific treatment.

§1045 is not a stacking mechanism per se — it does not multiply the cap. It is a *holding-period-preservation* mechanism that lets a pre-5-year sale still lead to §1202 treatment on the replacement stock. In many exit fact patterns, §1045 is not operationally practical (the founder does not intend to reinvest in another qualifying startup within 60 days); when it is available, it is a specific tool worth knowing.

## The QSBS packing pattern — increasing basis for the 10x-basis pathway

A less commonly used but legitimate technique: increasing the shareholder's aggregate adjusted basis in QSBS by contributing appreciated property (not stock) to the corporation in exchange for stock. The 10x-basis pathway of §1202(b) sets the cap at 10 times the shareholder's aggregate basis, so raising the basis raises the cap.

- **The mechanic.** The shareholder contributes property (e.g., intellectual property, real estate, or other appreciated non-stock property) to the corporation in exchange for QSBS. Under §351, the contribution is generally tax-free at the corporate level and to the shareholder, with the shareholder taking the contributed stock with a basis equal to the basis of the contributed property (adjusted for any gain recognised).
- **The QSBS effect.** For §1202 purposes, the shareholder's basis in the QSBS received includes the basis of the contributed property. If the shareholder had contributed property with a $5M basis, the shareholder now has (an increment of) $5M of QSBS basis, and 10 × $5M = $50M of 10x-basis pathway cap.
- **Practical use.** The QSBS packing pattern is relevant primarily for founders whose non-cash assets (patents, IP that the founder developed personally and can transfer to the corporation) provide a source of contributable basis. It is not a widely-applied technique for most founders, but for the specific fact patterns where it fits, it can be material.

Tax counsel should confirm whether the packing pattern fits any specific fact pattern — the §351 mechanics, the §1202(i) basis-adjustment rules for contributed property, and the qualification of the contributed property under the active-business test all require specific analysis.

## The stacking timeline — why 12–24 months in advance matters

Every element of the stacking pattern is stronger with advance timing:

- **Trust drafting and situs establishment** — takes 4–12 weeks with estate counsel. Longer if the trust involves independent trustee selection (interviewing trust companies, negotiating fees) or foreign situs.
- **Gift-tax return filing** — Form 709 for the year of the gift. Not on the transaction critical path, but the record of the completed gift must exist before the transaction.
- **Trust administration establishment** — the trust must operate as a separate entity from the founder. Bank accounts, tax-ID numbers, initial trustee actions. This is not a one-week task.
- **The "no principal purpose of tax avoidance" defence** — the longer the gap between the trust establishment and the transaction, the stronger the defence against a substance-over-form or step-transaction challenge. Advance timing is arguably the *single largest determinant* of stacking-plan defensibility.
- **Valuation of the transferred QSBS** — a defensible fair-market-value determination requires a qualified appraisal (typically) or a defensible internal valuation. Advance timing supports engaging a valuation firm with time to do the work properly.
- **State residency planning** (if applicable) — physical relocation, driver's license changes, voter registration, home purchase in the new state, severance of California ties. Advance timing is essential; a residency change executed weeks before a sale is not defensible against California FTB challenge.

A stacking plan implemented 18 months before a transaction, with genuine trust administration and independent trustees, is qualitatively different from one implemented 3 weeks before signing an LOI. The former is defensible; the latter is at high risk of collapse under substance-over-form challenge.

The practical implication for a founder-CEO thinking about a possible sale in a 12–36-month horizon: begin the stacking-planning conversation with a private-client tax attorney and an estate attorney *now*, not when the LOI is on the desk. Chapter 07's counsel-hand-off discipline develops the mechanics of engaging these advisors.

## Common failure modes — what to watch for

- **Retained-control problem.** A trust that looks non-grantor on paper but is administered as if it were the founder's personal account (founder-controlled trustee, distributions solely at founder's direction, no genuine independent oversight) can be attacked as a grantor trust under §674 or §675, collapsing the stacking design.
- **§643(f) aggregation.** Multiple trusts with substantially the same grantor(s) and substantially the same primary beneficiaries, particularly if implemented in a compressed timeline, can be aggregated. Distinct primary-beneficiary designations and advance timing are the main defences.
- **Compressed timing / step-transaction.** A stacking plan implemented in the weeks before signing an LOI is at high risk of substance-over-form attack. The rebuttal is "the trusts serve genuine estate-planning purposes independent of the transaction," which is much easier to make when the trusts were set up 12–24 months in advance and the transaction was not on the horizon.
- **Failure to allocate GST exemption.** Trusts with grandchild-generation beneficiaries can trigger GST tax on distribution or termination if the GST exemption is not properly allocated. Estate counsel should draft any grandchild-beneficiary trust with careful GST-allocation planning.
- **Missing §1045 election window.** The 60-day reinvestment window is unforgiving. Founders who did not pre-identify replacement QSBS investments before the sale often cannot execute the rollover in the available window.
- **Not consuming lifetime exemption strategically.** Founders whose lifetime exemption is largely intact face the question of *how much* to consume via QSBS gifts vs. reserving for other estate-planning uses. Depending on family circumstances (net worth, other planned gifts, expected future appreciation of retained assets), the answer varies. Estate counsel with a full picture of the family's estate plan is the right decision-maker.
- **Not coordinating with the state-conformity analysis.** A California-resident founder who gifts QSBS to a non-grantor trust in California *and keeps the trust in California* has not moved the trust income outside California's reach. Trust situs planning (Delaware, South Dakota) is a specific design consideration for California and other high-tax-state residents. Trust situs also interacts with the "throwback tax" rules under §643(g) and California's specific residency-of-trust rules under Cal. Rev. & Tax Code §17742.

## Interaction with the M&A structuring choice

Stacking depends on the underlying transaction structure preserving QSBS characteristics through the transaction. From chapter 08 of mod-103, the transaction-structure-to-QSBS-preservation matrix:

- **Stock sale (all-cash)** — QSBS preserved at the shareholder level; §1202 exclusion applies at each shareholder / trust's $10M cap.
- **Stock sale (all-acquirer-stock §368 reorg)** — no current sale; acquirer stock carries QSBS characteristics under §1202(h)(4). The stacking-established caps remain available for a *future* sale of the acquirer stock, subject to the acquirer's qualifying-issuer status at issuance (a nuanced analysis when the acquirer has grown well beyond $50M by the merger date).
- **Stock sale (mixed cash + stock)** — cash portion is a current QSBS sale (excluded up to cap); stock portion carries over.
- **Asset sale of C-corp target** — QSBS not preserved at shareholder level (the corporation sells assets and distributes proceeds; shareholders' stock is not sold in a §1202 sale). Stacking does not rescue this; if the transaction is an asset deal, the QSBS exclusion is generally forfeit for all shareholders regardless of stacking structure.

For a founder with a stacking plan in place, the M&A structure discussion becomes *doubly* important — the stock-vs-asset choice not only affects the founder's personal QSBS but also determines whether all the stacked trusts' caps are usable. This is a specific input to the mod-103 / mod-104 negotiation discipline and one of the reasons founders with stacking plans typically push very hard on stock-form structure.

## Summary

QSBS stacking multiplies the $10M / 10x-basis cap by transferring QSBS — via completed gift under §1202(h)(2) — to separate taxpayers (non-grantor trusts, adult family members), each of whom has their own $10M cap. Non-grantor trusts are the workhorse vehicle, subject to careful drafting to avoid the §§671–679 grantor-trust triggers and the §643(f) multiple-trust aggregation rule. Gift-tax rules (annual exclusion, lifetime unified exemption, GST tax) set the cost of the transfers and require careful coordination with estate planning. Advance timing (12–24 months minimum) is the single largest determinant of defensibility against substance-over-form challenge. The §1045 rollover provides a deferral mechanism for pre-5-year QSBS, preserving the eventual §1202 opportunity for shareholders whose stock does not reach 5 years by the transaction close. Stacking depends on the underlying transaction being stock-form (asset deals forfeit QSBS regardless of stacking). Live stacking plans are authored by a private-client tax attorney and an estate attorney, with independent trust-company trustees for high-value structures. Chapter 3 shifts from M&A cash-out planning to the IPO-founder planning problem, starting with the Rule 10b5-1 trading plan that governs post-IPO founder sales.
