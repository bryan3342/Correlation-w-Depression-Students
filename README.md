# Student Depression Analysis

## Description

A collaborative CSCI 381 notebook project exploring associations between student attributes and the dataset's depression label. It contains research drafts, two deliverable notebooks, and a PDF report.

## Dependencies

Python 3, Jupyter Notebook or Google Colab, pandas, NumPy, Matplotlib, Seaborn, SciPy, and scikit-learn. No pinned dependency file is included.

## Technologies

Python notebooks, statistical exploration, and scikit-learn classifiers.

## Setup

```bash
git clone https://github.com/bryan3342/Correlation-w-Depression-Students.git
cd Correlation-w-Depression-Students
python -m venv .venv
source .venv/bin/activate
python -m pip install notebook pandas numpy matplotlib seaborn scipy scikit-learn
```

On Windows, activate the environment with `.venv\Scripts\activate` instead.

The notebooks download `depression_dataset.txt` from `falsefoobar/CS381` through a raw GitHub URL. That dataset is not bundled here, so the loading cell requires access to the external source.

## Features

- Missing-value checks, categorical analysis, and visualizations.
- Analysis of academic pressure, financial stress, sleep, diet, and study/work hours.
- Chi-square tests and classification experiments.
- Logistic regression, K-nearest neighbors, decision tree, random forest, SVM, and Gaussian naive Bayes in the deliverable notebooks.
- Classification reports and model comparisons.

These are exploratory coursework results, not a diagnostic tool or evidence of causation.

## Commands to run

```bash
jupyter notebook Project_2_Deliverable_CSCI_381.1.ipynb
```

Run cells in order. `Project_2_Deliverable_CSCI_381.ipynb` and the individual research notebooks are also retained.

## Contributors

- [Bryan Mejia (@bryan3342)](https://github.com/bryan3342)
- [Abul Hasan (@AbulHasan03)](https://github.com/AbulHasan03)
- Ahmed Ali
- [Roger Leung (@falsefoobar)](https://github.com/falsefoobar)

Credit follows the project notebooks and human authors in Git history.
