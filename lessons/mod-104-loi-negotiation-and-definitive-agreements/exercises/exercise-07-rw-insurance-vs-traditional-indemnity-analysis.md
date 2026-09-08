# exercise-07: R&W insurance vs. traditional indemnity analysis

**Estimated effort:** 3–4 hours

## Objective

Model the retention / limit / premium economics of an R&W insurance policy against the traditional-indemnification alternative for a specific hypothetical transaction. Run the numbers under three scenarios (buyer-side policy, seller-side policy, no policy / traditional indemnification only). Then defend the choice — the choice is not obviously the same for every transaction, and a sophisticated decision requires stress-testing.

The finished artefact is a decision memo (3–5 pages) with a supporting spreadsheet-quality economic model that a General Counsel or a Corp-Dev VP would present to a board or investment committee to defend the R&W-vs-traditional decision. You should also be able to defend the choice to a CFO who is comparing the R&W premium against alternative uses of capital, and to a sell-side board that is weighing accelerated distribution against indemnification-package exposure.

## Background

This exercise covers material from:

- [Chapter 7 — R&W Insurance — Mechanics, Underwriting, and the Traditional-Indemnity Trade-Off](../07-rw-insurance-mechanics.md) as the primary reference — market conditions, retention economics, policy limits, premium economics, underwriting process, exclusions, buyer-side vs. seller-side placement decision, trade-off analysis.
- [Chapter 6 — Indemnification Package Design](../06-indemnification-package-design.md) for the traditional-indemnification package that R&W insurance is compared against.
- [Chapter 4 — Definitive-Agreement Architecture](../04-definitive-agreement-architecture-and-reps-layering.md) for the rep-package underlying the insurance and indemnification.

## Prerequisites

- The hypothetical transaction one-pager from earlier exercises.
- The indemnification package from exercise 6.
- Access to the current-cycle Marsh, Aon, and Lockton R&W insurance market reports for premium rates, retention levels, claim frequency, and exclusion trends.
- A spreadsheet tool (Excel, Google Sheets, or equivalent) for the economic model.
- If possible, a conversation with an R&W-insurance broker — brokers routinely provide indicative-quote conversations at no cost and the exposure to market conditions is educational.

## Tasks

### 1. Set the transaction-facts baseline

Write a 1-page transaction-facts baseline covering:

- **Transaction structure and size.** Enterprise value, purchase-price components, cash / stock / structured split.
- **Buyer profile.** Strategic vs. financial, first-time-acquirer vs. serial-acquirer, in-house-M&A-team capacity, insurance-market comfort.
- **Seller profile.** Founder-CEO + venture-investor cap table (typical for venture-backed target) vs. controlled-company (typical for founder-controlled target) vs. widely-dispersed (typical for public-target).
- **Target risk profile.** Sector, ARR / revenue, growth, employee count, specific diligence-surfaced risk categories.
- **Rep package characteristics.** Rep breadth, materiality qualifier density, knowledge qualifier density. Reference exercise 4.
- **Diligence quality.** Buy-side diligence workstream depth and completion status. Well-diligenced targets command better R&W insurance terms.
- **Timeline.** Signing target, closing target, exclusivity duration.

### 2. Model the traditional-indemnification-only baseline

Using the indemnification package from exercise 6, model the traditional-indemnification-only baseline. The specific outputs:

