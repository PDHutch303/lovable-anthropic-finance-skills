---
name: close-management
description: Use when planning, running, resuming, or reviewing a month-end, quarter-end, or year-end close, including readiness, dependencies, reconciliations, adjusting entries, review, exceptions, period lock, and reporting handoff.
---

# Close Management

Follow `QUALITY-STANDARD.md`. The close is evidence-gated: a task is complete because the supporting work is complete and still ties to the current books, not because a checklist box says so.

## Preflight
Pin entity/entities, period, basis, close deadline, materiality, closed-through state, source set, and ownership. Determine whether this is a new close or a resumption; do not start a parallel close for the same entity/period if current workpapers already exist.

## Phases

### 1. Intake / readiness
Inventory TB/GL, bank/card statements, AR/AP, payroll, revenue, inventory, fixed assets, debt, leases, intercompany, tax/equity and other entity-specific schedules. Validate TB and source-period completeness. List missing evidence and what it blocks.

### 2. Reconcile / prepare
Complete cash/card, AR/AP, payroll, fixed assets, inventory/WIP, debt, leases, taxes and intercompany reconciliations as applicable. Every balance-sheet account should have support, explicit immaterial disposition, or an exception.

### 3. Adjust
Prepare supported accruals, prepaids, depreciation, revenue/cutoff, inventory/COGS, payroll, intercompany/elimination, tax/equity and other entries. Keep proposed, approved, posted and declined entries distinct.

### 4. Controller review
Re-run critical tie-outs after entries; inspect suspense/uncategorized accounts, negative/unusual balances, stale reconciling items, cutoff, related parties, large manual journals and material period movements.

### 5. Deliver / lock
Only after review: produce final statements/reporting package, record unresolved accepted exceptions, lock/close the period where authorized, archive workpapers, and roll forward recurring schedules.

## Standard sequencing
A typical target may be T+1 through T+5, but actual dependencies outrank an arbitrary calendar. Downstream reporting should not be labeled final while material source reconciliations remain open.

## Exception register
Track item, amount/exposure, source, phase, owner, status, due date, disposition, and whether it blocks final close. Resolved/accepted items remain in history.

## Completion criteria
A close is `ready` only when:
- TB/GL integrity tests pass;
- material balance-sheet accounts are supported;
- subledgers reconcile or differences are explicitly accepted;
- required entries are posted/approved or disclosed;
- material intercompany differences are resolved/accepted;
- review is performed after the latest material change;
- final reporting ties to the adjusted books.

Otherwise report `ready with exceptions` or `blocked` and name the items.

## Output
Return phase status, critical path, reconciliations, proposed/posted entries, open exceptions, review status, reporting readiness, and next owners/deadlines.

## Guardrails
- No generic close plugs.
- Do not infer approval from silence or prior conversation.
- A material late adjustment sends impacted reconciliations/review back to open.
- Unattended automation may prepare and surface; material entries and final sign-off remain subject to policy/approval.