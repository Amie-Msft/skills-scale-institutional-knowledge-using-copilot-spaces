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

## Delivery Lead

### Role Summary
Delivery Leads drive day-to-day delivery flow across teams and ensure dependencies are actively managed. They act as the operational link between planning commitments and actual execution outcomes.

### Responsibilities
- Track cross-team dependencies and unblock sequencing issues
- Maintain delivery plan health (milestones, risks, and scope changes)
- Partner with Project Managers on escalation and stakeholder readiness
- Flag capacity and sequencing risks before they impact delivery

### Goals
- Keep delivery flowing without bottlenecks
- Surface dependency and sequencing risks early
- Ensure hand-offs between phases are clean and documented

### Typical Communication
- Daily check-ins on blockers and dependency status
- Delivery health updates in weekly syncs
- Escalation flags to Project Managers when risks materialize

---

## QA / Test Lead

### Role Summary
QA / Test Leads own quality strategy, release-readiness criteria, and test coverage transparency across the delivery lifecycle.

### Responsibilities
- Define and maintain test strategy across unit, integration, and end-to-end layers
- Ensure acceptance criteria are testable and traceable
- Report quality risks and release confidence signals
- Coordinate QA activities during execution and release phases

### Goals
- Prevent defects from reaching production
- Make release confidence visible to the whole team
- Embed quality practices early in the development cycle

### Typical Communication
- Test coverage and release-readiness reports in weekly syncs
- Quality risk flags in the risk register
- Collaboration with Developers on acceptance criteria and testability

---

## Engineering Manager

### Role Summary
Engineering Managers ensure engineering capacity, technical direction, and sustainable delivery practices. They balance people, process, and technical concerns to enable the team to deliver reliably.

### Responsibilities
- Balance staffing, technical debt, and delivery commitments
- Guide architecture and engineering standards
- Coach developers and support cross-team technical decisions
- Represent engineering capacity constraints in planning

### Goals
- Sustain a productive and psychologically safe engineering team
- Align technical decisions with delivery and product goals
- Reduce long-term risk through sound engineering practices

### Typical Communication
- Weekly alignment with Project Managers on capacity and constraints
- Technical design discussions and architecture reviews
- Escalation partner for technical risks and trade-offs

---

## UX Designer / Researcher

### Role Summary
UX Designers / Researchers represent user experience quality through research-informed design decisions. They ensure solutions are usable, accessible, and validated before significant engineering effort is invested.

### Responsibilities
- Conduct lightweight user research and usability validation
- Produce design artifacts and interaction guidance
- Define UX acceptance considerations with product and engineering
- Identify and communicate UX dependencies and timelines

### Goals
- Ensure solutions are usable and meet user needs
- Reduce rework caused by late-stage UX feedback
- Make design intent clear and actionable for developers

### Typical Communication
- Design reviews and prototype walkthroughs
- UX dependency flags in planning and execution syncs
- Collaboration with Product Managers on problem framing and outcome definition

---

## Technical Writer / Documentation Owner

### Role Summary
Technical Writers / Documentation Owners maintain process and product documentation quality, structure, and consistency. They ensure that process changes are reflected in living documents and that documentation supports onboarding and day-to-day execution.

### Responsibilities
- Standardize documentation patterns, templates, and updates
- Ensure process changes are reflected in docs and linked artifacts
- Improve discoverability and onboarding through clear guidance
- Review and maintain the docs index and cross-doc consistency

### Goals
- Keep documentation accurate, discoverable, and actionable
- Reduce onboarding time for new contributors
- Ensure all personas have clear communication artifacts to work with

### Typical Communication
- Documentation review cycles after major process changes
- Coordination with Project Managers and Product Managers to capture decisions
- Feedback loops with Developers for technical accuracy

---

## Program Manager

### Role Summary
Program Managers coordinate delivery across multiple related workstreams or projects. They own milestone tracking at a program level, surface cross-project dependencies, and keep strategic stakeholders informed of overall delivery health.

### Responsibilities
- Own the cross-workstream delivery plan and milestone calendar
- Surface dependencies, sequencing risks, and resource conflicts across projects
- Communicate program-level status and risks to the Project Sponsor and senior stakeholders
- Facilitate alignment meetings across Project Managers and workstream leads
- Maintain the program roadmap and ensure planning assumptions stay current

### Decision-Making Boundaries
- **Can decide:** Sequencing priorities and dependency resolution within the program backlog
- **Escalates to Project Sponsor:** Resource trade-offs between workstreams, scope changes that affect strategic commitments, or budget decisions

