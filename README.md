# HR Analytics – Predict Employee Attrition

##  Objective
Use data analytics and machine learning to:
- Understand key reasons for employee attrition.
- Predict which employees are at risk of leaving.
- Provide actionable insights to help reduce turnover.

---

##  Tools & Technologies
- **Python:** Pandas, Seaborn, Matplotlib, Scikit-learn, SHAP
- **Power BI:** Dashboard visualization
- **Jupyter Notebook / Colab:** Data analysis & model training
- **MS Word or PDF:** Report documentation

---

##  Project Structure

HR-Attrition-Analysis/
 - data/ # Raw dataset (CSV/Excel)
 - notebooks/ # EDA and model building notebooks
 - visualizations/ # SHAP plots and confusion matrices
 - dashboard/ # Power BI dashboard file (.pbix)
 - report/ # Final PDF or Word report
 - README.md # Project overview


---

##  Steps & Features

### 1. Dataset Preparation
- Used IBM HR Analytics Employee Attrition dataset (1470 records).
- Checked for nulls, inconsistencies, and class imbalance.

### 2. Exploratory Data Analysis (EDA)
- Visualized attrition trends across:
  - Departments
  - Salary bands
  - Promotions & job roles
- Tools: Seaborn, Matplotlib

### 3. Preprocessing
- Label encoding for categorical features.
- Normalized numeric columns where needed.

### 4. Model Building
- Classification models:
  - Logistic Regression
  - Decision Tree
- Evaluation metrics:
  - Accuracy, Confusion Matrix
  - Classification Report (Precision, Recall, F1-Score)

### 5. Model Explainability
- Used **SHAP** to identify key features influencing attrition (e.g., Overtime, JobRole, YearsAtCompany).

### 6. Power BI Dashboard
- Visuals include:
  - Attrition by Department, Gender, EducationField
  - Salary Distribution and Promotion Impact
  - High-risk employee segments

### 7. Final Deliverables
- ** Power BI Dashboard**
- ** Model Evaluation Report (PDF)**
- ** Attrition Prevention Suggestions**

---

##  Key Insights
- **OverTime**, **JobRole**, and **YearsAtCompany** are strong predictors of attrition.
- Employees with no recent promotions or high workload show increased risk.
- Targeted actions in specific departments can reduce turnover.

---

##  How to Run
1. Clone the repo and open the Jupyter notebook.
2. Run each cell step-by-step:
   - `EDA`
   - `Preprocessing`
   - `Model Training`
   - `SHAP Analysis`
3. Open the Power BI file for dashboard exploration.
4. Review final PDF report in `/report`.

---


