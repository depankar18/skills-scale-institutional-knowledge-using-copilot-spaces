# OctoAcme Personas (expanded)

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It expands the existing core roles with additional supporting and cross-functional personas to improve clarity and accountability.

---

## Core Roles (unchanged)

(See original content for Developers, Product Managers, Project Managers; retain previous summaries and responsibilities.)

---

## Additional Personas (new)

### Engineering Manager
- Responsibilities:
  - Coordinate team capacity planning and resource allocation.
  - Support career development and performance coaching for engineers.
  - Make technical resourcing decisions and lead cross-team architectural efforts.
- How they interact with existing roles:
  - Work with Project Managers (PM) on resourcing, timelines, and availability.
  - Collaborate with Product Managers (PdM) about scope trade-offs that affect resourcing.
  - Support Developers during technical planning, code reviews, and implementation.
- Example scenarios:
  - During planning, the Engineering Manager confirms team capacity and suggests realistic sprint commitments.

### UX Researcher / Designer
- Responsibilities:
  - Lead user research, usability testing, and accessibility validation.
  - Produce wireframes, prototypes, and design specifications.
- How they interact with existing roles:
  - Partner with PdMs to shape product direction informed by user insights.
  - Work with Developers to ensure implementation fidelity and feasibility.
  - Provide QA with usability acceptance criteria and test cases.
- Example scenarios:
  - Early in discovery, the UX Researcher validates problem hypotheses to reduce rework.

### Release Engineer / CI Lead
- Responsibilities:
  - Own CI/CD pipelines, release automation, and deployment tooling.
  - Maintain rollback mechanisms and deployment playbooks.
- How they interact with existing roles:
  - Coordinate release windows with PMs and communicate deployment constraints.
  - Work with Developers and SREs to ensure deployments are reliable and observable.
  - Collaborate with QA to run pre-release verification jobs.
- Example scenarios:
  - When a release requires a complex migration, the Release Engineer designs the pipeline steps and rollback plan.

### Site Reliability Engineer (SRE) / On-call
- Responsibilities:
  - Maintain production reliability, monitoring, and alerting.
  - Lead incident response and post-incident work to improve system resilience.
- How they interact with existing roles:
  - Work with Developers to implement observability and reliability improvements.
  - Drive post-incident reviews with PMs and Stakeholders to prioritize remediation.
  - Coordinate with Release Engineers on safe rollout strategies.
- Example scenarios:
  - During a production incident, SRE leads the response and communicates status to stakeholders.

### Business Analyst / Data Analyst
- Responsibilities:
  - Translate business requirements into measurable acceptance criteria.
  - Define success metrics, run analyses, and validate outcomes post-release.
- How they interact with existing roles:
  - Partner with PdMs to clarify requirements and metrics.
  - Provide Developers with data schema and query requirements.
  - Share findings with Stakeholders to inform decisions.
- Example scenarios:
  - After launch, the Data Analyst measures key metrics and recommends follow-up experiments.

### Security Liaison
- Responsibilities:
  - Represent security requirements in planning and design.
  - Conduct threat assessments and ensure compliance with policies.
- How they interact with existing roles:
  - Engage Developers and SREs on secure implementation and CI security scans.
  - Escalate risks to Product/Project Leads and the Security team when needed.
- Example scenarios:
  - Prior to release, Security Liaison approves security mitigations and residual risk.

### Technical Writer / Documentation Owner
- Responsibilities:
  - Maintain user-facing and internal process documentation, release notes, and onboarding content.
  - Ensure docs are updated to reflect shipped behavior and process changes.
- How they interact with existing roles:
  - Work with Developers, QA, and PMs to capture changes and acceptance criteria.
  - Coordinate with Release Engineers for release notes and migration instructions.
- Example scenarios:
  - When features ship, Technical Writer publishes release notes and updates the project README.

---

## Guidance for Adding New Roles
- For each new persona, provide:
  - Role summary
  - Responsibilities
  - Interaction points with existing roles
  - Example scenarios (release planning, incident response, discovery)
- Add acceptance criteria for role adoption (who owns the role, onboarding checklist, contact points).

---

## Change Log
- 2026-07-08: Added Engineering Manager, UX Researcher/Designer, Release Engineer/CI Lead, SRE, Business/Data Analyst, Security Liaison, Technical Writer.
