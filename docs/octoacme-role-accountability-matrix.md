# OctoAcme — Role Accountability Matrix (RACI)

## Purpose
Clarify ownership, accountability, and collaboration expectations across all OctoAcme roles and project lifecycle phases. Use this matrix to resolve ambiguity about who makes decisions, who does the work, who must be consulted, and who should be informed.

---

## RACI Key

| Code | Meaning |
|---|---|
| **R** | **Responsible** — does the work |
| **A** | **Accountable** — owns the outcome; approves and is answerable |
| **C** | **Consulted** — provides input before work is complete |
| **I** | **Informed** — kept up to date on decisions and outcomes |

> Each task should have exactly one **A**. Multiple **R** roles are allowed.

---

## Initiation Phase

| Activity | Project Sponsor | Program Manager | Project Manager | Product Manager | Engineering Manager | Delivery Lead | Risk & Compliance Coord. | Change Mgmt Lead |
|---|---|---|---|---|---|---|---|---|
| Approve project charter and funding | A | I | C | C | I | I | I | I |
| Define business goals and success metrics | A | I | C | R | I | I | I | I |
| Identify stakeholders and communication needs | C | C | A | R | C | I | C | R |
| Capture initial risk list | I | C | A | C | C | C | R | I |
| Confirm team roles and assignments | C | A | R | C | R | C | I | I |
| Initial compliance and regulatory scan | I | I | C | I | C | I | R | I |

---

## Planning Phase

| Activity | Project Sponsor | Program Manager | Project Manager | Product Manager | Engineering Manager | Delivery Lead | Release Coordinator | Risk & Compliance Coord. | Metrics & Process Improv. Owner |
|---|---|---|---|---|---|---|---|---|---|
| Approve milestone plan and resource allocation | A | C | R | C | C | C | I | I | I |
| Prioritize backlog and define acceptance criteria | C | I | C | A | C | I | I | I | I |
| Map cross-team dependencies | I | A | R | C | C | R | C | C | I |
| Define release schedule and readiness criteria | I | I | C | C | C | C | A | C | I |
| Complete risk assessment and mitigation planning | I | I | C | I | C | C | C | A | I |
| Establish process metrics baseline | I | I | C | I | C | I | I | I | A |
| Draft communication and adoption plan | I | I | C | C | I | I | C | I | I |

---

## Execution Phase

| Activity | Project Manager | Product Manager | Engineering Manager | Delivery Lead | Developers | QA / Test Lead | Risk & Compliance Coord. | Metrics & Process Improv. Owner |
|---|---|---|---|---|---|---|---|---|
| Manage sprint/iteration delivery | A | C | C | R | R | C | I | I |
| Maintain and update risk register | C | I | I | C | I | C | R | I |
| Track cross-team dependencies and blockers | C | I | I | A | R | I | C | I |
| Test and validate acceptance criteria | C | C | C | I | R | A | I | I |
| Escalate risks exceeding team authority | A | I | C | C | I | I | R | I |
| Monitor delivery process health metrics | C | I | C | C | I | I | I | A |

---

## Release Phase

| Activity | Project Sponsor | Project Manager | Delivery Lead | QA / Test Lead | Release Coordinator | Change Mgmt Lead | Risk & Compliance Coord. |
|---|---|---|---|---|---|---|---|
| Complete release readiness checklist | I | C | C | R | A | C | C |
| Facilitate go/no-go decision | C | C | C | C | A | I | C |
| Approve major release (business sign-off) | A | I | I | I | C | I | I |
| Coordinate deployment window and logistics | I | I | C | C | A | C | I |
| Send stakeholder release communication | I | I | I | I | C | A | I |
| Confirm post-deploy verification | I | C | C | R | A | I | I |

---

## Retrospective Phase

| Activity | Project Manager | Program Manager | Delivery Lead | Product Manager | Metrics & Process Improv. Owner | Technical Writer |
|---|---|---|---|---|---|---|
| Facilitate retrospective session | A | C | C | C | C | I |
| Capture and publish retrospective notes | R | I | C | C | C | A |
| Identify and prioritize process improvements | C | C | C | C | A | C |
| Update process documentation | C | I | I | I | C | A |
| Track improvement action items to completion | C | C | I | I | A | I |

---

## Decision Rights Summary

| Decision | Who Decides | Who Must Be Consulted | Who Is Informed |
|---|---|---|---|
| Strategic scope and priority changes | Project Sponsor | Program Manager, Project Manager, Product Manager | Full delivery team |
| Release go/no-go | Release Coordinator | Delivery Lead, QA / Test Lead, Project Manager | Project Sponsor, Change Mgmt Lead |
| Risk escalation beyond team authority | Project Manager → Project Sponsor | Risk & Compliance Coordinator | Affected workstream leads |
| Backlog prioritization | Product Manager | Project Manager, Engineering Manager | Developers, QA / Test Lead |
| Process improvement adoption | Metrics & Process Improvement Owner | Project Manager, Delivery Lead | Full delivery team |
| Major external communications | Change Mgmt Lead (standard) / Project Sponsor (high impact) | Product Manager, Release Coordinator | All affected stakeholders |
| Cross-workstream sequencing | Program Manager | Project Managers, Delivery Lead | Project Sponsor |

---

## Notes on Usage

- **This matrix is a starting point.** Adapt it at project kickoff to reflect the actual team composition and decision norms.
- **Accountability should be singular.** If two roles share an **A**, clarify ownership before work begins.
- **Escalation paths follow the accountability chain.** When a task owner (R) is blocked, escalate to the accountable role (A) and, if needed, to the next level in the decision rights table above.
- Review this matrix at retrospectives and update it to reflect any changes in team structure or process.
