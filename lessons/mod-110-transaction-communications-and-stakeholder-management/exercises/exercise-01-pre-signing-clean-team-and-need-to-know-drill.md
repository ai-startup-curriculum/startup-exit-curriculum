# exercise-01: Pre-Signing Clean Team and Need-to-Know Drill

**Estimated effort:** 3 hours

## Objective

Build the operational perimeter that keeps a specific pre-signing transaction off the front page of the *Wall Street Journal*. Take a specific transaction profile — a sell-side M&A to a strategic acquirer, a controller take-private, or a dual-track-ending-in-sale — and produce a defensible **pre-signing need-to-know package** that a GC and SVP-Corp-Dev could hand to a new corp-dev analyst on day one. By the end of the exercise you should be able to show the specific clean-list roster, the specific code-name discipline, the VDR access-group map, the executive-team briefing script, the deal-team-adds-only approval workflow, and the leak-response playbook — each tied to the specific transaction facts rather than to generic boilerplate.

## Background

This exercise covers material from:

- [Chapter 1 — Pre-Signing Employee Communications and the Need-to-Know Perimeter](../01-pre-signing-employee-communications-and-need-to-know.md)

The specific perimeter you build in this exercise is the **starter artefact for every subsequent exercise in the module** — the clean list is what the announcement-day cascade (exercise 02) layers onto, the customer-reference pre-warning (exercise 03) runs against, the press embargo (exercise 04) sits inside, and the WARN notice drafting (exercise 06) is kept out of until a specific decision is made to add it.

## Prerequisites

