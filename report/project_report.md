# AI-Powered Employee Attrition Prediction

## 🔍 Objective
To develop an AI system that predicts whether an employee is likely to leave a company using historical HR data. The goal is to enable proactive employee retention strategies and reduce turnover costs.

## 📊 Dataset
- Source: [IBM HR Analytics Employee Attrition Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- Features include: Age, Department, JobRole, MonthlyIncome, JobSatisfaction, OverTime, etc.
- Target variable: `Attrition` (Yes/No)

## 🧠 Approach
1. **Data Preprocessing**:
   - Handled missing values
   - Encoded categorical variables
   - Performed feature scaling

2. **Exploratory Data Analysis (EDA)**:
   - Visualized attrition distribution and key feature correlations
   - Noted high attrition among employees with low job satisfaction and overtime

3. **Modeling**:
   - Used RandomForestClassifier
   - Achieved accuracy of ~85% on test set

4. **Evaluation**:
   - Used metrics: Accuracy, Precision, Recall, F1-score
   - Confusion matrix showed good balance between false positives and false negatives

## 💡 Key Insights
- Employees working overtime and earning lower income were more likely to leave.
- Job satisfaction, environment satisfaction, and years at company were important predictors.

## 🏁 Conclusion
The developed model can be used by HR teams to flag at-risk employees and implement retention strategies. While effective, future enhancements can include:
- Live dashboard integration
- External data (e.g., engagement survey results)
- Fairness checks to ensure ethical AI

---

**Submitted by:** Sreehari A  
**Role:** AI Intern Applicant  
**Date:** August 2025
