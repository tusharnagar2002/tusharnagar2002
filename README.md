# Hi, I'm Tushar 👋

Open-source contributor learning by shipping — Python fixes, docs, and dev tooling.

📍 Mumbai, India

## 🚀 Projects

- **[inbox-archaeology](https://github.com/tusharnagar2002/inbox-archaeology)** — finds the accounts you've forgotten you have, by scanning an email export (Google Takeout) locally for signup emails. No OAuth, no upload, no server — entirely offline. 59 tests, including real bugs caught by testing against actual mbox files rather than mocks.
- **[Second Look](https://tusharnagar2002.github.io/second-look/)** — paste a suspicious text or email, get a plain-language scam check. Built for non-developers. Nothing ever leaves your device. 36 tests including automated accessibility (WCAG AA) validation.
- **[Is This Phishing?](https://github.com/tusharnagar2002/is-this-phishing)** — a browser extension that checks the site you're on for phishing patterns automatically, entirely locally, with zero network requests. 53 tests; a real security issue was caught by Mozilla's official extension linter during development and fixed structurally, not patched over.

A small suite tackling the same real gap from three angles — as AI agents contribute more code, there's no standard way to find a repo's policy on it, enforce good behavior while working, or verify what actually happened afterward:

- **[ai-recon](https://github.com/tusharnagar2002/ai-recon)** — finds a repo's AI-contribution policy (banned / disclosure-required / allowed / unclear) before you invest time contributing to it. 56 tests, validated against real projects' actual policies.
- **[in-lane](https://github.com/tusharnagar2002/in-lane)** — a Claude Code plugin that keeps every code change scoped to exactly what was asked, with exceptions for security and data-loss issues that are never traded away for a smaller diff. `claude plugin validate --strict` passing in CI.
- **[git-vouch](https://github.com/tusharnagar2002/git-vouch)** — verifiable attestation for AI-assisted commits: a computed (not hand-typed) diff stat in a git trailer, protected by the commit's own signature.

Also: **[beachhead](https://github.com/tusharnagar2002/beachhead)** — a zero-dependency CLI that automates fork → wait → clone → branch, the setup before a contribution. 62 tests, CI passing on every push.

## 🌱 Recent work

Getting started with open source, one focused PR at a time:

- **[The-PR-Agent/pr-agent](https://github.com/The-PR-Agent/pr-agent)** — fixed an inverted line-range bug in the GitLab/Gitea link builders and extracted a shared normalization helper onto the base provider class, with new regression tests.
- **[eduMFA/eduMFA](https://github.com/eduMFA/eduMFA)** — documented an undocumented audit config option (`EDUMFA_AUDIT_SQL_COLUMN_LENGTH`) in both the class docstring and the install reference docs.
- **[wheelry/deep-skill-finder](https://github.com/wheelry/deep-skill-finder)** — added a `--dry-run` preview mode to the skill installer, reporting files, scripts, external URLs, env vars, and basic security notes before anything touches disk.
- **[MetOffice/CMEW](https://github.com/MetOffice/CMEW)** — improved a confusing validation error message so it tells you how to fix it (`-O <site>`), not just that something's wrong.
- **[vinhnguyenthanhdn/claude-jobs](https://github.com/vinhnguyenthanhdn/claude-jobs)** — fixed a silent bug where the scheduler's random start delay was capped at ~9 hours regardless of the configured value, and added the first end-to-end tests exercising that delay.
- **[mycelium-labs/mycelium](https://github.com/mycelium-labs/mycelium)** — pinned every third-party GitHub Action to an immutable commit SHA (with readable version comments) and added the missing Dependabot config so the pins stay maintainable.
- **[Hebbian-Robotics/hflow](https://github.com/Hebbian-Robotics/hflow)** — documented 7 metadata keys a data importer was silently writing that FORMAT.md never named, including 6 that gate a correctness-critical resume decision.

## 🛠️ Currently focused on

Python and JavaScript — widening out to other ecosystems as I go.

## 📫 Reach me

Open an issue or PR on any of my repos, or find me here on GitHub.

---
<sub>This README is a work in progress and updates as new contributions land.</sub>
