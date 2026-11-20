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

## Product Owners

### Role Summary
Product Owners translate product direction into an actionable, ordered backlog and clarify what is ready for delivery. Where a Product Manager is present, the Product Owner focuses on day-to-day backlog decisions in alignment with the Product Manager’s strategy and priorities.

### Responsibilities
- Refine backlog items with clear descriptions and acceptance criteria
- Answer delivery-team questions about intended behavior and scope
- Order backlog work within the priorities and outcomes agreed with the Product Manager
- Review completed work against acceptance criteria and provide acceptance feedback
- Surface scope questions or priority conflicts to the Product Manager

### Decision Boundaries
- Make day-to-day backlog and acceptance decisions within agreed product direction
- Partner with the Product Manager on priority or scope changes that affect outcomes, roadmap, or commitments

### Typical Communication and Interactions
- Work with Product Managers to connect backlog decisions to product goals
- Collaborate with Developers and QA/Test Leads to clarify requirements and acceptance criteria
- Coordinate with the Project Manager on readiness, dependencies, and delivery status

---

## UX/UI Designers and User Researchers

### Role Summary
UX/UI Designers and User Researchers help teams understand user needs and shape usable, accessible solutions. One person may perform both functions, depending on the project.

### Responsibilities
- Plan or conduct user research and synthesize findings
- Create user flows, wireframes, prototypes, and design specifications as appropriate
- Validate design concepts with users and stakeholders
- Identify usability and accessibility considerations
- Communicate design intent and research evidence to the delivery team

### Decision Boundaries
- Recommend design approaches based on user evidence and design standards
- Partner with the Product Manager or Product Owner when research findings imply changes to product scope or priorities

### Typical Communication and Interactions
- Work with Product Managers and Product Owners to connect user needs to product goals and acceptance criteria
- Collaborate with Developers and QA/Test Leads on implementation details and usability validation
- Share research plans, findings, and design handoffs with the Project Manager for scheduling and dependency coordination

---

## Technical Leads and Architects

### Role Summary
Technical Leads and Architects guide technical design and help ensure that solutions are secure, maintainable, and consistent with the system architecture. The Technical Lead may work directly with the team; an Architect may focus on broader system-wide decisions.

### Responsibilities
- Facilitate technical design and document significant decisions
- Identify technical risks, constraints, and integration dependencies
- Help Developers break down work and evaluate implementation trade-offs
- Promote engineering standards, security, reliability, and maintainability
- Escalate decisions that affect other teams or system architecture

### Decision Boundaries
- Guide technical decisions within the agreed architecture and engineering standards
- Involve relevant teams or decision-makers when changes have cross-system impact or require product, schedule, or resource trade-offs

### Typical Communication and Interactions
- Partner with Developers on design, implementation, and code reviews
- Explain technical options and trade-offs to Product Managers and Product Owners
- Coordinate technical dependencies, risks, and estimates with the Project Manager
- Collaborate with QA/Test Leads and Operations/SRE on testability, observability, and operational readiness

---

## QA/Test Leads

### Role Summary
QA/Test Leads coordinate quality strategy and validation so that delivery meets agreed acceptance criteria and quality standards. Testing may be a dedicated role or a shared team responsibility.

### Responsibilities
- Define a proportionate test approach with the delivery team
- Identify test coverage needs, environments, and data dependencies
- Coordinate testing of requirements, integrations, and critical user flows
- Report defects and quality risks with enough context for triage
- Support release readiness by summarizing test outcomes and remaining concerns

### Decision Boundaries
- Recommend whether quality evidence is sufficient for acceptance or release
- Escalate unresolved defects or quality risks to the Product Owner or Product Manager and Project Manager; release decisions follow the team’s agreed policy

### Typical Communication and Interactions
- Work with Product Owners to make acceptance criteria testable
- Collaborate with Developers on unit, integration, and end-to-end testing
- Coordinate test timing and dependencies with the Project Manager
- Partner with Operations/SRE or Release Managers on smoke tests and post-deployment verification

---

## Delivery and Program Coordinators

### Role Summary
Delivery and Program Coordinators help coordinate work across teams or related projects. They support Project Managers by making cross-team plans, dependencies, and delivery status visible; they do not replace the Project Manager’s ownership of an individual project plan unless explicitly agreed.

### Responsibilities
- Track cross-team milestones, dependencies, and handoffs
- Gather status and highlight schedule conflicts or delivery risks
- Facilitate coordination across teams and maintain shared delivery information
- Route unresolved dependency or resource issues to the appropriate Project Managers or sponsors

### Decision Boundaries
- Coordinate agreed plans and surface conflicts; changes to project scope, priority, or commitments remain with the accountable product and project decision-makers

### Typical Communication and Interactions
- Partner with Project Managers to keep plans, risks, and status aligned
- Coordinate dependency owners and timelines across teams
- Share milestone impacts with Product Managers and relevant stakeholders
- Work with Technical Leads or Architects when dependencies involve system design or integration

---

## Operations/SRE and Release Managers

### Role Summary
Operations/SRE and Release Managers help ensure services are ready to operate and that releases are deployed and verified safely. These responsibilities may be held by one person, shared by a team, or handled through established operational processes.

### Responsibilities
- Define or advise on operational readiness, reliability, monitoring, and alerting needs
- Review deployment, rollback, and mitigation plans
- Coordinate release windows and deployment handoffs where needed
- Support incident response and communicate operational risks
- Verify service health after deployment and capture follow-up actions

### Decision Boundaries
- Advise on operational readiness and raise reliability or safety concerns
- Follow established incident and release authority for pausing, rolling back, or proceeding with a deployment

### Typical Communication and Interactions
- Collaborate with Developers and Technical Leads on observability, reliability, and deployability
- Work with QA/Test Leads on smoke tests and post-deployment checks
- Coordinate release timing, status, and escalations with the Project Manager
- Align release scope and customer impact with the Product Manager or Product Owner

---

## Adapting Roles to Project Context

Not every project needs a separate person for each persona. On smaller projects, one person may hold multiple roles, provided responsibilities and decision authority remain clear and conflicts of interest are addressed. Teams should identify who owns each responsibility, decision, and handoff during initiation or planning, and revisit assignments when project scope or risk changes.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

