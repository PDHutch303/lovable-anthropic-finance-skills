---
name: accounting-cfo
description: Use when performing bookkeeping, accounting, controller, FP&A, tax-readiness, reconciliation, month-end close, multi-entity, or CFO analysis and reporting tasks.
---

# Accounting & CFO

Use this skill as the primary accounting, bookkeeping, controller, and CFO operating playbook. Apply the most relevant bundled workflow for the user's request and combine workflows only when the task genuinely spans multiple functions.

## Core principles

1. Preserve accounting integrity: debits must equal credits, statements must reconcile, and adjustments require support.
2. Separate fact from assumption. Never invent balances, dates, tax treatment, account classifications, or management intent.
3. Prefer source records and reconciled data over summaries when they conflict.
4. Maintain entity boundaries. Do not mix transactions across legal entities without explicit intercompany treatment.
5. Flag unresolved exceptions rather than forcing a reconciliation.
6. Distinguish bookkeeping, management reporting, tax readiness, and GAAP conclusions. Escalate legal, tax, audit, or technical-accounting judgments when professional review is appropriate.
7. For every material adjustment, explain the business purpose, accounts affected, debit/credit logic, period, support, and financial-statement impact.
8. When analyzing financial performance, quantify both dollars and percentages and identify the operational driver rather than merely restating the variance.
9. Preserve historical actuals. Forecasts and budgets should not overwrite closed-period actual data.
10. For multi-entity work, reconcile due-to/due-from, management fees, contributions/distributions, loans, and eliminations symmetrically between entities.

## Workflow router

Use the bundled playbook that best matches the request:

### Bookkeeping & close
- `bank-reconciliation/SKILL.md` — bank and credit-card reconciliations
- `expense-categorization/SKILL.md` — transaction coding and chart-of-accounts classification
- `receipt-processing/SKILL.md` — receipt and source-document processing
- `close-management/SKILL.md` — month-end close sequencing and status
- `journal-entry-prep/SKILL.md` — prepare supported journal entries
- `journal-entry/SKILL.md` — debit/credit construction and posting logic
- `reconciliation/SKILL.md` — balance-sheet, subledger, GL, and other reconciliations
- `depreciation-assets/SKILL.md` — fixed assets and depreciation
- `inventory-cogs/SKILL.md` — inventory and cost-of-goods-sold analysis
- `payroll-reconciliation/SKILL.md` — payroll-to-GL reconciliation

### Accounts payable & receivable
- `accounts-payable/SKILL.md` — AP review and payment readiness
- `invoice-aging/SKILL.md` — AR aging and collection prioritization
- `payment-reconciliation/SKILL.md` — cash receipt/payment matching
- `ar-collections/SKILL.md` — collection workflow and follow-up
- `ar-dunning/SKILL.md` — structured customer dunning and escalation
- `purchase-order-management/SKILL.md` — PO approvals, matching, commitments, and accruals
- `expense-management/SKILL.md` — employee/card spend controls, coding, and approvals

### Financial reporting & controller
- `financial-statements/SKILL.md` — P&L, balance sheet, and cash flow reporting
- `variance-analysis/SKILL.md` — budget/actual and period-over-period analysis
- `board-reporting/SKILL.md` — board and management reporting packages
- `management-dashboard/SKILL.md` — recurring KPI scorecards and operating reviews
- `multi-entity-accounting/SKILL.md` — accounting across multiple legal entities
- `intercompany-reconciliation/SKILL.md` — intercompany matching and due-to/due-from
- `consolidation/SKILL.md` — consolidated reporting and eliminations
- `revenue-recognition/SKILL.md` — revenue-recognition analysis
- `lease-accounting-asc842/SKILL.md` — lease accounting under ASC 842

### FP&A & CFO
- `cash-flow-forecast/SKILL.md` — short- and medium-term cash forecasting
- `working-capital/SKILL.md` — receivables, payables, inventory, and liquidity
- `budgeting/SKILL.md` — annual and departmental budgets
- `financial-forecasting/SKILL.md` — rolling forecasts and scenario planning
- `profitability-analysis/SKILL.md` — product, service, location, or segment profitability
- `client-profitability/SKILL.md` — customer/client economics and pricing
- `revenue-concentration/SKILL.md` — concentration risk by customer/product/channel/location
- `runway-analysis/SKILL.md` — burn, liquidity floor, and runway scenarios
- `debt-covenant-analysis/SKILL.md` — leverage, DSCR, covenant headroom, and refinancing risk
- `treasury-cash-management/SKILL.md` — cash positioning, transfers, liquidity, and treasury controls
- `quality-of-earnings/SKILL.md` — QoE and normalized earnings analysis

### Tax & compliance readiness
- `contractor-1099/SKILL.md` — contractor and 1099 readiness
- `sales-tax-nexus/SKILL.md` — sales-tax nexus and filing-readiness analysis
- `tax-prep/SKILL.md` — tax-preparation readiness and support schedules
- `audit-support/SKILL.md` — audit support and evidence preparation
- `sox-testing/SKILL.md` — internal-control and SOX testing support

### Systems & integrations
- `quickbooks-online/SKILL.md` — QuickBooks Online accounting workflows
- `stripe-reconciliation/SKILL.md` — Stripe settlement and fee reconciliation
- `xero-integration/SKILL.md` — Xero accounting workflows

## Standard response pattern

When applicable, structure accounting work as:

1. **What the records show** — factual observations and reconciled balances.
2. **Issues / exceptions** — discrepancies, unsupported items, unusual activity, or missing data.
3. **Recommended treatment** — accounting workflow or management action.
4. **Journal entries** — debit, credit, amount, entity, date, and memo when an entry is required.
5. **Financial-statement impact** — P&L, balance sheet, cash flow, equity, and intercompany effects.
6. **Open items** — questions or documentation still needed.

For management reporting, add trends, material variances, KPIs, liquidity, risks, and recommended next actions.

## Guardrails

- Do not treat transfers between related entities as revenue or expense without determining whether they are loans, contributions, distributions, reimbursements, management fees, or other intercompany transactions.
- Do not book cash movement itself as proof of the underlying accounting treatment.
- Do not force bank reconciliation differences to miscellaneous expense or income solely to make the reconciliation balance.
- Do not net unrelated receivables and payables unless the accounting and legal right of offset is established.
- Do not assume a tax deduction, tax rate, nexus position, filing obligation, or GAAP conclusion when facts are incomplete.
- Do not change historical closed periods without clearly identifying the correction and its effect.
- For owner transactions, related parties, debt, equity, acquisitions, leases, revenue recognition, or material tax matters, clearly surface the applicable professional-review point.

## Quality check

Before finalizing any accounting output, confirm:
- debits equal credits;
- beginning balance + activity = ending balance where relevant;
- bank/subledger totals tie to the GL or differences are explicitly listed;
- intercompany entries mirror across entities;
- reporting period and entity are correct;
- no unsupported assumptions are presented as fact;
- all material exceptions are visible;
- recommended actions are operationally clear.