---
name: financial-model-audit
description: Use when auditing, debugging, quality-checking, or reviewing an Excel/Google Sheets financial model for formula integrity, hidden hardcodes, broken links, inconsistent formulas, circularity, sign/unit/period errors, statement tie-outs, schedule roll-forwards, scenario propagation and output reliability.
---

# Financial Model Audit

Follow `QUALITY-STANDARD.md`.

Audit the model as a dependency system. A model can look polished and still be structurally wrong.

## Preserve the original

Work from a copy/version where possible and document changes. Do not silently replace formulas or assumptions during an audit unless the user explicitly requests remediation after findings are identified.

## Map the model

Identify:
- input/assumption areas;
- historical data;
- calculation/support schedules;
- financial statements;
- debt/tax/PPE/working-capital schedules;
- scenario/sensitivity logic;
- outputs/valuation/returns;
- checks;
- hidden sheets/rows/columns and external links.

## Structural audit

Scan for:
- hardcodes inside formula regions;
- formulas inconsistent across a row/column/time series;
- overwritten formulas;
- broken/external links;
- `#REF!`, `#VALUE!`, `#DIV/0!`, `#N/A` and other errors;
- unintended circular references;
- formulas that omit inserted rows/columns;
- sign-convention inconsistencies;
- percent vs decimal, thousands vs units, currency or date-period mismatches;
- hidden or unused assumptions feeding outputs;
- manual plugs and balancing items;
- values that should be linked to source schedules but are retyped.

## Financial integrity tests

Apply only the tests relevant to the model:
- three-statement balance and cash-flow tie;
- retained earnings/equity roll-forward;
- PPE/depreciation roll-forward;
- debt/interest roll-forward;
- working-capital balances and cash-flow signs;
- sources & uses;
- LBO debt waterfall and exit bridge;
- DCF enterprise/equity bridge;
- fund/NAV or capital-account roll-forwards;
- waterfall/distribution totals;
- scenario/sensitivity mechanics.

## Dynamic propagation test

Change a small number of safe copied inputs and verify expected downstream effects reach the schedules, statements and outputs. Restore original assumptions afterward. A workbook of hardcoded outputs can pass static visual review and fail this test.

## Findings classification

Separate:
- critical structural/model error;
- formula inconsistency;
- broken linkage/data issue;
- questionable modeling convention;
- unsupported assumption;
- cosmetic/usability issue.

Do not label an assumption "wrong" simply because another assumption is preferred; distinguish model mechanics from business judgment.

## Output

Provide model map, check status, prioritized findings with sheet/cell/range evidence, financial/output impact, remediation recommendation, and retest results if changes are authorized.

## Guardrails

Do not rewrite the model wholesale during an audit. Preserve formulas and source lineage. If the tool cannot evaluate formulas or inspect hidden/external links reliably, disclose that limitation rather than certifying the model.