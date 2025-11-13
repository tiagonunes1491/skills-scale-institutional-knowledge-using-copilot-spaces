# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- QA Engineer sign-off on test results and quality validation
- Release notes drafted (Product Manager, Release Manager)
- Rollback / mitigation plan documented (Release Manager)
- Smoke tests prepared (QA Engineer)
- UX Designer validation for user-facing changes

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) — Release Manager coordinates
- [ ] Backup or snapshot (if applicable) — Release Manager validates
- [ ] Deploy to staging and run smoke tests — QA Engineer executes
- [ ] Deploy to production (automated pipeline preferred) — Release Manager executes
- [ ] Run post-deploy verifications — QA Engineer and Release Manager validate
- [ ] Announce release to stakeholders and support — Product Manager and Release Manager

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Release Manager triggers incident response and notifies on-call
  - Rollback to last known-good release if necessary (Release Manager executes)
  - Triage root cause and capture action items (Release Manager, Project Manager, QA Engineer)
  - Post-incident retrospective to identify improvements (Scrum Master facilitates)

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