### Key Interactions with Existing Roles
- **Project Managers:** Receives workstream status; helps resolve cross-PM dependencies
- **Delivery Lead:** Partners on milestone health and delivery forecasting
- **Project Sponsor:** Provides program-level status and escalates decisions requiring sponsor authority
- **Engineering Manager:** Aligns on staffing capacity across workstreams

### Handoff Points
| Phase | Program Manager Activity |
|---|---|
| Initiation | Confirms scope boundaries across workstreams; reviews dependencies with Project Sponsor |
| Planning | Consolidates workstream plans into a program roadmap; maps cross-team dependencies |
| Execution | Runs weekly cross-workstream sync; escalates blockers and milestone risks |
| Release | Coordinates release sequencing across workstreams with Release Coordinator |
| Retrospective | Captures program-level learnings and recommends process improvements |

---

## Project Sponsor / Business Owner

### Role Summary
Project Sponsors provide strategic direction, fund and approve priority decisions, and are ultimately accountable for the business outcomes delivered by the project or program. They resolve escalations that exceed the team's decision authority.

### Responsibilities
- Approve project scope, funding, and strategic priorities at initiation
- Review and validate business case and success metrics
- Resolve escalated scope, resource, and prioritization decisions
- Champion the project within the organization and remove organizational blockers
- Accept project deliverables and sign off at major milestones and release

### Decision-Making Boundaries
- **Can decide:** Strategic priorities, budget allocation, scope trade-offs, and escalated resource conflicts
- **Escalates to:** Executive stakeholders or steering committee for decisions with cross-organizational impact

### Key Interactions with Existing Roles
- **Program Manager / Project Manager:** Receives escalated risks and decisions; provides strategic direction
- **Product Manager:** Aligns on business outcomes, success metrics, and priority calls
- **Risk and Compliance Coordinator:** Reviews high-impact risk items that require sponsor-level mitigation decisions
- **Change Management Lead:** Approves organizational change strategies and major communications

### Handoff Points
| Phase | Project Sponsor Activity |
|---|---|
| Initiation | Approves project charter and initial budget; confirms strategic alignment |
| Planning | Reviews and approves milestone commitments and resource plans |
| Execution | Available for escalation; receives monthly or milestone-based status updates |
| Release | Reviews release readiness summary; provides go/no-go approval for major releases |
| Retrospective | Reviews outcomes against business goals; sponsors recommended improvements |

---

## Risk and Compliance Coordinator

### Role Summary
Risk and Compliance Coordinators maintain the risk register, drive mitigation tracking, and ensure governance and compliance expectations are met across the delivery lifecycle. They partner with teams on escalation paths and proactively surface issues before they impact delivery.

### Responsibilities
- Maintain and update the risk and issue register throughout the project lifecycle
- Facilitate risk identification sessions during planning and execution
- Track mitigation actions to completion; flag overdue items to Project Managers
- Ensure compliance requirements are identified early and integrated into delivery planning
- Define and communicate escalation criteria so teams know when to escalate

### Decision-Making Boundaries
- **Can decide:** Risk register prioritization, escalation timing, and mitigation approach recommendations
- **Escalates to Project Manager or Sponsor:** Risks where mitigation decisions exceed team authority, or compliance findings requiring organizational action

### Key Interactions with Existing Roles
- **Project Manager:** Provides risk and issue register updates; recommends escalation actions
- **Project Sponsor:** Escalates high-severity risks requiring sponsor-level decisions
- **Delivery Lead:** Flags delivery risks that affect sequencing or milestone commitments
- **QA / Test Lead:** Collaborates on quality risks and release-blocking issue tracking

### Handoff Points
| Phase | Risk and Compliance Coordinator Activity |
|---|---|
| Initiation | Captures initial risk list; identifies compliance and regulatory requirements |
| Planning | Facilitates risk assessment; ensures mitigations are assigned and prioritized |
| Execution | Reviews risk register weekly; escalates new or worsening risks promptly |
| Release | Confirms all release-blocking risks are resolved or accepted before go/no-go |
| Retrospective | Reviews risk tracking effectiveness; updates escalation guidance based on learnings |

---

## Release Coordinator

### Role Summary
Release Coordinators prepare and own release readiness checkpoints, coordinate go/no-go decisions, and align engineering, operations, and communications before and during deployments. They are the central point of contact for release logistics.

### Responsibilities
- Own the release readiness checklist and track completion against it
- Coordinate the go/no-go decision meeting with all required participants
- Schedule deployment windows and communicate them to stakeholders and on-call teams
- Ensure rollback and mitigation plans are documented and rehearsed
- Track post-deploy verification and communicate release status

