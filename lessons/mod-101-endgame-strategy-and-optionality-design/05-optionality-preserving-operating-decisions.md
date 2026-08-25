# Optionality-Preserving Operating Decisions

## Why this matters

The endgame ranking (chapter 2), the buyer map (chapter 3), and the market-window read (chapter 4) all sit above the operating loop. This chapter turns the frame downward and asks a specific question:

> Which decisions we make in this quarter's operating loop pre-close a future endgame option — and how would we design them differently to keep it live?

Founders sometimes forget how much routine operating machinery has endgame consequences. A venture-debt covenant signed at Series B forbids the change-of-control transaction the CFO now wants to run. A ROFR clause negotiated as boilerplate three years ago blocks the secondary the board wants this quarter. A "we accept our standard MSA" from a growth-round enterprise customer contains a change-of-control clause that lets that customer terminate on assignment — and now the acquirer's diligence team is discounting the ARR by 40%.

None of these decisions felt strategic when they were made. All of them foreclose specific endgame paths in ways that are hard to undo later.

This chapter is the audit — the operating disciplines that keep endgame optionality live rather than pre-closed. Four surfaces: financing choices, cap-table structure, board composition, and contract terms.

## Boundary reminder

This chapter does *not* re-teach the mechanics of any of these. Term-sheet mechanics live in `startup-finance-fundraising-curriculum`. Contract drafting lives in `startup-operations-governance-curriculum`. Deep waterfall math and preferred-stock economics live in `startup-finance-fundraising-curriculum` mod-104 and mod-106. The endgame lens sits on top: given those mechanics are installed, *which specific choices pre-close optionality?*

## Surface 1: Financing choices

Every dollar of capital comes with terms. The endgame-relevant terms cluster into three sub-surfaces.

### Venture debt covenants

Venture debt is a legitimate financing tool. It is also the single most common source of "we can't do that transaction because our lender's consent is required." A pre-close audit of your venture-debt facility should surface:

- **Change-of-control restrictions.** Most venture-debt facilities require lender consent for a change of control, or accelerate the balance at close, or (in aggressive facilities) impose a make-whole premium that can equal 6–12 months of forward interest. If your endgame includes an acquisition path, this term shapes the negotiating leverage and the effective consideration.
- **Financial covenants.** MRR / ARR floors, minimum cash covenants, revenue-run-rate covenants, and debt-service-coverage ratios can all trip in an operating downturn. A tripped covenant that requires waiver from the lender narrows the options for how to respond to the downturn — you lose the option to *pivot* because the lender may prefer *sell* over *run-lean*.
- **Warrant coverage.** Venture-debt warrants are typically 1–2% of the facility as coverage; they dilute at exit and are often exercised or converted at close. The endgame impact is small in dollar terms but can be non-trivial at very small acquisitions (an aqui-hire).
- **Prepayment penalties.** How costly is it to repay the facility early — e.g., if you want to be debt-free before an acquisition negotiation or an IPO S-1? A prepayment penalty of a few points of the facility is standard; anything more onerous restricts refinancing optionality.

The endgame audit does not necessarily change whether you take venture debt. It changes what you *negotiate* on it and how you sequence it relative to the endgame frame.

### Warrant coverage on convertible instruments

Warrants attached to a convertible note or SAFE (as sweeteners in a distressed extension, or on a bridge round) can produce large dilution at conversion and, in some structures, cash-settlement obligations at change of control that do not align with common shareholders' interests. Audit any outstanding warrants for change-of-control mechanics and for whether they cash-settle or share-settle.

### Secondary-restriction terms

Many term sheets — especially from later-stage growth investors — include restrictions on future secondary sales by common or preferred shareholders, sometimes worded broadly enough that they effectively prevent the company from running a future tender offer without that investor's consent. Others impose ROFRs on secondary sales that are workable but slow. If your endgame frame includes a live secondary option, these terms are the ones to negotiate hardest at the primary financing stage. Once they are signed, they are difficult to remove.

## Surface 2: Cap-table structure

The cap table is a snapshot of every past financing decision. Each of them has an endgame consequence.

### Preference-stack overhang

The most consequential single item. The cumulative liquidation preference stack determines how much of any acquisition price goes to preferred holders *before* common (founders and employees) sees anything, and — for participating preferences — how the residual after the preference is split.

