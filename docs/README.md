# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation. This folder contains the complete set of processes, workflows, and guidance used to initiate, plan, execute, and deliver projects at OctoAcme.

## Overview

OctoAcme uses a lightweight, iterative project management approach centered on customer value and continuous improvement. The process follows a structured lifecycle:

1. **Initiation**: Validate business need and stakeholder alignment by creating a Project One-pager that defines the problem statement, success metrics, and resource requirements.
2. **Planning**: Break work into a prioritized, estimated backlog with clear acceptance criteria and a defined Definition of Done.
3. **Execution**: Deliver work through a structured rhythm of daily standups, weekly syncs, and milestone-based demos. Teams operate using a project board with small PRs (≤400 lines) that include issue links and acceptance criteria.
4. **Release**: Deploy features through a standardized release process with pre-release requirements, deployment checklists, and rollback playbooks to minimize risk and ensure observability.
5. **Retrospective & Continuous Improvement**: Capture learnings after each sprint, release, or milestone, converting them into actionable improvements with clear owners and due dates.

Key to OctoAcme's success is clear role definition (Project Managers, Product Managers, Developers, QA), consistent communication rhythms (daily standups, weekly syncs, monthly stakeholder updates), and embedded quality practices (unit tests, integration tests, security scanning in CI, manual QA validation). Risk management is continuous—teams maintain a Risk Register and escalate blockers through defined levels to prevent delays and surface issues early.

## Documentation Index

- **[Project Management Overview](./octoacme-project-management-overview.md)** — Introduction to OctoAcme's approach, core roles, key artifacts, and high-level lifecycle
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- **[Project Planning](./octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog for delivery
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution and tracking progress toward project milestones
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardized process for releasing features to production and managing rollbacks
- **[Risks & Communication](./octoacme-risks-and-communication.md)** — How to identify, manage, and communicate risks and dependencies
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Define typical roles and responsibilities (Developers, Product Managers, Project Managers)

## Getting Started

- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a concise introduction.
- **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md) to validate your idea and get approval.
- **Executing a project?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) for day-to-day workflows and the project board.
- **About to release?** Review the [Release & Deployment Guide](./octoacme-release-and-deployment.md) for pre-release checklists and deployment steps.
- **Wrapping up or hitting a snag?** Check [Risks & Communication](./octoacme-risks-and-communication.md) and [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) for guidance.

## Key Artifacts

Across all phases, OctoAcme projects produce and maintain:

- **Project Charter / One-pager** — Problem statement, goals, success metrics, stakeholders, timeline
- **Backlog & Acceptance Criteria** — Prioritized list of work with clear Definition of Done
- **Risk Register** — Tracked risks with impact, likelihood, mitigation, and owner
- **Project Board** — Visual workflow (Backlog → Ready → In Progress → In Review → QA → Done)
- **Release Notes** — Summary of changes, migration steps, known issues
- **Retrospective Notes & Action Items** — Learnings and improvements for the next cycle

## Questions?

If you need clarification on any process or want to suggest improvements, refer to the [Issue Template for Process Doc Updates](./.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose changes or additions to this documentation.
