# AI Security & Adversarial R&D Portfolio

A dedicated Red Teaming and Threat Modeling R&D laboratory focused on auditing Large Language Models (LLMs) and Agentic AI workflows against the OWASP Top 10 for LLMs.

## Project Overview
This repository serves as a live journal of adversarial threat simulations conducted within an isolated, self-hosted AI architecture. The objective is to proactively identify, exploit, and mitigate vulnerabilities in generative AI systems before they are deployed in enterprise environments.

## Lab Infrastructure
To ensure zero data leakage and full telemetry control, all tests are conducted on local hardware using containerized microservices:
* **Inference Engine:** Local Qwen 3.5 2B (via `llama-server`)
* **API Gateway & Telemetry:** LiteLLM Proxy routing to Langfuse for full token-level observability
* **Agentic Framework:** Hermes Agent / Open WebUI
* **Host OS:** Pop!_OS (Linux)

## Threat Simulation Logs (OWASP Top 10)
* **[Lab 1: Direct Prompt Injection (LLM01)](SECURITY_JOURNAL.md)** - Bypassing strict systemic persona guardrails via Cognitive Paradoxes (Roleplay Inception).
## 🔬 Hands-On AI Security Labs

A structured index of vulnerability audits, threat models, and local model evaluations:

| Lab | Threat Category (OWASP) | Target | Audit Write-up |
| :--- | :--- | :--- | :--- |
| **Lab 02** | [LLM01: Prompt Injection](https://genai.owasp.org/llmrisk/llm01-prompt-injection/) | Local `Qwen 2.5 (2B)` | [System Prompt Leakage & JSON Schema Bypassing](./labs/02-system-prompt-leakage/README.md) |
| **Lab 01** | *Coming Soon* | *TBD* | *In Progress* |