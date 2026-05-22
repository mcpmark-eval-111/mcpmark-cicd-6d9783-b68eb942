---
name: Maintenance Report
about: Track maintenance, refactoring, dependency, or housekeeping work
title: "<short description> maintenance"
labels: maintenance, needs-triage
assignees: ''
---

## 🧹 Maintenance Report

Use this template for cleanup, refactoring, dependency upgrades, infra changes,
or any other housekeeping tasks. Please follow the **Maintenance Guidelines**
below so the work can be reviewed efficiently.

### Type of Maintenance

- [ ] Refactor
- [ ] Dependency upgrade
- [ ] CI / build / tooling
- [ ] Documentation
- [ ] Tech debt cleanup
- [ ] Other (describe)

### Description

Describe the maintenance work in detail. What is being changed and why?

### Scope

Which modules, packages, services, or workflows are affected?

### Impact & Risk

- Backwards-incompatible changes? (yes/no — if yes, describe)
- User-facing impact? (yes/no — if yes, describe)
- Rollback plan?

### Verification

How will this maintenance work be verified?

- [ ] Unit tests pass
- [ ] Lint / formatting checks pass
- [ ] Manual smoke test
- [ ] Other (describe)

### Schedule / Priority Hints (optional)

Use **low**, **nice-to-have**, **minor** for routine cleanup, or **medium /
normal** for standard maintenance. If the work is **urgent** or **blocking**,
mention it explicitly.
