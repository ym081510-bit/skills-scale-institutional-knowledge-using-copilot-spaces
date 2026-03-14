# OctoAcme Project Management Processes

This folder collects OctoAcme's core project/program management practices, checklists, and roles to promote shared understanding and consistent project execution.

## Summary of OctoAcme Project Management Processes

OctoAcme operates on these core principles:

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments rather than large releases
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning across the team

### Project Lifecycle

OctoAcme projects follow a structured lifecycle with five key phases:

1. **Initiation** → Validate business need, identify stakeholders, and confirm success metrics
2. **Planning** → Break work into shippable increments, define dependencies and timeline
3. **Execution & Tracking** → Build, test, review, and iterate with regular progress updates
4. **Release & Deployment** → Deploy to production with quality gates and monitoring
5. **Retrospective & Improvement** → Capture learnings and drive continuous improvements

### Key Roles

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and strategic guidance

### Communication Cadence

- **Weekly sync** between PM + PdM
- **Twice-weekly standups** for delivery team (or as agreed)
- **Monthly stakeholder updates**
- **Ad-hoc escalations** as needed

---

## Process Documentation Index

Explore detailed guidance for each phase and function:

### Core Processes

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme approach, principles, roles, and key artifacts
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps to validate ideas, align stakeholders, and authorize work
- **[Project Planning](./octoacme-project-planning.md)** — Turn approved initiatives into actionable plans and backlogs
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day delivery, quality, and progress tracking
- **[Release & Deployment](./octoacme-release-and-deployment.md)** — Standardize releases to production with safety and observability
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements

### Cross-Cutting Concerns

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks, dependencies, and escalations
- **[Roles and Personas](./octoacme-roles-and-personas.md)** — Detailed descriptions of typical roles, responsibilities, and communication patterns

---

## How to Use These Docs

### For Project Teams
1. Start with the **Project Management Overview** to understand the framework
2. Follow the **Project Initiation Guide** when kicking off new work
3. Use process-specific docs as you move through each lifecycle phase
4. Reference **Risk Management & Communication** throughout for escalations and updates

### For Onboarding
New team members should read:
1. **Project Management Overview** (10 min) — Core principles and roles
2. **Roles and Personas** (10 min) — Understand your role and peers
3. Specific process docs for your current project phase

### For Copilot Spaces
Add process-specific docs into `.copilot/` if you want Copilot Spaces to reference them as context. This ensures consistent, role-based guidance across your organization.

### For Continuous Improvement
- Updates to these docs are tracked in GitHub issues using the **"Add Content to Project Management Process Docs"** template
- Changes are reviewed for alignment and clarity before merging
- Action items from retrospectives often result in doc updates

---

## Quick Reference: Checklists

Each process document includes a detailed checklist. Here's a quick summary:

| Phase | Key Checkpoint |
|-------|---|
| **Initiation** | One-pager completed, stakeholders aligned, decision gate approved |
| **Planning** | Backlog prioritized, acceptance criteria clear, DoD documented, risks identified |
| **Execution** | CI configured, demos scheduled, risk register updated weekly |
| **Release** | Acceptance criteria met, CI passing, release notes drafted, smoke tests ready |
| **Retrospective** | 2–3 action items identified, owners and due dates assigned, improvements tracked |

---

## Contributing to These Docs

To propose updates or additions:

1. Review the existing documentation to identify gaps or improvements
2. Create an issue using the **"Add Content to Project Management Process Docs"** template (`.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`)
3. Include:
   - Which document(s) you're updating
   - Summary of new content
   - Rationale for the change
   - Suggested content (optional)
4. Wait for review and approval before merging

---

## Questions or Feedback?

If you have questions about OctoAcme processes or suggestions for improvement, please:
- Comment on relevant issues
- Reach out to your Project Manager or Product Lead
- Create a new issue for larger process improvements

Happy building! 🚀
