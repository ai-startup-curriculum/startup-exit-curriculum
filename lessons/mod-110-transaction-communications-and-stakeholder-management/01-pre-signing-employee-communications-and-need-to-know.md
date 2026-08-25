# Pre-Signing Employee Communications and the Need-to-Know Perimeter

## Why this matters

Every M&A process leaks. The only variable is *how far* and *when*. A leak that hits the *Financial Times*, *WSJ*, *Bloomberg*, or *The Information* two weeks before an intended signing is the single most reliable price-compressor in the deal-execution playbook — it forces the sell-side into a compressed timetable (because the market now expects an announcement), it invites competing bidders who arrive under-diligenced and with unrealistic price expectations, it puts pressure on the buyer's board to walk (because the buyer's stock trades down on the rumour and the board's independent directors get spooked), and it hands the employee base a story with no context that gets metabolised on Slack and Blind through the worst possible retention channels. The corporate-development literature is consistent: a leak between LOI and signing typically pushes closing out by 30–90 days, and where it does not kill the deal outright it commonly re-prices the transaction down by 5–15% as the buyer captures the leverage the seller lost.

The corporate-development discipline that keeps a deal off the front page is not exotic. It is a specific set of practices — a **clean list** with named individuals and dated additions, a **code name** for every project across every touchpoint (email subject lines, VDR folder names, calendar entries, expense codes, Slack channels), an **executive-team-only briefing pattern** with an explicit deal-team-adds-only rule, and a **VDR access audit** that catches the seven documents someone tagged wrong. It is enforced by the GC and the SVP-Corp-Dev, is documented in the deal's project file, and is reviewed at every deal-team touchpoint.

This chapter installs that discipline. The intent is to turn the practitioner's tacit "we run this tight" into an explicit playbook — one the CFO can hand to a new corp-dev analyst on day one, one the GC can point to when an in-house paralegal asks why they cannot see the VDR, and one the founder-CEO can defend to a nervous board director who is used to running a public-company disclosure regime and has to trust a private-company deal-team perimeter.

> Reminder: this module is education, not legal advice. Every specific deal engages qualified securities counsel who will impose their own confidentiality and insider-trading discipline on the deal team, which typically includes an explicit **material non-public information (MNPI)** framework, a written insider-trading policy, and (for a public target) a pre-clearance requirement on any securities trading by insiders. Follow the counsel-imposed regime; this chapter describes the operational overlay that sits underneath it.

## Why leaks happen — the eight failure modes

Leaks are not random. They fall into a recognisable pattern of failure modes, and the perimeter discipline below is designed to close each one specifically.

