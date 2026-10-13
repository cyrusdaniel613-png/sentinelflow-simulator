# SentinelFlow 🛡️💳
*Professional Fintech Transaction Simulator & Monitoring Platform*

## Overview
SentinelFlow is an enterprise-grade transaction simulation and monitoring tool designed to demonstrate high-reliability financial workflows, secure incident detection, and idempotent recovery.

## Key Architecture & Features
- **Defense-in-Depth Security:** Employs Edge WAF, cloud micro-segmentation, and zero-trust principles for sensitive logs.
- **Financial Idempotency:** Safely handles payment timeouts (`UNKNOWN` status) to prevent double-charging.
- **Recovery Center:** Human-in-the-loop control room requiring admin verification before executing resolution playbooks.
- **Deterministic Root-Cause Analysis:** Fast, auditable failure classification with local LLM extensibility.

## How to Run Locally
1. Clone the repository.
2. Open `index.html` directly in any modern web browser.
