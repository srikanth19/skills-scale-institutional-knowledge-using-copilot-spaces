# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- Project Manager (PM): coordinates delivery, schedules, risk, communications.
- Product Manager (PdM): defines outcomes, prioritizes backlog, and measures success.
- Developers: implement features, collaborate on design and testability.
- UI/UX Designer: designs user experiences and validates implementation fidelity.
- DevOps / Platform Engineer: manages infrastructure, CI/CD, and deployment.
- QA Lead / Test Engineer: oversees quality strategy, test planning, and defect management.
- Business Analyst: gathers requirements and bridges stakeholders with the delivery team.
- Customer Support / Customer Advocate: surfaces customer feedback and supports release adoption.
- Stakeholders: provide inputs and approvals.

See [OctoAcme Personas](./octoacme-roles-and-personas.md) for full role descriptions and interaction points.
See [Cross-Functional Roles RACI](./octoacme-cross-functional-roles-raci.md) for accountability across each lifecycle phase.

## Key Artifacts
- Project Charter / One-pager (owned by Project Manager, drafted with Business Analyst)
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done (QA Lead owns DoD; Business Analyst authors acceptance criteria)
- Risk Register
- Retrospective notes and action items
- [Cross-Functional Roles RACI](./octoacme-cross-functional-roles-raci.md)
- [Handoff Checklists](./octoacme-handoff-checklists.md)

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
