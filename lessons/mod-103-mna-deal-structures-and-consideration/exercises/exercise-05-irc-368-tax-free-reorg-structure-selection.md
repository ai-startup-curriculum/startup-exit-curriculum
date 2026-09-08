# exercise-05: IRC §368 Tax-Free Reorg Structure Selection

**Estimated effort:** 3 hours

## Objective

For three target profiles (a Delaware C-corp with venture-backed cap table, an S-corp with founder owners, and a single-member LLC with a C-corp holding company on top), select the tax structure that fits and explain the tax-and-corporate mechanics. Match the structure to the specific consideration mix, buyer's step-up requirements, and seller's tax-preference constraints. By the end you should be able to explain to the buyer's tax director why the recommended structure works for each profile and what the downstream tax consequences are for each shareholder cohort.

## Background

This exercise covers material from:

- [Chapter 5 — IRC §368 Tax-Free Reorg Selection and §338(h)(10)](../05-irc-368-tax-free-reorg-selection.md)

Chapter 1 (form choice) provides the corporate-form vocabulary; the tax structure is layered on top of the corporate form. Chapter 8 (§1202 QSBS) determines whether the shareholders can preserve QSBS treatment through the chosen structure.

> **Education, not tax advice.** Live transactions require qualified tax counsel. This exercise builds the decision framework so you can meaningfully engage with tax counsel — it does not substitute for their analysis.

## Prerequisites

- You have read chapter 5 in full.
- Basic familiarity with §368 reorg types (A/B/C/F), §338(h)(10) election, and §1202 QSBS.
- Access to the Treasury Regulations under §368 (Treas. Reg. §1.368-1 through §1.368-3) — these are available on the eCFR.

## The three target profiles

### Profile A — Delaware C-corp with venture-backed cap table

