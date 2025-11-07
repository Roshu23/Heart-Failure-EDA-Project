# Heart Failure Risk Prediction: An Exploratory Data Analysis (EDA)

### Project Goal
This project is an in-depth Exploratory Data Analysis (EDA) of a clinical dataset. The primary objective was to identify the key risk factors and hidden patterns associated with heart failure to provide actionable, data-driven insights.

---

### Key Insights & Recommendations

My analysis uncovered several critical findings:

1.  **Critical Data Quality Issue:**
    * **Finding:** The dataset had a 19% error rate, with 'Cholesterol' values impossibly recorded as '0'.
    * **Recommendation:** I recommend fixing the data collection process to validate data at the point of entry and prevent these errors.

2.  **The "Silent" Risk Group:**
    * **Finding:** The highest-risk patient group was **Asymptomatic** (reporting no chest pain) but showed a **'Flat' ST-Slope** on their ECG.
    * **Recommendation:** A new screening protocol should be implemented to target this "silent" high-risk group, as they are unlikely to be discovered by traditional symptom-based screening.

3.  **Other Key Predictors:**
    * Age, Sex (Male), Exercise-Induced Angina, and a lower Max Heart Rate were all confirmed as statistically significant predictors of heart disease.

---

### Tools & Technologies
* **Python**
* **Pandas:** For data cleaning, imputation, and manipulation.
* **Matplotlib & Seaborn:** For data visualization.
* **Jupyter Notebook:** For the complete analysis.

---

### Dataset
The `heart.csv` file used for this analysis is included in the repository.
