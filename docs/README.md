# OctoAcme Project Management Documentation

Welcome — this folder contains OctoAcme’s standardized project management process documents and a short overview to help new teammates and stakeholders find the right guidance quickly.

## Overview
OctoAcme follows an iterative, outcome-driven approach that moves work through clear stages: Initiation, Planning, Execution & Tracking, Release & Deployment, and Retrospective/Continuous Improvement. Initiatives start with a lightweight Project One-pager to confirm the business need, success metrics, and stakeholders, then move into planning where scope, dependencies, and a release timeline are defined. Execution focuses on small, testable increments managed on a project board and delivered through a disciplined pull request workflow.

## Key Workflows & Quality Practices
Work is managed on a project board with columns (Backlog, Ready, In Progress, In Review, QA, Done). PRs should be small, include issue links and acceptance criteria, and run CI (tests, linting, and security scans) before review. Quality assurance is integrated across the lifecycle with unit and integration tests, smoke tests for critical flows, manual QA when needed, and post-deploy verifications and rollback plans. Releases are classified (patch, minor, major) with a checklist for staging, verification, and communication.

## Roles, Communication & Continuous Improvement
Roles are clearly defined: Product Managers set outcomes and priorities, Project Managers coordinate delivery and communication, Developers implement and test, and QA validates acceptance criteria. Communication cadence includes daily standups, weekly delivery syncs, and regular stakeholder updates with escalation paths for blockers. Retrospectives after sprints or releases capture action items that are tracked back into the backlog for measurable follow-up.

## Documentation Index
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

## How to propose changes
Use the "Add Content to Project Management Process Docs" issue template in .github/ISSUE_TEMPLATE to propose updates to any document, or open a new issue and link the proposed changes. For small edits, open a PR against this docs/ README or the targeted document and request a review from the relevant stakeholders.
