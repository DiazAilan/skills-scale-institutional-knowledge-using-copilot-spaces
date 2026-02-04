# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- **QA sign-off**: All test cases passed, no critical or high-priority bugs (QA Lead)
- **Design validation**: UI/UX implementation matches approved designs (Design Lead)
- Passing CI and security scans (DevOps Engineer)
- **Infrastructure readiness**: Deployment scripts tested, monitoring configured (DevOps Engineer)
- Release notes drafted (PM with input from all roles)
- Rollback / mitigation plan documented (DevOps Engineer)
- Smoke tests prepared (QA Lead)
- **Customer communication prepared**: release announcements, documentation updates (Support Lead)

## Deployment Checklist
- [ ] **QA Sign-off obtained** (QA Lead confirms all tests passed)
- [ ] **Design approval confirmed** for UI changes (Design Lead)
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot completed (DevOps Engineer)
- [ ] Deploy to staging and run smoke tests (QA Lead)
- [ ] **Infrastructure verification**: monitoring, alerts, capacity checks (DevOps Engineer)
- [ ] Deploy to production (automated pipeline preferred, managed by DevOps Engineer)
- [ ] Run post-deploy verifications (QA Lead, DevOps Engineer)
- [ ] **Customer communication sent**: release notes, announcements (Support Lead)
- [ ] Announce release to stakeholders and support team (PM, Support Lead)
- [ ] **Support team briefed** on new features and known issues (Support Lead)

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (DevOps Engineer coordinates)
  - **Customer communication**: Notify affected users of the issue (Support Lead)
  - Rollback to last known-good release if necessary (DevOps Engineer)
  - **QA verification**: Test rollback to ensure system stability (QA Lead)
  - Triage root cause and capture action items (PM, with input from all relevant roles)
  - Post-incident: Update customer communication with resolution (Support Lead)

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
