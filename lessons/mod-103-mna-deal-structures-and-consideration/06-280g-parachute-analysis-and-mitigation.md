# IRC §280G Golden-Parachute Analysis and Mitigation

## Why this matters

IRC §280G imposes a punitive tax regime on "excess parachute payments" — change-of-control-related compensation to certain executives and other disqualified individuals — that exceeds a specified threshold. If triggered, §280G produces two economic consequences: the recipient pays a **20% federal excise tax** on the excess portion of the parachute payment (in addition to ordinary income tax), and the corporation making the payment loses the **corporate deduction** for the excess portion under §280G(a). For a mid-size transaction with a founder-CEO receiving $10M of accelerated equity vesting, a change-of-control cash bonus, and a modest severance arrangement, the §280G cost can easily exceed $2M in combined excise tax and lost corporate deduction — a cost that lands on the company and its shareholders through reduced net proceeds or increased buyer-side deal expense.

Left unmitigated, §280G is one of the most economically consequential tax provisions in an M&A transaction. Fortunately, §280G is *addressable* for private-company targets: IRC §280G(b)(5) provides a **shareholder-vote exception** that can cleanse parachute payments from §280G treatment for private companies. Public-company targets do not have access to the shareholder-vote exception and must rely on other mitigation techniques (cutback provisions, value-shifting into reasonable-compensation buckets, pre-close bonus payments outside the change-of-control window).

This chapter installs the §280G analysis mechanics — who is a disqualified individual, what is a parachute payment, how the base amount is computed, when the 3x threshold is crossed — and the mitigation techniques (specifically the §280G(b)(5) shareholder vote for private companies, cutback drafting, value-shifting, and pre-close-bonus techniques). This is education, not tax advice — a live §280G analysis requires qualified tax counsel with specific §280G expertise, and the calculations involve substantial technical judgment.

## The §280G threshold and the excise tax

§280G imposes its regime on "parachute payments" to "disqualified individuals" that in aggregate equal or exceed **three times the disqualified individual's base amount**. When the 3x threshold is crossed:

- The **entire parachute payment** in excess of one times the base amount (the "excess parachute payment") is subject to a 20% federal excise tax under IRC §4999, imposed on the recipient (not withheld by the payor for excise-tax purposes, though income tax withholding still applies to the compensation portion).
- The corporation **loses its deduction** under §162 for the excess parachute payment portion. For a corporation with a 21% federal corporate tax rate, this means the corporation effectively pays 21% additional tax on the excess parachute portion.

Note the cliff structure: if the aggregate parachute payment is at 2.99x the base amount, no excise tax and no lost deduction. If it is at 3.00x, the *excess portion* (everything above 1x the base amount, i.e., the 2.00x portion) is fully subject to both consequences. A dollar's difference in aggregate payment across the 3x threshold triggers meaningful tax on the entire 2x-of-base-amount excess.

## Who is a "disqualified individual"?

Under §280G(c), a disqualified individual is a "shareholder, officer, or highly-compensated individual" of the corporation. The categories:

- **Officers.** The corporation's officers, subject to a maximum count. §280G looks to the greater of three individuals or 10% of the corporation's employees (capped at 50), designated in order of compensation. For a small startup with 30 employees, that is 3 officers; for a company with 400 employees, that is 40 officers (capped).
- **Shareholders.** Individuals who own more than 1% of the corporation's stock (measured under §280G specifics that consider both direct and indirect ownership). Founders holding meaningful stock positions are typically shareholders under this test.
- **Highly-compensated individuals.** The lesser of the top 250 compensated employees or 1% of the employees, subject to an income threshold that is adjusted annually (the threshold applies to the year of the change of control; verify the current threshold with counsel or the applicable IRS guidance).

The disqualified-individual analysis has to be run for each individual who might be a recipient of change-of-control payments, and the analysis has to be done as of the date of the change in control (not, e.g., as of the LOI signing date or the merger agreement signing date).

## What is a "parachute payment"?

Under §280G(b)(2), a parachute payment is compensation to a disqualified individual that is *contingent on* a change of ownership or effective control of the corporation. The key elements:

