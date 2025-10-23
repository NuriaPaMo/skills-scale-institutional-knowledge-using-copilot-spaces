# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged (Developer sign-off)
- Passing CI and security scans
- QA sign-off from QA Lead (all test cases passed, no critical bugs)
- UX validation for user-facing changes (UX Designer sign-off)
- Release notes drafted (coordinated by Release Manager with Technical Writer)
- Rollback / mitigation plan documented (Release Manager)
- Smoke tests prepared and reviewed (QA Lead)
- Documentation updated (Technical Writer)
- Stakeholder communication prepared (see [Stakeholder Communications Template](stakeholder-communications-template.md))

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) - Release Manager coordinates
- [ ] Backup or snapshot (if applicable) - Release Manager ensures
- [ ] Deploy to staging and run smoke tests - QA Lead validates
- [ ] Deploy to production (automated pipeline preferred) - Release Manager executes
- [ ] Run post-deploy verifications - QA Lead and Release Manager
- [ ] Announce release to stakeholders and support - Release Manager with input from Technical Writer
- [ ] Update documentation as live - Technical Writer confirms

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (Release Manager leads)
  - Rollback to last known-good release if necessary (Release Manager executes)
  - Triage root cause and capture action items (Project Manager coordinates)
  - Notify stakeholders of issue and resolution (use [Stakeholder Communications Template](stakeholder-communications-template.md))
  
**Role Responsibilities in Incident Response:**
- Release Manager: Lead rollback, coordinate technical response
- QA Lead: Verify rollback success, help identify root cause
- Developers: Provide technical analysis and fixes
- Project Manager: Coordinate communication, track action items
- Product Manager: Assess business impact, prioritize fixes
- Technical Writer: Update documentation with incident details and resolutions

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:

**Prepared by:** Release Manager and Technical Writer  
**Reviewed by:** Product Manager and QA Lead  
**Published to:** All stakeholders via communication channels (see [Stakeholder Communications Template](stakeholder-communications-template.md))

For the Release Manager role and responsibilities, see [Roles and Personas](octoacme-roles-and-personas.md).
