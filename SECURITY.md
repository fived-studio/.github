# Security Policy

We take security seriously across every product and service in the FiveD Studio organization.

## Supported versions

We patch the **latest released minor version** of every actively maintained product. Older versions get fixes only for critical issues, on a best‑effort basis.

| Status | What it means |
| --- | --- |
| 🟢 Actively maintained | Security patches within target SLA |
| 🟡 Maintenance only | Critical patches only |
| 🔴 End‑of‑life | No further updates — please upgrade |

Status per repo lives in that repo's README.

## Reporting a vulnerability

**Please do not open a public GitHub issue for security problems.**

Use one of these instead:

1. **GitHub Private Vulnerability Reporting** — open a private advisory on the affected repository (preferred).
2. **Email** — `security@fived.studio` *(or contact a maintainer directly via the team list on our [org profile](https://github.com/fived-studio))*.

Please include:
- A clear description of the issue and its impact
- Steps to reproduce (PoC welcome)
- Affected repo, version, and environment
- Your contact info for follow‑up

## What to expect

| Step | Target |
| --- | --- |
| Acknowledgement | within **48 hours** |
| Initial triage & severity assessment | within **5 business days** |
| Fix or mitigation plan | within **14 days** for high/critical |
| Public disclosure | coordinated with the reporter |

We follow **coordinated disclosure**: we will not publicize the issue or release notes until a fix is available and reporters have had a chance to verify. Researchers acting in good faith will be credited (with consent) in the release notes and advisory.

## Out of scope

- Findings from automated scanners without a working PoC
- Social engineering, physical attacks, or attacks requiring privileged access already granted
- Vulnerabilities in third‑party dependencies that have no exploitable path through our code (please report upstream)

Thanks for helping keep our users safe.
