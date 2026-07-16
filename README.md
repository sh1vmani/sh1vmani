# Shivamani Vastrala

**Security Engineer - Application & AI Security · Detection Engineering · Security Operations · Vulnerability Research**

Security Engineer with 3+ years across application and AI security, detection engineering,
and security operations in enterprise, cloud, and AI-driven environments. At Cybertrust
America I assess RAG-based AI platforms and LLM inference pipelines: prompt injection,
denial-of-wallet, broken access control, and CI/CD security gates. Earlier at TCS I spanned
application and operations security: web application penetration testing (SQL injection,
XSS, IDOR) and secure code review, alongside SIEM detection engineering and triage of 1,000+
daily alerts, cutting false positives 35% with Python threat-intel enrichment. Independently
I run coordinated vulnerability disclosure with 9 published CVEs in widely used WordPress
plugins. M.Eng. in Cybersecurity Engineering, University of Maryland.

---

## Featured Project: Vectrava

[![License](https://img.shields.io/badge/license-Apache--2.0-blue)](https://github.com/sh1vmani/vectrava)
[![Python](https://img.shields.io/badge/python-3.11%20%7C%203.12%20%7C%203.13-blue)](https://github.com/sh1vmani/vectrava)

**[vectrava](https://github.com/sh1vmani/vectrava)** is an AI application security scanner I
designed, built, and shipped end-to-end as a solo open-source project (Apache-2.0).

- 18 probes across three modules: Denial-of-Wallet, indirect prompt injection, and RAG
  pipeline boundary attacks.
- Every scan is gated behind an Ed25519-signed authorization scope with BYOK credential
  handling; it refuses to run on unsigned, expired, or untrusted scopes.
- Emits schema-validated SARIF v2.1.0, JSON, and HTML findings.
- Tamper-evident, hash-chained JSONL audit log with a `verify` command, plus per-invocation
  token and USD cost estimation. Authorization-gated by design under a documented dual-use
  safety posture.

---

## What I Work On

- **Application & AI Security**: Burp Suite DAST, SAST (Semgrep), OWASP Top 10, LLM threat
  modeling, prompt injection detection, RAG boundary evaluation, CI/CD security gates
- **Detection Engineering**: full detection lifecycle covering scoping, rule development,
  tuning, and validation; Python automation for threat-intel enrichment (VirusTotal, OSINT)
- **Security Operations & IR**: Splunk (SPL), Microsoft Sentinel (KQL), MITRE ATT&CK and
  Cyber Kill Chain mapping, end-to-end investigation and root cause analysis
- **Vulnerability Management**: Tenable Nessus, CVSS v3.1 prioritization, remediation validation
- **Cloud Security**: AWS IAM/S3/CloudFormation hardening, Prowler compliance automation,
  least-privilege enforcement

---

## Other Projects

| Project | Description |
|---|---|
| [secure-file-locker](https://github.com/sh1vmani/secure-file-locker) | Defense-in-depth path traversal remediation lab across OS, application, and network controls (OWASP WSTG-AUTHZ-01, CWE-22) |
| [trapnet](https://github.com/sh1vmani/trapnet) | Lightweight multi-service honeypot with built-in scanner detection |
| [wp-plugin-screener](https://github.com/sh1vmani/wp-plugin-screener) | WordPress plugin scanner and static authorization screener |

---

## Security Research

9 CVEs published through coordinated disclosure with WPScan for unauthenticated
authorization, injection, and account-takeover flaws in WordPress plugins. Findings with a
public proof-of-concept are linked below; the rest are added here as each WPScan embargo lifts.

| CVE | Plugin | Severity | Class |
|-----|--------|----------|-------|
| [CVE-2026-11869](https://wpscan.com/vulnerability/49170650-0006-4f3b-90f4-f8bb176beb7b) | WP DSGVO Tools (GDPR) < 3.1.40 | 7.5 High | Unauthenticated GDPR personal-data disclosure |
| [CVE-2026-12510](https://wpscan.com/vulnerability/b7825c8a-1817-4a17-b641-076e48ac7c2e) | AI Engine < 3.5.5 | 5.9 Medium | Subscriber+ IDOR, chatbot discussion takeover |
| [CVE-2026-12082](https://wpscan.com/vulnerability/d23cb7bd-b40c-4f87-a134-7c3b62043f18) | Praison AI SEO < 5.0.7 | 5.3 Medium | Unauthenticated broken access control (entire REST API) |
| [CVE-2026-12723](https://wpscan.com/vulnerability/76df2c61-4ba7-4987-9e61-5d02142b3db5) | Kirki < 6.0.12 | 5.3 Medium | Unauthenticated comment tampering / moderation bypass |
| [CVE-2026-11868](https://wpscan.com/vulnerability/a82da13b-ee86-495b-a684-324c1541d7ab) | WP Travel < 11.7.1 | 5.3 Medium | Unauthenticated arbitrary booking cancellation |

Additional disclosed CVEs, including two payment-bypass and one account-takeover (CVSS up to
8.1), publish through early August.

---

## Tech & Tools

`Python` `Bash` `SQL` `KQL` `SPL` Splunk Microsoft Sentinel CrowdStrike Falcon Cortex XDR
Burp Suite OWASP ZAP Semgrep Tenable Nessus Metasploit Wireshark Nmap Prowler
AWS (IAM, S3, CloudFormation) Kali Linux

---

## Certifications

- CompTIA Security+
- eJPT (INE Security)
- AWS Certified Security - Specialty
- OSCP (pursuing)
- CDSA (pursuing)

---

## Connect

- Email: shivamaniuni1@gmail.com
- LinkedIn: [linkedin.com/in/shivamanivastrala](https://linkedin.com/in/shivamanivastrala)
