# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
  - Participation: All team members (Developers, QA Lead, UX Designer, Project Manager)
  - See [Roles and Personas](octoacme-roles-and-personas.md) for role-specific contributions
- Weekly delivery sync — show progress, updates, and flagged risks
  - Includes: Project Manager, Product Manager, key Stakeholder Representatives
- Demo/Review at the end of each sprint or milestone
  - Invite: All team members, Stakeholder Representatives, and interested parties
  - UX Designer presents design validations; QA Lead presents test results

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Developer peer review required
  - UX Designer review for UI changes
  - QA Lead review and testing before merge (or team-defined policy)
  - Technical Writer notified for documentation updates

## Quality & Testing
- Unit tests for new logic (Developer responsibility)
- Integration tests where applicable (Developer and QA Lead collaboration)
- End-to-end smoke tests for critical flows before release (QA Lead)
- Security scanning in CI
- Manual QA for feature acceptance when needed (QA Lead)
- Usability testing for significant UI changes (UX Designer and QA Lead)
- QA sign-off required before release (see [Release & Deployment Guide](octoacme-release-and-deployment.md))

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup (facilitated by Project Manager)
- Level 2: Project Manager escalates to Product Manager/Product Lead and dependent teams
- Level 3: Stakeholder Representative and Sponsor-level escalation for business-impacting issues
- For detailed escalation procedures, see [Risk Management & Communication](octoacme-risks-and-communication.md)

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled with stakeholder invitations
- [ ] Risk register updated weekly (Project Manager)
- [ ] QA Lead assigned and test strategy in place
- [ ] UX Designer engaged for design reviews
- [ ] Technical Writer informed of documentation needs
- [ ] Release Manager coordinating with deployment pipeline
