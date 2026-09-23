# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Roles may be mandatory or situational depending on project size, risk, regulatory needs, and delivery model. The Project Manager coordinates the lifecycle and delivery system; the Product Manager owns product outcomes and priorities; and delivery team members build, validate, and release the solution.

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
- Weekly alignment with Project Managers and engineering leads
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

## Additional Personas and Roles

The following roles are assigned when their expertise or decision authority is needed. A person may hold more than one situational role on a small project, but decision conflicts and accountability must be made explicit during initiation.

### Executive Sponsor (Situational)

**Responsibilities**
- Own strategic sponsorship and secure organizational support, funding, and resources
- Make or escalate high-impact decisions outside the project team's authority
- Resolve executive-level priority, scope, or capacity conflicts
- Receive delivery, outcome, and risk updates from the Project Manager

**Interactions and decision rights**
- Partners with the Product Manager to confirm strategic outcomes and success measures
- Works with the Project Manager on escalated risks, major trade-offs, and changes to commitments
- Supports the Technical Lead and delivery team by removing organizational impediments rather than directing implementation
- Approves or escalates changes that materially affect strategy, funding, scope, or organizational risk

### Business Owner or Business Stakeholder (Situational)

**Responsibilities**
- Represent operational goals, business constraints, and process impacts
- Validate that the project addresses business needs
- Provide timely decisions, feedback, and acceptance input
- Identify affected business groups and adoption needs

**Interactions and decision rights**
- Works with the Product Manager on value, priorities, and outcome validation
- Works with the Project Manager on scope, readiness, dependencies, and acceptance planning
- Consults the Technical Lead and delivery team when business constraints affect feasibility
- Owns business acceptance recommendations; unresolved conflicts are escalated through the Project Manager to the Executive Sponsor or appropriate governance body

### Technical Lead or Architect (Situational, mandatory for material technical change)

**Responsibilities**
- Own technical direction, architecture decisions, and alignment with engineering standards
- Identify technical dependencies, constraints, risks, and required sequencing
- Guide technical estimates, design reviews, and non-functional requirements
- Ensure the solution is maintainable, secure, observable, and feasible to operate

**Interactions and decision rights**
- Collaborates with the Project Manager on dependencies, estimates, risks, and delivery sequencing
- Partners with the Product Manager to explain technical trade-offs that affect scope, value, or timing
- Guides Developers, QA, Security and Privacy, and Release or Operations contributors on implementation decisions
- Owns technical design decisions within agreed standards; escalates decisions affecting major scope, risk, or funding to the Project Manager and Executive Sponsor

### UX or Research Lead (Situational, mandatory for user-facing or experience-critical work)

**Responsibilities**
- Represent user needs, usability, accessibility, and evidence from research
- Plan discovery, user research, journey mapping, and usability validation
- Produce or review designs and define experience-related acceptance criteria
- Surface unmet needs and usability risks before release

**Interactions and decision rights**
- Works with the Product Manager on outcomes, user problems, and backlog priorities
- Coordinates with the Project Manager on research milestones, dependencies, and stakeholder participation
- Collaborates with Developers and QA to make designs testable and accessible
- Recommends experience decisions based on evidence; the Product Manager decides priority and outcome trade-offs when constraints arise

### Quality Assurance or Test Lead (Situational, mandatory for significant or high-risk releases)

**Responsibilities**
- Define the test strategy, coverage expectations, environments, and validation approach
- Coordinate functional, integration, regression, performance, and acceptance testing as appropriate
- Track defects and quality risks and communicate release confidence
- Confirm evidence for quality gates and readiness decisions

**Interactions and decision rights**
- Works with the Technical Lead and Developers throughout design and execution to prevent and detect defects early
- Works with the Product Manager and Business Owner on acceptance criteria and business validation
- Reports test status, residual quality risks, and evidence to the Project Manager
- Owns the quality assessment and recommends whether criteria are met; release go/no-go authority follows the agreed release governance rather than being assumed by QA alone

### Security and Privacy Partner (Situational, mandatory when data, regulated requirements, or material security risk is involved)

