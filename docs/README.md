# OctoAcme Project Management Process Documentation

Welcome to OctoAcme's project management process library. This collection of documents guides how we plan, execute, and deliver projects across teams.

## Brief overview

OctoAcme runs projects with a structured, lifecycle-driven approach that moves work from a lightweight initiation into planning, disciplined execution, and formal release/retrospective steps. Initiation centers on a Project One-pager to capture problem, goals, success metrics, stakeholders and a high-level timeline; a decision gate (clear success metrics, stakeholder agreement, team availability) must be met before moving into planning. Planning breaks approved initiatives into shippable backlog items using a standard template (title, description, acceptance criteria, estimate, owner) and produces a release plan and Definition of Done. Teams use a project board (Backlog → Ready → In Progress → In Review → QA → Done) and follow an execution checklist (branching/PR conventions, CI, demos, weekly-updated risk register) to keep delivery predictable.

Roles and responsibilities are explicit: Project Managers coordinate delivery, schedules, risks and communications; Product Managers define outcomes, prioritize the backlog, and measure success; Developers implement and test features; QA validates acceptance criteria and supports manual testing when required; stakeholders provide inputs and approvals. Persona definitions are used consistently in artifacts and exercises so ownership, communication expectations, and handoffs are clear. The process emphasizes clear ownership for the Risk Register entries and maps escalation paths from team-level triage up through PM → Product Lead → Sponsor, with a special path for security incidents to the security runbook/on-call.

Communication is cadence-driven and lightweight: daily 15-minute standups to surface progress and blockers, a weekly delivery sync for progress and flagged risks, demo/review at the end of each sprint or milestone, and regular PM–PdM alignment (weekly) plus monthly stakeholder updates. Templates are recommended for weekly status updates and incident communications to keep messages consistent and single-source (project README or release doc). Blocker escalation levels are defined so critical, business-impacting issues receive sponsor-level attention and quicker remediation.

Quality assurance is integrated into the workflow: PRs are small when possible (<=400 lines), must reference issues and acceptance criteria, and require CI (tests, linting, security scans) before requesting review and at least one approval before merging. Testing discipline mandates unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows; manual QA is used for feature acceptance when needed. Pre-release requirements (passing CI/security scans, drafted release notes, rollback plan, smoke tests) and a deployment checklist govern releases, and a rollback/incident playbook guides response and post-incident retrospectives to capture action items and continuous improvements.

## Documentation Index

### Getting Started
- [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
- [OctoAcme Roles & Personas](octoacme-roles-and-personas.md)

### Project Phases
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)

### Cross-cutting Concerns
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## How to use these docs
1. New team members: Start with the Project Management Overview and Roles & Personas.
2. Starting a new project: Follow the Initiation Guide.
3. Planning work: Refer to Project Planning.
4. Executing and tracking: Use Execution & Tracking for daily workflows.
5. Preparing for release: Consult the Release & Deployment Guide.
6. Learning and improving: Follow Retrospective & Continuous Improvement.

## Key Artifacts
- Project One-pager / Charter
- Risk Register
- Backlog & Sprint Plans
- Project Board
- Release Notes
- Retrospective Notes

---

If you have questions or suggestions about these processes, please open an issue using the "Add Content to Project Management Process Docs" template.