- **Seller-side indemnification exposure.** For a rep breach of size X, what is the seller's exposure? Layer by layer (general reps, fundamental reps, tax reps, specific carve-outs). Include the effective cap, the effective basket, the effective de-minimis.
- **Buyer-side effective recovery.** For a rep breach of size X, what is the buyer's likely recovery — from escrow, from direct seller recourse, from specific-indemnity funding? Model the collectibility gap (buyer's cap minus available collateral).
- **Seller-side accelerated-distribution profile.** With a 10% general escrow held 18 months, how much of the purchase price is delayed from closing to escrow release? What is the seller-side present-value cost of the delay (at the seller's discount rate)?

Model this at 3 rep-breach scenarios: small (below basket), medium (above basket, within escrow), large (above escrow, within cap).

### 3. Model the buyer-side R&W policy scenario

Design a buyer-side R&W policy for the transaction. The specific outputs:

- **Policy limit.** Typical range 10–20% of enterprise value. Defend the specific choice.
- **Retention structure.** Primary retention typically 1% of enterprise value dropping to 0.5% at 12 months. Defend the specific choice.
- **Premium.** Typical range 2–5% of policy limit (rate on line), varies with transaction and target factors. Reference the current-cycle Marsh / Aon / Lockton market reports.
- **Retention gap coverage.** Who bears the retention — buyer self-insured, seller escrow, or hybrid? Model each option and its impact on seller-side accelerated-distribution profile.
- **Exclusions.** Draft the anticipated standard-exclusion list (chapter 7 references — fraud, purchase-price adjustment, forward-looking statements, breach-of-covenant, specific-jurisdiction restrictions) plus any specific-diligence exclusions the underwriter would insist on for your target.
- **Coverage layer.** How losses above retention up to policy limit are recovered.
- **Above-policy-limit coverage.** For losses above the policy limit — either buyer self-insured (typical), additional excess-layer coverage (available for large transactions), or buyer-and-seller-split.

Model the same 3 rep-breach scenarios: small (below retention), medium (within coverage layer), large (above policy limit).

### 4. Model the seller-side R&W policy scenario

Design a seller-side R&W policy for the transaction. Note that seller-side policies are less common than buyer-side but exist in specific transaction contexts (see chapter 7).

- **Policy limit.** Similar range to buyer-side.
- **Retention structure.** Typically similar.
- **Premium.** Seller pays.
- **Coverage mechanic.** The policy indemnifies the seller for the seller's post-closing indemnification obligations to the buyer. Effectively, the seller passes the indemnification obligation to the insurer.
- **Buyer's protection.** With a seller-side policy, the buyer's protection depends on the seller having the insurance policy in force and available. The buyer typically has no direct rights against the insurer.

When would a seller-side policy make sense? Chapter 7 discusses. Common scenarios: (a) seller has specific rationale to keep indemnification off the seller-side balance sheet, (b) seller has specific relationships with insurance brokers, (c) transaction structure prefers seller-side placement for tax or accounting reasons.

For your specific transaction, evaluate whether a seller-side policy makes sense. If yes, model it. If no, document the rationale for excluding.

### 5. Compare the three scenarios

Build a comparison table across the three scenarios (traditional-indemnification-only, buyer-side policy, seller-side policy) on:

- **Seller-side exposure at each rep-breach scenario.** Under traditional indemnification the seller bears the full cap up to escrow-plus-direct-recourse; under buyer-side policy the seller bears only the retention gap; under seller-side policy the seller has similar exposure to buyer-side (with insurance pay-through mechanic differences).
- **Buyer-side effective recovery at each rep-breach scenario.** Under traditional indemnification the buyer's recovery is limited by collateral availability; under buyer-side policy the buyer has policy-limit recovery certainty; under seller-side policy the buyer's recovery is contingent on the seller's insurance being in force.
- **Seller-side accelerated-distribution profile.** With traditional-indemnification the escrow-delay economics are material; with R&W insurance the escrow is dramatically smaller. Model the seller-side present-value benefit.
- **Total transaction cost.** Under traditional-indemnification the cost is the seller's exposure plus escrow delay; under R&W insurance the cost includes the premium plus retention exposure. Where is the crossover point?

The comparison should be quantitative (dollar amounts) rather than qualitative.

### 6. Stress-test the analysis

Stress-test the analysis under 3 scenarios:

**Scenario A — the low-claim-frequency world.** Actual rep-breach claims turn out to be small and infrequent (below the basket in most cases). Which scenario delivers the best economic outcome?

**Scenario B — the moderate-claim-frequency world.** Actual rep-breach claims turn out to be moderate — one or two claims in the mid-single-digit-millions range. Which scenario delivers the best economic outcome?

**Scenario C — the high-claim world.** A significant claim above the R&W policy limit surfaces post-closing. Which scenario delivers the best economic outcome?

For each stress-test, note the assumptions and the specific dollar impact.

### 7. Consider the specific-diligence exclusion strategy

R&W insurance underwriters typically exclude specific-diligence-surfaced items from the standard coverage — the "known matter" exclusion. For each of the special-indemnity items you identified in exercise 6, evaluate:

- Would the R&W underwriter accept the item within coverage, or exclude?
- If excluded, does the item become a specific-indemnity carve-out from the seller-side (funded from separate escrow), a buyer-side self-insured risk, or a specific-negotiated coverage-exception?
- What is the specific-indemnity-cost delta between the R&W-supported structure and the traditional structure for this item?

Consider especially: state-tax nexus, specific customer litigation, specific IP-infringement claims, specific privacy incidents, AI-model-training-data-licensing exposure (increasingly a common exclusion in current market).

### 8. Consider the buyer-side vs. seller-side placement decision

Beyond the economic modelling, consider the strategic decision:

- **Buyer-side placement rationale.** Standard for most transactions. Buyer controls the underwriting process, selects the broker, negotiates the policy terms. Seller has less exposure to the specific insurance-market conditions.
- **Seller-side placement rationale.** Less common. Applicable in specific transaction contexts — controlled-company transactions, seller-driven-marketing transactions, specific insurance-broker relationships.
- **Hybrid placement.** Some transactions use both — a buyer-side policy for standard coverage plus a seller-side specific-indemnity policy for known-matter exposure.

Defend the specific placement choice for your transaction.

### 9. Draft the decision memo

Write a 3–5 page decision memo covering:

- **Recommendation.** Buyer-side R&W policy, seller-side R&W policy, or traditional-indemnification only.
- **Rationale.** Grounded in the economic modelling and the strategic placement analysis.
- **Specific terms.** Policy limit, retention structure, premium expectation, exclusions.
- **Alternative considered and rejected.** The specific reason to reject the alternative.
- **Stress-test outcomes.** How does the recommendation perform across the three stress-test scenarios?
- **Trade-offs.** What is the seller giving up? What is the buyer giving up? What is the specific dollar cost of each?
- **Broker-selection recommendation.** Marsh, Aon, Lockton, WTW, or specific mid-tier. Rationale (deal-size fit, sector experience, broker-partner reputation, cost).
- **Underwriter-market read.** Which underwriters are currently active in your sector at your transaction size? Marsh's or Aon's or Lockton's current market report should inform this.

### 10. Chapter-8 negotiation-canon overlay

For the R&W-vs-traditional negotiation between buyer and seller, name:

- The Freund frame — where in the definitive-agreement negotiation does this decision get made? Is it a closing-conversation issue or an earlier issue?
- The Harvard frame — what is the buyer's underlying interest (post-close protection) vs. position (specific package)? What is the seller's underlying interest (accelerated-distribution, capped exposure) vs. position? Where is the interest-based middle ground?
- The Voss frame — what calibrated questions surface the other side's willingness to pay for R&W insurance vs. accept traditional-indemnification exposure?

## Starter guidance

Common R&W-vs-traditional analysis errors to avoid:

- **The premium-cost-only focus.** Focusing on the R&W premium in isolation without modelling the seller-side accelerated-distribution benefit. For sellers with high time-value-of-money, the accelerated distribution alone can more than offset the premium cost.
- **The exclusions-blind analysis.** Assuming R&W insurance covers everything. In practice, R&W policies have specific exclusions and known-matter carve-outs that reshape the effective coverage. Model the effective coverage, not the nominal policy limit.
- **The market-conditions-static analysis.** R&W insurance market pricing fluctuates materially year over year. Assumptions from a tight-market cycle (compressed premiums, generous coverage) do not carry into a loose-market cycle (higher premiums, tighter exclusions).
- **The single-scenario analysis.** Modelling only one rep-breach scenario. The analysis needs to hold across multiple scenarios to be robust.
- **The seller-side-only-analysis.** Analysing the R&W decision from the seller's perspective without modelling the buyer's perspective. The decision affects both sides; the analysis needs to be joint.

## Acceptance criteria

You can demonstrate that:

- Transaction-facts baseline is written and includes rep-package characteristics, diligence quality, and timeline.
- Traditional-indemnification-only baseline is modelled at 3 rep-breach scenarios with dollar-quantified seller exposure, buyer recovery, and seller accelerated-distribution profile.
- Buyer-side R&W policy is modelled with policy limit, retention structure, premium, exclusions, and retention-gap coverage.
- Seller-side R&W policy is evaluated (either modelled or explicitly rejected with rationale).
- Comparison table across the three scenarios is quantitative on seller exposure, buyer recovery, accelerated-distribution profile, and total transaction cost.
- Stress-test analysis covers low, moderate, and high claim-frequency scenarios.
- Specific-diligence exclusion strategy is documented for each special-indemnity item from exercise 6.
- Buyer-side vs. seller-side placement decision is defended.
- Decision memo is drafted at 3–5 page depth with recommendation, rationale, terms, alternatives, stress-test outcomes, trade-offs, broker-selection, and underwriter-market read.
- Chapter-8 negotiation-canon overlay identifies frames.

## Reflection

Add a short reflection:

1. Which single factor drove your recommendation the most — transaction size, seller-side accelerated-distribution benefit, buyer-side recovery certainty, or specific-exclusion risk?
2. If the R&W insurance market moved (premiums up 30%, retention up 50%, exclusions broader) between LOI and signing, how would your recommendation change?
3. The known-matter exclusion for the AI-model-training-data risk on an AI-first target — is that risk best handled through a specific-indemnity carve-out, a specific negotiated coverage-exception with the underwriter, or a buyer-side self-insured retention?
4. For a widely-dispersed employee stockholder base, does R&W insurance change the recommendation compared to a concentrated founder-plus-investor base? Why?

## Stretch goals

- **Broker-outreach conversation.** Schedule a 30-minute conversation with an R&W-insurance broker. Ask for an indicative quote on your specific transaction facts. Compare the actual indicative quote to your modelled assumption.
- **Underwriter-perspective simulation.** From the underwriter's chair, what specific diligence outputs (Q of E memo, legal-diligence memo, tax-diligence memo) would the underwriter want to see? What specific exclusions would the underwriter propose based on the target's specific risk profile?
- **AI-model-training-data-exclusion negotiation.** For an AI-first target, draft the specific coverage-exception negotiation you would run with the underwriter to bring the AI-model-training-data risk within coverage. Note the market-conditions dependency.
- **Historical-transaction diagnostic.** Retrieve a specific publicly-filed R&W policy binder or R&W-supported merger agreement. Compare the specific coverage structure to your recommended structure.
- **Multi-year cost-of-capital analysis.** For a seller with high cost-of-capital (a founder-CEO planning to fund the next venture from the exit proceeds), extend the accelerated-distribution analysis to a multi-year cost-of-capital comparison. What is the specific dollar benefit of R&W insurance's accelerated-distribution profile over a 5–10 year horizon?
- **Combined-package design.** Consider a hybrid structure — R&W insurance for standard coverage, specific-indemnity escrow for known-matter exposure, seller-side accelerated distribution for the balance. Design the specific structure and defend against a pure buyer-side R&W or pure traditional-indemnification approach.
