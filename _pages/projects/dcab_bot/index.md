---
layout: default
title: "DCA Buyer Bot"
permalink: /projects/dcab_bot/
description: "Automated dollar-cost-averaging bot that schedules periodic asset purchases."
---

# DCA Buyer Bot

**Dollar Cost Average Buyer Bot** — a personal-use bot that automates DCA by scheduling periodic asset purchases.

---

## Status

Archived prototype. Kept here so the legacy /projects/dcab_bot/ route stays alive.

## Concept

Schedule a fixed-cadence, fixed-dollar-amount buy across a basket of assets, with idempotent execution and human-readable logs. The interesting parts were the broker abstraction (so adapters could be swapped) and the small reconciliation tool that flagged failed buys without paging me at 2am.
