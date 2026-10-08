# exercise-06: Lock-Up Architecture Authoring Drill

**Estimated effort:** 3 hours

## Objective

Design and document the complete lock-up architecture for your frozen company's IPO — the specific period, covered parties, covered dispositions, carve-outs, staggered-release pattern (if any), milestone conditions (if any), earnings-window carve-outs (if any), and underwriter-release discretion — and author the specific-form lock-up agreement, the specific S-1 disclosure, the specific lock-up-signature-collection workflow, and the specific lock-up-expiry IR-and-communications playbook. By the end of the exercise you should be able to defend the architecture to the underwriters (who want tight lock-ups), to the pre-IPO VCs (who want earlier liquidity), to the founders (who want specific tax-planning flexibility), and to the specific board that approves the architecture.

## Background

This exercise covers material from:

- [Chapter 6 — Lock-Up Architecture — 180-Day Standard, Carve-Outs, and Staggered Releases](../06-lock-up-architecture.md)

It also interacts with mod-106 if your frozen company ran a pre-IPO structured secondary / tender programme — the specific tender-participant carve-out and the specific extended-lock-up terms on post-tender positions are an input here.

## Prerequisites

- Frozen company profile from exercise-01, including specific cap-table composition (founder concentration, VC-concentration, employee-equity concentration, specific board holder concentration).
- The syndicate from exercise-01.
- Any specific prior tender-offer / structured-secondary history from mod-106 (if applicable).
- Access to specific recent-comparable-IPO S-1 lock-up disclosures on SEC EDGAR (the "Shares Eligible for Future Sale" and "Underwriting" sections) and specific exhibit filings.
- The SEC Rule 10b5-1 2023 amendments text for the specific cooling-off-period and plan-adoption discipline.

## Tasks

### 1. The cap-table-driven lock-up census

Produce a specific lock-up census of your frozen company's cap table. Classify each holder into one of the following lock-up buckets:

