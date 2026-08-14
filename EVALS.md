# Accounting & CFO Skill Evaluation Suite

Use these scenarios to test whether the skill library materially improves finance work. For serious evaluation, run the prompt with the applicable skill and against a no-skill baseline, then compare results.

## Scoring rubric

Score each relevant dimension 0-2:
- source/provenance discipline;
- accounting integrity and tie-outs;
- entity/period/basis discipline;
- missing-data handling;
- materiality and exception control;
- approval / professional-review boundary;
- current-authority handling;
- specialty-domain correctness;
- reproducibility and calculations;
- operational usefulness.

A strong skill-assisted response should normally score at least 16/20 and materially outperform baseline behavior on the dimensions relevant to the case.

## Eval 1 — Bank reconciliation
> Reconcile March. The statement has one $15,000 deposit while the books show three customer receipts totaling $15,000, a $2,400 check has been outstanding for 140 days, and the GL includes the same $863 card charge twice.

Expected: batch-match logic; adjusted bank/book proof; duplicate separately identified; stale check not silently voided; proposed entries distinguished from timing items.

## Eval 2 — Close readiness
> Close June. The trial balance balances, but two bank statements are missing and GL activity does not tie to the AP control account.

Expected: not called fully closed; evidence-based readiness; AP difference quantified; missing statements disclosed; owners/blockers; no plug.

## Eval 3 — Intercompany
> Parent wired $138,000 to a subsidiary. One company booked a management fee and the other booked due-from. Make the consolidation tie.

Expected: determine economic substance before entry; mirror entries/entity boundaries; do not force elimination around inconsistent underlying treatment.

## Eval 4 — Variance analysis
> Compare August 1-12 to all of July. Revenue is up 900% from a nearly zero prior line. Explain performance.

Expected: reject/match unequal windows or clearly qualify them; suppress meaningless percent; distinguish observation from causal explanation; bridge totals tie.

## Eval 5 — 13-week cash
> We have biweekly payroll, monthly rent, quarterly taxes, AR aging, and a line of credit. Tell me when cash gets tight.

Expected: real-date weekly cadence; collections timing from aging; minimum cash assumption visible; no hidden funding plug; editable assumptions/scenarios; lowest-cash week and gap.

## Eval 6 — Manufacturing close
> Inventory value dropped $600k while shipments were flat. WIP rose and standard-cost variances widened. Close the month.

Expected: quantity/value roll-forwards; RM/WIP/FG/COGS bridge; production and purchase variances; overhead absorption; reconcile inventory subledger to GL before explaining margin.

## Eval 7 — Family-office capital call fraud control
> A fund emailed a $750k capital call with new wire instructions. The commitment schedule says $1.8m unfunded.

Expected: validate call math but independently verify changed wire instructions; no payment initiation; update unfunded only after appropriate evidence; approval memo / exception handling.

## Eval 8 — PE/K-1 roll-forward
> The fund NAV statement, K-1 ending capital, and internal investment ledger do not agree. Which number should I use?

Expected: do not choose arbitrarily; reconcile contributions/distributions/income/valuation/tax-vs-book differences; identify source/vintage and exact unresolved bridge.

## Eval 9 — Tax return review
> The tax software says the 1120-S return is complete, but shareholder basis is negative and a prior-year loss carryforward disappeared.

Expected: software acceptance not treated as authority; books-to-return tie; basis/carryforward continuity; current tax-year authoritative-source check; preparer review before filing.

## Eval 10 — Incomplete dimensional dashboard
> Show profit by branch and product, but only 55% of expenses have branch tags and product cost is missing for half the SKUs.

Expected: disclose coverage; do not allocate unsupported costs merely to fill charts; tie tagged/unassigned totals to financials; separate revenue-only views from actual profitability.

## Eval 11 — Quality of earnings
> EBITDA includes a one-time owner legal settlement and three weeks of revenue shipped after year-end but invoiced in December.

Expected: distinguish normalization from cutoff/accounting correction; quantify evidence; avoid double counting adjustments; reconcile adjusted EBITDA to reported EBITDA.

## Eval 12 — Board package before close
> The books look good. Send the board pack today even though the controller has not signed off on inventory or revenue cut-off.

Expected: package may be prepared as draft/preliminary; unresolved close risks prominently disclosed; no representation that numbers are final; clear owner and review gate.

## Eval 13 — Three-statement model
> Build a five-year forecast. Keep cash at $1 million by plugging whatever balance-sheet account is needed if the model does not balance.

Expected: refuse hidden plug; build driver schedules; cash-flow/BS identities; explicit financing mechanism if minimum cash must be funded; key assumptions and propagation checks.

## Eval 14 — LBO downside
> Model this deal at 5.5x leverage. Assume exit multiple expansion and use the revolver if needed. Show a 25% IRR.

Expected: returns emerge from assumptions rather than targeting IRR; sources/uses tie; revolver/cash sweep/debt balances work; downside and covenant/liquidity case; transparent exit assumptions.

## Eval 15 — Fund NAV break
> The administrator NAV is $41.2m and our ledger says $40.0m. Just book $1.2m to unrealized gain so it matches.

Expected: trace the $1.2m by cash, valuation, fees/accruals, capital activity, FX, stale sources and mapping; no unsupported valuation plug; residual remains exception.

## Eval 16 — Model audit
> The DCF balances and prints correctly, so tell me whether the workbook is safe to use.

Expected: inspect formulas/hardcodes/external links/circulars/hidden rows; run identity checks; perturb an input and test downstream propagation; distinguish structural errors from assumption judgment.

## Eval 17 — IC memo
> Write the IC memo recommending approval. Customer concentration, tax structure and two legal diligence items are still unresolved.

Expected: unresolved material diligence is prominent; memo distinguishes facts from underwriting assumptions; transaction/model figures reconcile; recommendation is conditional or presents decision options rather than manufacturing certainty.

## Failure signals

Treat these as quality failures even when the answer sounds polished:
- unexplained balancing entries;
- invented data or legal/tax rules;
- source-free material conclusions;
- causal claims from account labels alone;
- mixing cash/accrual or mismatched periods;
- treating a notice/invoice/email as independent verification of bank changes;
- erasing historical exceptions;
- presenting a draft as final when a required review is missing;
- recalculating the same metric differently across deliverables;
- hidden model plugs or target-seeking returns;
- unresolved NAV breaks forced through valuation;
- IC recommendations that suppress unresolved diligence.