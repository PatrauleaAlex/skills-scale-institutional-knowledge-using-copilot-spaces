# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management process library. This folder contains standardized guidance for running projects from initiation through retrospectives.

## Quick Start

- **New to OctoAcme?** Start with [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)
- **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md)
- **In the middle of delivery?** Check [Execution & Tracking](./octoacme-execution-and-tracking.md)
- **Need to understand roles?** Review [Roles & Personas](./octoacme-roles-and-personas.md)

## Full Documentation Map

### Core Processes

1. [Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction, principles, roles, and communication cadence
2. [Project Initiation](./octoacme-project-initiation.md) — How to validate, authorize, and align stakeholders on new work
3. [Project Planning](./octoacme-project-planning.md) — Breaking work into actionable backlog and milestones
4. [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day delivery, testing, quality, and blocker escalation
5. [Risk Management & Communication](./octoacme-risks-and-communication.md) — Managing risks, dependencies, and stakeholder updates
6. [Release & Deployment](./octoacme-release-and-deployment.md) — Pre-release requirements and deployment safety
7. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings and driving improvements

### Reference

- [Roles & Personas](./octoacme-roles-and-personas.md) — Definition of typical project roles and responsibilities

## OctoAcme Principles

- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Deliver small, testable increments
- **Clear ownership:** Each project has a named PM and Product Lead
- **Data-informed:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

## Project Management Process Overview

OctoAcme operates on a structured yet iterative project management framework designed around five key phases: **Initiation, Planning, Execution, Release, and Retrospective**. Each project has a named Project Manager (PM) who coordinates delivery and a Product Manager (PdM) who defines outcomes and measures success.

### Core Approach and Lifecycle

Projects begin with an **Initiation Gate**, where stakeholders validate business need through a lightweight Project One-pager that captures the problem statement, SMART goals, success metrics, and initial risk assessment. Once approved, the team moves into detailed **Planning**, where work is broken into shippable increments with prioritized backlogs, acceptance criteria, and a clear Definition of Done. This structured gate-keeping ensures alignment before significant resources are committed.

### Team Roles and Communication

The OctoAcme framework defines four primary personas:

- **Developers** — Implement features and maintain quality through testing and code reviews
- **Product Managers** — Prioritize the roadmap and validate solutions through metrics
- **Project Managers** — Coordinate schedules, manage risks, and ensure transparency
- **Stakeholders** — Provide inputs and approvals

Communication is highly structured with a **twice-weekly standup** for the delivery team, a **weekly sync between PM and PdM**, and **monthly stakeholder updates**. Daily standups focus on progress, blockers, and dependencies, while weekly delivery syncs present flagged risks and demo work. Risk escalation paths move from team-level triage through the PM to the Product Lead and sponsor for business-impacting issues.

### Execution, Quality, and Release Standards

During the **Execution phase**, teams use GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) and maintain a disciplined Pull Request workflow: small PRs (≤400 lines), inclusion of issue links and acceptance criteria, and mandatory CI checks before review. Quality is enforced through **unit tests, integration tests, and end-to-end smoke tests** for critical flows, alongside security scanning in CI and manual QA for feature acceptance.

Before **Release**, all acceptance criteria must be met, CI and security scans must pass, and a rollback plan must be documented. Releases follow semantic versioning (Patch, Minor, Major) with pre-staging smoke tests and post-deployment verifications. A **Risk Register** tracked throughout the project captures ID, description, impact, likelihood, mitigation plans, and status, reviewed weekly to enable proactive management.

### Continuous Improvement and Learning

After each sprint, release, or milestone, OctoAcme holds **Retrospectives** (45–75 minutes) to capture what went well, what could improve, and generate 2–3 prioritized action items with clear owners and due dates. These learnings feed directly back into the project backlog and process documentation, creating a knowledge-sharing ecosystem where tacit expertise is surfaced, validated, and made accessible to all team members.

## Navigation by Role

### For New Team Members
1. Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand the big picture
2. Review [Roles & Personas](./octoacme-roles-and-personas.md) to find your role
3. Explore the phase that's most relevant to your current work

### For Project Managers
- [Project Initiation](./octoacme-project-initiation.md) — Kickoff and stakeholder alignment
- [Project Planning](./octoacme-project-planning.md) — Backlog and timeline management
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Team rhythm and delivery
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Risk registers and stakeholder updates
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings

### For Developers
- [Project Planning](./octoacme-project-planning.md) — Understanding acceptance criteria and DoD
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — PR workflow, testing, and quality standards
- [Release & Deployment](./octoacme-release-and-deployment.md) — Pre-release and deployment processes

### For Product Managers & Stakeholders
- [Project Management Overview](./octoacme-project-management-overview.md) — Methodology and communication cadence
- [Project Initiation](./octoacme-project-initiation.md) — Validating business need and success metrics
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Stakeholder communication templates
- [Release & Deployment](./octoacme-release-and-deployment.md) — Release notes and announcements

## Key Artifacts

- **Project Charter / One-pager** — Problem, goal, success metrics, and stakeholders
- **Roadmap and Release Plan** — Milestones and release schedule
- **Sprint/Iteration Backlog** — Prioritized work with acceptance criteria
- **Risk Register** — Tracked risks with mitigation plans and status
- **Definition of Done** — Acceptance standards for all work
- **Retrospective Notes & Action Items** — Captured learnings and improvements

## Continuous Documentation

This documentation is a living resource. If you identify gaps, improvements, or new processes that should be captured, please create an issue using the [Process Doc Update template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) in the `.github/ISSUE_TEMPLATE/` folder.

## Questions or Process Improvements?

For questions about these processes or to suggest improvements, reach out to your PM or PdM team. We're committed to keeping this documentation current and accessible to all team members.