**Responsibilities**
- Identify security, privacy, compliance, and data-protection requirements
- Review threat, privacy, and compliance risks and recommend controls
- Advise on required approvals, evidence, and release gates
- Support incident readiness and security or privacy risk escalation

**Interactions and decision rights**
- Engages early with the Product Manager, Technical Lead, and Project Manager so compliance work is planned
- Collaborates with Developers and QA on secure design, testing, and verification of controls
- Coordinates with the Release or Operations Lead on production access, monitoring, and response readiness
- Owns specialist advice and approval recommendations; unresolved material risks are escalated by the Project Manager to the Executive Sponsor or designated governance authority

### Release or Operations Lead (Situational, mandatory for production deployments)

**Responsibilities**
- Coordinate deployment readiness, operational procedures, monitoring, and support handoffs
- Define or validate rollback, recovery, and communication plans
- Confirm operational capacity, observability, runbooks, and on-call readiness
- Capture production outcomes and operational follow-up actions

**Interactions and decision rights**
- Partners with the Project Manager on the release plan, milestones, dependencies, and communications
- Works with the Technical Lead, Developers, and QA on deployment validation and go/no-go criteria
- Coordinates with Security and Privacy on production controls and with the Business Owner on operational readiness
- Owns operational readiness recommendations and deployment execution within the approved plan; material release risks are escalated to the Project Manager and Executive Sponsor

### Customer or End-User Representative (Situational)

**Responsibilities**
- Provide direct feedback on needs, usability, accessibility, and acceptance
- Participate in discovery, demos, pilots, validation, or user acceptance activities as appropriate
- Explain real-world workflows, constraints, and adoption risks

**Interactions and decision rights**
- Collaborates with the Product Manager to validate customer value and outcome measures
- Works with the UX or Research Lead on evidence and usability feedback
- Provides acceptance input to the Business Owner and Product Manager and communicates findings to the delivery team through agreed channels
- Advises on user needs but does not unilaterally change scope; prioritization remains with the Product Manager

### Change and Communications Lead (Situational, mandatory for material organizational change)

**Responsibilities**
- Coordinate stakeholder messaging, readiness activities, training, and adoption support
- Maintain a communications and change-readiness plan aligned to project milestones
- Identify stakeholder impacts and adoption risks
- Track feedback and ensure important changes reach affected audiences

**Interactions and decision rights**
- Works with the Project Manager and Product Manager to align communications with milestones, risks, releases, and scope changes
- Partners with the Business Owner and Customer or End-User Representative on readiness, training, and feedback
- Coordinates with the Release or Operations Lead so launch communications match operational readiness and support plans
- Recommends communications and adoption actions; the Project Manager coordinates timing and the Product Manager confirms product messaging and priority

---

## Lifecycle Ownership and Escalation

- **Initiation:** The Executive Sponsor confirms strategic sponsorship; the Product Manager defines intended outcomes; the Project Manager establishes governance; Business, Technical, UX, Security, and other situational roles identify constraints and required involvement.
- **Planning:** The Project Manager owns the integrated plan, risks, dependencies, and communication cadence. The Product Manager owns priority and product decisions. Technical, UX, QA, Security, and Operations leads provide specialist estimates, acceptance criteria, controls, and readiness work.
- **Execution and tracking:** Developers and other delivery team members implement and validate the work. Specialist leads manage their quality, technical, experience, security, or operational concerns. The Project Manager coordinates status, risks, decisions, and escalations.
- **Release:** The QA Lead reports validation evidence, the Release or Operations Lead confirms operational readiness, the Security and Privacy Partner confirms required controls, and the Product Manager and Business Owner confirm value and acceptance input. The agreed governance authority makes the final go/no-go decision.
- **Retrospective and improvement:** The Project Manager facilitates the review. All participating roles contribute evidence and actions; accountable owners are assigned follow-ups and the Product Manager or Executive Sponsor confirms priority when improvements compete with delivery work.

When a decision exceeds a role's authority, the role owner records the decision and impact, informs the Project Manager, and escalates through the agreed governance path. The Project Manager should make ownership, decision rights, handoffs, and escalation contacts visible in the project plan or decision log.

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Tailor the role set to project size and risk, while keeping accountability and escalation paths explicit.
