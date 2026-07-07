# Edward Meyman

**Founder & CEO, FERZ, Inc.** Building runtime authorization infrastructure, the enforcement layer of AI governance, for regulated industries.

ORCID: [0009-0008-8012-6100](https://orcid.org/0009-0008-8012-6100)

---

## What I'm Building

Published, vendor-neutral work on **AI governance that can be independently verified**, not merely documented and trusted.

**Core thesis:** AI governance is an enforcement problem, not a monitoring problem. Governance must shift from policy statements and process documentation to **authorization artifacts that support independent replay**. If you can't replay the decision, you can't audit it. If you can't audit it, you can't govern it.

This approach treats governance as a **runtime property of the system**, not an after-the-fact reporting function.

The work centers on **tamper-evident authorization artifacts, implemented as Proof-Carrying Decisions under 5TS**: artifacts that carry verification evidence, enabling **fail-closed authorization** where effect-bearing actions do not execute without a verdict.

---

## Published Standard

### [Five Tests Standard (5TS)](https://github.com/edmeyman/4ts-standard)

The **Five Tests Standard (5TS)** is a published, vendor-neutral standard defining five conformance tests for AI governance mechanisms. It supersedes the Four Tests Standard (4TS); the repository name is retained from the predecessor.

* **Stop.** The system can be halted before side effects occur.
* **Ownership.** Each consequential decision maps to a named accountable authority.
* **Replay.** The decision can be reproduced at the boundary.
* **Escalation.** Control transfers at defined policy boundaries.
* **Provenance.** The inputs grounding a verdict have an established origin. Origin, not truth.

The verdict space is ALLOW, DENY, and ABSTAIN. An ABSTAIN blocks execution pending authorized human override; escalation is the consequence of ABSTAIN, not a fourth verdict.

Archived under concept DOI [10.5281/zenodo.21040295](https://doi.org/10.5281/zenodo.21040295).

---

## [AI Governance Executive Guide Series](https://github.com/edmeyman/ai-governance-guides)

A decision-grade guide series for executives, regulators, and system owners responsible for deploying AI in regulated environments.

The series translates deterministic governance principles into **actionable authorization models**, clarifying:

* What must be *verifiable* vs. what can be merely *documented*
* Where traditional compliance frameworks stop short of pre-execution authorization evidence
* Why logs, audits, and attestations are insufficient as authorization evidence
* How to operationalize fail-closed authorization for AI systems

> Written for leaders who must **authorize AI systems**, not merely observe them.

---

## Publications & Prior Art

* 📚 **SSRN:** https://papers.ssrn.com/sol3/cf_dev/AbsByAuth.cfm?per_id=7471418
* 🧾 **Zenodo:** https://zenodo.org/communities/ferz/
* 🔬 **ResearchGate:** https://www.researchgate.net/profile/Edward-Meyman
* 🛡️ **IP.com:** defensive publications establishing AI governance prior art; search: *Meyman*

These publications establish architectural and conceptual prior art for deterministic AI governance, authorization artifacts, and independently reconstructable verification.

---

## FERZ Intellectual Property Portfolio

Patent-pending governance infrastructure addressing distinct failure modes in AI authorization, escalation, and accountability under regulatory constraints.

Patent filings and published prior-art materials include work on:

* **LASO(f):** deterministic linguistic policy enforcement
* **DELIA:** deterministic governance of AI-generated multimodal outputs and serialized action descriptions
* **CausaCore:** causal governance and decision lineage infrastructure

The filed portfolio is complemented by defensive publications establishing foundational prior art. Mechanism details are not published outside the filings themselves.

---

## How to Read This Profile

* **The standard** defines *what must be verifiable*
* **The systems** enforce *authorization at runtime*
* **The publications** explain *why observation-based approaches fail*

Governance architecture, not product documentation.

---

## Looking For

* **Standards adoption:** organizations implementing verifiable governance frameworks
* **Pilot customers:** regulated enterprises ready to move beyond compliance theater
* **Collaborators:** researchers and engineers working on deterministic governance, formal methods, or regulatory technology

---

## Connect

* 🌐 Website: https://ferz.ai
* 📧 Research correspondence: [edward@ferz.ai](mailto:edward@ferz.ai)
* 📧 FERZ and pilot inquiries: [info@ferz.ai](mailto:info@ferz.ai)
* 💼 LinkedIn: https://www.linkedin.com/in/edmeyman/

---

> Governance without verification is theater.
> Verification without determinism is sampling.
> — Edward Meyman
