# Chapter 7 vs. Chapter 11 — Trustee Liquidation vs. Debtor-in-Possession Reorganisation

## Why this matters

For most venture-backed shutdowns the framework in chapter 1 points to an Assignment for the Benefit of Creditors and chapter 2 develops that branch. But a specific subset of shutdowns points to federal bankruptcy — either because the automatic stay of 11 U.S.C. §362 is required to stop a creditor collection action the company cannot otherwise contain, because a specific buyer requires "free and clear of liens and interests" title under 11 U.S.C. §363(f) that an ABC cannot deliver in the same statutory form, because the pre-petition period contains transactions that will be scrutinised by a trustee regardless (and a fair-process Chapter 7 is preferable to being forced there by an involuntary petition), or because the case is materially cross-border and Chapter 15 recognition of a foreign proceeding is the operative device.

When the mechanism is federal bankruptcy, the sub-choice is Chapter 7 vs. Chapter 11 — and within Chapter 11, sub-choices among an operating-emergence plan (rare for venture-backed startups), a Chapter 11 §363 sale followed by a liquidating plan or conversion to Chapter 7, and a pre-packaged Chapter 11 with pre-negotiated creditor treatment. This chapter installs the vocabulary and the decision structure at the depth a founder-CEO, CFO, and GC need to work with restructuring counsel as informed principals. The mechanics beyond that depth — the day-to-day debtor-in-possession financial reporting, the specific case-administration workflow, the trustee-interaction discipline — belong to a future `startup-restructuring-controllership` sub-track.

