# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner (Project Manager coordinates, assigns to appropriate role)
- Mitigation plan
- Status

**Role Responsibilities:**
- Project Manager: Maintains register, facilitates reviews
- Product Manager: Assesses product/market risks
- Developers: Identify technical risks
- QA Lead: Identifies quality and testing risks
- Release Manager: Identifies deployment and release risks
- UX Designer: Identifies usability and design risks

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support, Stakeholder Representatives)
- Provide regular updates (weekly or milestone-based) - use [Stakeholder Communications Template](stakeholder-communications-template.md)
- Use a single source of truth (project README or release doc) for status
- Engage Stakeholder Representatives to cascade information to their groups
- Technical Writer maintains documentation and communications materials
- For role-specific communication patterns, see [Roles and Personas](octoacme-roles-and-personas.md)

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
- Team-level → Project Manager → Product Manager/Product Lead → Stakeholder Representative → Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
- For quality issues blocking release, QA Lead → Release Manager → Product Manager
- For design/UX concerns, UX Designer → Product Manager → Stakeholder Representative
- See [Roles and Personas](octoacme-roles-and-personas.md) for role-specific escalation responsibilities
