# exercise-08: HSR, CFIUS, Foreign-Antitrust Filing Assessment

**Estimated effort:** 3.5 hours

## Objective

For a specific hypothetical transaction, assess the regulatory-filing exposure across HSR, CFIUS, and foreign-antitrust regimes. Translate the exposure into a specific signing-to-closing timeline, reverse-termination-fee structure, "outside date" recommendation, and interim-operating-covenant discipline. Then design the buyer's clearance-obligation covenant (from "commercially reasonable efforts" through "hell or high water") given the deal-specific risk profile. By the end you should be able to present a regulatory-filing plan to the board that translates filing exposure into concrete SPA design choices.

## Background

This exercise covers material from:

- [Chapter 9 — Regulatory-Filing Assessment: HSR, CFIUS, Foreign Antitrust](../09-regulatory-filing-assessment.md)

Chapter 1 (form choice) and chapter 2 (consideration mix) shape the filing profile; interim operating covenants and clearance covenants live in mod-104's SPA-drafting depth, but this exercise establishes the risk-allocation position from the mod-103 side.

## Prerequisites

- You have read chapter 9 in full.
- Familiarity with the FTC's Premerger Notification Program page and Treasury's CFIUS resources (see resources.md).
- Optional: recent WSGR, Cooley, Wilmer Hale, Cleary Gottlieb, or Skadden practitioner memos on merger-clearance trends. The 2023 Horizontal Merger Guidelines are worth skimming.

## The fact pattern

**Target:** Delaware C-corp developer of enterprise AI infrastructure software with $95M ARR. Business:
- **Products.** AI model orchestration and inference-serving platform. Software includes items that may be on the Commerce Control List for AI / semiconductor-related exports (verify at filing).
- **Customer base.** ~200 customers, including US federal-government customers (Department of Defense, intelligence community — modest but non-zero revenue), Fortune 500 enterprises, and international customers in EU, UK, and Japan.
- **Data.** Customers upload proprietary data (sometimes sensitive) for model fine-tuning; target maintains logs of customer data. Some customer usage patterns include telematics data on US persons at defined thresholds.
- **Employees.** ~250 employees. ~40% based outside the US (Ireland, Germany, India, Canada). ~15 employees hold US security clearances for the federal-customer work.

