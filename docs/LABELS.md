# GitHub Labels — GuildPass Frontend

Create labels via **GitHub Settings → Labels** or with the GitHub CLI:

```bash
gh label create "good first issue" --color "7057ff" --description "Well-scoped task for new contributors"
gh label create "help wanted" --color "008672" --description "Extra attention or contributor help needed"
gh label create "bug" --color "d73a4a" --description "Something is not working"
gh label create "feature" --color "a2eeef" --description "New feature or enhancement request"
gh label create "documentation" --color "0075ca" --description "Improvements or additions to documentation"
gh label create "frontend" --color "f9d0c4" --description "Frontend / React / Next.js changes"
gh label create "ui" --color "fef2c0" --description "UI component or visual change"
gh label create "api-layer" --color "c5def5" --description "Changes to lib/api (mock or live)"
gh label create "wallet" --color "8b5cf6" --description "Wallet connect / wagmi / viem changes"
gh label create "tests" --color "bfd4f2" --description "Related to test coverage"
gh label create "a11y" --color "b2dfdb" --description "Accessibility improvement"
gh label create "priority: low" --color "eeeeee" --description "Low priority"
gh label create "priority: medium" --color "fbca04" --description "Medium priority"
gh label create "priority: high" --color "e99695" --description "High priority — address promptly"
gh label create "needs-triage" --color "ededed" --description "Awaiting maintainer triage"
gh label create "duplicate" --color "cfd3d7" --description "This issue or PR already exists"
```

## Label Usage Guide

| Label | When to use |
|---|---|
| `good first issue` | Clear scope, low risk, great for new contributors |
| `help wanted` | Community help wanted; may need more context |
| `bug` | Confirmed broken UI or integration |
| `feature` | New page, component, or capability |
| `documentation` | README or inline doc changes |
| `frontend` | General React / Next.js / TypeScript changes |
| `ui` | Visual-only changes (colour, spacing, layout) |
| `api-layer` | Changes to `lib/api/*` |
| `wallet` | Wallet connect flow or wagmi/viem hook changes |
| `tests` | Test-only changes |
| `a11y` | Accessibility improvements |
| `priority: high` | Blocks users — address within 48 h |
