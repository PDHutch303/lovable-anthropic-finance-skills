---
name: family-office-reporting
description: Use when preparing consolidated family-office reporting across legal entities, trusts, operating companies, bank/custody accounts, private investments, debt, commitments, distributions, taxes and liquidity while preserving legal ownership boundaries.
---

# Family Office Reporting

Follow `QUALITY-STANDARD.md`.

## Reporting perimeter
Map each entity/trust/account/investment to legal owner, beneficial/reporting owner if different, account/custodian, tax classification, currency, and consolidation/reporting treatment. Economic aggregation does not change legal ownership.

## Source hierarchy
Reconcile cash/custody to statements; operating entities to closed books; private investments to manager statements/capital notices/K-1s; debt to lender statements; ownership to governing/official records. Record source date because private-asset NAVs may be stale.

## Core roll-forwards
For each investment/entity where applicable show beginning value + contributions/calls + income/gains or valuation change - distributions/fees = ending value. Separate book, tax-basis, market/NAV and estimated values rather than blending them.

## Consolidated views
Produce as supported:
- net worth / NAV by owner, entity and asset class;
- cash and near-term liquidity;
- debt and guarantees;
- private investment cost, NAV, realized/unrealized, unfunded commitments;
- capital calls/distributions and expected obligations;
- tax/estimated-payment reserve;
- trust/estate distributions;
- concentration and stale/missing valuation flags.

Eliminate true intercompany/duplicate economic positions only in an explicitly consolidated view and preserve the underlying legal-entity balances.

## Controls
- opening + activity = ending for investments and cash;
- consolidated totals reconcile to components and documented eliminations;
- account/asset appears once economically unless intentionally shown in both legal and look-through views;
- valuation date/source visible;
- unfunded commitment reconciles to notices/manager statements and internal ledger.

## Output
Provide reporting date, coverage/source map, consolidated summary, entity/asset schedules, liquidity/commitment calendar, exceptions, stale valuations, ownership/tax notes, and next actions.

## Guardrails
Do not infer legal ownership from who paid for an asset, combine trust property with individual property without clear reporting treatment, or portray estimated private-company values as appraisals.