> Reminder: filing a bankruptcy petition is a specific legal act with immediate and irreversible consequences. Every live consideration of Chapter 7 or Chapter 11 engages specific bankruptcy counsel (a firm with a dedicated restructuring practice — the practitioner canon includes Weil, Kirkland, Skadden, Latham, Sullivan & Cromwell, Simpson Thacher, Wachtell, Paul Weiss, Davis Polk, Cleary, Milbank, Akin, Willkie, Ropes & Gray, Sidley, Jones Day, and several others for large cases; and firms like Pachulski Stang Ziehl & Jones, Levene Neale, Sheppard Mullin, and Sheppard Mullin's specific California mid-market bankruptcy practice for mid-market cases). This chapter is what you read before those engagements, not a substitute for them.

## The Bankruptcy Code in one paragraph

Title 11 of the United States Code (the "Bankruptcy Code") is the federal framework for insolvency proceedings. Chapter 1 (general provisions), Chapter 3 (case administration), and Chapter 5 (creditors, the debtor, and the estate) apply to all cases. The specific chapters that create particular types of case are Chapter 7 (liquidation), Chapter 9 (municipality), Chapter 11 (reorganisation), Chapter 12 (family farmer), Chapter 13 (individual with regular income), and Chapter 15 (ancillary and cross-border). For a venture-backed corporate shutdown, only Chapters 7, 11, and 15 are typically relevant. Every case is filed in the specific US Bankruptcy Court for a specific district (typically the district where the debtor is incorporated or where its principal place of business is located; venue rules are set by 28 U.S.C. §1408). The filing establishes the estate (11 U.S.C. §541 — broadly, "all legal or equitable interests of the debtor in property as of the commencement of the case"), triggers the automatic stay (§362), and installs the specific case administrator (a trustee in Ch 7; a debtor-in-possession or, in some cases, a trustee in Ch 11).

## The automatic stay

The single most operational feature of a bankruptcy filing: §362(a) automatically stays "the commencement or continuation" of virtually all pre-petition collection actions against the debtor or the estate the moment the petition is filed. It stops lawsuits, foreclosures, self-help repossession by secured creditors, government-agency collection actions (subject to specific exceptions in §362(b) for regulatory or police-power actions), setoff by counterparties, and enforcement of judgments.

The automatic stay is the primary functional reason to file Chapter 7 or Chapter 11 rather than run an ABC when there is a specific creditor whose collection action the company cannot manage informally. An ABC does not deliver a statutory automatic stay — the assignee's possession of the assets gives some practical protection, but a persistent creditor can still bring an action against the (now empty) shell company or against specific pre-assignment transactions. The automatic stay stops the action cold.

Exceptions to the stay under §362(b) that a shutdown-planning session should surface:

- Criminal proceedings against the debtor.
- Government-agency regulatory or police-power actions (with a specific carve-out that has been litigated extensively — see, e.g., the analysis of environmental enforcement under §362(b)(4)).
- Certain tax proceedings (though collection actions on assessed taxes are stayed).
- Perfection of certain security interests as of the date they were acquired.

A creditor can also seek "relief from stay" under §362(d) — most commonly a secured creditor whose collateral is depreciating without adequate protection.

## Chapter 7 — trustee-controlled liquidation

The company files a voluntary petition under Chapter 7. The petition is a specific set of forms (Official Forms 201–207 for a corporate debtor; verify the current forms at <https://www.uscourts.gov/services-forms/bankruptcy/bankruptcy-forms>) that require detailed schedules of assets, liabilities, executory contracts, unexpired leases, statements of financial affairs, and payroll and other operating information. Preparing the petition thoroughly takes 4–8 weeks; an emergency filing can be done in days but with a follow-up amendment period.

### The interim trustee and the §341 meeting

Upon filing, the US Trustee (a division of the Department of Justice that supervises bankruptcy administration; not the same as the "case trustee") appoints an interim trustee under 11 U.S.C. §701. The interim trustee is drawn from a panel of professional trustees in the district. Between filing and the §341 meeting of creditors, the interim trustee reviews the schedules and begins the estate administration.

Section 341 requires the debtor's representatives (typically the CEO or CFO) to appear at a specific meeting of creditors, under oath, to answer questions from the trustee and any creditors who choose to appear. The meeting is scheduled 21–40 days after the filing (Fed. R. Bankr. P. 2003). Creditors then have an opportunity to elect a case trustee under §702; in most Chapter 7 cases the interim trustee continues as the case trustee.

### Trustee duties under §704

The trustee's statutory duties under 11 U.S.C. §704(a) include:

- Collecting and reducing to money the property of the estate.
- Being accountable for all property received.
- Ensuring that the debtor performs its remaining intent (e.g., surrenders any collateral to secured creditors).
- Investigating the financial affairs of the debtor.
- Examining proofs of claim and objecting to allowance of any claim that is improper.
- Opposing the discharge of the debtor if advisable (for a corporate debtor, there is no discharge under §727(a)(1) — that is specific to individual debtors).
- Furnishing information about the estate on request.
- Filing a final report and final account of the administration of the estate.

The specific duty to *investigate* is what makes Chapter 7 different from an ABC on the D&O-exposure axis. The trustee will look at pre-petition transactions and, where warranted, bring avoidance actions.

### Avoidance actions

Two specific statutory powers of the trustee under Chapter 5 of the Bankruptcy Code:

- **§547 — preferences.** Any transfer of an interest of the debtor in property (i) to or for the benefit of a creditor, (ii) on account of an antecedent debt, (iii) made while the debtor was insolvent, (iv) made within 90 days before the filing (or within 1 year for a transfer to an *insider* — a specific defined term in §101(31) that includes officers, directors, and controlling stockholders of a corporate debtor), (v) that enables the creditor to receive more than the creditor would have received in a Chapter 7 case had the transfer not been made. Preference actions typically seek to claw back payments made to specific creditors in the 90-day / 1-year period so those payments can be redistributed to the estate.
- **§548 — fraudulent transfers.** Any transfer made or obligation incurred within 2 years before the filing (extended by §544(b)'s reachback into state fraudulent-transfer law, which is typically 4 years) that was either (i) made with actual intent to hinder, delay, or defraud creditors, or (ii) constructively fraudulent (made for less than reasonably-equivalent value while the debtor was insolvent or became insolvent as a result). Fraudulent-transfer actions are particularly relevant when there have been transfers to insiders, non-arm's-length sales of assets, or dividends to stockholders in the pre-petition period.

Both actions are the trustee's to pursue. The trustee's ability to recover on them can materially increase the estate's distributable value — which sounds good but also means specific pre-petition counterparties (including possibly insiders) will be defendants in adversary proceedings during the case.

### Chapter 7 timeline

The typical timeline:

- **Day 0.** Petition filed.
- **Day 0 + up to 7 days.** Interim trustee appointed.
- **Day 21–40.** §341 meeting of creditors.
- **Day 90.** Deadline for filing proofs of claim (may vary — set by Fed. R. Bankr. P. 3002).
- **Months 3–6.** Estate administration, asset liquidation, avoidance-action review.
- **Months 6–18.** Continued administration, asset sales, claims objections, avoidance-action prosecution.
- **Months 12–24.** Final report and account, closing of the case.

Distributions to creditors typically begin 6–12 months in and continue through the case; interim distributions are possible if the trustee has enough on hand.

### When Chapter 7 is the right mechanism

- The company has significant pre-petition transactions that will be scrutinised regardless (a Chapter 7 is preferable to being forced into a Chapter 7 by an involuntary petition, and preferable to an ABC assignee finding the same transactions and turning them over to a subsequent Chapter 7 trustee).
- The automatic stay is specifically needed and no §363 sale is planned.
- The estate is too complex for a self-managed wind-up but not sufficient to sustain the cost of Chapter 11.
- The board and counsel judge that the trustee-controlled process is preferable to a debtor-in-possession process (e.g., because the officers and directors have exhausted their capacity to run the wind-up, or because a specific investigation is likely to be more credible when run by an independent trustee).

## Chapter 11 — debtor-in-possession reorganisation

The company files a voluntary petition under Chapter 11. The automatic stay fires. Unlike Chapter 7, no trustee is appointed by default — the debtor remains in possession of the estate as a *debtor-in-possession* (DIP) under 11 U.S.C. §1107 and continues to operate the business (subject to court oversight and, for material transactions, court approval).

### The DIP and the first-day motions

The DIP's first substantive act after filing is a set of *first-day motions* — requests to the court, filed on or shortly after the petition date, for authority to take specific actions that keep the business running through the early days of the case. Typical first-day motions include:

- Authority to use existing cash management systems.
- Authority to pay pre-petition wages and benefits to employees (a "critical wage" order — usually granted because keeping the workforce is critical to preserving value).
- Authority to pay pre-petition taxes required to be paid (e.g., trust-fund taxes withheld from employees).
- Authority to honour certain customer programmes and warranty obligations.
- Authority to maintain existing bank accounts.
- Authority to obtain DIP financing (if a DIP lender is providing post-petition financing).
- Authority to use cash collateral of secured lenders (with adequate protection).

The first-day motions are typically heard on the first or second business day after filing. Well-prepared cases have the motions drafted and ready to file with the petition.

### DIP financing

Post-petition financing to fund the case. A DIP lender extends new credit to the debtor with a specific priority (typically a super-priority administrative expense claim under 11 U.S.C. §364(c)(1), and often a lien on unencumbered estate assets under §364(c)(2) or a priming lien on encumbered assets under §364(d) with adequate protection to the primed lienholder). DIP financing is what allows a Chapter 11 debtor to keep operating through the case.

For a venture-backed startup filing Chapter 11 as a §363-sale vehicle, DIP financing is often not needed if the case is short and the estate has enough cash to run through the sale. For a longer operating Chapter 11, DIP financing is typically required.

### The Section 363 sale — the dominant Chapter 11 pattern for venture-backed shutdowns

The most common shape of a Chapter 11 for a venture-backed startup is a *§363 sale* — the DIP sells substantially all its assets to a buyer, free and clear of liens and interests under §363(f), with the sale approved by a specific court order after a market-check auction. The proceeds are distributed under a subsequent liquidating plan or (in some structures) the case is converted to Chapter 7 for distribution.

The §363 sale process:

- **The sale motion.** The DIP files a motion seeking authority to sell substantially all its assets. The motion identifies the proposed buyer (the *stalking horse*), the proposed purchase price, the bidding procedures for competing bids, and the timeline.
- **Bidding procedures order.** The court approves the specific bidding procedures — the minimum overbid increment (typically 2–5% above the stalking-horse bid), the bidder-qualification requirements (deposit, financial-capacity showing, non-contingent bid), the auction date, and any bid-protection provisions for the stalking horse (break-up fee typically 2–4% of the purchase price; expense reimbursement typically capped at a specific amount).
- **The marketing period.** Between the bidding-procedures order and the auction, the DIP (typically through an investment banker retained under §327) markets the assets to potential buyers.
- **The auction.** If multiple qualified bidders emerge, an auction is held. The winning bidder is identified.
- **The sale hearing.** The court holds a hearing to approve the sale to the winning bidder. If approved, a sale order is entered under §363(b) authorising the sale and under §363(f) providing that the sale is free and clear of liens and interests.
- **Closing.** The sale closes; the purchase price is delivered to the DIP.

The specific value of §363(f) — the free-and-clear feature — is that the buyer takes the assets without the encumbrances that would otherwise attach. This is materially different from an ABC sale, where the assignee sells subject to whatever encumbrances the assets carry. For assets with complex encumbrance shapes (patents with recorded security interests, contracts with anti-assignment clauses that §365(f) can override) the §363(f) machinery is often the decisive advantage.

### The plan of reorganisation

The core Chapter 11 document. A plan under 11 U.S.C. §1123 divides claims and interests into classes, specifies the treatment of each class, and describes how the plan will be executed. Confirmation of the plan under §1129 requires that:

- The plan complies with applicable provisions of the Bankruptcy Code.
- The plan has been proposed in good faith.
- Each class has either accepted the plan (majority in number and two-thirds in amount of claims voting) or is being paid in full or is unimpaired.
- The plan is *feasible* (§1129(a)(11)) — that is, confirmation is not likely to be followed by liquidation or the need for further reorganisation (unless the plan itself provides for liquidation).
- The best-interests-of-creditors test is met (§1129(a)(7)) — each dissenting creditor receives at least as much as it would in a Chapter 7 liquidation.

*Cramdown* under §1129(b) allows a plan to be confirmed over the dissent of an impaired class if the plan does not "discriminate unfairly" against the class and is "fair and equitable" — the specific tests turn on whether senior classes are being paid in full before junior classes receive anything (the absolute priority rule).

For a venture-backed §363-sale-followed-by-liquidating-plan case, the plan is a specific short document that distributes the sale proceeds to creditors in priority order and dissolves the debtor. For an operating-emergence Chapter 11, the plan is a longer document that restructures the debtor's liabilities and defines the post-emergence capital structure.

### The pre-packaged and pre-negotiated Chapter 11

A *pre-packaged* Chapter 11 is one where the debtor solicits votes on the plan *before* filing the petition — the debtor negotiates with the key creditor constituencies, drafts the plan and disclosure statement, distributes them, collects votes, and only then files the petition with the plan and votes already secured. Confirmation can happen 30–45 days after filing.

A *pre-negotiated* Chapter 11 is a lighter version where the debtor has pre-filing agreements-in-principle with the key constituencies but has not solicited votes; votes are solicited post-filing. Confirmation typically takes 90–180 days.

For a venture-backed startup with a specific creditor constituency (a specific secured lender, a specific set of noteholders), the pre-packaged or pre-negotiated Chapter 11 can compress the case timeline materially. For a startup without a concentrated creditor constituency, the pre-packaged pattern typically does not apply because there is no one to pre-negotiate with.

### Chapter 11 timeline

- **Day 0.** Petition filed with first-day motions.
- **Day 1–2.** First-day hearing; interim orders on first-day motions.
- **Day 21–40.** §341 meeting of creditors.
- **Day 30–60.** Committee formation (creditors' committee typically formed under §1102).
- **Weeks 4–12.** For a §363-sale case: bidding procedures approved, marketing period, auction, sale hearing, closing.
- **Months 3–9.** For a longer §363 case: same steps but with more marketing time.
- **Months 6–18.** For a plan case: plan drafting, disclosure-statement approval, plan solicitation, confirmation hearing.
- **Months 12–24+.** For a large operating-emergence case.

### The creditors' committee

For most Chapter 11 cases, a creditors' committee is formed under 11 U.S.C. §1102 — typically composed of the seven largest unsecured creditors willing to serve. The committee has statutory rights: to be consulted on major decisions, to retain counsel and financial advisors (paid by the estate under §328), to investigate the debtor's affairs, and to be heard on any matter in the case.

The committee is a *creditor advocacy* institution. Its interests are aligned with maximising creditor recovery, which can put it in tension with the DIP's decisions (particularly on DIP-financing terms, sale-process timelines, and management retention). For a small venture-backed case, the committee may not be formed if unsecured creditors are not sufficiently interested; for a larger case, the committee is a significant institutional counterparty for the DIP.

### When Chapter 11 is the right mechanism

- A specific §363-sale-free-and-clear requirement that only bankruptcy court can deliver.
- A specific creditor constituency that requires pre-negotiated treatment through a plan (rare for venture-backed startups).
- A specific operating business that can emerge from reorganisation as a going concern (rare for venture-backed startups).
- Cross-border cases where the automatic stay and the plan-confirmation machinery provide the necessary discipline.

## Chapter 15 — cross-border cases

Chapter 15 of the Bankruptcy Code implements the UNCITRAL Model Law on Cross-Border Insolvency. It provides for US recognition of a *foreign main proceeding* (a foreign insolvency proceeding in the debtor's centre of main interests, typically the country of the debtor's registered office) or a *foreign nonmain proceeding*. Once a foreign proceeding is recognised as a foreign main proceeding, specific relief applies automatically: the automatic stay of §362 attaches to the debtor's US assets, the foreign representative can operate the debtor's US business, and the US court can assist in the administration of the foreign proceeding.

For a venture-backed startup with a specific cross-border shape (e.g., a Delaware-incorporated parent with a UK subsidiary, or a US-headquartered company with material assets and creditors in Europe or Asia), Chapter 15 can be the operative device that coordinates the US aspects of a foreign insolvency proceeding.

The mechanism is technical, and most venture-backed startups do not need it. It is included here because the reference to "Delaware Chapter 15" in some practitioner discussions is a common shorthand that conflates the state-law ABC alternative (which is not Chapter 15) with the actual Chapter 15 device. If your case has a genuine cross-border dimension, counsel with cross-border restructuring experience is required.

## Comparing Chapter 7 and Chapter 11 on the six axes

Re-anchoring to the framework from chapter 1:

- **Cost.** Chapter 7 professional fees for a mid-sized venture-backed case: trustee compensation under §326 (percentage of moneys disbursed) plus trustee's professional fees (counsel, accountant) typically total 5–15% of the estate. Chapter 11 professional fees: DIP counsel, financial advisor, banker for §363, committee counsel, US Trustee fees — routinely $500K–$2M for a modest case, several million for a larger one. Chapter 11 is materially more expensive than Chapter 7.
- **Speed.** Chapter 7: 6–24 months from filing to case closure. Chapter 11 with §363 sale: 3–9 months to sale close; case closure often 12–24 months later. Pre-packaged Chapter 11: 30–90 days to confirmation. Chapter 11 is not necessarily slower than Chapter 7 for the sale step, but the full case is typically longer.
- **Creditor treatment.** Chapter 7: strict statutory priority under §507; distributions net of trustee compensation and professional fees. Chapter 11: statutory priority under §507 with negotiated flexibility through the plan; distributions net of the (typically higher) professional-fee spend. For most venture-backed cases with no going-concern value the professional-fee gap is a direct reduction in creditor recovery.
- **D&O exposure.** Chapter 7: trustee-driven investigation and avoidance-action prosecution. Chapter 11 (DIP): avoidance-action powers held by the DIP (which is nominally the debtor's management) or by the creditors' committee (which typically requires standing); trustee appointed under §1104 only for cause. Chapter 11 provides marginally more control over the investigation but does not immunise pre-petition transactions.
- **Employee outcomes.** Chapter 7: wages within priority cap ($15,150 as of 2024, verify at <https://www.uscourts.gov/services-forms/bankruptcy/bankruptcy-basics/priority-claims>) are priority claims; post-petition wages are administrative expenses. Chapter 11: typically pays "critical" pre-petition wages under a first-day order; post-petition employees paid as administrative expenses; KERPs and KEIPs under §503(c) can retain key employees during the case (with court approval). Chapter 11 typically produces better short-term employee outcomes because of the first-day wage order and the retention plans.
- **IP disposition.** Chapter 7: trustee runs the sale; less flexibility, more procedural. Chapter 11: §363 sale with free-and-clear machinery under §363(f); more flexibility, more expensive process. The IP disposition axis is the specific reason to file Chapter 11 rather than Chapter 7 when a buyer requires the free-and-clear feature.

## The specific interaction with insurance

The D&O policy in place at the time of the filing is a specific and highly-litigated question. If the policy has been renewed just before the filing on a claims-made basis, post-petition claims (which are common — securities claims, breach-of-fiduciary-duty claims, wrongful-termination claims) may be covered under the policy. If the policy expires or is not renewed during the case, tail coverage (chapter 8) becomes essential to catch post-shutdown claims.

The bankruptcy court can approve the payment of policy premiums as an ordinary-course expense under §363(c) or as a specific first-day order. In some cases the D&O tail is procured pre-petition and paid for by the company (as part of the pre-petition cleanup); in other cases it is procured post-petition with court approval.

The tail is not something you buy after the shutdown is complete — chapter 8 develops the timing rules — and it is not something a Chapter 7 trustee or a DIP will spontaneously procure for the benefit of former directors and officers. The founder-CEO, CFO, GC, and board need to raise the tail-procurement question early and specifically.

## When to file Chapter 7 vs. Chapter 11 — a compressed decision

The compressed decision tree:

1. **Is a §363-sale-free-and-clear requirement present?** If yes, Chapter 11. If no, continue.
2. **Is the automatic stay specifically needed for a creditor action the company cannot otherwise manage?** If yes, Chapter 7 or Chapter 11 — go to question 3. If no, an ABC may still be the right mechanism; reconsider.
3. **Are there specific pre-petition transactions that will be scrutinised regardless?** If yes, and no §363-sale requirement, Chapter 7 is often preferable (independent trustee, cleaner investigation optics). If no, and no §363-sale requirement, either Chapter 7 or Chapter 11 works — cost typically pushes to Chapter 7.
4. **Is there a specific pre-negotiated creditor treatment that requires the plan-confirmation machinery?** If yes, pre-packaged Chapter 11. If no, and no §363-sale, Chapter 7.
5. **Is the case cross-border?** If yes, Chapter 15 recognition of the foreign main proceeding is likely the primary framework, with a Chapter 7 or Chapter 11 as an ancillary US case if the debtor has material US assets.

## Common failure modes

- **Filing Chapter 11 without a specific reason.** The default assumption "Chapter 11 preserves optionality" is wrong for venture-backed startups without going-concern value. Chapter 11 preserves the optionality to confirm a plan of reorganisation; if no such plan is realistic, the mechanism is expensive process consuming what would be creditor recovery.
- **Filing Chapter 7 to hide from a trustee-driven investigation.** Chapter 7 *invites* a trustee-driven investigation. If the pre-petition period contains transactions the debtor would prefer not be scrutinised, no bankruptcy chapter provides cover; ABC provides marginally more privacy but not immunity.
- **Missing the DIP-financing window.** For a Chapter 11 case that requires post-petition financing, DIP-lender negotiation must begin before the filing — not after. A DIP-lender-less Chapter 11 that runs out of cash mid-case is a specific and destructive failure mode.
- **Underestimating the case-administration cost of Chapter 11 for the DIP's officers.** The DIP-in-possession requires officer time — testimony, motion practice, monthly operating reports, committee meetings — that materially exceeds an ABC's demand on officer time. The board and the officers need to be willing to make that time commitment.

## What the choice produces

A well-executed Chapter 7:

- Independent-trustee-driven wind-up.
- Statutory priority distributions.
- Adversary-proceeding investigation of pre-petition transactions with recoveries added to the estate.
- Case closure typically 12–24 months after filing.
- Officers and directors displaced from the wind-up shortly after filing.

A well-executed Chapter 11 §363-sale:

- Buyer receives free-and-clear title to the assets under §363(f).
- Sale proceeds distributed under a subsequent liquidating plan.
- Case closure typically 6–18 months after filing.
- DIP officers remain involved throughout; time commitment is substantial.

## Summary

Federal bankruptcy — Chapter 7 or Chapter 11 — is the mechanism when the automatic stay of §362 is required, when a §363-sale-free-and-clear feature is specifically needed by a buyer, when specific pre-petition transactions favour a trustee-driven investigation, or when the case is materially cross-border and Chapter 15 is the operative device. Chapter 7 is cheaper and simpler; Chapter 11 is more expensive but provides the DIP structure, the §363 sale machinery, and the plan-confirmation flexibility. For most venture-backed shutdowns the framework in chapter 1 does not point here — it points to ABC (chapter 2) — but when it does, the specific decisions in this chapter shape whether the mechanism runs to its best-case outcome or its worst.
