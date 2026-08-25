# Intellectual-Property Disposition

## Why this matters

For a venture-backed startup at shutdown, the intellectual property estate is often the largest realisable asset — sometimes the only asset with meaningful residual value beyond cash on hand. Patents (issued and pending), trademarks (registered and unregistered), copyrights (in source code, documentation, marketing materials), trade secrets (algorithms, customer lists, technical processes), source code repositories, domain names, and brand assets are the substance of what the company built. The disposition decision — sell to a strategic buyer, assign to investors or founders under a pre-existing agreement, abandon (with the cost implications of forfeited patent-maintenance fees), license back to founders or to a spin-out, transfer to a special-purpose vehicle for later monetisation — is one of the highest-consequence decisions in the shutdown because it is (a) irreversible once made, (b) subject to specific fiduciary-duty and creditor-priority discipline when the company is insolvent, and (c) often the anchor around which the shutdown mechanism itself is chosen.

This chapter installs the five disposition options and the specific facts that push the decision toward each. It is not IP-counsel in miniature — every live shutdown engages specific IP counsel (in-house if there is one, or specialist IP counsel like Fenwick, Wilson Sonsini's IP group, Kilpatrick Townsend, Fish & Richardson, Finnegan, or a boutique firm depending on the specific technology area). The chapter is what the founder-CEO, CFO, GC, and CTO read before that engagement.

> Reminder: IP disposition in a shutdown intersects fiduciary duty (in the zone of insolvency the duty runs to the creditor class, not the stockholder class), fraudulent-transfer doctrine (transfers to insiders for less than reasonably-equivalent value), patent-office and trademark-office procedural rules, and open-source-license compliance obligations. This chapter surfaces the framework; counsel executes the transactions.

## The IP estate — what is being disposed of

Before the disposition decision, name what is actually in the estate. The typical inventory:

### Patents

- **Issued patents.** Patents granted by the USPTO (or foreign patent offices) and currently in force. Each requires payment of maintenance fees at 3.5, 7.5, and 11.5 years post-issuance under 37 C.F.R. §1.20. Missed maintenance fees cause the patent to lapse.
- **Pending applications.** Applications filed but not yet granted. Each has ongoing prosecution costs (office-action responses, examiner interviews, appeals) and specific procedural deadlines.
- **Provisional applications.** Applications filed with the specific 12-month priority-preservation function but not converted to non-provisional; they lapse if not converted.
- **International applications.** PCT applications, foreign national-phase applications, EP applications — each with their own ongoing costs and deadlines.

Track the patent estate in a specific spreadsheet with: patent number or application number, issue / filing date, next maintenance-fee due date, next prosecution response due date, jurisdiction, technology area, and any recorded encumbrances (security interests, license grants, assignments).

### Trademarks

- **Registered trademarks.** Trademarks registered with the USPTO (or state trademark offices or foreign offices). Each requires periodic renewal (Section 8 declaration between 5–6 years post-registration; Section 8 and 9 renewal every 10 years). Missed renewals cause the registration to lapse.
- **Common-law / unregistered trademarks.** Trademarks used in commerce but not registered. Rights are limited to the geographic area of use.
- **Domain names.** Not technically trademarks but often treated as brand assets in a shutdown. Domain-name registration must be paid annually.

### Copyrights

Copyrights in source code, documentation, marketing materials, and other original works of authorship. Copyright vests automatically in the author on fixation but can be registered with the US Copyright Office for statutory-damages and attorneys'-fees eligibility (17 U.S.C. §§411, 412). In an employment context, works created within the scope of employment are typically works-made-for-hire owned by the employer under 17 U.S.C. §101 — verify the specific employment agreements assign copyright to the company (a common gap in early-stage cap-table hygiene).

### Trade secrets

Confidential information that derives economic value from not being generally known (algorithms, customer lists, technical processes, financial data, engineering documentation). Protected under the Defend Trade Secrets Act of 2016 (18 U.S.C. §1836) and state Uniform Trade Secrets Act (UTSA) equivalents. Trade secrets are transferred by transferring the confidential information itself along with the associated documentation and confidentiality obligations.

### Source code and technical assets

Repositories on GitHub, GitLab, or Bitbucket; internal servers and infrastructure; deployment configurations; databases (customer data, product data, analytics data — subject to privacy-law constraints on transfer under GDPR / CCPA / CPRA).

### Contracts and customer relationships

Not technically IP but often disposed of alongside it: customer contracts, license agreements with third parties, distribution agreements, and vendor agreements. Assignment is subject to specific contract-term restrictions and consents.

### Encumbrances

Any IP that is subject to a security interest (typically recorded as a UCC-1 filing for the general company grant, and — for patents — recorded specifically with the USPTO under 35 U.S.C. §261 and 37 C.F.R. §3.11), a license grant to a third party, or an assignment obligation must be identified. Encumbered IP cannot be freely disposed of without addressing the encumbrance.

## The five disposition options

### Option 1 — Sell to a strategic buyer

The most common and typically the highest-value disposition. The IP (often bundled with related assets like the operating team, customer relationships, and specific in-flight contracts) is sold to a strategic buyer who will use it in their own business.

**When it fits.** The IP has specific value to a specific set of strategic buyers — the technology addresses a problem the buyer wants to solve, the patent portfolio complements the buyer's existing portfolio, the trademark has brand equity the buyer can use, the customer relationships expand the buyer's footprint.

**Process.** Typically run through the assignee (in an ABC) or the DIP (in Chapter 11 §363 sale), with a marketing memorandum circulated to identified buyers, competitive bidding, and a definitive asset-purchase agreement. Chapter 2 develops the ABC sale process; chapter 3 develops the §363 sale process.

**Structural considerations.**

- **Encumbrance handling.** In an ABC, encumbrances typically stay with the assets. In a §363 sale, §363(f) provides for sale free and clear — a specific and important structural advantage. For heavily-encumbered IP, this is often the decisive choice.
- **Chain of title.** Buyer will diligence the IP chain of title. Missing invention-assignment agreements from early employees, missing consultant-IP-assignment agreements, missing academic-institution assignments in university-spin-out cases — all are common gaps that can materially reduce IP value in diligence.
- **Open-source-license compliance.** If the software incorporates open-source components under specific licenses (GPL, LGPL, AGPL, MIT, Apache, BSD), the license terms transfer with the software. Buyer's IP diligence typically includes an open-source-license compliance review (Black Duck, Snyk, Sonatype, or manual review). Copyleft-license compliance issues can materially reduce IP value or require specific remediation.
- **Regulatory constraints.** For life-sciences IP, FDA regulatory status may transfer with the assets (with specific FDA notification requirements). For export-controlled technology, ITAR and EAR compliance apply. For AI models and datasets, emerging AI-specific regulatory frameworks may apply.

**Common structures.**

- **Straight asset sale.** Buyer pays cash for the assets; seller (the company or the assignee / DIP) transfers title.
- **Asset sale with earn-out.** Buyer pays cash at close plus additional consideration contingent on specific milestones. Less common in a distressed sale because the assignee / DIP has fiduciary duties to creditors that make contingent consideration risky.
- **Asset sale with employee transfer.** Buyer hires specific members of the operating team as part of the transaction. The "acqui-hire" pattern is common when the technology is early-stage and the operating team is the primary value.
- **Section 363 sale.** In Chapter 11, with the specific §363(f) free-and-clear feature.

### Option 2 — Assign to investors or founders under a pre-existing agreement

Some companies have specific pre-existing agreements that trigger IP transfer on a specified event. Common patterns:

- **Founder / investor buy-back provisions.** Some early-stage financing documents (particularly in specific university-spin-out contexts or in industry-specific investment structures) include provisions allowing founders or investors to buy back specific IP on the company's dissolution. These are rare in standard NVCA-style venture financings but exist in specific contexts.
- **University IP-assignment reversion.** If the IP originated from a university technology-transfer agreement with a reversion clause (the university retains the right to reclaim the IP on the company's failure to develop it or on the company's dissolution), the reversion may fire on shutdown. Common in life-sciences and specific hardware / semiconductor spin-outs.
- **Investor consortium buy-back.** In some multi-investor structures the investors as a group have a pre-negotiated right to acquire the IP on a shutdown event, often at a specified price or through a specified valuation mechanism.

When such an agreement exists, the assignment is a specific contractual obligation that runs regardless of the shutdown mechanism (subject to the fiduciary-duty and fraudulent-transfer overlays). Counsel should identify these agreements early in the shutdown planning.

### Option 3 — Abandon the IP

The company allows the IP to lapse through non-payment of maintenance fees, non-renewal of registrations, or affirmative abandonment. The IP effectively enters the public domain (for patents and copyrights on expiration; trade secrets on disclosure or loss of secrecy; trademarks on abandonment through non-use).

**When it fits.** The IP has no realisable value beyond the cost of maintaining it, no buyer interest, and no strategic use for founders or investors post-shutdown. Common for:

- Patents in technology areas the market has moved past.
- Trademarks for products the company will not continue and that have no brand equity.
- Registrations in jurisdictions where maintenance costs exceed expected value.

**Cost implications.**

- **Patent maintenance fees.** Missing fees causes the patent to lapse. The maintenance fee schedule (37 C.F.R. §1.20) requires fees at 3.5 years ($1,600 for a large entity), 7.5 years ($3,600), and 11.5 years ($7,400) post-issuance. Small entities pay half; micro entities pay 25%. Missing a fee causes the patent to lapse; the patent can be revived under 37 C.F.R. §1.378 for unintentional non-payment (with a specific late fee) for a limited time.
- **Trademark renewal fees.** Section 8 declaration between years 5–6 ($225 per class); Section 8 and 9 renewal at year 10 and every 10 years thereafter ($525 per class per verification of current fee at <https://www.uspto.gov/trademarks/fees>). Missing renewal causes the registration to lapse.
- **Foreign registrations.** Foreign patent maintenance and foreign trademark renewal have their own schedules and costs, often materially higher than US fees.

**Process.** Abandonment is typically not a specific affirmative act — it is the omission of the required maintenance / renewal. But for the assignee / trustee / DIP running the estate, the specific decision to *not* pay a maintenance fee is a fiduciary decision that requires deliberate consideration and (in an insolvency context) may require justification to creditors.

### Option 4 — License back to founders or a spin-out

The IP is licensed (not sold) to a newly-formed entity typically formed by the founders or a subset of the operating team, allowing the newco to continue development of the technology in a specific field of use.

**When it fits.** The founders want to continue working on the technology after the shutdown, but the estate has other creditors who need to be paid from the IP's residual value. A license-back structure allows the founders to continue development while the estate retains ownership and receives ongoing royalty streams from the newco's success.

**Structure.**

- **The newco.** A new entity formed by founders, sometimes with new investors. Distinct from the shutting-down entity.
- **The license.** Grants the newco specific rights to use the IP — exclusive or non-exclusive, all-field or field-of-use limited, worldwide or geographic, royalty-bearing or royalty-free. The specific terms depend on the value assessment and the fiduciary-duty analysis.
- **The royalty.** Typically a percentage of newco's revenue derived from the licensed IP, or a fixed schedule of milestone payments, or an equity interest in the newco. The specific royalty structure needs to reflect the market value of the licensed IP.
- **The estate's role.** The estate (in an ABC, the assignee; in a Chapter 7, the trustee; in a Chapter 11, the DIP) is the licensor and receives the royalty stream. Distributions to creditors continue as royalties are received.

**Fiduciary discipline.** A license-back to insiders (founders) requires specific fiduciary discipline in an insolvency context. The license terms must be at fair-market value or better for the estate; a market-check or specific valuation analysis is typically required. Failure to run the discipline exposes the officers to fraudulent-transfer challenges.

### Option 5 — Transfer to a special-purpose vehicle for later monetisation

The IP is transferred to a specially-formed entity (often a trust or LLC) whose sole purpose is to hold the IP for later sale or licensing. Common in patent-portfolio contexts where the individual patents have limited immediate value but the portfolio as a whole has potential value in a future licensing or sale transaction.

**When it fits.** The IP has potential future value but no immediate buyer or realiser, and holding the IP in the shutting-down entity is not workable (because the entity is dissolving) or in a licensee-newco (because there is no natural licensee).

**Structure.**

- **The SPV.** A specific trust or LLC formed to hold the IP. Beneficiaries or members are typically the creditors of the shutting-down entity in the priority order of the underlying waterfall (or a specific subset of creditors as negotiated).
- **The management.** Typically a specific IP-management firm or a trustee is engaged to manage the SPV — assessing the portfolio, seeking licensees, pursuing enforcement, distributing recoveries.
- **The distribution mechanism.** Recoveries by the SPV are distributed to the beneficiaries per the trust or LLC agreement.

This pattern is more common for larger IP portfolios and specific patent-heavy sectors (semiconductors, biotech, complex software patents). For a typical venture-backed startup shutdown with a modest IP estate, the SPV structure is often over-engineered relative to the value; the sale-to-strategic or license-back options are more typical.

## The decision structure

The disposition decision typically runs as follows:

1. **Inventory the estate.** What is actually here — patents, trademarks, copyrights, trade secrets, source code, domain names, contracts, encumbrances. Get to a specific list.
2. **Identify potential strategic buyers.** Who has bought similar IP in the past? Who has expressed interest in the company's technology previously? Who is a natural strategic acquirer for the specific patent or technology area?
3. **Assess buyer interest quickly.** In an ABC context, the assignee runs this in the first 2–3 weeks post-assignment. In a Chapter 11 context, the DIP's investment banker runs this in the pre-filing period if possible, or in the first weeks post-filing.
4. **Assess founder / investor interest.** Do the founders want to continue working on the technology? Do investors have specific structures that give them a right or an interest? Is a license-back or a founder-led purchase (chapter 2) the right structure for continuing use?
5. **Assess the abandonment alternative.** For each specific asset, what is the ongoing cost of maintenance, and what is the realistic value if not sold? Assets that cost more to maintain than they will realise should be abandoned (with appropriate fiduciary discipline).
6. **Choose the disposition per asset.** Different assets can have different dispositions. The core-patent portfolio might sell to a strategic; specific trademarks might be abandoned; specific domain names might transfer to founders; specific source-code repositories might license-back to a spin-out.
7. **Execute the transactions.** Sales through the assignee / trustee / DIP with fiduciary-duty and creditor-priority discipline; abandonment through the specific USPTO / Copyright Office / registrar procedures; license-back or SPV through specific transaction documents.

## The fiduciary-duty overlay

For an insolvent company, the fiduciary duty of directors and officers in the zone of insolvency shifts (Credit Lyonnais Bank Nederland N.V. v. Pathe Communications Corp., 1991 Del. Ch. LEXIS 215; North American Catholic Educational Programming Foundation, Inc. v. Gheewalla, 930 A.2d 92 (Del. 2007)). The duty runs to the corporate entity for the benefit of the corporate enterprise, which — when the enterprise is insolvent — includes the creditor class as residual claimant.

The specific implication for IP disposition:

- **The disposition must be defensible to creditors as a class.** A sale for less than reasonably-equivalent value that benefits insiders (founders buying at a low price without market-check) is a fraudulent-transfer risk under UFTA / UVTA and under 11 U.S.C. §548 in a subsequent bankruptcy.
- **The process must be a fair one.** Arm's-length transactions with disinterested directors approving specific insider transactions, and (ideally) an independent valuation supporting the price. Chapter 2's ABC-market-check framework and chapter 3's §363-sale framework provide the specific process patterns.
- **The record must be preserved.** The board minutes, the valuation analysis, the market-check documentation, and the fiduciary-duty analysis should be preserved for the D&O tail's (chapter 8) response to any later challenge.

## The chain-of-title question

The single most-frequent IP-diligence gap that reduces disposition value: incomplete chain of title. The typical failure modes:

- **Missing invention-assignment agreements from early employees.** The first 2–5 employees often start work without formal offer letters or with offer letters missing the specific present-tense assignment language required to transfer IP created during employment. The classic doctrine (Stanford v. Roche Molecular Systems, 563 U.S. 776 (2011)) makes clear that a promise to assign is not an assignment — specific "I hereby assign" present-tense language is required.
- **Missing consultant IP-assignment agreements.** Independent contractors who wrote significant code or created designs without a formal IP-assignment agreement typically retain copyright under 17 U.S.C. §201(a) unless the work is a specifically-enumerated work-made-for-hire under §101 (which most software is not) or has been transferred by a signed writing under §204(a).
- **Missing university / academic institution assignments.** University-spin-out patents that were assigned from the university to the company but where the assignment paperwork is incomplete or was never recorded with the USPTO.
- **Missing predecessor-entity assignments.** IP that was created in a predecessor entity (a converted LLC, a former DBA, a prior corporate form) but where the assignment to the current corporate entity was never documented.

Buyer's IP diligence will find these gaps. Fixing them requires specific corrective assignments from the original creators — which is often difficult if the creators have left the company on bad terms or cannot be located. A shutdown that discovers a chain-of-title gap in a specific patent can lose 20–80% of that patent's value in the sale.

The remediation options in a shutdown:

- **Chase the original creators for corrective assignments.** Time-consuming and dependent on cooperation.
- **Sell "as-is" with a discount.** The buyer accepts the risk in exchange for a lower price.
- **Structure the sale with specific representations and warranties** and a specific escrow or holdback for later-emerging chain-of-title issues. Not feasible in a distressed sale where the estate has no long-term ability to satisfy indemnities.
- **Abandon the specific IP** if remediation is not feasible and the discounted value does not justify the sale.

## The open-source-license compliance layer

For software companies with any codebase that incorporates open-source components, open-source-license compliance is a specific IP-diligence item and a specific disposition constraint.

The relevant license patterns:

- **Permissive licenses (MIT, Apache 2.0, BSD-2/3-Clause).** Allow reuse with attribution requirements. Rarely a disposition problem.
- **Weak copyleft (LGPL, MPL).** Require sharing of specific derivative works. Manageable but requires compliance documentation.
- **Strong copyleft (GPL, AGPL).** Require sharing of derivative works under the same license. Can be a significant constraint on disposition if proprietary code has been linked with GPL code — the "GPL contamination" concern.

A buyer's IP diligence will scan the codebase (Black Duck, Snyk, Sonatype FOSSA, or manual review) and identify specific compliance issues. Remediation options include: replacing the contaminated components, restructuring the software architecture to isolate the copyleft-licensed code, or (in some cases) obtaining commercial licenses from the copyleft component owners.

In a shutdown, a specific unremediated GPL / AGPL contamination can materially reduce the software's value or make specific dispositions impossible.

## Common failure modes

Six recurring failure modes in shutdown IP disposition:

1. **Sale-to-insider without market-check.** Founders "buy back" the IP from the assignee at a price they set without an arm's-length process. Fiduciary-duty exposure for the officers and fraudulent-transfer exposure for the assignee.
2. **Missed patent maintenance fees during the wind-up.** The assignee / trustee / DIP forgets to pay a maintenance fee that falls due in the wind-up period. The patent lapses; the buyer's price drops.
3. **Missed chain-of-title diligence.** The chain of title is only discovered to be broken after the sale is being negotiated, causing renegotiation or termination.
4. **Missed open-source compliance issues.** GPL contamination discovered in buyer diligence causes a specific renegotiation or termination.
5. **Missed data-privacy compliance in the customer-data transfer.** GDPR / CCPA / CPRA constraints on transferring personal data require specific consents or specific structural handling; missed compliance exposes the buyer and the seller to regulatory-and-private-litigation risk.
6. **Missed regulatory clearance on the IP transfer.** ITAR / EAR export-control approvals for certain technology; FDA notifications for medical-device IP; specific sector-regulator notifications. Missed compliance exposes both parties.

## What good IP disposition produces

- A specific and complete inventory of the IP estate.
- A specific decision-per-asset on disposition (sell / assign / abandon / license-back / SPV).
- Arm's-length transactions with fiduciary-duty and creditor-priority discipline, especially for any insider-involved transactions.
- Clean chain of title where possible, or a specific and disclosed as-is sale with a discount where remediation is not feasible.
- Open-source-license compliance addressed or documented for the buyer.
- Data-privacy compliance for any personal-data transfer.
- Specific procedural closure with the USPTO / Copyright Office / registrars for abandoned or transferred assets.
- Preserved records for any later challenge (fiduciary duty, fraudulent transfer, chain of title).

## Summary

IP disposition in a shutdown is often the highest-value single decision and one of the most irreversible. The five disposition options — sell to strategic, assign under pre-existing agreement, abandon, license-back to founders / spin-out, transfer to SPV — each have specific facts that push the decision toward them, specific fiduciary-duty and creditor-priority discipline that constrains the process, and specific procedural and compliance overlays (patent maintenance, trademark renewal, chain of title, open-source-license compliance, data privacy, regulatory clearance) that determine whether the disposition realises the intended value. The next chapter turns to the investor-communications and wind-up-vs-distribute workstream that runs alongside the disposition decisions.
