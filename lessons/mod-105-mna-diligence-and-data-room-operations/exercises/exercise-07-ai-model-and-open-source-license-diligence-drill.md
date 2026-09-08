# exercise-07: AI-model and open-source-licence diligence drill

**Estimated effort:** 4–5 hours

## Objective

Run an AI-model diligence pass and an OSS-licence-obligation inventory for a specific hypothetical target, translate the findings into definitive-agreement rep language, and translate the findings into R&W-policy exclusion / specific-indemnity carve-out proposals.

The finished artefact is an AI-diligence memo (6–10 pages), an OSS-licence-obligation inventory (in tabular form plus a 3–5 page findings memo), an emerging-AI-rep drafted for insertion into the definitive-agreement rep set, an OSS-licence-rep drafted for the same, and a specific-indemnity / R&W-exclusion translation table.

You should end the exercise able to defend the diligence scope choices for both workstreams against alternative scopes, defend the specific rep language against a seller-side redline that would tighten the reps, and defend the specific-indemnity-vs-R&W-exclusion translation for each material finding.

## Background

This exercise covers material from:

- [Chapter 7 — AI-Model, Open-Source, and Specialty Diligence](../07-ai-model-and-open-source-diligence.md) — AI-model diligence scope, model cards, training-data provenance, foundation-model usage compliance, GPAI-provider posture, EU AI Act high-risk-system obligations, NIST AI RMF alignment, copyright-training-data exposure, AI-vendor-contract inventory; OSS-licence diligence scope, SBOM, licence families, copyleft exposure, attribution completeness, license-changed components, patent-grant-back, target-maintained OSS; rep-language emergence; R&W-exclusion mechanics.

Supporting references:

- [Chapter 4](../04-buy-side-diligence-workstream-design.md) for the workstream-plan placement.
- [Chapter 5](../05-buy-side-findings-memo-and-price-renegotiation.md) for the findings-memo architecture.
- [Chapter 6](../06-rw-underwriter-diligence-negotiation.md) for R&W-exclusion mechanics.
- [mod-104 chapter 4](../../mod-104-loi-negotiation-and-definitive-agreements/04-definitive-agreement-architecture-and-reps-layering.md) for the rep-set architecture the AI and OSS reps land in.
- **EU AI Act primary source** — Regulation (EU) 2024/1689 on artificial intelligence. Verify current implementation timelines at eur-lex.europa.eu.
- **NIST AI RMF 1.0** and Generative AI Profile. <https://www.nist.gov/itl/ai-risk-management-framework>
- **SPDX Specification and Licence List.** <https://spdx.dev/>
- **Open Source Initiative (OSI) Approved Licences.** <https://opensource.org/licenses/>

## Prerequisites

- The hypothetical target you have been carrying through mod-101–104 and earlier exercises of this module. For this exercise, freeze the target's AI posture:
  - Foundation-model dependency (which providers, which models, which use-cases).
  - In-house fine-tuning or from-scratch training (which models, on what data).
  - Any embedded open-weight models (Llama, Mistral, Qwen, DeepSeek, others).
  - AI-generated-content surface (user-facing outputs; any C2PA / watermarking posture).
  - EU customer / user exposure (drives EU AI Act in-scope determination).
- Freeze the target's OSS posture:
  - Language stack (drives which OSS ecosystems apply — npm, PyPI, Maven, Go, Rust, others).
  - Distribution model (SaaS-only, downloadable client, on-premise deployment, hybrid).
  - Any target-maintained OSS projects (open-source SDKs, sample code, community libraries).
- Familiarity with the OSS-scanning tool ecosystem (Black Duck, Fossa, Snyk Open Source, Scancode, ORT, Mend). A free trial or open-source variant lets you run a real scan against a sample codebase.
- Familiarity with SPDX and CycloneDX SBOM formats. The SPDX specification is a good starting reference.

## Tasks

### 1. Set the target AI and OSS baseline

Write a 1-page baseline covering:

- Target product and AI-use-case summary.
- Foundation-model dependency map (provider, model, use-case, usage-policy-relevant considerations).
- In-house training and fine-tuning summary (models, training-data-source categories).
- Embedded open-weight model use.
- AI-generated-content posture (labelling, C2PA, watermarking).
- EU / UK / non-US exposure summary.
- OSS-language-stack summary.
- Distribution-model summary.
- Any known-issue context (prior copyright complaint, GPAI-provider classification uncertainty, known AGPLv3 exposure).

