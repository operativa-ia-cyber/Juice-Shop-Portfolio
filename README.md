# OWASP Juice Shop Security Portfolio

A documented security-testing portfolio based on the intentionally vulnerable
[OWASP Juice Shop](https://owasp.org/www-project-juice-shop/) application.

> Educational use only. All testing was performed against a locally hosted,
> intentionally vulnerable training environment.

## Purpose

This repository demonstrates my methodology for reconnaissance, vulnerability
validation, risk assessment, and remediation reporting.

## Scope and Authorisation

- **Target:** OWASP Juice Shop (local lab instance)
- **Testing type:** Educational / authorised lab environment
- **Out of scope:** Real systems, third-party services, and production targets
- **Data handling:** No real user data, credentials, API keys, or tokens are included

## Environment

| Item | Details |
|---|---|
| Host operating system | macOS 26.5.1|
| Testing operating system | Kali Linux (VM) 2026.3 |
| Juice Shop version | 72208a244450 |
| Deployment method | Docker|
| Tools used | Nmap, Burp Suite, Zap, ffuf |

## Repository Structure

```text
.
├── images/       # Images related to the findings
├── findings/    # Individual vulnerability reports
└── README.md
