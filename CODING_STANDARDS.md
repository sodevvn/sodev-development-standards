# Coding Standards

- Follow existing project conventions and architecture.
- Prefer clear, modular, maintainable code over clever abstractions.
- Avoid duplication where an existing shared implementation is appropriate.
- Validate inputs at boundaries and handle errors explicitly.
- Keep UI, domain logic, data access and integration concerns appropriately separated.
- Avoid unnecessary dependencies and unexplained configuration changes.
- Add or update tests for behavior changes.
- Document non-obvious decisions and public interfaces.
- Do not include secrets, customer data, or credentials in source, logs, fixtures, or screenshots.
- Do not make unrelated formatting or refactoring changes in feature/bugfix tasks.
- For SODEV web products, prefer TypeScript/Next.js for core web, SaaS, CRM, dashboard and API work; use Python for specialized AI, data processing, OCR or engineering automation when justified by the project.
