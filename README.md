# Manoj D

**Applied AI & Systems Engineer** • Building measured, verifiable AI systems and developer infrastructure.

[LinkedIn](https://www.linkedin.com/in/manojd7/) • [Portfolio](https://manojdevaraj-portfoliov1.vercel.app) • [X (Twitter)](https://x.com/ManojDevarajulu) • [GitHub](https://github.com/ManojDevarajulu)

---

### Focus & Engineering Principles

I design and build autonomous agent pipelines, document intelligence engines, and developer infrastructure focused on **reliability, deterministic verification, and measurable performance**.

* **Deterministic Verification over Blind Trust:** Pairing probabilistic LLM generation with sandboxed formal validators (Python AST execution, Luhn check algorithms, clinical taxonomy constraints) to eliminate mathematical and logical hallucinations.
* **Empirical Benchmarks over Intuition:** Evaluating retrieval and agent architectures against established industry benchmarks (FinanceBench, FHIR R4 conformance, RRF ablation studies).
* **Zero-Bloat Architecture:** Prioritizing in-memory algorithms, pure Python AST traversal, and lightweight data structures before introducing heavy distributed database daemons.

---

### Featured Systems

#### [Ledger AI](https://github.com/ManojDevarajulu/Ledger-AI)
*Audit-Grade Financial RAG Engine & Deterministic SEC 10-K Analysis Terminal*
- Eliminates financial hallucinations across corporate filings by pairing table-aware structural chunking with a deterministic Python AST math engine (`decimal.Decimal`).
- **Live Ingestion:** Directly streams and parses real Form 10-Ks from SEC EDGAR over HTTPS with fair-access rate limiting and content-addressable disk caching.
- **Empirical Results:** Increases Answer Accuracy from **5.0% to 90.0%** and Evidence Recall@1 to **90.0%** across 20 FinanceBench corporate disclosures.
- **Stack:** Python, FastAPI, NumPy, Rank-BM25, SEC EDGAR API, Python AST, Vanilla JS/CSS.

#### [Intake AI](https://github.com/ManojDevarajulu/Intake-AI) *(Active)*
*Calibrated Clinical Document Intelligence Engine for Healthcare Intake*
- Automated clinical referral extraction engine for noisy, degraded medical faxes with distribution-free risk control (conformal prediction).
- Enforces strict deterministic invariants: CMS 10-digit NPI Luhn verification, ICD-10-CM clinical code taxonomy lookup, and chronological consistency.
- Automatically accepts high-confidence records into validated **HL7 FHIR R4 US Core** bundles; routes ambiguous fields to an interactive clinician review queue with coordinate bounding-box overlays.
- **Stack:** Python, FastAPI, Pydantic v2, Conformal Prediction, HL7 FHIR R4, Synthetic Clinical Generation.

#### [Sentinel](https://sentinel-teal-two.vercel.app/)
*Developer Infrastructure & Codebase Dependency Visualization*
- Code intelligence engine providing dependency graphs, blast-radius detection, and architectural impact analysis for large-scale software repositories.
- **Stack:** Next.js, TypeScript, FastAPI, Supabase.

---

### Technical Toolkit

* **AI & Retrieval:** Retrieval-Augmented Generation (RAG), Hybrid Search (BM25 + Dense RRF), Neuro-Symbolic Agent Architectures, Conformal Risk Routing, Abstract Syntax Trees (AST).
* **Backend & Systems:** Python 3.12+, FastAPI, Pydantic v2, PostgreSQL, NumPy, REST APIs, Asynchronous I/O.
* **Domain Standards & Interoperability:** SEC EDGAR (HTML/XBRL), HL7 FHIR R4, JSON Schema, Docker, Git.
