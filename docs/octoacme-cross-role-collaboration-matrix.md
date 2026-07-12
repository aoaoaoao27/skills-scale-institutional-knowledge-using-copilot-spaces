# OctoAcme Cross-Role Collaboration Matrix

This document provides a lightweight RACI-style matrix for key delivery activities across all OctoAcme personas. It is intended to clarify ownership, reduce ambiguity in handoffs, and make accountability visible at each stage of the project lifecycle.

---

## How to Use This Matrix

| Symbol | Meaning |
|--------|---------|
| **R** | **Responsible** — does the work |
| **A** | **Accountable** — owns the outcome; final decision authority |
| **C** | **Consulted** — provides input before or during; two-way communication |
| **I** | **Informed** — kept up to date; one-way communication |

**Guidelines for teams:**

- Review this matrix at project kickoff to confirm role assignments for the current project.
- Update role assignments when the project team composition changes (e.g., no dedicated QA — a Developer may take on **R** for acceptance validation).
- Reference this matrix during retrospectives to identify recurring accountability gaps or handoff friction.
- If a cell is blank, that role has no expected involvement for that activity — but teams can add entries as needed.

---

## Matrix

| Activity | Developer | Product Manager | Project Manager | Engineering Manager | Designer / UX Researcher | QA Engineer / Test Lead | DevOps / SRE | Security / Compliance Lead | Customer Support / Success | Data Analyst / Analytics Lead |
|---|---|---|---|---|---|---|---|---|---|---|
| **Planning** | C | A | R | C | C | C | C | C | I | C |
| **Acceptance Definition** | C | A | I | I | R | C | I | C | C | C |
| **Release Readiness** | R | C | A | C | I | R | R | C | R | I |
| **Incident Response** | R | I | A | C | — | C | R | C | I | C |
| **Retrospective Follow-Through** | R | C | A | C | C | C | C | C | C | C |

---

## Activity Descriptions

### Planning
Converts approved work into a prioritized backlog with milestones, dependencies, capacity estimates, and a clear Definition of Done.

- **Project Manager (A)**: sets the plan structure, timeline, and tracks risks.
- **Product Manager (A)**: owns prioritization decisions and scope boundaries.
- **Developer (C)**: provides effort estimates and flags technical risks.
- **Engineering Manager (C)**: validates capacity and surface staffing constraints.
- **Designer / UX Researcher (C)**: flags design dependencies and discovery needs.
- **QA Engineer / Test Lead (C)**: identifies test coverage needs and quality milestones.
- **DevOps / SRE (C)**: highlights deployment and infrastructure constraints.
- **Security / Compliance Lead (C)**: surfaces any compliance or threat model requirements.
- **Data Analyst (C)**: proposes success metric instrumentation needs.
- **Customer Support / Success (I)**: informed of upcoming scope that may affect customers.

---

### Acceptance Definition
Creates clear, testable acceptance criteria and a Definition of Done for each work item before development begins.

- **Product Manager (A)**: owns the acceptance criteria and outcome expectations.
- **Designer / UX Researcher (R)**: authors UX and accessibility acceptance inputs.
- **Developer (C)**: reviews for technical feasibility and implementation clarity.
- **QA Engineer / Test Lead (C)**: reviews for testability and validation approach.
- **Security / Compliance Lead (C)**: adds security or compliance acceptance conditions where applicable.
- **Customer Support / Success (C)**: contributes customer usability expectations.
- **Data Analyst (C)**: ensures measurability and instrumentation requirements are captured.

---

### Release Readiness
Confirms that code, quality, operational, communication, and compliance requirements are met before a release proceeds.

- **Project Manager (A)**: facilitates the go/no-go decision and tracks readiness status.
- **Developer (R)**: completes implementation, resolves open defects, and verifies deployability.
- **QA Engineer / Test Lead (R)**: provides final quality assessment and go/no-go recommendation.
- **DevOps / SRE (R)**: validates deployment plan, rollback readiness, and monitoring coverage.
- **Customer Support / Success (R)**: confirms support enablement materials and known issues documentation are ready.
- **Product Manager (C)**: validates that acceptance criteria are met and business value is deliverable.
- **Engineering Manager (C)**: confirms team readiness and capacity for post-release support.
- **Security / Compliance Lead (C)**: signs off on security review or risk acceptance where applicable.

---

### Incident Response
Coordinates detection, triage, remediation, and communication when a production incident occurs.

- **Project Manager (A)**: coordinates response, stakeholder communication, and timeline.
- **Developer (R)**: investigates, implements, and deploys fixes.
- **DevOps / SRE (R)**: leads triage, monitors systems, and manages rollback or mitigation.
- **Engineering Manager (C)**: provides escalation support and resourcing if needed.
- **QA Engineer / Test Lead (C)**: validates fix quality before re-deployment.
- **Security / Compliance Lead (C)**: advises if the incident has security or compliance implications.
- **Data Analyst (C)**: provides metrics to assess incident impact and resolution effectiveness.
- **Product Manager (I)**: informed of impact, timeline, and customer-facing effects.
- **Customer Support / Success (I)**: informed early to manage customer communications.

---

### Retrospective Follow-Through
Ensures that retrospective action items are assigned, tracked, and completed — not lost after the session ends.

- **Project Manager (A)**: owns the action log and tracks completion across the team.
- **Developer (R)**: implements or leads engineering improvement actions.
- **Engineering Manager (C)**: supports systemic changes and removes blockers to improvement actions.
- **Product Manager (C)**: evaluates process changes that affect planning or prioritization.
- **Designer / UX Researcher (C)**: contributes to UX or discovery process improvements.
- **QA Engineer / Test Lead (C)**: drives quality process improvements and test coverage gaps.
- **DevOps / SRE (C)**: acts on reliability, pipeline, or deployment retrospective items.
- **Security / Compliance Lead (C)**: follows through on security process findings.
- **Customer Support / Success (C)**: surfaces customer-reported patterns for team action.
- **Data Analyst (C)**: supports measurement of whether process improvements are working.

---

## Updating This Matrix

When adapting this matrix for a specific project:

1. Copy this file into the project's documentation folder.
2. At kickoff, review each activity row with the team and confirm or adjust role assignments.
3. Note any deviations (e.g., "No dedicated QA — Developer takes R for release readiness validation") in a comment below the relevant row.
4. Revisit at retrospectives and update if accountability gaps or handoff friction were observed.
