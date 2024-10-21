# Blue Delta Airways Customer Satisfaction Prediction

## Project Overview
This project aimed to predict customer satisfaction levels for **Blue Delta Airways** based on several features such as flight delays, onboard service, and customer type. The goal was to understand the key factors that influence customer satisfaction and provide actionable insights to the airline for improving their services.

## Business Problem
- Blue Delta Airways was facing challenges in understanding why a large proportion of their customers were dissatisfied.
- We aimed to build a predictive model to identify key drivers of satisfaction and make data-driven recommendations to the airline.

## Approach
1. **Data Preprocessing**:
    - Handled missing values using **Simple Imputer** (Mode for Likert Scale data and Mean for continuous variables).
    - Removed outliers using **IQR method**, capping values beyond the 99th percentile.
  
2. **Exploratory Data Analysis**:
    - Analyzed customer demographics (age, gender, travel class) and flying patterns.
    - Identified that **82%** of customers were loyal, but **57%** were dissatisfied.

3. **Modelling**:
    - Built a **Random Forest Classifier** to predict customer satisfaction.
    - Achieved an accuracy of **96.17%** on the test data.

4. **Feature Importance**:
    - The top features impacting customer satisfaction were:
      - **Arrival Delay**: 33.8%
      - **Onboard Service**: 20.8%
      - **Customer Type**: 12.3%
      - **Gender**: 10.1%

## Key Insights
- **Arrival delays** are the most important factor in customer dissatisfaction.
- **Onboard service** quality is the second most significant factor.
- **Loyal customers** tend to be more satisfied, but improvements could be made for **specific gender groups**.

## Technologies Used
- **Python** (Pandas, NumPy, Scikit-learn)
- **Google Colab** for model development
- **Random Forest Classifier** for predictive modeling

## Next Steps
- Further improvements to the model could involve tuning hyperparameters for better accuracy or using other algorithms such as **XGBoost** for comparison.
- Explore more detailed demographic features to understand customer behavior.


