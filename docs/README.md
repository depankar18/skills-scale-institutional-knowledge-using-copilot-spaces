# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documentation. The README below provides a concise overview of our approach and quick links to each process document stored in this repository's docs/ folder.

## Project Management Summary

OctoAcme runs projects using an iterative, customer-first approach that emphasizes small, measurable deliveries and clear ownership. Work follows a simple lifecycle—initiation, planning, execution, release, and close—using lightweight artifacts to keep decisions and progress visible. Initiation produces a one-pager that clarifies the problem, success metrics, stakeholders, and an initial timeline; planning turns approved initiatives into prioritized backlogs, estimates, a Definition of Done, and a release milestone map.

Day-to-day execution is organized around a predictable workflow and a project board (Backlog → Ready → In Progress → In Review → QA → Done). Pull requests are kept small where possible, include issue links and acceptance criteria, and require passing CI (tests and linters) and at least one approval before merge. Sprint and iteration planning focus on pulling items that meet the Definition of Done and team capacity; dependencies and risks are captured explicitly in a risk register and escalated through defined paths when needed.

Roles and responsibilities are clearly defined so accountability is maintained across the lifecycle. Product Managers own problem definition, success metrics, and prioritization; Project Managers coordinate delivery, schedules, risk, and stakeholder communication; Developers implement features, write tests, and participate in reviews; QA ensures acceptance criteria and test plans are met; stakeholders provide input and approvals. This role clarity helps accelerate decisions and reduces single-person dependencies.

Quality assurance and communication are built into the process. QA is multi-layered—unit tests for logic, integration tests for cross-component behavior, end-to-end smoke tests for critical flows, and manual QA when acceptance requires human validation—combined with security scanning in CI. Communication cadence includes daily standups for blockers and progress, weekly delivery syncs and PM/PdM alignment, scheduled demos at the end of sprints or milestones, and weekly or milestone status updates to stakeholders; incident and escalation playbooks exist for rapid response and post-incident learning.

## Docs

- [Project Management Overview](octoacme-project-management-overview.md) — concise introduction to OctoAcme's approach, principles, roles, and lifecycle.
- [Project Initiation Guide](octoacme-project-initiation.md) — steps and one-pager template for starting new projects and deciding go/no-go.
- [Project Planning](octoacme-project-planning.md) — how to turn approved initiatives into prioritized backlogs, estimates, and release plans.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — team rhythms, workflows, PR guidance, and execution checklist.
- [Release & Deployment](octoacme-release-and-deployment.md) — release types, pre-release requirements, deployment checklist, and rollback playbook.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — running retrospectives and tracking improvements.
- [Risks & Communication](octoacme-risks-and-communication.md) — risk register format, communication templates, and escalation paths.
- [Roles & Personas](octoacme-roles-and-personas.md) — role definitions and responsibilities used across the process docs.

## How to use this README

- This README is the single entry point for OctoAcme's process documentation. Update links if files move.
- To add or update process documents, use the repository's issue template: "Add Content to Project Management Process Docs" (.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).
- Add new or updated content under docs/ and open a PR referencing the relevant process doc issue for review.
