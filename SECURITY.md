# Security Policy

## Supported Versions

The Jiajiri organization actively maintains and applies security updates to the following repositories and branches:

| Repository | Branch / Target | Supported |
| :--- | :--- | :--- |
| `frontend-jiajiri` | `main` (Latest Production) | :white_check_mark: |
| `.github` | `main` | :white_check_mark: |

---

## Reporting a Vulnerability

The Jiajiri team is committed to ensuring candidate privacy, zero data leaks, and platform integrity. We appreciate the responsible disclosure of any security concerns.

### How to Report
Please **do not** report vulnerabilities through public GitHub issues, pull requests, or public forums.

Instead, please report security issues through one of the following methods:
1. **GitHub Private Vulnerability Reporting**: Use the **"Report a vulnerability"** tab on the relevant repository's Security page.
2. **Direct Maintainer Contact**: Contact the organization maintainer via GitHub at [@laphilemon](https://github.com/laphilemon).

### What to Include in Your Report
To help us triage and resolve the issue quickly, please provide:
- A clear description of the vulnerability and its potential impact.
- Step-by-step reproduction instructions or a minimal proof of concept (PoC).
- Affected URLs, endpoints, or components.
- Any suggested mitigations or patches if known.

### Response Timelines
- **Initial Acknowledgement**: Within 48 hours of submission.
- **Triage & Assessment**: Within 5 business days.
- **Remediation & Advisory**: We coordinate with the reporter on a timeline before any public disclosure.

---

## Strict Data & Privacy Guarantees
- The Jiajiri ATS scanner is architected to process resume data in-memory without persistent storage of candidate resumes or unconsented data sharing.
- External dependencies and packages are regularly audited for known CVEs.