- **Contingency on change of control.** The payment must be linked to the change-of-control event. A payment that would have been made regardless of the transaction is not a parachute payment. A payment that is triggered *by* the transaction is.
- **Present value at change of control.** Parachute payments are measured at their present value as of the date of the change in control, using a specified discount rate (120% of the applicable federal rate under §280G rules).
- **Categories of parachute payments.** Common categories in an M&A context:
  - **Cash bonuses** paid at closing or contingent on the transaction (change-of-control bonuses, transaction bonuses, MIP payouts).
  - **Accelerated vesting** of equity awards (RSUs, options, restricted stock) that vest upon the change of control. The accelerated portion's value is the parachute payment amount for this component; the value is measured at closing.
  - **Severance payments** contingent on termination in connection with the transaction (single-trigger severance, double-trigger severance triggered post-close).
  - **Retention payments** that are payable in connection with the change of control (as opposed to retention payments contingent solely on continued employment without change-of-control triggers).
  - **Fringe benefits and other benefits** enhanced or provided in connection with the transaction (continued health coverage, gross-ups on other benefits).

Not every payment is a parachute payment. Payments that are *not* contingent on the change of control (regular cash comp, existing deferred comp that vests on ordinary schedule) are not parachute payments. Payments that would have vested on schedule and are only *accelerated* by the change of control have the acceleration portion counted (typically valued using specified §280G rules for the accelerated portion) but not the entire underlying award.

## The base-amount calculation

The **base amount** is the disqualified individual's average annual compensation from the corporation over the **five taxable years immediately preceding the year of the change in control** (or the individual's period of employment if less than five years).

- **Compensation included.** All W-2 wages and, generally, similar compensation from the corporation and its affiliates. Deferred compensation, bonus, equity income (on exercise or vesting), and other forms of taxable compensation.
- **Compensation excluded.** Amounts not included in W-2 income (e.g., pre-tax retirement contributions, non-taxable fringe benefits).
- **Prorating for short periods.** If the disqualified individual was employed for less than five years, the base amount is computed over the shorter period, with annualisation adjustments as specified in §280G regulations.
- **Practical implication.** A founder-CEO whose W-2 compensation has been modest (say, $200K/year for the past five years while equity accrued but had not yet been realised) has a base amount of ~$200K. The 3x threshold is ~$600K; anything above that is excess parachute. A modest change-of-control acceleration on the founder's equity can easily cross $600K, triggering §280G.

The base-amount calculation is where the practical severity of §280G is most visible for founder-CEOs: because founder cash compensation is often modest relative to equity value, the base amount is small, and the 3x threshold is easy to cross with even modest change-of-control payments and equity acceleration.

## The 3x safe harbour and the excess parachute payment

- **3x safe harbour.** If aggregate parachute payments to a specific disqualified individual are less than 3 times the base amount, §280G does not apply — no excise tax, no lost deduction. The 3x threshold is a *safe harbour*, not a target to hit exactly.
- **Excess parachute payment.** When the 3x threshold is crossed, the excess parachute payment is defined as the aggregate parachute payment *minus 1x the base amount* (not minus 3x). If a founder has a $200K base amount and receives $1M of parachute payments, the aggregate is 5x base, above the 3x safe harbour, and the excess parachute payment is $800K ($1M minus $200K). The 20% excise tax applies to the full $800K ($160K excise tax), and the corporation loses the $800K deduction.
- **Cliff effect.** The 3x threshold is a cliff. At 2.99x, zero §280G consequences. At 3.00x, full consequences on the excess portion.

## Mitigation techniques

### 1. §280G(b)(5) shareholder-vote cleanse (private companies only)

The most powerful §280G mitigation for private companies. Under §280G(b)(5), if the corporation is *not* readily-tradable (i.e., is not publicly traded) at the time of the change in control, parachute payments can be **cleansed** from §280G treatment via a shareholder vote.

- **Vote requirement.** More than 75% of the *voting power* of the corporation's stock (excluding stock held by the disqualified individuals whose parachute payments are being cleansed) must approve the specific parachute payments after adequate disclosure. Note: the "disqualified individuals" whose payments are being cleansed are excluded from the vote; those individuals' stock is disregarded from both the numerator and denominator.
- **Disclosure requirement.** All material facts about the parachute payments must be disclosed to the voting shareholders before the vote. In practice, this is a detailed disclosure document identifying each disqualified individual, their base amount, the specific parachute payments, the calculation of the excess parachute portion, and the specific §280G tax consequences that would apply if the cleanse fails.
- **Cleanse effect.** If more than 75% of the non-disqualified voting power approves after adequate disclosure, the parachute payments are cleansed — no excise tax, no lost deduction.
- **Practical execution.** The §280G shareholder-vote process is a specific choreography that runs in parallel with the merger-approval vote. Timing typically has the §280G cleanse vote conducted *before* the merger closing (so the cleanse is effective for the closing-triggered payments). The vote materials, the calculation, and the disclosure are prepared by tax counsel with specific §280G expertise.

