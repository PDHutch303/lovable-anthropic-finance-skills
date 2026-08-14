---
name: wip-reconciliation
description: Reconcile manufacturing work-in-process quantities and value between production records, inventory subledger, and GL.
---
# WIP Reconciliation
Roll forward beginning WIP + material/labor/overhead additions - completed/transferred cost - scrap/write-offs = ending WIP. Tie to open work orders and physical/operational status. Flag old WIP, negative balances, completed jobs not relieved, and unsupported manual entries.