# Security Policy

Lambdaplex is an onchain exchange protocol. A vulnerability in the protocol, settlement contract, or matching service could put user funds and assets at risk. We take security reports seriously and ask that you disclose responsibly.

## ⚠️ Please do not open public issues for security problems

Do **not** report vulnerabilities through public GitHub issues, discussions, or pull requests. Public disclosure before a fix is in place can put users at immediate risk.

## How to report a vulnerability

Please use **one** of the following private channels:

1. **GitHub Private Vulnerability Reporting** (preferred) — use the **"Report a vulnerability"** button on the [Security tab](https://github.com/lambdaplexlabs/feedback/security/advisories/new) of this repository.
2. **Email** — send details to **support@lambdaplex.io**.

If you'd like to encrypt your report, request our PGP key by email first.

## What to include

To help us triage quickly, please include as much of the following as you can:

- A clear description of the vulnerability and its potential impact (e.g. fund loss, order manipulation, denial of service).
- The affected component (settlement contract, matching service, SDK, web app).
- The network (Hedera Mainnet / Testnet) and any relevant contract address.
- Step-by-step reproduction details, proof-of-concept code, or transaction IDs (`0.0.x@timestamp`).
- Any suggested remediation, if you have one.

**Never include private keys, seed phrases, or other secrets in your report.**

## Our commitment

- We will acknowledge your report within **3 business days**.
- We will keep you informed as we investigate and work toward a fix.
- We will credit you for the discovery once the issue is resolved, unless you prefer to remain anonymous.
- We ask that you give us a reasonable window to remediate before any public disclosure.

## Scope

In scope: the Lambdaplex settlement smart contract, matching/order-book service, official SDKs/APIs, and the official web app.

Out of scope: third-party wallets, the Hedera network itself, the Supra oracle infrastructure, and issues already publicly known. For those, please report to the respective project.