- **Entity type.** Delaware C-corporation, 8 years old.
- **Shareholder mix.** 4 founders (each holding ~7-8% of fully-diluted, all §1202 QSBS with >5-year holding, minimal basis). 25 early employees with exercised options (mixed QSBS status). 40 later employees with mostly unexercised options. Series A/B/C/D preferred investors holding a $175M preference stack.
- **Financials.** $52M ARR, growing 45%, cash-flow-neutral.
- **Business.** Vertical B2B SaaS. No product-liability issues. Clean tax history except for state-nexus questions in 3 states (buyer's tax diligence estimates $500k-$1M exposure).
- **Acquirer.** Publicly-traded strategic, S&P 500. Cash-rich.
- **Consideration.** $520M — LOI proposes 60% cash / 40% acquirer stock.
- **Buyer preferences.** Buyer's tax director wants amortisable goodwill on the intangible portion.
- **Seller preferences.** Founders want §1202 QSBS preservation on their qualifying stock. All founder principals hold >5 years so QSBS is available.

### Profile B — S-corporation with founder owners

- **Entity type.** Delaware S-corporation, 12 years old.
- **Shareholder mix.** 2 co-founder owners each holding 50% of the S-corp stock. No outside investors.
- **Financials.** $28M revenue, $8M EBITDA, growing 20%. Cash-generative.
- **Business.** Managed-services / consulting in enterprise cybersecurity. Long customer contracts with change-of-control consent in 40% of contracts.
- **Acquirer.** Mid-market financial buyer (PE fund).
- **Consideration.** $72M all-cash.
- **Buyer preferences.** Buyer's tax director wants asset-deal-tax treatment for step-up.
- **Seller preferences.** Founders' tax advisor has raised the §338(h)(10) election as a compromise. Founders want their proceeds tax-optimised but recognise that S-corp status limits their §1202 options (S-corp stock is not §1202-eligible).

### Profile C — LLC operating company with C-corp holding company

- **Entity type.** Delaware LLC operating company (partnership-taxed) with a Delaware C-corp holding company on top. Holding company holds 100% of the LLC.
- **Shareholder mix.** Founders hold C-corp common (§1202 QSBS if issued at qualifying time; assume qualifying issuance). Employees hold options on C-corp stock. VC investors hold preferred at C-corp level with $60M preference stack.
- **Financials.** $18M ARR, growing 75%.
- **Business.** Vertical SaaS with some product-liability exposure (one settled customer claim and one active reservation-of-rights letter).
- **Acquirer.** Mid-market strategic ($5B revenue diversified industrial-tech).
- **Consideration.** $140M all-cash.
- **Buyer preferences.** Buyer's tax director wants step-up in asset basis (amortisable goodwill under §197). Buyer's M&A counsel wants to isolate the reservation-of-rights liability.
- **Seller preferences.** Founders want QSBS preservation on qualifying stock. R&W insurer will not cover the specific product-liability item.

## Tasks

### 1. Structure selection for each profile

For each of the three profiles, choose one of the following structures (or a variant / hybrid):

- Taxable stock deal (no §338(h)(10) election, no §368 reorg).
- Taxable asset deal.
- §368(a)(1)(A) forward merger.
- §368(a)(2)(D) forward-triangular merger (requires ≥50% qualifying stock consideration).
- §368(a)(2)(E) reverse-triangular merger (requires ≥80% qualifying stock consideration).
- §368(a)(1)(B) stock-for-stock (requires solely voting stock).
- §368(a)(1)(C) stock-for-assets (requires substantially all assets + voting stock).
- §368(a)(1)(F) reorganisation (F-reorg drop-down pattern).
- Stock deal with §338(h)(10) joint election (requires S-corp target or 80%-owned subsidiary of consolidated group).
- F-reorg drop-down followed by §338(h)(10)-eligible stock sale of the C-corp parent (for C-corp targets).

Write a **1-page structure-selection memo per profile** with the following sections:

- **A. Structure chosen.** Name the specific structure. Note if you propose an alternative (e.g., "Option 1 is my recommendation; Option 2 is a fallback if the buyer refuses on the tax cost").
- **B. Continuity-of-interest analysis.** For any §368 structure, does the consideration mix meet the applicable continuity-of-interest requirement (40% for §368(a)(1)(A) under current IRS practice; 50% for §368(a)(2)(D); 80% for §368(a)(2)(E))?
- **C. Continuity-of-business-enterprise analysis.** Will the acquirer continue the target's historic business or use a significant portion of its historic assets?
- **D. Tax consequences at each level.**
  - **Target level.** Does the target recognise gain? Are there two levels of tax?
  - **Shareholder level.** For each cohort (founders, early employees, preferred investors), how is the consideration taxed? Any deferral available (e.g., §368 stock portion)?
  - **Buyer level.** Does the buyer get a step-up in asset basis? What is the amortisation profile of intangibles under §197?
- **E. §1202 QSBS analysis.** Preserved, tacked (via §1202(h) reorg carryover), or forfeit? Per shareholder cohort as applicable.
- **F. Corporate-form implications.** Does the tax structure force a specific corporate form (e.g., §368(a)(2)(E) requires an RTM)? What are the DGCL / consent implications?
- **G. Risks and open questions.** What further diligence or counsel review is required?

### 2. Buyer-counter-preference analysis

For each profile, the buyer's tax director has expressed a preference that partially conflicts with your recommended structure. For each profile:

- **What is the buyer's first-pass preference?** Name specifically (e.g., "asset deal for step-up; if not, §338(h)(10) election for step-up").
- **Why does your recommended structure not fully accommodate the buyer?**
- **What compensation or concession does the buyer receive to accept your structure?** (E.g., price gross-up to cover the deferred step-up; specific-indemnity protection for the liability the buyer would have isolated in an asset deal.)
- **What is the fallback structure if the buyer refuses your recommendation?** Name specifically.

### 3. Seller-shareholder disclosure

For each profile, produce a **shareholder-cohort disclosure table** showing the after-tax outcome for each cohort under your recommended structure:

| Cohort | Consideration received | Tax treatment | After-tax value |
|---|---|---|---|
| Founders (C-corp common with §1202) | | | |
| Early employees (exercised, some §1202) | | | |
| Later employees (options exercised at closing) | | | |
| Series A preferred | | | |
| ... | | | |

Simplify the tax rates:
- §1202 exclusion: $10M per shareholder per issuer capped, remainder at 23.8% long-term capital gains (including NIIT).
- Long-term capital gain (non-QSBS): 23.8%.
- Ordinary income (compensation portion): assume 40.8% marginal rate (37% federal top rate + 3.8% NIIT).
- S-corp pass-through: 37% marginal rate + 3.8% NIIT on ordinary; 23.8% on capital gain portion.
- Corporate tax on target (asset deal for C-corp): 21%. State tax varies; assume 5% average for simplicity.

### 4. Draft the specific tax-and-structure clauses

For each profile, draft 2-3 specific clauses that would appear in the merger agreement to implement your structure:

- **Profile A example:** the reverse-triangular merger provision (§368(a)(2)(E)), the §1202(h) preservation acknowledgment for the acquirer stock consideration, and the §280G (chapter 6) treatment of parachute payments (if relevant).
- **Profile B example:** the joint §338(h)(10) election provision, the "gross-up" for the incremental tax cost to the S-corp shareholders, and the closing-condition-precedent that both parties execute IRS Form 8023.
- **Profile C example:** the F-reorg drop-down pre-transaction restructuring steps and the §338(h)(10) election at the C-corp-parent level; the specific-indemnity holdback for the product-liability item.

Draft each clause as a 2-4 sentence provision.

### 5. Cross-profile synthesis

Write a **½–1 page synthesis** answering:

- Which of the three profiles produced the *cleanest* structure-choice? Which was most contested? Why?
- For which profile did §1202 QSBS drive the structure choice? Where did QSBS become the tie-breaker?
- Which profile had the largest gap between the buyer's tax preference and the seller's tax preference? Where would this fact pattern be most likely to lose the deal at first-pass negotiation?
- Where did an F-reorg drop-down provide the reconciliation between buyer step-up and seller stock-form treatment? Is this structure widely used, or is it specialist counsel territory?

## Starter guidance

- **The reverse-triangular merger with 80% stock is the modal §368 structure** for venture-backed C-corp targets. If your Profile A consideration mix (60% cash / 40% stock) does not meet the 80% threshold, either (a) a forward-triangular merger with §368(a)(2)(D) (requires ≥50% stock; qualifies here) is available for §368 treatment on the stock portion, or (b) the transaction is a taxable stock deal on the cash portion and §368-treated on the stock portion under a different theory (this is more complex). Cover this specifically.
- **§338(h)(10) requires an S-corp target or an 80%-owned corporate subsidiary of a consolidated group.** For Profile A (C-corp with venture-backed cap table), §338(h)(10) is *not directly available* — the F-reorg drop-down pattern is the way to reconcile.
- **§338(h)(10) requires a joint election.** The buyer cannot make the election unilaterally. The seller has leverage; the tax cost of the election to the seller (asset-deal-level tax on the target's assets, passed through to the S-corp shareholders) typically has to be grossed-up in the purchase price.
- **F-reorg drop-down is specialist territory.** The mechanics — pre-transaction restructuring of the C-corp target through an F-reorg to become a disregarded LLC, followed by an asset-deal-taxable sale that flows through the surviving parent — require careful drafting. Consult chapter 5 for the specific steps.

## Acceptance criteria

You can demonstrate that:

- All three profiles have completed 1-page structure-selection memos covering sections A-G.
- The buyer-counter-preference analysis names the buyer's first-pass position and the concession structure.
- The shareholder-cohort disclosure tables show after-tax outcomes by cohort.
- The specific tax-and-structure clauses are drafted for each profile.
- The cross-profile synthesis answers the four questions.

## Reflection

Add a short reflection:

1. For Profile B (S-corp), why is §338(h)(10) attractive to the buyer? Why does it not disadvantage the seller in the same way an asset deal for a C-corp would?
2. For Profile C (LLC-under-C-corp), the F-reorg drop-down is more complex than a typical §368 reorg. What is the specific compensating advantage that justifies the complexity? Would you recommend this structure to a founder-CEO who is uncomfortable with complex tax structures, or would you steer toward a simpler alternative even at cost to the seller's tax outcome?
3. In Profile A, if the buyer's tax director insists on a §338(h)(10) election (which is unavailable for a C-corp target), what alternative structure could you propose that achieves the buyer's step-up objective? What is the incremental cost or complexity?
4. Which of the three profiles feels most likely to have a *tax lawyer who thinks it can be done differently*? Where would you want a second opinion from independent tax counsel before committing to your recommendation?

## Stretch goals

- **Continuity-of-interest depth.** Read Rev. Proc. 77-37 (superseded but instructive) and current IRS Continuity-of-Interest guidance. Note the specific 40% floor and its historical evolution. Cite in your Profile A memo.
- **§336(e) alternative.** For a C-corp target where §338(h)(10) is unavailable, §336(e) is a related asset-deal-treatment election. Read the §336(e) mechanics and note whether it could apply to Profile A. What are the specific §336(e)-vs-§338(h)(10) differences?
- **Cross-border complication.** Assume Profile A's acquirer is foreign (a public UK strategic instead of a US S&P 500). How does that change the §368 analysis? What is the §7874 inversion analysis? What specific structure would you use to avoid inversion characterisation?
- **Read a tax opinion.** Practitioner memos from Cooley, WSGR, Fried Frank, or Wachtell on §368 / §338(h)(10) tax structuring for private-target M&A are available on their websites. Read one and note 3-5 nuances that go beyond chapter 5's framing.
