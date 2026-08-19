# Pull Request Draft

## PR Title
HDL-24: Implement SLA Auto-Escalation Trigger

## Purpose
This pull request implements the SLA Auto-Escalation feature for HelpDesk Lite. The goal is to automatically identify support tickets that exceed their SLA deadline and escalate them to ensure timely resolution.

## Summary of Changes
- Added SLA monitoring logic.
- Implemented automatic ticket escalation.
- Updated ticket priority to High when SLA is breached.
- Added unit tests for the new functionality.
- Updated project documentation.

## Evidence / Checks
- Unit tests completed successfully.
- Manual testing confirmed overdue tickets are escalated correctly.
- Verified that tickets within SLA remain unchanged.
- No existing functionality was affected during testing.

## Reviewer Focus
Please review:
- SLA validation logic.
- Auto-escalation conditions.
- Code readability and maintainability.
- Unit test coverage.
- Edge cases for ticket escalation.

## Known Risks
- Incorrect SLA calculation may cause unnecessary escalations.
- Future notification functionality is not included in this change.

## Intentionally Left Out
- Email notifications.
- SMS alerts.
- Dashboard reporting.
- Analytics and performance improvements.
