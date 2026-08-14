# Lovable Accounting & CFO Skill

A lightweight, Lovable-compatible **single master skill** for bookkeeping, accounting, controller, FP&A, treasury, tax-readiness, and CFO workflows.

## Import into Lovable

Use this public repository URL:

`https://github.com/PDHutch303/lovable-anthropic-finance-skills`

Lovable currently imports **one skill per GitHub repository**. The required root `SKILL.md` is named `accounting-cfo`; the specialized workflow files in this repository serve as bundled reference playbooks for that master skill.

## Master skill

- `SKILL.md` — `accounting-cfo`, the routing and quality-control playbook Lovable imports.

## Bundled workflow library

### Bookkeeping and close
- bank reconciliation
- expense categorization
- receipt processing
- close management
- reconciliation
- journal-entry preparation and posting
- financial statements
- variance analysis
- fixed assets/depreciation
- inventory and COGS
- payroll reconciliation

### AP, AR, purchasing, and spend
- accounts payable
- invoice aging
- payment reconciliation
- AR collections and dunning
- purchase-order management
- expense management
- Stripe reconciliation

### Multi-entity and controller
- multi-entity accounting
- intercompany reconciliation
- consolidation and eliminations
- audit support
- SOX/control testing
- revenue recognition
- ASC 842 lease accounting

### FP&A, treasury, and CFO
- cash-flow forecasting
- rolling financial forecasting
- annual budgeting
- working-capital management
- profitability analysis
- client profitability
- revenue concentration
- runway analysis
- debt and covenant analysis
- treasury and cash management
- management dashboards
- board reporting
- quality of earnings

### Tax and compliance readiness
- contractor/1099 readiness
- sales-tax nexus support
- tax-preparation readiness

### Accounting systems
- QuickBooks Online workflows
- Xero workflows

## Source inspiration / attribution

These compact playbooks were curated from concepts and workflows found in public repositories reviewed for this project, including:

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

The repository is intentionally compact so Lovable can import it without downloading the large upstream monorepositories. For legal, tax, audit, and material technical-accounting conclusions, the skill is designed to surface the need for qualified professional review rather than inventing conclusions.