For a venture-backed private-company target, the §280G(b)(5) shareholder vote is the standard mitigation, and it is highly effective when done properly. The specific execution complexity — getting the vote conducted with proper disclosure and threshold satisfaction — is non-trivial but well-established in practitioner practice.

### 2. Cutback provisions

A **cutback** is a contractual mechanism in the employment agreement or transaction documents that reduces (cuts back) parachute payments to a level that stays *below* the 3x threshold, avoiding §280G application.

- **Best-net cutback.** The parachute payments are reduced to the level that maximises the recipient's after-tax amount. In some cases, cutting back is worse for the recipient than paying full and absorbing the excise tax (because the excise tax is only 20% of the excess portion, and the recipient still keeps 80% of the excess). The best-net cutback computes both scenarios and applies whichever produces the higher after-tax amount to the recipient.
- **Automatic cutback.** The parachute payments are reduced to just below the 3x threshold regardless of best-net analysis.
- **Practical use.** Cutback provisions are common in public-company employment agreements (where §280G(b)(5) is not available) and in private-company employment agreements as a backstop in case the §280G(b)(5) vote fails. They may also be used for specific parachute-payment components that are known to push a disqualified individual over the 3x threshold.

### 3. Value-shifting into reasonable-compensation buckets

Payments that are properly characterised as **reasonable compensation for services rendered post-change-of-control** are *not* parachute payments — the §280G regulations exclude reasonable-comp payments for future services. This creates a mitigation opportunity: structuring post-close compensation (whether ongoing salary, bonus, or restricted stock retention grants tied to post-close performance) as reasonable comp reduces the parachute-payment total.

- **Requirement.** The compensation must be *reasonable* under §280G reasonable-compensation analysis (which is more stringent than the general §162 reasonable-comp analysis) and must be for *services rendered post-change of control* (not services rendered pre-change of control).
- **Documentation.** The reasonable-compensation characterisation should be documented at signing with an explicit rationale, employment agreement terms that support the reasonable-comp characterisation, and (in some cases) a valuation opinion from an independent compensation consultant.
- **Practical use.** Value-shifting is common for founder-CEOs who continue post-close in an operating role. The retention-grant portion of their consideration, if properly characterised as reasonable comp for the post-close services, can substantially reduce the parachute-payment total that would otherwise trigger §280G.

### 4. Pre-close bonus payments outside the change-of-control window

Payments made *before* the change of control are not parachute payments — parachute payments are defined by their contingency on the change of control. This creates a technique: paying a bonus *before* the change of control (or, more precisely, before the specific §280G measurement window) reduces the aggregate parachute-payment total.

- **Timing.** The specific timing requirements are governed by §280G rules. In general, payments made well before the change-of-control transaction (and not contingent on it) are not parachute payments. Payments made close to the change of control that could be characterised as contingent on it may still be treated as parachute payments.
- **Practical use.** For companies planning a transaction with a foreseeable close date, spot bonuses paid to key executives 6–12 months pre-close can materially reduce the base amount recomputation problem (though caution is required — payments that appear to be pre-close bonus payments but are actually structured as change-of-control bonuses may be re-characterised).

### 5. Increasing the base amount over time

Because the base amount is the 5-year average W-2 compensation, increasing an executive's W-2 compensation over the 5 years pre-close raises the base amount and pushes the 3x threshold higher. This is not a *specific* §280G technique but is a design consideration in ongoing executive-compensation planning for a company on a plausible M&A trajectory.

- **Practical use.** A founder-CEO whose cash compensation has been kept artificially low (say, $150K/year) while equity has accrued value is exposed to §280G when the transaction happens. Increasing cash compensation to $400K/year for the 3 years before the transaction raises the base amount to something like $300K (weighted average of the $150K and $400K years), which pushes the 3x threshold to $900K. The tax planning is an *ongoing* consideration, not a transaction-window consideration — but its consequences appear at the transaction.

### 6. Gross-up (rarely used post-2010)

Historically, some employment agreements included a **§280G gross-up** — the corporation would pay the executive additional compensation to cover the §280G excise tax and the additional taxes on the gross-up itself, iteratively grossed up until the executive was made whole. Post-2010, the practitioner and shareholder-governance consensus has strongly disfavoured gross-ups (ISS and Glass Lewis vote against companies whose executive employment agreements include §280G gross-ups); most modern employment agreements do not include them. Cited here for completeness.

## The §280G analysis workflow

For a specific transaction, the §280G analysis typically runs on the following timeline:

