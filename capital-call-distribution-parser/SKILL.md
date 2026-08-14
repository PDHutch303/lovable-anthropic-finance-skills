---
name: capital-call-distribution-parser
description: Parse private-fund and direct-investment capital-call/distribution notices, update commitment schedules, and prepare controlled approval memos.
---
# Capital Call / Distribution Parser
Extract fund/SPV, investor entity, notice date, due/payment date, call or distribution amount, purpose, commitment remaining, recallable amount, withholding, fees, and stated wire/remit details. Tie the notice to the approved investment record and commitment ledger. Recalculate commitment roll-forward and expected cash impact. For payments, never approve new or changed wire instructions solely from the notice; compare to previously approved custody/vendor records and require independent verification under treasury controls. Produce an approval memo, accounting treatment, cash forecast impact, and exception list.