# Consideration-Mix Design Against the Cap-Table Waterfall

## Why this matters

Once the corporate form is chosen (chapter 1), the next design decision is *what the shareholders receive* in exchange for their shares. The consideration mix — cash, acquirer stock, mixed, or structured (contingent value rights, seller-note holdback, rollover equity) — determines three things at once:

- **Cash certainty vs. equity upside for the seller.** Cash at closing is certain; acquirer stock is subject to the acquirer's post-close performance and any stock-lock-up terms; a CVR is contingent on a future milestone; rollover equity is illiquid until the acquirer itself has a liquidity event.
- **Tax treatment of the consideration.** All-cash and most cash-mixed structures are fully taxable at the shareholder level. Sufficient acquirer-stock consideration (with the corporate form structured appropriately — chapter 5) can qualify for §368 tax-free reorg treatment on the stock portion. Rollover equity structured through the acquirer's holding-company entity may also qualify for tax-free rollover treatment under §351 or §368 depending on the specific mechanics.
- **The waterfall payout across the target's cap table.** Different consideration structures interact differently with the target's preference stack, participation rights, and common-holder economics. A structure that looks fair on the headline number can collapse for common holders in the presence of a large preference stack and participating preferred, and can move materially between "acceptable to founders" and "unacceptable to founders" as the mix shifts.

Founders and CFOs sometimes negotiate the headline number as if it were all that mattered and discover at the eleventh hour that the winner-loser distribution across the cap table is what the actual signing decision hinges on. This chapter installs the consideration-mix vocabulary at the depth a CFO / GC / founder-CEO needs, with the waterfall interaction as the framing lens.

> **Ownership boundary reminder.** The cap-table maintenance and waterfall-computation mechanics live in `startup-finance-fundraising-curriculum` mod-104. This chapter *uses* the waterfall as a transaction-input; it does not re-teach how to construct one. When you need to compute the specific dollar payout to Series A preferred under a $400M sale with a $180M preference stack and 1x non-participating preferred with a conversion threshold, that mechanic is imported.

## The consideration-mix palette

### All-cash

Every dollar of consideration is paid in cash at closing (or, more precisely, at the closing minus the escrow / holdback / working-capital-adjustment amounts covered in chapter 4).

- **Cash certainty:** maximum — the shareholders receive cash and it does not depend on the acquirer's post-close performance.
- **Tax treatment:** fully taxable at the shareholder level. Each shareholder recognises capital gain / loss on the sale of their stock (or, in an asset deal, at both the corporate and shareholder levels for a C-corp target). §1202 QSBS treatment on qualifying stock is preserved in a stock-form all-cash sale (chapter 8); a fully taxable transaction does not qualify for §368 tax-free treatment.
- **Waterfall behaviour:** clean and predictable. Each shareholder receives their portion of the waterfall in cash at closing (minus escrow / holdback / adjustments held back per the SPA). No structural complications; the waterfall math computed for the modelled headline number is what the shareholders receive.
- **Buyer-side considerations:** the buyer must fund the full purchase price in cash at closing — from cash on hand, revolver, term debt, or fresh equity issuance. For larger transactions this can require substantial debt financing or a leverage / dilution acceptance from the acquirer's own shareholders. Buyer's cash certainty concerns become the seller's leverage on the escrow / holdback terms (chapter 4).

**When the modal choice is all-cash:** smaller-to-mid market transactions where the buyer can fund from cash on hand; buyout-PE transactions (LBO structure — chapter 1 in mod-102 discusses the sub-type); transactions where the seller's shareholders have no confidence in or interest in the acquirer's stock as post-close currency; distressed transactions where speed and certainty dominate.

### All-stock (acquirer's equity)

Every dollar of consideration is paid in the acquirer's stock at a specified exchange ratio (fixed-ratio vs. fixed-value with a collar — see below).

