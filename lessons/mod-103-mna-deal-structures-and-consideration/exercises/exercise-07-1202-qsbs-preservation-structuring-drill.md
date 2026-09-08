# exercise-07: §1202 QSBS Preservation Structuring Drill

**Estimated effort:** 3 hours

## Objective

For a founder-and-early-employee cohort with specific §1202 QSBS positions, structure the transaction to preserve QSBS treatment where possible and identify where it must be forfeit. For each shareholder, compute the QSBS-driven personal-tax outcome under three transaction structures (all-cash stock deal, all-stock §368 reorg, and asset deal) and identify the structural-preference implications. Then design the deal-structuring criteria that best preserves QSBS at the specific-shareholder level. By the end you should be able to advise founders on their QSBS-preservation options, quantify what an asset-deal alternative would cost them, and present a QSBS-preservation-informed structuring recommendation to the board.

## Background

This exercise covers material from:

- [Chapter 8 — IRC §1202 QSBS Preservation Through the Transaction](../08-irc-1202-qsbs-preservation.md)

Chapter 1 (form choice) is the primary framework driver: stock-form deals preserve QSBS; asset deals forfeit it. Chapter 5 (§368 reorg) determines the specific tax-deferral mechanics when the consideration includes acquirer stock. Chapter 2 (consideration mix) provides the transaction context.

> **Education, not tax advice.** §1202 has technical requirements and state-conformity variations. Live analysis requires qualified tax counsel and, for individual planning, personal tax advisors. This exercise builds the framework — a live analysis is done with counsel.

## Prerequisites

- You have read chapter 8 in full.
- Basic familiarity with §1202 qualifying-stock requirements.
- Optional: Cooley / Fenwick / WSGR / Foundry Group practitioner memos on QSBS in M&A structuring.

## The fact pattern

**Target:** Delaware C-corp, 8 years old at the transaction date. Founded as a C-corp; at incorporation, the aggregate gross assets were $2M (well below the $50M cap for §1202 qualifying). The corporation's business is a vertical B2B SaaS platform — not in any of the §1202-excluded categories.

**Transaction:** $520M sale to a publicly-traded strategic acquirer. Various structures under consideration.

**Founder-and-early-employee cohort:**

| Person | Role | Stock cohort | Original acquisition date | Original acquisition method | Adjusted basis | Fair value at transaction | §1202-eligible? |
|---|---|---|---|---|---|---|---|
| A | Co-founder (CEO) | Founder common | Founding (year 0) | Original issuance for services | $500 | $34M | Yes, holding >5 years |
| B | Co-founder (CTO) | Founder common | Founding (year 0) | Original issuance for services | $500 | $34M | Yes, holding >5 years |
| C | Co-founder (Chief Product) | Founder common | Founding (year 0) | Original issuance for services | $500 | $26M | Yes, holding >5 years |
| D | Co-founder (Chief Revenue) | Founder common | Founding (year 0) | Original issuance for services | $500 | $21M | Yes, holding >5 years |
| E | Early employee (VP Eng) | Exercised options, first year | Year 1 exercise | Option exercise, original grant $1 strike | $10,000 | $9M | Yes, holding >5 years (option exercise triggers holding period from exercise date) |
| F | Early employee (VP Sales) | Exercised options, second year | Year 2 exercise | Option exercise, $2 strike | $18,000 | $6M | Yes, holding >5 years |
| G | Year-3 employee (early PM) | Exercised at grant, year 3 | Year 3 exercise | Option exercise, $5 strike | $45,000 | $3.5M | Yes, holding >5 years |
| H | Year-5 employee (Head of Engineering) | Exercised options, year 5 | Year 5 exercise | Option exercise, $8 strike | $80,000 | $2.8M | **Approximately 3 years holding** — NOT eligible for §1202 exclusion (< 5-year holding); §1045 rollover candidate |
| I | Year-6 employee (Head of Marketing) | Vested but unexercised options | To be exercised at closing | Cashless exercise at closing | Minimal | $1.5M | **Not §1202-eligible** — option exercise at closing means holding period starts at exercise; no 5-year period |
| J | Year-7 employee (Head of People) | Vested but unexercised options | To be exercised at closing | Cashless exercise at closing | Minimal | $0.9M | Not §1202-eligible |

**State-tax note:** Assume all executives are California residents. California does not conform to §1202 — the state imposes tax on the full gain regardless of federal §1202 treatment.

## Tasks

### 1. Per-shareholder QSBS analysis under three transaction structures

For each of the 10 individuals, compute the after-tax outcome under three transaction structures. Use these tax rates:

- **§1202 exclusion:** greater of $10M per shareholder per issuer OR 10x adjusted basis. For all founders and early employees with minimal basis, this effectively caps at $10M.
- **Long-term capital gains (non-QSBS or above-exclusion):** 23.8% federal (20% + 3.8% NIIT).
- **Ordinary income:** 37% federal + 3.8% NIIT = 40.8% marginal.
- **California state tax:** 13.3% top marginal rate; California does not conform to §1202 (imposes state tax on full gain).
- **Corporate tax (asset deal C-corp):** 21% federal + 8.84% California = ~29% blended; assume double-taxation for asset-deal-to-C-corp structure.

