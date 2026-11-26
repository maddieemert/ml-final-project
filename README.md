# DS 4021 Final Project: Predicting Counseling or Therapy Use

## Research question

Among U.S. undergraduates with elevated depressive symptoms, how well
do demographic characteristics and symptom severity predict whether
they report using counseling or therapy in the past 12 months?

## Data

We use data from the 2025–26 Healthy Minds Study. The development set
is used for preprocessing, training, hyperparameter tuning, and
cross-validation. The reporting set (`Data/HMS_reporting_set.csv`)
is reserved for the group's final evaluation.

## Individual modeling assignments

| Student | Assigned model(s) |
| --- | --- |
| Clairice Lou | Random Forest (bagging) and Gradient Boosting (boosting) |
| Maddie Emert | [Add confirmed assignment] |
| Syd Nguyen | [Add confirmed assignment] |

## Individual notebooks

The final individual modeling notebooks will be in `NOTEBOOKS/`.
Each notebook includes instructions for obtaining the development
data and running the analysis in Google Colab.

## Software and platform

The project uses Python and Jupyter notebooks (`.ipynb`) in Google Colab. The notebooks run on Colab’s Linux runtime.

- **Python version:** 3.13.18 (Google Colab)
- **Packages:** pandas, NumPy, scikit-learn, Matplotlib, and seaborn

## Repository contents

```text
.
├── README.md
├── Data/
│   └── HMS_reporting_set.csv
└── NOTEBOOKS/
    └── DS4021_individual_finalproject.ipynb
```
