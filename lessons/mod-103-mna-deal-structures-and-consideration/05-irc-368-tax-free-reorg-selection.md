# IRC §368 Tax-Free Reorg Selection and §338(h)(10)

## Why this matters

The corporate form choice from chapter 1 and the consideration-mix design from chapter 2 both interact with a body of tax law — IRC §368 (tax-free reorganisations), §338(h)(10) (elective asset-deal treatment for stock deals), and the surrounding continuity-of-interest and continuity-of-business-enterprise doctrines — that determines whether a given transaction is *taxable* to the target's shareholders or *tax-deferred* on some portion of the consideration. For founders and early employees with substantial gain on their stock, the difference between a taxable transaction and a tax-deferred reorg on the stock portion is measured in millions of dollars of personal tax. For the buyer's tax director, the choice determines whether the buyer inherits the target's tax basis in its assets (stock deal, no step-up) or takes a step-up to purchase price (asset deal or §338(h)(10) stock deal), which drives the deductibility of goodwill amortisation under §197 for the next 15 years.

This chapter installs the §368 reorg-type taxonomy, the general requirements that apply across all reorg types (continuity of interest and continuity of business enterprise), the §338(h)(10) election mechanics, and the decision framework for matching a specific target profile (entity type, shareholder composition, consideration mix) to a specific structure. The §368 mechanics are conceptually straightforward but drafted with substantial specificity in the Treasury Regulations; the practical craft is choosing the right reorg type and ensuring the drafting satisfies the technical requirements without inadvertently disqualifying the transaction.

> **This is education, not tax advice.** A live transaction hands off to qualified tax counsel with jurisdiction-specific expertise. The chapter installs the vocabulary and decision framework so that the CFO / GC / founder-CEO can meaningfully engage with the tax counsel; it does not substitute for that engagement.

## The §368 reorg types

IRC §368(a) defines seven statutory reorganisation types (A through G). For M&A involving a corporate target, four are relevant: A, B, C, and F. Each has distinct structural and consideration-mix requirements.

### §368(a)(1)(A) — statutory merger or consolidation ("A reorg")

A direct statutory merger of two corporations under state merger law (chapter 1, form 5) or the parallel consolidation. The A reorg is the most flexible of the reorg types — it does not impose a specific stock-consideration percentage threshold; the only consideration constraint is the general **continuity-of-interest** requirement (discussed below).

- **Structural requirement:** the transaction must be a statutory merger or consolidation under state (or foreign, in certain cases) corporate law. Contractual arrangements that mimic a merger without being one under corporate law do not qualify.
- **Consideration flexibility:** any consideration mix that satisfies the continuity-of-interest requirement (typically 40%+ stock consideration under current IRS practice). Cash consideration ("boot") above the qualifying-stock threshold is currently taxable to the shareholders receiving it.
- **Common variants:** §368(a)(2)(D) forward-triangular merger (target merges into acquiring subsidiary; requires at least 50% stock consideration for tax-free treatment) and §368(a)(2)(E) reverse-triangular merger (subsidiary merges into target with target surviving; requires at least 80% stock consideration for tax-free treatment).

The A reorg (and its triangular variants) is the modal §368 structure for venture-backed private-company M&A.

### §368(a)(1)(B) — stock-for-stock ("B reorg")

An acquisition by one corporation of the stock of another, solely in exchange for the acquirer's own voting stock (or the voting stock of its parent), where the acquirer ends up in control of the target (defined as 80% ownership under §368(c)).

- **Structural requirement:** the target continues to exist as a subsidiary of the acquirer.
- **Consideration constraint:** the *only* consideration permitted is voting stock of the acquirer (or its parent). Any cash consideration disqualifies the transaction as a B reorg — "solely for voting stock" is strictly enforced.
- **Continuity of interest:** the 100%-stock consideration structure inherently satisfies continuity of interest.

The B reorg is a relatively rare structure because the "solely for voting stock" constraint is unforgiving — even a small amount of cash consideration (for example, cash paid for fractional shares) can disqualify the entire transaction from B reorg treatment. In practice, B reorgs are used mainly when the deal is intentionally all-stock and the parties want the strict-compliance benefits of the B reorg's simplicity.

### §368(a)(1)(C) — stock-for-assets ("C reorg")

An acquisition by one corporation of substantially all of the assets of another in exchange for voting stock of the acquirer (or its parent). The target then typically liquidates and distributes the acquirer's stock to its shareholders.