### 2. Draft the AI-model diligence scope

Produce a 1-page AI-diligence scope covering:

- **Model inventory.** Every model in production with purpose, inputs, outputs, lifecycle stage, owning team, customer-facing surface.
- **Model-card review.** For each in-scope model, the model-card documentation (or absence).
- **Training-data provenance.** For each model, source categorisation (publicly-scraped, licensed, user-generated, third-party, synthetic).
- **Foundation-model usage compliance.** Provider by provider.
- **Evaluation-harness and results.** Methodology and outputs.
- **AI-vendor contract inventory.**
- **GPAI-provider posture.** EU AI Act Articles 53 and 55 applicability.
- **High-risk-system posture.** EU AI Act Annex III applicability.
- **NIST AI RMF alignment.**
- **Copyright-training-data litigation exposure.**
- **AI-content-labelling posture.**
- **AI-governance-programme review.**

### 3. Execute the AI-model diligence

Populate the scope with findings for your specific target. For each category, name what you found, what evidence supports it, and any red-flag observations. The exercise is about doing the analytical work, not about achieving a specific outcome.

Common findings to expect (invent-with-plausibility for your target):

- Model inventory gaps — models in production without ownership assigned or without a model card.
- Training-data-provenance gaps — a fine-tuned model whose training data source is not documented.
- Foundation-model-provider-terms concerns — usage that arguably violates a specific prohibited use case in the provider's policy.
- Evaluation absence — no formal evaluation methodology for one or more production models.
- AI-vendor concentration — sole-source foundation-model dependency without a fallback.
- GPAI or high-risk-system uncertainty — the target is unclear on whether it is in-scope for specific EU AI Act obligations.
- Copyright-training-data exposure — any received copyright-related contacts, or any known-scraped-data-source use.
- AI-content-labelling absence — AI-generated content shipped without label in a jurisdiction with disclosure requirements.

### 4. Draft the AI-diligence findings memo

Produce a 6–10 page AI-diligence findings memo using the finding / evidence / impact / recommendation architecture from chapter 5:

- Executive summary.
- Red findings in full four-field format.
- Yellow findings summary.
- Green findings summary.
- Cross-cutting themes if any.
- Read-across to the definitive agreement (rep language, disclosure schedule, specific-indemnity considerations).
- Read-across to the R&W policy (expected exclusions, additional-diligence commitments, sub-limit alternatives).
- Read-across to the integration plan (post-close AI-governance-programme build actions).

### 5. Draft the emerging AI-model rep

The AI-model rep is not standardised (chapter 7). Draft the specific rep language for insertion into the definitive-agreement rep set:

- **Ownership and rights.** The target owns or has valid licence to use the AI models embedded in its product; training or fine-tuning data was properly licensed or permissibly used.
- **Provider-terms compliance.** The target's use of third-party AI providers complies with applicable terms of service.
- **Absence of infringement claims.** No third party has claimed that the target's AI models, training data, or outputs infringe or violate third-party rights.
- **Regulatory compliance.** The target's AI-related activities comply with applicable AI-specific laws and regulations.
- **Model-card and documentation.** The target maintains reasonably-adequate documentation of production models.

Draft the rep language with attention to materiality qualifier, knowledge qualifier, and time-period qualifier calibration. Then predict the seller's redline — where would the seller push for a knowledge qualifier, a materiality qualifier, or a specific carve-out? Draft the buyer-side response to each seller redline.

### 6. Draft the AI-related disclosure-schedule and specific-indemnity carve-outs

For the specific findings surfaced in your AI-diligence:

- Disclosure-schedule entries (specific known exposures listed as exceptions to the reps).
- Specific-indemnity carve-outs (for material known exposures the R&W policy will exclude).
- Escrow proposals for the specific-indemnity carve-outs.

### 7. Draft the OSS-licence diligence scope

Produce a 1-page OSS-diligence scope covering:

- **SBOM generation or verification.** Format (SPDX or CycloneDX); tool.
- **Scan-tool selection and configuration.**
- **Licence-obligation summary by licence family.** Permissive, weak-copyleft, strong-copyleft, network-copyleft, non-OSS-restrictive, unlicensed.
- **Copyleft-exposure memo scope.** With particular attention to AGPLv3-in-SaaS-service findings.
- **Attribution-completeness review.**
- **Patent-grant-back inventory scope.**
- **License-changed-component review scope.**
- **Target-maintained OSS review scope.**

