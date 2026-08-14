---
name: three-statement-model
description: Use when building, completing, extending, reviewing, or debugging an integrated income statement, balance sheet, and cash flow model with operating drivers, working capital, capex/depreciation, debt/interest, taxes, equity, scenarios, and balance checks.
---

# Three-Statement Model

Follow `QUALITY-STANDARD.md`.

Build the model from drivers and supporting schedules so the three statements are an integrated system, not three independently forecast tables.

## Preflight

Confirm entity/perimeter, historical periods, forecast horizon, periodicity, currency, source actuals, accounting basis, management assumptions, financing structure, and whether a user-provided model/template must be preserved.

If a template exists, preserve its architecture and identify its input, schedule, statement, output, and check areas before modifying it. Do not rebuild from scratch merely because a different layout would be easier.

## Historical spine

Historical income statement, balance sheet, cash flow and supporting schedules must tie to source financials/TB. Preserve historical actuals as immutable inputs. Do not overwrite history with forecast assumptions.

## Build order

1. Revenue drivers by the level of detail the evidence supports.
2. COGS / gross-margin and operating-expense drivers.
3. Working-capital schedules for AR, inventory, AP, deferred/accrued items and other material balances.
4. Capex, fixed assets and depreciation/amortization roll-forwards.
5. Debt, revolver, interest and mandatory/optional amortization.
6. Taxes using clearly stated modeled assumptions and current-authority review where tax law matters.
7. Equity, retained earnings, contributions/distributions/dividends and other financing items.
8. Integrated statements.
9. Scenarios, sensitivities and output metrics.

## Integration identities

At minimum prove for every modeled period:
- retained earnings/equity roll-forward incorporates modeled earnings and distributions/contributions as applicable;
- ending cash on the cash flow equals balance-sheet cash;
- beginning cash + cash-flow movement = ending cash;
- balance sheet assets = liabilities + equity;
- debt ending balances equal the debt schedule;
- fixed assets equal the PPE schedule;
- working-capital balances equal their supporting schedules.

Cash is normally the result of operating/investing/financing flows, not an unexplained balance-sheet plug. If a revolver is the explicit funding mechanism, model the draw/paydown logic and capacity transparently.

## Circularity

Do not hide interest/debt circularity. Use a deliberate convention such as beginning-balance interest, average-balance interest with controlled iteration, or another documented approach. The model must converge reproducibly and should not depend on accidental spreadsheet iteration settings.

## Assumption discipline

Separate historical data, management assumptions, analyst assumptions, formulas and external references. Show driver units and timing. Avoid hardcoding forecast statement cells when the value belongs in a schedule/assumption.

## Scenarios

Preserve a base case and use coherent scenario switches or driver sets for upside/downside. A scenario should change assumptions, not historical actuals or accounting identities.

## Output

Provide assumptions, integrated statements, supporting schedules, key KPIs, cash/liquidity, leverage, scenario outputs, model checks and open data gaps.

## Final model checks

- historical statements tie to source;
- balance sheet balances each period;
- cash flow ties exactly to cash;
- schedule roll-forwards foot;
- formula direction is consistent across periods;
- no hidden balancing plugs;
- key input changes propagate through all affected schedules/statements;
- scenario switch changes intended drivers only;
- no unexplained formula errors/circulars remain.

## Guardrails

Do not manufacture forecast precision beyond the assumptions available. Do not present a forecast as a prediction. Material tax, accounting, debt or covenant assumptions should identify their evidence and review point.