# Release Checklist (Project-level)

Purpose: Standardize release activities so releases are predictable, auditable, and safe.

- [ ] Confirm release date/time and stakeholder availability
- [ ] Update release plan and publish to stakeholders
- [ ] Confirm all PRs targeted for release are merged and green
- [ ] Verify deploy pipeline status (no blocking failures)
- [ ] Smoke test plan defined and owner assigned
- [ ] Rollback plan defined and tested in staging
- [ ] Database migration plan reviewed and approved (if applicable)
- [ ] QA sign-off obtained from QA Liaison
- [ ] Release notes drafted and reviewed by Documentation Owner
- [ ] Stakeholder notification sent (pre-release)
- [ ] Execute deploy during approved window
- [ ] Run smoke tests and confirm health checks
- [ ] Post-release monitoring active and owner assigned
- [ ] Post-release retrospective scheduled (if significant)

Notes:
- Release Coordinator owns this checklist. Any skipped item must be explicitly approved and recorded in the release decision log.
