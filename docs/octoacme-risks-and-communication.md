# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call

## Role-based Communication Handoffs
- **Requirements handoff (PdM/BA -> Developers/QA)**: include business context, acceptance criteria, and open assumptions.
- **Design handoff (UX -> Developers/QA)**: include user flow, edge cases, and expected behavior for validation.
- **Delivery handoff (Developers -> QA/Testing)**: include test notes, known limitations, and links to relevant PRs/issues.
- **Release handoff (QA/Testing + Developers -> DevOps + PM)**: include test evidence, release risks, and rollback expectations.
- **Stakeholder update handoff (PM + PdM -> Stakeholders)**: include current status, blockers, decisions needed, and owners.

Use the [Role Accountability Matrix](./octoacme-role-accountability-matrix.md) during planning and weekly syncs to confirm owners for each handoff.
