# The Burning Question

**Can the AI Economy Afford Itself?**

A standalone HTML article examining the physical and economic infrastructure underpinning the AI industry — energy consumption, capital expenditure, and the sustainability of current revenue models.

Published: April 2026  
Companion piece to: *The Great Inversion*

## Contents

- [`burning-question.html`](burning-question.html) — The article itself; open directly in a browser, no build step required.
- [`scripts/create_clean_tar.sh`](scripts/create_clean_tar.sh) — Creates a clean `.tar.xz` archive of the project for distribution.

## Topics Covered

- The energy cost of AI inference and agentic workloads
- The Jevons Paradox applied to AI efficiency gains
- Hyperscaler capex arms race ($400B+ in 2025)
- Revenue model sustainability for frontier AI providers
- Bull/base/bear scenarios for AI infrastructure economics

## Usage

Open `burning-question.html` in any modern browser. No server, dependencies, or build tools required.

To create a distributable archive:

```bash
./scripts/create_clean_tar.sh
```

The archive is written to `dumps/` (excluded from version control).
