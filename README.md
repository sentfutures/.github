# .github

Org-wide GitHub defaults for sentfutures. `workflow-templates/` holds the
starter workflows every repo sees under Actions → New workflow → "By
sentfutures" — currently the Claude PR review bot and the @claude mention
handler. These templates are thin callers; the shared logic and the setup
runbook live in [sentfutures/devops](https://github.com/sentfutures/devops).
Keep each template in sync with its twin in that repo's `callers/` directory.

> **⚠️ This repo silently changes every repo in the org.** Any community
> health file added here — `PULL_REQUEST_TEMPLATE.md`, `ISSUE_TEMPLATE/`,
> `CONTRIBUTING.md`, `SECURITY.md`, `CODE_OF_CONDUCT.md` — becomes the
> default for **every** sentfutures repo that lacks its own copy, with no
> opt-in from those repos. (`profile/README.md` likewise becomes the org's
> public profile page.) Workflow templates are the safe kind of content:
> they are suggestions only and change nothing until a repo adopts one.
> Add anything else here deliberately, and say so in the PR.
