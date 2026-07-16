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

| Activity | Project Sponsor | Program Manager | Project Manager | Product Manager | Engineering Manager | Delivery Lead | Risk & Compliance Coord. | Change Mgmt Lead | Solution Architect | Security / Privacy Reviewer |
|---|---|---|---|---|---|---|---|---|---|---|
| Approve project charter and funding | A | I | C | C | I | I | I | I | I | I |
| Define business goals and success metrics | A | I | C | R | I | I | I | I | I | I |
| Identify stakeholders and communication needs | C | C | A | R | C | I | C | R | I | I |
| Capture initial risk list | I | C | A | C | C | C | R | I | C | C |
| Confirm team roles and assignments | C | A | R | C | R | C | I | I | C | I |
| Initial compliance and regulatory scan | I | I | C | I | C | I | R | I | I | R |
| Confirm technical feasibility and architectural approach | I | I | C | C | C | I | I | I | A | C |
| Review project for security and privacy requirements | I | I | C | C | I | I | C | I | C | A |

---

## Planning Phase

| Activity | Project Sponsor | Program Manager | Project Manager | Product Manager | Engineering Manager | Delivery Lead | Release Coordinator | Risk & Compliance Coord. | Metrics & Process Improv. Owner | Solution Architect | Security / Privacy Reviewer | Operations / SRE |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Approve milestone plan and resource allocation | A | C | R | C | C | C | I | I | I | I | I | I |
| Prioritize backlog and define acceptance criteria | C | I | C | A | C | I | I | I | I | I | I | I |
| Map cross-team dependencies | I | A | R | C | C | R | C | C | I | C | I | C |
| Define release schedule and readiness criteria | I | I | C | C | C | C | A | C | I | I | C | C |
| Complete risk assessment and mitigation planning | I | I | C | I | C | C | C | A | I | C | R | C |
| Establish process metrics baseline | I | I | C | I | C | I | I | I | A | I | I | I |
| Draft communication and adoption plan | I | I | C | C | I | I | C | I | I | I | I | I |
| Define architectural standards and integration dependencies | I | I | C | C | C | C | I | I | I | A | C | C |
| Complete threat model and security planning | I | I | C | C | C | I | I | C | I | C | A | I |
| Define SLOs, monitoring, and operational readiness criteria | I | I | C | I | C | C | C | I | I | C | I | A |

---

## Execution Phase

| Activity | Project Manager | Product Manager | Engineering Manager | Delivery Lead | Developers | QA / Test Lead | Risk & Compliance Coord. | Metrics & Process Improv. Owner | Scrum Master | Solution Architect | Security / Privacy Reviewer | Operations / SRE |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Manage sprint/iteration delivery | A | C | C | R | R | C | I | I | R | I | I | I |
| Maintain and update risk register | C | I | I | C | I | C | R | I | I | I | C | C |
| Track cross-team dependencies and blockers | C | I | I | A | R | I | C | I | R | C | I | I |
| Test and validate acceptance criteria | C | C | C | I | R | A | I | I | I | C | C | I |
| Escalate risks exceeding team authority | A | I | C | C | I | I | R | I | I | I | C | C |
| Monitor delivery process health metrics | C | I | C | C | I | I | I | A | C | I | I | I |
| Review designs and code for architectural conformance | I | I | C | I | R | I | I | I | I | A | C | I |
| Review implementation for security and privacy issues | I | I | C | I | R | C | C | I | I | C | A | I |
| Validate observability and operational readiness | I | I | C | C | R | I | I | I | I | I | I | A |
| Remove team impediments and facilitate ceremonies | C | I | I | C | I | I | I | I | A | I | I | I |

---

## Release Phase

| Activity | Project Sponsor | Project Manager | Delivery Lead | QA / Test Lead | Release Coordinator | Change Mgmt Lead | Risk & Compliance Coord. | Security / Privacy Reviewer | Operations / SRE | Support / Customer Success Rep. |
|---|---|---|---|---|---|---|---|---|---|---|
| Complete release readiness checklist | I | C | C | R | A | C | C | C | C | C |
| Facilitate go/no-go decision | C | C | C | C | A | I | C | C | C | I |
| Approve major release (business sign-off) | A | I | I | I | C | I | I | I | I | I |
| Coordinate deployment window and logistics | I | I | C | C | A | C | I | I | R | I |
| Send stakeholder release communication | I | I | I | I | C | A | I | I | I | C |
| Confirm post-deploy verification | I | C | C | R | A | I | I | I | R | C |
| Complete security sign-off | I | C | I | C | C | I | C | A | I | I |
| Complete operational readiness sign-off | I | C | C | I | C | I | I | I | A | I |
| Validate customer-facing release readiness | I | C | I | C | C | C | I | I | I | A |

---

## Retrospective Phase

| Activity | Project Manager | Program Manager | Delivery Lead | Product Manager | Metrics & Process Improv. Owner | Technical Writer | Scrum Master | Operations / SRE | Data Analyst |
|---|---|---|---|---|---|---|---|---|---|
| Facilitate retrospective session | A | C | C | C | C | I | R | I | I |
| Capture and publish retrospective notes | R | I | C | C | C | A | C | I | I |
| Identify and prioritize process improvements | C | C | C | C | A | C | C | C | C |
| Update process documentation | C | I | I | I | C | A | I | I | I |
| Track improvement action items to completion | C | C | I | I | A | I | C | I | I |
| Review metrics and delivery data trends | C | C | C | C | C | I | I | C | A |
| Review operational and incident data | I | I | C | I | C | I | I | A | C |

---

## Decision Rights Summary

| Decision | Who Decides | Who Must Be Consulted | Who Is Informed |
|---|---|---|---|
| Strategic scope and priority changes | Project Sponsor | Program Manager, Project Manager, Product Manager | Full delivery team |
| Release go/no-go | Release Coordinator | Delivery Lead, QA / Test Lead, Security / Privacy Reviewer, Operations / SRE, Project Manager | Project Sponsor, Change Mgmt Lead |
| Risk escalation beyond team authority | Project Manager → Project Sponsor | Risk & Compliance Coordinator | Affected workstream leads |
| Backlog prioritization | Product Manager | Project Manager, Engineering Manager | Developers, QA / Test Lead |
| Process improvement adoption | Metrics & Process Improvement Owner | Project Manager, Delivery Lead | Full delivery team |
| Major external communications | Change Mgmt Lead (standard) / Project Sponsor (high impact) | Product Manager, Release Coordinator | All affected stakeholders |
| Cross-workstream sequencing | Program Manager | Project Managers, Delivery Lead | Project Sponsor |
| Technical architecture decisions | Solution Architect | Engineering Manager, Project Manager | Developers, QA / Test Lead |
| Security sign-off for release | Security / Privacy Reviewer | Risk & Compliance Coordinator, Engineering Manager | Project Manager, Release Coordinator, Project Sponsor |
| Operational readiness sign-off | Operations / SRE | Release Coordinator, Engineering Manager | Project Manager, Delivery Lead |
| Customer-facing readiness sign-off | Support / Customer Success Representative | Product Manager, Change Mgmt Lead | Release Coordinator, Project Manager |

---

## Notes on Usage

- **This matrix is a starting point.** Adapt it at project kickoff to reflect the actual team composition and decision norms.
- **Accountability should be singular.** If two roles share an **A**, clarify ownership before work begins.
- **Escalation paths follow the accountability chain.** When a task owner (R) is blocked, escalate to the accountable role (A) and, if needed, to the next level in the decision rights table above.
- Review this matrix at retrospectives and update it to reflect any changes in team structure or process.
