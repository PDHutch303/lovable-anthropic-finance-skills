# Lovable Accounting, CPA, Family Office & CFO Skill Library

A professional-finance skill library for Lovable covering bookkeeping, accounting close, controller/CPA review, FP&A/CFO work, financial modeling, tax readiness and review, audit support, family-office/private-investment administration, private equity/acquisitions, and industry-specific accounting.

## Lovable import

Use the repository root:

`https://github.com/PDHutch303/lovable-anthropic-finance-skills`

The root skill is `accounting-cfo`. Bundled specialist playbooks support the master router.

## Quality architecture

This repository intentionally separates **breadth** from **control quality**:

- `SKILL.md` routes finance work.
- `QUALITY-STANDARD.md` defines provenance, scope, tie-outs, exceptions, materiality, approval boundaries, current-authority requirements and review-ready output.
- `EVALS.md` provides adversarial scenarios and a scoring rubric so skill quality can be tested against a no-skill baseline.
- High-consequence workflows contain deeper procedures, reconciliation identities, failure rules, evidence standards and review gates.
- Smaller specialty skills add domain logic and inherit the master quality standard.

## Coverage

### Bookkeeping & close
Onboarding, COA, receipt/invoice extraction, categorization, bank and balance-sheet reconciliation, journal entries, payroll, fixed assets, inventory/COGS, cleanup/catch-up, close management and controller review.

### AP / AR / billing
AP, purchasing, invoice aging, payments, collections/dunning, contract-to-invoice, usage billing, expense management and processor reconciliation.

### Controller / CPA / reporting
Financial statements, variance analysis, board reporting, dashboards, multi-entity/intercompany/consolidation, revenue, leases, related parties, technical accounting, accounting policies and disclosures.

### FP&A / CFO / modeling / transactions
Budgeting, rolling forecasts, 13-week and longer cash forecasts, integrated three-statement modeling, financial-model audit/debugging, working capital, profitability, concentration, debt/covenants, treasury, valuation, capital allocation/structure, M&A, LBO modeling, QoE, investment-committee memos and post-close analysis.

### Family office / private equity / planning
Entity maps, consolidated family-office reporting, private investment roll-forwards, fund NAV reconciliation/break tracing, capital calls/distributions, basis/K-1 reconciliation, unfunded commitments, IRR/MOIC and fund metrics, waterfalls/carry, liquidity, trusts/estates, philanthropy, portfolio reporting, wealth diagnostics and succession planning support.

### Tax / audit support
Tax workpapers, return review, entity/individual return readiness, estimated tax, SALT/sales tax, payroll tax, provision/notice support, audit planning/testing/analytics, fraud/going-concern/SOX support. Material positions require current authoritative guidance and qualified professional review.

### Industry packs
Family office/private equity/trusts, manufacturing, blue-collar service/construction, plastic surgery/medical/aesthetic practices, and acquisitions/post-close integration. See `INDUSTRIES.md`.

## Best-of-breed benchmark sources

The workflows are original/adapted procedures informed by strong public finance-agent and accounting resources, including:

- Anthropic Knowledge Work Plugins — close, reconciliation, statements, variance and audit-support workflows
- Anthropic Financial Services — financial modeling (DCF/LBO/3-statement/model audit), private equity, fund administration, wealth management and investment-committee workflows
- Receiptor-AI bookkeeping skills
- OpenAccountant skills
- OpenAccountants tax/accounting resources
- Xero official prompt library
- Stripe AI resources
- CaseMark skills

This repository does not copy large upstream skill files verbatim. The goal is a Lovable-oriented operating system that emphasizes evidence, reproducibility, controls, model integrity and professional review.

## Design rule

More skills are not automatically better. Add or deepen a skill when it changes behavior materially, clarifies a trigger, adds domain-specific controls, or improves a recurring deliverable. Prefer evidence-tested workflows over a directory of shallow prompts.