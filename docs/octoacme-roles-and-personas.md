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

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality assurance strategy, acceptance testing, and test coverage for the project. They collaborate with product and development to define testability requirements and validate deliverables.

### Responsibilities
- Define test strategy and acceptance criteria validation approach
- Coordinate manual QA and acceptance testing for features
- Maintain test plans and coverage metrics
- Collaborate with developers on testability and edge cases
- Escalate quality blockers and track defect resolution

### Goals
- Ensure acceptance criteria are met before release
- Reduce production defects and rework
- Provide confidence in release readiness

### Typical Communication
- Acceptance testing status in daily standups
- QA reviews during sprint planning
- Test report and coverage metrics in weekly syncs

### Interaction with Existing Roles
QA/Testing Leads work closely with **Developers** to define testability requirements early in development, collaborate with **Product Managers** to validate acceptance criteria, and support **Project Managers** in release readiness assessments. They escalate quality blockers to **Project Managers** for prioritization.

---

## Security/Compliance Officer

### Role Summary
Security/Compliance Officers ensure projects meet security standards, manage vulnerability scanning, coordinate incident response, and ensure regulatory compliance.

### Responsibilities
- Configure and monitor security scanning in CI/CD
- Conduct security reviews for critical features
- Coordinate incident response and triage
- Provide guidance on compliance requirements
- Track and escalate security risks

### Goals
- Minimize production security incidents
- Maintain compliance with organizational and regulatory standards
- Enable secure delivery without blocking progress

### Typical Communication
- Security scan results in CI
- Security incident notifications and post-mortems
- Compliance reviews during planning phase

### Interaction with Existing Roles
Security/Compliance Officers partner with **Developers** on secure coding practices and vulnerability remediation, advise **Product Managers** on security trade-offs, and inform **Project Managers** of security-related risks and timelines. They coordinate with **DevOps/Infrastructure Engineers** on scanning tool configuration and production incident response.

---

## Stakeholder/Sponsor

### Role Summary
Sponsors and Stakeholders provide business context, strategic alignment, executive approvals, and escalation authority for projects. They represent customer, business, or organizational interests.

### Responsibilities
- Provide business context and success criteria
- Approve go/no-go decisions at key gates
- Escalate business-impacting risks and blockers
- Review progress and provide feedback
- Support resource allocation and priority alignment

### Goals
- Ensure projects align with business strategy
- Enable timely decision-making and escalation
- Maintain executive visibility and confidence

### Typical Communication
- Monthly stakeholder updates
- Project initiation approval
- Ad-hoc escalations for business-critical decisions

### Interaction with Existing Roles
Stakeholders/Sponsors engage with **Product Managers** to align on business priorities and roadmap, work with **Project Managers** for progress reviews and escalation authority, and provide context to **Developers** on business impact. They are key decision-makers for trade-offs involving schedule, scope, and resources.

---

## Product Lead / Head of Product

### Role Summary
Product Leads oversee cross-project product strategy, ensure alignment with company roadmap, and escalate complex trade-offs. They support Product Managers and coordinate between multiple initiatives.

### Responsibilities
- Align individual projects with company product strategy
- Escalate and resolve cross-project trade-offs and dependencies
- Mentor Product Managers
- Communicate product roadmap to stakeholders
- Review major project decisions and metrics

### Goals
- Maximize coherent product strategy and customer value
- Reduce cross-project friction and duplication
- Build a strong product management practice

### Typical Communication
- Weekly sync with PMs on strategy and trade-offs
- Monthly roadmap and stakeholder updates
- Ad-hoc escalations from individual projects

### Interaction with Existing Roles
Product Leads mentor and guide **Product Managers** on strategy and prioritization, escalate complex trade-offs involving multiple projects to **Stakeholders/Sponsors**, and work with **Project Managers** on cross-project dependencies. They provide strategic context to **Developers** and align product decisions across the organization.

---

## DevOps / Infrastructure Engineer

### Role Summary
DevOps Engineers design, maintain, and operate deployment pipelines, infrastructure, monitoring, and production systems. They enable reliable, observable, and secure releases.

### Responsibilities
- Design and implement CI/CD pipelines
- Manage staging and production infrastructure
- Configure monitoring, alerting, and observability
- Coordinate deployments and rollbacks
- Support incident response and post-mortems

### Goals
- Enable fast, safe, and automated deployments
- Maintain high system reliability and observability
- Reduce deployment risk and incident impact

### Typical Communication
- Deployment window coordination
- Infrastructure and pipeline updates in planning
- Incident response and post-mortem facilitation
- Monitoring dashboards and alerts shared with teams

### Interaction with Existing Roles
DevOps/Infrastructure Engineers collaborate with **Developers** on CI/CD optimization and deployment practices, support **Project Managers** with release coordination, and work with **Security/Compliance Officers** on security scanning and incident response. They provide **QA/Testing Leads** with staging environments and monitoring data.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
