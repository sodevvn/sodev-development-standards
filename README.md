# SODEV AI Software Factory — Development Standards

Central standards for SODEV projects developed with AI coding agents and human oversight.

## Documents
- `SODEV_AI_SOFTWARE_FACTORY.md`: overall operating model
- `AI_AGENT_RULES.md`: agent behavior and authorization boundaries
- `DEVELOPMENT_WORKFLOW.md`: task lifecycle
- `CODING_STANDARDS.md`: code quality and scope rules
- `GIT_WORKFLOW.md`: branch, commit, PR practices
- `CODE_REVIEW.md`: review checklist
- `TESTING_STANDARD.md`: testing requirements
- `RELEASE_STANDARD.md`: release and deployment safeguards
- `templates/`: reusable task, bug and PR templates

## Starting principle
AI agents may implement scoped tasks and run checks, but they must not merge to `main`, deploy to production, perform destructive data operations, or change approved architecture without explicit human approval.

Treat this repository as the source of truth for standards. Project-specific `AGENTS.md` files may add rules but must not weaken security and approval requirements here.
