---
name: accounting-cfo
description: Use when performing bookkeeping, accounting, controller/CPA review, financial close, tax readiness/review, audit support, family-office administration, FP&A, financial modeling, private-equity/fund analysis, financial advisory analysis, industry-specific accounting, multi-entity reporting, or CFO decision-support work. Not for app/software development unrelated to finance.
---

# Accounting, CPA, Family Office & CFO Operating Skill

Use this as the master finance router. For any material or review-facing task, apply `QUALITY-STANDARD.md` before the specialty workflow. Use `EVALS.md` to test and improve skill behavior.

## Operating order

For complex work, use this order unless the task clearly requires less:
1. **Scope:** entity, period, basis, currency, data-as-of/closed-through and materiality.
2. **Source:** identify the authoritative/source set and avoid duplicate pulls.
3. **Prove:** reconcile/tie-out the relevant balances or roll-forwards.
4. **Analyze:** use the appropriate accounting, tax, modeling, family-office, industry or advisory workflow.
5. **Exceptions:** surface unresolved differences and missing evidence.
6. **Review:** identify approvals and qualified-professional review points.
7. **Deliver:** make the conclusion reproducible and operational.

## Core workflow router

### Bookkeeping, source records & close
Use `client-onboarding-intake`, `client-intake-context-profiler`, `bookkeeping-setup`, `chart-of-accounts`, `receipt-invoice-extractor`, `receipt-processing`, `uncategorized-transaction-chaser`, `expense-categorization`, `bank-reconciliation`, `reconciliation`, `cleanup-catchup-bookkeeping`, `accruals-prepaids`, `journal-entry-prep`, `journal-entry`, `payroll-reconciliation`, `inventory-cogs`, `depreciation-assets`, `close-management`, and `controller-review`.

For close work, evidence and tie-outs outrank checklist status. Never use a generic balancing plug to finish a close.

### Billing, AP, AR & payments
Use `contract-to-invoice`, `usage-billing-review`, `accounts-payable`, `invoice-aging`, `payment-reconciliation`, `ar-collections`, `ar-dunning`, `purchase-order-management`, `expense-management`, and `stripe-reconciliation`.

### Financial statements, reporting & controller work
Use `financial-statements`, `variance-analysis`, `board-reporting`, `management-dashboard`, `technical-accounting-research`, `accounting-policy-memo`, `gaap-disclosure-review`, `revenue-recognition`, `lease-accounting-asc842`, `multi-entity`, `intercompany-reconciliation`, `consolidation`, `business-combinations`, `debt-equity-accounting`, `related-party-review`, and `subsequent-events`.

### FP&A, modeling, CFO & corporate finance
Use `strategic-finance`, `budgeting`, `financial-forecasting`, `scenario-planning`, `cash-flow-forecast`, `three-statement-model`, `financial-model-audit`, `working-capital`, `profitability-analysis`, `client-profitability`, `revenue-concentration`, `runway-analysis`, `debt-covenant-analysis`, `treasury-cash-management`, `capital-allocation`, `capital-structure`, `valuation`, `investment-analysis`, `m-and-a-analysis`, `lbo-model`, `investment-committee-memo`, `quality-of-earnings`, `sources-and-uses`, and acquisition/post-close playbooks.

For spreadsheet/model work, model identities, formula integrity and dynamic propagation must pass before outputs are treated as decision-ready.

### Family office, private investments & planning
Use `family-office-reporting`, `family-office-pe-investment-accounting`, `fund-nav-reconciliation`, `private-investment-tracking`, `fund-investment-rollforward`, `capital-calls-distributions`, `capital-call-distribution-parser`, `capital-account-tracking`, `investment-basis-tracking`, `k1-investment-reconciliation`, `unfunded-commitment-tracking`, `investment-performance-irr-moic`, `family-office-liquidity`, `family-office-cash-forecasting`, `family-office-consolidation`, `entity-structure-mapping`, `partnership-waterfalls`, `preferred-return-waterfalls`, `carried-interest-analysis`, `portfolio-company-reporting`, `investment-committee-memo`, `family-council-minutes`, `philanthropic-planning`, `estate-trust-coordination`, `trust-accounting`, `trust-distribution-tracking`, `estate-administration-accounting`, `beneficiary-reporting`, `gift-estate-tax-readiness`, `financial-planning`, `investment-policy-statement`, `portfolio-reporting`, `portfolio-allocation-drift`, `multi-custody-aggregation`, `wealth-diagnostic-memo`, `insurance-risk-review`, `personal-financial-statement`, and `succession-planning-finance`.

Keep legal ownership, tax basis, accounting carrying value, manager NAV and estimated market value distinct. Reconcile material NAV breaks rather than selecting one source arbitrarily.

