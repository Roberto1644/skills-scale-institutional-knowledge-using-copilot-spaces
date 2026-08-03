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

## Product Managers (PdM)

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

## Project Managers (PM)

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

## QA / Testing

### Role Summary
QA ensures features meet the Definition of Done and acceptance criteria through planned testing and verification activities.

### Responsibilities
- Define test cases and validation steps
- Execute manual and automated tests
- Report and verify bug fixes
- Collaborate with Developers to ensure testability

### Typical Communication
- QA sign-off in PRs
- Test results in CI and release notes

---

## Stakeholders

Provide inputs, approvals, and domain expertise as needed. Stakeholders may include business sponsors, legal, compliance, or partner teams.

---

## Additional operational roles (proposed additions)

### Release Manager
- Responsibilities:
  - Coordinate release windows and maintain the release calendar
  - Ensure all pre-release checks pass (CI, security, QA)
  - Author/curate release notes and stakeholder communications
  - Execute rollback/mitigation plans when needed
- Interactions:
  - Works with PM for scheduling, Developers and QA for verifications, Security Lead for scans, and Support/SRE for operational readiness
- Why it helps:
  - Centralizes release ownership and reduces ambiguity during deployments

### Technical Lead (Tech Lead)
- Responsibilities:
  - Provide technical direction and architecture leadership
  - Approve high-risk or high-impact design changes
  - Mentor developers and review complex PRs
- Interactions:
  - Advises PdM/PM on feasibility and estimates, collaborates with Developers and Security Lead on architecture and controls
- Why it helps:
  - Speeds technical decision-making and clarifies ownership for non-routine technical tradeoffs

### Security Lead
- Responsibilities:
  - Define security acceptance criteria and integration checks
  - Coordinate security scans and triage findings
  - Advise on remediation priority and secure design patterns
- Interactions:
  - Works with Developers on fixes, Release Manager on pre-release security checks, and PM/Product on risk decisions
- Why it helps:
  - Ensures security is surfaced early and consistently during planning and release

### Support / SRE Lead
- Responsibilities:
  - Own operational readiness, runbooks, on-call coordination, and incident triage
  - Ensure observability and run pre-deploy operational checks
- Interactions:
  - Coordinates with Developers for fixes, PM for stakeholder comms, Release Manager for deployment readiness, and Security Lead for incident handling if security-related
- Why it helps:
  - Improves production stability and accelerates incident response

### UX Researcher / Designer
- Responsibilities:
  - Validate UX assumptions, run user studies, and provide design specs
  - Define UX acceptance criteria and review user-facing changes
- Interactions:
  - Works closely with PdM on product decisions, Developers on implementation, and QA on acceptance tests
- Why it helps:
  - Ensures user needs and usability are explicitly represented in the process

---

## How to use these personas
- Add the role owner (name/alias) to the project README or charter.
- Where appropriate, add a one-line RACI (Responsible/Accountable/Consulted/Informed) for cross-team handoffs (e.g., Release: R=Release Manager, A=PM, C=Tech Lead, I=Stakeholders).
- For new projects, confirm which of these operational roles are assigned or are shared responsibilities.
