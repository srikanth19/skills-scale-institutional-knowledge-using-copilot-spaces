# OctoAcme — Cross-Functional Roles RACI

This matrix maps every role to each project lifecycle phase using the RACI convention:

| Key | Meaning |
|-----|---------|
| **R** | **Responsible** — does the work |
| **A** | **Accountable** — owns the outcome (one per row) |
| **C** | **Consulted** — provides input before the work is done |
| **I** | **Informed** — notified when the work is done |

For full role descriptions see [OctoAcme Personas](./octoacme-roles-and-personas.md).

---

## RACI Matrix

| Lifecycle Activity | Project Manager | Product Manager | Developer | UI/UX Designer | DevOps / Platform Eng. | QA Lead | Business Analyst | Customer Support |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Initiation** | | | | | | | | |
| Define problem statement & success metrics | C | **A** | I | I | I | I | **R** | C |
| Complete Project One-pager | **A** | R | I | I | I | I | R | I |
| Stakeholder alignment & communication plan | **A** | R | I | I | I | I | C | C |
| Initial risk identification | **A** | C | C | C | C | C | R | I |
| Go / No-go decision | C | **A** | I | I | I | I | C | I |
| **Planning** | | | | | | | | |
| Backlog creation & prioritization | C | **A** | C | C | I | C | R | C |
| Acceptance criteria authoring | C | A | C | C | I | C | **R** | I |
| Definition of Done (DoD) | C | C | R | C | C | **A** | C | I |
| Test plan creation | I | C | C | C | C | **A** | C | I |
| Release plan & milestone map | **A** | R | C | I | C | C | I | I |
| Risk register setup | **A** | C | C | I | C | C | R | I |
| UX / Design review (wireframes) | I | C | C | **A** | I | I | C | I |
| **Execution & Tracking** | | | | | | | | |
| Feature development | I | C | **A** | C | I | C | I | I |
| UI implementation & design QA | I | I | R | **A** | I | C | I | I |
| CI/CD pipeline & environment management | I | I | C | I | **A** | C | I | I |
| Testing (functional, regression) | C | I | C | C | C | **A** | I | I |
| Defect triage & resolution | C | I | R | C | C | **A** | I | I |
| Risk register updates | **A** | I | C | I | C | C | C | I |
| Weekly status reporting | **A** | C | I | I | I | C | I | I |
| **Release & Deployment** | | | | | | | | |
| Release readiness sign-off | **A** | C | C | C | C | R | I | C |
| Deployment execution | I | I | C | I | **A** | C | I | I |
| Smoke & post-deploy verification | C | I | C | I | C | **A** | I | I |
| Rollback decision | **A** | C | C | I | R | C | I | I |
| Release notes & stakeholder announcement | **A** | R | I | I | I | I | I | R |
| Customer-facing communication | C | R | I | I | I | I | I | **A** |
| **Retrospective & Improvement** | | | | | | | | |
| Retro facilitation | **A** | C | C | C | C | C | C | C |
| Action item capture & tracking | **A** | C | R | C | C | C | C | C |
| Process improvement proposals | C | C | R | C | C | R | C | **R** |
| Customer feedback synthesis | I | **A** | I | C | I | I | R | R |

---

## Notes
- A single **A** (Accountable) per activity is intentional. If your team uses a different model, adapt accordingly.
- Cells with **R** and **A** in the same role mean that role both does the work and owns the outcome.
- Adjust this matrix at project kickoff to reflect actual team composition.
