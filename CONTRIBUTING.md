# Contributing to Flowterm

Thanks for taking the time to help improve Flowterm.

## This repository is for **issue tracking only**

The Flowterm desktop application is **closed-source**. Its source code lives in a private repository and is not published. This public repo exists to give end users one place to:

- **Report bugs** — see [Bug report template](./.github/ISSUE_TEMPLATE/bug_report.md).
- **Request features** — see [Feature request template](./.github/ISSUE_TEMPLATE/feature_request.md).
- **Disclose security issues privately** — see [SECURITY.md](./SECURITY.md).

We **do not accept pull requests** here. Any PRs opened against this repo will be closed without review (please don't take it personally — there's just nothing to merge into). If you'd like to propose a behavior change, the best path is a clearly-described feature-request issue: workflow + pain point + sketched solution.

## How to file a good issue

A good issue takes about five minutes to write and saves an hour of back-and-forth.

1. **Search first.** Someone may already have reported it. If you find an existing issue, add a 👍 or a comment — that helps us prioritize.
2. **Use the template.** GitHub and GitLab both show the template inline when you open a new issue.
3. **Be specific.** "It crashes" is hard to act on; "On macOS 14.5 arm64, opening a new tab when the sidebar has more than ~50 hosts crashes the renderer within 2 seconds; here's the log" is gold.
4. **Attach logs.** Flowterm writes a log file you can grep:
   - macOS: `~/Library/Application Support/app.flowterm/flowterm.log`
   - Linux: `~/.local/share/app.flowterm/flowterm.log`
   - Windows: `%APPDATA%\app.flowterm\flowterm.log`
5. **Redact secrets.** Strip API tokens, host IPs, SSH key material, and private prompts before pasting.

## Triage labels

- `bug` — confirmed defect; expected behavior differs from actual.
- `enhancement` — feature requests, larger refactors of UX.
- `needs-repro` — we can't reproduce yet, please share more.
- `wontfix` — out of scope or by design; reasoning will be in a comment.
- `duplicate` — already tracked elsewhere; we'll link the canonical issue.

## Response times

We aim to acknowledge new issues within **2 business days**. We may not always have an immediate fix, but you'll hear from a human.

Security issues are handled out of band — please email <support@flowterm.ai> directly rather than filing a public issue.

## Code of conduct

Be kind. Be specific. Assume good faith. Anything overtly hostile, discriminatory, or harassing is grounds for removal without notice. We're a small team and our patience for bad-faith engagement is short — please save us the energy and we'll do the same for you.
