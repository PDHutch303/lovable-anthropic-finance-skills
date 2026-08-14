# Optional Integrations for the Accounting & CFO Master Skill

This repository is a Lovable-compatible **skill library**, not an MCP server bundle. External systems must be configured separately. The master skill should use an integration only when it is actually connected and should never imply access that is unavailable.

## Tax / compliance knowledge
- OpenAccountants: https://github.com/openaccountants/openaccountants — optional tax/accounting knowledge MCP. Use `openaccountants-tax-lookup` when connected.

## Ledger / ERP query
- Ledger MCP: https://github.com/minhyeoky/mcp-server-ledger — read-only ledger balances, registers, and accounts when configured.
- Odoo Accounting MCP: https://github.com/jeevanism/odoo-accounting-mcp — ERP accounting/transaction access when configured.

## Custody / portfolio data
- Plaid or equivalent bank/custody aggregation — optional source for bank and investment account data.
- IBKR or other brokerage/custodian feeds — optional source for holdings and transactions.
- Use `multi-custody-aggregation` only against connected/authorized data sources.

## Accounting systems already represented by playbooks
- QuickBooks Online — `quickbooks-online/SKILL.md`
- Xero — `xero-integration/SKILL.md`
- Stripe — `stripe-reconciliation/SKILL.md`

## Integration controls
1. Verify the connection exists before claiming live access.
2. Treat source-system IDs and timestamps as part of the audit trail.
3. Prefer read-only access for research/reconciliation unless a write is explicitly authorized.
4. Never change payment/wire instructions based only on email or a capital-call notice.
5. Preserve entity and user authorization boundaries.
6. If a live integration is unavailable, identify the required export/input rather than fabricating results.
