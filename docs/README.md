# OctoAcme Project Management Process Documentation

## Welcome

This directory contains the complete OctoAcme project management processes and frameworks. Use this guide to navigate to the right document for your current phase or challenge.

## Our Approach

OctoAcme follows a structured lifecycle approach to project delivery that spans five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. The initiation phase validates business need and stakeholder alignment through a lightweight Project One-pager template, while the planning phase breaks approved work into shippable increments with prioritized backlogs, clear acceptance criteria, and documented dependencies. This foundation ensures teams move into execution with clarity on scope, success metrics, and risk mitigations before code is written.

The organization relies on three core roles to drive delivery: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define outcomes, prioritize the backlog, and measure success; and **Developers** implement features while collaborating on design, testing, and risk identification. This clear ownership model is reinforced through a regular communication cadence—daily standups (15 min), weekly delivery syncs, weekly PM/PdM alignment, and monthly stakeholder updates—ensuring transparency and rapid issue escalation across team levels when needed.

Execution emphasizes quality and iterative delivery through small pull requests (≤400 lines), automated CI testing and linting, security scanning, and manual QA for feature acceptance. Work flows through a project board with standard columns (Backlog, Ready, In Progress, In Review, QA, Done), while a Risk Register tracks emerging issues by ID, impact, likelihood, and mitigation strategy, reviewed weekly to catch blockers early. The team rhythm includes demos at sprint end and a structured escalation path (team → PM → Product Lead → Sponsor) for critical issues.

Finally, OctoAcme embeds learning into every release and milestone through **Retrospectives & Continuous Improvement**—timeboxed sessions (45–75 min) that capture what went well, identify improvements, and convert findings into prioritized action items with clear owners and due dates. This cycle of delivery, measurement, and reflection (supported by velocity tracking, burndown, and key success metrics from the project charter) enables the organization to scale institutional knowledge, reduce single-person dependency risk, and continuously refine its processes based on real-world execution insights.

## Core Principles

OctoAcme's project management approach is grounded in these key principles:

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Ship small, testable increments
- **Clear ownership**: Named roles with clear accountability
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and continuous learning

## Core Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

## Documentation Map

### Getting Started

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, roles, and key artifacts
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Detailed descriptions of team roles and responsibilities

### Project Lifecycle

#### Initiation Phase

- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Validate business need, align stakeholders, create lightweight project plan. Use when a new project idea or feature proposal is ready to be explored.

#### Planning Phase

- **[Project Planning](./octoacme-project-planning.md)** — Break work into shippable increments, identify dependencies, create backlog, and establish release timelines.

#### Execution Phase

- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Day-to-day execution, team rhythm, quality standards, progress tracking, and blocker escalation.
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify and manage risks, escalation paths, stakeholder communication, and incident handling.

#### Release Phase

- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Pre-release requirements, deployment checklist, rollback procedures, and release notes.

#### Closure Phase

- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings, convert insights into action items, and drive continuous process improvement.

## Quick Reference

**I'm starting a new project**
→ Start with [Project Initiation Guide](./octoacme-project-initiation.md)

**I need to break down work and create a plan**
→ See [Project Planning](./octoacme-project-planning.md)

**I need to track daily progress**
→ Check [Execution & Tracking](./octoacme-execution-and-tracking.md)

**I have a blocker or risk**
→ Refer to [Risk Management & Communication](./octoacme-risks-and-communication.md)

**I'm preparing a release**
→ Follow [Release & Deployment Guide](./octoacme-release-and-deployment.md)

**I want to learn from this project**
→ See [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

**I need to understand team roles**
→ Review [Roles & Personas](./octoacme-roles-and-personas.md)

## How to Use This Documentation

- Keep the Project Charter updated in the project repo
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context
- Reference relevant checklists and templates throughout your project lifecycle
- Contribute improvements and updates via process doc update issues

## Contributing Updates

Have feedback or spotted a gap? Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose updates or new content.
