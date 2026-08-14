---
name: cash-flow-forecast
description: Use when building or reviewing a short- or medium-term cash forecast, especially a 13-week weekly model, liquidity runway, minimum-cash analysis, or scenario plan based on AR/AP timing, payroll, debt, taxes, capex and recurring cash drivers.
---

# Cash Flow Forecast

Follow `QUALITY-STANDARD.md`.

## Preflight
Pin opening cash and its source/as-of date, forecast start, horizon, currency, minimum cash target, available facilities, entity scope, and whether this is a new model or roll-forward.

## Build from timing, not averages where evidence exists
Use actual expected dates/cadences for:
- AR collections using aging and payment behavior;
- AP/vendor commitments;
- biweekly/semi-monthly payroll;
- rent/debt by payment date;
- taxes, insurance, capex, owner distributions and one-offs;
- known capital calls or financing events.

Use straight-line run rates only as explicit fallback assumptions when better timing data is absent.

## Weekly model controls
For a 13-week model, every week should show beginning cash + inflows - outflows = ending cash. Ending cash rolls exactly to the next week's beginning cash. Inputs should be editable assumptions, not numbers embedded invisibly in formulas.

Do not insert an automatic funding plug that prevents cash from going negative; show the actual shortfall first. If modeling a credit facility, model draw capacity, conditions, interest and availability explicitly.

## Scenarios
Use controlled base/upside/downside or sensitivity drivers for items that are genuinely uncertain, such as collection timing, revenue, payroll/hiring, capex or discretionary spending. Preserve the base case.

## Output
Provide opening cash, lowest cash and week, first week below minimum, amount required to remain above minimum, major inflow/outflow drivers, assumptions, scenario effects, financing headroom and actions.

## Verification
- weekly roll-forward works;
- total inflows/outflows reconcile to source schedules/assumptions;
- payroll and monthly/quarterly events land on real dates;
- no circular or hidden balancing formula;
- changing an input changes the affected weeks.

## Guardrails
Forecast cash is a planning model, not a booked balance. Do not schedule payments, draw debt, or promise financing without authorization.