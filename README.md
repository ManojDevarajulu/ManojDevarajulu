# Manoj D

**Applied AI & Systems Engineer** • Building measured, verifiable AI systems and developer infrastructure.

[LinkedIn](https://www.linkedin.com/in/manojdevarajulu/) • [Portfolio](https://manojdevarajulu.cc) • [X (Twitter)](https://x.com/ManojDevarajulu) • [GitHub](https://github.com/ManojDevarajulu)

---

### Focus & Engineering Principles

I design and build autonomous agent pipelines, document intelligence engines, and developer infrastructure focused on **reliability, deterministic verification, and measurable performance**.

* **Deterministic Verification over Blind Trust:** Pairing probabilistic LLM generation with sandboxed formal validators (Python AST execution, Luhn check algorithms, clinical taxonomy constraints) to eliminate mathematical and logical hallucinations.
* **Empirical Benchmarks over Intuition:** Evaluating retrieval and agent architectures against established industry benchmarks (FinanceBench, FHIR R4 conformance, RRF ablation studies).
* **Zero-Bloat Architecture:** Prioritizing in-memory algorithms, pure Python AST traversal, and lightweight data structures before introducing heavy distributed database daemons.

---

### Upstream Open Source Contributions

* **[Mintplex-Labs/anything-llm](https://github.com/Mintplex-Labs/anything-llm)** (35k+ ⭐)
  - [PR #6738](https://github.com/Mintplex-Labs/anything-llm/pull/6738) *(Merged)*: Resolved prompt compressor crash on skipped history records during conversion.
  - [PR #6726](https://github.com/Mintplex-Labs/anything-llm/pull/6726) *(Merged)*: Added token limit warning handling for LLM streaming responses.

---

### Featured Systems

#### [Ledger AI](https://github.com/ManojDevarajulu/Ledger-AI)
*Audit-Grade Financial RAG Engine & Deterministic SEC 10-K Analysis Terminal*
- Eliminates financial hallucinations across corporate filings by pairing table-aware structural chunking with a deterministic Python AST math engine (`decimal.Decimal`).
- **Live Ingestion:** Directly streams and parses real Form 10-Ks from SEC EDGAR over HTTPS with fair-access rate limiting and content-addressable disk caching.
- **Empirical Results:** Increases Answer Accuracy from **5.0% to 90.0%** and Evidence Recall@1 to **90.0%** across 20 FinanceBench corporate disclosures.
- **Stack:** Python, FastAPI, NumPy, Rank-BM25, SEC EDGAR API, Python AST, Vanilla JS/CSS.

#### [Intake AI](https://github.com/ManojDevarajulu/IntakeAI)
*Clinical Document IDP Engine & Calibrated Clinician Review Terminal*
- Production-grade Intelligent Document Processing (IDP) pipeline for ambulatory medical referrals and facsimile forms with distribution-free conformal risk control.
- **Deterministic Clinical Invariants:** Enforces closed-form verification—CMS 10-digit NPI Luhn check digit formula, CMS ICD-10-CM active taxonomy registry, and timeline chronology.
- **Pluggable Architecture:** Works 100% offline with zero API keys via native hardware-accelerated Windows OCR / Tesseract, or seamlessly plugs into Gemini 2.5 Flash, GPT-4o, or local Ollama.
- **Interoperability:** Auto-accepts verified records into standard **HL7 FHIR R4 US Core** bundles; routes ambiguous fields to a split-pane clinician adjudication workstation with interactive SVG bounding boxes.
- **Stack:** Python, FastAPI, Pydantic v2, Windows Native OCR, Conformal Risk Routing, HL7 FHIR R4, Docker.

#### [CrashProof](https://github.com/ManojDevarajulu/CrashProof)
*Deterministic Fault-Injection Harness & Invariant Verifier for LLM Agents*
- Eliminates duplicate customer refunds, phantom return labels, and race conditions in autonomous agent workflows under simulated crashes, network retries, and timeouts.
- **Empirical Results:** Tested across 1,000 deterministic execution seeds; hardened runtime achieved 0 invariant violations vs. 747 violations in naive unhardened agent loops.
- **Stack:** Python, Abstract Syntax Trees (AST), Deterministic Event Simulator, React Trace Viewer.

#### [Sentinel](https://sentinel-teal-two.vercel.app/) *(Production / Closed Source)*
*Developer Infrastructure & Codebase Dependency Visualization*
- Code intelligence engine providing dependency graphs, blast-radius detection, and architectural impact analysis for large-scale software repositories.
- **Stack:** Next.js, TypeScript, FastAPI, Supabase.

---

### Technical Toolkit

* **AI & Retrieval:** Retrieval-Augmented Generation (RAG), Hybrid Search (BM25 + Dense RRF), Neuro-Symbolic Agent Architectures, Conformal Risk Routing, Abstract Syntax Trees (AST).
* **Backend & Systems:** Python 3.12+, FastAPI, Pydantic v2, PostgreSQL, NumPy, REST APIs, Asynchronous I/O.
* **Domain Standards & Interoperability:** SEC EDGAR (HTML/XBRL), HL7 FHIR R4, JSON Schema, Docker, Git.
