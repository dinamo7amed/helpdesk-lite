# Repo-Ready Change Brief

## Change Name
SLA Auto-Escalation Trigger

## Jira Work Item
HDL-24 – SLA Auto-Escalation Trigger

## Purpose
Implement an automatic escalation feature that detects support tickets exceeding their Service Level Agreement (SLA) deadline and automatically increases their priority to ensure timely resolution.

## Expected Behavior
When a ticket exceeds its SLA deadline without being resolved, the system automatically changes its priority to High, assigns it to the escalation queue, and records the escalation event for tracking.

## Files / Modules Likely Affected
- TicketService
- EscalationService
- SLAValidator
- Ticket Model
- Unit Tests
- Documentation

## Evidence of Completion
- Unit tests pass successfully.
- Manual testing confirms expired tickets are automatically escalated.
- Active tickets remain unchanged.
- Escalation events are recorded correctly.
- Jira work item HDL-24 is moved to Done after verification.
