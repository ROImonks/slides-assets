# slides-assets

Public asset host for the **ROImonks Slides proposal template** (`roimonks-proposal-v2`).

Google Slides' `createImage` API fetches images by **public URL**, anonymously and
server-side — so the template's brand chrome and example client visuals must live at a
publicly reachable address. This repo is that address.

## Contents

| Folder | Files | Used by |
|---|---|---|
| `logo/` | `roimonks-logo.png`, `roimonks-logo-inverse.png` | Template chrome (every deck) |
| `illustrations/` | brand flat-vector icons + device frames | Section / content slide illustration slots |
| `client/` | `alchemista-*.png` | **Example fill only** — Alchemista logo + homepage screenshot |

The `client/` images are example data for the Alchemista demo deck. Per-deal client
logos/screenshots are supplied at fill time by the engine, not stored here.

## URL form

```
https://raw.githubusercontent.com/ROImonks/slides-assets/main/<folder>/<file>
```

Nothing confidential lives here: ROImonks brand assets, generic illustrations, and a
screenshot of a client's already-public homepage.
