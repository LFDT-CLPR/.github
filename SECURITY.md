# Security Policy

This policy aligns with the
[LF Decentralized Trust security vulnerability disclosure policy](https://lf-decentralized-trust.github.io/governance/governing-documents/security).
It applies to every repository in this GitHub organization that does not publish its own
`SECURITY.md`.

## Reporting a Vulnerability

If you think you have discovered a security issue in any of the repositories in this GitHub
organization, we'd love to hear from you. We take all security bugs seriously, and if one is
confirmed upon investigation we will patch it within a reasonable amount of time and release a
public security advisory describing the impact and crediting the discoverer.

**Please do not report security vulnerabilities through public GitHub issues, discussions, or pull
requests.**

### Report privately through GitHub

The preferred way to reach us is GitHub's private vulnerability reporting, which opens a
confidential thread visible only to you and the project maintainers:

1. Go to the **Security** tab of the affected repository.
2. Click **Report a vulnerability** (under *Advisories*).
3. Fill in the report and submit it.

You can also go straight there with the URL
`https://github.com/<org>/<repository>/security/advisories/new`, substituting the repository where
you found the issue. For example, to report an issue in this repository, use
[hyperledger/.github/security/advisories/new](https://github.com/hyperledger/.github/security/advisories/new).

If the **Report a vulnerability** button is not available on the repository in question, please
report by email instead.

### What to include

The more detail you can give us, the faster we can confirm and fix the issue. Where possible,
please include:

- The affected repository, version, commit, or release.
- A description of the vulnerability and its potential impact.
- Step-by-step instructions to reproduce it, including any proof-of-concept code.
- Your assessment of the severity, and any suggested mitigation or fix.
- How you would like to be credited in the advisory, if the issue is confirmed.

### Report by email

Reports are also always accepted by email to the LF Decentralized Trust security list,
[security@lists.lfdecentralizedtrust.org](mailto:security@lists.lfdecentralizedtrust.org). Include
the name of the project or repository along with the details listed above. If triage determines the
issue is a security vulnerability, the security team will open a GitHub security advisory for it.

## What to expect

- We will acknowledge receipt of your report within 2 business days.
- We will keep you updated on our progress and let you know if we need more information.
- We will coordinate a fix and a public advisory with you, and credit you unless you ask us not to.

Please keep the details of the issue confidential until we have published an advisory, so that
users have a chance to update.