1. **Deal-team accidental disclosure.** A deal-team member forwards a project email to a broader distribution list, or copies a helpful colleague on a subject line that names the target, or leaves a document open on a laptop in a co-working space. This is the single most common failure mode and is closed by discipline on the deal-team roster, code-name usage, and endpoint hygiene.
2. **Non-deal-team detection through side effects.** A colleague notices that the CFO has been in three days of unusual meetings with unfamiliar people, that the VP of Engineering has been asked for an unusual data-request, that the SVP of Sales has been in the CEO's office for two hours on a Friday afternoon, that the corporate calendar shows recurring meetings with a code-named project. Side-effect inference is closed by disguising the operational fingerprint of a deal — meetings booked as one-on-ones with the CEO, data pulls routed through the CFO or a specific analyst, code-names used throughout, and the CEO's calendar populated with plausible cover meetings.
3. **VDR access-permission errors.** A document uploaded to the VDR under the wrong access permission is visible to a group that should not have access — sometimes to buy-side representatives who then have leverage they were not intended to have, sometimes to a broader internal group. VDR discipline is the specific perimeter that closes this.
4. **Vendor / advisor accidental disclosure.** The financial advisor's associate discusses the deal at a bar, the auditor's manager mentions the diligence workstream in a partner meeting, the outside legal team's paralegal Slacks a friend at another firm. Vendor discipline is imposed by NDA (already in place) and by the specific advisor-firm's internal deal-team clean-list, which the sell-side GC should verify.
5. **Counterparty leak.** The buyer's internal team, the buyer's PE-sponsor's LP-communications team, the buyer's banker, or the buyer's legal team leaks — either accidentally, or (in some patterns) strategically to pressure the sell-side. Counterparty leaks are managed through counterparty deal-team roster review at LOI, mutual clean-list acknowledgement, and explicit contractual confidentiality with liquidated damages where possible.
6. **Journalist inference from multiple weak signals.** A specific sector reporter notices that three different sources have mentioned the target unusually, that the CEO cancelled a conference speaking slot, that the target's CFO's LinkedIn profile now lists "Corp Dev advisor" in the summary. Journalists trained on M&A do this professionally and are frequently the ones who "break" a deal that has, in fact, been available to inference for weeks. Chapter 4 covers the press-strategy overlay that manages the journalist inference channel.
7. **Employee inference from workspace signals.** Employees notice that the CFO has taken over the small conference room for a week, that the printer in the executive suite is running unusual volumes, that the office cleaner has been asked to skip a specific room, that the SVP-Corp-Dev is suddenly in the office every day when they usually work remote. Employee inference is the reason large deals in large companies typically run their diligence workstreams off-site or in a specific "war room" that has its own access control.
8. **Regulatory-filing-timing detection.** An HSR filing is public information once the FTC's Premerger Notification Office indexes it (though the index is not immediately searchable in real time), and specific sector regulators (banking regulators, insurance commissioners, FCC, CFIUS via public notice in some cases) have public-notice regimes that a sufficiently plugged-in reporter can detect. This is a signing-timing consideration rather than a pre-signing perimeter consideration, but the deal-team should be aware of what leaves an inference trail.

The perimeter discipline below is designed to close failure modes 1–5 and 7. Chapter 4 (press strategy) covers 6. Regulatory-timing detection is a mod-103 deal-structure consideration.

## The clean list — the specific named-individual roster

The **clean list** (also called the **deal-team roster** or the **insider list**) is the specific document that names every individual who has been *knowingly* granted access to the transaction. It is the single source of truth for who is inside the perimeter and — for a public-company issuer or where public-company insider-trading rules apply — is the basis for the **insider trading blackout** and for the **regulatory insider list** required in some jurisdictions (notably the EU under MAR Article 18).

**What the clean list contains.** For each individual:

- Full name and title.
- Date added to the list.
- Reason for addition (specific workstream — legal counsel, financial advisor lead, target-side CFO, buyer-side technology diligence lead, etc.).
- Who authorised the addition (GC and/or SVP-Corp-Dev signature).
- Type of information the person has access to (full deal, specific workstream, specific document set).
- Date removed from the list (if applicable, e.g., a specialist consultant whose work ended).

**Who typically appears on the clean list before signing.** In a typical mid-size private-company sell-side transaction:

