# Pinterest ROI Calculator

A single-page, client-side calculator that estimates when Pinterest marketing spend breaks even, and projects revenue and ROI beyond that point.

**Live example:** open `index.html` in any browser — no build step or server required.

## What it does

Given a monthly Pinterest investment and either a minimum or average order value, the calculator works out:

- the number of annual orders needed to break even
- monthly and annual investment totals
- a set of forward-looking scenarios (break-even, faster-earning, healthy growth, strong performance, high growth)
- an interactive projection with a slider for a custom number of projected orders, showing revenue, net profit/loss, ROI, and revenue multiple

It supports English and Ukrainian, and EUR/USD/UAH currency display.

## Tech

Plain HTML, CSS, and vanilla JavaScript — no frameworks, no dependencies, no build tooling. All calculation logic lives in a single `<script>` block in `index.html`.

## Usage

Clone the repo and open `index.html` directly, or serve the folder with any static file server:

```bash
npx serve .
```

## License

MIT — see [LICENSE](LICENSE).