- **Structural requirement:** substantially all of the target's assets transfer (the "substantially all" test is a specific technical requirement, generally interpreted as at least 90% of net assets and 70% of gross assets under the IRS's advance-ruling guidelines).
- **Consideration constraint:** primarily voting stock of the acquirer, with limited "boot" (cash or other property) permitted — the "solely for voting stock" requirement is relaxed for the C reorg to allow assumption of liabilities and limited additional consideration under specific rules.

The C reorg is less common than the A reorg for private-company M&A because the "substantially all of the assets" transfer mechanic imposes procedural complexity that the merger-statute alternative (A reorg) avoids.

### §368(a)(1)(F) — mere change of form ("F reorg")

A "mere change in identity, form, or place of organization" of a single corporation. Not a two-party acquisition; the F reorg is a single-corporation restructuring — reincorporating in a different state, changing corporate name, converting from one entity form to another.

- **The Delaware LLC drop-down pattern.** Increasingly common in venture-backed startup exits: pre-close, the target reorganises through an F reorg into a Delaware LLC structure, dropping the operating business into a subsidiary. This can facilitate certain transaction structures (particularly enabling S-corp targets to accept a §338(h)(10) election-like structure) and can position the target's ownership for tax-optimised rollover into the acquirer's holding company.

The F reorg is not itself an M&A structure — it is a *pre-transaction* restructuring that positions the target for a subsequent M&A transaction. It is included in the taxonomy because it appears in venture-backed startup transactions with material frequency, and because misunderstanding it causes founders to be surprised by pre-close corporate restructurings that their tax counsel recommends.

## Continuity of interest — the general constraint

The **continuity-of-interest** ("COI") doctrine, developed through case law and codified in the Treasury Regulations at §1.368-1, requires that a substantial portion of the transaction's consideration take the form of an *equity* interest in the acquirer. The COI is what distinguishes a tax-free reorganisation (which shifts the underlying business from one corporate form to another, preserving shareholder equity participation) from a taxable sale (which converts equity participation into cash or non-equity consideration).

- **Threshold.** The Treasury Regulations do not specify a fixed percentage. IRS advance-ruling practice (Rev. Proc. 77-37, later modified) historically applied a 50% stock-consideration threshold for private-letter-ruling purposes. Case law (including *Nelson v. Helvering*) has upheld reorganisations at lower stock percentages — the 38.4% stock consideration in *Nelson* was sufficient. Current practitioner practice generally uses a **40% stock consideration** threshold as the safe-harbour rule of thumb for A reorgs, though the specific facts and the acquirer's stock's suitability as equity currency matter.
- **Measurement.** COI is measured based on the *value* of stock consideration relative to total consideration, using the signing-date value of the acquirer's stock (or, per certain regulatory provisions, the closing-date value if signing-to-closing volatility is material).
- **Special rules.** Certain post-transaction transactions (a sale of the acquirer stock by former target shareholders shortly after closing) can disqualify COI if pre-arranged; the regulations at §1.368-1(e)(6) address the "pre-arranged" analysis in specific detail.

For the reverse-triangular merger under §368(a)(2)(E), the COI threshold is higher (80% stock consideration) — a statutory requirement specific to that variant, not just the general COI doctrine.

## Continuity of business enterprise

The **continuity-of-business-enterprise** ("COBE") doctrine, codified at §1.368-1(d), requires that the acquirer either (1) continue the target's *historic business* or (2) use a *significant portion* of the target's historic business assets in a business. COBE is what prevents a §368 reorganisation from being used to acquire a target and immediately dispose of its business (an "acquisition-and-liquidation" that would look economically like a sale but claim reorg treatment).

- **Historic business.** The target's business must have been the actual business of the target for a reasonable period pre-close (not one that was set up shortly before the transaction to satisfy COBE).
- **Significant portion of assets.** If the acquirer does not continue the target's historic business, the acquirer must use a significant portion of the target's historic assets in *some* business — the assets cannot simply be sold or abandoned.

COBE rarely constrains venture-backed M&A structures because the acquirer typically genuinely does intend to continue the target's business (or integrate it into the acquirer's own business, which satisfies COBE). It can matter in aqui-hire transactions where the acquirer plans to shelve the product post-close — the acquirer's use of the acquired *team* on other projects does not obviously satisfy COBE with respect to the target's *business*, and tax counsel needs to work through the specific facts.

## The §338(h)(10) election

The §338(h)(10) election is a joint election by the buyer and seller that treats a **stock acquisition** as an **asset acquisition for tax purposes**, while retaining the corporate-law-form of a stock deal.

- **Availability.** §338(h)(10) is available for stock acquisitions of:
  - **S-corporation targets** where all shareholders consent to the election.
  - **80%-or-more-owned corporate subsidiaries** of a consolidated group where the parent consents.
