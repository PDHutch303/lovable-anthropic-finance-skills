---
name: bank-reconciliation
description: Reconcile bank and credit-card accounts to the general ledger, identify unmatched items, timing differences, duplicates, and errors, and prepare correcting entries.
user-invocable: false
---

# Bank Reconciliation

Use this skill to reconcile bank or card activity to the books.

## Workflow
1. Confirm account, entity, statement period, statement ending balance, and GL ending balance.
2. Normalize transaction dates, amounts, descriptions, and reference numbers.
3. Match exact transactions first, then near matches based on date/amount/reference.
4. Identify outstanding checks, deposits in transit, bank-only items, book-only items, duplicates, reversals, and posting errors.
5. Recalculate the adjusted bank balance and adjusted book balance; they should agree.
6. Prepare proposed journal entries for fees, interest, returned items, merchant adjustments, or book errors.
7. Flag stale reconciling items and unusual transactions for review.

## Output
Provide reconciled balance, unmatched items, proposed entries, and open items with owner and aging.
