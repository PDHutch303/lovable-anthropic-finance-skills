---
name: bank-reconciliation
description: Use when reconciling bank or credit-card statements to the general ledger, matching transactions, proving adjusted balances, identifying timing items and errors, or preparing supported correcting entries. Not for simply categorizing unreconciled expenses.
---

# Bank Reconciliation

Follow `QUALITY-STANDARD.md`.

## Inputs and preflight
Confirm entity, account, statement period, statement beginning/ending balances, GL beginning/ending balances, and the source transaction exports. Confirm the statement covers the complete period.

Normalize date, posting date, amount/sign, description, reference/check number, currency, and source ID without overwriting the original values.

## Matching hierarchy
1. Exact reference + amount.
2. Exact amount with close posting date.
3. Strong vendor/customer/reference evidence with close date.
4. Batch match when multiple book items exactly explain one bank settlement, or vice versa.
5. Suggested fuzzy match only when evidence is insufficient for automatic acceptance.

Do not force-match to clear the reconciliation.

## Classify unmatched items
Separate:
- deposits in transit and outstanding checks/payments;
- bank-only fees, interest, returned items or automatic transactions;
- book-only duplicates, wrong-account postings, voided items or errors;
- transfers between owned accounts;
- unidentified transactions;
- stale reconciling items.

Timing items normally carry forward; errors normally require supported book correction. Do not treat an outstanding check as an expense twice or void it merely because it is old.

## Balance proof
Show:
`statement ending balance + deposits in transit - outstanding payments = adjusted bank balance`

Then show the book balance after supported bank-only/book-error adjustments. Adjusted bank and adjusted book balances must agree exactly, subject only to explicitly justified rounding.

If they do not agree, stop and quantify the remaining difference. Look for omitted items, duplicates, sign errors, transpositions, wrong dates/accounts, and batch settlements. Never create a generic reconciliation plug.

## Output
Provide:
- account/period/source set;
- reconciliation proof;
- matched totals and match confidence summary;
- outstanding/timing items with aging;
- bank-only and book-error items;
- proposed journal entries with support;
- stale/unusual items and owner;
- final difference and reviewer status.

## Guardrails
- Preserve original transaction IDs and evidence.
- Proposed entries are not posted unless the user explicitly authorizes a connected-system write.
- Unrecognized payees, unusual round-dollar transactions, check gaps, repeated NSF items, or suspicious patterns should be escalated rather than rationalized.
- For foreign currency, separate transaction economics from FX differences and use an appropriate supported exchange-rate source.