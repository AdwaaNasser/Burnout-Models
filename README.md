## Notebooks

- `Bayyinah_Burnout_Data_Preparation.ipynb`: fixes impossible values, removes leakage columns, and creates the train/test split.
- `Bayyinah_Burnout_Regression.ipynb`: trains and compares the regression models that predict `burnout_score`.
- `Bayyinah_Burnout_Classification.ipynb`: trains and compares the classification models that predict `burnout_level`.

---

## Data files

- `mental_health_burnout_tech_2026.csv`: the original dataset (never modified).
- `mental_health_burnout_tech_2026_consistent.csv`: the dataset after fixing impossible values.
- `changes_log.csv`: every value we changed, with the old and new value.

---

## `prepared/`

The processed data used to train the models:

- `X_train.csv`, `X_test.csv`: the features.
- `y_*_reg.csv`: regression target (`burnout_score`).
- `y_*_clf.csv`: classification target (`burnout_level`).
