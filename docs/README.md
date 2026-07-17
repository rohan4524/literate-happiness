# OctoAcme Project Management Docs

This README indexes the OctoAcme project management process documents and provides a comprehensive summary of the processes and how to use them.

## Overview of OctoAcme Project Management Processes

OctoAcme follows a structured five-phase project lifecycle designed to balance agility with clarity: **Initiation, Planning, Execution, Release, and Retrospective**. Each phase is gated by clear decision points and minimum deliverables. During **Initiation**, teams validate business need, align stakeholders, and create a lightweight One-pager that captures the problem statement, success metrics, and resource needs. **Planning** transforms the approved initiative into a prioritized, estimated backlog with a defined release timeline and risk register. **Execution** is managed through daily standups (15 min), weekly delivery syncs, and a project board workflow that moves items through Backlog → Ready → In Progress → In Review → QA → Done. Pull requests are kept small (≤400 lines), include acceptance criteria, and require automated testing and at least one approval before merging. This iterative, increment-focused approach enables teams to ship testable features regularly while maintaining quality and catching risks early.

OctoAcme defines three core personas: **Developers** (design, build, test, and deliver software; write tests and participate in code reviews), **Product Managers** (define what to build, prioritize the backlog, and measure outcomes), and **Project Managers** (coordinate delivery, manage schedules, risks, and communications). Clear ownership is a key principle—each project has a named PM and Product Lead who work together in weekly syncs to track progress, blockers, and escalations. Communication is structured and frequent: daily standups focus on progress and blockers at the team level, twice-weekly delivery standups ensure alignment, and monthly stakeholder updates provide business-level visibility. Escalation follows a three-level path (Team → PM → Product Lead → Sponsor), ensuring blockers are addressed promptly without bypassing context.

Risk management is embedded throughout the project lifecycle, with a Risk Register maintained from planning through execution that tracks ID, Description, Impact, Likelihood, Owner, and Mitigation Plan. Risks are reviewed weekly during syncs and updated as mitigation actions progress. Quality is enforced through multiple layers: unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, and security scanning in CI. Manual QA validates feature acceptance when needed. Before any release, teams confirm all acceptance criteria are met, passing CI and security scans, release notes are drafted, and a rollback plan is documented—reducing risk and enabling faster, more confident deployments. OctoAcme closes the loop through structured retrospectives held after each sprint, release, or significant milestone, capturing learnings and converting them into prioritized action items that feed back into the project backlog.

## Quick Summary

- **Initiation** — Validate and authorize work (one-pager, stakeholders, go/no-go decision gate)
- **Planning** — Break approved work into a plan and backlog, estimate, and define Definition of Done
- **Execution & Tracking** — Day-to-day delivery, PR/CI conventions, checklists, and blocker escalation
- **Risks & Communication** — Maintain a risk register, stakeholder updates, and escalation paths
- **Release & Deployment** — Deployment checklist, rollback plan, and release notes
- **Retrospectives & Continuous Improvement** — Capture learnings and convert to action items
- **Roles & Personas** — Responsibilities for PM, PdM, developers, and QA

## Links to Process Docs

- [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) — Project management overview and lifecycle
- [octoacme-project-initiation.md](./octoacme-project-initiation.md) — Project initiation guide and one-pager template
- [octoacme-project-planning.md](./octoacme-project-planning.md) — Planning activities, backlog template, and checklists
- [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) — Execution rhythm, PR workflow, QA, and reporting
- [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) — Risk register, communication templates, and escalation
- [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) — Release types, deployment checklist, and rollback playbook
- [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) — Retrospective structure and tracking
- [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) — Role descriptions and responsibilities

## How to Use

- **Getting Started:** Start with this README and the [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) to understand the OctoAcme approach and core roles.
- **Finding Guidance:** Use the Quick Summary and Links section to navigate to the specific process document you need.
- **Proposing Updates:** For edits or additions to any process doc, use the ["Add Content to Project Management Process Docs"](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template and reference the specific document.
- **Keeping Docs Fresh:** Keep links and summaries up to date when process docs change. Assign updates to the relevant project owner.
