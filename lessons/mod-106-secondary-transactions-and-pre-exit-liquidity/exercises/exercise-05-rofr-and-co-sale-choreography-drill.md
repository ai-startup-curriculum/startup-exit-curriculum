# exercise-05: ROFR and Co-Sale Choreography Drill

**Estimated effort:** 3–4 hours

## Objective

Run a Right-of-First-Refusal (ROFR) and co-sale process end-to-end against a specific proposed transfer. Draft the transfer notice; model the board-and-preferred waiver deliberations; run the co-sale (tag-along) calculation; and simulate three failure modes (notice-window lapse, price change mid-process, preferred over-subscription). Produce a run-book (8–12 pages) suitable as an operational playbook for the target's GC and outside counsel, plus the specific artefacts (transfer notice, board resolution, preferred-holder waiver circulation, co-sale participation election, closing certificate). At the end you should be able to walk any share-transfer scenario through the choreography without missing a mechanic.

## Background

This exercise covers material from:

- [Chapter 6 — ROFR and Co-Sale Choreography — The Standard NVCA Pattern, Notice, Waiver, and Tag-Along Rights](../06-rofr-and-co-sale-choreography.md) — the three-level ROFR cascade, the exception categories, the notice mechanics, the waiver mechanics, and the co-sale participation right.

Supporting references:

- [Chapter 1 — Founder Secondary](../01-founder-secondary-structuring.md) and [Chapter 2 — Employee Tender](../02-employee-tender-offer-design.md) — the transactions the ROFR / co-sale apparatus governs.
- The NVCA Model Legal Documents (charter, voting agreement, ROFR / co-sale agreement) — the canonical drafting baseline for the choreography.

## Prerequisites

