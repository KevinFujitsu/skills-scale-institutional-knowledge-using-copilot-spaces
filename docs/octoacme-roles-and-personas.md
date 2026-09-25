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

## Security & Compliance Leads

### Role Summary
Security and Compliance Leads ensure that project decisions, implementation practices, and releases address applicable security, privacy, regulatory, and compliance requirements.

### Responsibilities
- Identify security, privacy, and compliance requirements during initiation and planning
- Review designs, controls, data handling, and release plans for material risks
- Define security checkpoints, evidence requirements, and exception processes
- Coordinate security assessments and track remediation work
- Escalate unresolved or business-impacting risks through the documented escalation path

### Interaction with Existing Roles
- Partner with Product Managers to translate customer, privacy, and regulatory needs into acceptance criteria and success measures
- Work with Project Managers to record risks, dependencies, decisions, and approval gates
- Collaborate with Developers and Technical Architects on secure design, implementation controls, and remediation plans
- Coordinate with QA/Test Leads to include security and compliance checks in test and release readiness activities

---

## Technical Architects / Solution Architects

### Role Summary
Technical Architects and Solution Architects guide the technical direction of a project. They define architectural approaches, integration patterns, and trade-offs that support the desired outcomes while managing technical risk.

### Responsibilities
- Define and document architecture decisions and technical constraints
- Evaluate scalability, reliability, maintainability, and integration considerations
- Identify technical dependencies, risks, and migration requirements
- Establish design standards and support consistent implementation across teams
- Review significant technical changes and help resolve cross-team design issues

### Interaction with Existing Roles
- Work with Product Managers to translate product goals and acceptance criteria into feasible solution options
- Work with Project Managers to surface technical dependencies, estimate sequencing constraints, and communicate architecture decisions
- Collaborate with Developers through design reviews, implementation guidance, and technical risk mitigation
- Partner with Security & Compliance Leads to incorporate secure-by-design controls
- Coordinate with QA/Test Leads to ensure architectural qualities and integration behaviors are testable

---

## QA / Test Leads

### Role Summary
QA and Test Leads establish the quality strategy for a project and help the team determine whether work is ready for release. They coordinate validation across unit, integration, end-to-end, and manual testing as appropriate.

### Responsibilities
- Define the test strategy, quality gates, and environments for the project
- Ensure acceptance criteria are testable and coverage is appropriate to risk
- Coordinate regression testing, defect triage, and release-readiness reviews
- Track quality risks and communicate unresolved issues and recommendations
- Promote automation and reliable test practices across delivery work

### Interaction with Existing Roles
- Work with Product Managers to clarify acceptance criteria, edge cases, and user-facing expectations
- Work with Project Managers to plan testing milestones, report quality risks, and support release decisions
- Collaborate with Developers on test design, defect reproduction, automation, and implementation feedback
- Partner with Technical Architects on integration, reliability, and other non-functional validation
- Coordinate with Security & Compliance Leads when security or compliance verification is part of the release criteria

---

## Customer Success / Enablement Leads

### Role Summary
Customer Success and Enablement Leads help ensure that delivered changes are understandable, adoptable, and operationally ready for customers and internal support teams.

### Responsibilities
- Identify onboarding, training, documentation, and support needs before release
- Coordinate readiness activities and feedback loops with customers or customer-facing teams
- Surface adoption risks, recurring user issues, and operational dependencies
- Help define rollout communications and post-release support plans
- Report customer feedback and adoption signals that can inform future priorities

### Interaction with Existing Roles
- Work with Product Managers to connect customer needs and feedback to roadmap priorities and success metrics
- Work with Project Managers to include readiness activities, communications, and dependencies in the delivery plan
- Collaborate with Developers and QA/Test Leads to validate usability, supportability, and critical customer workflows
- Coordinate with Security & Compliance Leads when customer communications or enablement materials include security, privacy, or regulatory commitments
- Provide stakeholder and customer feedback during demos, release reviews, and retrospectives

---

## Data / Analytics Leads

### Role Summary
Data and Analytics Leads define how project outcomes will be measured and help teams use reliable evidence to evaluate impact and guide decisions.

### Responsibilities
- Translate project goals into measurable indicators and reporting requirements
- Define data sources, instrumentation, dashboarding, and measurement plans
- Validate data quality and clarify interpretation of project metrics
- Report trends and outcomes after delivery, including limitations and open questions
- Recommend follow-up analysis or experiments when results do not meet expectations

### Interaction with Existing Roles
- Partner with Product Managers to define success metrics and evaluate customer and business outcomes
- Work with Project Managers to include measurement milestones, dependencies, and reporting in the project plan
- Collaborate with Developers and Technical Architects on instrumentation, data contracts, and observability
- Work with QA/Test Leads to validate metric calculations and important measurement paths
- Share evidence with stakeholders during demos, release reviews, and retrospectives to support informed decisions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Assign the personas involved in a project according to its scope, risk, and delivery needs; not every project requires every role.