- A specific transaction profile that you will carry through the module. If you do not have a live transaction, construct a realistic hypothetical with the following completeness.
- Access to a specific recent SEC Form 8-K announcement with the specific joint press release attached (search EDGAR for recent `8-K` filings under Item 1.01 "Entry into a Material Definitive Agreement" and Item 2.01 "Completion of Acquisition" at <https://www.sec.gov/cgi-bin/browse-edgar>) to anchor the specific transaction-structure and specific advisor-naming patterns.
- Access to a specific VDR vendor's permissions documentation — at least one of Intralinks (<https://www.intralinks.com>), Datasite (<https://www.datasite.com>), Firmex (<https://www.firmex.com>), or Ansarada (<https://www.ansarada.com>) — to anchor the specific access-group vocabulary.
- For EU-nexus deals, access to the specific **Market Abuse Regulation Article 18** insider-list format: ESMA technical implementing standards at <https://www.esma.europa.eu/document/draft-regulatory-and-implementing-technical-standards-mar> and the specific Commission Implementing Regulation (EU) 2016/347.

## The transaction profile

Fill in this profile at the top of your deliverable. If a field does not apply, write "N/A — because …" rather than skipping. Freeze the profile — the subsequent exercises in this module reference it.

- Target name (or real codename for the exercise — pick one and apply it consistently): _____
- Target state / country of incorporation and primary operating country: _____
- Transaction type (sell-side M&A to strategic / sell-side to PE / controller take-private / dual-track terminated in sale / IPO with concurrent secondary): _____
- Deal size (approximate enterprise value): _____
- Target securities status (private / publicly-listed common / privately-held with publicly-traded debt or preferred / EU-regulated-market admitted): _____
- Target headcount by site (give at minimum the top 3 sites by headcount and the aggregate for the long tail): _____
- Target executive team (CEO, CFO, GC, CTO, CRO, CHRO, SVP-Corp-Dev; name the specific individuals or roles that exist in the target): _____
- Expected sell-side advisors (financial advisor, legal counsel lead firm, auditor, specialist counsel for 280G / IP / environmental / regulatory, R&W broker if applicable, communications / PR firm): _____
- Expected sign-to-announcement timeline (weeks): _____
- Expected regulatory clearances required (HSR, foreign antitrust in specific jurisdictions, CFIUS, sector regulator, works councils): _____
- Any publicly-listed securities subject to insider-trading blackout: yes / no / which

## Tasks

### 1. Author the specific clean-list roster (spreadsheet or structured markdown table)

Produce a specific clean-list roster that will govern the deal through signing. The roster should have one row per individual, with the columns described in chapter 1:

- Full name (or role-slot where the specific individual is not yet named).
- Title.
- Entity (target, sell-side banker firm, sell-side counsel firm, buyer, buyer's advisor firm, etc.).
- Date added to the list.
- Workstream the individual covers (named workstream — "Q-of-E lead," "technology diligence," "280G counsel," etc. — not "general counsel work").
- Who authorised the addition (GC and/or SVP-Corp-Dev signature).
- Access scope (full deal / specific workstream / specific document set / clean-team only).
- Insider-trading status (presumptive insider for target securities / presumptive insider for buyer securities / N/A).
- Date removed (if applicable).

Populate the roster for the specific transaction. At minimum include:

- The sell-side deal-team core (CEO, CFO, GC, SVP-Corp-Dev) and the specific executive-team members you add before signing with the specific workstream rationale for each.
- The sell-side advisor layer — the specific financial-advisor staffing (named individuals or named role-slots at the lead-MD / VP / associate / analyst level), the specific legal-counsel partners and specific senior associates, and the specific specialist advisors (auditor, 280G counsel, IP counsel, environmental, regulatory, R&W broker, communications / PR firm) sequenced to the specific point each one is added.
- The board-and-stockholder additions (board members, specific preferred-stockholder designees, specific significant-common-stockholder representatives who need to vote).
- The buy-side layer the sell-side knows about through the bankers (buyer CEO / CFO / SVP-Corp-Dev / GC, buyer's banker and counsel firms, buyer's financial-diligence lead, buyer's R&W broker).

Explicitly list — in a separate "intentionally excluded" section — the specific individuals and functions you are **not** adding before signing (marketing, PR day-to-day account team, field sales, customer success, broader engineering, broader finance, HR business partners). For each exclusion, state the specific point at which the person *would* be added and under what specific process.

### 2. Define the code-name convention (1-page memo)

Draft a specific 1-page internal memo that defines the specific code name for the transaction and the specific operational discipline around it:

- The specific code name you have chosen, and the specific reason it is a safe choice (not derivable from the target, not previously used in a public artefact, not vulnerable to a search-engine query).
- The specific "where the code name is used" list — email subject lines, VDR folder names, calendar entries, expense codes, Slack / Teams channels, meeting-room bookings, printed documents, deal-team file-share folders.
- The specific "where the target's real name is permitted" list — inside the body of an email to clean-list recipients, inside documents accessed under the VDR permission system — and the specific reason the real name is permitted in those venues.
- A specific "slip-up protocol" — what happens when a specific deal-team member accidentally uses the real name in the wrong venue, who reports it, how it is logged, and whether the specific slip triggers any specific additional discipline.
- A specific executive-assistant protocol — which executive assistants are on the clean list, what calendar / meeting-room / printer discipline each one owns, and the specific escalation path if an assistant is **not** on the clean list (e.g., the executive schedules the meeting personally — a specific operational tax that signals to the assistant that something unusual is happening).

### 3. Build the VDR access-group map (table + 1-page memo)

Produce a specific VDR access-group map covering:

- The specific access groups you will configure in the VDR (at minimum: sell-side deal team, sell-side counsel, sell-side banker, sell-side auditor, buy-side core team, buy-side legal, buy-side financial diligence, buy-side tech diligence, buy-side HR diligence, R&W underwriter — plus any specific additional groups the specific transaction requires).
- The specific document categories each group can see, and specifically what each group **cannot** see.
- The specific clean-team sub-folders — which specific documents (customer top-20 pricing, pipeline / forecast detail, employee-comp detail with named individuals, in-flight litigation strategy, target's M&A pipeline, specific IP strategy items) sit behind the specific clean-team wall and which specific buy-side advisors (outside counsel, outside financial-diligence firm) have specific clean-team access.
- The specific watermarking and view-only configuration for each sensitive document category.
- The specific weekly access-audit protocol — who runs the report, what unusual patterns the reviewer looks for, what the specific "unusual-access-flag" escalation path is, who signs off that the audit was completed.

Attach a specific 1-page memo explaining the specific clean-team-agreement framework — who signs it (sell-side counsel, buy-side counsel, the specific clean-team advisors), what it specifically prohibits (operating-team access, re-distribution outside the clean team, use for purposes other than the specific transaction), and what the specific enforcement mechanism is (contractual damages, injunctive relief, deal termination).

### 4. Draft the specific executive-team briefing script (2-page document)

Draft the specific script the CEO will use to brief the executive team at the specific moment the deal expands beyond the CEO / CFO / GC core (typically at LOI or shortly before). The script should include:

- The specific pre-meeting choreography — venue (off-site vs. secure on-site room), timing (Friday afternoon? end of day?), who else is present (CFO, GC, deal-team scribe), who is excluded (assistants, note-takers).
- The specific opening framing — what the deal is, why now, what the process looks like from here, what specifically is being asked of the executive team.
- The specific confidentiality-and-insider-trading-acknowledgement document that each executive signs before leaving the room (draft the specific one-page acknowledgement — one that references the specific transaction code name, specific MNPI framework, specific trading restrictions, and specific clean-list addition).
- The specific "assigned workstream per executive" slide — each specific executive's specific role in diligence (CTO owns technology diligence, CRO owns the customer-reference workstream, CHRO owns the 280G and WARN analysis and the retention list, etc.) and the specific point at which each one adds their specific sub-team members to the clean list.
- The specific 1:1 follow-up protocol — which executive has 1:1 with the CEO (or CFO) in the next 48 hours to address their specific personal-consequence questions (compensation impact, equity treatment, retention-package terms).
- The specific "what you don't know yet" caveat — the specific topics on which the CEO cannot yet give a specific answer (buyer's post-close org design, specific role commitments beyond the executive-level, workforce-action detail) and the specific escalation path when a specific executive raises one of those questions.

### 5. Design the deal-team-adds-only approval workflow (process diagram + 1-page memo)

Define the specific process by which any new individual is added to the clean list after the executive-team briefing. The deliverable:

- A specific process diagram showing the specific steps — workstream lead identifies the specific need, submits a specific written request (template included), SVP-Corp-Dev confirms need-to-know with the workstream lead, GC confirms the specific NDA / confidentiality overlay is in place, GC signs the clean-list addition, the specific individual receives a specific onboarding briefing covering code name discipline and MNPI framework.
- The specific written-request template — one page with fields for requester name, individual to add, specific workstream, specific document / information scope, specific duration, specific NDA / employment-agreement confidentiality basis.
- The specific onboarding-briefing template — a specific 15-minute briefing script that covers code name, communication channels, meeting discipline, insider-trading restrictions, and the specific "if you need to add someone, here is the process" rule.
- The specific "exception" protocol — when the CEO or an executive believes the standard workflow is too slow, what the exception path is (same-day GC approval with retroactive paper trail, or emergency clean-team-counsel-only path with the operating executive formally added within 24 hours).

### 6. Author the leak-response playbook (3-page document)

Draft the specific leak-response playbook that the deal team will execute if a specific rumour surfaces before the specific intended announcement. The playbook should cover the six elements from chapter 1:

- **Detection.** The specific channels monitored (sector-relevant financial press, industry blogs, Blind / Reddit, short-seller channels, rumour-driven trading desks), the specific named individual on each side who owns daily monitoring, and the specific coordination mechanism (daily end-of-day banker-to-GC email on monitoring findings).
- **Confirmation and source-identification.** The specific triage protocol — what the specific deal team does in the first hour after a specific rumour surfaces (confirm the specific outlet, confirm the specific wording, assess whether the specific rumour contains specific-enough detail to indicate a specific inside source).
- **Legal-response coordination.** The specific legal workstream — specific cease-and-desist if the specific source is identified and is in breach of a specific NDA, specific SEC engagement if the specific target is a public issuer, specific insider-trading-review for the clean list.
- **Counterparty coordination.** The specific communication path between the sell-side and buy-side deal teams in a specific leak event — bankers coordinate, GCs coordinate, CEOs coordinate at specific designated moments.
- **Employee-and-customer-facing response.** The specific pre-approved "no comment on rumour or speculation" script executives use if asked. The specific extended-script for the specific scenario where the leak is specific-enough that silence looks like confirmation. The specific "social-media silence" discipline (no deal-team member posts, likes, or shares anything that could be interpreted as commentary during the specific leak window).
- **Timetable-acceleration decision.** The specific framework for the 24–48 hour decision — who makes it (CEO with board input), what the specific decision inputs are (buyer's view on acceleration, banker's view on remaining diligence, counsel's view on execution risk), and the specific documentation discipline (board minutes capturing the specific decision rationale for later defensibility).

### 7. Produce a one-page SVP-Corp-Dev summary

Reduce the whole package to a one-page summary for the SVP-Corp-Dev that lists:

- The clean-list roster size by category (sell-side, sell-side advisors, buy-side, board / stockholders) and the specific "intentionally excluded" count.
- The code name and the three specific operational points you are most worried about (the one assistant not yet on the list, the one printer location that is uncontrolled, the one Slack workspace where the deal-team channel might be guessed).
- The specific VDR configuration summary (number of access groups, number of clean-team documents, specific weekly audit owner).
- The specific executive-team briefing date and the specific 1:1 schedule for the 48-hour follow-up window.
- The specific deal-team-adds-only workflow owner and the specific escalation path.
- The specific leak-response named owners for each of the six elements.

## Starter guidance

Three anti-patterns to avoid:

- **"We'll add people as we need them, no need for a formal list."** The clean list is the artefact that lets the GC answer the specific question "who knew what, when" at a specific later point — in response to a specific SEC inquiry, a specific state attorney-general inquiry, or a specific litigation discovery request. A list that is not maintained does not help; a list that is maintained is both an operational discipline and a defensive record.
- **"The code name is just comms theatre."** The code name is the specific mechanism by which the specific out-of-hours exposure of a specific laptop screen, a specific calendar entry visible in a conference room, a specific overheard conversation does not immediately identify the target. It is a specific low-cost, high-value discipline. The slip-ups that cost deals are typically the ones where a specific executive forgot that the specific name mattered.
- **"The VDR access controls are the vendor's job."** The vendor provides the mechanism; the specific configuration is the deal-team's responsibility. A specific document uploaded under the wrong permission is a specific self-inflicted leak that is specifically detectable in a specific weekly access audit — but only if the specific audit is run.

## Acceptance criteria

You can demonstrate that:

- The transaction profile is populated with specific facts (not placeholder values) and is frozen for the module.
- The clean-list roster has specific named individuals or specific named role-slots across every category, with specific dated additions and specific workstream rationales. The "intentionally excluded" section is populated and credible.
- The code-name memo chooses a specific defensible name, identifies the specific venues the name is used in, and specifies the specific slip-up protocol.
- The VDR access-group map covers every specific category of document the deal will produce, specifies the specific clean-team wall, and specifies the specific weekly-audit owner and protocol.
- The executive-team briefing script is a specific usable artefact — a reader could execute the briefing from the document.
- The deal-team-adds-only workflow is a specific operational process — a reader could add a specific new individual by following the specific template.
- The leak-response playbook has specific named owners for each of the six elements and specific pre-drafted scripts rather than placeholders.
- A critical reader (deal-experienced GC, SVP-Corp-Dev, or senior corporate M&A partner) could disagree with a specific line in the package and see the specific evidence or specific judgement call that led to it.

## Reflection

Add a short reflection (½ page):

1. What is the single leak-vector you believe is most likely to compromise this specific transaction? What specific operational change in the package above would most reduce that risk?
2. Which specific individual on the clean list is the one whose removal from the deal team would most reduce the perimeter risk? (This is a hypothetical — not a recommendation to remove them.) What does that tell you about the specific point where need-to-know and need-to-execute diverge?
3. If a leak hit the WSJ at the end of week 2 of the sign-to-announcement window, which element of the leak-response playbook would you execute first and why?

## Stretch goals

- **MAR Article 18 insider list.** For a specific EU-regulated-securities issuer, convert the clean-list roster into the specific MAR Article 18 format (permanent section and event-specific section, with the specific prescribed data fields and the specific 5-year retention protocol). Reference Commission Implementing Regulation (EU) 2016/347 for the specific template.
- **Counterparty clean-list review.** Draft the specific letter from the sell-side GC to the buy-side GC requesting a specific representation that the buy-side has a specific clean-list discipline in place, with a specific proposed clean-list roster to be exchanged under NDA.
- **Workspace signal audit.** Walk the specific physical office (if there is one) during a specific normal workday and document the specific operational-fingerprint signals that an alert employee would notice (new conference-room reservations, unusual printer traffic, unfamiliar visitors through reception, calendar patterns, late-night light in a specific office). Score each signal on how much it reveals and propose a specific mitigation for each one.
- **Pre-signing leak-dry-run.** Simulate a specific leak event with a specific hypothetical rumour published by a specific outlet. Walk the specific playbook step-by-step through the first 4 hours, documenting each specific decision, each specific communication, and each specific artefact produced. Compare the simulated outcome to the specific pre-leak timeline and quantify the specific delta.
