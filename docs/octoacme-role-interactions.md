# OctoAcme Role Interactions & Accountability Guide

This guide provides a lightweight RACI-style reference for common project activities. Use it to quickly identify who leads each activity, who is ultimately accountable, who should be consulted, and who should be kept informed.

**Legend:** R = Responsible (does the work) · A = Accountable (owns the outcome) · C = Consulted (provides input) · I = Informed (kept up to date)

---

## RACI-Lite Table

| Activity | PM | PdM | Scrum Master | BA | UX Designer | Tech Lead | Developers | QA | Stakeholders |
|---|---|---|---|---|---|---|---|---|---|
| Discovery & Requirements | C | A | I | R | C | C | I | I | C |
| Sprint Planning | C | A | R | C | C | C | R | C | I |
| Design & UX | I | C | I | C | R/A | C | C | C | I |
| Implementation | C | I | I | C | C | A | R | C | I |
| QA & Acceptance | C | C | I | C | C | C | C | R/A | I |
| Release & Deployment | A | C | I | I | I | C | R | C | I |
| Incident Triage | A | I | I | I | I | C | R | C | I |

> **Note:** Where two letters appear (R/A), the same person or team is both doing the work and accountable for the outcome. Adjust assignments to match your project's specific structure.

---

## Escalation & Handoff Points

### Scrum Master → Project Manager
**When to escalate:**
- A blocker cannot be resolved within 24 hours and is threatening the sprint goal.
- Unplanned external requests are repeatedly disrupting the team during a sprint.
- Inter-team dependencies are not being resolved through normal channels.

**How:** Scrum Master notifies PM in writing (email or project channel) with a clear description of the blocker, the impact, and what has already been tried.

### Project Manager → Product Lead / Sponsor
**When to escalate:**
- A scope change significantly impacts cost, timeline, or quality.
- A risk in the register has been realized and requires a decision above the PM's authority.
- Resource constraints cannot be resolved at the delivery team level.

**How:** PM drafts a brief escalation memo (issue, options, recommendation) and schedules a decision meeting with the Product Lead or Sponsor within 48 hours.

### Business Analyst → Project Manager
**When to escalate:**
- Stakeholders cannot agree on requirements, causing work to stall.
- A change request significantly expands scope mid-sprint.

**How:** BA documents the conflicting requirements and proposed resolution options, then hands off to PM for stakeholder arbitration.

### Tech Lead → Project Manager
**When to escalate:**
- A technical risk has materialized and will impact delivery timelines.
- An architectural decision requires cross-team alignment or sign-off from a senior architect.

**How:** Tech Lead updates the risk register and flags the item at the weekly PM sync.

---

## Handoff Checkpoints by Phase

| Phase transition | Handing off | Receiving | Key artifact |
|---|---|---|---|
| Discovery → Planning | PdM + BA | PM + Tech Lead | Refined user stories with acceptance criteria |
| Planning → Sprint | PM + Scrum Master | Developers + QA | Sprint backlog, sprint goal |
| Design → Implementation | UX Designer | Developers | Annotated design specs |
| Implementation → QA | Developers | QA | PR merged, test environment updated |
| QA → Release | QA + Tech Lead | PM | Signed-off test report, release checklist |
| Release → Close | PM | PdM + Stakeholders | Release notes, updated roadmap |

---

## See Also
- [Roles & Personas](octoacme-roles-and-personas.md) — Full definitions for all roles including responsibilities and interaction examples.
- [Role Onboarding Checklist](role-onboarding-checklist.md) — Checklist template for any role joining a project.
