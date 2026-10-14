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

## QA / Test Lead

### Role Summary
The QA / Test Lead leads the project’s quality strategy and coordinates validation so the team can deliver reliable software that meets agreed acceptance criteria.

### Responsibilities
- Define the test approach, coverage, and quality checks for each delivery
- Coordinate functional, integration, regression, and acceptance testing
- Identify, document, and communicate defects and quality risks
- Work with Developers to improve testability and automate appropriate checks
- Confirm that quality evidence and unresolved risks are visible before release

### Goals
- Detect important issues early and reduce escaped defects
- Make quality expectations and test results transparent
- Support releases that meet agreed acceptance and quality standards

### Typical Communication
- Test plans, test results, defect reports, and quality summaries
- Ongoing coordination with Developers and Product Managers during validation
- Release-readiness and risk updates with the Project Manager

### Decision Ownership and Interactions
- Owns the test strategy and communicates whether quality evidence meets agreed criteria; does not independently change product priorities or acceptance criteria.
- Aligns with the Product Manager on acceptance criteria and unresolved product-quality trade-offs.
- Coordinates with Developers on coverage, testability, defect triage, and fixes, handing verified results back for acceptance.
- Shares test scope and risks with the Project Manager for schedule and release coordination.
- Coordinates with the UX / Product Designer on usability checks, the Business Analyst on requirement coverage, the Technical Lead on technical test risks, and the Security / Privacy Representative on security and privacy validation.

---

## UX / Product Designer

### Role Summary
The UX / Product Designer researches user needs and shapes accessible, usable experiences that support the product’s intended outcomes.

### Responsibilities
- Conduct or coordinate user research and usability validation
- Create interaction flows, wireframes, prototypes, and design specifications
- Apply accessibility and design-system guidance
- Validate that implemented experiences reflect the approved design intent
- Surface usability findings and design trade-offs early

### Goals
- Make the product intuitive, accessible, and useful to its intended users
- Ground design decisions in user evidence and product outcomes
- Reduce rework by resolving experience questions before and during implementation

### Typical Communication
- Research findings, user journeys, prototypes, and design reviews
- Regular design collaboration with the Product Manager and Developers
- Usability findings and design dependencies shared with the Project Manager

### Decision Ownership and Interactions
- Owns design recommendations and interaction details within agreed product goals and constraints; the Product Manager owns product priorities and the Sponsor owns strategic direction.
- Partners with the Product Manager to connect user needs and research findings to product outcomes and backlog decisions.
- Hands design specifications and rationale to Developers, then collaborates with them and the Technical Lead on feasible implementation without compromising essential user needs.
- Coordinates usability validation with the QA / Test Lead and clarifies user flows and requirements with the Business Analyst.
- Raises design dependencies or scope impacts with the Project Manager for planning.

---

## Business Analyst

### Role Summary
The Business Analyst translates stakeholder and business needs into clear requirements, workflows, and acceptance criteria that the delivery team can validate.

### Responsibilities
- Elicit, analyze, document, and validate business and user requirements
- Map processes, rules, dependencies, and exceptions
- Help define testable acceptance criteria and maintain requirements traceability
- Identify ambiguity, conflicting needs, and changes in requirements
- Support impact analysis and communicate requirement decisions

### Goals
- Give the team a shared, testable understanding of the problem and expected outcomes
- Reduce ambiguity, missed requirements, and avoidable scope changes
- Ensure delivered capabilities address validated business needs

### Typical Communication
- Requirements, process maps, decision records, and acceptance criteria
- Workshops and clarification sessions with stakeholders and Product Managers
- Requirement-change and dependency updates with the Project Manager

### Decision Ownership and Interactions
- Owns requirements analysis and documentation, but does not set product priority or approve changes to product strategy.
- Works with the Product Manager to clarify intended outcomes, backlog scope, and acceptance criteria; escalates priority or value trade-offs to the Product Manager.
- Hands Developers clear requirements and answers implementation questions, and works with the QA / Test Lead to ensure requirements are testable and covered.
- Coordinates scope changes and requirement dependencies with the Project Manager.
- Clarifies technical constraints with the Technical Lead and user needs with the UX / Product Designer; brings unresolved business trade-offs to the Product Manager or Business Sponsor as appropriate.

---

## Technical Lead / Architect

### Role Summary
The Technical Lead / Architect guides technical design and engineering practices so the solution is secure, maintainable, and feasible within the project’s constraints.

### Responsibilities
- Lead architecture and technical design decisions and document significant trade-offs
- Establish or apply engineering standards and review technical consistency
- Identify technical risks, dependencies, and non-functional requirements
- Support Developers with complex implementation decisions
- Coordinate technical input to test, security, and operational readiness

### Goals
- Deliver a coherent, maintainable solution that meets functional and non-functional needs
- Resolve technical risks and dependencies early
- Enable Developers to implement consistently and safely

### Typical Communication
- Architecture diagrams, technical decision records, and design reviews
- Technical planning and implementation discussions with Developers
- Risk and dependency updates with the Project Manager and Product Manager

