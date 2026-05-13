# Security policy

Thank you for taking the time to disclose a Flowterm security issue responsibly.

## Reporting

**Please email <support@flowterm.ai>** with the subject line `SECURITY: <short description>`. Do not open a public GitHub or GitLab issue — that exposes the vulnerability before a fix is shipped.

Include:

- A description of the issue and its impact.
- Steps to reproduce, or a proof-of-concept.
- Your platform, Flowterm version, and any relevant environment.
- Whether you would like to be credited in the release notes once the fix is shipped (and under what handle).

## What to expect

- We acknowledge new reports within **2 business days**.
- We aim to ship a fix or a public mitigation within **30 days** for high-severity issues.
- We will keep you informed during triage and remediation.
- We're happy to credit you publicly after the fix ships, with your consent.

## In scope

- The desktop application (`flowterm` / `Flowterm.app`).
- The Flowterm-operated sync / auth backend (`*.flowterm.ai`).
- The website (`flowterm.ai`).

## Out of scope

- Third-party SSH servers, or any host you connect *to* with Flowterm. Flowterm is a client; remote host vulnerabilities should be reported to that host's vendor.
- Vulnerabilities that require physical access to an unlocked, signed-in machine.
- DoS via running unbounded numbers of sessions or files locally.
- Issues in unmaintained or unreleased branches.
