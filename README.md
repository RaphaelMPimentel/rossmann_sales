### **Store Sales Prediction**

---

#### **Overview**

This project focuses on predicting store sales using historical sales data combined with store metadata. The analysis spans data preparation, feature engineering, and machine learning modeling to build a robust predictive framework for sales forecasting.

---

#### **Telegram App**

I developed a Telegram application using an API that provides sales forecasts for the next 6 weeks. The app integrates predictive models with user-friendly interaction, allowing businesses to easily access future sales insights directly through Telegram.

![app](img/app.png)

---

#### **Business Problem**

The CFO of the company held a meeting with all Store Managers, requesting that each manager provide a daily sales forecast for the next 6 weeks. Following this meeting, all Store Managers reached out to you, requesting a sales forecast specifically for their respective stores. This created an immediate need for an efficient and accurate forecasting solution to meet these demands and support strategic decision-making.

---

#### **Project Structure**

1. **Data Preparation**
   - Loading and merging sales and store datasets.
   - Renaming columns to snake_case for consistency.
   - Handling missing values and adjusting data types.

2. **Exploratory Data Analysis (EDA)**
   - Statistical summary for numerical and categorical attributes.
   - Visualization of sales trends:
     - Store performance.
     - Seasonality patterns and trends over time.
   - Identification of outliers and data anomalies.

3. **Feature Engineering**
   - Transforming raw data into actionable features.
   - Encoding categorical variables and scaling numerical features.
   - Creating new features to capture trends and seasonality.

4. **Descriptive Statistics**
   - Analyzing central tendency and variability of key metrics.
   - Investigating relationships between features and target variables.

5. **Machine Learning Modeling**
   - Training and validating models including:
     - Linear Regression
     - Random Forest Regressor
     - XGBoost Regressor
   - Hyperparameter tuning for optimal performance.
   - Model evaluation using cross-validation metrics (MAE, MAPE, RMSE).

6. **Insights & Forecasting**
   - Evaluating the importance of features.
   - Visualizing model predictions and comparing them to actual sales.

---

#### **Key Features**

1. **Data Cleaning & Organization**
   - Automated pipeline for handling missing values and merging datasets.
   - Consistent formatting and preprocessing steps.

2. **Visualization**
   - Time series plots for sales trends.
   - Bar charts and heatmaps to compare store performance and correlations.

3. **Predictive Modeling**
   - Custom cross-validation function to evaluate model performance over rolling time periods.
   - Integration of ensemble and boosting models for accurate predictions.

---

#### **Tools & Libraries**

- **Data Manipulation:** pandas, numpy
- **Visualization:** seaborn, matplotlib
- **Modeling:** scikit-learn, xgboost, boruta

---

#### **Insights**

- **Seasonality:** Sales demonstrate clear seasonal trends, with peaks during specific months and holidays.
- **Store-Specific Trends:** Certain stores consistently outperform others, indicating the need for tailored strategies.
- **Feature Importance:** Features like promotions, holidays, and store type significantly impact sales.

---

#### **Next Steps**

- Enhance feature engineering by incorporating external factors such as weather and economic indicators.
- Deploy the model in a real-time environment to forecast future sales dynamically.

---

#### **Acknowledgments**

This project was conducted using open-source libraries and datasets. Special thanks to contributors for their efforts in building tools and frameworks used in this analysis.

