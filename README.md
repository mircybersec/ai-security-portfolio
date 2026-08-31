# AI Security & Governance Portfolio

**Security Professional | GRC & Threat Modeling | AI Vulnerability Research**

Welcome to my AI Security research repository. I am bridging 8+ years of enterprise Information Security management (GRC, ISMS, BCMS) with hands-on technical auditing of Large Language Models (LLMs) and Agentic AI systems. 

This portfolio demonstrates a comprehensive approach to AI risk—proving not just how to exploit frontier AI models, but how to govern, monitor, and defend them using enterprise frameworks like ISO 27001 and NIST AI RMF.

---

## 🔬 Hands-On LLM Audits (OWASP Top 10)

My active vulnerability research maps directly to the [OWASP Top 10 for LLM Applications (2025/2026)](https://owasp.org/www-project-top-10-for-large-language-model-applications/). All tests are conducted locally using containerized open-weight models (Qwen, Llama) with strict telemetry logging via Langfuse.

| Status | Lab | OWASP Category | Target | Write-up |
| :---: | :--- | :--- | :--- | :--- |
| 🔄 | **Lab 01** | [LLM01: Prompt Injection] | Local `Qwen` | *Under Construction* |
| ✅ | **Lab 02** | [LLM07: System Prompt Leakage] | Local `Qwen 2.5` | [JSON Schema Bypassing](./labs/02-system-prompt-leakage/README.md) |
| 📅 | **Lab 03** | [LLM06: Excessive Agency] | Agent Tooling | *Planned* |
| 📅 | **Lab 04** | [LLM02: Sensitive Info Disclosure] | Local RAG | *Planned* |
| 📅 | **Lab 05** | [LLM04: Data & Model Poisoning] | File Processing | *Planned* |

---

## 📑 Governance, Risk & Compliance (GRC)

Technical exploitation is only half the battle. The `docs/` section of this repository contains architectural diagrams, threat models, and policy mappings that translate AI vulnerabilities into actionable enterprise risk mitigation.

* *(Documents coming soon as labs are completed)*

---
*Disclaimer: All vulnerabilities are researched locally in air-gapped sandboxes. No enterprise APIs or proprietary corporate models are targeted in these labs.*
