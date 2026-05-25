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

## UX Designers

### Role Summary
UX Designers ensure solutions are usable, intuitive, and aligned with user needs before and during implementation.

### Responsibilities
- Plan and run lightweight discovery (interviews, usability checks, journey mapping)
- Produce wireframes, user flows, and interaction notes
- Partner with Product and Developers to refine acceptance criteria from a usability perspective
- Validate implemented experiences and flag usability gaps before release

### Goals
- Reduce usability defects and rework
- Increase user satisfaction and task completion
- Ensure feature scope includes clear user experience outcomes

### Typical Communication
- Design reviews with Developers and QA/Testing
- Regular syncs with Product Managers on user needs and trade-offs
- Milestone demos with Project Managers and Stakeholders

### Interaction Points with Existing Roles
- **Project Manager**: align design milestones with delivery timeline and dependencies
- **Product Manager**: translate product goals into user flows, UI priorities, and acceptance criteria
- **Developers**: hand off design intent, clarify edge cases, and review implementation fidelity
- **QA/Testing**: define usability-focused scenarios and support feature acceptance checks
- **Stakeholders**: share prototypes and rationale to gather early alignment and feedback

---

## Scrum Masters / Agile Facilitators

### Role Summary
Scrum Masters / Agile Facilitators improve team flow and execution discipline by facilitating agile ceremonies and removing process blockers.

### Responsibilities
- Facilitate planning, standups, reviews, and retrospectives
- Track and escalate blockers that affect sprint outcomes
- Coach teams on agile practices, estimation, and continuous improvement
- Help teams maintain clear backlog readiness and predictable delivery cadence

### Goals
- Improve delivery predictability and team focus
- Reduce blocker resolution time
- Enable sustainable team velocity and healthy collaboration

### Typical Communication
- Daily facilitation with delivery teams
- Weekly coordination with Project Managers and Product Managers
- Retrospective action-item tracking across sprints

### Interaction Points with Existing Roles
- **Project Manager**: align ceremony outputs with project plans, risks, and escalation paths
- **Product Manager**: ensure backlog readiness and priority clarity before sprint commitments
- **Developers**: support workload balance, team agreements, and issue escalation
- **QA/Testing**: coordinate test planning visibility and reduce late-stage quality surprises
- **Stakeholders**: provide transparent delivery signals through agreed cadence and reporting

---

## DevOps Engineers

### Role Summary
DevOps Engineers own delivery pipeline reliability and operational readiness so features can be shipped safely and repeatedly.

### Responsibilities
- Maintain CI/CD pipelines, release automation, and deployment standards
- Improve observability (logging, metrics, alerts) and operational runbooks
- Partner on environment strategy, rollback planning, and production readiness
- Identify operational risks early and propose mitigation actions

### Goals
- Shorten lead time to production with stable releases
- Reduce deployment failures and recovery time
- Improve confidence in release readiness and incident response

### Typical Communication
- Release readiness checkpoints with PM, QA/Testing, and Developers
- Incident and post-incident coordination
- Regular updates on pipeline health and operational risks

### Interaction Points with Existing Roles
- **Project Manager**: coordinate release calendars, deployment dependencies, and risk escalations
- **Product Manager**: align release approach with customer impact and rollout strategy
- **Developers**: co-own build/deploy quality, environment parity, and production support practices
- **QA/Testing**: integrate test gates, smoke tests, and quality signals into CI/CD
- **Stakeholders**: communicate release readiness, deployment outcomes, and incident status when needed

---

## Business Analysts

### Role Summary
Business Analysts bridge business needs and delivery teams by translating stakeholder goals into clear, testable requirements.

### Responsibilities
- Elicit and document business requirements, assumptions, and constraints
- Refine process flows and acceptance criteria with Product and delivery teams
- Trace requirements to delivered outcomes and identify scope gaps
- Support decision-making with impact analysis and option trade-offs

### Goals
- Reduce ambiguity in requirements and handoffs
- Improve alignment between business intent and implementation
- Increase first-pass acceptance of delivered work

### Typical Communication
- Discovery workshops with Stakeholders and Product Managers
- Clarification sessions with Project Managers, Developers, and QA/Testing
- Ongoing documentation updates in shared project artifacts

### Interaction Points with Existing Roles
- **Project Manager**: align requirement milestones with planning checkpoints and dependency tracking
- **Product Manager**: convert goals into structured requirements, acceptance criteria, and scope decisions
- **Developers**: clarify business rules, edge cases, and expected behavior before and during implementation
- **QA/Testing**: confirm test scenarios map to requirements and expected business outcomes
- **Stakeholders**: capture priorities, validate interpretations, and communicate requirement changes

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Use the [Role Accountability Matrix](./octoacme-role-accountability-matrix.md) to clarify ownership and handoff points for recurring project activities.
