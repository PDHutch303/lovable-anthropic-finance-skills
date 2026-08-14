---
name: lbo-model
description: Use when building, completing, reviewing, or debugging a leveraged-buyout model for an acquisition, private-equity investment, recapitalization, or investment-committee analysis, including sources and uses, operating forecast, debt schedules, cash sweep, exit valuation, IRR/MOIC and sensitivities.
---

# LBO Model

Follow `QUALITY-STANDARD.md`. Use `three-statement-model` where an integrated operating model is needed and `quality-of-earnings` when reported EBITDA requires normalization.

## Preflight

Confirm transaction perimeter, purchase date, entry valuation, EBITDA definition, existing/net debt, cash treatment, fees, rollover/reinvestment, seller financing, financing commitments/assumptions, forecast horizon, exit method, tax assumptions, and sponsor/equity ownership.

If a user supplies an LBO template, preserve it and audit its conventions before populating it.

## Sources & uses

Build a fully balanced sources-and-uses schedule including as applicable:
- purchase of equity / enterprise-value bridge;
- debt assumed/refinanced;
- minimum cash / cash to balance sheet;
- transaction and financing fees;
- seller note / earnout funding treatment;
- rollover equity;
- new debt by tranche;
- sponsor equity as the explicit balancing source only when that is the intended deal structure.

Sources must equal uses exactly. The sponsor-equity plug must be visible, not hidden.

## Operating model

Build or link a supportable operating forecast with revenue, EBITDA, capex, working capital, cash taxes and other items needed to derive free cash flow available for debt service. Preserve QoE adjustments separately from forecast operating improvements.

## Debt schedule

For each tranche capture opening balance, mandatory amortization, optional paydown/cash sweep, draws, PIK where applicable, interest rate/base/spread/floor, cash interest, maturity, minimum cash constraints and ending balance.

Enforce priority/waterfall rules. Ending debt cannot become negative. Revolver draw/paydown logic must respond to cash needs and capacity. Document interest convention and any circularity treatment.

## Returns

At exit:
1. derive exit enterprise value from the selected metric and exit multiple or other supportable method;
2. bridge EV to equity using ending debt, cash and other agreed adjustments;
3. calculate sponsor proceeds including rollover/management ownership as applicable;
4. calculate MOIC and IRR from dated or consistently periodized sponsor cash flows.

Show the actual cash-flow series used for IRR/MOIC. Do not calculate returns from mismatched signs or silently exclude interim sponsor flows.

## Sensitivities and downside

At minimum consider entry valuation, exit multiple, EBITDA/operating performance and leverage/debt paydown where decision-relevant. Include downside cases that test liquidity/covenant or debt-service pressure, not only return sensitivity.

## Return attribution

Where useful, explain value creation across earnings growth, multiple change, deleveraging/free-cash-flow generation and other discrete effects. Do not double count the same driver.

## Checks

- sources = uses;
- entry EV/equity bridge works;
- debt schedule rolls forward by tranche;
- revolver/cash sweep works without negative balances;
- interest links to the chosen debt convention;
- FCF available for debt service ties to the operating model;
- exit EV-to-equity bridge works;
- sponsor cash flows reconcile to ownership/proceeds;
- IRR/MOIC responds correctly to changed entry/exit/operating assumptions;
- sensitivity tables actually vary the intended inputs.

## Output

Provide transaction assumptions, sources & uses, operating case, debt schedule, leverage/covenant metrics, exit bridge, sponsor returns, sensitivities/downside, value-creation bridge, key risks and model checks.

## Guardrails

Returns are scenarios, not guarantees. Do not use unsupported exit multiples, financing terms, tax rules or QoE adjustments as facts. Clearly identify assumptions requiring lender, tax, legal or investment-professional review.