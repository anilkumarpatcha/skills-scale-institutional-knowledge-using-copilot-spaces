# Release Readiness Checklist

Purpose: Ensure releases are safe, observable, and properly communicated.

Pre-release
- [ ] All acceptance criteria met and verified
- [ ] PRs merged and CI green
- [ ] Security and dependency scans completed
- [ ] Release notes drafted (owner: PdM)
- [ ] Rollback / mitigation plan documented (owner: DevOps/PM)
- [ ] Staging smoke tests passed (owner: QA/Dev)

Release day
- [ ] Deployment window and owners confirmed (owner: PM)
- [ ] Backups/snapshots (if applicable)
- [ ] Execute deployment via CI/CD pipeline (owner: DevOps)
- [ ] Post-deploy smoke tests executed (owner: QA/Dev)
- [ ] Notify stakeholders and support channels of release (owner: PM/PdM)

Post-release
- [ ] Monitor dashboards for errors/latency (owner: DevOps/Data Analyst)
- [ ] Validate success metrics (owner: PdM/Data Analyst)
- [ ] Capture any follow-ups/action items (owner: PM)
