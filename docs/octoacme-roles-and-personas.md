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

## Engineering Manager

### Role Summary
Engineering Managers lead engineering execution capacity, technical staffing, and delivery health for the team. They bridge individual contributor development and organizational delivery commitments.

### Responsibilities
- Ensure team capacity planning and sustainable workload
- Coach developers and support technical decision quality
- Partner with Product Managers and Project Managers on scope-risk tradeoffs
- Remove systemic blockers and escalate staffing or skill gaps
- Own engineering hiring, onboarding, and performance for their team

### Goals
- Maintain a healthy, high-performing engineering team
- Enable predictable delivery without burning out contributors
- Continuously improve engineering practices and standards

### Typical Communication
- 1:1s with direct reports and skip-level check-ins
- Capacity and resourcing discussions with Project Managers
- Engineering standards and technical strategy conversations with staff engineers

### Interactions with Existing Roles
- **Project Managers**: aligns on timelines, dependency risk, and escalation paths for delivery blockers
- **Product Managers**: validates scope prioritization feasibility and flags tradeoff risks
- **Developers**: provides mentorship, removes blockers, and upholds delivery standards

---

## Designer / UX Researcher

### Role Summary
Designers and UX Researchers ensure solutions are usable, accessible, and validated against real user needs before and during implementation.

### Responsibilities
- Produce interaction designs, wireframes, and design artifacts for implementation
- Validate usability through lightweight research or prototype testing
- Define UX acceptance inputs and accessibility considerations
- Maintain a design system or component standards where applicable

### Goals
- Ensure features are intuitive and meet real user needs
- Reduce implementation rework caused by late-breaking UX changes
- Raise team awareness of accessibility and inclusive design

### Typical Communication
- Design reviews and critique sessions
- Figma or design tool annotations and handoff notes
- UX research summary reports tied to roadmap items

### Interactions with Existing Roles
- **Product Managers**: collaborates on problem framing, user outcomes, and feature scope
- **Developers**: partners early to ensure designs are implementable and handoff notes are clear
- **Project Managers**: surfaces design dependencies and readiness risks before development starts

---

## QA Engineer / Test Lead

### Role Summary
QA Engineers and Test Leads drive test strategy and quality gates across feature and release cycles. They are responsible for making release readiness signals visible and actionable.

### Responsibilities
- Define risk-based test plans and acceptance validation approaches
- Maintain regression and smoke test coverage expectations
- Report quality trends, defect metrics, and release readiness signals
- Collaborate on Definition of Done and acceptance criteria quality

### Goals
- Prevent defects from reaching production
- Shorten feedback loops between development and quality validation
- Increase team confidence in release readiness

### Typical Communication
- Test plans and test summary reports
- Bug reports and severity triage notes
- Go/no-go quality assessments before releases

### Interactions with Existing Roles
- **Developers**: improves testability, defines defect prevention standards, and clarifies acceptance criteria
- **Project Managers**: provides quality milestone status and participates in go/no-go decisions
- **Product Managers**: aligns on acceptance quality thresholds and user-facing defect tolerance

---

## DevOps / SRE

### Role Summary
DevOps Engineers and Site Reliability Engineers (SREs) own deployment reliability, observability, and production readiness practices. They ensure releases can be deployed safely and rolled back quickly if needed.

### Responsibilities
- Maintain CI/CD pipeline health and deployment safeguards
- Define operational readiness checks and rollback procedures
- Monitor reliability signals: latency, error rates, and availability
- Drive incident response tooling and runbook documentation

### Goals
- Achieve fast, safe, and repeatable deployments
- Minimize mean time to detection (MTTD) and resolution (MTTR) for production incidents
- Reduce manual toil through automation

### Typical Communication
- Deployment runbooks and operational readiness checklists
- On-call handoffs and incident postmortems
- SLO/SLI dashboards and reliability reports

### Interactions with Existing Roles
- **Developers**: provides build and deploy automation support; advises on observability and testability in production
- **Project Managers**: aligns on release windows, deployment plans, and rollback readiness
- **Product Managers**: informs on operational constraints, reliability tradeoffs, and capacity considerations

---

## Security / Compliance Lead

### Role Summary
Security and Compliance Leads embed security and compliance expectations into delivery workflows. They reduce risk by making security a standard part of the project lifecycle rather than a late-stage gate.

### Responsibilities
- Define security review requirements and threat or risk checks for new features
- Track remediation priorities and timelines for high-risk findings
- Advise on policy, regulatory, or data-handling controls where applicable
- Support security awareness and secure development practices

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure the team meets applicable compliance and regulatory requirements
- Reduce friction by integrating security early in the delivery process

### Typical Communication
- Security review checkpoints and threat model summaries
- Remediation tracking and risk acceptance documentation
- Policy guidance and compliance status updates

### Interactions with Existing Roles
- **Developers**: partners on secure implementation practices, code review standards, and dependency hygiene
- **Project Managers**: coordinates risk escalation paths, mitigation tracking, and compliance milestones
- **Product Managers**: helps evaluate security impact of scope decisions and data-handling changes

---

## Customer Support / Success Representative

### Role Summary
Customer Support and Success Representatives bring customer impact, adoption insights, and support readiness into delivery planning. They ensure that releases are communicated clearly and that support teams are prepared to help users.

### Responsibilities
- Provide recurring customer pain points and usage insights to inform prioritization
- Prepare support enablement for releases: known issues, FAQs, troubleshooting notes
- Capture and relay post-release customer feedback loops
- Represent the customer voice in planning and retrospective discussions

### Goals
- Reduce support escalations by improving release quality and communication
- Ensure customers and support staff are not surprised by changes
- Close the loop between customer feedback and product iteration

### Typical Communication
- Release notes and customer-facing communication drafts
- Support readiness checklists before go-live
- Customer feedback summaries and issue trend reports

### Interactions with Existing Roles
- **Product Managers**: informs customer-value priorities and surfaces unmet needs from support data
- **Project Managers**: coordinates release communication plans and support readiness timing
- **Developers**: feeds issue and bug trends back to guide prioritization and quality improvement

---

## Data Analyst / Analytics Lead

### Role Summary
Data Analysts and Analytics Leads ensure outcome measurement and instrumentation quality so teams can make data-informed decisions throughout the delivery lifecycle.

### Responsibilities
- Define and validate success metrics instrumentation for new features
- Build and maintain dashboards tied to project and product outcomes
- Provide analysis and insights to support iteration and retrospective decisions
- Identify data quality issues and track instrumentation coverage

### Goals
- Ensure every significant release has measurable success criteria
- Give teams reliable, timely data to evaluate impact
- Support a culture of evidence-based decision-making

### Typical Communication
- Metrics definition docs and instrumentation specs
- Dashboard links and outcome summaries at retrospectives
- Ad-hoc analysis reports for key decisions

### Interactions with Existing Roles
- **Product Managers**: partners to evaluate feature impact and validate success metric definitions
- **Developers**: works on event tracking quality, data pipeline reliability, and instrumentation coverage
- **Project Managers**: provides status metrics, progress indicators, and risk signals for reporting

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [Cross-Role Collaboration Matrix](./octoacme-cross-role-collaboration-matrix.md) for a lightweight RACI covering key delivery activities across all personas.

