---
name: receipt-processing
description: Extract and validate receipt or invoice details, detect duplicates, identify missing support, and prepare transactions for bookkeeping review.
user-invocable: false
---

# Receipt Processing

Extract vendor, date, total, tax, payment method, line-item/business purpose when available, and source document reference. Match the document to an existing transaction when possible. Flag duplicates, illegible documents, missing business purpose, conflicting totals, personal items, and transactions requiring capitalization or allocation. Do not invent missing data. Output the matched transaction, proposed category, support status, exceptions, and follow-up needed.
