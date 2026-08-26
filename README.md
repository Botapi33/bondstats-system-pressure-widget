# BondStats System Pressure Widget

Compact live homepage widget for the BondStats System Pressure Index.

## Mobile behavior
Below 680 px the widget switches to a dedicated compact layout rather than stacking the desktop UI. Mobile shows only:
- System Pressure Index title
- live score and state
- short two-line market interpretation
- compact pressure scale
- eligible-market count and observation date
- link to the full index

The detailed market context and desktop metadata are intentionally hidden on mobile to keep the embed short and readable in Google Sites.

## Data
Uses the BondStats Global Yields JSON and the same fixed methodology as the full System Pressure Index.

## Deploy
Upload `index.html` directly to the repository root and enable GitHub Pages from `main / (root)`.
