---
name: fund-nav-reconciliation
description: Use when reconciling a private fund, SPV, partnership, PE/VC vehicle, family-office investment vehicle, or administrator NAV between the internal GL, fund administrator, custodian/bank, portfolio valuation schedules, investor capital accounts, cash activity, fees/accruals and manager statements.
---

# Fund NAV Reconciliation

Follow `QUALITY-STANDARD.md`.

The objective is to explain NAV from independently traceable components and resolve breaks, not select whichever source looks most plausible.

## Preflight

Pin fund/vehicle, legal entity, as-of date, base currency, accounting basis/valuation policy, administrator, custodian/banks, internal GL, portfolio schedule, capital activity records and prior finalized NAV.

Record source and timestamp/vintage for every major component. Private investment values can have different effective dates; do not silently treat stale valuation dates as current.

## Core NAV bridge

Build a roll-forward from prior approved NAV/accounting balances through:
- subscriptions/contributions/capital calls;
- distributions/redemptions;
- investment purchases/sales;
- realized gains/losses;
- unrealized valuation changes;
- interest/dividend/other income;
- management fees/carried-interest/incentive allocation where applicable;
- fund/operating expenses and accruals;
- receivables/payables;
- FX;
- other documented activity.

Beginning NAV + supported activity = ending NAV. The bridge must close before the ending value is represented as reconciled.

## Component reconciliations

As applicable reconcile:
- bank/cash to external statements;
- investments to custodian/manager/valuation schedules;
- accrued fees and expenses to agreements/workpapers;
- portfolio-company or fund valuations to the approved valuation source;
- investor capital accounts to contributions, allocations and distributions;
- unfunded commitments to subscription/governing records and notices;
- fund-level debt to lender statements;
- intercompany/related-party balances to counterpart records.

## Break tracing

Classify breaks rather than plugging them:
- timing/cutoff;
- missing or duplicate cash activity;
- stale valuation;
- FX rate/date;
- classification/map difference;
- missing accrual or fee;
- capital activity allocation;
- administrator/GL posting difference;
- ownership/allocation difference;
- unsupported/manual adjustment;
- source-version mismatch.

Quantify each break, source evidence, owner, aging and next step. An unresolved material break remains an exception; it is not absorbed into an `other` line merely to make NAV tie.

## Multiple value concepts

Keep manager-reported NAV/fair value, accounting carrying value, tax basis/capital and family-office estimated value distinct. Reconciliation may explain differences without asserting that one definition replaces another.

## Output

Provide NAV bridge, component tie-outs, capital-account/commitment reconciliation where applicable, break register, stale/missing valuation list, proposed supported entries/reclasses, final residual difference and reviewer status.

## Guardrails

Do not describe an internally reconciled NAV as audited NAV. Do not create valuation marks merely to clear a GL break. Material valuation, allocation, carried-interest or accounting conclusions require the applicable valuation/accounting/fund-document review.