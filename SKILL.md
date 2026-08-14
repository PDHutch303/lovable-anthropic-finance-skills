---
name: accounting-cfo
description: Use for bookkeeping, accounting, CPA/controller work, tax readiness and planning support, audit support, family-office administration, financial planning, FP&A, financial advisory analysis, multi-entity reporting, industry-specific accounting, and CFO decision support.
---

# Accounting, CPA, Tax, Audit, Family Office & Financial Advisory

Use this as the master professional-finance operating skill. Route each request to the most relevant bundled playbook and combine playbooks when the work genuinely spans functions or industries.

## Core principles
1. Preserve accounting integrity: debits equal credits, reconciliations tie, and material adjustments require support.
2. Separate facts, estimates, assumptions, and professional judgments.
3. Preserve entity, trust, fund, and owner boundaries even in consolidated economic reporting.
4. Prefer source records and reconciled schedules over summaries when they conflict.
5. Never force unresolved differences merely to make a schedule balance.
6. Distinguish bookkeeping, GAAP/accounting analysis, management reporting, tax analysis, audit support, legal conclusions, insurance advice, and investment advice.
7. Show assumptions, evidence, financial impact, and the professional-review point for material conclusions.
8. Use current authoritative sources when tax law, accounting standards, audit standards, regulations, rates, thresholds, or filing requirements matter.
9. Preserve historical actuals; forecasts and scenarios do not overwrite closed-period records.
10. For related parties and multi-entity activity, determine economic substance before selecting accounting treatment.

## Workflow router

### Bookkeeping & onboarding
- `client-onboarding-intake/SKILL.md` — full new-client/entity accounting intake
- `client-intake-context-profiler/SKILL.md` — recurring client rules and context profile
- `bookkeeping-setup/SKILL.md` — new-book setup and architecture
- `chart-of-accounts/SKILL.md` — COA design, cleanup, and mapping
- `receipt-invoice-extractor/SKILL.md` — structured extraction from receipts and invoices
- `receipt-processing/SKILL.md` — receipt/source-document processing
- `uncategorized-transaction-chaser/SKILL.md` — unresolved transaction client-question queue
- `bank-reconciliation/SKILL.md` — bank/credit-card reconciliation
- `expense-categorization/SKILL.md` — transaction coding
- `cleanup-catchup-bookkeeping/SKILL.md` — historical cleanup and catch-up
- `accruals-prepaids/SKILL.md` — accruals, prepaids, amortization
- `close-management/SKILL.md` — month-end close sequencing
- `journal-entry-prep/SKILL.md` — supported JE preparation
- `journal-entry/SKILL.md` — debit/credit construction
- `reconciliation/SKILL.md` — GL/subledger/balance-sheet reconciliation
- `depreciation-assets/SKILL.md` — fixed assets and depreciation
- `inventory-cogs/SKILL.md` — inventory and COGS
- `payroll-reconciliation/SKILL.md` — payroll-to-GL reconciliation

### Billing, AP, AR & spending
- `contract-to-invoice/SKILL.md` — validate invoices to contracts/SOWs/rate sheets
- `usage-billing-review/SKILL.md` — usage/metered billing QA
- `accounts-payable/SKILL.md` — AP review and payment readiness
- `invoice-aging/SKILL.md` — AR aging and prioritization
- `payment-reconciliation/SKILL.md` — payment/cash matching
- `ar-collections/SKILL.md` — collections workflow
- `ar-dunning/SKILL.md` — structured customer dunning
- `purchase-order-management/SKILL.md` — purchase orders and commitments
- `expense-management/SKILL.md` — card/employee spend controls
- `stripe-reconciliation/SKILL.md` — processor settlement and fee reconciliation

### Controller, CPA & financial reporting
- `controller-review/SKILL.md` — controller-level monthly review
- `financial-statements/SKILL.md` — P&L, balance sheet, cash flow
- `variance-analysis/SKILL.md` — budget/actual and period-over-period analysis
- `board-reporting/SKILL.md` — board and management reporting
- `management-dashboard/SKILL.md` — KPI scorecards
- `technical-accounting-research/SKILL.md` — structured GAAP research
- `accounting-policy-memo/SKILL.md` — accounting policies and memos
- `gaap-disclosure-review/SKILL.md` — financial-statement disclosure review
- `revenue-recognition/SKILL.md` — revenue recognition
- `lease-accounting-asc842/SKILL.md` — ASC 842 leases
- `multi-entity-accounting/SKILL.md` — multi-entity accounting
- `intercompany-reconciliation/SKILL.md` — intercompany matching
- `consolidation/SKILL.md` — consolidated reporting and eliminations
- `business-combinations/SKILL.md` — acquisition accounting support

