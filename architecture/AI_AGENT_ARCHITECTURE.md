# AI Agent Architecture — V1

V1 is semi-automated. Agent roles are protocols, not necessarily separate software agents or accounts.

## Roles
- Planner: analyze requirements, scope, dependencies, risks and plan.
- Builder: implement approved task in isolated branch.
- QA: run tests and assess test coverage/risks.
- Reviewer: inspect diff and provide findings.
- Release assistant: prepare notes/checklists.

## Control points
- Issue is the source of task intent.
- Plan approval is required for high-risk/complex tasks.
- Branch isolates implementation.
- CI/test evidence supports review.
- Human owns merge, production actions and release approval.

## Later automation
Automation may be added only after V1 is used successfully. Any automation must have least privilege, bounded scope, auditable outputs and explicit approval gates for high-impact actions.
