# IRC §409A Timing Constraints on Earn-Outs and Transaction Bonuses

## Why this matters

IRC §409A governs the taxation of *nonqualified deferred compensation* — compensation that a service provider (typically an employee or an independent contractor) earns in one year but that is paid in a later year, unless it fits within a specific exception. §409A was enacted in 2004 in response to the Enron collapse, where executives were perceived to have used deferred-compensation arrangements to time the receipt of compensation to their tax advantage. It imposes strict rules on the *timing* of deferred-comp payments, and on the elections service providers can make about that timing. If a compensation arrangement violates §409A, the consequences are severe: the deferred compensation is *currently taxable* to the recipient in the year of the violation, plus a **20% federal additional tax** (in addition to ordinary income tax) is imposed on the recipient, plus (in some cases) a premium interest tax under §409A(a)(1)(B).

In the M&A context, §409A matters because two common structural elements — **earn-outs** paid to founders / executives / employees who remain in service post-close, and **transaction bonuses** paid at closing to employees who are service providers — can constitute deferred compensation subject to §409A. If not structured to comply with §409A (either through a specific exemption or through a compliant deferred-compensation arrangement), the recipient pays a punishing tax and the transaction's employee-retention economics fall apart.

This chapter installs the §409A framework as it applies to M&A structures, the two key exemptions that most M&A payments rely on (the short-term-deferral exception and, more limitedly, the separation-pay exception), the substantial-risk-of-forfeiture concept that keeps some payments outside §409A, and the drafting mechanics that keep earn-outs and transaction bonuses §409A-compliant.

> **Reminder: education, not tax advice.** §409A analysis in a live transaction requires qualified tax counsel with specific §409A expertise. The framework here supports engagement with that counsel, not substitution.

## The §409A framework

§409A applies to any arrangement that is a **nonqualified deferred-compensation plan** — a plan providing for the deferral of compensation, other than qualified plans (401(k), pensions) and certain welfare-benefit plans. When §409A applies, it requires that:

- **Payment timing.** The plan must specify (either at the time of the deferral or as of a permitted payment event) *when* the compensation will be paid. Permissible payment events include:
  - **Separation from service** (with a 6-month delay for "specified employees" of publicly traded corporations under §409A(a)(2)(B)(i)).
  - **A specified time or fixed schedule** at the time of deferral.
  - **Change in control** of the corporation (as defined in §409A regulations, not to be confused with the §280G change-of-control definition).
  - **Disability** or **death** of the service provider.
  - **Unforeseeable emergency** of the service provider (narrowly defined).
- **No acceleration.** Once payment timing is fixed, acceleration of payment is generally prohibited except in very specific circumstances (plan termination and liquidation, certain domestic-relations orders, etc.).
- **Deferral elections.** Elections to defer compensation must generally be made before the year in which the service is performed (for annual elections) or within 30 days of first becoming eligible (for initial-eligibility elections).
- **Redeferral.** Once compensation is set for payment, redeferral (pushing the payment out further) requires the election to be made at least 12 months in advance and to push the payment out at least 5 years.

Violation of any of these rules triggers the §409A consequences described above.

## The short-term-deferral exception

