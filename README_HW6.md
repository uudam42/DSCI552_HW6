# DSCI 552 Homework 6

Tree-based classification on the APS Failure at Scania Trucks data set, including random forests, XGBoost, SMOTE, and ISLR exercises.

## Structure

```text
.
├── Homework 6 Data/
│   ├── aps_failure_training_set.csv
│   └── aps_failure_test_set.csv
├── notebook/
│   └── Agudanmu_Danmu_HW6_Submission_v2.ipynb
└── README.md
```

## How to run

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost imbalanced-learn jupyter
cd notebook
jupyter notebook Agudanmu_Danmu_HW6_Submission_v2.ipynb
```

The notebook reads the CSV files from `../Homework 6 Data/`, so run it from the `notebook/` folder. Run all cells to generate the plots, model results, and cross-validation summaries. The original data files are not modified.
