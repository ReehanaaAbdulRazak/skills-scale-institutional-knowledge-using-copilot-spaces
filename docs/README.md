# OctoAcme Project Management Docs

This README provides a concise summary of OctoAcme's project management processes and direct links to the detailed documents in the docs/ folder.

## OctoAcme Project Management Overview

OctoAcme follows a structured five-phase project lifecycle designed to balance customer value delivery with organizational clarity. Projects begin with **Initiation**, where a lightweight One-pager validates the business need, identifies stakeholders, and confirms go/no-go approval. Once approved, the **Planning** phase breaks work into shippable increments with prioritized backlogs, acceptance criteria, and risk registers. Teams then move into **Execution**, guided by daily standups, weekly delivery syncs, and a project board with columns for Backlog, Ready, In Progress, In Review, QA, and Done. Small pull requests (≤400 lines) are paired with automated CI testing and linting before requiring at least one approval. The **Release** phase applies standardized checklists—including smoke tests, rollback plans, and release notes—to minimize production risk. Finally, **Retrospectives** capture learnings and convert them into tracked action items, closing the loop on continuous improvement.

### Key Roles and Communication

OctoAcme defines clear ownership through four primary personas: **Developers** implement features to acceptance criteria and participate in design/code reviews; **Product Managers** own the vision, prioritize the backlog, and validate solutions through metrics; **Project Managers** coordinate schedules, manage risks, and facilitate communication; and **Stakeholders** provide inputs and approvals. Communication is structured around a predictable cadence—daily standups focus on progress and blockers, weekly PM-PdM syncs align strategy, twice-weekly delivery standups drive execution, and monthly stakeholder updates provide visibility. Risk escalation follows a three-level path: team-level triage in standups, PM escalation to Product Lead and dependent teams, and sponsor-level involvement for business-impacting issues.

### Quality Assurance and Risk Management

Quality and testing are embedded throughout execution: unit tests cover new logic, integration tests validate cross-component interactions, and end-to-end smoke tests protect critical flows before release. Security scanning runs in CI, and manual QA validates feature acceptance when needed. Velocity and burndown are tracked, alongside success metrics from the Project One-pager and key dashboards monitoring errors, latency, and usage. Risk management is continuous—risks are identified during planning and execution, assessed for impact and likelihood, and tracked in a shared register with mitigation plans and ownership. This combination of preventive quality practices, data-informed decision-making, and proactive risk monitoring ensures OctoAcme delivers reliable, measurable outcomes while maintaining transparency and psychological safety across teams.

## Documents

- **[octoacme-project-management-overview.md](./octoacme-project-management-overview.md)** — High-level overview: purpose, principles, roles, artifacts, lifecycle, and how to use these docs.
- **[octoacme-project-initiation.md](./octoacme-project-initiation.md)** — Project initiation guide: one-pager template, minimum deliverables, decision gate.
- **[octoacme-project-planning.md](./octoacme-project-planning.md)** — Project planning: backlog template, planning activities, risk & dependency management.
- **[octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md)** — Execution & tracking: team rhythm, workflows, quality/testing, reporting, and escalation.
- **[octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md)** — Release & deployment: release types, pre-release checks, deployment checklist, rollback playbook.
- **[octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md)** — Retrospectives: running retros, tracking improvements, action item template.
- **[octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md)** — Risks & communication: risk register, stakeholder comms, escalation paths.
- **[octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md)** — Personas: role summaries and responsibilities used in exercises.

## How to Contribute

Use the "[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)" issue template to propose new docs or updates. For new documents, select the appropriate option in the template dropdown and paste the proposed content.

## License & Ownership

Maintained by the OctoAcme project maintainers. Keep process docs up to date and lightweight; propose improvements via PRs or the issue template.