Preference-stack overhang forecloses low-and-mid-range acquisitions from the founder / employee perspective long before it forecloses them from the preferred-holder perspective. A company that has raised $200M cumulative with average 1x non-participating preference has a $200M "waterline" below which common holders see nothing. If the buyer map top-tier is offering in the $150–250M range, that waterline sits *inside* the range and dominates the endgame frame.

The audit item: run the current waterfall at a small set of plausible acquisition prices ($X, $2X, $3X of the cumulative preference stack) and see where common breaks through. If most of the plausible range zeroes out common, the endgame frame is *forced* toward either a much higher acquisition, an IPO (where preferences convert), or a restructuring of the stack before any transaction.

### ROFR and co-sale mechanics

Right of First Refusal and co-sale provisions govern who can transfer shares to whom without triggering counterparty rights. They matter for:

- Founder secondaries — a broad ROFR that captures founder sales requires either investor consent or a formalised waiver process for the founder to sell to a third party.
- Employee tender offers — the ROFR / co-sale structure on the company's charter and stockholders' agreement dictates whether a tender can be run cleanly or requires waivers from multiple parties.
- Change-of-control transactions — most ROFRs have change-of-control exclusions, but some do not; check.

The audit item: for each material class of shareholder, name what ROFRs and co-sale rights attach, and whether they trigger on the endgame path you have ranked highest.

### Drag-along coverage

Drag-along rights let a defined majority of a defined class *force* other holders to participate in an approved sale on the same terms. Without adequate drag coverage, a sale that needs 90% shareholder participation (as most stock-purchase transactions do) can be blocked by a dissenting 15% common holder demanding a premium.

The audit item: your drag-along clause covers what percentage of what classes, and does it survive the current cap table? Old drag-along clauses drafted for smaller cap tables sometimes silently expire in the face of later dilution.

### Preferred-stock protective provisions

Preferred stockholders typically have protective provisions requiring their vote (as a class, or a majority of the class, or a defined "requisite holders" definition) for a change of control, a wind-down, an IPO, or a change to the charter. The audit item: what actions require preferred consent, at what threshold, and how does the current allocation of preferred shares distribute among your investors? A preferred class that has consolidated into two or three investors is easier to move than one distributed across ten.

## Surface 3: Board composition

The board approves every material endgame decision — a sale, an IPO, a wind-down, a material secondary. Board composition therefore constrains which endgame paths are approvable at all.

Three audit dimensions:

### Transaction-committee readiness

If a change of control becomes proximate, most companies form a transaction committee (or special committee if there are interested-party dynamics — mod-109 develops the fiduciary-duty framework). Committee construction is only fast if the board *already has* independent directors with transaction experience.

The audit item: how many current directors would qualify as independent (no material relationship with the company, its investors, or the counterparty in a proximate transaction), and do they have relevant transaction experience? If the answer is "zero" or "one who last did a deal fifteen years ago," a proximate transaction will be slowed by the need to recruit independents onto the board mid-process, which telegraphs to acquirers and shareholders exactly what is happening.

### Independent-director sourcing

Related — where does the board look when an independent seat opens? Founders who have not built relationships in the independent-director world are recruiting into a market at short notice with limited network. Founders who have kept a rolling short-list of 3–5 candidates for future independent seats (former CEOs of comparable companies, former public-company CFOs, category-expert operators) are ready when the seat opens.

`startup-operations-governance-curriculum` owns the ongoing-company governance / board machinery. This module lays the endgame lens on top: an *endgame-ready* board is a board that has one or two independent directors *before* the transaction is proximate, not one that recruits them under time pressure.

### Board size and information rights

Board sizes that were reasonable at seed become unwieldy at growth. Boards of 9+ (increasingly common at multi-round venture-backed companies) are slower to convene, slower to reach consensus, and harder to inform. In a fast-moving transaction, that slowness costs optionality. Similarly, information rights held by non-board investors (observer seats, pro-rata information, protective-provisions veto) can make certain transactions functionally require consent from a larger set than the board.

The audit item: what is the effective decision-making body for a change-of-control, and how many humans does it include? If the answer is >9, the endgame conversation is de facto slower than the calendar you might want.

## Surface 4: Contract terms

Every commercial contract the company signs is a small endgame decision. The audit focuses on three clause categories that most often cause endgame pain.

### Change-of-control clauses

Many enterprise customer contracts, partner agreements, and technology-licensing agreements include change-of-control provisions that give the counterparty rights on assignment. Common flavours:

