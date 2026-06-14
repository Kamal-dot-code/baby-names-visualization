# Baby Names — Visualization 3 (Gender effects)

Interactive visualization exploring **gender effects** in French baby-name data
(1900–2020): for names given to both sexes, how does the male/female split
evolve over time?

The visualization is a **dual area chart** (male vs. female counts per year) for
a selected name that has been given to both sexes, letting you see whether a
name's gendered popularity stays balanced, shifts, or flips over the decades.

## Branch to grade

The graded branch is **`master`**. The initial implementation is tagged
**`initial-implementation`**.

## Data

- `dpt2020.csv` — French baby names by department and year (1900–2020), included
  in the repo.

## How to run

This project uses [uv](https://docs.astral.sh/uv/) for a reproducible
environment (dependencies pinned in `uv.lock`).

```bash
# 1. Install uv if needed: https://docs.astral.sh/uv/getting-started/installation/
# 2. Clone the repo, then from the project root:
uv sync                       # create the environment from uv.lock
uv run jupyter lab viz3_gender.ipynb
```

Then run all cells in `viz3_gender.ipynb` to produce the interactive chart.

### Just want to view the result

Open the pre-rendered **`viz3_gender.html`** in any browser — it contains the
interactive chart with no setup required.
