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

## Scrum Master

### Role Summary
The Scrum Master is an Agile coach and process facilitator, not a people manager. They ensure the team follows Agile principles, remove impediments, and create conditions for sustainable delivery.

### Responsibilities
- Facilitate standups, sprint planning, sprint reviews, and retrospectives
- Identify and remove blockers that slow the team
- Shield the team from unplanned external disruptions during a sprint
- Coach team members on Agile practices and self-organization
- Track sprint metrics (velocity, burndown) and surface trends

### Goals
- Keep sprint cadence consistent and predictable
- Foster a culture of continuous improvement
- Reduce cycle time and unplanned interruptions

### Typical Communication
- Daily standup facilitation and blocker escalation
- Sprint reports and burndown updates to PM
- Retrospective action items to the full team

### How they interact with existing roles
| Role | Interaction |
|------|-------------|
| Project Manager (PM) | Escalates cross-team blockers; aligns sprint schedule with project milestones |
| Product Manager (PdM) | Coordinates backlog refinement timing; flags when scope creep threatens sprint goals |
| Developers | Protects focus time; coaches on Agile practices; facilitates ceremonies |
| QA | Ensures test tasks are included in sprint planning; flags testing bottlenecks |
| Stakeholders | Summarizes sprint outcomes at reviews; manages ad-hoc requests through PM/PdM |

---

## Business Analyst

### Role Summary
The Business Analyst (BA) bridges business stakeholders and the delivery team by gathering, refining, and documenting requirements so developers build the right thing.

### Responsibilities
- Elicit and document requirements through stakeholder interviews and workshops
- Translate business needs into user stories with clear acceptance criteria
- Maintain a requirements traceability matrix
- Clarify scope ambiguities for developers and QA during implementation
- Support test-case preparation and sign-off on acceptance criteria

### Goals
- Ensure requirements are complete, unambiguous, and testable before work begins
- Reduce mid-sprint scope changes caused by unclear requirements
- Improve alignment between business expectations and delivered output

### Typical Communication
- Requirements workshops and stakeholder review sessions
- User story walkthroughs with developers and QA
- Scope change requests routed through PM and PdM

### How they interact with existing roles
| Role | Interaction |
|------|-------------|
| Project Manager (PM) | Flags scope changes and timeline impacts; contributes to risk register |
| Product Manager (PdM) | Refines roadmap items into sprint-ready stories; validates prioritization |
| Developers | Answers requirement questions during implementation; reviews PRs for spec alignment |
| QA | Co-authors acceptance criteria; assists in test-case reviews |
| Stakeholders | Primary point of contact for requirement gathering and change requests |

---

## UX Designer

### Role Summary
The UX Designer advocates for the end user throughout the product lifecycle, ensuring solutions are usable, accessible, and aligned with user needs.

### Responsibilities
- Conduct user research, usability studies, and persona development
- Create user flows, wireframes, and interactive prototypes
- Define and maintain design system components and accessibility standards
- Collaborate with developers during implementation to preserve design intent
- Participate in acceptance testing to validate usability outcomes

### Goals
- Deliver experiences that are intuitive and accessible
- Reduce rework by validating designs with users before implementation
- Ensure design decisions are evidence-based and documented

### Typical Communication
- Design reviews and prototype walkthroughs with PM, PdM, and developers
- Usability study findings shared with stakeholders
- Annotations and design specs provided in shared design tool

### How they interact with existing roles
| Role | Interaction |
|------|-------------|
| Project Manager (PM) | Aligns design sprints to project timeline; surfaces dependency risks |
| Product Manager (PdM) | Translates product vision into user flows; validates designs against success metrics |
| Developers | Provides annotated specs and is available for implementation Q&A |
| QA | Reviews test cases for usability coverage; participates in UAT |
| Stakeholders | Shares research findings and prototype demos for early feedback |

---

## Technical Lead

### Role Summary
The Technical Lead (Tech Lead) is the most senior engineer on a project team. They own architecture decisions, set technical standards, and provide guidance to developers.

### Responsibilities
- Define and document the technical architecture and key design decisions
- Review and approve major code and architectural changes
- Mentor developers and conduct code reviews
- Identify and communicate technical risks to the PM
- Coordinate with DevOps/Platform teams on infrastructure and deployment readiness

### Goals
- Ensure the solution is scalable, maintainable, and secure
- Reduce technical debt by setting clear coding and testing standards
- Enable the team to move quickly without sacrificing quality

### Typical Communication
- Architecture decision records (ADRs) and technical design docs
- Code review feedback in PRs
- Weekly technical sync with PM and QA on risks and dependencies

### How they interact with existing roles
| Role | Interaction |
|------|-------------|
| Project Manager (PM) | Reports technical risks and dependency blockers; contributes to milestone planning |
| Product Manager (PdM) | Provides feasibility assessments and effort estimates for roadmap items |
| Developers | Leads design reviews; mentors; approves PRs for architectural changes |
| QA | Collaborates on test strategy and environment readiness |
| Stakeholders | Presents technical approach at kickoff and demos on request |

---

## Interaction Examples

### Feature Discovery
1. **PdM** identifies a new feature opportunity from user research and drafts a problem statement.
2. **BA** runs stakeholder workshops to gather requirements; **UX Designer** creates initial user flows.
3. **Tech Lead** provides a feasibility assessment and high-level effort estimate.
4. **PM** incorporates findings into the roadmap and communicates timeline to stakeholders.
5. **Scrum Master** adds refined stories to the backlog for the next sprint planning session.

### Sprint Planning
1. **PdM** presents the prioritized backlog; **BA** walks through acceptance criteria for top items.
2. **Scrum Master** facilitates estimation and confirms sprint capacity with developers.
3. **Tech Lead** flags dependencies and technical risks; **PM** captures them in the risk register.
4. **UX Designer** confirms design specs are ready for stories entering the sprint.
5. **Scrum Master** finalizes the sprint goal and communicates it to stakeholders via **PM**.

### Release Readiness
1. **Tech Lead** confirms code freeze and ensures all critical PRs are merged and reviewed.
2. **QA** runs final acceptance tests; **BA** validates that acceptance criteria are met.
3. **UX Designer** performs a usability spot-check on key flows.
4. **PM** prepares the release communication and coordinates with stakeholders.
5. **Scrum Master** facilitates the sprint review, capturing demo feedback for the next cycle.

---

## See Also
- [Role Interactions & Accountability Guide](octoacme-role-interactions.md) — RACI-lite table and escalation patterns for common project activities.
- [Role Onboarding Checklist](role-onboarding-checklist.md) — Actionable checklist template for onboarding any role on a project.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

