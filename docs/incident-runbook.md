# Incident Runbook (OctoAcme) — Template

Purpose: Quick, actionable steps for triage and communication during production incidents.

1. Triage
- [ ] Identify and confirm the incident (severity classification)
- [ ] Capture initial incident summary (time, scope, affected users)
- [ ] Page/notify on-call contacts (Support/SRE Lead, Release Manager, Tech Lead)
- [ ] Create an incident issue (or use incident channel) and record timeline

2. Containment & Mitigation
- [ ] Apply immediate mitigations (feature flag, rollback, traffic cutover)
- [ ] Collect logs, traces, and metrics relevant to the problem
- [ ] If security-related, notify Security Lead and follow security incident protocol

3. Communication
- [ ] Post an incident update to stakeholders (status, next steps)
- [ ] Keep a visible timeline and assign owners for actions
- [ ] If customer-impacting, coordinate public messaging with PM/Support

4. Recovery & Root Cause
- [ ] Restore service to acceptable levels
- [ ] Run post-incident checks and validate fixes
- [ ] Run a blameless retrospective and create action items

5. Post-incident
- [ ] Assign owners and due dates for action items
- [ ] Update runbooks and documentation with learnings
- [ ] Share summary with stakeholders and capture metrics for improvement
