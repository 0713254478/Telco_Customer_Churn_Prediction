# Telco Customer Churn Prediction

## Project Overview

This project aimed to develop a predictive model to identify customers likely to churn from a telecommunications company. Using the Telco Customer Churn dataset, the process involved thorough data cleaning, feature engineering, and model selection to optimize prediction accuracy.

A Random Forest Classifier was employed and fine-tuned through hyperparameter optimization using GridSearchCV, resulting in a model achieving approximately 80% accuracy on unseen test data. The model successfully identifies key factors influencing churn, including contract type, payment method, and customer tenure.

The insights derived from the model enable the business to design targeted retention strategies such as incentivizing customers on month-to-month contracts to switch to longer-term plans, improving payment options, and enhancing customer support services.

Overall, this project demonstrates an end-to-end application of machine learning for customer retention, providing actionable business value and a foundation for further model improvements or deployment.

---

## Business Insights and Recommendations

Based on the customer churn prediction model, several key factors influencing customer attrition have been identified:

- **Contract Type:** Customers on month-to-month contracts exhibit significantly higher churn rates compared to those on one-year or two-year contracts. This suggests that longer-term agreements contribute to customer retention.

- **Payment Method:** Customers using electronic check payment are more likely to churn than those using other payment methods, indicating potential issues with this payment channel that warrant further investigation.

- **Customer Tenure:** Customers with longer tenure tend to remain loyal, reinforcing the importance of nurturing new customers during their initial period to reduce early churn.

- **Service Features:** Certain service-related factors such as access to technical support and online security also impact churn, highlighting opportunities to improve service offerings and customer satisfaction.

**Recommendations:**

- Develop targeted retention campaigns focusing on month-to-month contract customers, possibly by offering incentives to switch to longer contracts.

- Review and optimize the electronic check payment process to improve customer experience and reduce churn.

- Enhance onboarding and engagement strategies for new customers to increase tenure and loyalty.

- Invest in improving technical support and security services to increase overall customer satisfaction.

Implementing these strategies can reduce churn rates, thereby increasing customer lifetime value and improving company revenue.

---

## How to Run

1. Clone this repository.  
2. Open the Jupyter Notebook (`Telco_Customer_Churn_Prediction.ipynb`) or Google Colab link.  
3. Install required libraries if needed: `pandas`, `scikit-learn`, `matplotlib`, `seaborn`, etc.  
4. Follow the notebook to see data loading, cleaning, modeling, and evaluation steps.
