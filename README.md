# Customer Churn Storyboard
### GetIntern — Week 4 Milestone Project

## Project Overview

This project explores customer attrition in a telecommunications company using the IBM Telco Customer Churn dataset.

The analysis uses Python, Pandas, Seaborn, and Matplotlib to investigate the overall churn rate and understand how contract duration and payment method are associated with customer attrition.

## Technologies Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Google Colab / Jupyter Notebook

## Business Questions

1. What is the overall customer churn rate?
2. How does contract duration relate to customer churn?
3. Does payment method show an association with customer churn?

## Visual Analysis

### 1. Overall Customer Churn

**Key takeaways:**
- The baseline churn rate is approximately 26.54%.
- Around 73.46% of customers remain with the company.
- This baseline provides a reference for identifying higher-risk customer groups.

### 2. Contract Type and Churn

**Key takeaways:**
- Month-to-month customers show the highest churn rate.
- One-year and two-year contract customers have lower churn rates.
- Longer contracts are associated with better customer retention.

### 3. Payment Method and Churn

**Key takeaways:**
- Electronic-check users show the highest churn rate among the payment groups.
- Automatic bank transfer and credit card users show lower churn rates.
- Payment experience may be a useful area for further customer-retention investigation.

## Overall Business Insights

- The overall customer churn rate is approximately 26.54%.
- Month-to-month contracts are associated with substantially higher churn.
- Electronic-check users have a noticeably higher churn rate than other payment groups.
- Customer retention strategies could prioritize investigating these customer segments.

## Conclusion

The exploratory analysis demonstrates how customer data can be transformed into meaningful business insights through data cleaning, aggregation, and visualization.

The findings can help a business identify customer segments that may need additional retention attention. These are observational relationships and should not be interpreted as proof of causation.

## Final Output
=======================================================
CUSTOMER CHURN STORYBOARD — BUSINESS FINDINGS
=======================================================

1. Overall churn rate: 26.54%

2. Highest churn contract: Month-to-month (42.71%)
   Lowest churn contract: Two year (2.83%)

3. Highest churn payment method: Electronic check (45.29%)
   Lowest churn payment method: Credit card (automatic) (15.24%)


## Dataset Source

IBM Telco Customer Churn sample dataset:

https://github.com/IBM/telco-customer-churn-on-icp4d

**Note:** The dataset represents a fictional telecommunications company and is used for educational and analytical purposes.