- **Not available for standalone C-corp targets** (which is why §338(h)(10) is not directly available to typical venture-backed C-corp startup targets — but see the F-reorg drop-down pattern below).
- **Mechanics.** With the election, the seller is treated as having sold the target's *assets* (recognising gain on the deemed asset sale, with the character and timing of an asset sale) rather than having sold the target's *stock*. The buyer takes a stepped-up basis in the target's assets (the *inside* basis), enabling depreciation and amortisation deductions against the stepped-up basis over the applicable §197 amortisation period (typically 15 years for acquired goodwill).
- **Timing.** The election must be filed by the 15th day of the 9th month after the closing of the qualified stock purchase (IRS Form 8023).
- **Gross-up.** Because the election generally increases the seller's tax liability relative to a pure stock deal (the seller pays asset-sale-level tax at the corporate level, not just capital-gains tax on the stock), the negotiation typically involves a *gross-up* — the buyer pays additional purchase price to compensate the seller for the incremental tax cost. The gross-up amount is computed at the specific tax rates applicable to the seller and often adds 5–15% to the effective purchase price.

**The Delaware LLC drop-down / F-reorg pattern for C-corp targets.** For a venture-backed C-corp target where §338(h)(10) is not directly available, tax counsel sometimes recommends a pre-closing F-reorg that converts the C-corp into a single-member LLC (disregarded for tax purposes) held by a new C-corp parent. The subsequent stock sale of the C-corp parent produces the tax result of a stock sale to the shareholders while the buyer effectively acquires the LLC's assets (through the disregarded entity), enabling a step-up in asset basis. The mechanics are complex and require specific tax expertise; not every C-corp is eligible or advised to pursue this pattern.

**§336(e) election.** A related election under §336(e) provides similar step-up-with-election treatment for certain sales that do not qualify for §338(h)(10) (specifically, sales to buyers who are not corporations or where the target is not an S-corp / corporate subsidiary). Available in a narrower set of circumstances; conceptually similar to §338(h)(10) in effect.

## Taxable stock deal vs. taxable asset deal

For transactions that do not qualify (or the parties choose not to qualify) for §368 or §338(h)(10) treatment, the transaction is fully taxable:

- **Taxable stock deal.** Shareholders recognise gain / loss on the sale of their stock. Character is capital gain / loss (long-term if held > 1 year), subject to §1202 QSBS exclusion for qualifying stock (chapter 8). Buyer takes stock at cost basis; no inside-asset step-up.
- **Taxable asset deal.** For a C-corp target: target recognises gain / loss on asset sale at the corporate level (paying corporate-level tax), then shareholders recognise gain / loss on the distribution of after-tax proceeds (paying dividend / capital-gains tax). Two-level tax problem. For an S-corp or partnership: gain / loss passes through to owners (single-level tax). Buyer takes stepped-up basis in assets.

The two-level-tax problem is why C-corp asset deals are uncommon for tax-driven transactions — the effective tax rate on the shareholders can approach 50%+ (corporate tax plus shareholder-level tax) versus the ~20% capital-gains rate on a stock sale. Buyer's step-up motivation has to overcome this seller-side tax cost, which typically requires a substantial gross-up.

## The structure-selection decision framework

For a specific transaction, the tax structure decision resolves through a matching of the target's entity type, shareholder composition, and consideration mix to the available structures:

| Target profile | Consideration mix | Likely modal structure |
|---|---|---|
| C-corp, venture-backed, founders with material §1202 QSBS | 50–100% acquirer stock | Reverse-triangular merger as §368(a)(2)(E) A reorg — tax-free on stock portion; QSBS preserved (chapter 8) |
| C-corp, venture-backed, founders with material §1202 QSBS | All-cash | Reverse-triangular merger, fully taxable stock sale; QSBS exclusion applies on qualifying stock |
| C-corp, venture-backed, mixed consideration below §368 thresholds | Mixed cash and stock, <80% stock | Forward-triangular merger as §368(a)(2)(D) if stock ≥50%; else fully taxable |
| C-corp, buyer requires step-up | Any | Consider F-reorg drop-down to enable §338(h)(10)-like treatment; alternatively, taxable asset deal with gross-up |
| S-corp | Any | Stock deal with §338(h)(10) election — buyer step-up, seller pays asset-sale-level tax with gross-up |
| LLC (partnership-taxed) | Any | Asset deal / interest-purchase depending on state law; single-level tax passes through to members |
| Consolidated-group subsidiary | Any | Stock deal with §338(h)(10) election available with parent consent |
| Foreign target | Any | Chapter 9's foreign-antitrust framework and the §7874 inversion rules constrain structure |