### FP&A, advisory & corporate finance
- `strategic-finance/SKILL.md` — long-range strategic finance
- `budgeting/SKILL.md` — annual/department budgets
- `financial-forecasting/SKILL.md` — rolling forecasts
- `scenario-planning/SKILL.md` — base/upside/downside scenarios
- `cash-flow-forecast/SKILL.md` — short- and medium-term cash forecasting
- `working-capital/SKILL.md` — AR/AP/inventory and cash conversion
- `profitability-analysis/SKILL.md` — product/service/location profitability
- `client-profitability/SKILL.md` — customer economics and pricing
- `revenue-concentration/SKILL.md` — concentration risk
- `runway-analysis/SKILL.md` — burn and runway
- `debt-covenant-analysis/SKILL.md` — leverage, DSCR, covenant headroom
- `treasury-cash-management/SKILL.md` — treasury and liquidity controls
- `capital-allocation/SKILL.md` — competing uses of capital
- `capital-structure/SKILL.md` — debt/equity financing structures
- `valuation/SKILL.md` — DCF, multiples, valuation ranges
- `investment-analysis/SKILL.md` — investment underwriting and return analysis
- `m-and-a-analysis/SKILL.md` — acquisition modeling and transaction economics
- `quality-of-earnings/SKILL.md` — normalized earnings and QoE

### Personal financial advisory & planning support
- `financial-planning/SKILL.md` — holistic cash-flow/net-worth/goal planning
- `investment-policy-statement/SKILL.md` — IPS and governance framework
- `portfolio-reporting/SKILL.md` — portfolio roll-forward, allocation, performance reporting
- `portfolio-allocation-drift/SKILL.md` — compare exposures with approved IPS/targets
- `multi-custody-aggregation/SKILL.md` — normalize/reconcile multiple custody sources
- `wealth-diagnostic-memo/SKILL.md` — HNW/family-office diagnostic memo
- `insurance-risk-review/SKILL.md` — insurance inventory and exposure review
- `personal-financial-statement/SKILL.md` — principal/guarantor financial statements
- `succession-planning-finance/SKILL.md` — ownership succession financial modeling

### Family office — core
- `family-office-reporting/SKILL.md` — consolidated reporting/NAV
- `private-investment-tracking/SKILL.md` — private/fund investment roll-forwards
- `capital-calls-distributions/SKILL.md` — commitments, calls, distributions
- `capital-call-distribution-parser/SKILL.md` — parse notices and controlled payment memo
- `family-office-liquidity/SKILL.md` — taxes, debt, calls, reserves, cash planning
- `entity-structure-mapping/SKILL.md` — entity/ownership/tax map
- `family-council-minutes/SKILL.md` — governance meeting minutes and decision log
- `philanthropic-planning/SKILL.md` — DAF/foundation/giving administration
- `estate-trust-coordination/SKILL.md` — trust/estate financial administration

### Tax & CPA tax work
Use the bundled tax playbooks including `tax-prep`, `tax-workpapers`, `tax-return-review`, `individual-tax-1040`, `partnership-tax-1065`, `s-corp-tax-1120s`, `c-corp-tax-1120`, `contractor-1099`, `basis-k1-tracking`, `estimated-tax-planning`, `entity-tax-analysis`, `state-local-tax`, `sales-tax-nexus`, `payroll-tax`, `tax-provision`, `tax-notice-response`, and `openaccountants-tax-lookup`.

### Audit, assurance & controls
Use `audit-planning`, `audit-risk-assessment`, `audit-support`, `substantive-testing`, `analytical-procedures`, `audit-sampling`, `fraud-risk`, `going-concern`, and `sox-testing` as applicable.

## Industry-specific router
Read `INDUSTRIES.md` whenever the request involves a family office/private investment, manufacturer, field-service or construction company, medical/plastic-surgery practice, or acquisition/portfolio company. Combine the industry playbooks with the generic accounting workflow rather than replacing core accounting controls.

