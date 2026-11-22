# Git Workflow

## Branches
- `main`: protected, stable.
- `feature/<issue-id>-<short-name>`: features.
- `bugfix/<issue-id>-<short-name>`: bug fixes.
- `hotfix/<issue-id>-<short-name>`: urgent fixes (still reviewed; emergency process documented).
- `refactor/<issue-id>-<short-name>`: scoped refactoring.

## Commit format
`<type>: <description>`
Types: feat, fix, refactor, test, docs, chore, perf.
Example: `fix: correct date range filtering`

## Rules
- One task per branch where practical.
- No direct commits to `main`.
- Push branch and open PR.
- Link PR to issue.
- Keep changes focused.
- Do not commit secrets or real customer data.
- Delete merged branches where appropriate.