### Decision Ownership and Interactions
- Owns or facilitates technical design decisions within agreed product goals, security requirements, and delivery constraints; does not set business priorities or make delivery commitments on behalf of the Project Manager.
- Partners with Developers on implementation, code quality, and technical trade-offs, and explains material constraints to the Product Manager.
- Shares estimates, dependencies, and technical risks with the Project Manager for planning and escalation.
- Coordinates testability with the QA / Test Lead, operational requirements with Operations / Site Reliability Engineering, and security controls with the Security / Privacy Representative.
- Consults the UX / Product Designer and Business Analyst when technical choices affect user experience or requirements.

---

## Operations / Site Reliability Engineer

### Role Summary
The Operations / Site Reliability Engineer (SRE) helps ensure the service can be deployed, monitored, supported, and operated reliably in production.

### Responsibilities
- Define or advise on reliability, availability, capacity, and operational requirements
- Plan monitoring, alerting, logging, backup, and recovery needs with the team
- Review deployment and rollback approaches and operational runbooks
- Identify production risks and support incident readiness and response planning
- Validate operational readiness and communicate remaining risks before release

### Goals
- Make releases safe and services observable and supportable
- Meet agreed reliability and operational expectations
- Reduce avoidable incidents and shorten recovery time

### Typical Communication
- Operational requirements, SLOs, dashboards, runbooks, and readiness reviews
- Deployment and rollback coordination with Developers and the Technical Lead
- Readiness and production-risk updates with the Project Manager

### Decision Ownership and Interactions
- Owns operational guidance and readiness assessment for services within their remit, including raising unresolved risks; product scope and delivery timing remain with the Product Manager and Project Manager respectively.
- Partners with Developers and the Technical Lead to design monitoring, deployment, rollback, and recovery, handing operational requirements and runbooks to the team before release.
- Coordinates release timing, dependencies, and readiness risks with the Project Manager and clarifies customer impact with the Product Manager.
- Aligns service-level and operational validation with the QA / Test Lead and applicable security and privacy controls with the Security / Privacy Representative.

---

## Security / Privacy Representative

### Role Summary
The Security / Privacy Representative advises the team on security, privacy, and compliance needs and helps ensure risks and required controls are addressed throughout delivery.

### Responsibilities
- Identify applicable security, privacy, and data-handling requirements
- Assess risks and recommend proportionate controls and mitigations
- Review designs and implementation plans for relevant risks
- Coordinate security and privacy testing or specialist reviews
- Document findings, required actions, exceptions, and residual risks

### Goals
- Protect users, data, and services from unacceptable security and privacy risks
- Make required controls and risk decisions clear early enough to act
- Ensure unresolved findings are visible to accountable decision-makers

### Typical Communication
- Threat and privacy assessments, control requirements, and review findings
- Direct review discussions with Developers and the Technical Lead
- Risk escalation and remediation tracking with the Project Manager

### Decision Ownership and Interactions
- Owns security and privacy advice and communicates control requirements under applicable policy; escalates unacceptable or unresolved risks to the accountable authority rather than silently accepting them. Product scope and delivery sequencing remain with the Product Manager and Project Manager.
- Works with Developers and the Technical Lead to design and implement controls, and with the QA / Test Lead to plan security and privacy validation.
- Gives the Project Manager clear findings, owners, and due dates for risk tracking and escalation.
- Advises the Product Manager on user and product impacts, and coordinates data and retention requirements with the Business Analyst and operational controls with Operations / SRE.

---

## Business Sponsor / Decision Maker

### Role Summary
The Business Sponsor / Decision Maker provides executive sponsorship, ensures the project remains aligned with business strategy, and makes or escalates decisions that exceed the delivery team’s authority.

### Responsibilities
- Confirm strategic outcomes, sponsorship, and appropriate business support
- Resolve escalated priority, funding, scope, or cross-organizational trade-offs
- Make timely decisions when delegated ownership or governance requires sponsor approval
- Review progress and outcomes against the business case
- Support stakeholder alignment and remove organizational blockers

### Goals
- Achieve the intended strategic and business outcomes
- Ensure important decisions and escalations have a clear owner
- Provide the team with timely direction and support

### Typical Communication
- Sponsor checkpoints, decision requests, and concise status or outcome briefings
- Escalations and delivery-impact updates with the Project Manager
- Strategic outcome and priority alignment with the Product Manager

### Decision Ownership and Interactions
- Owns strategic sponsorship and decisions explicitly delegated to the sponsor, such as funding or major business trade-offs; does not direct day-to-day delivery or replace the Product Manager’s backlog prioritization.
- Aligns outcomes and strategic priorities with the Product Manager, who translates them into product direction and backlog decisions.
- Receives delivery status, risks, and decision requests from the Project Manager, and returns timely decisions or escalations to the Project Manager for coordination.
- Provides business context to Developers through the Product Manager and appropriate delivery channels rather than assigning implementation work directly.
- Consults relevant roles, such as the Business Analyst on business impact and the Security / Privacy Representative on risk, before making decisions in those areas.

---

## Adapting Roles to Team Size

In smaller teams, one person may cover multiple roles or a role may be shared across teams. Adapt assignments to the project’s needs, but name an accountable owner for each responsibility and decision area, make any conflicts of interest visible, and keep handoffs clear. Combining roles does not remove the need for the relevant expertise, review, or approval.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
