---
title: "Security"
slug: "security"
url: "/security/"
lastmod: 2026-11-16
draft: false
comments: false
---

## Security reporting

M&L AI is run by volunteers. We do our best to provide security and support for all of our
projects, but both are best effort: there is no guaranteed response, fix, or timeline.
Coordinated vulnerability disclosure (CVD) under this vulnerability disclosure policy (VDP) is
handled the same way. M&L AI is not a commercial security service and has no dedicated security
or support team.

The complete and canonical policy is the
[mlaify organization-wide security reporting policy](https://github.com/mlaify/.github/blob/main/SECURITY.md).

There is no bug bounty or paid disclosure program. Payment, rewards, sponsorship, employment,
gifts, and swag are not offered or promised. A report does not create an obligation to respond,
investigate, remediate, publish an advisory, provide credit, or coordinate disclosure.

Unless a project explicitly documents otherwise, maintainer development and testing are on
macOS. Linux support is best effort only where documented, and Windows is unsupported.

### Choose the right GitHub channel

Use a public GitHub issue in the affected repository for ordinary bugs, crashes, installation or
compatibility problems, false positives or negatives, incorrect findings, feature requests, and
documentation corrections.

For a credible, confidential vulnerability in a project itself:

1. Open the affected repository on [github.com/mlaify](https://github.com/mlaify).
2. Select its **Security** tab.
3. Select **Report a vulnerability**.

Do not put unpatched vulnerability details in a public issue, pull request, discussion, or
comment. Reports sent by email are not processed. Automated scanner output without manual
validation and a demonstrated project-specific impact is not sufficient.

Machine-readable reporting details are at [/.well-known/security.txt](/.well-known/security.txt).

### Scope for this website

The deployed **mlaify.io** site and its
[source repository](https://github.com/mlaify/mlaify.io) are in scope under the canonical policy.
Other `mlaify` repositories are covered individually by that same policy.

---

## Acknowledgements

Previous acknowledgements do not create a commitment to respond to or remediate future reports.

| Date | Researcher | Finding | Reference |
|---|---|---|---|
| 2026-11-11 | [0xhyu](https://github.com/0xhyu) | AttackMap: a pull request could silence its own findings under `--suppress-from-ref` | [GHSA-677m-4884-vg22](https://github.com/mlaify/AttackMap/security/advisories/GHSA-677m-4884-vg22) |
| 2026-11-11 | [0xhyu](https://github.com/0xhyu) | AttackMap: Markdown injection in generated reports | [GHSA-3qwr-cfpj-hgjr](https://github.com/mlaify/AttackMap/security/advisories/GHSA-3qwr-cfpj-hgjr) |
