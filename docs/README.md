# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management process library. This `docs/` folder is the authoritative source for the team's project management guidance and provides a clear starting point for running successful, cross-functional projects from initiation through close.

## Quick Start

OctoAcme projects follow a five-phase lifecycle:
1. **Initiation** — Validate business need, align stakeholders
2. **Planning** — Define scope, resources, milestones, dependencies
3. **Execution** — Build, test, and deliver iteratively
4. **Release** — Deploy to production and verify
5. **Close & Retrospective** — Capture learnings and improvements

## Documentation Index

### Core Guides
- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme principles, roles, and artifacts
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Definitions of Project Manager, Product Manager, Developer, and QA responsibilities

### Phase-Based Guides
- **[Project Initiation](octoacme-project-initiation.md)** — Steps to validate ideas and launch new projects
- **[Project Planning](octoacme-project-planning.md)** — Creating backlogs, estimating work, and defining release timelines
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day delivery, quality standards, and risk escalation
- **[Release & Deployment](octoacme-release-and-deployment.md)** — Pre-release checks, deployment procedures, and rollback playbooks
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capturing learnings and iterating on processes

### Supporting Guides
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Managing risks, dependencies, and stakeholder communication

## OctoAcme Project Management Overview

OctoAcme operates on a structured yet iterative project lifecycle designed to deliver customer value while maintaining clear ownership and data-driven decision-making. The framework encompasses five key phases—Initiation, Planning, Execution, Release, and Retrospective—supported by three primary roles: Project Managers (PMs) who coordinate delivery and timelines; Product Managers (PdMs) who define outcomes and measure success; and Developers who implement features while collaborating on design and quality. The organization prioritizes psychological safety, iterative delivery of small testable increments, and evidence-based improvements, with all projects grounded in a lightweight Project Charter that captures problem statements, success metrics, stakeholders, and initial resource needs.

### Workflows & Communication Cadence

Execution follows a structured rhythm anchored by daily standups (15 minutes), weekly delivery syncs, and sprint-based planning cycles. Teams use GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) and enforce small pull requests (≤400 lines) that include issue links and acceptance criteria before merging. Dependencies and risks are tracked in a Risk Register and escalated through a three-level structure: team-level triage in standups, PM escalation to Product Leads and dependent teams, and sponsor-level escalation for business-impacting issues. Regular stakeholder updates, weekly PM-PdM syncs, and ad-hoc incident communications keep all parties informed and aligned.

### Quality Assurance & Release Management

Quality is embedded throughout the delivery cycle with unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and security scanning in CI pipelines. Manual QA validates feature acceptance when needed, and all work must meet a documented Definition of Done before progression. Release management is standardized across patch, minor, and major releases, with pre-release requirements including passing CI/security scans, drafted release notes, and documented rollback plans. Post-deployment verification and stakeholder announcements formalize the handoff to production, while a blameless retrospective process captures learnings after each sprint, release, or milestone to drive continuous improvement through prioritized action items.

## Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named PM and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Core Roles

- **Project Manager (PM)**: Coordinates delivery, timelines, risk management, and stakeholder communication
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success
- **Developers**: Build solutions, collaborate on implementation details, and maintain engineering quality
- **QA/Testing**: Validates acceptance criteria and supports release readiness
- **Stakeholders**: Provide business context, approvals, and ongoing feedback

## Quick Reference

- **New to OctoAcme project delivery?** Start with the [Project Management Overview](octoacme-project-management-overview.md), then review [Roles & Personas](octoacme-roles-and-personas.md).
- **Starting a new project?** Use [Project Initiation](octoacme-project-initiation.md) to define the problem, stakeholders, and initial success measures.
- **Preparing the delivery plan?** Follow [Project Planning](octoacme-project-planning.md) for scope, sequencing, estimation, and milestone setup.
- **Running day-to-day execution?** Use [Execution & Tracking](octoacme-execution-and-tracking.md) alongside [Risk Management & Communication](octoacme-risks-and-communication.md).
- **Getting ready to ship?** Review [Release & Deployment](octoacme-release-and-deployment.md) for release checks, deployment, and rollback planning.
- **Closing a project or sprint?** Capture learnings in [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).

## Getting Help

- New to OctoAcme? Start with the [Project Management Overview](octoacme-project-management-overview.md)
- Starting a new project? Follow the [Project Initiation](octoacme-project-initiation.md) guide
- Questions about roles? See [Roles & Personas](octoacme-roles-and-personas.md)
- Need to update these docs? Use the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template
