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

## New / Expanded Personas (proposed additions)

Below are proposed personas to add to the document to improve clarity and handoffs. Each persona includes a short role summary, responsibilities, and typical interactions with existing roles.

### UI/UX Designer

- Role Summary: Designs user experiences, workflows, and user interfaces; translates product requirements into prototypes and visual designs.
- Responsibilities:
  - Create wireframes, high-fidelity mockups, and interactive prototypes
  - Conduct or coordinate usability testing and synthesize results
  - Define UI patterns and accessibility considerations
  - Provide design assets and specs for implementation
- Interactions:
  - Partners with Product Managers to turn requirements into user-centered designs
  - Works with Developers to ensure designs are implemented as intended and provide component specs
  - Coordinates with QA to validate accessibility and visual regressions
  - Shares user-testing findings with PMs and Project Managers to inform priorities

### DevOps Engineer

- Role Summary: Builds and maintains CI/CD pipelines, deployment automation, infrastructure-as-code, and observability tooling to enable reliable delivery.
- Responsibilities:
  - Design and maintain build, test, and deployment pipelines
  - Manage infrastructure provisioning, configuration, and secrets
  - Implement monitoring, alerting, and runbook automation
  - Support performance and scalability improvements
- Interactions:
  - Works closely with Developers to enable repeatable builds and safe deployments
  - Partners with Project Managers to schedule deployments and maintenance windows
  - Supports QA and SRE/Support in diagnosing production issues
  - Advises Product on feasibility and risk for operational changes

### Data Analyst

- Role Summary: Collects, analyzes, and interprets product and usage data to inform decisions and measure success metrics.
- Responsibilities:
  - Define instrumentation and data collection requirements with Product and Engineering
  - Produce dashboards, reports, and ad-hoc analyses for feature validation
  - Help define success metrics and experiment measurement plans
  - Identify data quality issues and propose mitigations
- Interactions:
  - Collaborates with Product Managers to define metrics and interpret results
  - Works with Developers to ensure correct event instrumentation
  - Shares findings with Project Managers and stakeholders to inform priorities and retrospectives

### Support Lead (Post-launch Support / Customer Success Liaison)

- Role Summary: Owns post-launch customer support coordination and feedback loops to product and engineering.
- Responsibilities:
  - Triage incoming support issues and escalate critical incidents
  - Capture recurring user issues and feature requests
  - Maintain runbooks and knowledge-base updates for common issues
  - Coordinate with Product and Engineering to prioritize bug fixes and improvements
- Interactions:
  - Communicates customer-impacting issues to Product and Project Managers
  - Works with Developers and DevOps for incident troubleshooting and post-incident actions
  - Provides input for release notes and customer communications

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Notes on adoption
- When adding a new persona, include:
  - A brief role summary (1–2 lines)
  - Primary responsibilities (short bullet list)
  - Who they most frequently interact with (Product, Project, Dev, QA, Support)
  - A short note on how success is measured for that role in the context of the project

- Consider placing persona ownership (a named contact) for larger projects so handoffs are clear.
