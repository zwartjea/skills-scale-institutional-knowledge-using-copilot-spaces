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

## QA / Testing

### Role Summary
QA/Testing verifies that deliverables meet acceptance criteria, functional requirements, and quality standards before release.

### Responsibilities
- Create and execute test cases (manual and automated)
- Report and validate defect resolution
- Maintain test environments and test data (where applicable)
- Contribute to test strategy and definition of done

### Typical Communication
- Test reports in PRs and release notes
- Coordination with Developers and QA leads for triage

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas (New — recommended)

The following personas are recommended additions to ensure clearer ownership and coverage of responsibilities across modern cross-functional teams. Each includes responsibilities and interaction notes to clarify handoffs and collaboration.

### User Researcher

- Role Summary:
  Designs and conducts user studies, gathers qualitative insights, and ensures user needs are central to project outcomes.

- Responsibilities:
  - Plan and conduct interviews, usability tests, surveys, and other research activities.
  - Synthesize qualitative findings into personas, user journeys, and actionable recommendations.
  - Validate product assumptions and inform prioritization with user evidence.
  - Work with PdM to define research questions and success criteria.

- Goals:
  - Ensure product decisions are grounded in user needs and behaviors.
  - Reduce rework by surfacing usability issues early.

- Interactions:
  - Frequent collaboration with Product Managers to inform roadmap and acceptance criteria.
  - Share findings with Designers, Developers, and Project Managers; provide input to acceptance criteria or DoD when UX or usability is impacted.
  - Provide artifacts (research summaries, recordings, journey maps) into the project repo/docs for transparency.

### DevOps Engineer

- Role Summary:
  Builds and maintains CI/CD pipelines, infrastructure-as-code, observability, and deployment processes; ensures reliable, repeatable releases.

- Responsibilities:
  - Design, implement, and maintain build/test/deploy pipelines.
  - Manage infrastructure-as-code, configuration, and environment provisioning.
  - Implement monitoring, alerting, and runbook guidance for production systems.
  - Support release automation, rollback strategies, and incident response coordination.

- Goals:
  - Reduce deployment risk and mean time to recovery.
  - Increase deployment frequency while maintaining system stability.

- Interactions:
  - Works closely with Developers on build/test requirements and release readiness.
  - Coordinates with Project Managers and QA on release windows, smoke tests, and rollback plans.
  - Aligns with Security and SRE/Operations for production controls and incident escalation.

### QA Lead

- Role Summary:
  Responsible for defining and coordinating the test strategy, prioritizing testing efforts, and ensuring product quality aligns with expectations.

- Responsibilities:
  - Define overall QA strategy and define regression/test coverage expectations.
  - Coordinate test planning, resource allocation, and defect triage.
  - Maintain acceptance criteria alignment with Product and Project Managers.
  - Mentor/test automation engineers and coordinate manual testing as needed.

- Goals:
  - Ensure high confidence in releases and reduce escaped defects to production.
  - Make testing effort visible and predictable for planning.

- Interactions:
  - Collaborates with Developers and DevOps to ensure test automation and test environment availability.
  - Works with Product Managers on acceptance criteria and with Project Managers to schedule testing cycles into the release plan.
  - Reports quality metrics and test status in the weekly delivery sync.

### Business Analyst

- Role Summary:
  Translates stakeholder needs and business context into clear requirements, models, and acceptance criteria to enable effective delivery.

- Responsibilities:
  - Elicit, document, and validate business requirements with stakeholders.
  - Model workflows and edge cases, produce clear acceptance criteria, and help refine user stories.
  - Validate that delivered solutions meet business needs and measurable outcomes.
  - Maintain traceability between requirements and delivered features.

- Goals:
  - Reduce ambiguity in requirements and ensure delivered outcomes align with business goals.
  - Accelerate stakeholder approvals and reduce rework.

- Interactions:
  - Works across Product Managers, Project Managers, and Stakeholders to clarify scope and acceptance criteria.
  - Engages with Developers and QA to validate implementation against business rules.
  - Serves as a point of contact for downstream stakeholders (support, sales) when requirements affect other teams.

---

## Role Interaction Guidance (general)

- When introducing or assigning a new role in a project, record:
  - Who owns the role for this project (name & contact)
  - Decision authority and escalation path
  - Expected deliverables and cadence
  - Cross-role dependencies and handoffs (e.g., "DevOps ensures staging environment availability 2 days before release window")
- Document these items in the project one-pager or project README so responsibilities are surfaced to new team members and stakeholders.