**Structure I: All-cash stock-form sale.**
$520M cash. Each shareholder receives their pro-rata share of the waterfall in cash. Assume simplification: waterfall gives each individual their fair-value amount from the table (a real waterfall would depend on the preference stack; ignore for this exercise's simplification).

**Structure II: All-stock §368(a)(2)(E) reverse-triangular merger.**
$520M in acquirer stock. Each shareholder receives their pro-rata share in acquirer stock, tax-deferred under §368. Assume qualifying reorg (>80% stock, meets continuity-of-interest).

**Structure III: Taxable asset deal.**
$520M sale of target's assets. Target-level corporate tax at ~29% blended (federal + California). After-tax net distributable to shareholders after two-level tax.

For each individual, compute:

| Structure | Gross consideration | Federal tax | California state tax | Corporate-level tax reduction | After-tax value |
|---|---|---|---|---|---|
| Structure I | | | | | |
| Structure II | | | | | |
| Structure III | | | | | |

For Structure II, note that the tax is *deferred* rather than eliminated; the shareholder receives acquirer stock and defers gain recognition. When the shareholder later sells acquirer stock, the QSBS characteristics *may* carry over under §1202(h) (chapter 8 discusses the technical requirements). For simplification, assume the acquirer stock retains QSBS characteristics and the shareholder can claim §1202 on future sale (if holding period tacks).

For Structure III, distinguish:
- **Federal treatment of the corporate-level tax.** Target-level 21% federal + California-level 8.84% = ~29% at the corporate level. Each dollar of pre-tax gain is reduced to $0.71 at the shareholder distribution.
- **Shareholder-level tax on the distribution.** The distribution is taxed as capital gains under §336 liquidating distribution (assuming liquidation) at ~23.8% + California 13.3%. Founders lose the §1202 exclusion entirely.

### 2. Aggregate impact table

Summarise the aggregate after-tax outcomes:

| Individual | Structure I after-tax | Structure II after-tax (deferred; equivalent) | Structure III after-tax | Structure I vs. III delta (in QSBS-forfeit cost) |
|---|---|---|---|---|
| A | | | | |
| ... | | | | |
| **Total** | | | | |

The Structure I vs. III delta is the aggregate QSBS-forfeit cost to founders and early employees of an asset deal.

### 3. §1045 rollover for pre-5-year holders

For Individuals H, I, J (whose stock is not yet §1202-eligible because of holding period), analyse:

- **Is §1045 rollover applicable?** §1045 requires holding for at least 6 months but less than 5 years, and reinvestment in replacement QSBS within 60 days.
- **Operational feasibility.** Is the individual likely to (a) receive their sale proceeds and (b) reinvest in a new qualifying startup within 60 days? What are the practical constraints?
- **Cost / benefit.** If §1045 is used, gain is deferred; the individual carries a lower basis in the replacement stock. When the replacement stock is later sold, if the replacement stock qualifies as §1202 (5-year tacking under §1045), the deferred gain plus any new gain may be §1202-eligible.
- **Individual planning conversation.** For each of Individuals H, I, J, what would you tell them at the transaction announcement?

Write a ½-page §1045-rollover analysis addressing each of Individuals H, I, J.

### 4. Structure-preference recommendation

Based on the analysis, produce a per-cohort structure-preference recommendation:

- **Founders (A-D).** Structure I is preferred (all-cash preserves QSBS on the qualifying portion; cash certainty). Structure II is acceptable and offers §1202(h) carryover for the acquirer stock, with the trade-off of illiquidity (until acquirer stock is liquid) and acquirer-specific risk. Structure III is worst — QSBS forfeit + two-level tax.
- **Early employees with QSBS (E, F, G).** Same preference ordering, but their absolute exposure is smaller.
- **Non-QSBS-eligible (H, I, J).** §1202 does not apply; the QSBS analysis is not driving their preference. Their preference is likely driven by other factors (cash certainty, retention economics, personal liquidity needs).
- **Aggregate cohort recommendation.** What structure recommendation would you give the board, weighted by cohort economics?

### 5. Interaction with buyer preferences

The buyer's tax director wants a step-up in asset basis for §197 amortization on goodwill (chapter 5). This creates the buyer-vs-seller tension of chapter 1:

- **In Structure I** (stock deal, cash), the buyer gets no step-up (unless §338(h)(10) applies, which for a C-corp target is not directly available; F-reorg drop-down is the alternative).
- **In Structure II** (all-stock §368 reorg), the buyer also gets no step-up.
- **In Structure III** (asset deal), the buyer gets full step-up but the seller loses QSBS and pays two-level tax.

For a C-corp target with material QSBS, an F-reorg drop-down structure (chapter 5) could reconcile — buyer gets step-up via §338(h)(10)-like mechanics at the C-corp-parent level; seller preserves stock-form treatment. Analyse whether F-reorg drop-down is available for this target.

**Alternatively**, if the buyer refuses a stock-form structure without step-up, the seller could demand a *gross-up* to the purchase price to compensate for the QSBS forfeit. Compute:

- **Aggregate QSBS forfeit cost** (Structure I vs. Structure III at the aggregate).
- **Purchase-price gross-up needed** to make the seller indifferent.
- **What percentage of the headline is this?**

### 6. Board memo

Draft a **1-page board memo** for the founders and board that:

- States the QSBS-preservation recommendation.
- Names the specific per-cohort economics under each structure.
- Presents the recommended structure (Structure I or II) and the fallback (F-reorg drop-down or price gross-up).
- Flags the individual-planning conversations that need to happen with pre-5-year holders (Individuals H, I, J) about §1045 rollover.
- Notes the state-tax reality — California QSBS non-conformity applies regardless of structure, so the state-tax cost is largely unavoidable at the transaction level.

## Starter guidance

- **§1202 caps at *the greater of* $10M or 10x basis.** For founders with negligible basis (founding stock at par), the effective cap is $10M. If a founder has $34M gain, only $10M is excluded; the remaining $24M is fully taxable at capital-gains rates.
- **§1202 cap is per shareholder per issuer.** A founder holding stock in one company has one $10M cap for that company. Advanced planning (mod-114) can *stack* multiple $10M exclusions through gifting to trusts and family members, but this is a pre-transaction planning discipline that must be done 12+ months before the transaction — it is not available for last-minute planning.
- **QSBS-preservation *only* protects the qualifying-stock portion.** For founders with $34M gain of which $10M is §1202-eligible and $24M is above the cap, only the $10M is preserved; the $24M is taxable regardless of structure. Asset-deal cost is limited to the $10M forfeit for each such shareholder.
- **State tax is often the biggest hidden cost.** California's non-conformity to §1202 imposes 13.3% state tax on the full gain. For a California-based founder with $34M gain, the state-level cost is ~$4.5M regardless of federal §1202 treatment.
- **§1045 rollover requires operational commitment.** The individual must reinvest sale proceeds in a new QSBS issuer within 60 days. If the individual is not planning to start / join a new startup immediately, §1045 is not practical.

## Acceptance criteria

You can demonstrate that:

- Per-shareholder QSBS analysis is complete for all 10 individuals under all three structures.
- Aggregate impact table shows the total QSBS-forfeit cost of an asset deal.
- §1045 rollover analysis for Individuals H, I, J is complete.
- Structure-preference recommendation by cohort is documented.
- Buyer-preference interaction is analyzed with F-reorg drop-down and price-gross-up options.
- Board memo is 1 page and would be presentable.

## Reflection

Add a short reflection:

1. For Founder A with $34M gain, the §1202 exclusion covers $10M; the remaining $24M is taxable at 23.8% federal + 13.3% California = ~37% blended. Is the marginal QSBS savings on the $10M ($2.4M federal + $1.3M California ≈ $3.7M) worth the structural fight for a stock-form deal?
2. If a founder held their stock in a state that *does* conform to §1202 (Colorado, for example, largely conforms), how much larger would the QSBS-preservation savings be? What does this suggest about founder-state-of-residence planning?
3. For Individuals H, I, J who don't have 5-year holding, the §1045 rollover is theoretical but operationally difficult. What would a realistic personal-planning conversation with these individuals look like?
4. If the acquirer refuses a stock-form structure and insists on an asset deal, at what price gross-up does the founder-CEO become indifferent between (a) accepting the asset deal at the higher price and (b) walking from the transaction and waiting for another buyer? What does the founder-CEO's answer tell you about their true reserve price?

## Stretch goals

- **Read a QSBS practitioner memo.** Cooley, Wilson Sonsini, Fenwick, or Foundry Group all publish QSBS primers. Read one and note 3-5 nuances not fully covered in chapter 8.
- **§1202(h) reorg carryover depth.** Read §1202(h) and Treas. Reg. §1.1202 relevant sections on carryover through reorganizations. Under what specific conditions does acquirer stock carryover QSBS treatment? What if the acquirer itself has grown beyond the $50M gross-asset threshold? Cite specific regulations.
- **QSBS stacking (mod-114 depth).** Read on QSBS stacking through non-grantor trusts. If Founder A had gifted 40% of their stock to non-grantor trusts for their two children 24 months before the transaction, how many $10M exclusions would apply? What is the aggregate QSBS-preservation improvement?
- **State conformity map.** Build a table of §1202 conformity for the 10 largest state-taxes-on-founders (CA, NY, MA, WA, TX, etc.). Note which states conform, which do not, and by how much the state-conformity issue changes the founder economics for a $10M-eligible gain.
