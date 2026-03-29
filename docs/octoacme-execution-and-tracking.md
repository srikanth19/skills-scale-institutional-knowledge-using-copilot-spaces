# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic (owned by **Developers**)
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release (owned by **QA Lead**)
- Security scanning in CI (configured by **DevOps / Platform Engineer**)
- UI/UX fidelity review by **UI/UX Designer** before QA begins
- Manual QA for feature acceptance (**QA Lead** coordinates; **Customer Support** provides UAT scenarios when relevant)
- Use the [Development → QA Handoff Checklist](./octoacme-handoff-checklists.md#3-development--qa-handoff-per-feature--sprint) before moving to QA

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint (DevOps / Platform Engineer)
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] Design reviews with UI/UX Designer scheduled each sprint
- [ ] QA has access to staging environment (DevOps)
