# OctoAcme — Handoff Checklists

Structured checklists for the critical handoffs between roles and lifecycle phases. Use these to reduce miscommunication and ensure nothing falls through the cracks.

For role descriptions see [OctoAcme Personas](./octoacme-roles-and-personas.md).
For accountability at each phase see [Cross-Functional Roles RACI](./octoacme-cross-functional-roles-raci.md).

---

## 1. Initiation → Planning Handoff

**From:** Project Manager + Business Analyst + Product Manager  
**To:** Full delivery team (Developers, UI/UX Designer, QA Lead, DevOps)

- [ ] Project One-pager reviewed and approved by sponsor/stakeholder
- [ ] Success metrics defined and measurable
- [ ] Stakeholder list and communication plan documented
- [ ] Initial risk list created in the Risk Register
- [ ] High-level timeline and key milestones agreed
- [ ] Team roles confirmed and capacity checked
- [ ] Go / No-go decision recorded

---

## 2. Planning → Execution Handoff

**From:** Product Manager + Business Analyst + Project Manager  
**To:** Developers, UI/UX Designer, QA Lead, DevOps / Platform Engineer

- [ ] Prioritized backlog with acceptance criteria finalized
- [ ] Definition of Done (DoD) documented and shared with the team
- [ ] Initial test plan drafted by QA Lead
- [ ] Wireframes / design specs published and reviewed by Developers
- [ ] Environments provisioned or confirmed by DevOps
- [ ] CI/CD pipeline is operational for the project
- [ ] Release plan and milestone map communicated to all roles
- [ ] Risk Register updated with planning-phase risks

---

## 3. Development → QA Handoff (per feature / sprint)

**From:** Developer  
**To:** QA Lead / Test Engineer

- [ ] Feature branch merged to integration/staging branch
- [ ] PR description includes issue link, acceptance criteria, and testing notes
- [ ] All automated tests (unit, integration) pass in CI
- [ ] Feature deployed to staging environment by DevOps
- [ ] Known limitations or out-of-scope items documented
- [ ] Design fidelity reviewed by UI/UX Designer before QA begins
- [ ] QA notified (via project board column move or direct message)

---

## 4. QA → Release Handoff

**From:** QA Lead  
**To:** DevOps / Platform Engineer + Project Manager + Product Manager

- [ ] All acceptance criteria verified and marked as passed
- [ ] No open P0 or P1 defects
- [ ] Regression test suite executed with results documented
- [ ] UAT scenarios reviewed (with Customer Support input if applicable)
- [ ] Release readiness sign-off provided by QA Lead
- [ ] Performance and security tests completed (if in scope)
- [ ] Release notes reviewed for accuracy by Product Manager

---

## 5. Release → Post-Release / Support Handoff

**From:** DevOps / Platform Engineer + Product Manager  
**To:** Customer Support / Customer Advocate + Project Manager

- [ ] Deployment completed and post-deploy verification passed
- [ ] Rollback plan confirmed as available (and not needed)
- [ ] Release notes published (internal and customer-facing)
- [ ] Customer Support briefed on new features, known issues, and workarounds
- [ ] Monitoring dashboards checked for anomalies
- [ ] On-call rotation updated if applicable
- [ ] Support FAQ or documentation updated by Customer Support

---

## 6. Post-Release → Retrospective Handoff

**From:** Project Manager  
**To:** Full team

- [ ] Retrospective meeting scheduled within one week of release
- [ ] All roles invited (Developers, QA, DevOps, Design, BA, PM, PdM, Support)
- [ ] Key metrics shared ahead of the retro (velocity, defect rate, customer issues)
- [ ] Incident summaries and post-mortems available for review
- [ ] Previous retrospective action items reviewed for follow-up
- [ ] Action items from this retro assigned owners and due dates
- [ ] Action items added to project backlog or tracking system

---

## Tips for using these checklists
- Copy the relevant checklist into your sprint/milestone ticket or project README.
- The **Accountable** role (see [RACI](./octoacme-cross-functional-roles-raci.md)) is responsible for ensuring the checklist is completed before moving forward.
- If items are intentionally skipped, document the reason.
