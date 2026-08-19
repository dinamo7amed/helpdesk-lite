# Merge and Release Checklist

## Before Merge

The pull request can be merged only if:

- All code review comments have been addressed.
- At least one reviewer has approved the pull request.
- All unit tests pass successfully.
- Manual testing confirms the SLA auto-escalation works correctly.
- No merge conflicts exist.
- The Jira work item (HDL-24) is updated with the latest status.
- Documentation has been updated.

---

## Before Release / Production

Before deploying the feature to production, the following should be confirmed:

- The feature has been tested in a staging environment.
- No critical bugs remain open.
- Performance has not been negatively affected.
- Monitoring and logging are enabled for SLA escalation events.
- The support team is informed about the new feature.
- A rollback plan is available in case unexpected issues occur after deployment.

---

## Difference Between Merge and Release

- **Merge** means the approved code is added to the main branch.
- **Release** means the tested code is deployed to production and becomes available to users.