- *Consent-required assignment.* The counterparty must consent before assignment; consent may be withheld.
- *Auto-terminate on assignment.* The contract terminates automatically at close if assigned.
- *Anti-assignment* full stop. The contract cannot be assigned at all.
- *Change-of-control notice.* Counterparty is entitled to notice but has no consent right.

At buy-side commercial diligence (mod-105), the acquirer will inventory these clauses across your customer contracts. Every consent-required or auto-terminate clause in a top-tier customer contract discounts the effective ARR the acquirer will pay for. A concentrated customer base with restrictive change-of-control clauses can cut deal value materially.

The audit item: run a report against your CLM (or your Google Drive of PDFs, if that is what you have) categorising every commercial contract by the change-of-control flavour. Any material customer with an assignment-restrictive clause should be a candidate for renegotiation at the next renewal — not necessarily removed, but understood.

### MFN triggers

Most-Favoured-Nation clauses in enterprise contracts commit you to offer the customer terms no less favourable than you offer any other. In an M&A context, an acquirer offering discounts to their existing customer base can trigger MFN cascades across your acquired book that materially reprice contracts you thought were fixed. Similarly, an MFN in a partnership contract can constrain the acquirer's future dealings with competitors.

The audit item: identify all MFN clauses across the commercial-contract base and, for each, ask "would an acquisition trigger this in an unfavourable way?"

### Most-favoured-customer effects (implicit)

A customer that has a public commitment to being the "lead adopter" or "reference customer" for your product may have soft (non-contractual) claims on early access, roadmap influence, or reciprocity that the acquirer will not honour. An acquisition that shifts the product's roadmap can produce a public loss of a reference customer, which materially reprices your ARR going forward.

This is not usually captured in a specific clause. The audit item is to identify the top 5–10 reference customers whose relationship depends on non-contractual expectations, and to name explicitly what would happen to those relationships under each candidate endgame path.

## The audit as a recurring practice

None of these audits is expensive to run. All of them are usually left un-run because no one owns the endgame lens on operating decisions.

A working practice:

- **Annual pre-endgame audit.** Once a year, the CFO / GC / SVP-Corp-Dev (or founder-CEO if you don't have those seats) walks through the four surfaces and produces a one-page summary of *what has been pre-closed by past decisions* and *what should be surfaced at the next board meeting.*
- **Point-in-time audit before signing.** Before signing a term sheet, a venture-debt facility, a large enterprise contract, or accepting a director candidate, run the specific decision through the four-surface frame: does this pre-close a future endgame option, and is that acceptable given the current ranking?
- **Post-transaction retro.** When a transaction (financing, secondary, acquisition, IPO) closes, note which of the four surfaces produced friction. That signal informs which audit deserves more attention next cycle.

## An example: the "we're stuck" post-mortem

A common failure pattern: a growth-stage founder-CEO wants to explore acquisition. They call their board, discover that (a) the largest venture-debt lender's consent is required and will cost 6–9 months of forward interest to prepay, (b) the drag-along threshold is set at 90% of preferred *and* 66% of common combined, and the current common allocation makes 66% hard, (c) the two most likely strategic acquirers both have change-of-control clauses in their largest customer contract with you that let them terminate on assignment, and (d) the current board has no independent directors with transaction experience, so a special committee cannot be formed without new director recruitment.

Any one of these is manageable. All four at once is what "we're stuck" looks like. Each was a defensible decision at the time it was made — the venture debt got the company through a hard quarter, the drag-along was standard NVCA language, the customer contract was accepted because "we needed the deal," and the board composition simply reflected the fact that no one had prioritised bringing on independents.

The audit exists so that this stack of decisions is *visible* before it becomes binding. The remedy is rarely "undo them all"; the remedy is to see the trade-offs clearly enough that the board is deliberately choosing which optionality to preserve and which to trade away.

## Summary

Endgame optionality is preserved or pre-closed one operating decision at a time. Four surfaces need periodic audit — financing choices (venture-debt covenants, warrant coverage, secondary restrictions), cap-table structure (preference-stack overhang, ROFR / co-sale, drag-along, protective provisions), board composition (transaction-committee readiness, independent-director sourcing, board size), and contract terms (change-of-control clauses, MFN triggers, implicit most-favoured-customer effects). An annual pre-endgame audit and a point-in-time audit before every material signing is enough to keep the frame honest. The failure mode is not any single decision; it is the accretion of small, defensible decisions that in aggregate have already picked an endgame the founder never explicitly chose.
