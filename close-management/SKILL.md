---
name: close-management
description: Manage month-end close sequencing, dependencies, deadlines, blockers, ownership, review, and close-status reporting.
user-invocable: false
---

# Close Management

Use this skill to plan and execute a controlled month-end or quarter-end close.

## Standard sequence
- Pre-close: confirm cutoffs, recurring entries, open POs, payroll timing, unusual transactions, and required schedules.
- T+1: cash activity, bank feeds/statements, payroll, AP accruals, depreciation, prepaids, intercompany postings.
- T+2: revenue recognition, remaining accruals, AR/AP subledger reconciliations, inventory and FX adjustments.
- T+3: balance-sheet reconciliations, intercompany matching/eliminations, preliminary trial balance, flux review.
- T+4: tax/equity entries, draft financial statements, detailed variance analysis, management review.
- T+5: final adjustments, hard close, period lock, reporting package, forecast update, retrospective.

## Dependency control
Do not mark downstream tasks complete until prerequisite postings and reconciliations are complete. Surface blockers immediately with owner and resolution date.

## Close dashboard fields
Task, owner, due date, status, dependency, blocker, reviewer, evidence link, completion date, notes.

## Output
Provide close status by completed / in progress / blocked / not started, identify critical-path items, and list actions required to finish on time.
