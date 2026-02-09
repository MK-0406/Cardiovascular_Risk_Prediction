# Cardiovascular Risk Prediction

This repository contains a Jupyter notebook that demonstrates building and evaluating models to predict cardiovascular risk using the provided dataset.

**Contents**
- [cardio.ipynb](cardio.ipynb): Jupyter notebook with data loading, preprocessing, modeling, and evaluation.
- [dataset.csv](dataset.csv): CSV dataset used by the notebook.

## Quick Overview

The notebook `cardio.ipynb` walks through data exploration, preprocessing, model training, and basic evaluation for cardiovascular risk prediction. It is intended as a reproducible analysis and starting point for further experimentation.

## Requirements

- Python 3.8+ (3.10 recommended)
- Jupyter (Notebook or Lab)
- Common data science libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

Example setup:

```bash
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install jupyter pandas numpy scikit-learn matplotlib seaborn
```

## Usage

1. Ensure `dataset.csv` is in the repository root (or update the path in the notebook).
2. Start Jupyter and open the notebook:

```bash
jupyter lab
# or
jupyter notebook cardio.ipynb
```

3. Run the notebook cells in order. Read the comments and markdown cells for explanations of each step (preprocessing, feature selection, model training, evaluation).

## Data

The analysis uses `dataset.csv`. The notebook contains the code that:
- loads the CSV into a `pandas` DataFrame
- performs any necessary preprocessing (missing values, encoding, scaling)
- splits data into training and test sets

Open the notebook to see column-level handling and assumptions made for the target variable.