- **Sell-side executive team, deal-team layer.** CEO, CFO, GC, SVP-Corp-Dev, board members (as needed for approvals). Some executive-team members are *not* added — for example, the CTO is often added only when technology diligence starts; the CRO is often added only when a specific customer-reference workstream starts; the CHRO is often added when compensation and 280G analysis or WARN analysis starts. The deal-team layer of the sell-side is deliberately kept small — often 5–8 people — until the diligence workstreams require broader involvement.
- **Sell-side advisor deal-team layer.** Sell-side investment banker (lead MD, VP, associate, analyst — the specific staffing team, not the entire bank), sell-side legal team (lead partner, corporate M&A partner, specific specialist partners for tax / employment / IP / securities, key associates), sell-side accountants (Q-of-E lead partner and team), specialist advisors as needed (executive-compensation counsel for 280G, environmental consultant for a manufacturing target, IP counsel for a patent-heavy target).
- **Buyer-side deal-team layer.** Buyer's CEO / CFO / SVP-Corp-Dev / GC, buyer's investment banker team, buyer's legal team, buyer's financial diligence team, buyer's insurance-broker team for R&W. In the buyer's case the deal-team is often much broader (a strategic acquirer may have twenty diligence-workstream leads) — the sell-side does not control the buyer's clean list but should require the buyer to represent that a clean-list discipline is in place.
- **Board members and specific significant stockholders.** Board is added when the transaction is board-approved (typically at LOI signing, sometimes earlier for a specific strategic-review authorisation). Preferred-stockholder representatives (specifically the lead investor's board designee) are typically on the deal-team from a very early point because the preferred stockholders' vote is required.

**Who typically does not appear on the clean list before signing** — and this is where the discipline matters most:

- Marketing team, product-marketing team, PR firm's day-to-day account team. These are added *after* signing when the announcement plan is executed.
- Field sales team, customer-success team. Added *after* signing.
- Broader engineering team beyond the specific CTO or VP-Engineering diligence lead. Added *after* signing.
- People / HR business partners beyond the specific CHRO or the specific comp-analysis lead. Added *after* signing when the retention conversations and benefits-transition workstreams begin.
- Finance team beyond the specific CFO / VP-Finance / controller / FP&A lead. Broader finance-team members typically pulled in for specific diligence responses under a "need-to-know for this specific response" pattern, with each person's exposure logged.

**The deal-team-adds-only rule.** Once the clean list exists, no one is added except through an explicit process: a request routes to the SVP-Corp-Dev, who confirms need-to-know with the workstream lead, who obtains GC signature, who updates the list. The rule is enforced by the deal-team never referring to the deal in the presence of anyone not on the list. In practice this means the SVP-Corp-Dev's daily behaviour changes — meetings are titled with the code name, materials are labelled with the code name, conversations in shared spaces defer or reschedule. The founder-CEO who "just wants to loop in" the head of product for a specific question either formally adds the head of product to the list (with the appropriate NDA and paper trail) or defers the conversation until post-signing.

**The insider-trading interaction (for public targets).** If the target has public securities (a public-company target being taken private, or a private company with publicly-traded convertible debt or preferred), the insider-trading blackout applies from the moment MNPI attaches. Everyone on the clean list is presumptively an insider for the duration of the transaction. Trading in the target's securities by any insider requires pre-clearance from the GC and typically is prohibited outright until public disclosure. The clean list is the operational document that identifies who is subject to the blackout.

**EU MAR insider-list requirement.** Under the EU Market Abuse Regulation (MAR) Article 18, issuers of financial instruments admitted to trading on an EU regulated market or MTF must maintain an insider list in a specific format (permanent and event-specific sections, prescribed data fields, prompt updates, retained for five years, provided to the competent authority on request). A public-company issuer with EU-listed securities running a transaction is subject to this discipline as a matter of law, and the deal-team clean list forms the basis of the MAR insider list. Chapter 4 covers Regulation FD, which is the US analog for public-company issuers.

## The code name — one project, one name, applied everywhere

Every deal gets a **code name** at the moment the deal is contemplated seriously enough to have a first outside meeting. The code name is used in every artefact — email subject lines, VDR folder names, calendar entries, expense codes, Slack channels, meeting-room bookings, printed documents. The purpose is twofold: (1) it prevents accidental disclosure via subject-line-visible-in-a-conference-room, and (2) it establishes a discipline that separates the deal from ordinary-course business.

**Naming conventions.** The industry convention is that the target's code name is neutral — a colour, a metal, a city, an animal, a Greek letter. Some firms use a two-part code name (Project Falcon, Project Marlin) that distinguishes seller-side name from buyer-side name so both sides can talk about the deal internally without confusion. Some firms use the codename that the investment banker assigns (banks maintain a standard list of code names to prevent overlap across concurrent deals). The specific name is less important than the *consistency* — every artefact uses the same name.

**What to avoid in a code name.** Do not use a name that itself gives away the target — no "Project Apple" for an Apple-adjacent target, no "Project Cobalt" for a battery company, no code name based on the CEO's alma mater. Do not use a code name that has been used publicly for another purpose recently (a project name that appears in a job posting, a product name that a marketing team is using). Do not use a code name so distinctive that a search engine query would surface it.

**Applied everywhere.** The discipline is enforced by:

- Email subject lines: "Project Falcon — diligence Q&A" rather than "TargetCo diligence Q&A." The email body may reference the target by name (recipients on the clean list know), but the subject line does not.
- VDR folder names: top-level folder is "Project Falcon," sub-folders are named for workstreams. Document filenames use the code name in place of the target's real name.
- Calendar entries: "Project Falcon working session" rather than "TargetCo diligence call." The invitee list is on the clean list.
- Expense codes: a specific general-ledger code for deal expenses that does not reference the target name. Advisors bill against this code.
- Slack / Teams channels: private channels named "project-falcon" with membership restricted to the clean list. No use of the target's name in channel titles or in messages.
- Meeting rooms and printers: a specific meeting room is reserved for the deal team and physically locked when not in use; printer settings ensure documents print to a specific device the deal team monitors.
- Executive assistants: the CEO's, CFO's, and GC's assistants are typically on the clean list from an early point and are the people who enforce calendar and meeting-room discipline. If they are not on the clean list, the executive schedules the meetings personally, which is a specific operational tax that signals to the assistant that something unusual is happening.

## Executive-team briefing pattern — who hears about the deal in what order

The **executive-team-only briefing** is the specific pattern by which the sell-side executive team is informed of the deal without expanding the clean list prematurely. The pattern is:

**Step 1 — the founder-CEO and one or two others contemplate the deal.** Typically the founder-CEO, the CFO, and the GC form the initial core. The board chair (if a non-founder) is often included at this stage as a consultation partner rather than a formal approver.

**Step 2 — the sell-side banker is engaged.** The banker's engagement letter is signed by the CEO / CFO (typically with board notification, sometimes with formal board approval depending on the specific corporate governance framework). At this point the banker's clean-team is added to the deal-team roster.

**Step 3 — the executive-team briefing.** At a moment when the deal is real enough to require executive-team participation — typically at LOI or shortly before — the CEO briefs the executive team in a specific meeting that follows a specific pattern:

- Held off-site or in a specific secure room, with no assistants or note-takers other than a designated deal-team scribe.
- Held on a Friday afternoon or a specific low-traffic time, to give the executive team a weekend to process before returning to the office on Monday.
- Opened by the CEO with the specific transaction framing — what the deal is, why now, what the process looks like from here.
- Each executive is asked to sign an acknowledgement of the confidentiality and insider-trading discipline before leaving the room (typically the acknowledgement was pre-drafted by GC).
- Each executive is added to the clean list with the specific workstreams they will lead.
- Post-meeting, each executive is followed up with 1:1 by the CEO or CFO to answer specific personal-consequence questions (compensation impact, retention package, personal-holdings implications).

**Step 4 — the executive-team deal-team-adds-only rule kicks in.** From this point, additions to the clean list are governed by the process above — the CFO's request to loop in a specific FP&A analyst for a specific diligence question routes to SVP-Corp-Dev / GC, is approved with a specific need-to-know rationale, and is logged.

**What executive-team-only does not mean.** It does not mean the CEO makes the decision alone; the executive team is a *deliberative* body about the deal. It does not mean the executive team is on all diligence calls; each executive has a specific workstream. It does not mean the executive team is on the clean list from day one; the CEO / CFO / GC often carry the deal for weeks before the wider executive team is briefed, especially at the exploratory / IOI stage.

**Board timing.** The board is typically briefed at the LOI stage (or earlier under a specific strategic-review authorisation resolution). Full board briefing typically follows the executive-team briefing by days rather than weeks. Board members are added to the clean list at briefing.

## Virtual data room (VDR) access-audit discipline

The VDR is the specific document repository for the transaction, hosted on a specialist platform (Intralinks, Datasite, Firmex, Ansarada, DealRoom — see mod-105 for VDR selection). The VDR's specific access-audit features are the operational perimeter for who has seen what.

**Access-group discipline.** The VDR is structured with a specific set of access groups — typically at minimum: sell-side deal team (full access), sell-side counsel (full access), sell-side banker (full access), sell-side auditor (audit-workstream access only), buyer's core team (full access), buyer's legal counsel (full access), buyer's financial diligence (financial-workstream access), buyer's technology diligence (tech-workstream access), buyer's HR diligence (HR-workstream access), R&W underwriter (R&W-scope access). Each user is placed in exactly one group; group memberships are audited weekly by the sell-side deal-team lead.

**Access-audit review — the specific weekly discipline.** Every week during the diligence period, the sell-side deal-team lead (or a designated deal-team analyst) runs the VDR access-audit report and reviews it against expectations:

- Which specific individuals accessed which specific documents in the past week?
- Are any access patterns unusual (a technology-diligence analyst accessing a customer-list document, an R&W underwriter accessing an executive-compensation document outside their scope)?
- Are any specific groups accessing documents at a volume that suggests something they should not have access to?
- Have any new users been added to any access group without deal-team approval?
- Have any documents been uploaded to the VDR with the wrong access-group permission (a specific "customer top-20" document uploaded with buyer's-full-team access when it should have been in a clean-team-only sub-folder)?

The specific pattern that surfaces from a weekly audit is the *unexpected access* — a person on the buyer's team accessing something the buyer's counsel had confirmed they would not access, a specific document the sell-side did not intend to expose. The audit closes this by flagging the pattern to counsel, who then addresses it either through a permission correction, a specific commitment from the buyer, or (in serious cases) a specific escalation to the buyer's principal.

**Watermarking and access-locking.** Sensitive documents (customer contracts, executive-compensation schedules, cap-table detail, code-of-conduct investigations, litigation-strategy memoranda) are watermarked with the accessing user's name and access timestamp, and are often set to "view-only" (no download, no print, no copy). The watermark serves as a deterrent against re-distribution and — in the case of a leak — as a forensic marker.

**Clean-team documents.** A specific sub-set of documents in the VDR are labelled **clean-team documents** and are accessible only to a specific **clean team** — typically the buyer's specific outside counsel and outside financial-diligence team, deliberately excluding the buyer's own operating employees. Clean-team documents typically include: current-customer pricing detail (where pricing disclosure to the buyer's operating team would be a competitive risk), pipeline / sales-forecast detail, employee-comp detail with named individuals, current-litigation strategy, current M&A pipeline of the target. The clean-team designation is negotiated at LOI or shortly after and is documented in a specific **clean-team agreement** among sell-side counsel, buyer's counsel, and the clean-team advisors. Clean-team compliance is one of the specific enforcement points during the deal.

## Financial-advisor and legal-advisor briefings gated separately

The financial advisor (investment banker) and the legal advisor (corporate M&A counsel) are typically the earliest external parties on the clean list — the banker is engaged to run the process, the legal counsel is engaged to draft and negotiate the documents. But specific *sub-workstreams* of the advisor teams are gated separately as they come into scope:

- The **auditor** joins when Q-of-E work begins.
- The **executive-compensation counsel** joins when 280G analysis or MIP design begins.
- The **environmental consultant** joins when environmental diligence begins.
- The **IP counsel** joins when patent / trademark diligence begins.
- The **regulatory counsel** joins when HSR / CFIUS / sector-regulatory workstreams begin.
- The **R&W insurance broker** joins when R&W coverage is being sought.
- The **communications / PR firm** joins in the pre-signing period, typically 2–4 weeks before signing, when announcement-day planning begins.

Each addition follows the deal-team-adds-only pattern — the workstream lead requests, the SVP-Corp-Dev / GC approves, the individual is added to the clean list, the NDA is confirmed, and the code-name discipline extends to that individual's firm.

## The leak-response playbook

Every deal-team plans for the specific event of a leak — before it happens — so that when it does happen the response is not improvised. The playbook has six elements.

**1. Detection.** The deal team monitors specific channels for leaks — the sector-relevant financial press (WSJ, Bloomberg, FT, Reuters, sector-specific outlets), industry blogs (The Information, TechCrunch, sector-specific), Blind and Reddit (for employee-side conversations), and (where relevant) short-seller channels. The banker's IR / M&A-desk typically has visibility into rumour-driven trading in the target's securities (if public) and in comparable-company securities that might signal a leak. Detection responsibilities are assigned specifically — a named individual on the sell-side and a named individual on the buyer's side (with coordination through the bankers) are watching every day.

**2. Confirmation and source-identification.** When a specific rumour surfaces, the deal team first confirms the specifics — what did the outlet publish, what did they reference, who might have been the source. The GC coordinates with the banker's team on source-identification (typically without much success — journalist sources are usually not identifiable). The purpose is to inform the response strategy, not to punish.

**3. Legal-response coordination.** If the leak crosses specific legal thresholds — public-company insider-trading concerns, specific NDA-breach exposure — outside counsel is engaged for a specific legal response (which may include a specific cease-and-desist to the source, if identified, or a specific engagement with the SEC for a public target).

**4. Counterparty coordination.** The sell-side and buy-side coordinate on the response. The buyer may want to accelerate the deal to prevent competing bids from being drawn in by the leak; the seller may want to accelerate to prevent price compression; the two sides may want to jointly deny the specific leak or jointly acknowledge and reframe it. The coordination is done through the bankers, in real time.

**5. Employee-and-customer-facing response.** The comms team activates a specific "leak response" script — a specific approved statement that executives use if asked about the rumour by employees, customers, journalists. Typical framing: "We do not comment on rumours or speculation. We remain focused on our current strategy and our customers." The specific script is prepared in advance so the CEO does not have to improvise on a hot mic.

**6. Timetable acceleration decision.** The deal team decides — often within 24–48 hours of a specific leak — whether to accelerate to signing. Acceleration has costs (compressed diligence, compressed negotiation, higher execution risk) and benefits (preserves the buyer's leverage against competing bidders, prevents further price compression). The decision is made by the CEO / board with the banker's and GC's input, and is documented in the board minutes for defensibility.

The specific pattern that repeats across deals: the deals that leak and *do not* have a leak-response playbook lose 5–15% of price to timetable compression and buyer-side leverage capture; the deals that leak and *do* have a playbook typically hold price within 2–3% and preserve the intended timetable.

## Summary

The pre-signing communications regime is a *perimeter discipline*, not a messaging discipline. The perimeter is built from a **clean list** of specific named individuals with dated additions, a **code name** applied consistently across every artefact and touchpoint, an **executive-team-only briefing pattern** that expands the deal-team layer only through a formal deal-team-adds-only process, a **VDR access-audit** discipline that reviews document exposure weekly and flags unusual patterns, a **clean-team designation** that walls off competitively sensitive documents from the buyer's own operating team, a **financial-and-legal-advisor gating** that adds specialist workstreams only when they come into scope, and a **leak-response playbook** prepared in advance so the CEO does not have to improvise. The perimeter is enforced by the SVP-Corp-Dev and GC, is documented, and is auditable. The founder-CEO who treats the perimeter as bureaucracy discovers — usually on the day the WSJ tweets a specific rumour — that the perimeter existed for a specific reason.

The specific chapter that follows turns to the post-signing choreography — the day-of sequencing, the manager one-on-one waves, the retention conversations, and the benefits-transition FAQ that turns a signed deal into a retained team.
