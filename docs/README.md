# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation! This README provides a concise summary of our project management philosophy and core practices, along with direct links to all process documents for efficient navigation.

## Project Management Processes Overview

OctoAcme uses a customer-first, iterative approach to project delivery across all cross-functional initiatives. Every project begins with a thorough **initiation** phase: a lightweight one-pager captures the problem statement, success metrics, stakeholder list, and high-level timeline. Stakeholder alignment and a formal go/no-go decision gate ensure that only well-defined work advances to planning. Key roles—Project Manager (PM), Product Manager (PdM), Developers, QA, and Stakeholders—have clear ownership and responsibilities defined from the start, so accountability is never ambiguous.

During **planning and execution**, work is broken into shippable increments with prioritized backlogs, story-point estimates, and a documented Definition of Done. The delivery team operates in a steady rhythm of daily standups, weekly delivery syncs, and end-of-sprint demos tracked on a GitHub Projects board. Pull requests are kept small (≤ 400 lines when possible), linked to issues with acceptance criteria, and require CI passing and at least one peer approval before merging. Quality is built in through unit, integration, and end-to-end smoke tests as well as security scanning in CI.

**Risk management and communication** are continuous disciplines throughout the lifecycle. Risks are captured in a living Risk Register with impact, likelihood, owner, and mitigation plan, and are reviewed at every weekly sync. Stakeholder communication follows a structured cadence—weekly PM/PdM syncs, twice-weekly delivery standups, and monthly stakeholder updates—with a clear escalation path from team-level triage through the PM and Product Lead to sponsor-level intervention for business-impacting issues.

After each release or milestone, the team runs a **retrospective** to surface what went well, what could be improved, and concrete action items with owners and due dates. Action items feed back into the project backlog and are tracked in the weekly PM sync, fostering a culture of continuous improvement. Releases themselves follow a standardized deployment checklist—staging smoke tests, automated production pipeline, post-deploy verification, and a documented rollback plan—so every deployment reduces risk and maintains high observability.

---

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, lifecycle, and communication cadence |
| [Project Initiation Guide](octoacme-project-initiation.md) | How to validate and authorize new work, align stakeholders, and create a lightweight plan |
| [Project Planning](octoacme-project-planning.md) | Turning an approved initiative into an actionable backlog and release plan |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day team rhythm, PR workflow, quality practices, and blocker escalation |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, lifecycle, stakeholder communication templates, and escalation paths |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Pre-release requirements, deployment checklist, rollback playbook, and release notes template |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | How to run retrospectives and track improvement action items |
| [Roles and Personas](octoacme-roles-and-personas.md) | Detailed responsibilities, goals, and communication patterns for each project role |
