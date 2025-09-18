# 🏭 Garment Manufacturing Productivity Analysis

This project analyzes garment manufacturing data to understand the key factors that influence **production efficiency**.  
The notebook includes **exploratory data analysis (EDA)**, **data preprocessing**, and **machine learning modeling** to evaluate how variables such as work-in-progress, idle time, and incentives affect factory performance.

---

## 📊 Dataset

The dataset contains production line records with the following features:

* **date**: Date of the assessment  
* **day**: Day of the week  
* **quarter**: Business quarter (Q1–Q4)  
* **team_code**: Unique identifier for the team  
* **smv**: Standard Minute Value, time allocated for a task  
* **wip**: Work In Progress, number of unfinished products  
* **over_time**: Overtime worked (minutes)  
* **incentive**: Incentive provided to workers (USD)  
* **idle_time**: Idle time of workers (minutes)  
* **idle_men**: Number of idle workers  
* **no_of_style_change**: Number of style changes during production  
* **efficiency**: Target variable, efficiency percentage  

---

## ⚙️ Project Workflow

1. **Exploratory Data Analysis (EDA)**:
   * Inspected missing values, duplicates, and outliers.
   * Visualized production efficiency distribution and feature correlations.
   * Analyzed categorical variables (day, quarter) vs numerical features.

2. **Data Preprocessing**:
   * Encoded categorical variables (day, quarter, team_code).
   * Scaled numerical features to standardize input for modeling.
   * Addressed imbalances or anomalies in the dataset.

3. **Modeling & Evaluation**:
   * Built predictive models using TensorFlow/Keras.
   * Explored regression approaches to predict efficiency.
   * Evaluated models using metrics such as RMSE, MAE, and R².

---

## 📈 Results and Conclusion

- Key drivers of efficiency were identified as **SMV, WIP, overtime, and idle time**.  
- Models captured meaningful relationships between production features and efficiency.  
- Findings emphasize minimizing idle time and optimizing SMV as critical for productivity.  

**Future improvements**:
- Experiment with advanced models (e.g., XGBoost, Random Forest Regressor).  
- Add external features (e.g., seasonality, worker experience).  
- Perform hyperparameter tuning for better predictive performance.
