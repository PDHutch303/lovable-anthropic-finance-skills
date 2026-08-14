---
name: expense-categorization
description: Categorize business expenses consistently using vendor history, transaction context, chart-of-accounts policy, tax treatment, and review thresholds.
user-invocable: false
---

# Expense Categorization

Use this skill to classify expenses without guessing when evidence is weak.

## Workflow
1. Confirm entity and chart of accounts.
2. Review vendor, memo, amount, transaction history, receipt/invoice, and business purpose.
3. Apply the established account mapping for recurring vendors when appropriate.
4. Distinguish operating expense, COGS, prepaid, fixed asset, inventory, owner/shareholder activity, intercompany, and reimbursable expense.
5. Flag personal, unusual, high-dollar, duplicate, undocumented, or mixed-use transactions.
6. Apply class/location/customer/project dimensions when supported.
7. Record confidence and route low-confidence items for review.

## Output
Return proposed account, dimensions, rationale, confidence, and any follow-up documentation needed.