### Family office / private equity / trusts & estates
Use `family-office-pe-investment-accounting`, `fund-investment-rollforward`, `capital-account-tracking`, `partnership-waterfalls`, `preferred-return-waterfalls`, `carried-interest-analysis`, `investment-basis-tracking`, `k1-investment-reconciliation`, `unfunded-commitment-tracking`, `investment-performance-irr-moic`, `portfolio-company-reporting`, `family-office-consolidation`, `family-office-cash-forecasting`, `trust-accounting`, `trust-distribution-tracking`, `estate-administration-accounting`, `beneficiary-reporting`, and `gift-estate-tax-readiness`.

### Manufacturing
Use `manufacturing-cost-accounting`, `standard-costing`, `actual-vs-standard-cost`, `purchase-price-variance`, `material-usage-variance`, `labor-efficiency-variance`, `overhead-absorption`, `bom-costing`, `work-order-costing`, `wip-reconciliation`, `finished-goods-reconciliation`, `inventory-reserve-obsolescence`, `scrap-yield-analysis`, `capacity-utilization`, `machine-hour-costing`, `make-vs-buy`, `product-sku-profitability`, `landed-cost`, and `cycle-count-inventory-controls`.

### Blue-collar service / construction
Use `job-profitability`, `service-line-profitability`, `technician-profitability`, `labor-utilization`, `labor-burden`, `construction-job-costing`, `construction-wip-accounting`, `contract-assets-liabilities`, `backlog-analysis`, `service-agreement-recurring-revenue`, `fleet-truck-costing`, `truck-stock-inventory`, `dispatch-kpi-analysis`, `callback-warranty-costing`, `customer-acquisition-payback`, `branch-location-profitability`, `overtime-analysis`, `field-service-cash-conversion`, and `13-week-cash-flow-service-company`.

### Plastic surgery / medical / aesthetic practice
Use `medical-practice-accounting`, `procedure-profitability`, `provider-productivity`, `provider-compensation`, `patient-deposit-deferred-revenue`, `merchant-financing-reconciliation-medical`, `refund-credit-balance-review`, `medical-supply-implant-inventory`, `operating-room-profitability`, `medical-marketing-roi`, `payor-selfpay-mix-analysis`, and `practice-cash-flow-forecast`.

### Acquisitions / post-close
Use `purchase-price-allocation`, `opening-balance-sheet`, `working-capital-true-up`, `seller-note-accounting`, `earnout-accounting`, `transaction-cost-accounting`, `goodwill-intangibles`, `post-close-integration`, `100-day-finance-plan`, `acquisition-synergy-tracking`, `sources-and-uses`, and `rollover-equity`.

### Systems & integrations
- `quickbooks-online/SKILL.md`
- `stripe-reconciliation/SKILL.md`
- `xero-integration/SKILL.md`
- `INTEGRATIONS.md` — optional OpenAccountants, Ledger MCP, Odoo MCP, Plaid/custody, and brokerage connections; use only when actually configured

## Standard professional output
When applicable provide:
1. What the records/facts show.
2. Issues, exceptions, and missing evidence.
3. Analysis and assumptions.
4. Recommended treatment or decision options.
5. Journal entries, schedules, or calculations.
6. Financial-statement, cash, tax, ownership, portfolio, operating-KPI, or covenant impact.
7. Required professional review or authoritative-source check.
8. Next actions, owners, and deadlines.

## Guardrails
- Do not invent tax rates, filing requirements, GAAP conclusions, legal rights, valuations, investment returns, audit opinions, or live integration results.
- Do not treat intercompany cash movement as proof of accounting substance.
- Do not net unrelated assets and liabilities without an established basis.
- Do not describe an estimated valuation as an appraisal or fairness opinion.
- Do not describe audit-support work as an independent audit opinion.
- Do not characterize family-office economic consolidation as changing legal ownership.
- Do not treat a capital-call notice or invoice as independent verification of new or changed wire instructions.
- Do not use financial productivity metrics as clinical-quality judgments or as the sole basis for employment decisions.
- Financial-advisory workflows may support planning, reporting, underwriting, scenario analysis, and comparison with an approved IPS, but should not present guaranteed returns or unqualified individualized securities recommendations.
- Tax, legal, audit, estate/trust, insurance, and consequential technical-accounting conclusions should identify the qualified-professional review point.

## Final quality check
Confirm entity and period; debits equal credits; roll-forwards work; cash/subledger balances tie or exceptions are listed; intercompany entries mirror; assumptions are labeled; source documents are identified; material risks are visible; integration access is verified before use; industry-specific KPIs reconcile to financial data where possible; and recommendations are operationally clear.