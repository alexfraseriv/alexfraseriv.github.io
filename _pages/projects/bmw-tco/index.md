---
layout: default
title: "BMW TCO Calculator"
permalink: /projects/bmw-tco/
description: "3-year side-by-side total cost of ownership for a 2026 BMW 430i lease vs Hyundai IONIQ 6 / Polestar 3."
---

# BMW TCO Calculator

**3-year side-by-side total cost of ownership: 2026 BMW 430i lease vs Hyundai IONIQ 6 / Polestar 3.**

→ **[Open the tool ↗](https://alexfraseriv.github.io/bmw-tco-calculator/)**
→ **[Source on GitHub](https://github.com/alexfraseriv/bmw-tco-calculator)**

---

## Why it exists

I was negotiating a new car and wanted to stop guessing whether a BMW lease was actually cheaper than buying an EV outright. Every "TCO calculator" online either oversimplified or buried the assumptions. This one keeps every input editable and shows the year-by-year cumulative cost on a single chart.

## What's in it

- **Editable driving profile:** annual miles, % city vs highway, home charging share.
- **Live scenario knobs:** gas price, electricity rate, lease payment, insurance, registration, depreciation.
- **Cumulative cost chart:** year 1 → year 3, per vehicle.
- **Share-link state:** URL captures every input you've tweaked, so you can paste a scenario into a text thread.
- **Mobile-friendly:** the use case is "open this on my phone in the dealership," so the layout collapses cleanly.

## Stack

React + Vite, Tailwind CSS, deployed to GitHub Pages via the repo's own Actions workflow. No backend — everything is computed in the browser.
