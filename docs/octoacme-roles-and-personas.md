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

## QA Lead

### Role Summary
QA Leads ensure the quality of deliverables through test strategy, execution, and defect management. They collaborate with developers and product managers to validate features meet acceptance criteria and quality standards before release.

### Responsibilities
- Define test strategy and QA approach for projects
- Create and maintain test plans and test cases
- Execute manual testing and coordinate automated testing efforts
- Track and triage bugs and quality issues
- Sign off on releases based on quality criteria
- Establish and monitor quality metrics

### Goals
- Ensure high-quality releases with minimal production defects
- Reduce testing cycle time through automation
- Maintain comprehensive test coverage for critical flows
- Foster a culture of quality across the team

### Typical Communication
- Daily standup participation for blockers and testing status
- Weekly test status reports and defect summaries
- QA sign-off communications for releases
- Bug triage sessions and test case reviews

### Boundaries and Handoffs
- **From Product Managers**: Receive acceptance criteria and feature specifications
- **From Developers**: Receive code changes via PRs for testing; provide bug reports and feedback
- **To Release Manager**: Provide QA sign-off and test results before deployment
- **To Stakeholders**: Report on quality metrics and testing coverage

---

## UX Designer

### Role Summary
UX Designers research user needs, design intuitive interfaces, and validate solutions through usability testing. They ensure products are user-friendly, accessible, and aligned with user expectations.

### Responsibilities
- Conduct user research and usability studies
- Create wireframes, mockups, and interactive prototypes
- Define user flows and interaction patterns
- Collaborate with developers on implementation of designs
- Conduct usability testing and iterate based on feedback
- Maintain design systems and style guides

### Goals
- Maximize user satisfaction and product usability
- Ensure consistency across user interfaces
- Reduce user friction and support costs
- Validate design decisions with user data

### Typical Communication
- Design reviews and critique sessions
- User research findings presentations
- Collaboration with developers during implementation
- Stakeholder presentations for major design decisions

### Boundaries and Handoffs
- **From Product Managers**: Receive product requirements and user problems to solve
- **To Developers**: Deliver design specifications, assets, and interaction guidelines
- **To QA Lead**: Provide usability criteria and participate in acceptance testing
- **From Stakeholders**: Gather feedback on design direction and brand alignment

---

## Release Manager

### Role Summary
Release Managers coordinate and execute software releases across environments. They ensure deployments are planned, communicated, and executed safely with proper rollback procedures in place.

### Responsibilities
- Plan and schedule release windows
- Coordinate release activities across teams
- Maintain release documentation and runbooks
- Execute deployment procedures and monitor releases
- Manage rollback procedures when needed
- Track release metrics and success rates

### Goals
- Achieve zero-downtime deployments
- Minimize deployment-related incidents
- Maintain predictable release cadence
- Ensure all releases follow standardized procedures

### Typical Communication
- Release planning meetings with development and QA
- Pre-release checklists and go/no-go communications
- Release announcements to stakeholders and support teams
- Post-release status updates and incident reports

### Boundaries and Handoffs
- **From QA Lead**: Receive QA sign-off and test results
- **From Developers**: Coordinate with development team on release readiness
- **To Stakeholders**: Communicate release schedules and status
- **To Technical Writers**: Coordinate on release notes and documentation updates
- **To Support/Operations**: Provide release information and known issues

---

## Technical Writer

### Role Summary
Technical Writers create and maintain documentation for internal and external audiences. They translate technical concepts into clear, accessible documentation that enables users and team members to be successful.

### Responsibilities
- Write and maintain user guides, API docs, and tutorials
- Create internal process documentation and runbooks
- Review technical accuracy with subject matter experts
- Maintain documentation standards and style guides
- Update documentation with each release
- Organize and structure documentation for discoverability

### Goals
- Reduce support burden through clear documentation
- Improve developer experience and time-to-productivity
- Ensure documentation accuracy and currency
- Make knowledge accessible and searchable

### Typical Communication
- Documentation review sessions with developers
- Release coordination meetings for updates
- Stakeholder interviews for technical content
- User feedback sessions to improve documentation

### Boundaries and Handoffs
- **From Developers**: Receive technical details and API specifications
- **From Release Manager**: Coordinate on release notes and deployment documentation
- **From Product Managers**: Receive feature requirements for user documentation
- **To Users/Stakeholders**: Deliver comprehensive, accurate documentation

---

## Stakeholder Representative

### Role Summary
Stakeholder Representatives advocate for business units, customers, or other key stakeholder groups. They ensure stakeholder needs are understood, priorities are communicated, and project outcomes align with business objectives.

### Responsibilities
- Communicate stakeholder requirements and constraints
- Participate in planning and priority discussions
- Provide business context and user perspectives
- Review and approve project deliverables
- Escalate concerns and blockers to leadership
- Share project updates with their stakeholder groups

### Goals
- Ensure project outcomes meet stakeholder needs
- Maintain alignment between technical delivery and business goals
- Minimize surprises through proactive communication
- Represent user and business perspectives in decisions

### Typical Communication
- Monthly stakeholder update meetings
- Ad-hoc input on priorities and trade-offs
- Approval and sign-off communications
- Feedback on demos and releases

### Boundaries and Handoffs
- **From Project Managers**: Receive status updates and decision requests
- **From Product Managers**: Participate in roadmap and priority discussions
- **To Leadership**: Escalate risks and decisions requiring executive input
- **To Project Team**: Provide business requirements and constraints

---

## Role Interaction Summary

Understanding how roles interact is critical for smooth project execution:

- **Developers** implement features based on requirements from **Product Managers** and designs from **UX Designers**, with code reviewed by peers and tested by **QA Lead**
- **Product Managers** prioritize work with input from **Stakeholder Representatives** and collaborate with **UX Designers** on user needs
- **Project Managers** coordinate all roles, manage timelines, and facilitate communication across the team
- **QA Lead** validates work from **Developers** and provides sign-off to **Release Manager**
- **Release Manager** coordinates deployments with **Developers** and **QA Lead**, and communicates with **Technical Writers** for release documentation
- **Technical Writers** document features from **Developers** and **Product Managers**, and update docs for each release coordinated by **Release Manager**
- **Stakeholder Representatives** provide input to **Product Managers** and **Project Managers**, and receive updates on progress and decisions

For detailed templates on role onboarding and responsibilities, see:
- [Role Onboarding Template](role-onboarding-template.md)
- [Role Responsibilities Sign-off Template](role-responsibilities-signoff-template.md)
- [Stakeholder Communications Template](stakeholder-communications-template.md)

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