The most important exemption for M&A payments: under Treasury Regulation §1.409A-1(b)(4), a payment is not subject to §409A if it is paid no later than the **15th day of the third month** after the end of the *earlier* of the recipient's tax year or the service provider's (payor's) tax year in which the right to the payment ceases to be subject to a **substantial risk of forfeiture**.

- **Applied to calendar-year taxpayers:** for compensation that vests (i.e., ceases to be subject to substantial risk of forfeiture) at any point in year Y, the short-term-deferral exception requires payment by March 15 of year Y+1.
- **Applied to bonuses paid at closing:** a transaction bonus that vests (ceases to be subject to substantial risk of forfeiture) at closing on, say, June 15, 2026, and is paid on the same day, satisfies the short-term-deferral exception — the vesting and payment are simultaneous.
- **Applied to earn-outs:** an earn-out payment that vests when the earn-out target is achieved, and is paid within 2.5 months after year-end of the year of achievement, satisfies the short-term-deferral exception. An earn-out that vests in year Y (target achieved during year Y) and is paid in year Y+1 within the 2.5-month window is exempt.

The short-term-deferral exception is what most M&A transaction bonuses and many earn-outs rely on for §409A compliance. Getting the payment timing right — specifically, ensuring the payment falls within the 2.5-month window after the year of vesting — is the primary §409A compliance mechanism for these arrangements.

## Substantial risk of forfeiture

The **substantial-risk-of-forfeiture** ("SRF") concept is central to §409A. Compensation is subject to SRF if its receipt is conditioned on:

- The **performance of substantial future services** by the recipient, or
- The **occurrence of a condition related to a purpose of the compensation** (e.g., a specified performance metric), where the possibility of forfeiture is substantial.

Compensation *not* subject to SRF is "vested" for §409A purposes; once vested, the short-term-deferral clock starts running.

For earn-outs specifically:

- **Earn-outs conditioned on continued employment.** If the earn-out is payable *only if* the recipient continues to be employed through the earn-out measurement date, the earn-out is subject to SRF until the measurement date. Then the short-term-deferral clock starts.
- **Earn-outs conditioned on performance without employment condition.** If the earn-out pays out based purely on the target's performance without a continued-employment requirement, the SRF may be considered released at signing (or at some earlier event) — a different §409A analysis applies, and the arrangement may be treated as deferred comp subject to §409A rather than as short-term deferral. This is often the case for earn-outs paid to shareholders (whether or not they are employees) in their capacity as shareholders.
- **Earn-outs to non-employee shareholders.** If the earn-out payment is to a shareholder in their capacity *as a shareholder* (i.e., as consideration for the sale of their stock, not compensation for services), §409A does not apply — §409A applies to compensation for services, not to purchase-price consideration. The characterisation matters and is fact-specific.

The distinction between purchase-price consideration and compensation for services is one of the most consequential §409A questions in an M&A context. An earn-out that is characterised as purchase-price consideration is outside §409A entirely; one that is characterised as compensation is inside §409A and must comply.

## Applying §409A to specific M&A payment types

### Transaction bonuses (change-of-control cash bonuses)

A cash bonus paid to an employee at closing, contingent on the closing occurring and (typically) on the employee being employed at closing.

- **§409A analysis.** If the bonus vests at closing (employee employed at closing = SRF released) and is paid at closing (payment within 2.5 months of year-end), the short-term-deferral exception applies. §409A-compliant.
- **Drafting.** The bonus arrangement should specify that the payment is contingent on employment through closing and that the bonus is paid at closing (or, if deferred slightly, within the 2.5-month post-year-end window).

### Retention bonuses paid over time post-close

A retention bonus paid over 2 or 3 years post-close, contingent on continued employment.

- **§409A analysis.** Each tranche of the retention bonus vests when the continued-employment condition is satisfied for that tranche. If each tranche is paid within 2.5 months of the year of vesting, the short-term-deferral exception applies to each tranche.
- **Drafting.** Each tranche should be structured with a specific vesting date and payment window that satisfies the short-term-deferral exception. Alternatively, the retention bonus can be structured as §409A-compliant deferred comp with fixed payment timing.

### Earn-outs paid to founders and executives

An earn-out payable over 24 months post-close based on the acquired business's performance, contingent on the founder / executive being employed at the earn-out measurement date.

- **§409A analysis (compensation characterisation).** If the earn-out is characterised as compensation (because the continued-employment condition looks compensatory), the earn-out is subject to §409A. If each earn-out payment is made within 2.5 months of the year of vesting (i.e., achievement date), the short-term-deferral exception applies.
- **§409A analysis (purchase-price characterisation).** If the earn-out is characterised as purchase-price consideration (paid to the founder / executive in their capacity as former shareholder, not as employee), §409A does not apply.
- **Drafting.** The specific language of the earn-out matters. Purely performance-contingent earn-outs (no employment condition) tend to be characterised as purchase-price. Continued-employment-contingent earn-outs tend to be characterised as compensation and need to satisfy §409A. The specific characterisation is fact-dependent, and tax counsel makes the call.

### Rollover equity and post-close equity grants

Equity grants to the founder / executive in the acquirer's holding company post-close, subject to vesting.

- **§409A analysis.** Restricted stock (Section 83 property) is generally outside §409A. Non-qualified stock options (NSOs) with an exercise price at or above fair market value on the grant date are generally exempt from §409A under the option exemption. RSUs typically vest and settle on the same schedule and may qualify for short-term-deferral exception if settled within 2.5 months of vest. Deferred RSUs (settle later than vest) are subject to §409A and must comply.
- **Rollover equity in a NewCo.** The rollover-equity structure (chapter 2) typically involves the founder's target-company stock being exchanged for NewCo equity. If the NewCo equity is subject to substantial vesting or forfeiture terms, §409A analysis applies. Tax counsel structures the arrangement to fit within §409A exemptions or to comply with §409A timing requirements.

### Severance paid in connection with change of control

Severance paid to an executive whose employment terminates in connection with the change of control (single-trigger or double-trigger).

- **§409A analysis.** Severance is deferred compensation subject to §409A unless it fits within an exception. The most common exception: severance that qualifies as *separation pay* under Treasury Regulation §1.409A-1(b)(9), which requires:
  - The severance is paid on account of an *involuntary separation from service*, and
  - The severance does not exceed 2 times the lesser of (a) the executive's annualised compensation in the year before separation or (b) the qualified-plan compensation limit for that year (adjusted annually — a specific number the tax counsel supplies for the current year), and
  - The severance is paid by December 31 of the second year following the year of separation.
- **Drafting.** Executive severance arrangements are drafted to fit within the separation-pay exception or, if that exception is not available, to be §409A-compliant deferred comp with fixed payment timing (typically a lump sum paid within 60 days after separation from service, or paid in installments per a fixed schedule).

### Deferred consideration paid to selling shareholders (not compensation)

Deferred payments to shareholders as consideration for the sale of their stock (e.g., seller notes, deferred purchase-price payments) — as opposed to compensation for services.

- **§409A analysis.** §409A applies to compensation for services, not to purchase-price consideration. Deferred payments that are purely in exchange for the shareholder's stock (with no continued-service condition) are outside §409A.
- **Watch:** the *characterisation* matters. If a payment is nominally structured as deferred purchase price but is contingent on continued service by the shareholder-employee, it may be re-characterised as compensation for services and pulled into §409A. Tax counsel makes this call.

## The 6-month delay for public-company "specified employees"

For public companies (companies with tradable stock), §409A imposes a special rule under §409A(a)(2)(B)(i): payments to a **specified employee** on separation from service must be *delayed by 6 months*. A specified employee is one of the top 50 (or the corporation's chosen number up to 50) highest-compensated employees. This 6-month delay applies to deferred-compensation payments on separation and is a specific compliance requirement for post-close arrangements at publicly traded acquirers.

- **Application.** If a founder-CEO becomes an employee of a public-company acquirer post-close and then separates from service, deferred compensation triggered by that separation is delayed by 6 months. This affects the timing of severance, deferred earn-out payments contingent on employment, and other payment types.
- **Drafting.** Employment agreements and retention arrangements at public-company acquirers include the 6-month-delay language for specified employees, with a lump-sum catch-up payment after the delay period.

## The §409A/§280G interaction

§280G (chapter 6) and §409A can interact in ways that complicate transaction-payment design:

- **A cutback provision for §280G that reduces payments below the 3x threshold.** If the cutback is structured properly, it does not violate §409A — the cutback is a compliance mechanism, not a redeferral or acceleration. Draft the cutback as an automatic operation of law without a discretionary election.
- **A §280G shareholder-vote cleanse.** The cleanse does not affect §409A analysis — the payments are still subject to §409A regardless of §280G cleanse. Both analyses must be satisfied.
- **Reasonable-compensation value-shifting.** Payments characterised as reasonable comp for post-close services (to reduce §280G parachute-payment total) must also comply with §409A if they are deferred. A retention grant that is treated as reasonable comp for post-close services and is subject to vesting must satisfy §409A (typically through the short-term-deferral exception on each vesting tranche).

The two provisions must be co-designed. A transaction-payment structure that solves §280G by shifting payments to reasonable-comp buckets can fail §409A if the reasonable-comp payments are structured with impermissible timing. Tax counsel with expertise in both provisions is essential.

## Common pitfalls

- **Late payment of transaction bonuses.** A transaction bonus that vests at closing and is intended to be paid at closing but is actually paid several weeks later (say, in a subsequent payroll cycle) can still satisfy the short-term-deferral exception if it is within 2.5 months of year-end. A payment that slips into the following year and past the 2.5-month window fails §409A.
- **Redeferral of already-vested compensation.** Once compensation vests, redeferring it (paying it later than originally scheduled) requires strict compliance with §409A's redeferral rules (12-month advance election, 5-year push-out). Attempting to defer a bonus post-vesting without following these rules violates §409A.
- **Acceleration of vested compensation.** Paying vested deferred comp earlier than scheduled violates §409A (with limited exceptions). This can arise in transaction contexts if a change-of-control-triggered acceleration is not structured as an initial permitted-payment-event.
- **Change-in-control definition mismatch.** The §409A change-in-control definition (in Treasury Regulation §1.409A-3(i)(5)) is narrower and more specific than the §280G change-of-control definition. A transaction that is a change of control for §280G may or may not be a change in control for §409A. If deferred comp is scheduled to pay on a "change in control" without the correct definition, the intended payment may fail §409A.
- **Involuntary separation misclassification.** The separation-pay exception under §409A requires "involuntary" separation. Whether a separation is voluntary or involuntary is a specific factual and legal analysis; misclassifying a voluntary separation as involuntary to fit within the exception fails §409A.
- **Public-company specified-employee 6-month delay.** For companies that recently went public (or whose acquirer is public), the specified-employee delay rule can be missed on transaction-payment design and produce compliance violations.

## Practitioner notes on drafting

- **Short-term-deferral safe harbour.** For transaction bonuses and initial earn-out payments, drafting into the short-term-deferral exception is the cleanest §409A compliance path. Ensure payment occurs within the 2.5-month window after the year of vesting.
- **Fixed payment schedule.** For payments outside the short-term-deferral window (e.g., multi-year retention or long-term deferred comp), fix the payment schedule specifically in the arrangement — "paid in five equal annual installments beginning on [specific date]" rather than "paid at the corporation's discretion." Discretionary timing violates §409A.
- **Separation-from-service definition.** Use the §409A separation-from-service definition (which has specific requirements around what constitutes a "separation," including transitions to independent-contractor status and reductions in service level). Do not adopt an alternative separation definition without §409A analysis.
- **Change-in-control definition.** Use the §409A-compliant change-in-control definition (which differs from the standard-form change-of-control definitions in equity plans). Cross-reference to the §280G definition only if the two are separately drafted with the differences addressed.
- **Documentation.** §409A requires that the deferred-compensation plan be *documented* in writing with the payment terms specified. Verbal arrangements or informal understandings do not satisfy §409A documentation requirements.

## Summary

IRC §409A governs the timing of deferred-compensation payments and applies to two common M&A structural elements — earn-outs paid to founders / employees who remain in service post-close, and transaction bonuses paid to service providers. The short-term-deferral exception (payment within 2.5 months of year-end of vesting) is the primary §409A compliance mechanism for most M&A payments. Payments to shareholders in their capacity as shareholders (rather than as employees) are outside §409A entirely, but the characterisation is fact-dependent. Public-company acquirers face an additional 6-month delay on separation-triggered payments to specified employees. §409A violations trigger current taxation, a 20% additional federal tax on the recipient, and possible premium-interest tax — a severe penalty that transaction-payment design cannot afford to trip. §409A and §280G interact and must be co-designed; tax counsel with expertise in both provisions is essential. Well-drafted arrangements either fit within a §409A exception (typically short-term deferral) or comply as §409A deferred comp with fixed payment timing; ambiguous or discretionary payment timing is where §409A violations arise.
