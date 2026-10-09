# .github

Org-wide GitHub defaults for sentfutures. It holds no workflow templates.

`workflow-templates/` used to offer the Claude PR review bot and the @claude
mention handler under Actions → New workflow → "By sentfutures". They were
retired on 2026-10-09:
- **Unused:** no repo had been set up from them.
- **Not visible everywhere:** repos under personal accounts never see org
  templates.
- **Drift:** keeping a second copy of each caller in sync had failed twice.

To install the bots, use `/install-review-bot` or copy the callers from
[sentfutures/devops](https://github.com/sentfutures/devops)' `callers/`
directory, as its README describes.

> **⚠️ This repo silently changes every repo in the org.** Any community
> health file added here — `PULL_REQUEST_TEMPLATE.md`, `ISSUE_TEMPLATE/`,
> `CONTRIBUTING.md`, `SECURITY.md`, `CODE_OF_CONDUCT.md` — becomes the
> default for **every** sentfutures repo that lacks its own copy, with no
> opt-in from those repos. (`profile/README.md` likewise becomes the org's
> public profile page.) Workflow templates are the safe kind of content:
> they are suggestions only and change nothing until a repo adopts one.
> Add anything else here deliberately, and say so in the PR.
