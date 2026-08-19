# Commit Sequence

## Commit 1
**Message:**
feat: add SLA monitoring service

**Purpose:**
Create the service that checks whether support tickets have exceeded their SLA deadline.

---

## Commit 2
**Message:**
feat: implement auto-escalation logic

**Purpose:**
Automatically change ticket priority to High and move overdue tickets to the escalation queue.

---

## Commit 3
**Message:**
test: add unit tests for SLA auto-escalation

**Purpose:**
Add unit tests to verify that tickets are escalated only when the SLA is breached.

---

## Commit 4
**Message:**
docs: update SLA auto-escalation documentation

**Purpose:**
Update the project documentation to describe the new feature and its expected behavior.
