# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (verified by **DevOps / Platform Engineer**)
- Release notes drafted (**Product Manager**; reviewed by **Customer Support**)
- Rollback / mitigation plan documented (**DevOps / Platform Engineer**)
- Smoke tests prepared and signed off by **QA Lead**
- **QA Lead** provides formal release readiness sign-off
- **Customer Support** briefed on changes and known issues
- See [QA → Release Handoff Checklist](./octoacme-handoff-checklists.md#4-qa--release-handoff) before deploying

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests (**DevOps** deploys; **QA Lead** verifies)
- [ ] Deploy to production (automated pipeline preferred — **DevOps / Platform Engineer**)
- [ ] Run post-deploy verifications (**QA Lead**)
- [ ] Announce release to stakeholders and support (**Project Manager** + **Customer Support**)
- [ ] See [Release → Post-Release Handoff Checklist](./octoacme-handoff-checklists.md#5-release--post-release--support-handoff) after deploying

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
