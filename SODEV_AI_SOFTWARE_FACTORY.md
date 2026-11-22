# SODEV AI Software Factory

## Operating model
Human Product Owner / Technical Lead owns product intent, priority, acceptance, architecture approval, and release approval. AI agents support analysis, implementation, testing, review, and documentation.

## Standard delivery flow
1. Backlog: capture the request.
2. Ready: requirements, scope and acceptance criteria are clear.
3. Analysis: agent examines repository context and proposes a plan.
4. Approval: human approves plans for complex, risky, architectural or data-changing tasks.
5. Development: agent works on a task branch and stays within scope.
6. Testing: agent runs applicable checks and reports evidence.
7. Pull Request: agent prepares a PR summary and review evidence.
8. Review: human review is required before merge.
9. Release: human authorizes release/deployment.

## Work modes
- Small, low-risk task: agent may plan and implement without separate plan approval, but still must test and create a PR.
- Complex or risky task: plan approval required before implementation.
- Architecture, database schema/data migration, authentication, authorization, security, external integrations, API breaking changes, dependency changes with significant impact, or production operations: explicit human approval required.

## Roles
- Product Owner: requirements, priorities, acceptance, product decisions.
- Technical Lead: architecture, technical constraints, risk decisions, review.
- Coding Agent: implementation and tests for assigned task.
- QA Agent: independent checks and test analysis when feasible.
- Review Agent: review findings; not final approval authority.

## Definition of Done
- Acceptance criteria met.
- Scope checked; no unrelated changes.
- Tests and build executed, results accurately reported.
- Risks and limitations documented.
- PR reviewed and approved.
- Documentation updated when needed.
- Merge and release performed by authorized human.
