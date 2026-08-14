# Lovable Accounting, CPA, Tax, Audit, Family Office & Financial Advisory Skill

A Lovable-compatible **single master skill** with a broad professional-finance playbook library.

## Import into Lovable

Use:

`https://github.com/PDHutch303/lovable-anthropic-finance-skills`

Lovable imports one skill per GitHub repository. The root `SKILL.md` is the master skill named `accounting-cfo`; the specialized `SKILL.md` files are bundled playbooks routed by the master skill.

## Coverage

### Bookkeeping & onboarding
Client onboarding intake, client context profiling, bookkeeping setup, chart of accounts, structured receipt/invoice extraction, uncategorized-transaction chasing, bank/credit-card reconciliation, transaction coding, receipt processing, cleanup/catch-up, accruals/prepaids, close management, journal entries, account reconciliation, fixed assets, inventory/COGS, and payroll reconciliation.

### Billing, AP, AR & spend
Contract-to-invoice review, usage-billing QA, accounts payable, invoice aging, payment reconciliation, collections/dunning, purchase orders, employee/card expense management, and Stripe reconciliation.

### CPA, controller & accounting
Controller review, financial statements, variance analysis, management dashboards, board reporting, technical-accounting research, accounting policies, GAAP disclosure review, compilation/review preparation, related parties, subsequent events, revenue recognition, ASC 842, debt/equity accounting, business combinations, multi-entity accounting, intercompany, and consolidation.

### FP&A, corporate finance & financial advisory analysis
Strategic finance, budgeting, forecasting, scenario planning, cash-flow forecasting, working capital, profitability, client economics, concentration, runway, debt/covenants, treasury, capital allocation, capital structure, valuation, investment underwriting, M&A, and quality of earnings.

### Personal financial planning support
Holistic financial planning, investment-policy statements, portfolio reporting, portfolio-allocation drift, multi-custody aggregation, wealth diagnostic memos, insurance-risk review, personal financial statements, and succession-planning finance.

### Family office
Consolidated family-office reporting/NAV, private-investment tracking, capital calls/distributions, capital-call/distribution notice parsing with wire-verification controls, liquidity planning, entity/ownership mapping, family-council minutes/decision logs, philanthropic/DAF administration, and estate/trust financial coordination.

### Tax
Tax-prep readiness, tax workpapers, draft-return review, Form 1040 support, Form 1065 support, Form 1120-S support, Form 1120 support, contractor/1099 readiness, basis/K-1 tracking, estimated-tax planning support, entity-tax analysis, state/local tax readiness, sales-tax nexus support, payroll tax, tax provision, tax-notice response support, and an `openaccountants-tax-lookup` workflow for use when the OpenAccountants MCP is actually configured.

### Audit, assurance & controls
Audit planning, risk assessment, PBC/evidence support, substantive testing, analytical procedures, sampling, fraud-risk review, going-concern support, and SOX/internal-control testing.

### Systems & integrations
QuickBooks Online, Xero, and Stripe workflows. `INTEGRATIONS.md` documents optional OpenAccountants, Ledger MCP, Odoo Accounting MCP, Plaid/custody, and brokerage integrations. These external systems must be connected separately; the skill never assumes live access.

## Design principles

The repository is intentionally compact enough for Lovable import. The master skill distinguishes facts from assumptions, preserves legal-entity and trust boundaries, requires reconciled support, and surfaces professional-review points for consequential tax, legal, audit, estate/trust, insurance, investment, and technical-accounting matters.

Financial-planning and investment playbooks are designed for planning, reporting, underwriting, IPS frameworks, and scenario analysis—not individualized securities recommendations or guaranteed returns.

## Source inspiration / attribution

The compact playbooks were curated and adapted from concepts and workflows found in public repositories reviewed for this project, including:

- `https://github.com/anthropics/knowledge-work-plugins`
- `https://github.com/Receiptor-AI/bookkeeping-skills`
- `https://github.com/openaccountant/skills`
- `https://github.com/harshith-vaddiparthy/finance-skills`
- `https://github.com/wyre-technology/msp-claude-plugins`
- `https://github.com/XeroAPI/xero-prompt-library`
- `https://github.com/stripe/ai`
- `https://github.com/openaccountants/openaccountants`
- `https://github.com/CaseMark/skills`
- `https://github.com/aviskaar/open-org`

Additional integration candidates documented in `INTEGRATIONS.md` include:

- `https://github.com/minhyeoky/mcp-server-ledger`
- `https://github.com/jeevanism/odoo-accounting-mcp`

These files are compact Lovable-oriented adaptations rather than mirrors of the upstream repositories.