- **Mandatory lock-up — insiders.** Executive officers, directors, Section 16 reporting persons.
- **Mandatory lock-up — pre-IPO holders above de-minimis.** Pre-IPO shareholders holding above the specific de-minimis threshold (choose 0.5%, 1%, or 2% of class and justify).
- **Mandatory lock-up — EDSP / F&F participants.** Participants in the specific employee-directed-share-programme and the specific friends-and-family-programme (from exercise-04's allocation methodology).
- **Mandatory lock-up — IPO selling-stockholders on residual.** Pre-IPO holders who sold a portion of their position in the IPO's secondary component (if applicable) and are subject to lock-up on the residual.
- **No lock-up — pre-IPO holders below de-minimis.** Smaller pre-IPO holders below the de-minimis threshold (if the deal uses one).
- **No lock-up — post-IPO retail buyers.** New institutional and retail buyers in the IPO (not subject to lock-up).

For each lock-up-bucket entry, specify the specific-shares-count, the specific-%-of-class, and the specific-%-of-post-IPO-float represented. Compute the aggregate specific-%-of-shares-outstanding subject to lock-up vs. the specific-%-free-float on T+1.

### 2. The lock-up-architecture decision

Make and justify the specific lock-up architecture decisions:

**Period.**

- 180-day standard (justify), 90-day accelerated (justify), 365-day extended (justify), or a specific hybrid.
- If a hybrid, specify the specific period per bucket.

**Staggered-release pattern.**

- Full 180-day expiry at single event (default), OR
- 25% / 100% at day 90 / day 180, OR
- 33% / 66% / 100% at day 60 / day 120 / day 180, OR
- Milestone-conditional release (e.g., 25% released if the stock trades above 120% of offering price for 10 consecutive days following the Q1 earnings release).
- Justify the choice: why is this specific pattern the right trade-off between pre-IPO-holder-liquidity and aftermarket-supply-management for your cap-table composition?

**Earnings-window carve-outs.**

- Permit specific 10b5-1-plan sales within a specific window post-each-quarterly-earnings release (if used): specify the specific window length, eligibility, and specific-eligibility documentation.

**Tender-participant extended lock-up.**

- If your frozen company ran a pre-IPO tender under mod-106, specify the specific extended lock-up (270 days, 365 days, or a specific staggered-with-extended-period pattern) on the post-tender residual position.

**Underwriter-release discretion.**

- Specify the specific standard — "underwriters may in their sole discretion release any holder in whole or in part."
- Specify the specific pre-committed-posture that the engagement letter includes — e.g., a specific guidance that early releases will be considered only for specific-estate-planning, specific-founder-departure, or specific-VC-fund-lifecycle scenarios.

### 3. The specific lock-up agreement form

Draft a specific lock-up agreement form (2-3 pages). Include:

- Preamble (specific issuer identification, specific pricing date to be inserted, specific underwriter addressees).
- Covered securities definition (common stock, convertible-preferred-converting-at-IPO, options, RSUs, specific other equity).
- Covered dispositions definition (sale, pledge, hypothecation, hedge including specific-derivative-based hedges, transfer, charge against).
- Period (180 days from the pricing date, subject to specific-extension rules if applicable).
- Carve-outs:
  - Gifts and estate-planning transfers subject to transferee lock-up-bind.
  - Charitable transfers subject to transferee lock-up-bind.
  - Portfolio distributions by VC / PE funds to LPs, subject to LP lock-up-bind for remaining period.
  - Exercise / vesting (clarifying provision).
  - Tender-offer participation.
  - 10b5-1 plan adoption (not execution) during the lock-up, subject to the SEC's 2023-amendment compliance (90-120 day cooling-off, self-certification, no-overlapping-plan).
  - Underwriter-release.
  - Specific earnings-window carve-outs (if used).
- Enforcement (specific injunction + specific damages).
- Specific signature block.

### 4. The lock-up-signature-collection workflow

Author the specific workflow for collecting lock-up signatures from the specific 50-500 covered parties (specify the specific count from your lock-up census). The workflow should cover:

- **Timing.** Signatures collected during the pre-pricing window; specific deadline relative to the pricing date (typically T-7 to T-2 for all signatures).
- **Documentation platform.** Specific docusign-or-equivalent platform; specific-counsel-review discipline.
- **Specific-outreach choreography.** The specific-GC-coordinated outreach for the mandatory-lock-up holders — specific-template communications for founders, specific-template for VCs, specific-template for individual employees in EDSP / F&F.
- **Specific-pushback-handling.** How to respond to specific-VC pushback (fund-lifecycle concern), specific-founder pushback (tax-planning concern), specific-employee pushback (short-term-liquidity need).
- **Specific-missing-signatures protocol.** What happens if a specific pre-IPO holder refuses to sign — specific pricing-committee escalation, specific carve-out from the lock-up roster (and specific-impact on the deal), specific delay-pricing option.
- **Specific-registry.** Where the specific signatures are maintained; specific-syndicate-counsel audit-ready.

### 5. The S-1 lock-up disclosure

Draft the specific "Shares Eligible for Future Sale" disclosure section of the S-1 covering the lock-up. The section should include:

- Specific description of the lock-up period.
- Specific description of the covered parties.
- Specific description of covered dispositions and carve-outs.
- Specific number of shares subject to the lock-up (from your census).
- Specific aggregate percentage of shares outstanding subject to the lock-up.
- Specific timeline of shares eligible for sale at each release event (if staggered).
- Specific description of the underwriter's early-release discretion.
- Specific Rule 144 / Rule 701 affiliate-selling-restrictions that persist beyond the lock-up (relevant for post-lock-up resale discipline).

Match the style and specificity of recent-comparable-IPO S-1 Shares Eligible for Future Sale sections you can find on EDGAR.

### 6. The expiry-window IR-and-communications playbook

Author the specific IR-and-communications playbook for the lock-up expiry (and for each release event in a staggered pattern). The playbook covers:

- **90-day pre-expiry.** Specific IR communication to the sell-side analysts and the buy-side institutional accounts — specific expected supply, specific anticipated-holder-selling behaviour, specific-10b5-1-plan-roster-and-expected-timing briefing.
- **60-day pre-expiry.** Specific co-ordination with specific large lock-up holders (VC-funds, specific-founder-holdings, specific-director-holdings) on their specific selling plans; specific-10b5-1-plan-adoption discipline for the holders who plan to sell post-expiry.
- **30-day pre-expiry.** Specific decision on whether to run a specific lock-up-expiry follow-on offering — specific-syndicate conversation, specific-economics-of-follow-on-vs-aftermarket-selling, specific-decision choreography. If yes, specific marketing calendar for the follow-on.
- **Expiry day and immediate post-expiry.** Specific IR-staffing, specific-syndicate-stabilisation-expected (though Reg M stabilisation window is long closed, specific syndicate-indicative-dialogue may continue), specific press-handling, specific-employee-communication.
- **30-days post-expiry.** Specific aftermarket-report to the board, specific-10b5-1-plan-execution-tracking, specific-aftermarket-signal reading.

### 7. The multi-stakeholder negotiation decision

Pick one specific contentious lock-up-negotiation decision from your frozen company and run the specific multi-stakeholder negotiation. The decision candidates:

- A specific VC fund near its fund-end-of-life wants a 90-day lock-up on its position; underwriters want 180 days.
- A specific founder with a specific trust-planning event wants an early-release carve-out at day 60 for a specific tax-trigger reason.
- A specific pre-IPO strategic investor wants a specific staggered-release pattern that gives them earlier liquidity on 50% of position; other pre-IPO investors have standard lock-up.
- The underwriters want to extend the lock-up to 365 days on the founders' position in exchange for pricing-committee flexibility; the founders are pushing back.

For the specific decision you choose, author:

- Each specific stakeholder's position and underlying interest.
- The specific trade-space (what each side can give, what each side can take).
- The specific proposed resolution with specific terms.
- The specific risk if the resolution falls through.
- The specific documentation of the resolution.

## Starter guidance

Three anti-patterns to avoid:

- **The "180-days-fits-every-deal" default.** 180 days is the baseline but not a one-size-fits-all. A deal with heavy VC-fund-end-of-life concentration may need specific staggered releases; a deal with a specific tender-offer history may need extended lock-ups on post-tender positions; a deal with specific founder-exit-planning may need specific earnings-window carve-outs. The specific architecture reflects the specific cap-table.
- **The "sign-the-lock-up-and-ignore-10b5-1" sequencing failure.** 10b5-1 plan adoption during the lock-up (subject to the 2023 amendments' 90-120-day cooling-off period) is what lets specific holders sell cleanly at expiry. The specific sequencing — lock-up signed at pricing, 10b5-1 plans adopted during the lock-up with specific cooling-off compliance, specific plan execution post-expiry — is a specific pre-planned workflow, not an ad-hoc expiry-week scramble.
- **The silent expiry.** Deals that let the lock-up expire without specific IR-and-communications pre-work face specific larger aftermarket-price effects. The specific discipline is to communicate the specific anticipated supply and the specific selling-pattern to the buy-side 60-90 days in advance.

## Acceptance criteria

You can demonstrate that:

- The lock-up census classifies every covered party with specific shares-count and specific-%-of-class.
- The architecture-decision document is specific and justified (period, staggered pattern, earnings carve-outs, tender-participant extended lock-up, underwriter-release standard).
- The lock-up-agreement form is specific and would survive underwriter-counsel review.
- The signature-collection workflow is specific and timed.
- The S-1 Shares Eligible for Future Sale disclosure is specific and matches the style of a recent comparable-IPO S-1.
- The expiry-window playbook is specific day-by-day and tied to specific IR / syndicate activities.
- The multi-stakeholder negotiation decision has specific positions, trade-space, resolution, risk, and documentation.
- A critical reader (lead-left-counsel, specific VC-fund GP, specific-founder-adviser) can test each decision and find it defensible.

## Reflection

Add a short reflection (½ page):

1. Which specific lock-up-architecture decision is the one you expect the pre-IPO VC concentration to push back on hardest, and what is your specific fallback?
2. If your frozen company did not run a pre-IPO tender under mod-106, what specific lock-up-architecture pattern would you have proposed to compensate for the specific concentrated supply at the standard 180-day expiry?
3. What specific IR-communication would you prepare for the specific scenario where the aftermarket is soft (Scenario C from exercise-05) and lock-up expiry is approaching with specific VC-fund-end-of-life pressure?

## Stretch goals

- **Comparable-deal lock-up-architecture benchmark.** Pick 3-5 recent IPOs in your sector and reverse-engineer the specific lock-up architectures from the S-1 "Shares Eligible for Future Sale" disclosures. What specific patterns emerge in your sector? What specific-architecture lets your deal stand out?
- **Lock-up-expiry follow-on simulation.** Simulate the specific lock-up-expiry follow-on offering as an alternative to natural-aftermarket-selling. What specific pricing, size, and allocation methodology would you propose? What specific economics flow to the selling holders vs. aftermarket-selling-equivalent?
- **10b5-1 plan-portfolio design.** For 3 specific large lock-up holders (a founder, a VC fund, a specific director), draft the specific 10b5-1 plan parameters (plan-adoption date relative to lock-up expiry, specific cooling-off compliance, specific trading schedule, specific plan-horizon). What specific SEC Rule 10b5-1 2023-amendment compliance disciplines constrain each plan?