- **Cash certainty:** none at closing on the stock portion (assuming public acquirer with a liquid market for its stock, the shareholders can sell after any lock-up period expires; assuming private acquirer, the stock is illiquid until the acquirer itself has a liquidity event).
- **Equity upside:** full — the shareholders participate in the acquirer's post-close appreciation.
- **Tax treatment:** if the transaction qualifies as a §368 tax-free reorg (with the stock consideration meeting the continuity-of-interest requirement — chapter 5), the stock portion is tax-deferred; shareholders take a basis in the acquirer stock equal to their basis in the target stock and recognise gain / loss only when they sell the acquirer stock.
- **Fixed-ratio vs. fixed-value.** A **fixed-ratio** exchange (X shares of acquirer per share of target) exposes the seller to acquirer-stock-price volatility between signing and closing. A **fixed-value** exchange (Y dollars of acquirer stock per share of target, computed from a VWAP measurement close to closing) transfers that volatility to the acquirer. **Collars** — floors and ceilings on the exchange ratio or the aggregate value — are the standard mechanism for splitting the volatility risk.
- **Waterfall behaviour:** more complex than all-cash. The stock consideration needs to be distributed to the target's shareholders in proportion to their waterfall entitlements. For preferred shareholders with a preference-stack entitlement, the stock consideration may be allocated as a pro-rata share of the stock, or may be structured with a portion of preferred payout in cash and the remainder in stock, depending on negotiation. This is where waterfall design meets consideration-mix design — the choice is not automatic.
- **Buyer-side considerations:** the buyer is issuing its own stock as currency, which requires internal shareholder approval (NYSE §312.03 / Nasdaq Rule 5635 20% dilution threshold triggers a shareholder vote for a public buyer). The buyer's own dilution and any signalling effects on its stock price of issuing a large stock deal are real; the acquirer's board and CFO analyse this carefully. Registration-rights obligations (if the acquirer is not fully-reporting to allow immediate resale) are typical.

**When the modal choice is all-stock:** larger transactions where the acquirer cannot or does not want to fund with cash; transactions where the acquirer's stock is genuinely attractive as post-close currency to the target's shareholders (highly-valued acquirers with strong stock performance); platform-extending strategic transactions at scale where the strategic thesis benefits from the target's shareholders becoming acquirer shareholders (chapter 1 in mod-102's platform-extending sub-type).

### Mixed cash-and-stock

Some portion cash, some portion acquirer stock. The mix ratio is a specific negotiation point and often falls in the 50-70% cash / 30-50% stock band for mid-market transactions.

- **Cash certainty:** partial on the cash portion.
- **Tax treatment:** if the transaction qualifies as a §368 reorg (specifically §368(a)(2)(D) for a forward-triangular merger, which requires at least 50% stock consideration; or §368(a)(2)(E) for a reverse-triangular merger, which requires at least 80% stock consideration for the tax-free treatment on the stock portion), the stock portion is tax-deferred and the cash portion is "boot" that is currently taxable. The shareholder recognises gain to the extent of the boot (up to the total gain in the transaction). Chapter 5 develops the mechanics.
- **Waterfall behaviour:** requires allocation decisions between the cash and stock components across the shareholder cohorts. A structure where the preferred stack is paid entirely in cash and the common receives the remaining cash and all of the stock produces a very different waterfall outcome than a structure where each shareholder receives a pro-rata slice of the cash-and-stock mix.
- **Founder-personal considerations:** founders (and often senior early employees) may have specific preferences about whether their portion is cash or stock — some want cash certainty for personal liquidity reasons; others want stock for continued upside participation and tax-deferral. These preferences typically get accommodated through a personal-election mechanism inside the merger agreement.

**When the modal choice is mixed:** the most common consideration structure for mid-to-large transactions in the strategic-acquirer channel. Consideration mix is a specific negotiation, and the ratio is a lever the parties push against each other.

### Contingent Value Rights (CVRs)

A CVR is a right issued to the target's shareholders at closing that pays out cash (or, less commonly, stock) upon the achievement of a specified future contingent event. The event can be a milestone (regulatory approval, product launch, revenue threshold), a period of time (aged CVR), or an outcome of litigation / dispute (dispute-outcome CVR).

