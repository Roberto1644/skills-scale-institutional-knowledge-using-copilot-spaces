# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documents: concise, practical guidance for how we initiate, plan, execute, and improve cross-functional projects. Use this README as the single entry point to find the Project One-pager template, planning checklists, execution workflows, release guidance, risk management templates, and retrospective practices.

OctoAcme runs projects iteratively through a simple lifecycle: Initiation → Planning → Execution → Release → Retrospective. Projects begin with a one‑pager that captures problem statement, measurable success metrics, stakeholders, and a high‑level timeline. Teams move into planning once success metrics and stakeholders are aligned; planning outputs include a prioritized backlog with acceptance criteria, an agreed Definition of Done, and a release/milestone plan.

Execution emphasizes small, reviewable work (project board columns: Backlog → Ready → In Progress → In Review → QA → Done) and a pull request workflow that favors small PRs, linked issues, CI checks, and reviewer approvals. Quality practices include unit and integration tests, end-to-end smoke checks for critical flows, CI security scanning, and manual QA when needed. Release guidance distinguishes patch, minor, and major releases and includes pre-release checks, rollback plans, and post-deploy verifications.

Roles and communication are explicit: Product Managers define outcomes and success metrics, Project Managers coordinate delivery and risks, Developers implement and test, QA validates acceptance, and stakeholders provide inputs and approvals. Team cadence includes daily standups, weekly delivery syncs, sprint demos/reviews, a PM–PdM weekly alignment, and monthly stakeholder updates. Risks are tracked in a lightweight register and retrospectives convert top action items into backlog issues with owners and due dates.

Process documents in this folder:
- octoacme-project-management-overview.md
- octoacme-project-initiation.md
- octoacme-project-planning.md
- octoacme-execution-and-tracking.md
- octoacme-risks-and-communication.md
- octoacme-release-and-deployment.md
- octoacme-retrospective-and-continuous-improvement.md
- octoacme-roles-and-personas.md

How to propose changes
- Use the "Add Content to Project Management Process Docs" issue template (.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to request edits or additions.
- For small edits you can open a PR against the docs/ folder; for major changes, start with the issue template so stakeholders can review the proposal.
