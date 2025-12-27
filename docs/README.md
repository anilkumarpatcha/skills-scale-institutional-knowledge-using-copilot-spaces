# OctoAcme Project Management Docs

This README serves as an index and summary for all program management process documentation in this repository. It centralizes project management knowledge to accelerate onboarding, improve discoverability, and encourage consistent use of documented best practices.

## Project Management Summary

OctoAcme manages projects using an iterative, data-driven, cross-functional approach from initiation and planning through execution, release, and continuous improvement. Each stage is supported by lightweight artifacts — project one-pagers, risk registers, Definition of Done checklists — and clear decision gates to reduce ambiguity.

Teams operate with defined workflows and explicit roles: Product Managers (define outcomes and prioritize), Project Managers (coordinate delivery, schedules, and communications), Developers (implement and test), and QA (validate acceptance criteria). Work is tracked on project boards, with a regular cadence of standups, weekly delivery syncs, and demos. Pull request practices require linked issues, acceptance criteria, passing CI (tests and linters), and at least one approval before merging.

Quality assurance is integrated into the pipeline via unit/integration tests, end-to-end smoke tests for critical flows, and automated security scanning in CI. Releases follow a standardized checklist: staging verification, smoke testing, rollback plans, release notes, and stakeholder communication. Retrospectives after sprints, releases, or incidents convert learnings into prioritized action items that are tracked and reviewed to ensure continuous improvement.

## Key Project Management Processes (with Links)

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

## How to use these docs

- Keep the Project One-pager and project README updated in the project repo.
- Use the checklists and templates in the associated docs during initiation, planning, execution, release, and retrospectives.
- Add process-specific or sensitive artifacts into `.copilot/` if you want Copilot Spaces to use them as workspace context.

---
