# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. The personas below clarify ownership and collaboration across the project lifecycle; one person may hold more than one role on a small team.

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

## QA/Testing Lead

### Role Summary
QA/Testing Leads establish the test strategy and coordinate validation so that delivered work meets acceptance criteria and the Definition of Done.

### Responsibilities
- Define and execute unit, integration, end-to-end, and smoke-test plans
- Validate acceptance criteria and maintain release-readiness evidence
- Identify and report defects with clear reproduction steps
- Coordinate manual QA and contribute to test automation
- Advise Developers on testability, edge cases, and coverage
- Participate in planning, defect triage, release verification, and retrospectives

### Goals
- Reduce production defects and improve confidence in releases
- Detect quality risks early enough to protect delivery timelines
- Make quality expectations observable and repeatable

### Interaction with Existing Roles
- Partners with Product Managers to clarify acceptance criteria and edge cases
- Works with Developers during implementation, code reviews, defect triage, and test automation
- Provides Project Managers with quality risks, test status, and release-readiness information
- Confirms with Technical Leads that test environments and architecture support effective validation

### Typical Communication
- Sprint planning, daily standups, and defect triage
- Test-plan reviews and release-readiness checks
- Retrospectives focused on quality metrics and process improvements

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, approve initiatives and resources, and confirm that outcomes support organizational priorities.

### Responsibilities
- Define business outcomes and contribute to success criteria
- Approve project initiation, priority, and resource allocation when required
- Review status, risks, dependencies, and decisions
- Help resolve escalated blockers and resource conflicts
- Validate that delivered outcomes meet business needs
- Support risk mitigation and timely decision-making

### Goals
- Ensure projects deliver measurable business value
- Maintain alignment with strategic priorities
- Enable timely decisions and cross-team support

### Interaction with Existing Roles
- Aligns with Product Managers on customer value, outcomes, and prioritization
- Receives status, risk, and escalation updates from Project Managers
- Consults Developers and Technical Leads when business decisions have technical impact
- Reviews release outcomes with Product Managers and the delivery team rather than directing day-to-day implementation

### Typical Communication
- Project initiation and approval meetings
- Weekly or milestone-based status updates
- Monthly stakeholder briefings
- Release announcements and outcome reviews

---

## Security Champion

### Role Summary
Security Champions embed security practices in delivery, identify security risks, and connect the project team with security specialists and incident responders.

### Responsibilities
- Review designs and implementations for security risks
- Coordinate security scanning in CI and before release
- Identify, triage, and track security vulnerabilities
- Advise on authentication, authorization, data protection, and secure defaults
- Escalate critical security issues and support incident response
- Promote security training and awareness within the team

### Goals
- Protect customer data and reduce the likelihood of security incidents
- Integrate security into planning, development, testing, and release workflows
- Shorten the time to detect, remediate, and communicate security issues

### Interaction with Existing Roles
- Works with Technical Leads and Developers during design and code reviews to address vulnerabilities
- Partners with QA/Testing Leads to include security checks in test plans and release verification
- Advises Product Managers and Project Managers on security trade-offs, risks, dependencies, and release readiness
- Coordinates with Stakeholders/Sponsors on business impact and escalation for significant security risks

### Typical Communication
- Design and code review discussions
- Security scan results and pre-release verification
- Incident response and blameless post-incident reviews
- Security training and best-practice sharing

---

## Technical Lead/Architect

### Role Summary
Technical Leads guide architectural decisions, mentor Developers, and ensure technical quality, integration readiness, and long-term maintainability.

### Responsibilities
- Define and evolve technical architecture and design patterns
- Review designs and code for technical quality and maintainability
- Identify and mitigate technical risks, dependencies, and debt
- Mentor Developers and provide technical guidance
- Participate in integration planning and dependency management
- Advise on technology choices, trade-offs, performance, and reliability

### Goals
- Deliver scalable, maintainable, secure, and performant systems
- Reduce technical debt and integration risk
- Enable team growth through mentoring and knowledge sharing
- Minimize technical blockers and late architectural changes

### Interaction with Existing Roles
- Partners with Developers on implementation decisions, code reviews, and technical problem-solving
- Works with Product Managers to assess feasibility and explain technical trade-offs affecting outcomes
- Gives Project Managers input on estimates, dependencies, risks, and sequencing
- Collaborates with QA/Testing Leads on testability, environments, and non-functional validation
- Coordinates with Security Champions to address security requirements in architecture and delivery
- Communicates material technical decisions and risks to Stakeholders/Sponsors through the Product Manager or Project Manager

### Typical Communication
- Technical design reviews and architecture discussions
- Code reviews and mentoring conversations
- Sprint planning for technical feasibility and dependency assessment
- Retrospectives on technical improvements and learnings

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When roles overlap, explicitly name the accountable person for each decision or deliverable in the project plan, backlog, risk register, and release checklist.