The table is a starting reference. The specific deal's structure depends on the fact pattern within the row — a C-corp with heavy §1202 QSBS founders and a buyer that will not accept a stock-heavy structure produces a specific negotiation.

## Practitioner notes and common pitfalls

- **The COI trap for stock-heavy deals.** If the parties intend §368 treatment but the mix ends up below the COI threshold (through a late reduction in stock consideration, or through post-signing acquirer-stock volatility), the reorg treatment can be lost. Well-drafted merger agreements include an *escape valve* — a mechanism to reinstate a higher stock ratio if the COI test would otherwise fail, or to convert to a taxable structure with an adjusted purchase price if the reorg fails.
- **The reverse-triangular 80% threshold trap.** A reverse-triangular merger that is intended as §368(a)(2)(E) must have at least 80% qualifying stock consideration. A last-minute negotiation that shifts the mix to 75% stock / 25% cash disqualifies the entire reverse-triangular merger from reorg treatment — the deal is now fully taxable. Watch this closely.
- **§338(h)(10) gross-up math.** The gross-up to compensate the seller for the incremental tax is not the raw tax difference; it is the tax difference *itself grossed up for the incremental tax on the gross-up*, computed iteratively. The formula is standard tax-counsel math but requires careful modelling — an under-computed gross-up produces a seller-side loss and a signing-time dispute.
- **The F-reorg drop-down complexity.** Pre-close F-reorg restructurings can enable favorable tax structures, but the mechanics require IRS-guidance-current expertise. Founders sometimes discover the F-reorg pattern at LOI signing and are surprised by the pre-close restructuring their tax counsel is recommending; understanding the pattern in advance reduces friction.
- **§7874 inversion trap.** For US targets being acquired by foreign acquirers, §7874 imposes limits on the acquirer's ability to establish a foreign tax residence through the acquisition — the acquirer's foreign entity may be re-characterised as a US corporation for tax purposes if the transaction fails specific ownership-and-substance tests. Not typically an issue for pure strategic M&A but can arise in specific fact patterns.
- **State tax considerations.** Federal §368 treatment does not necessarily produce state-tax parallel treatment; some states impose their own tax at the entity or shareholder level regardless of federal reorg status. The state-tax analysis is a separate workstream and should not be assumed to follow federal.
- **Foreign shareholder complications.** Non-US shareholders receiving US acquirer stock in a §368 reorg may face specific US withholding, FIRPTA, or PFIC / CFC complications depending on the specific fact pattern. Cash consideration to non-US shareholders may be simpler to administer.

## Interaction with the other tax provisions

The §368 / §338(h)(10) structure interacts with the other tax provisions this module addresses:

- **§280G golden parachute (chapter 6).** The transaction's structure determines whether a change-of-control event triggers §280G analysis. A §368 reorg with continuing employment (rollover equity, management continuity) can affect the parachute-payment calculation and the disqualified-individual analysis.
- **§409A payment timing (chapter 7).** Earn-outs and transaction bonuses must comply with §409A regardless of the transaction's §368 treatment. The interaction affects how deferred consideration (earn-outs, seller notes) is structured for §409A compliance.
- **§1202 QSBS (chapter 8).** The transaction structure determines whether §1202 treatment is preserved. A stock-form transaction (whether taxable or §368 tax-free on the stock portion) preserves QSBS for qualifying stock; an asset deal breaks it. This is the single largest tax-structure consideration for founder-and-early-employee-heavy C-corp targets.
- **§453 installment sale.** Deferred consideration (seller notes, earn-outs) may qualify for §453 installment sale treatment, spreading the seller's gain over the payment schedule. Interaction with §368 treatment is limited — §453 typically applies only to the taxable portion of the transaction.

## Summary

The §368 reorg framework, together with the §338(h)(10) election, provides the tax-structuring toolkit for M&A transactions. The A reorg (including its triangular variants) is the modal §368 structure for venture-backed M&A. The B and C reorgs are less flexible and less commonly used. The F reorg enables pre-close restructurings that position the target for favorable transaction structures. The §338(h)(10) election converts a stock deal into an asset deal for tax purposes for S-corp and consolidated-subsidiary targets, giving the buyer step-up at the cost of a seller-side gross-up. Continuity of interest and continuity of business enterprise are general constraints that apply across the reorg types. For a specific transaction, the structure-selection decision matches the target's entity type, shareholder composition, and consideration mix to the available structures; the fact-pattern specifics within each row of the decision table drive the specific negotiation. Live transactions hand off to qualified tax counsel; this chapter installs the vocabulary and framework so that the founder-CEO / CFO / GC can meaningfully participate in that engagement.
