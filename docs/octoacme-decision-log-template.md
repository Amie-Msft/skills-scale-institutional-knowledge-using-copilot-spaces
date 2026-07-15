# OctoAcme — Decision Log Template

## Purpose
Track key decisions made during a project — what was decided, who made the call, why, and what alternatives were considered. A maintained decision log reduces re-litigation of settled questions and helps new contributors understand project context quickly.

## When to use
- Any significant architectural, process, or product decision
- Trade-off decisions where multiple options were considered
- Decisions that affect scope, timeline, or team responsibilities
- Choices that stakeholders need visibility into

---

## How to use this template

Copy the **Decision Record** block below for each decision. Add new records in reverse-chronological order (newest first). Store this file in the `docs/` folder and link it from the project README or relevant process docs.

---

## Decision Record

| Field | Details |
|---|---|
| **Decision ID** | DEC-NNN |
| **Date** | YYYY-MM-DD |
| **Status** | Proposed / Accepted / Deprecated / Superseded by DEC-NNN |
| **Owner** | Name / Role |
| **Participants** | Comma-separated list of names or roles |

### Context
_Describe the situation, problem, or question that prompted this decision. Include relevant constraints or pressures._

### Decision
_State clearly what was decided._

### Rationale
_Explain why this option was chosen over alternatives._

### Alternatives Considered

| Option | Pros | Cons | Reason Rejected |
|---|---|---|---|
| Option A | | | |
| Option B | | | |

### Consequences
_Describe the expected outcomes, trade-offs, or follow-up actions resulting from this decision._

### Related Links
- Risk Register entry: _(link or ID)_
- Related issue / PR: _(link)_
- Relevant process doc: _(link)_

---

## Example

| Field | Details |
|---|---|
| **Decision ID** | DEC-001 |
| **Date** | 2026-07-01 |
| **Status** | Accepted |
| **Owner** | Project Manager |
| **Participants** | Engineering Manager, Product Manager, QA/Test Lead |

### Context
The team needed to decide whether to run QA sign-off as a blocking gate before production deployment or to deploy to staging first and run QA in parallel with limited production traffic.

### Decision
QA sign-off is a blocking pre-production gate. No release proceeds without explicit QA/Test Lead approval.

### Rationale
Parallel staging/production QA introduces customer-facing risk that is inconsistent with our quality commitments. The release cadence allows enough time for sequential QA without impacting timelines.

### Alternatives Considered

| Option | Pros | Cons | Reason Rejected |
|---|---|---|---|
| Parallel staging + prod QA | Faster release | Customer-facing risk | Risk too high |
| Full automated QA gate only | No manual overhead | Gaps in coverage | Coverage not yet sufficient |

### Consequences
- QA/Test Lead is a required approver in the deployment checklist.
- Release timeline must include a dedicated QA window of at least two business days.
- Teams must flag QA readiness risks during execution sync, not at the release gate.

### Related Links
- Release checklist: `docs/octoacme-release-and-deployment.md`
- Risk Register: _(project risk register link)_
