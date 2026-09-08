# AI-Model, Open-Source, and Specialty Diligence

## Why this matters

Two diligence workstreams that barely existed as distinct disciplines a decade ago now sit at the top of the R&W underwriter's exclusions memo on almost every venture-backed AI-and-SaaS transaction: AI-model diligence and open-source-licence diligence. The reason in each case is the same — a specific wave of litigation, regulatory change, and market-loss experience has taught underwriters, acquirers' counsel, and deal teams that these areas can carry material, non-obvious, hard-to-quantify exposure that a target may not itself understand. On the AI side, the copyright-in-training-data class actions and government-actions against Stability AI, OpenAI, Anthropic, Perplexity, and their downstream users have opened a genuine question about the enforceability of a target's AI product on training-data-provenance grounds; the EU AI Act has added a regulatory overlay (particularly for general-purpose AI model providers); state-level algorithmic-decision-making laws have added US regulatory exposure. On the OSS side, a growing number of AGPLv3-in-SaaS-product findings, license-changes by dual-licensed vendors (MongoDB, Elastic, Redis, HashiCorp, and others moving off OSI-approved licences to SSPL, BSL, and Elastic License 2.0), and enforcement by copyleft-focused organisations (Software Freedom Conservancy, Free Software Foundation) have made OSS-licence compliance a real transactional risk category rather than a checkbox.

