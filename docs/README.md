# OctoAcme Project Management Documentation

Welcome to OctoAcme's centralized project management process documentation. This README provides an overview of how OctoAcme runs projects and links to detailed guidance for each phase.

## Overview

OctoAcme follows a **customer-first, iterative delivery approach** grounded in clear ownership, data-informed decisions, and psychological safety. All projects move through five core phases: **Initiation → Planning → Execution & Tracking → Release & Deployment → Retrospective & Continuous Improvement**.

### Key Principles
- **Customer-first**: Prioritize customer value and usability in all decisions.
- **Iterative delivery**: Deliver small, testable increments rather than big-bang releases.
- **Clear ownership**: Every project has named Project Manager and Product Manager roles.
- **Data-informed**: Measure impact and iterate based on evidence.
- **Psychological safety**: Encourage feedback, learning, and continuous improvement.

### How OctoAcme Manages Projects

OctoAcme's project management process is lifecycle-based and emphasizes transparency and collaboration across all phases. During **Initiation**, teams validate business needs and align stakeholders around a lightweight Project One-pager that captures the problem statement, success metrics, and resource needs. Once approved, the **Planning** phase breaks work into prioritized, estimated backlog items with clear acceptance criteria and a Definition of Done. **Execution** involves daily standups, sprint-based iterations, and continuous progress tracking using GitHub Projects boards with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done).

Quality and testing are embedded throughout execution rather than treated as an afterthought. Teams write unit and integration tests for new logic, run automated linting and security scans in CI, and conduct end-to-end smoke tests before release. Pull requests are kept small (≤ 400 lines when possible), require at least one approval, and must link to related issues. By the time work reaches the **Release** phase, quality gates have already been met, reducing deployment risk and enabling confidence in production deployments.

Throughout all phases, risk management and stakeholder communication are woven in. Risks are captured in a register and escalated through a three-level hierarchy (team-level, PM-level, sponsor-level) as needed. Weekly syncs between PM and Product Manager, twice-weekly delivery standups, and monthly stakeholder updates maintain alignment. Finally, OctoAcme emphasizes **continuous improvement** through structured retrospectives held after sprints, releases, or milestones. Retrospectives capture what went well, what could improve, and prioritize 2–3 actionable items with clear owners and due dates. These improvements feed back into the backlog or process documentation, creating a learning cycle that strengthens the organization over time.

## Documentation by Lifecycle Phase

### 📋 Project Initiation
- [Project Initiation Guide](./octoacme-project-initiation.md) — Validate business need, align stakeholders, confirm decision gates, and create a lightweight plan.
- **Use when**: A new project idea or feature proposal is ready to be explored.
- **Deliverables**: Project One-pager, Stakeholder list, High-level timeline, Risk list, Resource needs.

### 📐 Project Planning
- [Project Planning](./octoacme-project-planning.md) — Break work into shippable increments, identify dependencies, align timelines, and define Definition of Done.
- **Use when**: A project has been approved and is ready to move into detailed planning.
- **Deliverables**: Prioritized backlog, Estimated scope, Release plan, Risk & Dependency register, Test plan.

### 🚀 Execution & Tracking
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Manage day-to-day execution, quality standards, progress tracking, and blocker escalation.
- **Use when**: The project is in active development and delivery.
- **Key practices**: Daily standups, Weekly delivery syncs, Small PRs with automated testing, Regular demos, Risk register updates.

### 📤 Release & Deployment
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardize releases, reduce risk, improve observability, and execute deployments with confidence.
- **Use when**: Features are ready for production release.
- **Key practices**: Pre-release checklist, Smoke tests, Rollback plans, Release notes, Post-deploy verification.

### 🔄 Retrospective & Continuous Improvement
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings, identify action items, and convert insights into actionable improvements.
- **Use when**: After each sprint, release, or important milestone.
- **Cadence**: 45–75 minute retrospectives; track action items in project backlog.

## Cross-Cutting Guidance

- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction to roles, artifacts, communication cadence, and lifecycle.
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identify, manage, escalate, and communicate risks and dependencies across phases.
- [OctoAcme Personas](./octoacme-roles-and-personas.md) — Detailed definitions of key roles and responsibilities.

## Key Roles at a Glance

| Role | Primary Responsibility | Key Activities |
|------|------------------------|-----------------|
| **Project Manager (PM)** | Coordinate delivery, manage schedules, risks, and communications | Create/maintain plans, facilitate meetings, escalate blockers, report status |
| **Product Manager (PdM)** | Define outcomes, prioritize backlog, measure success | Define acceptance criteria, validate solutions, measure impact |
| **Developers** | Implement features, maintain code quality, collaborate on design | Write code/tests, participate in reviews, estimate work, identify risks |
| **QA/Testing** | Validate quality and acceptance criteria | Test features, identify bugs, verify acceptance criteria, smoke tests |
| **Stakeholders** | Provide inputs and approvals | Participate in reviews, make decisions, provide feedback |

For detailed role descriptions, see [OctoAcme Personas](./octoacme-roles-and-personas.md).

## Communication Cadence

- **Daily**: Team standups (15 min) — progress, blockers, dependencies
- **Twice-weekly**: Delivery team syncs
- **Weekly**: PM ↔ PdM alignment; Status updates to stakeholders
- **Monthly**: Stakeholder briefings and roadmap updates
- **Ad-hoc**: Escalations, incident response, risk updates

## Quick Start for New Team Members

1. **Start here**: Read the [Project Management Overview](./octoacme-project-management-overview.md) to understand core concepts and roles.
2. **Then navigate by phase**: Follow the phase-specific guides as your project progresses.
3. **Reference as needed**: Use cross-cutting guidance on risk management and communication throughout.
4. **Check your role**: Refer to [OctoAcme Personas](./octoacme-roles-and-personas.md) to understand your specific responsibilities.

## Key Artifacts

All OctoAcme projects maintain the following artifacts in their repository:

- **Project Charter / One-pager** — Problem, Goal, Success Metrics, Stakeholders, Timeline
- **Roadmap and Release Plan** — Phased delivery of features and milestones
- **Sprint/Iteration Backlog** — Prioritized, estimated work with acceptance criteria
- **Definition of Done** — Quality and testing standards for all deliverables
- **Risk Register** — Identified risks with impact, likelihood, mitigation, and status
- **Retrospective Notes** — Learnings, action items, and improvements from each cycle

## How to Use These Docs

- **Keep process docs updated**: When you identify a gap, improvement, or best practice, open an issue to update the relevant process doc using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
- **Reference in projects**: Link to these docs from your project repository, charter, or README.
- **Copilot Spaces context**: These docs can be added to Copilot Spaces for context-specific guidance on project management.

## Questions or Feedback?

If you have questions about OctoAcme's project management approach or want to suggest improvements, please:

1. Open an issue using the [Process Doc Update template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).
2. Tag the relevant PM or Product Manager for discussion.
3. Include any gaps you've identified or best practices you'd like to share.

---

*Last updated: 2026-07-24*
