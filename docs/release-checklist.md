# Release Checklist & Release Manager Guide

## Purpose
Provide a lightweight, repeatable release checklist and clarify the Release Manager's responsibilities to reduce deployment risk.

## Release Manager - Role Summary
The Release Manager coordinates production releases, owns release readiness, communications, and post-release verification.

## Responsibilities
- Coordinate release windows and stakeholder notifications
- Maintain release checklists and verify pre-release criteria
- Author release notes and confirm post-release checks
- Coordinate rollbacks and incident handoffs if needed

## Pre-release checklist
- [ ] All PRs merged and acceptance criteria met
- [ ] Automated tests passing (unit, integration) and CI green
- [ ] Security scans completed and no critical findings
- [ ] Migration steps documented and validated
- [ ] Backups/snapshots created (if applicable)
- [ ] Monitoring and alerts configured for new changes
- [ ] Support and on-call notified of the release schedule

## Deployment checklist
- [ ] Deploy to staging and run smoke tests
- [ ] Validate critical paths and health checks
- [ ] Schedule production deployment (or trigger pipeline)
- [ ] Monitor deployment progress and metrics

## Post-release checklist
- [ ] Run post-deploy smoke tests and sanity checks
- [ ] Monitor dashboards and error rates for 30–60 minutes
- [ ] Confirm stakeholders of successful release
- [ ] Capture any follow-up actions or bugs as issues

## Rollback & mitigation
- If critical issues are detected, coordinate rollback per the rollback plan.
- Trigger incident response and notify the on-call engineer when appropriate.

## Template: Quick release notes
- Release name/number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:

