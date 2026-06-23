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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas and Role Interactions

To address gaps in cross-functional ownership, release readiness, documentation stewardship, and onboarding, the following personas are proposed. Each persona includes responsibilities and how they interact with existing core roles.

### 1) Release Coordinator
- Responsibilities:
  - Own the release schedule and calendar for the project.
  - Maintain release checklists (pre-, during-, post-release).
  - Coordinate cutover tasks, verify release readiness (smoke tests, rollback plans).
  - Communicate release windows and stakeholder expectations.
- Interactions:
  - Works with Project Manager for timing and risk alignment.
  - Coordinates with Tech Lead and DevOps Integrator for deployment readiness.
  - Obtains test sign-off from QA Liaison.
  - Partners with Documentation Owner for release notes and stakeholder comms.

### 2) Documentation Owner
- Responsibilities:
  - Maintain process and product documentation under docs/.
  - Ensure documents are versioned, discoverable, and reviewed.
  - Run documentation review cycles and track outstanding doc work.
- Interactions:
  - Collaborates with Process Steward and SMEs for content accuracy.
  - Works with Onboarding Champion to ensure materials meet new-hire needs.
  - Receives updates from Project Manager about process changes.

### 3) Process Steward
- Responsibilities:
  - Act as custodian for project management processes and templates.
  - Propose process improvements, measure adoption, and curate retrospectives focused on process health.
  - Maintain or propose updates to templates stored in docs/.
- Interactions:
  - Escalates recommended changes to Project Manager and leadership.
  - Works with Documentation Owner to implement doc updates.
  - Coordinates with Onboarding Champion to incorporate process changes into onboarding flows.

### 4) QA Liaison
- Responsibilities:
  - Serve as single point-of-contact for quality criteria and test strategy.
  - Coordinate regression planning, test coverage reviews, and sign-offs for releases.
  - Ensure test artifacts and results are available and discoverable.
- Interactions:
  - Coordinates gating decisions with Release Coordinator and Project Manager.
  - Works with Developers and Tech Lead to triage quality issues.

### 5) DevOps Integrator
- Responsibilities:
  - Maintain and standardize CI/CD pipelines and deployment runbooks relevant to the project.
  - Validate automated deployments and rollback procedures.
  - Keep infra-related docs up to date for incident response.
- Interactions:
  - Works closely with Tech Lead and Release Coordinator for deployment automation.
  - Supports QA Liaison with environment provisioning and test automation integrations.

### 6) Stakeholder Liaison
- Responsibilities:
  - Represent external stakeholder needs (operations, legal, compliance, customer representatives).
  - Gather and clarify stakeholder constraints and acceptance criteria.
  - Maintain stakeholder communication cadence for major milestones.
- Interactions:
  - Escalates constraints and needs to Product Manager and Project Manager.
  - Works with Release Coordinator on stakeholder-facing release notifications.

### 7) Onboarding Champion
- Responsibilities:
  - Maintain and own role-specific onboarding checklists and newcomer documentation.
  - Track onboarding completion and identify onboarding gaps.
  - Coordinate environment access needs and first-week task lists.
- Interactions:
  - Collaborates with Documentation Owner and Process Steward to keep onboarding content current.
  - Coordinates with Tech Lead for environment and tooling access.

### Role Interaction Matrix (summary)
| Persona / Core Role | Project Manager | Product Manager | Tech Lead | Documentation Owner |
|---|---:|---:|---:|---:|
| Release Coordinator | Schedule & risk | Inform release impact | Deploy readiness | Release notes |
| QA Liaison | Gate releases | Clarify acceptance | Test integration | Test artifacts |
| DevOps Integrator | Deployment runbooks | N/A | Pipeline ownership | Runbook docs |
| Documentation Owner | Update process docs | Update product docs | Doc for designs | Maintain docs |
| Process Steward | Propose process changes | Align on policies | Advises on technical process | Coordinates updates |
| Stakeholder Liaison | Communicates constraints | Represents customers | N/A | N/A |
| Onboarding Champion | Tracks onboarding | N/A | Grants access | Maintains onboarding docs |

These additions clarify ownership for cross-functional activities, reduce single-person risks, and make it straightforward to find who owns recurring tasks (releases, documentation, onboarding).
