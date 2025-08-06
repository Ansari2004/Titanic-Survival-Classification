# 🚢 Titanic Survival Classification

Predict survival outcomes on the Titanic using machine learning (XGBoost) and the Kaggle dataset.

---

## 📁 Dataset

* **train.csv** – Training data with survival labels
* **test.csv** – Test data without survival labels
  *(Download both from [Kaggle Titanic Challenge](https://www.kaggle.com/c/titanic))*

---

## 🔧 Requirements

Install required packages:

```bash
pip install pandas numpy scikit-learn xgboost
```

---

## 📂 Project Structure

```
📆 titanic-survival-classification/
├── Titanic Survival Classification.ipynb
├── train.csv
├── test.csv
└── submission.csv (generated)
```

---

## 🚀 How to Run

1. Clone this repo:

   ```bash
   git clone https://github.com/your-username/titanic-survival-classification.git
   cd titanic-survival-classification
   ```

2. Add `train.csv` and `test.csv` to the folder (from Kaggle).

3. Launch the notebook:

   ```bash
   jupyter notebook "Titanic Survival Classification.ipynb"
   ```

4. Run all cells to preprocess data, train the model, and generate `submission.csv`.

---

## 🧐 Methodology

* **Preprocessing**: Handle missing values, drop irrelevant columns, encode categoricals
* **Feature Engineering**: `Title`, `FamilySize`, `IsAlone`
* **Model**: XGBoost with train-validation split
* **Output**: Predictions saved to `submission.csv`

---

## 📊 Result

* **Validation Accuracy**: \~80.45%
* **Submission file** ready for Kaggle evaluation

---

