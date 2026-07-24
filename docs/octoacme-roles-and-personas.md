# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Technical Program Manager (TPM)

### Role Summary
Coordinates technical dependencies and cross-team delivery for large, multi-team initiatives.

### Responsibilities
- Track cross-team milestones and dependencies
- Facilitate technical coordination meetings and decision logs
- Surface and triage technical risks to PM and PdM
- Help decompose large initiatives into coordinated deliverables

### Interactions
- Works closely with PM, PdM, Engineering Managers, Architects, and Release Manager to unblock technical work and escalate blockers

---

## UX Researcher / Designer

### Role Summary
Owns user research, synthesizes findings, and ensures designs align with user needs.

### Responsibilities
- Plan and run user research and usability studies
- Produce personas, journeys, and design artifacts
- Validate acceptance criteria against user needs
- Provide implementation guidance and design reviews

### Interactions
- Collaborates with PdM, Developers, and QA to ensure usability requirements are clear and tested

---

## Security Engineer / Reviewer

### Role Summary
Ensures features meet organizational security standards and threat models.

### Responsibilities
- Perform threat modeling and security reviews of designs and PRs
- Recommend mitigations and security controls
- Approve security-related changes before production
- Maintain a known list of security requirements for projects

### Interactions
- Works with Developers, DevOps, PM, and legal/security teams to integrate security requirements into backlog and release decisions

---

## Platform / DevOps Engineer

### Role Summary
Owns infrastructure, CI/CD pipelines, and production operability.

### Responsibilities
- Maintain deployment pipelines and automation
- Support staging and production environments
- Own rollback/runbook content and production runbooks
- Assist with performance and scaling guidance

### Interactions
- Partners with Developers and Release Manager during deploys and incident response

---

## Release Manager

### Role Summary
Coordinates releases across teams and enforces pre-release criteria.

### Responsibilities
- Validate release checklists and pre-release gates
- Schedule release windows and coordinate stakeholders
- Coordinate smoke tests and post-release verifications
- Maintain release notes and communication plans

### Interactions
- Works with PM, TPM, DevOps, Customer Support, and Observability teams to ensure smooth rollouts

---

## Data Analyst / Data Engineer

### Role Summary
Owns metrics instrumentation, data validation, and reporting for feature success.

### Responsibilities
- Define telemetry and metrics required for success metrics
- Validate data quality and instrumentation
- Create dashboards and reports for stakeholders
- Support experimentation analysis and metric definition

### Interactions
- Collaborates with PdM and Developers to ensure telemetry is implemented and dashboards reflect success metrics

---

## Customer Success / Support Liaison

### Role Summary
Represents customer operational concerns and feedback.

### Responsibilities
- Surface customer issues and patterns to the team
- Validate operational readiness and support documentation
- Coordinate rollout communications and support runbooks

### Interactions
- Works with PM and Release Manager to ensure support readiness and post-release monitoring

---

## Accessibility Specialist

### Role Summary
Ensures product accessibility standards are met.

### Responsibilities
- Conduct accessibility reviews and audits
- Provide remediation guidance and acceptance criteria
- Validate accessibility fixes during QA and release

### Interactions
- Partners with Developers, QA, and Designers to incorporate accessibility requirements

---

## Observability / SRE Specialist

### Role Summary
Ensures systems are observable and runbook-ready.

### Responsibilities
- Define and validate metrics, alerts, and dashboards
- Own incident detection instrumentation and playbooks
- Ensure runbooks and on-call handoffs are documented

### Interactions
- Works with DevOps, Developers, and PM to ensure runbooks and alerts are adequate for releases

---

## Compliance / Privacy Officer

### Role Summary
Ensures features comply with regulatory and privacy requirements.

### Responsibilities
- Review data flows and privacy impacts
- Approve data retention and access policies
- Recommend mitigation for compliance risks

### Interactions
- Escalates to PM, legal, and stakeholder groups as needed

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
