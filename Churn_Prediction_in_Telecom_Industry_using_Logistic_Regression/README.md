# Churn_Prediction_in_Telecom_Industry_using_Logistic_Regression

This project focuses on predicting customer churn in a telecom company. The goal is to analyze various customer-related variables and identify patterns and factors that influence churn. By understanding the key drivers of churn, the telecom company can take proactive measures to retain customers and improve customer satisfaction.

# Dataset
The dataset used for this project contains the following variables:

CustomerID: Unique identifier for each customer
Gender: Gender of the customer
SeniorCitizen: Whether the customer is a senior citizen or not
Partner: Whether the customer has a partner or not
Dependents: Whether the customer has dependents or not
Tenure: Number of months the customer has stayed with the company
PhoneService: Whether the customer has a phone service or not
MultipleLines: Whether the customer has multiple lines or not
InternetService: Type of internet service subscribed by the customer
OnlineSecurity: Whether the customer has online security or not
OnlineBackup: Whether the customer has online backup or not
DeviceProtection: Whether the customer has device protection or not
TechSupport: Whether the customer has tech support or not
StreamingTV: Whether the customer has streaming TV or not
StreamingMovies: Whether the customer has streaming movies or not
Contract: Type of contract subscribed by the customer
PaperlessBilling: Whether the customer has opted for paperless billing or not
PaymentMethod: Payment method used by the customer
MonthlyCharges: Monthly charges incurred by the customer
TotalCharges: Total charges incurred by the customer
Churn: Whether the customer churned or not (our target variable)

# Analysis Steps
Exploratory Data Analysis (EDA): Conducted an in-depth analysis of the dataset to understand the distribution of variables, identify correlations, and uncover insights related to customer churn.

1. Data Preprocessing: Performed necessary data cleaning, handling missing values, and encoding categorical variables.

2. Feature Selection: Utilized correlation analysis and domain knowledge to select relevant features for the prediction model.

3. Logistic Regression: Built a logistic regression model to predict customer churn based on the selected features.

4. Scaling Variables: Applied feature scaling to ensure all variables are within the range of 0 to 1, improving model performance.

5. Evaluation: Assessed the performance of the model using appropriate evaluation metrics such as accuracy, precision, recall, and F1-score.

6. Variable Importance: Compared the importance of variables derived from logistic regression with results from the random forest algorithm and EDA findings.

7. Hypothesis Generation: Based on the analysis, formulated hypotheses to explain the observed patterns and correlations, especially regarding contract types, internet services, and customer demographics.

# Conclusion
Through this project, we gained insights into the factors influencing customer churn in the telecom company. By analyzing various variables, we identified important features that have a significant impact on the churn rate. The findings from the logistic regression model were consistent with the correlations observed during exploratory data analysis.

Key findings:

1. Customers with a longer tenure and those with two-month contracts are less likely to churn.
2. Having DSL internet service reduces the probability of churn.
3. Total charges, monthly contracts, fiber optic internet services, and seniority can lead to higher churn rates.

Further exploration and analysis are recommended to understand the underlying reasons behind these patterns. Possible hypotheses include:

1. Total charges: Customers with lower total charges may be more price-sensitive and easily swayed by competitive offers.
2. Monthly contracts: Customers on monthly contracts have more flexibility to switch providers without penalties, making them more prone to exploring other options.
3. Fiber optic internet service: Although fiber optic services offer faster speeds, there could be underlying issues such as inconsistent service quality or higher pricing associated with fiber optic plans, leading customers to seek alternatives.
4. Seniority: It is possible that senior customers face unique challenges or preferences that contribute to a higher churn rate. This could include changing needs, competitive offers targeting senior citizens, or dissatisfaction with the services provided.

Further analysis, customer surveys, and data exploration will provide a deeper understanding of these factors and enable the telecom company to take proactive measures to reduce churn and improve customer retention.

Please refer to the accompanying code and documentation for detailed implementation steps and analysis.
