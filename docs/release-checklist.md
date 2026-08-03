# Release Checklist (OctoAcme)

Purpose: A practical checklist to ensure safe, observable, and repeatable releases.

Pre-release
- [ ] Release window scheduled and communicated
- [ ] Release Manager assigned
- [ ] PRs merged and linked to issues with acceptance criteria
- [ ] CI: all jobs passing (unit, integration, lint)
- [ ] Security scans completed and high/severe findings triaged
- [ ] Migration/DB changes validated in staging
- [ ] Feature flags configured (if applicable)
- [ ] Backups/snapshots taken (if applicable)
- [ ] Rollback plan documented and tested (or smoke-test reversal steps confirmed)
- [ ] Support/SRE notified and runbooks linked
- [ ] Release notes drafted and reviewed

Staging
- [ ] Deploy to staging completed
- [ ] Run smoke tests for critical flows
- [ ] Monitor metrics/dashboards and error logs during staging tests
- [ ] Sign-off from QA and Release Manager

Production
- [ ] Deploy via automated pipeline or verified deploy steps
- [ ] Post-deploy smoke checks executed
- [ ] Verify observability (errors, latency, traffic) as expected
- [ ] Notify stakeholders and support teams
- [ ] Publish release notes

Post-release
- [ ] Monitor system for X hours/days (per release type)
- [ ] Collect and triage feedback/issues
- [ ] Close release checklist and annotate lessons learned
- [ ] If issues occurred, ensure incident retrospective and action items are recorded

Release types
- Patch: shorter observation window, expedited rollback plan
- Minor: standard checklist and 24–72 hour monitoring
- Major: expanded stakeholder notification, migration window, and expanded QA
