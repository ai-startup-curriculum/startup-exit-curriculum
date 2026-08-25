# Executing an Assignment for the Benefit of Creditors (ABC)

## Why this matters

For the majority of venture-backed shutdowns where the informal-wind-down is off the table (creditors will be left short) and no specific §363-free-and-clear requirement forces Chapter 11, the mechanism is an Assignment for the Benefit of Creditors — a state-law process in which the company transfers all its assets to a specific third-party assignee who then liquidates them and distributes the proceeds to creditors under a priority waterfall. ABC is the default because the alternatives cost more and take longer with no better creditor outcome; but it is a *decision*, not a default, and the choreography of executing it — which assignee to retain, how to structure the assignment agreement, when and how to give notice to creditors and stockholders, how to run the asset-disposition process, how to interpret the priority-of-claims waterfall, how the specific state's statutory framework (California's Code of Civil Procedure §493 for wage claims, Delaware's trust-law framework, other states' hybrid frameworks) modifies the pattern, and how an ABC can serve as a precursor to a Section 363 sale in a subsequent Chapter 11 — is the substance of running one well.

This chapter installs the choreography. The prerequisite is chapter 1's decision framework; the sequel is chapter 3's Chapter 7 / Chapter 11 comparison for the cases where ABC is not the right mechanism. The chapter also assumes the reader will be working with specific restructuring counsel and a specific assignee firm; it is not a substitute for those engagements, but it is the reading that lets the founder-CEO, CFO, and GC engage those firms as informed principals rather than as clients being educated.

> Reminder: ABC statutory frameworks vary materially by state. California has the most-developed statutory and case-law framework (California Code of Civil Procedure §§493, 1800; California Commercial Code Article 9 for the security-interest interaction) and is the venue-of-choice for the majority of Silicon Valley ABCs. Delaware operates ABCs under trust law rather than a dedicated ABC statute; New York, Illinois, Massachusetts, and other states have their own frameworks with meaningful procedural differences. Verify the specific jurisdiction with counsel before applying any pattern in this chapter.

## What an ABC is, in one paragraph

An Assignment for the Benefit of Creditors is a common-law trust device (in states without dedicated ABC statutes) or a statutory device (in states with them) in which a company (the *assignor*) transfers all of its right, title, and interest in its assets to a third party (the *assignee*) under an assignment agreement, in trust for the benefit of the assignor's creditors. Legal title vests in the assignee, who then takes possession, liquidates the assets in an orderly (typically arm's-length) manner, and distributes the proceeds to the creditors in a priority order that broadly tracks bankruptcy priorities but is administered under state (not federal) law. The assignor's directors and officers are largely displaced from the wind-up upon execution of the assignment; the assignee runs it. The company itself continues to exist as a shell entity for some period (typically until state-law post-dissolution claim-period runs, e.g., three years under Delaware §278) but has no operating role.

Two conceptual differences from bankruptcy are worth naming up front. First, the ABC is not a court-supervised process in the same way a bankruptcy is — in California, for example, a General Assignment can be executed and effective without any court filing (though the assignee will typically file a Superior Court "notice of general assignment" as a public record). This is a feature (speed, cost, privacy) but also a limitation (no automatic stay, no discharge, no free-and-clear machinery, no formal proof-of-claim adjudication process). Second, the ABC is a *voluntary* mechanism initiated by the company; there is no involuntary ABC petition the way there is an involuntary bankruptcy petition under 11 U.S.C. §303.

## Choosing the assignee

The first substantive decision. The assignee is the entity that will run the wind-up; getting this right is the highest-leverage decision in the ABC.

### The main firms

The venture-backed ABC market is concentrated in a small number of specialist firms. Each has a specific reputation, geographic footprint, and pattern. Selection is largely a matter of jurisdiction fit, deal-size fit, sector fit, and cultural fit with the specific company and its board. In alphabetical order:

- **Armanino LLP** — an accounting and business advisory firm with a Restructuring & Turnaround Services practice that acts as ABC assignee in California and other jurisdictions. Sector coverage is broad (technology, life sciences, consumer, industrials). <https://www.armanino.com/services/restructuring-turnaround/>
- **Development Specialists, Inc. (DSI)** — a Chicago-headquartered restructuring firm with a national ABC practice; long track record on venture-backed shutdowns and cross-border matters. <https://www.dsi.biz/>
- **FTI Consulting — Corporate Finance & Restructuring** — a global firm with a large restructuring practice; typically engaged on larger and more-complex ABCs (mid-market to large), and often when the shutdown has a specific international dimension. <https://www.fticonsulting.com/services/corporate-finance-restructuring>
- **Sherwood Partners** — the venture-backed-shutdown specialist in California; probably the single most-frequent assignee for Silicon Valley technology-company ABCs over the last two decades, with a specific reputation for running the Sherwood-managed asset sale as a Section-363-style process at speed. <https://sherwoodpartners.com/>
- **SierraConstellation Partners** — a Los Angeles-headquartered restructuring firm with a growing ABC practice, particularly in California-based technology and consumer shutdowns. <https://sierraconstellation.com/>

Other firms operate in the space (Alvarez & Marsal, AlixPartners, and Berkeley Research Group all have restructuring practices; regional boutique firms serve local markets in states outside California), but the five above are the ones venture-backed founder-CEOs and CFOs most commonly encounter as candidates for the assignee role.

### The selection criteria

The decision criteria applied by a well-advised board and counsel:

- **Jurisdiction fit.** California ABC market and non-California ABC markets are meaningfully different. Sherwood Partners, SierraConstellation, and Armanino are California-centric. DSI and FTI are national. If the company is Delaware-incorporated but operating primarily in California with California employees and California assets, the California statutory framework typically governs the wind-up and a California-experienced assignee is preferable.
- **Deal-size fit.** Some assignees are set up for a $2M-remaining-cash / 20-employee shutdown; others for a $50M / 200-employee shutdown. Match the firm's typical case-size to yours.
- **Sector fit.** A software / SaaS company shutdown is different from a life-sciences shutdown (patent estate management, ongoing clinical-trial obligations, FDA notice obligations), which is different from a hardware / IoT shutdown (inventory disposition, contract-manufacturer relationships), which is different from a consumer shutdown (brand and inventory). Ask the candidate assignee for specific recent references in your sector.
- **IP-sale process capability.** The single most important operating capability the assignee brings is the ability to run a fast, arm's-length sale of the residual IP and any operating-team-and-customer-book. Ask specifically about (a) the assignee's proprietary buyer network in your sector, (b) the typical timeline from assignment to sale close (Sherwood, for example, has a documented pattern of running the sale in 2–6 weeks post-assignment), (c) the assignee's approach to a founder-led purchase of assets from the estate (the "founder-buys-back-the-IP" spin-out pattern is common and defensible if run properly).
- **Fee structure.** Assignees are typically paid a percentage of asset recoveries plus expenses, sometimes with a floor / cap or a specific fixed-fee minimum. Get the fee proposal in writing before signing the assignment agreement.
- **Coordination with counsel.** The assignee will coordinate closely with the company's restructuring counsel throughout the wind-up. Ask both parties whether they have worked together before and how they typically divide labour.

### The counsel-and-assignee coordination

The founder-CEO / CFO / GC does not select the assignee in a vacuum. The typical pattern is:

1. Restructuring counsel is retained first (Cooley, Wilson Sonsini, Fenwick, Gunderson, Latham, Orrick, DLA Piper, Sheppard Mullin, and several others all have specific ABC / wind-down practices).
2. Counsel presents 2–3 assignee candidates matched to the profile.
3. The company interviews the candidates on a compressed timeline (typically the same week).
4. The board approves the selected assignee via a board resolution that also authorises the assignment.
5. Counsel drafts the assignment agreement in coordination with the selected assignee.
6. The assignment is executed and the wind-up begins.

Compressing steps 1–5 into 2–3 weeks is normal. Compressing into a single week is possible when the runway is very short. Compressing into a single day is a red flag — the company has under-planned, and both counsel and assignee will do worse work under that pressure.

## The assignment agreement

The document that effects the transfer of assets from the company to the assignee. It is a bespoke document — no NVCA template — but has a recurring structure.

### Board authorisation

The board of directors must approve the assignment via a specific resolution. The resolution typically:

