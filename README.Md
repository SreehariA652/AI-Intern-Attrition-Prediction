# 🧠 Employee Attrition Prediction

This project aims to build a machine learning model to predict employee attrition using the IBM HR Analytics dataset. The model helps HR departments proactively identify employees at risk of leaving the company.

## 📂 Dataset

The dataset is provided by IBM and contains various employee attributes including:

- Demographics (Age, Gender, Marital Status)
- Job information (Department, Job Role, Job Satisfaction, Monthly Income)
- Work environment (Work-Life Balance, Years at Company, Overtime)

Target variable: `Attrition` (Yes/No)

---

## 🧪 Problem Statement

Employee attrition is a major cost to businesses. By building a model that can predict whether an employee is likely to leave, organizations can take action to improve retention.

---

## 📊 Approach

1. **Data Preprocessing**
    - Handled missing values
    - Converted categorical variables using one-hot encoding
    - Standardized numerical columns using `StandardScaler`

2. **Train-Test Split**
    - Dataset split into training and test sets using an 80-20 ratio

3. **Model Building**
    - Built a **Random Forest Classifier** using Scikit-learn
    - Performed basic hyperparameter tuning also used `GridSearchCV`
  
4. **Evaluation**
    - Accuracy
    - Precision
    - Recall
    - F1-Score
    - Confusion Matrix
    - ROC Curve

---

## ⚙️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 🧮 Model Evaluation

| Metric       | Score  |
|--------------|--------|
| Accuracy     | 0.88   |
| Precision    | 0.82   |
| Recall       | 0.22   |
| F1 Score     | 0.35   |

Confusion matrix and ROC Curve visualizations are included in the notebook.

---

## 📌 Key Findings

- Overtime and Job Satisfaction had strong correlation with attrition.
- Employees with low job satisfaction and high overtime hours were more likely to leave.

---

## 🚀 How to Run

1. Clone the repo or download the notebook
2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
3. Run the notebook in Jupyter or any Python IDE.

---

## 📁 Files

- `attrition_prediction.ipynb` – Main notebook
- `README.md` – Project overview
- `data` - contains the dataset

---

## ✅ Submission Requirements

- ✅ Train/Test Split
- ✅ Classification Model (Random Forest)
- ✅ Basic Hyperparameter Tuning
- ✅ Evaluation Metrics: Accuracy, Precision, Recall, F1 Score
- ✅ Confusion Matrix and ROC Curve

---

## 🙋‍♂️ Author

**Sreehari**  