- The NVCA Model ROFR / Co-Sale Agreement (available on the NVCA's Model Legal Documents portal). Use the current-generation version and note the specific provisions you rely on.
- The NVCA Model Voting Agreement (contains the ROFR and co-sale rights in some model configurations).
- A target company with a defined ROFR / co-sale agreement — either your carried-through target from prior exercises, or a hypothetical constructed from the NVCA baseline.
- A cap table with each preferred holder's ownership percentage (drives the pro-rata ROFR and co-sale calculations).
- A spreadsheet for the co-sale calculation.

## Tasks

### 1. Set the target-and-transaction baseline

Write a 1-page baseline covering:

- **Target profile** — cap-table shape (common outstanding, each preferred series with per-holder ownership breakdown, option pool position).
- **ROFR / co-sale agreement summary** — the specific provisions of the target's agreement, keyed to the NVCA baseline. Identify any material deviations from NVCA (e.g., different notice windows, different exception categories, absence of a specific tier of the cascade, different co-sale mechanics).
- **Proposed transfer** — the transferring shareholder identity (founder / employee / early investor), the proposed transferee identity (existing preferred investor / new institutional investor / individual accredited investor / family office), the share count, the per-share price, the aggregate consideration, and the proposed closing date.
- **Exception-category check** — does the transfer fall into any of the standard exception categories (family transfer, devolution, affiliated-entity transfer, small-transfer de minimis, employee-tender-blanket-waiver)? If yes, the ROFR / co-sale process does not apply and the exercise runs the exception-category confirmation choreography instead.

### 2. Draft the transfer notice

Produce the transfer notice document that the transferring shareholder must deliver to the company (and, per the specific agreement, to preferred holders directly). The notice should include:

- The identity of the proposed transferee, with any basic buyer information required by the agreement.
- The share count proposed to be transferred, with specific share-lot identification if relevant.
- The proposed transfer price and total transaction consideration.
- The proposed closing date.
- The bona fide offer document from the transferee (attached or referenced).
- The proposed transfer terms — any conditions, contingencies, or non-price economics.
- The specific ROFR / co-sale-agreement citations invoked.

The notice should be drafted in the specific format the agreement requires (typically a formal notice under a "Notices" clause with specified delivery mechanisms).

### 3. Model the board waiver deliberation

Produce a specific board-waiver package covering:

- **Board resolution draft** — the specific resolution to waive the company's ROFR on the proposed transfer. Cover the specific vote requirements (majority of the board; specific votes recused if the transferring shareholder or the transferee is a director-related party).
- **Board deliberation memo** — a 2-page memo the board would consider covering the transaction's context, the alignment-of-interest analysis (if the transferring shareholder is a founder or executive — cross-reference exercise-01), the company's cash position and other-uses-of-capital analysis (would the company use its cash to buy back the shares?), and the recommendation to waive.
- **Written-consent format** — if the board acts by written consent rather than at a meeting, the specific consent document with the required signatures.

Cover the failure-mode scenario: what if the board decides *not* to waive and instead to exercise the company's ROFR? Draft the alternate resolution and the mechanics for the company's actual purchase.

### 4. Run the preferred-holder waiver circulation

Produce the preferred-holder waiver circulation package covering:

- **Waiver document** — a formal waiver form each preferred holder receives, with the transfer details, their pro-rata participation percentage entitlement, and a response deadline.
- **Circulation mechanics** — how the waivers are distributed (email typically acceptable under most agreements; formal delivery in some), the tracker for outstanding responses, and the escalation-to-counsel process for non-responsive holders.
- **Response taxonomy** — what a "waive" response, an "exercise" response (with specific share count and per-share terms), and an "over-subscribe" response (for over-allotment-permitted agreements) look like.
- **Silence-is-a-waiver treatment** — the specific provision in the agreement and the operational mechanics for treating non-responses.
- **Aggregation and confirmation** — the mechanics for aggregating responses at close of window and confirming any exercises to the transferring shareholder and to the proposed transferee.

Cover the failure-mode scenario: what if one or more preferred holders exercise? Model the specific scenario in which two preferred holders each exercise half of their pro-rata allocation, aggregating to (say) 15% of the proposed transfer. Compute the transferring shareholder's actual disposition — 15% to the exercising preferred holders, 85% to the proposed third-party transferee (subject to the co-sale mechanics below).

### 5. Run the co-sale (tag-along) calculation

Produce the co-sale calculation covering:

- **Co-sale eligibility identification** — from the target's ROFR / co-sale agreement, identify who has co-sale rights (typically preferred holders, and sometimes named significant common holders).
- **Co-sale notice** — the same transfer notice typically triggers the co-sale process; identify any additional notice or election-mechanic requirements.
- **Participation calculation** — for each co-sale-eligible holder who elects to participate, compute their proportional participation share. Standard mechanics: each participant sells the proportion of their eligible shares equal to the proportion of the transferring shareholder's proposed sale to their total holdings. Model this against a specific cap-table.
- **Proration if the buyer will not accept full participation** — if the buyer's total purchase intent does not accommodate everyone's full proportional participation, the transferring shareholder's sale is reduced proportionally and everyone participates at the same reduced proportion.
- **Election form** — the specific form each co-sale-eligible holder uses to elect participation.
- **Impact on the transferring shareholder** — the reduced sale amount if co-sale participation reduces the buyer's available capacity for the transferring shareholder's shares.

Cover the failure-mode scenario: model a co-sale in which two preferred holders and one significant early common holder each elect to participate at full proportional participation, and compute the specific new allocation to each participant and to the transferring shareholder.

### 6. Simulate three failure modes

For each failure mode, produce a specific 1–2 page simulation covering the mechanics that go wrong, the specific consequences, and the recovery choreography:

#### Failure Mode A — Notice-window lapse

The transferring shareholder or counsel misses the response deadline for one preferred holder. That holder subsequently claims they were entitled to participate. The transaction has closed. Simulate the specific dispute mechanics:

- What the missing-notice preferred holder's specific claim is.
- The transferring shareholder's and target's defence (if any).
- The likely remedy (rescission, damages, or negotiated settlement).
- The choreography change that would have prevented the failure.

#### Failure Mode B — Price change mid-process

After the notice is delivered and while the ROFR windows are running, the transferee negotiates the price down 10% as a result of updated diligence. Simulate:

- Whether the price change requires a re-notice under the specific agreement.
- The additional time-cost of a re-notice.
- The transferring shareholder's specific choices (accept the price change and re-notice; refuse the price change and terminate the transaction; negotiate a non-price adjustment that leaves the notice-price intact).
- The recommendation.

#### Failure Mode C — Preferred over-subscription

Three preferred holders exercise their full pro-rata allocations, and two additional preferred holders over-subscribe. The over-subscription exceeds the un-exercised residual allocation from the non-exercising preferred holders. Simulate:

- The over-allotment allocation mechanic (typically pro-rata among over-subscribers).
- The specific arithmetic in the model.
- The final allocation to each exercising preferred holder and the residual (if any) to the proposed third-party transferee.
- The impact on the transaction's closing timeline (typically no extension, but the specific mechanics matter).

### 7. Draft the closing certificate

Produce a closing certificate that the target's officer would sign at close, confirming:

- The transfer notice was delivered in compliance with the agreement.
- The company's ROFR was waived (or exercised) per board resolution dated [X].
- The preferred-holder waiver process was administered in compliance with the agreement.
- The co-sale process was administered and participation was documented.
- The transferring shareholder's actual disposition is documented.
- All exemptions (Section 4(a)(7), Rule 144, or other) are confirmed by counsel.
- All blue-sky compliance actions are complete.
- The cap-table update is authorised.

The closing certificate is the artefact that anchors the target's defensible position in any future dispute over the transfer's regularity.

### 8. Author the target-side run-book

Produce a 4–6 page run-book that the target's GC and outside counsel could adopt as standing operational playbook covering:

- The end-to-end process from notice delivery through closing certificate.
- The specific timelines and windows against the target's agreement.
- The specific artefacts required at each stage.
- The escalation-to-counsel triggers.
- The board and management sign-offs required at each stage.
- The blue-sky and Section 4(a)(7) / Rule 144 exemption analysis coordination.
- The 409A materiality-check integration.
- The failure-mode recovery paths.

## Starter guidance

Common ROFR / co-sale choreography errors to avoid:

- **Verbal-approval-only board waiver.** The board must formally decide (resolution or written consent). A verbal "we're all fine with this" that never makes it to the minutes is a governance failure that surfaces in future M&A or IPO diligence.
- **Missing a preferred-holder in the notice circulation.** Cap-table records must be maintained current; a preferred holder who has transferred to an affiliated vehicle needs the affiliated-vehicle correspondence path updated. A missed holder can void the entire ROFR run.
- **Assuming "silence is a waiver" without checking the specific provision.** Some agreements do not have a silence-is-a-waiver clause; a preferred holder who does not respond may retain the right to exercise later. The specific agreement provision determines the default.
- **Running the co-sale calculation on gross rather than proportional participation.** Every co-sale-eligible holder should sell the *same proportion* of their eligible shares; not the same absolute number. Getting this wrong creates disproportionate treatment that a subsequent dispute will surface.
- **Treating exception categories as automatic.** A "transfer to family trust" that turns out to be a transfer to a trust with a non-family beneficiary is not an exception-category transfer. Counsel should confirm each exception-category invocation.
- **Closing the transaction before the ROFR windows have fully run.** Even if all responses received are waivers, the transaction should not close until the formal deadlines have passed. Otherwise a late-arriving exercise creates a rescission risk.
- **Skipping the closing certificate.** The certificate is what anchors the target's regularity defence in any future dispute; skipping it is a false economy.

## Acceptance criteria

You can demonstrate that:

- Target-and-transaction baseline covers the target's specific ROFR / co-sale agreement provisions and the proposed transfer's specific terms.
- Transfer notice is drafted in the specific format the agreement requires.
- Board waiver deliberation is modelled with resolution, memo, and alternate-exercise scenario.
- Preferred-holder waiver circulation is designed with waiver document, circulation mechanics, response taxonomy, silence-is-a-waiver treatment, and aggregation.
- Co-sale calculation is run with specific arithmetic against a specific cap table and a specific failure-mode participation scenario.
- Three failure modes are simulated (notice-window lapse, price change mid-process, preferred over-subscription) with specific consequences and recovery choreography.
- Closing certificate is drafted.
- Target-side run-book is authored at 4–6 pages.

## Reflection

Add a short reflection:

1. Which of the three failure-mode simulations produced the most consequential dispute risk, and what specific procedural discipline would have prevented it?
2. If the target's ROFR / co-sale agreement had a "silence is a waiver" provision replaced with a "silence is retention of rights" provision, how would the operational choreography change, and would the target need to invest in a specific tracking-and-escalation process to keep transactions on schedule?
3. If a preferred holder exercised their ROFR at less-than-friendly terms in a routine founder secondary, would the transferring shareholder proceed or withdraw the notice, and what does that tell you about the ROFR's economic function beyond the notice mechanics?
4. What is the single sentence you would add to a board's waiver-approval memo to lock in the alignment-of-interest analysis (chapter 1) inside the ROFR-waiver decision?

## Stretch goals

- **NVCA-document redline exercise.** Pull the NVCA Model ROFR / Co-Sale Agreement and produce a redline that modifies three specific provisions (notice windows, silence-is-a-waiver treatment, over-allotment mechanics) to produce a specific target-friendly variant. Defend the changes.
- **Multi-transfer batch choreography.** Draft the choreography for a batch of 15 simultaneous transfers (representing a tender's clearing) run through a single aggregated ROFR / co-sale process. Note the operational efficiencies vs. the specific-transferee-and-terms discipline.
- **Notice-window automation.** Build a spreadsheet or notebook that tracks specific notice deadlines across a set of transfers and produces automated reminders to counsel and to responsible officers.
- **International-transfer choreography.** Where the transferring shareholder or the transferee is resident in a foreign jurisdiction, identify the specific additional compliance work (CFIUS notice for national-security-sensitive targets, foreign-securities-law compliance in the transferee's jurisdiction, tax-withholding under §1445 for foreign transferees).
- **Voting-agreement drag-along interaction.** Some agreements combine ROFR / co-sale with drag-along rights; identify how a proposed transfer that triggers a drag-along would be handled differently than one that does not, and what the interaction with the ROFR notice mechanics looks like.
- **Preferred-holder-side counterparty view.** Draft the specific analysis a preferred holder's investment committee would run to decide whether to exercise their ROFR in a routine transaction. Identify the fund-level economics that drive the decision.
