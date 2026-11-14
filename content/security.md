---
title: "Security"
slug: "security"
url: "/security/"
draft: false
comments: false
---

## Reporting a Vulnerability

This website welcomes feedback from security researchers and the general public to help improve our security. If you believe you have discovered a vulnerability, privacy issue, exposed data, or other security issue in any of our assets, we want to hear from you.

### Choose the right channel

Use a public GitHub issue in the affected repository for ordinary bugs, crashes, installation problems, false positives, false negatives, incorrect findings, severity disagreements, feature requests, and documentation corrections.

Use GitHub Private Vulnerability Reporting only for a credible vulnerability in the affected project itself:

1. Open the affected repository on [github.com/mlaify](https://github.com/mlaify).
2. Select its **Security** tab.
3. Select **Report a vulnerability**.

Do not put vulnerability details in a public issue, pull request, discussion, or comment. Automated scanner output without validation and a demonstrated project-specific impact is not sufficient by itself.

This is a coordinated vulnerability disclosure program, not a bug bounty. Payment, rewards, and swag are not offered or promised.

### Systems in Scope

This policy covers any digital assets owned, operated, or maintained by mlaify.io, including:

- **mlaify.io** — this site
- **Public repositories** under [github.com/mlaify](https://github.com/mlaify)

### What We Ask of You

Please give us at least **90 days** from your initial report to resolve the issue before any public disclosure.

When participating in our vulnerability disclosure program in good faith, we ask that you:

- Follow our [Vulnerability Disclosure Policy](https://github.com/mlaify/mlaify.io/blob/main/SECURITY.md) and any other applicable agreements;
- Report vulnerabilities promptly and avoid violating the privacy of others or disrupting our systems;
- Limit data access to the minimum required for a Proof of Concept;
- Cease testing and report immediately if you encounter any user data (PII, PHI, financial data); and
- Not engage in extortion.

### Our Commitments

You can expect us to:

- Respond to your report promptly and work with you to understand and validate it;
- Keep you informed about the progress of the vulnerability as it is processed;
- Remediate confirmed vulnerabilities in a timely manner; and
- Extend Safe Harbor for good-faith research conducted under this policy.

### Safe Harbor

We consider security research conducted under this policy to be authorized under applicable anti-hacking and anti-circumvention laws. We will not initiate or support legal action against researchers who act in good faith in accordance with this policy.

---

For the complete policy text, see [SECURITY.md](https://github.com/mlaify/mlaify.io/blob/main/SECURITY.md) in our repository.

> This policy follows the [disclose.io](https://disclose.io) vulnerability disclosure framework.

---

## Acknowledgements

We thank the researchers who have reported vulnerabilities to us under this
policy.

| Date | Researcher | Finding | Reference |
|---|---|---|---|
| 2026-11-11 | [0xhyu](https://github.com/0xhyu) | AttackMap: a pull request could silence its own findings under `--suppress-from-ref` | [GHSA-677m-4884-vg22](https://github.com/mlaify/AttackMap/security/advisories/GHSA-677m-4884-vg22) |
| 2026-11-11 | [0xhyu](https://github.com/0xhyu) | AttackMap: Markdown injection in generated reports | [GHSA-3qwr-cfpj-hgjr](https://github.com/mlaify/AttackMap/security/advisories/GHSA-3qwr-cfpj-hgjr) |

---

Thank you for helping keep this site secure.
