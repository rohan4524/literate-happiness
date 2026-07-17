# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Docs. This repository contains our standardized processes, roles, and best practices for delivering projects successfully.

## Quick Start

New to OctoAcme? Start with the [Project Management Overview](#project-management-overview) for a high-level introduction to our approach, core roles, and key artifacts.

---

## Project Management Overview

OctoAcme uses a structured, customer-centric approach to project management built on these core principles:

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments to gather feedback early
- **Clear ownership**: Each project has named Project Manager and Product Lead roles
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and blameless retrospectives

### Core Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

### Project Lifecycle (High-Level)

1. **Initiation**: Problem statement, stakeholders, high-level timeline
2. **Planning**: Scope, resources, milestones, dependencies
3. **Execution**: Build, test, review, iterate
4. **Release**: Deploy, verify, announce
5. **Close & Retrospective**: Capture learnings and next steps

### Key Artifacts

- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

### Communication Cadence

- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

---

## Documentation by Project Phase

### 1. Initiation

Define the initial steps to validate and authorize work, align stakeholders, and create a lightweight plan.

📖 **[Project Initiation Guide](./octoacme-project-initiation.md)**
- Confirm business need and measurable outcome
- Identify stakeholders & champions
- Define success criteria and initial timeline
- Decide go/no-go for planning
- Use the Project One-pager template

**Key Deliverable**: Completed one-pager and stakeholder alignment

---

### 2. Planning

Turn an approved initiative into an actionable plan and backlog for delivery.

📖 **[Project Planning](./octoacme-project-planning.md)**
- Break work into shippable increments
- Identify dependencies and risks
- Align timelines, releases, and responsibilities
- Create prioritized backlog with acceptance criteria
- Define Definition of Done (DoD)

**Key Deliverable**: Prioritized backlog and release plan

---

### 3. Execution

Manage day-to-day execution and track progress toward project milestones.

📖 **[Execution & Tracking](./octoacme-execution-and-tracking.md)**
- Team rhythm: daily standups, weekly delivery syncs, demos/reviews
- Project board workflows with standard columns
- Pull Request best practices (small PRs, linked issues, automated tests)
- Quality & Testing standards (unit, integration, E2E, security)
- Blocker escalation framework

**Key Deliverable**: Consistent progress tracking and quality maintenance

---

### 4. Release

Standardize how OctoAcme releases features to production to reduce risk and improve observability.

📖 **[Release & Deployment Guide](./octoacme-release-and-deployment.md)**
- Release types: Patch, Minor, Major
- Pre-release requirements (acceptance criteria met, CI passing, security scans)
- Deployment checklist (staging, production, verification)
- Rollback & incident playbook
- Release notes template

**Key Deliverable**: Documented, safe, and verifiable release process

---

### 5. Retrospective

Capture learnings and convert them into actionable improvements.

📖 **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)**
- Run after each sprint, release, or important milestone
- Structure: What went well, what could be improved, action items
- Timebox: 45–75 minutes
- Track improvements with owners and due dates
- Measure impact and celebrate progress

**Key Deliverable**: Action items and documented learnings

---

## Cross-Cutting Processes

### Risk Management & Communication

Identify, manage, and communicate risks and dependencies throughout the project.

📖 **[Risk Management & Communication](./octoacme-risks-and-communication.md)**
- Risk Register: ID, Description, Impact, Likelihood, Owner, Mitigation
- Risk Lifecycle: Identify → Assess → Mitigate → Monitor
- Stakeholder Communication templates
- Escalation paths (Team → PM → Product Lead → Sponsor)
- Incident communication and post-incident retrospectives

**Key Deliverable**: Active risk register and clear communication plan

---

### Roles & Personas

Detailed definitions of key roles and responsibilities used in OctoAcme projects.

📖 **[Roles & Personas](./octoacme-roles-and-personas.md)**
- Developer: Design, build, test, deliver reliable code
- Product Manager: Define outcomes, prioritize backlog, measure success
- Project Manager: Coordinate delivery, manage schedules, risks, communications
- Typical communications and goals for each role

**Key Deliverable**: Shared understanding of role expectations

---

## Quick Reference: Key Artifacts & Templates

| Artifact | Purpose | Created During |
|----------|---------|-----------------|
| Project One-pager | Problem, Goal, Success Metrics | Initiation |
| Backlog Item Template | Standardized ticket format | Planning |
| Definition of Done | Acceptance criteria for "Done" | Planning |
| Risk Register | Track and monitor risks | Planning & Ongoing |
| Release Plan | Milestone and release roadmap | Planning |
| Weekly Status Template | Progress, next steps, risks, decisions | Execution |
| Retrospective Notes | Learnings and action items | Retrospective |
| Release Notes | Changes, migrations, known issues | Release |

---

## How to Use These Docs

### For New Team Members
1. Read the **Project Management Overview** section above
2. Review **[octoacme-project-management-overview.md](./octoacme-project-management-overview.md)** for details
3. As you join a project, review the relevant phase documents (Initiation → Planning → Execution, etc.)
4. Refer to **[Roles & Personas](./octoacme-roles-and-personas.md)** to understand your responsibilities

### For Project Managers
- Keep the Project One-pager updated in your project repository
- Reference the **Risk Management & Communication** guide for escalation and status updates
- Use the **Retrospective** guide to facilitate team learning

### For Product Managers
- Use the **Project Planning** guide to create and prioritize the backlog
- Define success metrics as outlined in **Project Initiation**
- Reference the **Execution & Tracking** guide for team rhythm

### For Developers
- Follow **Execution & Tracking** for PR workflows and quality standards
- Participate in planning activities outlined in **Project Planning**
- Contribute to retrospectives for continuous improvement

### For Copilot Spaces Users
- Add process-specific docs to `.copilot/` if you want Copilot Spaces to reference them as context
- Use these documents to ground Copilot Spaces knowledge in OctoAcme processes

---

## Document Index (Complete List)

- [octoacme-project-management-overview.md](./octoacme-project-management-overview.md)
- [octoacme-project-initiation.md](./octoacme-project-initiation.md)
- [octoacme-project-planning.md](./octoacme-project-planning.md)
- [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md)
- [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md)
- [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md)
- [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md)
- [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md)

---

## Need Help?

- **Lost?** Start with the [Project Management Overview](./octoacme-project-management-overview.md)
- **Planning a project?** Follow the phases from Initiation → Planning → Execution → Release
- **Stuck on a process?** Check the relevant phase document or cross-cutting guide
- **Contributing improvements?** Use the [Add Content to Project Management Process Docs](./../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template

---

**Last Updated**: 2026-07-17

For questions or updates to this documentation, please open an issue or contact the Project Management Office.
