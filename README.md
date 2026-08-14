# Lovable Accounting, CFO, Tax, Family Office & Industry Finance Skills

This repository is the **source library** for a professional-finance skill suite covering bookkeeping, close, controller/CPA work, FP&A/CFO analysis, financial modeling, tax/audit support, family office/private equity, acquisitions and industry accounting.

## Important: do not import `main` into Lovable

The complete source library is intentionally larger than Lovable's per-skill file limit. Import the five purpose-built `lovable-*` branches separately instead. Each branch has its own root `SKILL.md`, shared quality controls and only the specialist playbooks relevant to that skill.

## Lovable packs

### 1. Accounting & Close
Branch: `lovable-accounting-close`

Use for bookkeeping, onboarding, transaction processing, bank/balance-sheet reconciliations, AP/AR, billing, payroll, inventory/COGS, journal entries, month-end close, controller review, financial statements, multi-entity/intercompany/consolidation, technical accounting and QBO/Xero/Stripe workflows.

### 2. CFO, FP&A, Modeling & M&A
Branch: `lovable-cfo-fpa-ma`

Use for budgeting, forecasting, cash planning, profitability, board reporting, debt/covenants, treasury, valuation, three-statement models, model audit/debugging, M&A, LBOs, quality of earnings, investment-committee memos, purchase accounting and post-close finance integration.

### 3. Tax & Audit Support
Branch: `lovable-tax-audit`

Use for tax workpapers/return review, 1040/1065/1120-S/1120 readiness, basis/K-1 tracking, estimated tax, SALT/sales tax, payroll tax, tax notices/provision, audit planning/support/testing, sampling, fraud/going concern and SOX/internal controls.

### 4. Family Office & Private Equity
Branch: `lovable-family-office-pe`

Use for consolidated family-office reporting, private-investment/fund accounting, NAV reconciliation, capital calls/distributions, basis/K-1/unfunded commitments, IRR/MOIC, waterfalls/carry, custody aggregation, trusts/estates, philanthropy, portfolio reporting and wealth-planning support.

### 5. Industry Accounting & Operating Finance
Branch: `lovable-industry-accounting`

Use for manufacturing, construction/field service and medical/aesthetic practices: standard/actual costing, WIP, inventory, job/product/procedure profitability, labor/fleet/branch economics, backlog, capacity, provider economics and industry cash-flow drivers.

## ZIP import

For any branch, select that branch on GitHub and choose **Code → Download ZIP**. Upload that ZIP in Lovable under **Settings → Skills → Import skill → Upload ZIP**. Each archive contains one wrapping repository folder with a root `SKILL.md` inside it.

Import all five packs if you want the full finance operating system. Lovable can then select the relevant skill based on each skill's trigger description instead of loading one oversized general-purpose bundle.

## Quality architecture

Every pack inherits `QUALITY-STANDARD.md`, which requires entity/period/basis discipline, provenance, tie-outs, missing-data handling, materiality, exception tracking, approval boundaries, current-authority verification and review-ready deliverables.

The source library also maintains `EVALS.md` for adversarial quality testing and `INDUSTRIES.md` / `INTEGRATIONS.md` for specialized operating guidance.

## Design rule

More skills are not automatically better. Add or deepen a playbook only when it materially changes behavior, introduces domain-specific controls, clarifies a trigger or improves a recurring deliverable.