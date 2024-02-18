# Understanding Magazine Subscription Behavior

This project is focused on analyzing the decline in magazine subscriptions over the past year for a company that expected an increase due to more people spending time at home. 
Using a provided dataset, the goal is to uncover insights into the factors affecting subscription behavior and identify strategies to counter the decline. 
The project is structured into several tasks, each aimed at understanding different aspects of subscription behavior through various predictive modeling techniques.

## Project Description

### Problem Statement
Despite the assumption that more time spent at home would lead to an increase in magazine subscriptions, the company observed a decline last year. T
he project aims to analyze customer data to identify the factors contributing to this trend. By understanding these factors, the company seeks to develop
targeted strategies to enhance subscription rates.

### Approach
- **Task 1**: Data cleansing is the first critical step, ensuring the dataset's quality is high enough for accurate modeling. This involves addressing
  missing values, outliers, and ensuring data consistency. The cleansing process and rationale are thoroughly documented.
- **Task 2 to Task 4**: Different predictive models are constructed to forecast subscription behavior:
  - A logistic regression model to predict the likelihood of subscription renewal or cancellation.
  - An SVM (Support Vector Machine) model for subscription prediction, comparing its effectiveness against logistic regression.
  - A decision tree model, limited to four branches, to visualize and predict subscription behavior.
- **Task 5**: The models are evaluated and compared based on overall accuracy, precision, and recall. This comparison will highlight
  the most significant variables affecting subscription behavior and recommend the most effective model for predicting future trends.

### Data Dictionary
The analysis leverages the following data fields to understand and predict subscription behavior:
- **ID**: Unique identifier for each customer.
- **Year_Birth**: The year the customer was born.
- **Education**: Education level of the customer.
- **Marital_Status**: Marital status of the customer.
- **Income**: Yearly household income of the customer.
- **Kidhome**: Number of children in the customer's household.
- **Teenhome**: Number of teenagers in the customer's household.
- **Dt_Customer**: Date when the customer enrolled with the company.
- **Recency**: Days since the customer's last purchase.
- **Mnt**: Amount spent on various products in the last 2 years (Wines, Fruits, Meat Products, Fish Products, Sweet Products, Gold Products).
- **NumDealsPurchase**: Purchases made with a discount.
- **NumWebPurchase**: Purchases made through the company’s website.
- **NumCatalogPurchase**: Purchases made using a catalog.
- **NumStorePurchase**: Purchases made directly in stores.
- **NumWebVisitsMonth**: Visits to the company’s website in the last month.
- **AcceptedCmp**: Indicates whether the customer accepted the offer in various campaigns.
- **Complain**: Indicates whether the customer complained in the last 2 years.
- **Country**: Location of the customer.

The project will provide the magazine company with actionable insights into improving subscription rates by understanding customer behavior and preferences.
By identifying key factors influencing subscription decisions, the company can tailor its marketing and customer engagement strategies to address the observed decline in subscriptions.
