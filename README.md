# AI Stock Price Prediction – OBLIG2

This project is part of the DAVE3625 - Introduction to Artificial Intelligence course held at OsloMet. The notebook explores basic machine learning techniques to predict stock movement (or classification outcomes) using historical data.

---

## Contents

- `OBLIG2.ipynb` — Main Jupyter Notebook with code and results
- Basic classifiers: Decision Tree, Gaussian Naive Bayes
- Evaluation: accuracy score, data visualization

---

## Getting Started

### Requirements
- Python 3.7+
- Jupyter Notebook
- Packages:
  - pandas
  - numpy
  - matplotlib
  - scikit-learn

### How to Run
1. Clone the repo or download the notebook and dataset.
2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
   *(You may need to create this file manually or use pip freeze)*
3. Open the notebook:
   ```bash
   jupyter notebook OBLIG2.ipynb
   ```
4. Run each cell step by step.

---

## Models Used

- **DecisionTreeClassifier**
- **GaussianNB**

Each model is trained and evaluated on a holdout test set, and accuracy scores are printed.

---

## Evaluation Metrics

- Accuracy Score
- Visual plots of the model predictions

---

## Notes & Limitations

- Dataset is small and may not generalize well.
- Only basic classifiers are used.
- No cross-validation or hyperparameter tuning is included.

---

