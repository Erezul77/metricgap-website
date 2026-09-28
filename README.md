# metricgap.org

**The Irrational Ground** — a framework on the structural function of π.

The metric gap ε = |π − p/q| > 0 as constraint on the formally possible.

Live at [metricgap.org](https://metricgap.org/).

## Author

Erez Ashkenazi · Independent Researcher · Upper Galilee, Israel

## Papers

1. *The Irrational Ground: π, Informational Incompleteness, and the Structure of Nature*
2. *The Polygon and the Circle: Structural Consequences of the Metric Gap*

## Structure

Single-file static site. No build step.

- `index.html` — the site
- `og-image.png` — link preview image (1200×630)

## Running locally

No dependencies or build step. Clone and serve the folder:

```sh
git clone https://github.com/erezul77/metricgap-website.git
cd metricgap-website
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

Any static server works (e.g. `npx serve .`). Opening `index.html` directly in a browser also works. Fonts load from Google Fonts, so an internet connection is needed for correct typography.

## Deployment

Auto-deployed to Cloudflare Pages on push to `main`.

## License

Content © Erez Ashkenazi. All rights reserved.
