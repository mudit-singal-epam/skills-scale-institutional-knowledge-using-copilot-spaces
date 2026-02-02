# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged (validated by QA Lead)
- Passing CI and security scans (monitored by DevOps Engineer)
- Release notes drafted (Product Manager, Project Manager)
- Rollback / mitigation plan documented (DevOps Engineer)
- Smoke tests prepared and executed (QA Lead)
- Design validation complete for UI changes (UX/UI Designer)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) - coordinated by PM and DevOps Engineer
- [ ] Backup or snapshot (if applicable) - DevOps Engineer
- [ ] Deploy to staging and run smoke tests - DevOps Engineer, QA Lead
- [ ] Deploy to production (automated pipeline preferred) - DevOps Engineer
- [ ] Run post-deploy verifications - QA Lead, DevOps Engineer
- [ ] Announce release to stakeholders and support - Product Manager, PM

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (DevOps Engineer leads technical response)
  - Rollback to last known-good release if necessary (DevOps Engineer)
  - Triage root cause and capture action items (PM, DevOps Engineer, relevant team members)
  - QA Lead validates rollback or fix before re-deployment

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
