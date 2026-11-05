# Security Policy

CTFVault is a markdown-only resource list — it contains no code that runs on your machine. That keeps the attack surface small, but a list of outbound links still has one real risk worth a policy: **a link pointing somewhere it shouldn't.**

## What Counts as a Security Issue Here

- **A hijacked or malicious link** — a domain in this list that has expired and been re-registered by someone serving malware, phishing, or scam content
- **A link silently redirecting** to something other than the resource it claims to be
- **A PR that adds a link** to a resource that is actually malicious, a phishing clone of a legitimate platform, or designed to harvest credentials under the guise of a "CTF site"

## What's Out of Scope

- **Vulnerabilities on the linked platforms themselves** (e.g. a bug in picoCTF's infrastructure) — report those to the platform directly, not here
- **The fact that linked labs are intentionally vulnerable** (VulnHub VMs, Juice Shop, GOAD, etc.) — that's the stated purpose of those projects, not a vulnerability in this list
- **Pricing disputes** (a platform claimed free that's actually freemium) — that's a normal [issue/PR](CONTRIBUTING.md), not a security report

## Reporting

Please **do not** open a public issue for a suspected malicious link — someone could click it before it's pulled.

Instead:

1. **GitHub Private Vulnerability Reporting** (preferred) — [Security tab](https://github.com/arif-offsec/ctfvault/security) → "Report a vulnerability"
2. **Direct message** via [@arif-offsec](https://github.com/arif-offsec) on GitHub

Include the exact URL, which section of the README it's in, and what you observed (redirect target, content served, etc.).

This project is maintained in spare time. Malicious-link reports will be prioritized and the offending entry removed as fast as possible once confirmed — usually within a day or two.

---

Thanks for helping keep this list safe to click through. 🗝️
