# Release Standard

## Versioning
Use `MAJOR.MINOR.PATCH` when applicable:
- MAJOR: incompatible changes.
- MINOR: backward-compatible feature.
- PATCH: backward-compatible bug fix.

## Release gate
- [ ] PR approved and merged.
- [ ] Required tests and build pass.
- [ ] Regression checks complete.
- [ ] DB migration reviewed and backup/rollback plan prepared if relevant.
- [ ] Release notes prepared.
- [ ] Deployment plan and rollback plan prepared.
- [ ] Human authorization for deployment obtained.
- [ ] Deployment verified.

AI agents may prepare release artifacts/checklists but must not deploy to production without explicit authorization.
