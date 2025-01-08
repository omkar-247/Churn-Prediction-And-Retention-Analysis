# Churn Prediction and Retention Analysis

## Project Overview
This project focuses on predicting customer churn and providing key retention insights using a combination of machine learning (Random Forest), SQL for data manipulation, and Power BI for data visualization. By predicting which customers are likely to churn, we can take action to reduce churn rates and improve customer retention strategies.

## Objectives
- Predict customer churn using the Random Forest algorithm.
- Provide data visualizations that highlight important trends and insights using Power BI.
- Analyze customer segments most at risk of churning and recommend retention strategies.

## Technologies Used
- **Programming Language:** Python
- **Libraries:** Scikit-learn, Pandas, NumPy, Matplotlib
- **Database:** SQL (SQL Server)
- **Visualization Tool:** Power BI
- **Machine Learning Model:** Random Forest Classifier

## Dataset
The dataset contains customer information, including:
- **Customer demographics**: Age, gender, income.
- **Service usage**: Types of services subscribed to (Internet, TV, phone).
- **Billing information**: Monthly charges, payment methods.
- **Churn indicator**: Whether the customer has churned or not.

## Key Performance Indicators (KPIs)
- **Churn Rate**: Overall churn rate, broken down by demographics and service usage.
- **Customer Segmentation**: Segment customers by age, tenure, and services.
- **Retention Metrics**: Highlight factors contributing to customer retention, such as customer support and product usage.
- **Revenue Impact**: Quantify the impact of churn on company revenue.

## Workflow
1. **Data Preprocessing:** Data was cleaned and transformed using SQL for further analysis. Null values were handled, and categorical variables were encoded for machine learning.
2. **Exploratory Data Analysis (EDA):** Performed in Power BI to visualize trends such as churn rate by age, gender, tenure, and payment method.
3. **Random Forest Model:** Implemented using Python's Scikit-learn library to predict churn based on features such as monthly charges, tenure, and services used.
4. **Business Insights and Recommendations:** Insights were gathered from Power BI dashboards to drive actionable retention strategies.

## Model Performance
The Random Forest model achieved an accuracy of **85%**, with a precision of **80%** and recall of **78%**. The confusion matrix showed that the model performed well in predicting churn, but further improvement is possible by incorporating more data.

## Insights and Recommendations

### 1. Churn Rate by Age Group
- **Insight:** Customers over the age of 50 have the highest churn rate at **31.5%**, particularly those with shorter tenures.
- **Recommendation:** Introduce loyalty programs targeting older customers to reward them for staying longer. Offering discounts on long-term plans or personalized service upgrades could help reduce churn in this age group.

### 2. Churn by Payment Method
- **Insight:** Customers using **Mailed Check** as a payment method have the highest churn rate at **37.82%**, compared to **14.80%** for those using **Credit Card** payments.
- **Recommendation:** Encourage customers to switch to online or automatic payment methods by offering small discounts or incentives. This would make payments more convenient and reduce churn.

### 3. Churn by Internet Type
- **Insight:** Customers with **Fiber Optic Internet** have a high churn rate of **41.10%**, while customers using **DSL Internet** have a significantly lower churn rate at **12.35%**.
- **Recommendation:** Investigate the root causes of dissatisfaction among Fiber Optic customers (e.g., poor connection quality, high prices). Offer special deals or enhanced service support to retain these high-value customers.

### 4. Service Usage and Churn
- **Insight:** Customers subscribed to **Streaming Music** services have a churn rate of **61.14%**, indicating that they may not find this service valuable.
- **Recommendation:** Consider bundling streaming services with other high-value services (e.g., Internet or TV) to increase perceived value. Alternatively, offer customizable packages where customers can choose the services they need.

### 5. Contract Type and Churn
- **Insight:** Customers on **Month-to-Month contracts** are more likely to churn (churn rate of **45.23%**) compared to those on **Two-Year contracts** (churn rate of **13.54%**).
- **Recommendation:** Offer long-term contract incentives, such as discounts or additional services for signing up for yearly or two-year contracts. This can encourage customers to stay for longer durations and reduce churn risk.

### 6. Churn by Tenure
- **Insight:** Customers with tenure less than **12 months** have the highest churn rate of **43.80%**, whereas customers with tenure of more than **24 months** have a churn rate of **15.42%**.
- **Recommendation:** Implement a new customer retention program for those in their first year of service. This could include offering personalized onboarding experiences, regular check-ins, or discounts after 6 months of service.

### 7. Churn by Monthly Charges
- **Insight:** Customers with **higher monthly charges** (above $80) have a churn rate of **39.50%**, whereas customers with monthly charges below $40 churn at a rate of **15.20%**.
- **Recommendation:** Introduce tiered pricing plans that offer better value for high-spending customers. Alternatively, provide flexible payment options for those struggling with higher charges to prevent churn due to financial constraints.

### Power BI Dashboard 
Here are some key visuals from the Power BI dashboard that illustrate the findings:
1. **Churn by Age and Tenure**: Visual representation of how churn rates vary across different age groups and tenure.
2. **Churn by Payment Method**: A column chart showing the churn rates for each payment method.
3. **Churn by Service Usage**:  A table showing churn distribution across different services like Streaming Music and TV.
4. **Churn Rate by Internet Type**: Churn rates segmented by Internet Type(Fiber Optic, Cable, etc.).
5. **Churn by Gender**: A donut Chart showing Churn rate among the Male and Female.

![Dashboard ](https://github.com/omkar-247/Churn-Prediction-And-Retention-/blob/main/Churn%20Analysis.png)
## Project Files
- `sql_queries`:
  - [Data Exploration SQL](https://github.com/omkar-247/Churn-Prediction-And-Retention-/blob/main/SQLQueries.sql)
- `ml_notebook`:
  - [Churn Prediction Python Code](https://github.com/omkar-247/Churn-Prediction-And-Retention-/blob/main/Machine%20Learning%20Code.pdf)
- `powerbi`:
  - [Power BI Report](https://github.com/omkar-247/Churn-Prediction-And-Retention-/blob/main/Churn%20Prediction%20And%20Retention%20Analysis.pbix)
  - [Churn Analysis Visual](https://github.com/omkar-247/Churn-Prediction-And-Retention-/blob/main/Churn%20Analysis.png)
  - [Churn Prediction Visual](https://github.com/omkar-247/Churn-Prediction-And-Retention-/blob/main/Churn%20Prediction.png)
- `presentation`:
  - [Detailed Presentation](presentation/churn_project_presentation.pdf)