- Recites the board's determination that the company is unable to satisfy its obligations as they come due and that an assignment for the benefit of creditors is in the best interests of the company's creditors.
- Approves the selected assignee.
- Authorises the officers (typically the CEO or CFO) to execute the assignment agreement and take all further actions necessary to effect the assignment.
- Approves ancillary actions: payment of any outstanding wage claims through the payroll cutoff, filing of the certificate of dissolution or comparable state-law dissolution act, cancellation of ongoing insurance policies with the exception of the D&O tail (chapter 8), notice to specific counterparties.

Depending on the corporate structure the assignment may also need stockholder approval — for a Delaware corporation, DGCL §275 requires stockholder approval for dissolution but the *assignment* itself can be effected by board resolution; the *dissolution* is a separate act. Counsel will parse this for the specific corporate structure.

### The transfer clause

The core of the agreement is a general grant of "all right, title, and interest of the assignor in and to all of its property, real, personal, and mixed, tangible and intangible, of every kind and description and wherever located." The grant is typically written broadly to cover:

- Cash and cash equivalents.
- Accounts receivable.
- Inventory and physical assets.
- All intellectual property: patents (issued and pending), trademarks (registered and unregistered), copyrights, trade secrets, source code, domain names, brand assets. This grant is what makes IP disposition possible under the assignee.
- Contracts, subject to any restrictions on assignment in the contracts themselves (many commercial contracts have change-of-control or anti-assignment clauses that require counterparty consent).
- Books and records, including the customer database and employee records (subject to specific privacy-law constraints depending on jurisdiction).

Some assets may be specifically excluded — most commonly, the D&O tail policy itself (which is typically procured as a separate transaction just before or contemporaneously with the assignment; see chapter 8) and, in some structures, specific personal-property items that under state law are exempt from creditor claims.

### The assignee's obligations

The agreement sets out the assignee's duties:

