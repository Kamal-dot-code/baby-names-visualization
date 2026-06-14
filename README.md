# Baby Names — Visualizations

Interactive visualizations of French baby-name data (1900–2020).

## Branch to grade

- **`master`** — Week 2 initial implementation (tagged `initial-implementation`)
- **`week1`** — Design sketches (Week 1)

## Structure

```
viz3/               Visualization 3: gender effects (dual area chart M/F)
hints/              Provided hints notebook + GeoJSON map files
pyproject.toml      Project dependencies (uv)
```

## Data

The dataset `dpt2020.csv` is not included in the repo (too large). Download it from the course page and place it in the project root before running any notebook.

## How to run

Requires [uv](https://docs.astral.sh/uv/getting-started/installation/).

```bash
uv sync
uv run jupyter lab viz3/viz3_gender.ipynb
```

Or open `viz3/viz3_gender.html` directly in a browser — no setup needed.
