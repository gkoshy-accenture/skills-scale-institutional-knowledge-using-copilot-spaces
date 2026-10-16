# OctoAcme Project Management

This README centralizes OctoAcme's project management process documents and provides a concise overview of the processes used across projects. It serves as a single-entry index to the detailed process documents in the docs/ folder and is intended for onboarding, handbook references, and as a starting point for process improvements.

OctoAcme runs projects with a lightweight, lifecycle-driven approach that moves work from Initiation through Planning, Execution, Release, and Retrospective. Initiation focuses on validating the business need and producing a one‑pager with success metrics, stakeholders, and a high‑level timeline. Planning turns approved initiatives into a prioritized backlog of shippable increments with acceptance criteria, estimates, and a Definition of Done; it also captures dependencies and risks in a Risk Register. Execution emphasizes small, frequent deliveries using a project board and standard pull request practices so the team can iterate on measurable outcomes.

Workflows center on a standard PR and CI practice: small, focused pull requests where possible, PRs that include issue links and acceptance criteria, automated tests and linting in CI, and a review policy requiring at least one approval before merge. Releases follow a documented checklist (pre‑release checks, staging smoke tests, automated pipelines where possible) and include rollback/mitigation plans and release notes. Post‑deploy verifications and incident playbooks provide clear steps for triage and blameless root‑cause follow‑up when issues arise.

Roles and communications are explicit: a named Project Manager coordinates delivery, schedules, and stakeholder communications; a Product Manager owns outcomes and backlog prioritization; developers implement and test features; QA validates acceptance criteria; and stakeholders provide inputs and approvals. Regular cadence includes daily standups for blockers and progress, weekly delivery syncs for status and risks, demos at the end of sprints or milestones, and monthly stakeholder updates. Escalation paths are defined (team → PM → Product Lead → Sponsor) for unresolved or business‑impacting issues.

Quality assurance and observability are integrated across the lifecycle: unit and integration tests, security scanning in CI, smoke tests for critical flows, and manual QA for feature acceptance when needed. Dashboards track velocity, burndown, errors, latency, and usage tied to project success metrics. Retrospectives capture learnings, prioritize 2–3 actionable improvements, assign owners and due dates, and track outcomes in the backlog so changes are measurable and iteratively validated.

## Documents
- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)

## How to use this README
- Use this file as the landing page for project management processes in the repo.
- Update individual documents in the docs/ folder when you need to add details or examples specific to a process area.
- For major process changes, open a Process Doc Update issue using the .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml template and link the change to that issue.

