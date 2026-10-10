# Security Policy

## Reporting a vulnerability

**Do not open a public issue for security vulnerabilities.**

Email [security@brimble.app](mailto:security@brimble.app) with:

- A description of the vulnerability and its potential impact
- Steps to reproduce (proof of concept, requests, screenshots)
- Affected component, URL, or version/commit
- Your contact details for follow-up

We aim to acknowledge reports within 2 business days. We will keep you updated
as we investigate and fix the issue, and we ask that you give us reasonable
time to remediate before any public disclosure (we target 90 days or less).

## Scope

In scope:

- [brimble.io](https://brimble.io), [app.brimble.io](https://app.brimble.io),
  [paper.brimble.io](https://paper.brimble.io)
- Brimble APIs, Sandboxes, databases, object storage, and managed infrastructure
- Open-source code in [@brimblehq](https://github.com/brimblehq) repositories

Out of scope:

- Third-party services Brimble depends on
- Social engineering, phishing, or physical attacks
- Denial-of-service testing against production

## Ground rules

- Do not access, modify, or delete other users' data.
- Do not degrade service availability or run automated scanners against
  production at high volume.
- Do not exfiltrate data beyond what is necessary to demonstrate the issue,
  and delete it afterwards.
- Never share private credentials, tokens, or customer data in reports —
  redact them.

## Supported versions

We support the latest release of each actively maintained repository. Security
fixes are released as soon as they are ready; there is no fixed LTS schedule.

## Disclosure

Once a fix is deployed, we will coordinate disclosure with the reporter.
We credit reporters who wish to be acknowledged.
