# OctoAcme — Phase Handoff Checklist

## Purpose
Ensure clean, accountable transitions between project lifecycle phases. Use this checklist at each phase boundary to confirm that all required artifacts, decisions, and communication are complete before the next phase begins.

---

## Initiation → Planning Handoff

**Owner:** Project Manager  
**Participants:** Product Manager, Engineering Manager, Delivery Lead

### Checklist
- [ ] Project One-pager reviewed and approved by Product Lead and Sponsor
- [ ] Success metrics are clearly defined and measurable
- [ ] Primary stakeholders identified and communication plan drafted
- [ ] Go/no-go decision documented with rationale
- [ ] High-level timeline and key milestones shared with the team
- [ ] Initial risk list captured in the Risk Register
- [ ] Team roles confirmed (PM, PdM, Engineering Manager, Delivery Lead, QA/Test Lead, UX Designer if applicable)
- [ ] Repo or project board created and linked in the One-pager

---

## Planning → Execution Handoff

**Owner:** Delivery Lead  
**Participants:** Project Manager, Product Manager, Engineering Manager, QA/Test Lead, Developers

### Checklist
- [ ] Backlog prioritized with acceptance criteria on all top-priority items
- [ ] Definition of Done (DoD) documented and agreed by the team
- [ ] Sprint or iteration cadence confirmed and first session scheduled
- [ ] Cross-team dependencies mapped and owners assigned
- [ ] Initial test plan / QA approach drafted by QA/Test Lead
- [ ] UX designs and interaction guidance available for items in first sprint (if applicable)
- [ ] Risk Register updated with planning-phase risks
- [ ] Project board columns and workflow configured
- [ ] PR and branching conventions documented in the repo

---

## Execution → Release Handoff

**Owner:** Delivery Lead  
**Participants:** Project Manager, QA/Test Lead, Developers, Technical Writer/Documentation Owner

### Checklist
- [ ] All acceptance criteria for release scope met and verified
- [ ] CI passing — tests, lint, and security scans green
- [ ] QA/Test Lead sign-off on release confidence
- [ ] Release notes drafted (see Release Notes Template in `octoacme-release-and-deployment.md`)
- [ ] Rollback / mitigation plan documented
- [ ] Deployment window scheduled and communicated to stakeholders
- [ ] Smoke tests prepared and ready
- [ ] Process documentation updated to reflect any new patterns or changes (Technical Writer/Documentation Owner)
- [ ] Stakeholder communication drafted and ready to send

---

## Release → Retrospective Handoff

**Owner:** Project Manager  
**Participants:** Full delivery team, Product Manager

### Checklist
- [ ] Post-deploy verification complete and results shared
- [ ] Release announcement sent to stakeholders and support
- [ ] Any production incidents or rollbacks documented
- [ ] Retrospective session scheduled within one week of release
- [ ] Outstanding risk register items reviewed and closed or carried forward
- [ ] Decision log updated with key decisions made during this phase

---

## General Handoff Principles

- **Document, don't assume.** Every handoff requires written confirmation of key decisions and open items.
- **Name owners explicitly.** Each checklist item should have a named role (not just a team).
- **Escalate before the gate.** Raise blockers during execution — do not surface them for the first time at a handoff review.
- **Link artifacts.** Reference the relevant doc links (Risk Register, Decision Log, Release Notes) rather than duplicating content.
