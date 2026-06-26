# Baby Names — Visualizations

Interactive visualizations of French baby-name data (1900–2020).

## Branch to grade

- **`week2`** — Week 2 initial implementation (tagged `initial-implementation`)
- **`week1`** — Design sketches (Week 1)

## Structure

```
vis1.ipynb          Visualization 1: name popularity over time (heatmap)
viz3/               Visualization 3: gender effects (dual area chart M/F)
hints/              Provided hints notebook + GeoJSON map files
pyproject.toml      Project dependencies (uv)
```

## How to run

Requires [uv](https://docs.astral.sh/uv/getting-started/installation/).

```bash
uv sync
uv run jupyter lab
```

Then open `vis1.ipynb` (Viz 1) or `viz3/viz3_gender.ipynb` (Viz 3) in the browser.

Or open `viz3/viz3_gender.html` directly in a browser — no setup needed.
