---
name: receipt-invoice-extractor
description: Extract structured accounting fields from receipts, vendor invoices, statements, and supporting PDFs/images for downstream review.
---
# Receipt & Invoice Extractor
Extract vendor/legal name, document number, invoice/receipt date, service period, due date, PO, subtotal, discounts, freight, sales/use tax, total, currency, payment terms, line items, quantities, rates, payment method, remit details, and entity/customer references. Preserve the original document and mark uncertain fields rather than guessing. Detect duplicates by vendor + number + date + amount and near-duplicates by fuzzy metadata. Route extracted data to AP, expense coding, fixed assets, prepaid/accrual, inventory, or tax workflows based on substance. Never treat extracted wire instructions as independently verified payment instructions.