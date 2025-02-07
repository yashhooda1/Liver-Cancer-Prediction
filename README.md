# Liver-Cancer-Prediction
Predicting liver cancer outcomes using machine learning and data visualization. Includes EDA, hypothesis testing, and feature importance using SHAP.

Dataset can be found at https://www.kaggle.com/datasets/ankushpanday1/liver-cancer-predictions?resource=download

This dataset contains information about liver cancer predictions in the 30 most populated countries. 

It includes factors such as age, gender, alcohol use, healthcare access, and screening availability. 

The data helps understand how liver cancer spreads, which groups are at higher risk, and how healthcare differences affect survival chances.

This project explores liver cancer prediction using data visualization, hypothesis testing, and machine learning. The dataset contains various factors like healthcare access, lifestyle habits, and demographics, which are analyzed to uncover insights and build predictive models.

---

## **Features**

- **Exploratory Data Analysis (EDA):**
  - Geographical insights with choropleth maps for `Incidence_Rate` and `Mortality_Rate`.
  - Correlation heatmap of key features.
  - Risk factor analysis with barplots and chi-square tests.

- **Healthcare & Survival Analysis:**
  - Visualized `Survival_Rate` across `Healthcare_Access`, `Screening_Availability`, and `Treatment_Availability`.

- **Cost Analysis:**
  - Explored relationships between `Cost_of_Treatment` and `Survival_Rate` using scatter and boxplots.

- **Machine Learning:**
  - Built a Logistic Regression model to predict liver cancer risk.
  - Evaluated model performance using ROC Curve, AUC, and confusion matrix.
  - Explained feature importance using SHAP.

---

## **Dataset**
The dataset contains the following columns:
- **Country, Region:** Geographic information.
- **Incidence_Rate, Mortality_Rate:** Key cancer statistics.
- **Lifestyle Factors:** `Smoking_Status`, `Alcohol_Consumption`, `Obesity`.
- **Healthcare Factors:** `Healthcare_Access`, `Treatment_Availability`, `Cost_of_Treatment`.
- **Target Variable:** `Prediction` (Yes/No for liver cancer).