- To take possession and control of the transferred assets.
- To hold them in trust for the benefit of the assignor's creditors.
- To administer the estate in a commercially reasonable manner.
- To give notice to creditors and stockholders (see below).
- To liquidate the assets and distribute the proceeds in the priority order specified in the agreement (which typically tracks the state's statutory priority framework and, indirectly, the bankruptcy §507 priorities).
- To provide accounting to creditors on request.
- To indemnify itself (from the estate) for reasonable expenses of administration.

### The assignee's compensation

Explicitly stated in the agreement. Typical structures are:

- A percentage of aggregate distributions or of net recoveries (commonly 5–15% depending on complexity, deal size, and the specific firm's rate card), often with a floor and sometimes a cap.
- Reimbursement of out-of-pocket expenses.
- In some structures, a fixed monthly fee plus success fees for specific asset sales.

Counsel should insist that the compensation structure is transparent and consistent with the assignee's typical rate card, and that it does not create incentives misaligned with maximum creditor recovery (e.g., a structure that heavily rewards speed at the expense of price should be renegotiated).

### The company's covenants

The company covenants to cooperate with the assignee — providing books and records, executing further documents, refraining from acting on behalf of the estate — and typically covenants that the assignment has been duly authorised, that the assignor has disclosed all material assets and liabilities, and that no fraudulent-transfer or preference concerns are outstanding.

### Ancillary documents

The assignment agreement is typically accompanied by:

- A bill of sale for the tangible assets.
- Specific assignments of intellectual property (patent assignments recorded with the USPTO, trademark assignments recorded with the USPTO, copyright assignments recorded with the Copyright Office where applicable).
- Assignment of specific material contracts.
- Notice of general assignment (in California, filed with the Superior Court of the county in which the assignor's principal place of business is located).
- Board resolution and (where required) stockholder consent.

## Notice to creditors and stockholders

Once the assignment is executed, the assignee gives notice to creditors and stockholders. The notice choreography is one of the most-litigated parts of an ABC when it is done poorly — a missed notice can produce a preference claim, a fraudulent-transfer challenge, or a claim by a stockholder that the assignment was ultra vires.

### The notice content

Notice typically includes:

- Identification of the assignor and assignee.
- Date of the assignment.
- Statement that the assignee holds the assets in trust for the benefit of creditors.
- Instructions for filing a proof of claim, including the deadline (a *bar date*, typically 90–180 days from the notice).
- Contact information for the assignee.
- Notice of a claims-resolution process (informal in most ABCs — no formal court adjudication, but the assignee will review, allow, or disallow claims as filed).

### Recipients

Recipients typically include:

- All known creditors — from the accounts-payable ledger, the notes-payable schedule, the leases-and-contracts schedule, any pending-litigation counterparties, tax authorities (federal, state, local), and any other party the assignee or the company identifies as a possible claimant.
- All stockholders — from the cap-table (typically pulled from Carta, Shareworks, Pulley, or the company's stock-administration platform).
- Specific regulators where applicable (state Employment Development Department, state tax authority, and — for regulated sectors — the sector-specific regulator).

### Timing

For a California ABC, notice is typically given within 30 days of the assignment. In other jurisdictions the timing is set by state statute or by the assignment agreement. Counsel will drive the specific schedule.

### The California CCP §493 wage-claim interaction

California Code of Civil Procedure §493 gives wage claimants a specific priority in an ABC — wages earned within 90 days before the assignment and up to a per-claimant cap (currently $12,850 per verify the current amount at <https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?sectionNum=493.&lawCode=CCP>) are entitled to priority. The assignee is required to give specific notice to wage claimants and to process wage claims under the §493 framework rather than the general unsecured-claim process. Missing this step is a common assignee mis-step and is a specific area for counsel review.

## The asset-disposition process

Once notice is given (or in parallel, depending on the assignee's practice), the assignee runs the sale process. This is the most operational phase of the ABC — the phase where the assignee's asset-disposition capability determines how much creditors ultimately recover.

### The typical shape

- **Weeks 1–2 post-assignment.** The assignee takes possession of the assets. Books and records are transferred. Physical assets are inventoried. Data-room preparation begins. Initial outreach to the assignee's proprietary buyer network begins in parallel.
- **Weeks 2–4.** A marketing memorandum (or "confidential information memorandum," CIM) is prepared and circulated to identified potential buyers. Buyer diligence begins. Preliminary bids are received.
- **Weeks 3–6.** Selected buyers are given deeper diligence access. Final bids are received. The assignee selects the winning bid based on price, closing certainty, and (where relevant) other factors like employee retention.
- **Weeks 4–8.** The sale closes. Asset purchase agreement is signed. Purchase price is delivered to the assignee. Assets are transferred to the buyer.

Aggressive timelines are possible — the "melting ice cube" shutdown where key customers or employees will disappear during a delay can be run in 2–4 weeks — but the compression typically costs price.

### The founder-led purchase pattern

A specific and common pattern: the founders, or a subset of the executive team, form a new entity and purchase the residual assets (including IP) from the assignee. This is a defensible transaction *if* the assignee runs a genuine market-check and the founder-led entity's bid is the highest or is otherwise the best-and-final offer. It is not defensible if the assignee simply hands the assets to the founders without a process. When this pattern is anticipated, the assignee should be told at the outset so the market-check can be designed to withstand later scrutiny.

The founder-led purchase can be structured as:

- A cash purchase (with the cash coming from founder personal contribution or from a new investor into the newco).
- A credit-bid (rare in an ABC context because the founders typically do not hold estate claims, but possible in some structures).
- A structured earn-out or contingent-payment structure (where the newco pays a fixed amount at close and a contingent amount based on later revenue — the assignee's fiduciary duty to creditors makes this less common than a straight cash purchase).

### The Section-363-style sale pattern

An ABC sale is not literally a Section 363 sale — that specific statutory device exists only under 11 U.S.C. §363 in a bankruptcy context. But the *procedural pattern* the assignee runs is often modelled on a §363 sale: a "stalking horse" bid establishes a floor price, other bidders are invited to submit competing bids on a specific timeline, an auction is run if there are multiple qualified bidders, the winning bidder closes on the assets. The pattern is well-established and provides the market-check discipline that makes the sale defensible.

## The ABC-as-precursor-to-Chapter-11-Section-363-sale pattern

A specific hybrid pattern worth naming: the ABC runs the sale process and identifies the winning bidder, and then — because the winning bidder requires "free and clear of liens and interests" title under §363(f) that only a bankruptcy court can deliver — the company files a Chapter 11 case, the assignee's identified buyer serves as the stalking horse, and the sale is consummated under §363. This pattern combines the ABC's speed and cost advantages (in identifying and negotiating with the buyer) with Chapter 11's §363(f) machinery (in closing the sale with the buyer's required free-and-clear protection).

The pattern is not universal — it is expensive process on top of an ABC — but it is a live option when the sale requires the specific §363(f) protection. Counsel should raise it early in the ABC process if the buyer's requirements suggest it will be needed.

## The priority-of-claims waterfall

Once the assets are liquidated, the assignee distributes the proceeds. The priority order broadly tracks bankruptcy priorities but is administered under state law and modified by state-specific statutes (California's CCP §493 wage priority, for example).

### The typical order

Broadly, from top to bottom:

1. **Costs and expenses of administration.** Assignee compensation, assignee's counsel fees, assignee's out-of-pocket expenses, expenses of preserving and selling the assets. Paid before any distribution to creditors.
2. **Secured creditors, up to the value of their collateral.** A creditor with a properly-perfected security interest (typically under Article 9 of the Uniform Commercial Code — verify perfection status early) is paid from the proceeds of their collateral, up to the amount of the debt. Any excess proceeds from the collateral flow into the general estate; any deficiency (if the collateral proceeds are less than the debt) becomes a general unsecured claim.
3. **Priority unsecured creditors.** Broadly tracks bankruptcy §507 priorities: certain wage claims (subject to state-specific caps and the §493 interaction in California), certain tax claims (federal, state, local income and payroll taxes), certain benefit-plan contributions, certain trust-fund taxes (which is where the IRC §6672 personal-liability layer discussed in chapter 9 becomes acute).
4. **General unsecured creditors.** Trade creditors, contract counterparties without security interests, judgment creditors without perfected liens, deficiency claims from secured creditors, and any residual claims. Paid pro rata from whatever is left after priority classes are paid in full.
5. **Equity holders.** Preferred stockholders in liquidation-preference order, then common stockholders. In a typical venture-backed shutdown where creditors will not be paid in full, no distribution to equity — including no distribution to preferred stockholders' liquidation preferences.

### The specific implication for founders and investors

In an insolvent shutdown (creditors will not be paid in full), the equity waterfall does not fire. Founders and employees holding common stock receive nothing. Investors holding preferred stock receive nothing on their liquidation preferences from the estate. This is often surprising to founders on their first shutdown — the intuition from prior liquidation-preference math on M&A exits is that "at least the preferred will be paid." In an ABC of an insolvent company, the preferred are just another equity class below all creditors, and there is nothing left after creditors.

The one thing that *can* flow to specific stakeholders in an insolvent shutdown is the sale of *residual IP or other assets* to a founder-led newco (the pattern above) — that is a transaction with the estate, not a distribution to equity, and the founders pay the estate for the assets. The economics of the founder-led newco after the purchase are separate from the ABC.

## The California CCP §493 interaction, in more depth

California CCP §493 is the statutory framework for wage claims in California ABCs. It gives wage claimants a specific priority (wages earned within 90 days pre-assignment, up to a per-claimant cap that indexes over time — verify the current figure at <https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?sectionNum=493.&lawCode=CCP>) that runs ahead of general unsecured creditors and, by statute, is treated similarly to a priority-unsecured bankruptcy claim.

The key operating implications for the ABC:

- The assignee must specifically identify wage claimants from the payroll records and give them the specific §493 notice.
- The wage claims must be processed under the §493 framework, not the general unsecured process.
- Wages beyond the per-claimant cap flow to the general unsecured claims of the same employees.
- California has additional employee-facing statutes (Labor Code §200 et seq. on the general wage-and-hour framework, Labor Code §201 on immediate payment on termination, Labor Code §227.3 on vested-vacation payout, PAGA under Labor Code §2698 et seq.) that overlay the ABC-specific §493 framework. The interaction with PAGA (which allows employees to sue for civil penalties as private attorneys general) is a specific personal-liability watch item for officers — chapter 9 develops this.

## The Delaware alternative

Delaware does not have a dedicated ABC statute. Delaware assignments for the benefit of creditors are executed under Delaware common law and Delaware trust law. The practical differences from a California ABC:

- **Governing law.** The assignment agreement is governed by Delaware law; the assignee's duties are analysed under Delaware trust-law standards rather than under a dedicated ABC statute.
- **Notice.** No statutory notice framework; the assignment agreement will specify a notice process, and counsel will drive the schedule.
- **Wage priority.** No Delaware equivalent to California CCP §493. Wage priority tracks the general priority framework in the assignment agreement (which typically tracks bankruptcy §507 priorities).
- **Public filing.** Delaware assignments are typically not filed with the Court of Chancery in the same way California assignments are filed with the Superior Court. The transaction is more private.

For a Delaware-incorporated company operating in California with California assets and California employees, counsel typically recommends running the ABC under California law with a California assignee, because the operating-and-employee framework is California-governed even though the corporate charter is Delaware. For a Delaware-incorporated company operating in Delaware or in another state without an established ABC framework, Delaware trust law is the workable framework.

The reference to "Delaware Chapter 15" in some practitioner discussions is a slight misnomer — Chapter 15 of the US Bankruptcy Code is the *cross-border* bankruptcy framework for ancillary recognition of foreign insolvency proceedings, not a Delaware-specific state-law device. Chapter 3 develops Chapter 15 in the cross-border context.

## Common ABC failure modes

Five recurring failure modes in ABCs that a well-prepared founder-CEO / CFO / GC watches for:

1. **Assignee selection under pressure.** Selecting the assignee in a compressed timeline (one week rather than three) typically produces a worse selection. If runway forces the compression, at minimum interview more than one candidate and get counsel's written assessment of each.
2. **Missed pre-assignment cleanup.** The 90-day period before the assignment is the window in which preferential payments to insiders, related-party transactions, and non-arm's-length transfers can produce fraudulent-transfer or preference challenges from the assignee, from an involuntary Chapter 7 trustee (if one is later installed), or from creditors. Counsel should review the 90-day period specifically before the assignment executes.
3. **Missed employee obligations.** WARN notice (chapter 4), final-pay obligations under the specific state's Labor Code (chapter 5), PTO payout, COBRA administration. These are the highest-frequency source of officer personal liability post-ABC and should be closed before or contemporaneously with the assignment.
4. **Missed D&O tail procurement.** The D&O tail (chapter 8) must be procured *before* the underlying policy expires at the dissolution or non-renewal. Missing this step leaves post-shutdown claims (which are common and often filed months or years after the assignment) uninsured.
5. **Missed IP disposition planning.** Handing the IP to the assignee without a plan means the assignee runs the sale on the assignee's schedule and market read. If the founders have a specific plan (spin-out, license-back, sale to a specific buyer), it should be discussed with the assignee before the assignment executes so the assignee can incorporate the plan into the sale process (and preserve the arm's-length discipline).

## What the ABC produces

A well-executed ABC produces:

- A closed and dissolved (or in wind-up) company that has satisfied its statutory obligations to creditors under a priority framework.
- A distribution to creditors that is typically greater than they would have received in a Chapter 7 of the same estate (because ABC costs less to run) and greater than they would have received in an informal wind-down (because the assignment focused the disposition process).
- A sale of the operating assets (in most cases) to a buyer who continues to operate the technology or brand in some form, preserving employee optionality and (in some cases) customer continuity.
- A clean handoff to any subsequent workstreams — Chapter 11 if a §363 sale is required, claims-resolution over the following 6–24 months for tail matters, D&O tail responding to post-close claims.
- A specific set of records and process artefacts (the assignment agreement, the notice to creditors, the sale process, the priority waterfall, the distribution schedule) that allow the founders, investors, and board to demonstrate — if later challenged — that the wind-up was run with the discipline the fiduciary framework required.

## Summary

The Assignment for the Benefit of Creditors is the default shutdown mechanism for venture-backed startups when the informal wind-down is off the table and no specific §363-free-and-clear requirement forces Chapter 11. The choreography — assignee selection (Sherwood Partners in California; DSI, SierraConstellation, Armanino, FTI as alternatives), the assignment agreement, notice to creditors and stockholders, the asset-disposition process (often a §363-style sale, sometimes with a founder-led purchase of residual IP), the priority-of-claims waterfall, the California CCP §493 wage-priority interaction, the Delaware trust-law alternative, the ABC-as-precursor-to-a-Chapter-11-Section-363-sale hybrid — is well-understood and executes on a 4–8-week timeline when run well. The next chapter turns to the Chapter 7 / Chapter 11 branches for the cases where ABC is not the right mechanism.