### Tax / CPA tax support
Use `tax-prep`, `tax-workpapers`, `tax-return-review`, `individual-tax-1040`, `partnership-tax-1065`, `s-corp-tax-1120s`, `c-corp-tax-1120`, `contractor-1099`, `basis-k1-tracking`, `estimated-tax-planning`, `entity-tax-analysis`, `state-local-tax`, `sales-tax-nexus`, `payroll-tax`, `tax-provision`, `tax-notice-response`, and `openaccountants-tax-lookup`.

For material tax conclusions, verify the current tax-year/jurisdiction authority. Software acceptance is not authority. Do not file or make elections without authorization.

### Audit, assurance & controls
Use `audit-planning`, `audit-risk-assessment`, `audit-support`, `substantive-testing`, `analytical-procedures`, `audit-sampling`, `fraud-risk`, `going-concern`, `sox-testing`, and `compilation-review-prep`.

These workflows support preparation/testing/review; they do not turn the agent into an independent auditor or allow it to issue an audit opinion.

## Industry router

Read `INDUSTRIES.md` when the request involves a family office/private investment, manufacturer, blue-collar service/construction company, plastic-surgery/medical practice, or acquisition/portfolio company. Industry skills add operating logic but inherit the core quality standard.

### Manufacturing
Use `manufacturing-cost-accounting`, `standard-costing`, `actual-vs-standard-cost`, `purchase-price-variance`, `material-usage-variance`, `labor-efficiency-variance`, `overhead-absorption`, `bom-costing`, `work-order-costing`, `wip-reconciliation`, `finished-goods-reconciliation`, `inventory-reserve-obsolescence`, `scrap-yield-analysis`, `capacity-utilization`, `machine-hour-costing`, `make-vs-buy`, `product-sku-profitability`, `landed-cost`, and `cycle-count-inventory-controls`.

### Blue-collar service / construction
Use `job-profitability`, `service-line-profitability`, `technician-profitability`, `labor-utilization`, `labor-burden`, `construction-job-costing`, `construction-wip-accounting`, `contract-assets-liabilities`, `backlog-analysis`, `service-agreement-recurring-revenue`, `fleet-truck-costing`, `truck-stock-inventory`, `dispatch-kpi-analysis`, `callback-warranty-costing`, `customer-acquisition-payback`, `branch-location-profitability`, `overtime-analysis`, `field-service-cash-conversion`, and `13-week-cash-flow-service-company`.

### Plastic surgery / medical
Use `medical-practice-accounting`, `procedure-profitability`, `provider-productivity`, `provider-compensation`, `patient-deposit-deferred-revenue`, `merchant-financing-reconciliation-medical`, `refund-credit-balance-review`, `medical-supply-implant-inventory`, `operating-room-profitability`, `medical-marketing-roi`, `payor-selfpay-mix-analysis`, and `practice-cash-flow-forecast`. Financial productivity metrics are not clinical-quality judgments.

### Acquisition / post-close
Use `purchase-price-allocation`, `opening-balance-sheet`, `working-capital-true-up`, `seller-note-accounting`, `earnout-accounting`, `transaction-cost-accounting`, `goodwill-intangibles`, `post-close-integration`, `100-day-finance-plan`, `acquisition-synergy-tracking`, `sources-and-uses`, `rollover-equity`, `three-statement-model`, `lbo-model`, `quality-of-earnings`, `investment-committee-memo`, and `financial-model-audit` as appropriate.

## Systems & integrations
Use `quickbooks-online`, `xero-integration`, `stripe-reconciliation`, and `INTEGRATIONS.md`. Never claim an external integration is connected or a write succeeded unless the actual system confirms it.

## Master guardrails
- Preserve legal entity, trust, fund and owner boundaries.
- Preserve historical actuals and source records.
- Do not invent tax rules, GAAP conclusions, legal rights, valuations, audit opinions or investment returns.
- Do not treat intercompany cash movement as proof of accounting substance.
- Do not net unrelated assets/liabilities without an established basis.
- Do not describe an estimate as an appraisal/fairness opinion.
- Do not treat a capital-call notice or invoice as independent verification of changed wire instructions.
- Do not present guaranteed returns or unqualified individualized securities recommendations.
- Tax, legal, audit, trust/estate, insurance and consequential technical-accounting conclusions should identify qualified-professional review points.

## Final quality gate
Before completion confirm relevant tie-outs pass or exceptions are quantified; facts/assumptions/judgments are labeled; source documents and data dates are visible; material risks are surfaced; authority is current where required; model checks pass where applicable; approvals are respected; and another reviewer could reproduce the result.