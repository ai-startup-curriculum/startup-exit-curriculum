# exercise-04: Technology and Systems Integration Decision Drill

**Estimated effort:** 4 hours

## Objective

Author the specific **technology-and-systems integration decision memo** that resolves the specific "consolidate vs. preserve" question across each specific technology-and-systems axis for the specific transaction profile — product, engineering organisation, data-and-infrastructure, security perimeter, and the specific API-parity optionality-preservation overlay. Produce a specific defensible memo with specific decisions, specific alternatives considered, specific rationale, and specific implementation milestones that attach to the specific day-30 systems-cutover and day-90 organisational-integration milestones from exercise 02. By the end of the exercise, the specific IMO has a specific written decision-of-record on specific technology-and-systems integration that specific the specific CTO workstream specifically executes against.

## Background

This exercise covers material from:

- [Chapter 4 — Technology-and-Systems Integration Decisions](../04-technology-and-systems-integration-decisions.md), end to end.
- Cross-reference to [Chapter 2 — Acquired-Company 100-Day Plan](../02-acquiree-100-day-plan.md) — the specific day-30 systems-cutover milestones specifically depend on the specific decisions made here.
- Cross-reference to [Chapter 5 — Culture Integration](../05-culture-integration.md) — the specific engineering-organisation decisions specifically interact with the specific culture-integration workstream.
- Cross-reference to [Chapter 7 — Escrow and Earn-Out](../07-escrow-release-and-earn-out-management.md) — specifically the specific product-roadmap and specific resource-allocation decisions specifically affect the specific earn-out metric and specifically require specific documentation per the specific SPA mechanics.
- Cross-reference to mod-105 chapter on specific technology diligence outputs — the specific integration-diligence findings specifically attach to the specific decisions here.

The technology-and-systems decisions are specifically among the most consequential and specifically among the most frequently deferred integration decisions. The specific pattern of deferring them beyond day-100 is specifically how specific "preserved standalone" acquisitions specifically become specific permanent orphans in the specific acquirer architecture — unmaintained, unimprovable, and specifically a specific permanent integration tax.

## Prerequisites

