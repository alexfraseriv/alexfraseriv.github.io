---
layout: default
title: "Car cost compare"
permalink: /projects/car-cost-compare/
description: "Side-by-side 3-year total cost of ownership for any set of cars — lease, loan, or keep your current one."
---

# Car cost compare

**Side-by-side 3-year total cost of ownership for any set of cars — lease, loan, or keep your current one.**

→ **[Open the tool ↗](https://alexfraseriv.github.io/car-cost-compare/)**
→ **[Source on GitHub](https://github.com/alexfraseriv/car-cost-compare)**

---

## Why it exists

Every "TCO calculator" online either oversimplifies or buries the assumptions. This one keeps every input editable and shows the year-by-year cumulative cost on a single chart. It was seeded by a real lease-vs-EV negotiation but works for any vehicle mix you want to throw at it.

## What's in it

- **Editable driving profile:** annual miles, % city vs highway, home charging share.
- **Live scenario knobs:** gas price, electricity rate, lease payment, insurance, registration, depreciation.
- **Lease / loan / keep-current toggle** per vehicle — the math adapts (no overage cap on loans, payoff schedule on the keep-current scenario).
- **Cumulative cost chart:** year 1 → year 3, per vehicle.
- **Share-link state:** URL captures every input you've tweaked, so you can paste a scenario into a text thread.
- **Mobile-friendly:** the use case is "open this on my phone in the dealership," so the layout collapses cleanly.

## Stack

React + Vite, Tailwind CSS, deployed to GitHub Pages via the repo's own Actions workflow. No backend — everything is computed in the browser.
