# Neuralogic — Private Equity & Venture Capital

Landing page for Neuralogic Group's Autonomous Digital Employees (ADEs) offering for middle-market Private Equity and Venture Capital firms.

**Live:** https://vmgcompanies.github.io/neuralogic-pe-vc/

## Stack

Single static HTML file. No build step. External dependencies:

- Google Fonts (Inter, Source Serif 4)
- Calendly popup widget
- Neuralogic brand logo on Webflow CDN

## Analytics

Fires on `window.dataLayer` and `gtag` (when present):

- `cta_click` — hero + closing Calendly triggers
- `outbound_click` — homepage + industry-strip links
- `scroll_depth` — 25 / 50 / 75 / 100

## Deployment

This repo serves `index.html` from GitHub Pages (`main` branch, root).
