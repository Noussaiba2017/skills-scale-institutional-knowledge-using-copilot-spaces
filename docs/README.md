# OctoAcme Project Management Documentation

## Welcome

This folder contains the complete project management process documentation for OctoAcme. Whether you're new to the team or need a quick reference, start here to understand how we run projects, coordinate teams, and deliver value to our customers.

## Quick Overview

OctoAcme operates under a structured project lifecycle that emphasizes customer value, iterative delivery, and clear ownership. Our approach is built on five core principles:

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments to gather feedback early
- **Clear ownership**: Each project has a named Project Manager and Product Lead responsible for success
- **Data-informed decisions**: Measure impact and iterate based on evidence and metrics
- **Psychological safety**: Encourage candid feedback and learning from both successes and failures

### Project Lifecycle

All OctoAcme projects flow through five distinct phases, each with dedicated processes and artifacts:

1. **Initiation** — Validate business need, align stakeholders, and create a lightweight Project One-pager
2. **Planning** — Break work into prioritized backlog items, estimate scope, and map dependencies
3. **Execution** — Build, test, and review work using a structured team rhythm and quality standards
4. **Release** — Deploy to production with risk mitigation, verification, and stakeholder communication
5. **Retrospective & Continuous Improvement** — Capture learnings and convert them into actionable improvements

### Key Roles

OctoAcme projects rely on clear role separation to ensure accountability and smooth collaboration:

- **Product Manager** — Defines what should be built, prioritizes the backlog, and measures outcomes
- **Project Manager** — Coordinates schedules, manages risks and dependencies, and maintains stakeholder alignment
- **Developers** — Implement features, write tests, and contribute to design and estimation
- **QA/Testing** — Validate quality and ensure acceptance criteria are met
- **Stakeholders** — Provide inputs, approvals, and strategic direction

### Quality & Execution

Quality is woven throughout execution. Our standards include:

- Unit tests for new logic and integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI pipelines
- Manual QA for feature acceptance when needed
- Standardized PR workflow with automated testing and code review

### Communication & Risk Management

We maintain regular communication cadences and proactive risk management:

- **Daily standups** (15 min) — Focus on progress, blockers, and dependencies
- **Weekly delivery syncs** — Show progress, review updates, and flag risks
- **Weekly PM/PdM alignment** — Coordinate strategy and resolve cross-functional issues
- **Monthly stakeholder updates** — Keep leadership informed of progress and status

Risks are tracked in a Risk Register throughout the project lifecycle and escalated through a clear path: team triage → PM escalation to Product Lead → sponsor-level escalation.

## Documentation Index

Use this index to find the documentation most relevant to your role or current project phase:

### Getting Started
- **[Project Management Overview](./octoacme-project-management-overview.md)** — Start here for a high-level introduction to OctoAcme's approach, roles, key artifacts, and communication cadence

### Phase-Specific Guides
- **[Project Initiation](./octoacme-project-initiation.md)** — How we define, scope, and validate new projects before planning
- **[Project Planning](./octoacme-project-planning.md)** — Strategies for breaking work into shippable increments, estimating, and mapping dependencies
- **[Execution and Tracking](./octoacme-execution-and-tracking.md)** — Daily execution practices, PR workflows, quality standards, and progress tracking
- **[Release and Deployment](./octoacme-release-and-deployment.md)** — Pre-release requirements, deployment checklists, rollback playbooks, and release notes

### Cross-Phase Topics
- **[Risks and Communication](./octoacme-risks-and-communication.md)** — Risk identification, management strategies, and stakeholder communication templates
- **[Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Running effective retrospectives and converting learnings into action items

### Reference
- **[Roles and Personas](./octoacme-roles-and-personas.md)** — Detailed definitions of core roles, responsibilities, goals, and communication patterns

## How to Use These Docs

- **For new team members**: Start with the [Project Management Overview](./octoacme-project-management-overview.md), then read the phase-specific guide for your current project stage
- **For Project Managers**: Reference the phase guides and Risk & Communication docs for checklists, templates, and escalation paths
- **For Product Managers**: Use the Initiation and Planning guides to structure discovery and backlog management
- **For Developers**: Review Execution and Tracking for PR workflows, quality standards, and sprint practices
- **For stakeholders**: The Overview and monthly status templates in Risks & Communication will keep you informed

## Integration with Copilot Spaces

These documentation files are integrated with Copilot Spaces to provide context-aware guidance. When working in a project space, Copilot can reference these docs to provide role-specific coaching and process guidance aligned with OctoAcme's standards.

---

**Last updated**: August 2026  
**Maintained by**: OctoAcme Project Management Community  
**Feedback or updates?** Create a new issue using the [Process Doc Update template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