1. **Preliminary analysis (LOI or early diligence).** Identify the disqualified individuals, gather their W-2 history for the base-amount calculation, catalog the parachute-payment components (change-of-control cash bonuses, equity acceleration, severance, retention). Preliminary calculation of the excess parachute-payment exposure.
2. **Structuring decisions (SPA drafting).** Design the transaction bonus, retention, and equity-treatment structure with §280G exposure in mind. Value-shift into reasonable-comp buckets where possible. Include cutback provisions in employment agreements where appropriate.
3. **§280G shareholder-vote materials preparation (for private companies).** Tax counsel prepares the specific vote materials — disclosure document, calculation supporting materials, vote solicitation.
4. **§280G shareholder vote (for private companies).** Conducted before closing; typically bundled with the merger-approval solicitation to non-disqualified shareholders.
5. **Closing.** Payments made per the cleansed structure (if vote succeeded) or subject to the fallback cutback (if vote failed).
6. **Post-close reporting.** IRS Form W-2 reporting includes any §280G excess parachute payments; Form 1099 or W-2 reporting of the 20% excise tax as necessary; corporation's tax return reflects lost deduction.

## Common pitfalls and practitioner notes

- **Base-amount miscalculation.** The 5-year W-2 average is a specific calculation; short-tenure executives get proportional adjustments; certain payments are included and others excluded. Miscalculating the base amount produces a wrong 3x threshold and a wrong excess parachute calculation. Tax counsel supplies the calculation.
- **Missed disqualified individuals.** The disqualified-individual test can be wider than expected — the 1%-shareholder test can catch employees with material stock accumulations that were not previously considered "executives." Miss one and the §280G exposure is under-modelled.
- **Equity acceleration valuation.** Accelerated equity is valued at closing per §280G specific rules — the acceleration-portion valuation is not simply "the value of the accelerated shares" but a specific calculation reflecting the time value of the acceleration.
- **§280G(b)(5) vote logistics.** The 75%-of-non-disqualified-voting-power threshold is exclusive of the disqualified individuals' stock. For a company where founders hold 30%+ of the voting stock, the vote requires 75% of the remaining 70%, which is 52.5% of the total voting power — a substantial requirement that can fail if minority shareholders decline to vote or vote against. Vote-solicitation choreography matters.
- **Public-company target.** Because §280G(b)(5) is not available, public-company targets rely on cutback, reasonable-comp, and pre-close-bonus techniques. §280G exposure at public-company targets is often material and drives significant negotiation on executive-comp arrangements.
- **Buyer-side impact.** Some parachute payments are made by the buyer post-close (retention grants issued by the acquirer, transaction bonuses paid by the acquirer at closing). The §280G analysis needs to include these buyer-payment components; failure to do so under-models the exposure.
- **State tax parallels.** Some states have parallel golden-parachute rules (e.g., some states include state-level excise tax); the federal analysis does not automatically cover state exposure.

## Interaction with the other tax provisions

- **§409A (chapter 7).** Retention payments and earn-outs must comply with §409A regardless of §280G treatment. A payment structure that mitigates §280G exposure may create §409A compliance issues if not carefully drafted; the two provisions must be co-designed.
- **§1202 QSBS (chapter 8).** §280G excise-tax exposure and corporate-lost-deduction exposure are separate from the §1202 exclusion for qualifying stock; a §280G payment does not reduce a shareholder's QSBS exclusion, but the excise-tax cost falls on the recipient.
- **Consideration mix (chapter 2).** The management-carve-out mechanism (chapter 2) creates parachute payments to founders and executives that trigger §280G analysis. The carve-out design must run through §280G before the economics can be finalised.

## Summary

IRC §280G imposes a 20% federal excise tax on excess parachute payments to disqualified individuals and denies the corporation the deduction on the excess portion. The threshold is 3 times the individual's 5-year average W-2 compensation, and the excess portion (above 1x base) triggers the full consequences when the 3x threshold is crossed. Private companies can address §280G through the §280G(b)(5) shareholder-vote cleanse, which requires more than 75% of non-disqualified voting power to approve after adequate disclosure. Public companies rely on cutback provisions, value-shifting into reasonable-compensation buckets, and pre-close-bonus techniques. §280G is one of the most economically consequential tax provisions in an M&A transaction — for a founder-CEO with modest W-2 history and material change-of-control payments, unmitigated §280G can easily consume $2M+ of value. The analysis and mitigation choreography require qualified tax counsel with specific §280G expertise, and the timing of the analysis (starting at LOI, not at signing) determines whether mitigation is available.
