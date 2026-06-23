# OctoAcme Project Management Docs

This README is the central entry point for OctoAcme's project management processes. It summarizes the team's lifecycle, key workflows, roles, communication cadence, and quality assurance practices, and links to the full process documents stored in this folder.

OctoAcme follows a clear lifecycle from Initiation → Planning → Execution → Release → Retrospective. Initiation begins with a lightweight Project One‑pager capturing the problem, goals, success metrics, stakeholders, and a high‑level timeline. Planning turns approved initiatives into a prioritized backlog with acceptance criteria, estimates, a Definition of Done, and a release plan. A simple risk register is maintained and reviewed regularly to surface dependencies and mitigation actions.

Work is executed using a project board with columns like Backlog, Ready, In Progress, In Review, QA, and Done. The team follows a disciplined pull request workflow (small PRs when possible, link PRs to issues with acceptance criteria, and require CI to pass before review). The project emphasizes CI-backed quality checks (unit, integration, and security scans), manual QA for acceptance when needed, and pre-release smoke tests and rollback plans to reduce risk during deployments.

Roles and communication are explicit: Project Managers coordinate delivery and risk; Product Managers own outcomes and prioritization; Developers implement and test; QA validates acceptance. Team cadence includes daily standups, weekly delivery syncs, demos at the end of sprints/milestones, weekly PM–PdM syncs, and monthly stakeholder updates. Retrospectives after key milestones convert learnings into tracked action items that are added to the backlog for continuous improvement.

## Documents
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## How to use
- Link this README from the project repository README and from any .copilot/ index so Copilot Spaces can discover it.
- Request additions or updates using the "Add Content to Project Management Process Docs" issue template (.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).
- Keep the one-pager, risk register, and release notes up to date in the project repo to serve as the single source of truth.

## Acceptance Criteria
- [x] Content aligns with existing process docs
- [x] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with stakeholders (if needed)
