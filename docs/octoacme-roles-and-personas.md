# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

For a full view of how each role participates across the project lifecycle, see:
- [Cross-Functional Roles RACI](./octoacme-cross-functional-roles-raci.md)
- [Handoff Checklists](./octoacme-handoff-checklists.md)

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

## UI/UX Designer

### Role Summary
UI/UX Designers create user interfaces and experiences that maximize usability, accessibility, and alignment with product requirements. They bridge customer needs and technical implementation through iterative design.

### Responsibilities
- Create wireframes, mockups, and interactive prototypes
- Conduct usability testing, user research, and accessibility reviews
- Define and maintain the design system and style guide
- Review implemented features for design fidelity
- Document design decisions and rationale

### Goals
- Deliver intuitive and accessible user experiences
- Reduce rework by surfacing usability issues early
- Ensure design consistency across the product

### Typical Communication
- Design reviews with Product Managers and Developers (per sprint/milestone)
- Async feedback via design tools (e.g., Figma comments)
- Usability test summaries shared with the full team

### Interactions with Existing Roles
- **Product Managers**: Aligns designs to product vision and acceptance criteria; participates in backlog refinement.
- **Developers**: Pairs on implementation details; answers design questions during development; reviews built features before QA.
- **QA Lead**: Provides design specs so QA can validate visual and interaction acceptance criteria.
- **Business Analyst**: Reviews user research and requirements to inform design decisions.

---

## DevOps / Platform Engineer

### Role Summary
DevOps / Platform Engineers build and operate the infrastructure, CI/CD pipelines, and deployment processes that enable reliable, scalable delivery. They reduce friction between development and production.

### Responsibilities
- Design, automate, and maintain build, test, and deploy pipelines
- Manage cloud infrastructure, environments, and access controls
- Monitor system health and lead incident response
- Enforce security and compliance controls in deployment workflows
- Maintain runbooks and disaster-recovery procedures

### Goals
- Maximise deployment frequency while minimising risk
- Achieve high availability and fast mean time to recovery (MTTR)
- Keep infrastructure costs and complexity under control

### Typical Communication
- Release coordination meetings with PM and QA Lead
- Incident bridges (synchronous) and post-incident write-ups
- Infrastructure change notices to the delivery team

### Interactions with Existing Roles
- **Developers**: Collaborates on CI configuration, environment parity, and release automation.
- **QA Lead**: Coordinates deployment to test environments; supports test automation infrastructure.
- **Project Managers**: Reports deployment timelines, environment issues, and incident status.
- **Product Managers**: Communicates platform constraints that affect feature delivery.

---

## QA Lead / Test Engineer

### Role Summary
The QA Lead oversees quality strategy, test planning, and defect management, ensuring all deliverables meet acceptance criteria before release.

### Responsibilities
- Develop and maintain the test plan (functional, regression, performance, accessibility)
- Coordinate manual and automated testing across sprints
- Track, triage, and communicate defects with clear severity/priority
- Define and maintain the Definition of Done quality gates
- Participate in release readiness reviews

### Goals
- Prevent defects from reaching production
- Build a reliable, maintainable automated test suite
- Provide clear, timely quality signals to the team

### Typical Communication
- Daily bug triage (async) and weekly quality summary to PM
- Test results posted to the project board or PR comments
- Pre-release sign-off communicated to PM and DevOps

### Interactions with Existing Roles
- **Developers**: Pairs on bug reproduction and fix verification; reviews acceptance criteria together.
- **DevOps / Platform Engineer**: Syncs on test automation infrastructure and deployment pipelines.
- **Product Managers**: Clarifies acceptance criteria and edge cases; escalates quality risks.
- **UI/UX Designer**: Validates visual and interaction fidelity against design specs.
- **Project Managers**: Reports test progress and unresolved defects that may affect the release date.

---

## Business Analyst

### Role Summary
Business Analysts gather and document requirements, map business processes, and support Product Managers in translating stakeholder needs into actionable work.

### Responsibilities
- Elicit requirements through interviews, workshops, and document review
- Write detailed user stories, use cases, and acceptance criteria
- Analyze and diagram as-is and to-be processes
- Validate that delivered solutions meet the original business need
- Maintain the requirements traceability matrix

### Goals
- Ensure requirements are clear, complete, and testable before development begins
- Bridge communication between business stakeholders and the delivery team
- Reduce misunderstandings and late-stage scope changes

### Typical Communication
- Requirements workshops with stakeholders (at initiation and planning)
- Backlog refinement sessions with PM and development team
- Written acceptance criteria and process diagrams in project docs

### Interactions with Existing Roles
- **Product Managers**: Partners to translate product vision into prioritized backlog items.
- **Developers**: Clarifies requirements and acceptance criteria during development; validates solutions.
- **QA Lead**: Shares acceptance criteria and edge cases to support test planning.
- **Project Managers**: Provides requirements status and flags scope risks during planning and execution.
- **UI/UX Designer**: Collaborates on user research and user story mapping.

---

## Customer Support / Customer Advocate

### Role Summary
Customer Support / Customer Advocates represent the voice of end-users. They surface real-world customer feedback and help ensure releases are communicated clearly and adopted successfully.

### Responsibilities
- Share customer insights, pain points, and frequently reported issues with Product and Project Managers
- Support release communication, including customer-facing release notes and onboarding guidance
- Track and escalate incoming customer issues linked to new or changed features
- Assist QA with user acceptance testing (UAT) scenarios from a customer perspective
- Provide input on support documentation and FAQs for each release

### Goals
- Minimize customer-facing impact of releases
- Ensure customer feedback loops back into the product roadmap
- Reduce support ticket volume through proactive communication and documentation

### Typical Communication
- Weekly feedback summary to Product Manager
- Release readiness review participation (pre-release)
- Support ticket escalations to PM / Project Manager as needed

### Interactions with Existing Roles
- **Product Managers**: Provides customer feedback that informs backlog prioritization and roadmap.
- **Project Managers**: Reports support escalations that may affect release timelines or scope.
- **QA Lead**: Contributes real-world user scenarios for UAT and acceptance testing.
- **DevOps / Platform Engineer**: Escalates production issues reported by customers during incident response.
- **Developers**: Reports bug patterns discovered in the field for triage.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [Cross-Functional Roles RACI](./octoacme-cross-functional-roles-raci.md) for an at-a-glance view of who is Responsible, Accountable, Consulted, or Informed at each lifecycle phase.