### 8. Execute the OSS-licence diligence

Populate the scope for your specific target. For a realistic exercise, either:

- Run a scan-tool on a sample real-world OSS project you have access to (an open-source project you have permission to inspect, or a public codebase like a well-known open-source library).
- Simulate the scan output for a hypothetical target's SBOM with a plausible distribution of licences (typically 40-60% permissive, 20-30% weak-copyleft, 5-15% strong-copyleft, 1-5% network-copyleft, 5-10% license-changed / non-OSS-restrictive, 1-3% unlicensed).

Produce the findings inventory as a table:

- Component name.
- Version.
- Licence (SPDX identifier).
- Distribution model impact (does the licence trigger obligations for the target's SaaS use? for downloadable-client use?).
- Attribution status.
- Any red-flag observation.

### 9. Draft the OSS-licence findings memo

Produce a 3-5 page OSS-diligence findings memo using the finding / evidence / impact / recommendation architecture:

- Executive summary.
- Red findings (AGPLv3-in-SaaS-service, license-changed-component-in-production, GPL-in-proprietary-code, unlicensed-code).
- Yellow findings (attribution-notice-gap, SSPL-covered-use, weak-copyleft-component-with-attribution-requirement).
- Green findings (permissive-only, well-attributed).
- Read-across to the definitive agreement (OSS rep, OSS disclosure schedule, specific-indemnity considerations).
- Read-across to the R&W policy (expected exclusions for known copyleft-exposure findings).
- Read-across to the integration plan (attribution-remediation, AGPL-in-SaaS remediation options).

### 10. Draft the OSS-licence rep

The OSS-licence rep is more standardised than the AI-model rep. Draft the specific rep language:

- The target's use of open-source software complies with applicable licences.
- The target has not, through its use of open-source software, taken on any obligation to disclose, distribute, or license the target's own proprietary code under an open-source licence.
- The target has fulfilled applicable attribution and notice obligations.
- The target's own contributions to open-source projects have been made pursuant to the target's IP-ownership rights.
- A list of material open-source components is set forth in [OSS Disclosure Schedule].

Predict the seller's redline and draft the buyer-side response.

### 11. Draft the OSS-related disclosure-schedule and specific-indemnity carve-outs

For the specific findings surfaced in your OSS-diligence:

- Disclosure-schedule entries.
- Specific-indemnity carve-outs (particularly for AGPLv3-in-SaaS-service findings that R&W will exclude).
- Pre-closing remediation commitments (where the seller agrees to remediate before closing — e.g., remove the AGPLv3 component, ship the missing attribution notices) as an alternative to specific-indemnity.

### 12. Draft the R&W-exclusion / specific-indemnity translation table

Produce a translation table mapping each material finding to its expected R&W treatment and the seller-side specific-indemnity fallback:

- Finding.
- Expected R&W exclusion language.
- Specific-indemnity ask from seller (if the exclusion holds).
- Escrow requirement.
- Alternative treatment (additional diligence, coverage exception, pre-closing remediation).

### 13. Draft the AI-and-OSS section for the buyer's findings memo

Extract from the two diligence memos and integrate into a specific AI-and-OSS section (2-3 pages) for insertion into the exercise-5 findings memo. Cross-reference to the other workstreams' findings where relevant (e.g., an AI finding that intersects with a privacy finding on user-data training use, or an OSS finding that intersects with a security finding on supply-chain vulnerability).

## Starter guidance

Common AI-and-OSS diligence errors to avoid:

- **AI-diligence bundled inside tech-diligence.** A tech-diligence firm without AI-regulatory-counsel support is not equipped for the AI-Act, GPAI-obligation, or copyright-training-data-exposure analysis. Engage a distinct AI-diligence workstream.
- **Scan-tool output taken as truth.** OSS-scan tools produce false positives and false negatives. Human review by OSS-experienced counsel is essential for material findings.
- **AGPLv3-in-SaaS-service under-scoped.** This is the canonical high-risk OSS finding for a SaaS target and warrants specific search rather than reliance on general scan output.
- **Model-card absence treated as neutral.** Absence of model cards for production models is a diligence finding — it suggests the target has not run the discipline internally, which raises probability of hidden issues.
- **Foundation-model provider-terms compliance overlooked.** The specific prohibited-use-case violations (medical diagnosis without clinician, high-stakes credit decision, deepfake, weapons content) are often not visible until specific inspection of the target's use cases.
- **EU AI Act scope misidentification.** A US target with EU customers or EU users is in-scope. A US-only target using an EU-based foundation model is not necessarily in-scope for the target's own obligations but should verify.
- **Rep language without seller-redline anticipation.** The rep drafted without anticipating the seller's push for knowledge / materiality / carve-out qualifiers arrives at signing week and gets negotiated under time pressure.
- **R&W exclusion accepted without specific-indemnity fallback.** Every accepted R&W exclusion should have a specific-indemnity treatment plan or an accepted buyer-self-insured decision documented.
- **Attribution-gap remediation treated as easy.** "Ship the NOTICE files in the next release" sounds easy but requires the specific NOTICE files to have been retained, the customer-facing distribution model to accommodate the notice, and (for downloadable-client products) the target's release process to actually ship the notice.

## Acceptance criteria

You can demonstrate that:

- Target AI and OSS baseline is written.
- AI-model diligence scope is produced covering all 11 categories from the chapter.
- AI-model diligence findings memo is drafted at 6-10 page depth with finding / evidence / impact / recommendation structure.
- Emerging AI-model rep is drafted with specific language and anticipated seller-redline response.
- AI-related disclosure-schedule and specific-indemnity carve-outs are drafted.
- OSS-licence diligence scope is produced.
- OSS-licence findings inventory is produced (either from actual scan or simulated with plausible distribution).
- OSS-licence findings memo is drafted at 3-5 page depth.
- OSS-licence rep is drafted with anticipated seller-redline response.
- OSS-related disclosure-schedule and specific-indemnity carve-outs are drafted (including pre-closing remediation alternatives).
- R&W-exclusion / specific-indemnity translation table is produced.
- AI-and-OSS section for the buyer's findings memo is drafted at 2-3 page depth.

## Reflection

Add a short reflection:

1. Which single AI-diligence finding was hardest to translate into deal-side terms — the finding surfaces a real risk, but the mechanic to allocate it (rep, disclosure, indemnity, R&W exclusion) is unclear?
2. For an AGPLv3-in-SaaS-service finding, is the modal treatment pre-closing remediation (remove the component, rebuild) or specific-indemnity carve-out? What determines the choice?
3. If the target's foundation-model dependency is concentrated on one provider whose Terms of Service permit unilateral change, how would you draft the AI-vendor-concentration risk into the rep and disclosure-schedule package?
4. For an AI-first target that trains its own foundation models, does the EU AI Act GPAI-provider classification change your assessment of the deal's risk profile? By how much?

## Stretch goals

- **Live OSS-scan on a real codebase.** Run Black Duck Community Edition (or Fossa's free tier, or Snyk's free tier, or Scancode) on a real codebase you have permission to inspect. Compare the raw output to your simulated exercise.
- **SBOM generation exercise.** Generate an SBOM in both SPDX and CycloneDX formats for a sample project. Note the differences in what the two formats capture and how they present the data.
- **AI-Act GPAI-provider filing preparation.** For a target you have identified as a GPAI provider, prepare a draft training-data summary that would satisfy the Article 53(1)(d) obligation. Note where the target lacks the underlying documentation to prepare a compliant filing.
- **Copyright-training-data-litigation review.** Read one of the pending copyright-training-data class actions in full (New York Times v. OpenAI, Andersen v. Stability AI, Getty Images v. Stability AI). Note the specific plaintiff theories and how they would apply to your target.
- **OSS-supply-chain security overlap analysis.** For your OSS-licence findings, identify which specific components also carry OSS-supply-chain security risk (typo-squatting, dependency-confusion, unmaintained-package). Draft the overlap with the security workstream (chapter 4).
- **AI-vendor-contract deep-dive.** For the target's foundation-model-vendor contracts, review the specific IP indemnification provisions (OpenAI Copyright Shield, Anthropic IP indemnity, Google Generative AI Indemnity, Microsoft Copilot Copyright Commitment). Draft the analysis of the target's actual upstream indemnity coverage.
- **NIST AI RMF-alignment gap analysis.** For a target that has not adopted the NIST AI RMF, draft a gap analysis showing which specific practices the target has vs. lacks, and what the effort would be to reach alignment.
- **Historical OSS-licence-enforcement case study.** Research a specific OSS-licence-enforcement action (Software Freedom Conservancy actions, the historical VMware / gpl-violations.org cases, the more recent AGPL-enforcement actions). Note the specific-finding-to-enforcement-action pattern and its diligence implications.