### Decision-Making Boundaries
- **Can decide:** Release window scheduling, go/no-go readiness gating criteria, and post-deploy verification pass/fail
- **Escalates to Delivery Lead / Project Manager:** When a go/no-go decision is disputed or when release-blocking issues arise

### Key Interactions with Existing Roles
- **Delivery Lead:** Partners to confirm all execution exit criteria are met before release gate
- **QA / Test Lead:** Receives release confidence signal and quality sign-off
- **Engineering Manager / Developers:** Confirms deployment pipeline readiness and rollback plans
- **Change Management / Communications Lead:** Coordinates stakeholder communication timing around the release

### Handoff Points
| Phase | Release Coordinator Activity |
|---|---|
| Initiation | Identifies release type and high-level deployment constraints |
| Planning | Documents release schedule; drafts readiness criteria with QA/Test Lead and Delivery Lead |
| Execution | Monitors release-blocking items; keeps release readiness checklist current |
| Release | Runs go/no-go meeting; owns deployment coordination; confirms post-deploy verification |
| Retrospective | Captures release process improvements; updates checklists and runbooks |

---

## Change Management / Communications Lead

### Role Summary
Change Management / Communications Leads own stakeholder communication, training readiness, rollout messaging, and adoption planning for process or product changes. They ensure that affected audiences understand what is changing, why, and how to adapt.

### Responsibilities
- Develop and execute stakeholder communication plans for releases and process changes
- Produce change impact assessments to understand who is affected and how
- Coordinate training materials, enablement sessions, and adoption support
- Draft internal and external communications for major milestones and releases
- Monitor adoption signals and adjust communication or support strategies accordingly

### Decision-Making Boundaries
- **Can decide:** Communication timing, channel selection, and messaging framing for standard releases
- **Escalates to Project Sponsor:** For communications affecting external customers, regulatory audiences, or significant organizational change

### Key Interactions with Existing Roles
- **Project Sponsor:** Aligns on high-stakes communications requiring executive visibility or approval
- **Product Manager:** Collaborates on external messaging, release notes, and customer-facing content
- **Release Coordinator:** Aligns communication timing with deployment windows
- **Technical Writer / Documentation Owner:** Partners to ensure process changes are documented and accessible

### Handoff Points
| Phase | Change Management / Communications Lead Activity |
|---|---|
| Initiation | Identifies impacted stakeholder groups and preliminary change risks |
| Planning | Develops communication and adoption plan; maps training needs |
| Execution | Produces communications drafts; coordinates enablement sessions |
| Release | Sends release announcements; monitors adoption and feedback |
| Retrospective | Reviews communication effectiveness; refines templates and plans |

---

## Metrics and Process Improvement Owner

### Role Summary
Metrics and Process Improvement Owners track delivery process effectiveness, gather retrospective and operational feedback, and recommend documentation or workflow improvements. They ensure that lessons learned are systematically captured and acted upon.

### Responsibilities
- Define and track process health metrics (cycle time, defect rates, release frequency, retrospective action completion)
- Aggregate retrospective feedback and identify recurring themes or systemic issues
- Propose and pilot process improvements in collaboration with Project Managers and Delivery Leads
- Maintain a living backlog of process improvement actions with owners and timelines
- Communicate process metric trends and improvement outcomes to stakeholders

### Decision-Making Boundaries
- **Can decide:** Process improvement recommendations, metric definitions, and retrospective action prioritization
- **Escalates to Project Manager or Program Manager:** Improvements requiring resourcing, tooling investment, or changes to team-wide norms

### Key Interactions with Existing Roles
- **Project Manager:** Shares process health insights; co-owns retrospective action follow-through
- **Technical Writer / Documentation Owner:** Partners on updating process documentation to reflect improvements
- **Engineering Manager:** Collaborates on engineering process metrics (build health, PR cycle time, test reliability)
- **Delivery Lead:** Reviews delivery flow metrics to identify sequencing or dependency bottlenecks

### Handoff Points
| Phase | Metrics and Process Improvement Owner Activity |
|---|---|
| Initiation | Confirms measurement approach and baseline metrics for the project |
| Planning | Establishes reporting cadence and tooling for metric collection |
| Execution | Monitors process health indicators; flags anomalies to Project Manager |
| Release | Captures release process metrics (lead time, defect escape rate) |
| Retrospective | Facilitates metrics review; owns action backlog and tracks improvement outcomes |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

