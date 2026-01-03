<img width="840" height="498" alt="1" src="https://github.com/user-attachments/assets/baf02e27-cf61-42f3-8fbc-6ef7119460c7" />## Dataset

- **Dataset Name:** Heart Failure Clinical Records
- **Source:** Kaggle or uploaded CSV
- **Number of Rows / Columns:** 299 rows, 13 columns
- **Target Variable:** DEATH_EVENT (0 = Survived, 1 = Died)

**Columns include:**
- age, anaemia, creatinine_phosphokinase, diabetes, ejection_fraction, high_blood_pressure, platelets, serum_creatinine, serum_sodium, sex, smoking, time


## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn (for feature importance)


## Analysis Steps

1. **Dataset Overview**: Checked rows, columns, and target variable distribution.
2. **Missing Values**: Verified the dataset has no missing values.
3. **Data Visualization**:
   - Histograms for numeric columns
   - Countplots for categorical variables
   - Boxplots comparing DEATH_EVENT groups
   - Correlation heatmap and pairplots
4. **Feature Importance**:
   - Used RandomForestClassifier to identify key features affecting DEATH_EVENT.
5. **Insights**:
   - Patients who died had lower ejection fraction and abnormal serum creatinine levels.
   - Older age, anaemia, diabetes, and high blood pressure increased mortality risk.



## Key Findings

- Low ejection fraction and high serum creatinine increase mortality risk.
- Older patients are more likely to die.
- Anaemia, diabetes, and high blood pressure are risk factors.
- Ejection fraction, age, serum creatinine, and platelets are the most important features for predicting DEATH_EVENT.


## How to Run

1. Clone the repository:
2. Open `Heart Failure Prediction analysis.ipynb` in Jupyter Notebook.
3. Run all cells to see the data analysis and plots.










