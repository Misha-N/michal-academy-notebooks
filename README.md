# MichAl Academy notebooks

Practical exercises for [MichAl Academy](https://github.com/Misha-N/michal-academy), a free AI course for IT and security professionals, offered as supplementary support alongside CompTIA SecAI training.

Every notebook runs on free hardware with nothing to install. Open one in Colab or Kaggle, or download it and run it wherever you like.

## Why this repo exists separately

The course site is private. Colab and Kaggle both fetch a notebook from a public URL, and neither can read a private repository, so the `.ipynb` files live here on their own.

Nothing else is here: no lesson text, no site code.

## Track 1 — Python and data foundations

| Notebook | Lesson | What it covers |
|---|---|---|
| `01-python/first-notebook.ipynb` | 1.1 | Cells, run order, and the state that survives between them |
| `01-python/python-essentials.ipynb` | 1.2 | Names refer to objects, and the aliasing bug that follows |
| `01-python/numpy-and-shapes.ipynb` | 1.3 | Arrays, shapes, broadcasting, and a shape bug that raises nothing |
| `01-python/pandas-and-real-data.ipynb` | 1.4 | Loading, dtypes, grouping, missing values, chained assignment |
| `01-python/sql-and-where-data-lives.ipynb` | 1.5 | The same four operations in SQL, NULL handling, parameterised queries |
| `01-python/plotting-and-reading-charts.ipynb` | 1.6 | matplotlib, and two ways a true chart misleads |
| `01-python/linear-algebra.ipynb` | 1.7 | Dot products, cosine similarity, and a search engine in ten lines |
| `01-python/probability.ipynb` | 1.8 | Conditional probability, Bayes by counting, heavy tails |
| `01-python/is-the-difference-real.ipynb` | 1.9 | Confidence intervals, sample size, the bootstrap |
| `01-python/gradients.ipynb` | 1.10 | Loss, slope, step, and what a learning rate does |
| `01-python/capstone.ipynb` | 1.11 | One dataset with five planted faults, none of them labelled |

## A note on the answers

Each notebook ends with its solutions folded into a `<details>` block, so they are visible to anyone reading this repository. That is deliberate: these are teaching materials, not an assessment. You get nothing from reading the answer before you have tried.

## How this stays in sync

Published from the course repo by `tools/publish-notebooks.sh`, which refuses to publish unless every notebook runs clean top to bottom in a pinned container. Do not edit notebooks here; they will be overwritten on the next publish.

## Licence

Course material by Michal Frýba. Individual notebooks credit their sources in the lesson they belong to; adapted material retains its original attribution.