This chapter installs the transaction-side skill for both workstreams. It is *not* a treatise on AI safety, AI governance, or open-source law — the AI-safety-technical depth of a model-card audit or a training-data-provenance investigation lives in [`chief-ai-officer-learning`](https://github.com/ai-governance-curriculum/chief-ai-officer-learning) and [`head-of-ai-governance-learning`](https://github.com/ai-governance-curriculum/head-of-ai-governance-learning); the OSI / SPDX / SFC-level technical depth of licence-compatibility analysis lives with IP counsel and specialist OSS-legal firms. This chapter teaches the *transaction-side* skill: what to inspect, what to look for, how to translate findings into definitive-agreement rep language, how to translate findings into R&W-policy exclusions or specific-indemnity carve-outs, and where the boundaries to the deeper technical disciplines sit.

## Part one — AI-model diligence

## Why AI-model diligence is a distinct workstream

For a decade, "AI" in acquisition diligence sat inside technology diligence — a subset of the product-and-technology workstream, inspected by the same tech-diligence firm looking at the target's architecture and stack. That approach fails in the current market for four reasons:

1. **Training-data provenance is a legal question, not an engineering question.** Whether the target's foundation-model training data or fine-tuning data was properly licensed, was scraped from copyrighted material without permission, contains PII the target did not have consent to use, or contains third-party proprietary data the target does not have the right to embed — these are IP and contract questions that a tech-diligence engineer is not trained to evaluate. IP counsel is.
2. **Foundation-model usage-policy compliance is a contract question.** Whether the target's use of OpenAI, Anthropic, Google, AWS Bedrock, Azure OpenAI, or a self-hosted open-weight model complies with the provider's usage policies — no medical advice, no impersonation of real people without consent, no use for weapons development, no use for high-risk employment or credit decisions in some markets — requires reading and applying provider policies that update frequently.
3. **The regulatory landscape is fresh and moving.** The EU AI Act took effect August 2024 with staggered implementation dates (prohibited practices February 2025, GPAI-provider obligations August 2025, high-risk-system obligations August 2026, high-risk-in-Annex-III August 2027 — verify current dates at the primary source; the implementation calendar was set as of adoption but is subject to interpretation and enforcement pattern updates). The Colorado AI Act (SB 24-205), NYC Local Law 144 (automated employment-decision tools), the growing California AI-related bills, and the emerging federal AI-Executive-Order framework each add specific compliance obligations. A tech-diligence firm without AI-regulatory counsel is not equipped to inspect this.
4. **The R&W underwriter is asking specifically about AI.** The exclusions memo (chapter 6) increasingly names training-data provenance, copyright-in-training-data claims, and AI-Act-compliance as specific-exclusion or conditional-coverage categories. Coverage in these areas requires diligence work the underwriter recognises as adequate — a scan-only technology review is not.

So AI-model diligence has emerged as a distinct workstream, typically staffed by the buyer's AI-governance team (where present) supplemented by AI-specialist counsel and increasingly by AI-specialty diligence firms.

## The AI-model diligence scope

**Model inventory.** Every model the target has in production, with its purpose, its inputs and outputs, its lifecycle stage (in production / in beta / in evaluation / deprecated), the team that owns it, and the customer-facing surface where it appears. Includes foundation-model calls (OpenAI, Anthropic, Google, others), embedding models, in-house fine-tuned models, in-house from-scratch-trained models, and any embedded open-weight models (Llama, Mistral, Qwen, DeepSeek, others).

**Model-card documentation.** For each in-scope model, a model card documenting intended use, training data description, evaluation results, known limitations, ethical considerations. The Google Model Cards for Model Reporting paper (Mitchell et al., 2019) is the canonical template; the Hugging Face Model Cards standard is the practical implementation for open-weight models; the NIST AI RMF has adopted a comparable framing. Absence of model cards is itself a diligence finding — it suggests the target has not run the discipline internally, which raises the probability of hidden issues.

**Training-data provenance.** For each in-scope model, the sources of the training data or fine-tuning data. Categorisation:
- Publicly-available data collected through the target's own scraping — what licence terms attach, what robots.txt or Terms-of-Service the target has respected, what if any copyright material is in the corpus.
- Licensed data purchased or obtained from data providers — what the licence permits (training use, output use, redistribution), what representations the data provider gave the target about the underlying source rights.
- User-generated data from the target's own product — what the target's Terms of Service and Privacy Policy disclosed about training use, what user consent mechanism was in place, what deletion or opt-out mechanism the target honoured.
- Third-party data (partner data, embedded data-provider content) — what licence permits the training use.
- Synthetic data generated from foundation-model outputs — what the foundation-model provider's Terms of Service permit for that use (some providers prohibit training competing models on their outputs).

**Foundation-model usage compliance.** For each foundation model the target calls, the specific usage policy (OpenAI Usage Policies, Anthropic Acceptable Use Policy, Google Generative AI Prohibited Use Policy, AWS Bedrock Acceptable Use, Azure OpenAI Code of Conduct) and the target's compliance posture. Categories of concern:
- Prohibited use cases (medical diagnosis without appropriate clinician review, legal advice, high-stakes decisions in credit / employment / housing in some regimes, political-influence content, sexual content involving minors, deepfake creation of real people, weapons or dual-use content).
- Rate-limit and quota compliance.
- Data-processing-agreement compliance (whether the target's use exposes customer data to the foundation-model provider in a way that breaches the target's customer contracts).
- Attribution and disclosure obligations.

**Evaluation-harness and evaluation results.** The target's methodology for evaluating model performance (accuracy on task-specific benchmarks, hallucination rate, safety-eval performance, jailbreak resistance, red-team findings, bias evaluation on protected-class outputs). Modern targets often have some evaluation infrastructure (internal eval harnesses, benchmark comparisons, human-eval workflows); the absence of any evaluation methodology is a finding.

**AI-vendor contract inventory.** Every AI vendor the target uses (foundation-model API providers, embedding providers, vector databases, AI observability, LLM-evaluation platforms, prompt-management tools, agent frameworks). Terms of service, data-processing agreements, indemnification provisions, prohibited-use clauses. The R&W underwriter's diligence-review call will ask specifically about this stack.

**GPAI-provider posture.** For any target whose product places it in-scope of the EU AI Act's GPAI (general-purpose AI) provider obligations (Article 53 for standard GPAI, Article 55 for systemic-risk GPAI), the target's compliance posture: training-data summary published (Article 53(1)(d)), copyright-compliance policy in place (Article 53(1)(c)), technical documentation prepared, downstream-provider information provided. Most venture-backed targets are downstream users rather than GPAI providers themselves, but AI-first targets that train foundation models are in-scope.

**High-risk-system posture.** For targets whose products fall within Annex III of the EU AI Act (biometric identification, critical-infrastructure management, education, employment, essential public / private services, law enforcement, migration, judicial administration), the more-onerous high-risk-system obligations (Article 8–17: risk-management system, data governance, technical documentation, record-keeping, transparency and provision of information to deployers, human oversight, accuracy, robustness, cybersecurity). Non-EU targets with EU customers or EU users are in-scope.

**NIST AI RMF alignment.** For US targets, whether the target has adopted or aligned with the NIST AI Risk Management Framework (AI RMF 1.0, published January 2023, with subsequent Generative AI Profile). Not a legal obligation but an increasingly-expected practitioner-standard framework.

**Copyright-training-data litigation exposure.** Any subpoenas, cease-and-desist letters, discovery requests, or claims the target has received arising from training data. The wave of active litigation (New York Times v. OpenAI / Microsoft; the several class actions against OpenAI, Anthropic, Google, Meta, and others; Getty Images v. Stability AI in US and UK; Andersen v. Stability AI, Midjourney, and DeviantArt; Authors Guild-related actions) has established a general awareness at the AI-vendor level, but downstream users may have exposure too.

**AI-content-labelling posture.** For targets producing AI-generated content, the labelling and disclosure posture: C2PA (Coalition for Content Provenance and Authenticity) content-credentials adoption, watermarking, synthetic-media disclosure. Increasingly required by platform partners (Meta, LinkedIn, YouTube) and by emerging regulation (California AB 2013 for training-data transparency, Texas AI-content disclosure requirements, and similar bills).

**AI-governance-programme review.** The target's internal AI-governance apparatus — AI-policy documentation, AI-review-board or -committee if any, AI-use-case-approval process, AI-incident-response plan, employee AI-training, AI-vendor-vetting procedure.

## The AI-diligence findings memo

The AI-diligence findings memo follows the finding / evidence / impact / recommendation architecture (chapter 5). Common red findings the buyer's AI-diligence provider surfaces:

- **Training-data provenance gap for the flagship model.** The target trained (or fine-tuned) the flagship model on data whose provenance is not documented or whose licensing status is unclear.
- **Foundation-model usage-policy violation.** The target's product uses a foundation model for a prohibited use case (medical diagnosis, high-stakes credit decision, deepfake).
- **Prior copyright complaint or subpoena.** The target has received a copyright-related contact regarding its training data or model outputs.
- **GPAI-provider obligation gap.** The target is a GPAI provider under the EU AI Act and has not filed the required training-data summary or has no copyright-compliance policy.
- **High-risk-system obligation gap.** The target's product is in-scope for the EU AI Act high-risk-system obligations and lacks the required risk-management system, technical documentation, or human-oversight mechanism.
- **AI-vendor-contract concentration.** The target's product depends on a single foundation-model provider with no fallback, and the provider's Terms of Service permit unilateral change or termination.
- **Absence of AI-content labelling.** The target produces AI-generated content in a jurisdiction with disclosure requirements and does not label.
- **Model-card absence.** The target has no model cards or comparable documentation for its production models.
- **Evaluation-harness absence.** The target has no formal evaluation methodology for its production models beyond ad-hoc engineer inspection.

## AI-diligence read-across to the definitive agreement

The definitive-agreement rep language for AI-model matters is still emerging in the practitioner bar and is *not* standardised. That is itself a finding — the buyer's counsel drafts custom AI reps for each transaction, with content driven by the diligence findings.

Common structural elements of an emerging "AI-model rep":

- **Ownership and rights.** The target owns or has valid licence to use the AI models embedded in its product; the training data or fine-tuning data used to develop the models was properly licensed or was permissibly used.
- **Provider-terms compliance.** The target's use of third-party AI providers complies with the applicable providers' terms of service.
- **Absence of infringement claims.** No third party has claimed that the target's AI models, training data, or model outputs infringe or violate third-party rights.
- **Regulatory compliance.** The target's AI-related activities comply with applicable AI-specific laws and regulations, including the EU AI Act (where applicable), state-level AI laws, and any sector-specific AI regulation.
- **Model-card and documentation.** The target maintains reasonably-adequate documentation of its production models sufficient to support customer disclosure and regulatory requirements.

Alongside the rep, the disclosure schedule lists specific AI-related exposures (open subpoenas, foundation-model-provider notices, GPAI-registration status, high-risk-system identification if applicable). Specific-indemnity carve-outs typically cover training-data-provenance claims and copyright-related AI claims — these are the categories the R&W underwriter is most likely to exclude.

## AI-diligence read-across to the R&W policy

Chapter 6 introduced the AI-model exclusion pattern. The specific mechanics:

- **Training-data-provenance exclusion.** "Any Loss arising from or related to the collection, licensing, use, or provenance of any data used to train, fine-tune, or otherwise develop any AI model of the Target." Broad. Common in current market.
- **Copyright-in-training-data exclusion.** "Any Loss arising from any claim by a third party that the training data or fine-tuning data used by the Target infringes such third party's copyright." Narrower than provenance-broadly. Common.
- **AI-Act-compliance exclusion.** "Any Loss arising from a violation of the EU Artificial Intelligence Act." Common for EU-exposed targets, particularly where the target's GPAI or high-risk-system posture is unresolved.
- **Foundation-model-provider-terms exclusion.** "Any Loss arising from the Target's violation of the terms of service of any third-party AI-provider." Less common but appearing.

Negotiating these exclusions (chapter 6):
- **Narrowing.** "Excluded only for Loss arising from a claim first made by a Third Party, and only where the underlying training data was collected after [date]." Specific-date narrowing acknowledges the target's post-diligence-date remediation.
- **Sub-limits.** "Coverage up to $[X] sub-limit for training-data-provenance claims."
- **Coverage-exceptions.** "Excluded except for claims arising from data licensed under [named data-provider agreements]."
- **Additional-diligence triggers.** "Coverage available conditional on completion of the training-data-provenance audit by [named specialist firm] with results acceptable to Underwriter."

When exclusions cannot be narrowed, the buyer's paths (chapter 6) apply: bear the risk, negotiate a specific-indemnity carve-out from the seller backed by escrow, or (rarely, and only for widely-covered patterns like foundation-model IP indemnity that the foundation-model provider itself offers to enterprise customers) rely on upstream indemnity from the AI-vendor.

## Part two — open-source licence diligence

## Why OSS-licence diligence is a distinct workstream

Every modern software target ships open-source-software (OSS) components inside its product. Typically the OSS content is much larger than the target's own proprietary code — a modern SaaS product may be 80%+ OSS by lines of code once transitive dependencies are counted. Each OSS component carries a licence with specific obligations: attribution (Apache-2.0 §4, BSD, MIT); redistribution restrictions (source-availability for GPL, network-availability for AGPL); patent-grant-back (Apache-2.0 §3, GPLv3 §11); notice preservation; and (for some licences) the requirement to distribute the target's own derivative code under compatible terms.

The transactional risk is that the target may have taken on licence obligations it is not fulfilling — the most common failure modes:

- **AGPLv3 code in a customer-facing SaaS service.** AGPLv3 is designed for SaaS: any modification of the AGPLv3 code, distributed *or made available over a network to users*, triggers the AGPL's copyleft requirement to make the corresponding source code available. Many targets have quietly embedded AGPLv3 components (MongoDB pre-2018, GhostScript, and various libraries under AGPLv3) in their production stack without recognising the obligation. Discovering an AGPLv3 finding at diligence typically requires either re-licensing the code, removing the component and rebuilding, or negotiating a specific-indemnity from the seller for the exposure.
- **Attribution notice absence.** Apache-2.0 §4(a) requires distribution of the LICENSE file, §4(b) requires preservation of NOTICE files, and §4(d) requires acknowledgement. Many targets ship products without the NOTICE files that dozens of embedded Apache-2.0 components require. This is typically remediable (ship the NOTICE files in the next release) but requires the finding to be identified.
- **BSD 4-clause attribution.** The original BSD 4-clause licence's advertising clause requires acknowledgement in advertising materials. Rarely a practical issue but occasionally surfaces.
- **License-changed components.** Components originally released under OSI-approved licences (MIT / Apache-2.0) that changed to non-OSS or restrictive licences (SSPL, BSL, Elastic License 2.0, Commons Clause) with the target continuing to use the newer version under terms the target's ordinary licence-compliance did not vet. MongoDB's Server Side Public Licence (2018), Elastic's Elastic License 2.0 (2021), HashiCorp's Business Source License (2023), Redis's SSPL (2024), and others exemplify this pattern.
- **Copyleft components in the target's own proprietary code.** Where a GPL-family library has been embedded in a way that arguably creates a derivative work of the target's proprietary code — the "linking" question is legally complex, particularly for dynamic linking, but a finding that GPLv2 or GPLv3 code has been embedded in ways that arguably require the target's own code to be GPL is a material transactional risk.
- **Patent-grant-back activation.** Apache-2.0 §3 grants a patent licence from every contributor to every user, and terminates on the user's assertion of patent claims against the code. Similar patent-grant-back provisions appear in GPLv3 §11. Targets that hold patents and contribute to Apache-2.0 or GPLv3 projects have granted implicit patent licences the target may not have explicitly considered.
- **CLA / DCO absence for target-maintained OSS.** For targets that maintain their own OSS projects (open-source SDKs, sample code, community libraries), the absence of Contributor License Agreements or Developer Certificate of Origin signoffs from external contributors is a chain-of-title gap.

## The OSS-licence diligence scope

**SBOM (software bill of materials) generation.** A machine-readable inventory of every OSS component in the target's shipped code and infrastructure. SPDX (ISO/IEC 5962:2021) and CycloneDX are the two mainstream formats. The target should have an SBOM; if the target does not, the buyer's diligence commissions one via a scan tool.

**Scan-tool selection.** The market for OSS-scanning tools is concentrated:
- **Black Duck by Synopsys** — the incumbent OSS composition-analysis tool with broad language and package-manager coverage. Preferred for large, complex codebases.
- **Fossa (FOSSA)** — modern OSS-compliance platform with strong policy-enforcement features and CI integration. Widely adopted by mid-market and larger tech companies.
- **Snyk Open Source** — combined OSS-licence and OSS-vulnerability scanning. Often already deployed at the target and reused for diligence.
- **Scancode Toolkit** — open-source scanner from AboutCode / nexB. Free but requires more setup.
- **ORT (OSS Review Toolkit)** — Linux Foundation project. Free and increasingly deployed for automated compliance workflows.
- **Mend (formerly WhiteSource)** — enterprise OSS-compliance platform.

Scan tools produce false positives — a component detected but not actually used, a license inferred from filename rather than content, a snippet-level match that does not indicate incorporation. Practitioner-quality OSS diligence pairs scan output with human review by an OSS-experienced counsel or consultant.

**Licence-obligation summary.** For each detected licence family, a summary of obligations and the target's compliance posture:
- **Permissive (MIT, BSD, Apache-2.0, ISC, Unlicense).** Minimal obligations — typically attribution / notice preservation. High-volume, low-obligation.
- **Weak-copyleft (LGPL, MPL, EPL).** Modifications to the specific components must be shared; the target's proprietary code that merely uses the components is not affected. Attribution obligations apply.
- **Strong-copyleft (GPLv2, GPLv3, LGPL when statically linked in some interpretations).** Modifications to the components — and, under the strongest interpretations, derivative works incorporating the components — must be distributed under the same terms.
- **Network-copyleft (AGPLv3).** Same as GPLv3, plus the network-provision trigger for SaaS use.
- **Non-OSS restrictive (SSPL, BSL, Elastic License 2.0, Commons Clause, source-available).** Not OSI-approved. Specific commercial-use restrictions vary. The target must comply with the specific terms.
- **Unknown / unlicensed.** Code with no discernible licence. Legally unclear; safest practice is to remove and replace.

**Copyleft-exposure memo.** For each detected copyleft component, an analysis: is the component modified? is it distributed? if it is a SaaS service, is it exposed over the network? if the component is dynamically linked, does the linking model support the target's proprietary-code position under the applicable interpretation? The AGPLv3-in-SaaS-service question is the canonical red flag.

**Attribution completeness review.** Comparison of the SBOM's licence-required attributions against the target's shipped NOTICE, LICENSE, or attribution documents. Gaps become findings.

**Patent-grant-back inventory.** For every Apache-2.0 or GPLv3-family component contributed to by the target, the implicit patent-licence the target has granted to the community. Cross-referenced against the target's patent portfolio to identify any patents the target has effectively licensed to the world.

**License-changed component review.** Identification of components whose upstream licence has changed. Analysis of the target's use of the newer versions under the new terms.

**Target-maintained OSS review.** For OSS projects the target maintains, the CLA / DCO posture, contributor-agreement records, and any commercial-competitor use of the target's own OSS (which can create competitive dynamics separate from the licence question).

## OSS-diligence findings memo

Common red findings:

- **AGPLv3 in a customer-facing service.** As above. Requires re-licensing, removal, or specific indemnity.
- **Attribution notice gap.** Named components require notice; the target's shipped product does not include the notice. Typically remediable in the next release but a finding.
- **License-changed component in production.** The target uses a newer, non-OSS version of a formerly-OSS component without licence compliance.
- **Unlicensed code.** Snippets or components with no discernible licence in the target's own code repositories.
- **GPL-family in the target's proprietary product.** A finding of GPL-family code inside the target's proprietary product raises the "derivative work" question and can be a serious transactional issue.
- **SSPL-covered use.** The target uses MongoDB or another SSPL-licenced component in a way that arguably triggers the SSPL's "offering-as-a-service" clause.

## OSS-diligence read-across to the definitive agreement

The OSS-licence rep is a standard element of the modern IP rep set (mod-104 chapter 4). The typical structure:

- **The target's use of open-source software complies with the applicable licences.** The target has not, through its use of open-source software, taken on any obligation to disclose, distribute, or license the target's own proprietary code under an open-source licence.
- **The target has fulfilled the applicable attribution and notice obligations.**
- **The target's own contributions to open-source projects have been made pursuant to the target's IP-ownership rights.**
- **A list of material open-source components used by the target's product is set forth in [OSS Disclosure Schedule].**

The disclosure schedule lists material components, and specific findings (AGPLv3 exposure, license-changed components, attribution gaps) are listed there or in a specific-indemnity schedule.

## OSS-diligence read-across to the R&W policy

R&W policies typically cover the OSS-licence rep at the general limit, subject to two common exclusions:

- **Known-issue exclusion for AGPLv3-in-SaaS-service findings.** Once surfaced, an AGPLv3-in-SaaS-service finding is a known issue the R&W will not cover; the buyer's paths are re-licensing / removal by the target pre-closing (typical if timeline permits), a specific-indemnity carve-out from the seller (typical if remediation is not feasible pre-closing), or buyer self-insurance if the exposure is modest.
- **License-changed-component exclusion.** Similar treatment — the exposure is known; the R&W will not cover; the buyer negotiates with the seller.

Attribution gaps are typically not excluded — they are remediable in the next release and the exposure is small. Unknown-licence and GPL-in-proprietary-code findings are more heavily scrutinised; underwriters may exclude or require specific remediation before binding.

## Part three — specialty diligence topics

Beyond AI and OSS, a growing set of specialty topics has emerged that the diligence workstream design (chapter 4) should account for:

**Copyright-training-data specialty.** For AI-first targets with substantial training-data corpora, a dedicated training-data-provenance audit — beyond the AI-diligence workstream — may be warranted. Specialist firms with training-data-forensics capability (a small but growing niche) can perform this work.

**Foundation-model-vendor indemnity assessment.** For targets whose value depends on continued access to foundation-model APIs, the vendor's indemnification posture matters. OpenAI's Copyright Shield (November 2023), Anthropic's IP indemnity for enterprise customers, Google's Generative AI Indemnity, and Microsoft's Copilot Copyright Commitment vary in scope, conditions, and cap. The buyer's counsel reviews each vendor contract to understand the actual indemnity the target has.

**AI-vendor-supply-chain concentration.** For a target that depends on a single foundation-model provider, the switching-cost analysis and the vendor-risk analysis are their own diligence question. Some acquirers have accepted the concentration; others have required the target to demonstrate portability (evaluations across multiple models, abstraction layers that allow provider swap).

**AI-related privacy overlap.** Where the target's product processes personal data through AI models, the intersection of privacy law (GDPR Article 22 automated decision-making, CCPA sensitive-personal-information handling, state-level algorithmic-decision laws) and AI law (EU AI Act) creates a diligence intersection between the AI workstream and the privacy workstream (chapter 4). Coordinating the two is essential.

**AI-governance-programme maturity.** Beyond the technical AI diligence, the target's internal AI-governance programme is itself a diligence question — does the target have an AI-review-board, an AI-policy, an AI-incident-response plan, employee AI-training? The absence of a programme is a red-flag for future exposure.

**OSS-supply-chain security overlap.** OSS-licence diligence identifies what components are used; OSS-supply-chain security (typo-squatting, dependency-confusion, malicious package versions, unmaintained-package risk) is a separate question. The security workstream (chapter 4) covers this. The OSS-licence workstream and the security workstream should coordinate on any specific-component findings.

## Ownership boundaries

This module owns the *transaction-side skill* for AI and OSS diligence — what to inspect, how to translate findings into deal-side outcomes, how to negotiate R&W-policy exclusions and specific-indemnity carve-outs. It does not re-teach the underlying technical disciplines:

- **AI-safety-technical depth** — how to build a training-data-provenance investigation, how to construct a model card, how to design an evaluation harness, how to prepare a GPAI-provider filing under Article 53, how to run a systemic-risk assessment under Article 55, how to implement the NIST AI RMF — lives in [`chief-ai-officer-learning`](https://github.com/ai-governance-curriculum/chief-ai-officer-learning) and [`head-of-ai-governance-learning`](https://github.com/ai-governance-curriculum/head-of-ai-governance-learning). This module inspects the artefacts those disciplines produce.
- **AI-safety-engineering practice** — how to build safety-classifier stacks, how to implement content-provenance signing (C2PA), how to construct red-team infrastructure — lives in the AI-safety engineering track. This module reads the outputs.
- **OSS-supply-chain security depth** — how to detect typo-squatting, how to run reproducible builds, how to establish SLSA-compliant build provenance, how to implement Sigstore signing — lives in [`security-learning`](https://github.com/ai-infra-curriculum/security-learning). This module inspects the security posture around OSS supply chain but defers to the security track for the engineering depth.
- **OSS-legal specialist practice** — the detailed licence-compatibility analysis, the linking-question analysis under specific interpretations of GPL, the specific enforceability of AGPL's network-provision clause across jurisdictions — sits with IP counsel and OSS-legal specialists (Software Freedom Law Center, Heather Meeker's practice, other specialist boutiques). This module engages those specialists as workstream providers.

The transaction-side value this module adds: a workstream design that inspects both AI and OSS with the scope, providers, and deliverables the modern venture-M&A transaction actually requires, and a findings-to-deal-side translation that handles the increasingly-common R&W exclusions and specific-indemnity conversations.

## Summary

AI-model diligence and open-source-licence diligence have emerged as distinct transactional workstreams over the last three-to-five years, driven by copyright-in-training-data litigation, the EU AI Act, state-level AI laws, license-changes by former OSS vendors, and the R&W underwriter's targeted exclusions. AI diligence inspects the target's model inventory, model cards, training-data provenance, foundation-model usage-policy compliance, evaluation harness, AI-vendor contracts, GPAI-provider posture, high-risk-system posture, NIST AI RMF alignment, copyright-training-data litigation exposure, AI-content-labelling posture, and AI-governance programme. OSS diligence inspects the SBOM, licence-obligation posture by licence family, copyleft-exposure (particularly AGPLv3-in-SaaS-service), attribution completeness, patent-grant-back inventory, license-changed components, and target-maintained-OSS chain-of-title. Findings from both workstreams translate into definitive-agreement rep language (an emerging AI-model rep; the more-standardised OSS-licence rep), disclosure schedules, and R&W-policy considerations (training-data-provenance exclusion, copyright-in-training-data exclusion, AI-Act-compliance exclusion, AGPLv3-in-SaaS-service exclusion). The transaction-side skill is workstream design and findings-to-deal-side translation; the technical depth defers to `chief-ai-officer-learning`, `head-of-ai-governance-learning`, `security-learning`, and specialist OSS-legal counsel.

The module completes here on the substantive lecture chapters. The exercises apply the seven chapters against a specific hypothetical transaction; the resources page collects the primary references (regulatory, practitioner, empirical) the module has drawn from and cited.