**Acquirer:** Publicly-listed European strategic (Netherlands-headquartered), $8B enterprise-software-focused. Has significant US operations (US subsidiary generates approximately $600M of the parent's $2B annual revenue). Prior US acquisition history includes 4 acquisitions in the last 5 years, all cleared without material issues. Acquirer does not have US federal-government customers currently.

**Transaction:**
- **Headline.** $780M — 80% cash / 20% acquirer stock.
- **Structure.** Reverse-triangular merger; target survives as wholly-owned subsidiary of acquirer.
- **Signing target.** 90 days from LOI.
- **Consideration flow.** Cash from acquirer's US subsidiary; stock issued by the Dutch parent.

**Regulatory context:**
- HSR filing clearly required (well above threshold).
- CFIUS filing: mandatory-vs-voluntary analysis is live given the Dutch acquirer, the target's technology (potential Commerce Control List items), and the sensitive-data / federal-customer footprint.
- EU Merger Regulation may apply given the aggregate parties' revenues.
- UK CMA may voluntarily notify given UK customer revenue.
- Additional foreign-antitrust filings may be required (Japan JFTC, Germany BKartA — verify against thresholds).

## Tasks

### 1. HSR analysis

**1.1 — Reportability determination.**
- Confirm HSR reportability. The transaction value ($780M) is well above the size-of-transaction threshold. Confirm using current-year FTC threshold data (see resources.md).
- Identify the filing fee tier and current filing fee (per FTC published tiers).
- Note which party (buyer or seller, or both) files — HSR requires both to file; the waiting period starts when the last-filed party files.

**1.2 — Substantive antitrust risk assessment.**
- **Horizontal overlap.** Does the acquirer have competing products or services in the target's AI-infrastructure category? Assume the acquirer has a competing (though smaller) AI-inference product line — write down what this means for the horizontal-overlap risk.
- **HHI screening.** In the "AI model orchestration and inference-serving" market (assume this is a plausible relevant market), estimate the HHI pre- and post-transaction. If the market has 4-5 material competitors, this is a moderately concentrated market. Post-merger HHI increase is a material factor in FTC/DOJ analysis.
- **Second Request risk.** Given tech-sector-focused enforcement in the 2020s, what is your estimate (low/medium/high) of a Second Request risk? Support with 3-4 specific reasons.
- **Killer-acquisition angle.** Is there a plausible "acquirer buying target to neutralise future competition" narrative? What internal documents (Item 4(c)) would the target need to be careful about drafting to avoid setting the wrong tone?

**1.3 — Timeline estimate.**
- Base case (no Second Request): 30-day initial waiting period + closing.
- With Second Request: 3-6 months of substantial-compliance work + 30-day post-compliance waiting period.
- Range: how long from signing to HSR clearance?

### 2. CFIUS analysis

**2.1 — Jurisdictional determination.**
- **Foreign acquirer.** Yes — Dutch parent.
- **US business.** Yes — target is Delaware C-corp.
- **TID US business assessment.** Is the target a Technology, Infrastructure, or Data (TID) US business under 31 C.F.R. Part 800? Assess each of:
  - **Critical Technology (T).** Does the target produce, design, test, manufacture, or develop items subject to US export controls (ITAR / EAR / Commerce Control List)? AI, semiconductor-adjacent, and emerging-technology items are common flags.
  - **Critical Infrastructure (I).** Does the target's business relate to critical-infrastructure sectors (defense, energy, telecom, financial services, healthcare, water)? Probably not directly, but note any federal-customer relationships.
  - **Sensitive Personal Data (D).** Does the target maintain or collect sensitive personal data on US citizens above defined thresholds (genetic, financial, health, biometric, geolocation)? The telematics data at defined thresholds is a specific flag.

**2.2 — Mandatory vs. voluntary filing determination.**
- Foreign-government-investor analysis: is 25%+ of the Dutch acquirer's parent held by a foreign government? Assume no.
- Critical-technology-triggering-conditions analysis: do the target's technologies fall into the mandatory-notification categories under 31 C.F.R. § 800.401?
- Recommend: mandatory filing (if triggered), voluntary filing (if not mandatory but risk exists), or no filing (if clearly outside CFIUS jurisdiction).

**2.3 — Declaration vs. notice.**
- Short-form declaration (5-page, 30-day assessment period): appropriate if you expect a clean review.
- Full notice (45-day review + 45-day investigation potential): appropriate if complexity or specific concerns are anticipated.
- Recommend and justify.

**2.4 — Timeline and mitigation-agreement risk.**
- Base case: 30-day declaration review (if declaration path); 45-day notice review + optional 45-day investigation (if notice path).
- Mitigation-agreement risk: is CFIUS likely to require specific commitments (board composition restrictions, information-access limits, US-person management, ongoing reporting)? What operational impact would each of these have on the acquirer?
- Range: how long from signing to CFIUS clearance?

### 3. Foreign-antitrust filing analysis

For each of the following jurisdictions, determine whether a filing is required based on the parties' activities:

**3.1 — EU Merger Regulation (EUMR).**
- Combined worldwide turnover: acquirer $2B + target $95M ARR. Threshold: €5B (>~$5.5B). Likely below the primary threshold. But the alternative €2.5B / €100M threshold with Member-State-specific requirements may apply.
- EU-wide turnover of each party: does the acquirer have €250M+ EU-wide turnover? What about the target? Target has EU customers; approximate EU revenue?
- Recommend: EUMR filing required / not required. If required, expected 25-working-day Phase I review timeline.

**3.2 — UK CMA.**
- UK turnover of target exceeding £70M? Target's UK revenue is estimated at 10-15% of total = $9.5-14M — well below £70M threshold.
- Share-of-supply test (25%+ share in a UK market)? Assume no.
- CMA notification: voluntary — the parties can choose to notify. Recommend based on risk analysis.

**3.3 — Germany BKartA.**
- Turnover thresholds and transaction-value threshold. Assess whether German revenue / activities of the parties would trigger the German premerger-notification requirement.
- Recommend.

**3.4 — Other jurisdictions.**
- Japan JFTC: threshold-based analysis. Japan turnover of the parties?
- India CCI: threshold-based. Any India revenue?
- Brazil CADE: threshold-based.
- Canada Competition Bureau: threshold-based.
- China SAMR: RMB 2B China turnover threshold. Any China revenue? Chinese SAMR filings can materially delay closing.

Produce a **foreign-antitrust filing matrix** (table) showing:

| Jurisdiction | Threshold met? | Filing required (mandatory/voluntary)? | Estimated Phase I / Phase II timeline | Filing complexity |
|---|---|---|---|---|
| EU (EUMR) | | | | |
| UK CMA | | | | |
| Germany BKartA | | | | |
| Japan JFTC | | | | |
| Others | | | | |

### 4. Aggregate filing-timeline analysis

Combine the HSR, CFIUS, and foreign-antitrust timelines into a single closing-timeline picture:

- **Best case (all clearances arrive on schedule):** what is the signing-to-closing gap?
- **Base case (moderate complications; no Second Request, one foreign filing has a Phase II):** what is the gap?
- **Worst case (HSR Second Request + CFIUS full notice with mitigation + Phase II in one foreign jurisdiction):** what is the gap?

Present a Gantt-style timeline showing each filing's expected clearance path.

### 5. SPA-design implications

Translate the timeline analysis into specific SPA-design positions:

**5.1 — Outside date.**
- Recommend an outside date beyond which either party can walk. Should include a buffer over the base-case timeline; typically 3-6 months beyond the base-case expected close. What is your recommendation and rationale?
- Include extension mechanics: under what conditions can either party unilaterally extend the outside date (e.g., if a Second Request is still active)?

**5.2 — Buyer's clearance-obligation covenant.**
- Choose from:
  - "Commercially reasonable efforts." Buyer must try but not required to accept divestitures or specific commitments.
  - "Reasonable best efforts." Stronger than "commercially reasonable" but not "hell or high water."
  - "Hell or high water" — buyer must accept any divestiture, behavioural remedy, or condition to obtain clearance.
- Which do you recommend for this transaction, and why?
- If less than "hell or high water," what specific carve-outs or exceptions do you propose (e.g., "hell or high water except for divestitures exceeding $X in aggregate value or $Y in annual revenue")?

**5.3 — Reverse-termination fee.**
- Recommend a reverse-termination fee (buyer pays if transaction is blocked by regulatory failure attributable to the buyer). Benchmark: 4-8% of transaction value in high-antitrust-risk deals.
- For this transaction, given the moderate horizontal-overlap risk plus material CFIUS exposure, what specific dollar RTF do you propose?
- Under what specific triggers is the RTF payable? Any carve-outs (e.g., not payable if antitrust failure is caused by seller's non-cooperation)?

**5.4 — Interim-operating covenants.**
- What restrictions on the target's operations between signing and closing do you propose?
- For a long-close deal (6-12 months), interim-operating covenants are more critical. Consider:
  - Ordinary-course-of-business operations.
  - Restrictions on new employment contracts / material bonuses.
  - Restrictions on new material contracts (customer, vendor, or partner).
  - Restrictions on capital expenditures above thresholds.
  - Restrictions on price changes / discounting.
  - Restrictions on filings, patents, or IP transactions.
- The seller wants operational flexibility; the buyer wants the business preserved. Where is the appropriate line?

**5.5 — Filing preparation timeline.**
- HSR filing: draft ready 30-45 days after signing (Item 4(c) diligence and revenue-code categorisation take time).
- CFIUS filing: 30-45 days for declaration; 45-60 days for full notice.
- Foreign filings: 60-90+ days for complex multi-jurisdictional preparation.
- What is the filing-preparation schedule from signing?

### 6. Board memo

Draft a **1-page board memo** that:

- Names the filings required (HSR, CFIUS declaration/notice, EU, UK, Germany, other).
- Presents the aggregate timeline in best/base/worst case.
- Names the recommended SPA-design positions on outside date, clearance-obligation covenant, reverse-termination fee, and interim-operating covenants.
- Flags the specific risks the board should monitor between signing and closing.
- Estimates the aggregate filing cost (filing fees + counsel fees) and timeline impact.

## Starter guidance

- **HSR filing analysis is threshold-mechanical but substantive review is judgment-heavy.** The threshold analysis is straightforward — check the current FTC threshold, verify transaction value exceeds it, done. The substantive antitrust risk analysis is where market definitions and enforcement-policy calibration matter.
- **CFIUS scope is broader than founders often realise.** Post-FIRRMA, CFIUS reaches non-controlling investments in TID US businesses. AI companies and sensitive-data companies routinely have CFIUS exposure. Do not default-assume CFIUS is only for Chinese buyers of defense contractors.
- **Foreign antitrust is often the biggest surprise.** A transaction with clear HSR profile and no CFIUS risk can be materially delayed by an EU or China filing that the parties did not scope early enough. The systematic multi-jurisdictional screen is the discipline.
- **"Hell or high water" is a strong ask.** Buyers resist it for good reason — it commits them to divestitures they may not want to make. For a moderate-risk deal, "reasonable best efforts" with specific divestiture-value caps is often the compromise.
- **Reverse-termination fee is the seller's substitute for expectation damages.** Under-negotiate it and the seller has no material remedy if the buyer walks. Over-negotiate it and the buyer views the transaction as economically riskier.

## Acceptance criteria

You can demonstrate that:

- HSR reportability, filing fee, and Second Request risk are analysed and quantified.
- CFIUS jurisdictional determination (TID US business), mandatory-vs-voluntary filing, and declaration-vs-notice recommendation are made and defended.
- Foreign-antitrust filing matrix is complete for at least 5 jurisdictions.
- Aggregate filing-timeline analysis in best/base/worst case is documented.
- SPA-design recommendations on outside date, clearance covenant, RTF, and interim covenants are specified.
- Board memo is 1 page and would be presentable.

## Reflection

Add a short reflection:

1. Which filing regime posed the *biggest* timeline uncertainty for this transaction — HSR Second Request risk, CFIUS mitigation-agreement risk, or foreign-antitrust Phase II risk? What would you tell the founder-CEO to prepare them mentally for the range of outcomes?
2. If the acquirer were a US buyer (instead of a Dutch buyer), how would the CFIUS analysis change? What percentage of the total filing timeline is CFIUS-driven?
3. For the buyer's clearance-obligation covenant, if the buyer refuses "hell or high water" and insists on "commercially reasonable efforts," what is the seller's realistic negotiation position? What compensating protection (higher RTF, longer outside date, specific divestiture carve-outs) would you accept as trade-offs?
4. If a Second Request were issued in month 3 post-signing, what is the seller's board's most important operational decision at that point? Continue running the business normally, prepare for a possible deal failure, or pivot to protect optionality?

## Stretch goals

- **Read a real Second Request notice.** These are public in certain FTC / DOJ enforcement actions. Note the categories of information requested and the operational burden implied.
- **Read Broadcom / Qualcomm CFIUS case.** The 2018 Presidential order blocking the Broadcom acquisition of Qualcomm is the highest-profile CFIUS block. Note what specific national-security concerns motivated the intervention.
- **Read a merger-control practitioner memo.** WSGR, Cleary Gottlieb, Cravath, Skadden all publish periodic memos on merger-clearance trends. Read one and note recent enforcement themes that would affect this specific transaction.
- **Reverse-termination fee benchmark.** Research 5-10 recent transactions with material antitrust risk that included a reverse-termination fee. What percentage of transaction value did the fee represent? What were the specific triggers?
- **Interim-operating covenant redline.** Draft a full interim-operating covenant section (5-8 sub-sections) for the SPA. This is a specific drafting discipline that mod-104 develops further; use this exercise to build a first-draft position.