- The transaction profile frozen in exercise 01.
- The specific IMO charter from exercise 01, and specifically the specific acquiree-100-day plan from exercise 02.
- Access to the specific technology-diligence findings from the specific pre-close diligence (mod-105): specifically the specific acquiree infrastructure (cloud-vendor, services, data stores, pipelines, deployment), specifically the specific acquiree engineering-organisation structure (team shapes, tenure, specialisations), specifically the specific identified technology risks (specific technical debt, specific key-person dependencies, specific security findings, specific compliance posture).
- Access to specific published post-merger-technology-integration references — specific case studies from a specific recent well-documented acquisition where the specific technology-integration pattern was discussed (specifically a specific 10-K risk-factor or a specific earnings-call Q&A), specific IdP-consolidation vendor publications (Okta, Microsoft Entra, Google Cloud Identity), specific cloud-vendor migration tooling documentation (AWS Migration Hub, Azure Migrate, Google Cloud Migrate).
- Access to specific "well-architected" framework guidance from the specific hyperscaler the specific transaction will consolidate into (AWS Well-Architected at <https://aws.amazon.com/architecture/well-architected/>, Azure Well-Architected at <https://learn.microsoft.com/en-us/azure/well-architected/>, Google Cloud Architecture Framework at <https://cloud.google.com/architecture/framework>).

## Tasks

### 1. Author the specific product consolidate-vs-preserve decision (1 page)

Produce the specific decision memo for the specific product-portfolio question. Specifically identify, for each specific acquiree product offering (specifically — if the acquiree has multiple products or product lines, specifically per-offering; if a single product, specifically the single product), which specific disposition applies:

- **Immediate consolidation.** Specifically the specific acquiree product specifically is specifically absorbed into a specific equivalent acquirer product with specific customer-migration beginning on specific day 1 (or specific day 30, specific day 90). Specifically the specific sunset schedule, specific customer-migration timeline, specific feature-parity target.
- **Phased sunset.** Specifically the specific acquiree product specifically continues to be supported for a specific defined period (specifically typically 12–36 months), specifically with specific customer-migration encouraged but not forced. Specifically the specific support-level commitment through sunset, specific the specific customer-migration incentives.
- **Indefinite preservation.** Specifically the specific acquiree product specifically continues as a specific standalone offering indefinitely. Specifically the specific resource-and-roadmap commitment, specific the specific brand decision (specifically preserve acquiree brand, specific co-brand, specific rebrand under acquirer).

For each specific disposition decision: specifically rationale, specifically alternatives considered, specifically expected customer impact, specific expected revenue impact (specifically if earn-out metric is specifically revenue-based, specifically the specific impact on specific earn-out achievement), specific expected engineering-resource impact.

Specifically call out any specific disposition decisions that specifically have specific SPA-mandated constraints — specifically if the specific earn-out language specifically requires continued operation of the specific acquiree product per specific defined terms, specifically how the specific disposition decision specifically respects the specific constraint.

### 2. Author the specific engineering-org merge-vs-preserve decision (1 page)

Produce the specific decision memo for the specific engineering organisation. Specifically address:

- **The specific org-structure disposition.** Specifically do the specific acquiree engineering teams specifically become specific standalone BU engineering teams reporting to the specific founder (specific or specific other acquiree-side leader), specifically do they merge into the specific acquirer engineering function, specifically does a specific hybrid apply.
- **The specific manager-and-leveling disposition.** Specifically how specific the specific acquiree engineering managers specifically map to the specific acquirer engineering management levels (specifically typically — specific calibrated placement at the specific day-90 comp-and-leveling event per exercise 02). Specifically how the specific IC levels specifically map.
- **The specific team-shape decision.** Specifically do the specific acquiree teams specifically preserve their specific pre-close shapes (specifically typically if preserved as standalone BU) or specifically absorb into the specific acquirer's specific team-shape conventions (specifically typically if merged). Specifically if preserved, specifically how specific the specific acquiree teams specifically interact with specific acquirer-side specific equivalent teams.
- **The specific key-person dependency mitigation.** Specifically identify specifically each specific key-person engineering individual (specifically typically — specifically specific tech-lead or specific principal-engineer specific individuals specifically who specifically are specifically on the specific top-20 retention list from mod-110). Specifically identify the specific knowledge-transfer plan for each specific key-person — specifically document-the-architecture, specific pair-programming-with-acquirer-engineer, specific recorded-knowledge-transfer sessions.
- **The specific on-call-and-incident-response integration.** Specifically how the specific acquiree on-call rotation specifically continues (specifically typically preserved through at least day-90), specifically how the specific acquirer SRE / infra function specifically becomes specifically aware of the specific acquiree systems in case of specific incidents, specifically how a specific joint-escalation path specifically works.

### 3. Author the specific data-and-infrastructure migration-approach decision (1 page)

Produce the specific decision memo for the specific data-and-infrastructure disposition. Specifically address, for each specific major infrastructure domain:

- **Cloud-vendor disposition.** Specifically if the specific acquiree is specifically on a specific different cloud vendor than the specific acquirer (specifically — the specific acquiree on AWS, the specific acquirer on Azure, or specifically other combinations), specifically does the specific acquiree specifically migrate to the specific acquirer's cloud vendor (specifically typical for a specific tuck-in with specific merge-the-engineering-org thesis) or specifically remain on the specific pre-close cloud vendor (specifically typical for a specific preserved standalone BU). Specifically the specific migration approach:
  - **Lift-and-shift.** Specifically move the specific workloads specifically as-is to the specific new cloud, specifically preserving the specific architecture.
  - **Refactor.** Specifically move the specific workloads with specific architectural changes to specifically take advantage of specific target-cloud native services.
  - **Rebuild.** Specifically rewrite specifically on the specific target cloud (specifically rarely-chosen; specifically only when the specific legacy architecture is specifically unsalvageable or specifically the specific target cloud's native services specifically enable a specific materially different capability).
- **Data-store disposition.** Specifically which specific data stores specifically are specifically migrated to specific acquirer standards (specifically primary database engine, specifically data-warehouse, specific analytics platform) and specifically which specifically remain on specific pre-close standards. Specifically the specific data-ownership-and-sovereignty constraints (specifically — specific EU-residency data specifically subject to specific GDPR, specific specific HIPAA-covered data, specific specific sensitive-category data).
- **Data-pipeline disposition.** Specifically how the specific acquiree data pipelines specifically integrate with (or specifically remain separate from) the specific acquirer data pipelines. Specifically the specific analytics-and-BI consolidation question (specifically typically — specific BI tools consolidate at day 90 or specifically later, specifically data-warehouse consolidation specifically at day 180 or specifically later).
- **Observability-stack disposition.** Specifically which specific observability tools (metrics, logs, traces) specifically consolidate on specifically acquirer standards vs. specifically remain preserved. Specifically the specific threshold for consolidation (specifically typically — if the specific engineering organisation specifically merges, specifically consolidation specifically follows; if specifically preserved standalone, specifically preservation specifically follows).

### 4. Author the specific security-perimeter consolidation plan (1 page)

Produce the specific plan for the specific security-perimeter integration, specifically covering:

- **The specific IdP consolidation decision.** Specifically preserve the specific acquiree IdP (specifically Okta, specific Microsoft Entra, specific Google Workspace, specific Jumpcloud, specific custom), specifically cut over to the specific acquirer IdP, specifically federate. Specifically typically — specific preservation through day-30 or day-60, specific federation as specific intermediate step, specific full consolidation at specific day-90 or specific day-180 depending on the specific engineering-org disposition.
- **The specific endpoint-security consolidation.** Specifically EDR / endpoint-protection tooling (specifically CrowdStrike, specific SentinelOne, specific Microsoft Defender), specifically disk-encryption posture, specific MDM (specifically Jamf, specific Intune, specific Kandji) decisions. Specifically — specific typically consolidation at day-30 to day-90.
- **The specific SIEM / log-aggregation consolidation.** Specifically whether the specific acquiree security-event logging specifically specifically specifically flows into the specific acquirer SIEM (specifically Splunk, specific Microsoft Sentinel, specific Datadog Security, specific other) at specific day-30, specifically or specifically specifically remains in a specific preserved specific acquiree SIEM instance through transition.
- **The specific single-tenant to multi-tenant migration (if applicable).** Specifically if the specific acquiree product specifically runs as specific single-tenant deployments for each customer and the specific acquirer product specifically is specifically multi-tenant (or vice-versa), specifically how the specific migration specifically works. Specifically the specific customer-data-isolation preservation requirement.
- **The specific vulnerability-management-and-patching integration.** Specifically how the specific acquiree systems specifically are specifically specifically brought under the specific acquirer vulnerability-management discipline (specific SLA for specific patch deployment, specific CVE triage, specific pentesting cadence).
- **The specific compliance-posture integration.** Specifically how the specific acquiree compliance certifications (SOC 2, ISO 27001, HIPAA, PCI-DSS, FedRAMP) specifically are specifically transitioned — specifically typically preserved through specific transition and specifically consolidated under acquirer certifications in specific defined windows (specifically typically 12–24 months post-close, specifically dependent on specific certification-body procedures).

### 5. Author the specific API-parity optionality-preservation plan (½ page)

Specifically design the specific pattern for specifically preserving specific optionality in the specific product-and-engineering decisions through specific "API-parity-first" migration:

- **Specific principle.** Specifically — before specific consolidating the specific acquiree product's internal implementation, specifically preserve the specific acquiree product's specific public API surface at full parity so that specifically specific customers can specifically continue to specifically use the specific product on specifically the specific new implementation specifically without disruption. Specifically — this specifically preserves the specific optionality to specifically subsequently consolidate the specific internal implementation without specific customer-visible impact.
- **Specific implementation.** Specifically draft the specific API-parity-first migration pattern specifically for the specific acquired product — specific specific acquiree API specifically preserved as the specific public contract, specifically internal implementation specifically migrating specifically underneath, specifically eventual deprecation of specific acquiree-specific endpoints only after specifically explicit customer migration to specific acquirer-standard endpoints.
- **Specific exceptions.** Specifically identify any specific endpoints or specific features that specifically cannot be preserved under API-parity (specifically — specific features specifically that specifically depend on specifically acquiree-specific infrastructure that specifically cannot be specifically replicated, specifically specific legacy endpoints specifically with specific deprecation already-in-progress at close). Specifically for each exception, specifically specify the specific customer-migration path.

### 6. Author the specific "systems-cutover gate" document (½ page)

Specifically draft the specific "day-30 go/no-go" document that the specific IMO specifically runs for each specific systems-cutover. Specifically for each specific major cutover (IdP, HRIS, security-perimeter, finance-ledger), specifically identify:

- **The specific pre-conditions** that specifically must specifically all specifically be specifically true before the specific cutover specifically proceeds.
- **The specific day-29 verification** that specifically each specific pre-condition specifically has specifically been verified.
- **The specific day-30 execution choreography** — specific specific sequencing, specific communication to specific affected employees, specific rollback-plan if specific cutover specifically fails.
- **The specific day-31 post-cutover verification** — specific specifically identifying any specifically specific issues.

## Starter guidance

Three anti-patterns to avoid:

- **"We'll consolidate everything on acquirer standards because our standards are better."** This specifically ignores specific preserved-optionality value, specifically ignores specifically specific customer-visible impact, specifically ignores specifically specific engineering-team cultural attachment to specifically specific tools-and-practices. The specific defence is specifically a specific per-tool justification for consolidation rather than specifically a specific blanket consolidation default.
- **"We'll defer the technology decisions beyond day-100 to avoid rushing them."** This specifically produces specifically specific orphaned systems that specifically remain unmaintained and specifically become specifically specific permanent integration debt. The specific defence is specifically a specific explicit decision at day-100 (go/no-go on specific each specific consolidation) even if specific execution specifically continues beyond.
- **"Security consolidation can wait until the engineering-org merge is complete."** This specifically specifically creates specifically specific specific security gaps during the specific transition window (specific orphan accounts, specific unmaintained certificates, specific stale access patterns). The specific defence is specifically a specific explicit day-30 or specific day-60 security-perimeter cutover independent of specific engineering-org timing.

## Acceptance criteria

You can demonstrate that:

- The product consolidate-vs-preserve decision is specifically grounded in the specific deal thesis, the specific earn-out mechanics, and specific customer-impact assessment — rather than specifically default-to-consolidate boilerplate.
- The engineering-org decision specifically names specific disposition for every specific acquiree engineering team and specifically every specific key-person engineering individual.
- The data-and-infrastructure plan specifically chooses lift-and-shift / refactor / rebuild for each specific infrastructure domain and specifically defends the choice.
- The security-perimeter plan specifically covers IdP, endpoint, SIEM, compliance, and specifically names decision dates for each.
- The API-parity plan is specifically operational — a reader could specifically identify which specific acquiree API endpoints specifically are preserved and specifically which specific are migrated.
- The systems-cutover gate document is specifically a specific usable artefact for the specific day-29 go/no-go.
- A critical reader (an experienced CTO who has absorbed an acquired engineering organisation, a security practitioner who has consolidated IdPs, a cloud-architect who has run a cross-cloud migration) could specifically disagree with a specific decision in the memo and specifically see the specific judgement call that produced it.

## Reflection

Add a short reflection (½ page):

1. The specific product consolidate-vs-preserve decision — specifically which specific interaction with the specific earn-out mechanics specifically most constrains the specific decision? Specifically what specifically happens if the specific SPA language specifically requires preserved operation but the specific acquirer-side engineering specifically wants consolidation on efficiency grounds?
2. The specific IdP consolidation decision — specifically what specifically is the specific "day-after-cutover failure mode" — the specific most likely specific thing that specifically breaks on day 31, specifically how specific do you specifically detect it, specifically how specific do you specifically recover?
3. The specific API-parity optionality-preservation pattern — specifically what specifically is the specific long-tail risk? Specifically if the specific preserved API specifically becomes specifically a specific permanent commitment (because specific customers specifically never specifically migrate off), specifically how specifically does the specific acquirer specifically specifically specifically eventually sunset?

## Stretch goals

- **Model a specific cross-cloud migration case.** The specific acquiree is specifically on AWS, specifically the acquirer specifically is specifically on GCP. Specifically design the specific migration plan — specific what specifically moves (specific what specifically does not), specific the specific timing (specific day-30 vs. specific day-90 vs. specific day-365), specific the specific risks (specific data-egress cost, specific service-equivalence gaps, specific specific latency impact for specific customer-facing services).
- **Model a specific regulated-industry integration.** The specific acquiree specifically is specifically in specific a specific HIPAA or specific FedRAMP environment. Specifically design the specific additional constraints on specific IdP consolidation, specific data-store disposition, specific SIEM consolidation. Specifically identify specific what specifically specifically changes in the specific compliance-posture transition timeline.
- **Model a specific on-prem acquiree case.** The specific acquiree specifically runs on specific on-prem infrastructure. Specifically design the specific cloud-migration plan — specific specific decision on specific keep-on-prem (specifically for specific compliance reasons) vs. specific migrate-to-cloud, specific migration approach, specific timeline, specific customer impact.
- **Design the specific day-30 cutover rollback runbook.** Specifically draft the specific detailed runbook for specifically rolling back the specific day-30 IdP cutover if specific day-31 specifically produces specifically unacceptable issues. Specifically — specific decision authority, specific communication choreography, specific restoration mechanics, specific "when do we re-attempt" criteria.
