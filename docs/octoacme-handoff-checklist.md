# OctoAcme — Phase Handoff Checklist

## Purpose
Ensure clean, accountable transitions between project lifecycle phases. Use this checklist at each phase boundary to confirm that all required artifacts, decisions, and communication are complete before the next phase begins.

---

## Initiation → Planning Handoff

**Owner:** Project Manager  
**Participants:** Product Manager, Engineering Manager, Delivery Lead, Project Sponsor, Program Manager (if applicable), Risk and Compliance Coordinator, Change Management / Communications Lead

### Checklist
- [ ] Project One-pager reviewed and approved by Product Lead and Project Sponsor
- [ ] Success metrics are clearly defined and measurable
- [ ] Primary stakeholders identified and communication plan drafted (Change Management / Communications Lead)
- [ ] Go/no-go decision to enter planning documented with rationale (Project Sponsor sign-off)
- [ ] High-level timeline and key milestones shared with the team
- [ ] Initial risk list captured in the Risk Register (Risk and Compliance Coordinator)
- [ ] Compliance and regulatory requirements identified (Risk and Compliance Coordinator)
- [ ] Team roles confirmed (PM, PdM, Engineering Manager, Delivery Lead, QA/Test Lead, UX Designer, Release Coordinator, and other applicable roles)
- [ ] Program Manager engaged if this project is part of a broader program
- [ ] Repo or project board created and linked in the One-pager

---

## Planning → Execution Handoff

**Owner:** Delivery Lead  
**Participants:** Project Manager, Product Manager, Engineering Manager, QA/Test Lead, Developers, Release Coordinator, Risk and Compliance Coordinator, Metrics and Process Improvement Owner

### Checklist
- [ ] Backlog prioritized with acceptance criteria on all top-priority items
- [ ] Definition of Done (DoD) documented and agreed by the team
- [ ] Sprint or iteration cadence confirmed and first session scheduled
- [ ] Cross-team dependencies mapped and owners assigned
- [ ] Initial test plan / QA approach drafted by QA/Test Lead
- [ ] UX designs and interaction guidance available for items in first sprint (if applicable)
- [ ] Risk Register updated with planning-phase risks (Risk and Compliance Coordinator)
- [ ] Escalation criteria documented so teams know when to involve Risk and Compliance Coordinator or Project Sponsor
- [ ] Release schedule and initial readiness criteria agreed with Release Coordinator
- [ ] Communication and adoption plan reviewed by Change Management / Communications Lead
- [ ] Process metrics baseline and reporting cadence confirmed (Metrics and Process Improvement Owner)
- [ ] Project board columns and workflow configured
- [ ] PR and branching conventions documented in the repo

---

## Execution → Release Handoff

**Owner:** Release Coordinator  
**Participants:** Delivery Lead, Project Manager, QA/Test Lead, Developers, Technical Writer/Documentation Owner, Change Management / Communications Lead, Risk and Compliance Coordinator

### Checklist
- [ ] All acceptance criteria for release scope met and verified
- [ ] CI passing — tests, lint, and security scans green
- [ ] QA/Test Lead sign-off on release confidence
- [ ] Release Readiness Checklist completed (see [Release Readiness Checklist](./octoacme-release-readiness-checklist.md))
- [ ] Release notes drafted (see Release Notes Template in `octoacme-release-and-deployment.md`)
- [ ] Rollback / mitigation plan documented and reviewed with the team (Risk and Compliance Coordinator)
- [ ] No open release-blocking risks in the risk register (Risk and Compliance Coordinator confirms)
- [ ] Deployment window scheduled and communicated to stakeholders and on-call teams
- [ ] Smoke tests prepared and ready
- [ ] Process documentation updated to reflect any new patterns or changes (Technical Writer/Documentation Owner)
- [ ] Stakeholder communication drafted and ready to send (Change Management / Communications Lead)
- [ ] Training or enablement materials ready if release introduces process or behavioral changes

---

## Release → Retrospective Handoff

**Owner:** Project Manager  
**Participants:** Full delivery team, Product Manager, Metrics and Process Improvement Owner

### Checklist
- [ ] Post-deploy verification complete and results shared (Release Coordinator)
- [ ] Release announcement sent to stakeholders and support (Change Management / Communications Lead)
- [ ] Any production incidents or rollbacks documented
- [ ] Retrospective session scheduled within one week of release
- [ ] Outstanding risk register items reviewed and closed or carried forward (Risk and Compliance Coordinator)
- [ ] Decision log updated with key decisions made during this phase
- [ ] Process metrics for this release cycle collected (Metrics and Process Improvement Owner)
- [ ] Improvement action items from previous retrospective reviewed for completion

---

## General Handoff Principles

- **Document, don't assume.** Every handoff requires written confirmation of key decisions and open items.
- **Name owners explicitly.** Each checklist item should have a named role (not just a team).
- **Escalate before the gate.** Raise blockers during execution — do not surface them for the first time at a handoff review.
- **Link artifacts.** Reference the relevant doc links (Risk Register, Decision Log, Release Notes) rather than duplicating content.
