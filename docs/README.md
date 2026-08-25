# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Docs. This directory contains comprehensive guidance for running projects at OctoAcme, from initiation through retrospectives. Below you’ll find a concise overview of our processes, a quick-start guide to which document to consult at each stage, and links to templates and checklists.

## Brief Overview of OctoAcme Processes

OctoAcme manages work through a staged lifecycle: initiation, planning, execution, release, and retrospective. Initiation focuses on validating the business need with a Project One-pager, aligning stakeholders, and deciding whether to move into planning. Planning turns approved initiatives into an actionable backlog, defines the Definition of Done, identifies dependencies and risks, and produces a release timeline.

Execution emphasizes visible workflows and continuous delivery: teams use a project board (Backlog → Ready → In Progress → In Review → QA → Done), run a disciplined pull request process with CI gates and small PRs, and hold regular rhythms (daily standups, weekly delivery syncs, demos). Quality assurance is enforced through unit and integration tests, end-to-end smoke checks for critical flows, security scanning in CI, and manual QA when needed. Releases follow a pre-release checklist, automated deployment pipelines where possible, rollback plans, and post-deploy verifications.

After delivery, OctoAcme captures learnings in timeboxed retrospectives, prioritizes 2–3 action items, and tracks improvements as issues with owners and due dates. Risk management and stakeholder communication are continuous activities—teams maintain a risk register, escalate blockers through defined paths (team → PM → Product Lead → Sponsor), and use weekly status templates to keep stakeholders aligned.

## Quick Start: Find Your Process

| Project Stage | Document | Purpose |
|---|---|---|
| Starting a new project | [Project Initiation Guide](./octoacme-project-initiation.md) | Validate business need, align stakeholders, create lightweight plan |
| Planning & scoping | [Project Planning](./octoacme-project-planning.md) | Break work into shippable increments, identify dependencies & risks |
| Day-to-day delivery | [Execution & Tracking](./octoacme-execution-and-tracking.md) | Manage standups, PRs, quality, testing, blocker escalation |
| Managing uncertainty | [Risk Management & Communication](./octoacme-risks-and-communication.md) | Identify risks, manage dependencies, communicate with stakeholders |
| Shipping to production | [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Standardize release process, reduce risk, improve observability |
| Learning & improving | [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capture learnings, convert into actionable improvements |

## Complete Documentation Index

- [Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, roles, key artifacts, and lifecycle
- [Project Initiation Guide](./octoacme-project-initiation.md) — When to start a project, validation steps, minimum deliverables, and decision gates
- [Project Planning](./octoacme-project-planning.md) — Turning approved initiatives into actionable plans, creating backlogs, managing dependencies
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day workflows, PR standards, quality gates, blocker escalation
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Building and maintaining a risk register, stakeholder communication, escalation paths
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Release types, pre-release checklist, deployment process, rollback procedures
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Running effective retrospectives, tracking improvements, building learning culture
- [Roles & Personas](./octoacme-roles-and-personas.md) — Detailed personas for Project Managers, Product Managers, and Developers

## Core Principles

- Customer-first: prioritize customer value and usability
- Iterative delivery: deliver small, testable increments
- Clear ownership: each project has a named PM and Product Lead
- Data-informed decisions: measure impact and iterate based on evidence
- Psychological safety: encourage feedback and learning

## Key Roles (See Roles & Personas for details)

- Project Managers: coordinate delivery, manage schedules, risks, and communications
- Product Managers: define outcomes, prioritize backlog, measure success
- Developers: implement features, collaborate on design and testability
- QA/Testing: validate quality and acceptance criteria

## Frequently Used Templates & Checklists

- Project One-pager template (in Project Initiation Guide)
- Backlog Item template (in Project Planning)
- Risk Register format (in Risk Management & Communication)
- Release Notes template (in Release & Deployment Guide)
- Action Item template (in Retrospective & Continuous Improvement)

## Getting Started as a New Team Member

1. Start with [Project Management Overview](./octoacme-project-management-overview.md) to understand the big picture
2. Read [Roles & Personas](./octoacme-roles-and-personas.md) to find your role
3. Navigate to the process docs relevant to your current project stage
4. Use this README as your reference map to find answers

## Contributing to These Docs

OctoAcme's processes evolve as we learn and improve. To propose updates:

1. File an issue using the "Add Content to Project Management Process Docs" template
2. Include your suggested content and rationale
3. Collaborate with the team for review and refinement
4. Updates should align with existing principles and be reviewed for consistency

---

(Generated from issue #2 — when this change is merged, include "Closes #2" in the pull request description.)