- **Purpose:** bridge a valuation gap between what the buyer will pay today and what the seller believes the target is worth conditional on a specific future event. Common in biotech / pharma transactions (regulatory-approval CVRs) and in transactions where a specific pending dispute or contract renewal will resolve within a few years post-close.
- **Structure:** CVRs are securities issued to shareholders, subject to SEC registration considerations for public transactions. They can be **tradeable** (registered securities that shareholders can sell) or **non-tradeable** (pass-through only to the initial holders). Tradeable CVRs are more common in public-company M&A; non-tradeable CVRs are more common in private-company M&A because the registration burden is lower.
- **Tax treatment:** complicated. IRS guidance treats the CVR as either a debt instrument (with imputed interest and timing implications), an "open transaction" (where the CVR's basis and gain are unresolved at closing), or a "closed transaction" (where the CVR is valued at closing and the gain recognised then). The specific treatment depends on the CVR's terms and IRS pattern guidance; tax counsel is essential.
- **Waterfall behaviour:** CVRs are typically distributed pro rata across the shareholder cohorts based on their waterfall entitlement to the underlying consideration. If preferred shareholders receive $100M of the cash consideration and common shareholders receive $50M, the CVR would typically be distributed 2:1 in that ratio.
- **Failure modes:** CVRs frequently produce post-close disputes because the buyer, post-close, controls the operations that determine whether the CVR pays out. The buyer has an incentive to *not* trigger the CVR; the seller's shareholders have an incentive to allege that the buyer failed to use commercially reasonable efforts. Well-drafted CVR agreements include efforts covenants, reporting obligations, and dispute-resolution mechanics. Chapter 3 develops the equivalent dispute mechanics for earn-outs (CVR disputes follow the same pattern).

**When the modal choice is a CVR:** transactions with a specific, well-defined future contingency that materially affects the target's value. Biotech / pharma regulatory-approval CVRs are the archetypal case. In venture-backed technology M&A, CVRs are less common than earn-outs (chapter 3) because the specific-contingency structure is a less-natural fit than an ongoing-operating-performance earn-out.

### Seller-note holdback

The buyer issues a promissory note to the seller for a portion of the purchase price, typically maturing 1–5 years post-close, with interest at a market rate (or below-market with imputed interest tax consequences).

- **Purpose:** bridges a financing gap for the buyer (allowing the buyer to fund a portion of the price out of the target's future cash flows rather than at closing), gives the seller a security-holder / creditor position that can be used to enforce post-close obligations, and can substitute for or complement an escrow structure (chapter 4).
- **Structure:** subordinated or senior to other buyer debt depending on negotiation. May include *set-off rights* that allow the buyer to reduce the note obligation by indemnification claims (a mechanism that partially substitutes for an escrow).
- **Tax treatment:** installment sale under §453, with gain recognition spread over the note's principal repayment schedule (assuming the seller elects installment reporting and the transaction otherwise qualifies). Interest is separately taxable as ordinary income.
- **Credit risk:** the seller becomes a creditor of the buyer for the note principal. If the buyer's post-close credit deteriorates, the seller has recourse only to whatever collateral (if any) the note is secured by. Founder-CEOs whose primary personal liquidity comes from the sale should evaluate this credit risk explicitly.
- **Waterfall behaviour:** the seller note is typically issued to the shareholders in proportion to their waterfall entitlement to the deferred portion of the purchase price. Preferred shareholders often insist on their preference being paid in cash at closing rather than partially in a seller note; the seller note is more often used to defer a portion of the common-holder consideration.

**When the modal choice is a seller-note holdback:** lower-middle-market buyout-PE transactions where the buyer's leverage stack cannot accommodate the full purchase price without seller financing; strategic transactions where the buyer wants to align long-term seller incentives without a full earn-out structure; carve-outs where a portion of the price depends on post-close operational performance.

### Rollover equity

Some portion of the target's shareholders — typically the founders, senior operating team, and possibly key employees — take a portion of their consideration as equity in the acquirer's (or the acquiring entity's) holding company rather than as cash or acquirer public stock.

- **Purpose:** align long-term operating incentives with the acquirer's success. Common in buyout-PE transactions where the PE fund wants the management team to have a meaningful equity stake in the acquired-plus-existing platform going forward. Common in strategic transactions where the founder-CEO is expected to run the acquired business for 2–4 years post-close and the acquirer wants the founder to have equity in the *combined* entity's success.
- **Structure:** typically issued through a holding-company vehicle (a NewCo, often an LLC or corporation) that sits above the target's operating entity in the post-close structure. The rollover shareholders receive equity in the holding company; the buyer's own equity check funds the remainder. Rollover typically ranges from 5% to 30% of the equity check for a buyout-PE transaction, higher for growth-equity transactions.
- **Tax treatment:** if structured properly under §351 (contribution to a controlled corporation) or §721 (contribution to a partnership), the rollover portion can be tax-deferred — the rollover shareholders recognise no gain on the rolled portion until they exit the acquirer. This is the *tax-free rollover* structure. Getting the mechanics right requires tax counsel — the *investment-company* rules under §351(e) and the *disguised-sale* rules under §707(a)(2)(B) can trip up poorly-designed rollovers.
- **Waterfall behaviour:** rollover is typically negotiated as a specific personal election for the founders and named senior team members. The rollover portion is *not* distributed across the full cap table; it is a targeted mechanism for aligning the key operating team.
- **Governance implications:** rollover equity typically comes with a shareholders' agreement in the holding company that includes vesting, forfeiture-on-departure, drag-along rights that favour the majority owner (the PE fund or strategic acquirer), and tag-along rights that protect the rollover holders on a subsequent sale. The rollover shareholders are minority owners in the post-close structure and their downside protections are limited relative to a founder's own-company position.

**When the modal choice includes rollover equity:** buyout-PE transactions almost always; growth-equity transactions typically; strategic transactions where a specific business-unit structure post-close creates a natural rollover vehicle. Rollover is uncommon in traditional cash-or-stock strategic acquisitions where the acquirer's own public stock serves the alignment function.

## Waterfall interaction — where the design becomes concrete

A consideration structure has to be evaluated against the *specific* cap table of the target. The following patterns recur:

### The preference-stack overhang problem

For a target with a large preference stack relative to the sale price, the common-holder economics can collapse under structures that look fine on the headline number. A worked example:

*Target: $180M preference stack (1x non-participating preferred with a $180M liquidation preference, or the shareholder can convert to common and take a pro-rata share of the residual); 40% preferred / 60% common on an as-converted basis. Sale headline: $400M all-cash.*

- **If preferred takes the preference:** preferred receives $180M; common receives the remaining $220M pro rata on the common-only base. Founder / employee common on their common-only share.
- **If preferred converts to common:** preferred receives 40% × $400M = $160M; common receives 60% × $400M = $240M. Preferred is worse off ($160M vs. $180M), so they take the preference.

Now consider two consideration structures at the *same* headline:

**Structure A — All-cash $400M.**
- Preferred takes preference: $180M cash.
- Common receives: $220M cash pro rata on common-only base.

**Structure B — $220M cash + $180M CVR contingent on a specific product-milestone achievement over 3 years.**
- If preferred takes the preference in cash at closing, the preferred is fully paid. Common receives $40M cash + $180M CVR pro rata on common-only base.
- If the CVR fails to pay out (buyer alleges milestone missed), the common receives $40M in this structure vs. $220M in Structure A.

Structure B produces a *very* different outcome for common holders than Structure A, at the same headline. The waterfall is where the consideration structure becomes concrete for the individual founder / employee.

### The participating-preferred trap

For a target where the preferred stock is *participating* (takes its preference and *also* participates pro rata in the residual), the common-holder economics are further compressed.

*Target: same $180M preference stack, but participating preferred; $400M sale.*

- Preferred takes $180M preference, then participates in the $220M residual: $180M + 40% × $220M = $180M + $88M = $268M.
- Common receives 60% × $220M = $132M.

Compared to the non-participating example above, common receives $132M vs. $220M — the participating preferred captures $88M of what would otherwise have gone to common. This is the "participating preferred trap" and it is one of the specific patterns the mod-101 chapter 5 optionality-preserving-operating-decisions audit flags. In consideration-mix design, participating preferred materially constrains what a founder-CEO will accept as consideration structure — the founder wants any deferred / contingent consideration structured to *not* be captured by the participating preferred's participation rights.

### The management-carve-out mechanism

When the sale price would produce a poor common-holder outcome (either due to a large preference stack, a participating-preferred trap, or a below-preference-stack aqui-hire), the parties sometimes negotiate a **management-carve-out** or **management-incentive-plan (MIP)** that reserves a specific portion of the consideration for the founding / management team, funded by preferred shareholders waiving a portion of their preference.

- **Structure:** typically 5–15% of the total consideration is carved out into a management pool, funded by the preferred stack agreeing to a haircut on their preference. The pool is distributed to the management team (founders, executive team, sometimes broader employee base) under an agreed distribution list, subject to §280G analysis and §409A timing (chapters 6 and 7).
- **Preferred motivation:** the preferred's rational preference is "get 100% of my preference." The reason preferred sometimes agree to a carve-out is that *without it*, the founders and key employees may refuse to sign the deal (the founder cannot vote yes on a transaction where they get zero and the preferred gets 100%; drag-along mechanics have limits in practice even when they are legally enforceable). The carve-out is the price of getting the founders and key employees to support the transaction.
- **§280G exposure:** carve-outs paid to executives and other disqualified individuals are typically parachute payments for §280G purposes. Chapter 6 develops the mechanics; the analysis has to be run and the mitigation has to be designed *before* the carve-out is agreed, or the carve-out's economics collapse under the 20% excise tax and lost corporate deduction.

The management-carve-out is the specific mechanism by which aqui-hires (mod-102 chapter 2 sub-type 1) with headline numbers below the preference stack still produce economics for the founders and key employees. It is also relevant in modest tuck-ins where the preferred stack is thick and the acquirer's headline number produces poor common outcomes.

## The design decision framework

Given the palette and the waterfall interaction, the consideration-mix decision resolves through a sequence:

1. **Fix the corporate form** (chapter 1). This determines what consideration structures are available (all-stock only works if the form supports §368 tax-free treatment; §338(h)(10) requires stock-form only; etc.).
2. **Fix the buyer's funding capacity and preferences.** What can the buyer pay in cash? What is the buyer's cost of capital on the marginal cash dollar (relative to using stock)? What is the buyer's stock currency worth today and does its issuance require internal buyer-shareholder approval?
3. **Fix the seller's cash-certainty needs and tax preferences.** Do the founders need cash for personal liquidity (paying off a bridge loan, buying a house, meeting a personal tax obligation)? Do the founders and early employees have material §1202 QSBS that would benefit from cash consideration (the QSBS exclusion applies whether the consideration is cash or stock, but rolls into different mechanics)? Does the preferred stack have specific preferences?
4. **Model the waterfall under the candidate structures.** For each candidate consideration structure, run the waterfall under: (a) the base-case pricing, (b) a low-case pricing (say 20% below base), (c) a high-case pricing, and (d) a full-earn-out-failure or full-CVR-failure scenario if applicable. The winner-loser distribution across founders / employees / preferred shareholders is what the actual decision hinges on.
5. **Test the structure against §280G, §409A, §1202, and §368.** Each of these tax provisions constrains what is available. Chapters 5–8 develop the specific mechanics; a candidate consideration structure that fails the tax constraints has to be modified or rejected.
6. **Test the structure against buyer-side constraints.** R&W insurance underwriting on the specific consideration structure (some structures may not be insurable), the buyer's leverage covenants if the transaction is financed, and the buyer's own corporate approvals (NYSE / Nasdaq 20% dilution rule for public buyers issuing stock).
7. **Fix the CVR / earn-out / rollover / seller-note terms** (chapters 3 and 4). Structured consideration requires detailed drafting.
8. **Cross-check against the closing conditions and the deal timeline.** A CVR contingent on a milestone that may take 5 years to resolve produces a very different post-close operating relationship than one that resolves in 12 months.

The framework is iterative — a consideration structure that works in step 4 may fail in step 5 and require re-design; the iteration continues until a candidate survives all the constraints.

## Summary

Consideration mix is the second design layer after corporate form. The palette — all-cash, all-stock, mixed, CVRs, seller notes, rollover equity — offers a range of trade-offs across cash certainty, equity upside, tax treatment, and waterfall behaviour. The specific structure has to be evaluated against the target's cap-table waterfall, because a structure that looks fair on the headline number can collapse for common holders in the presence of a large preference stack, participating preferred, or below-preference-stack pricing. The management-carve-out mechanism is the specific tool for restoring common-holder economics when the waterfall would otherwise produce a founder / employee refusal. Structured consideration (earn-outs, CVRs, seller notes, rollover) is where post-close operating alignment gets designed, and its terms — payout curves, dispute mechanics, control obligations — are what chapters 3 and 4 develop.
