# Customer Churn Analysis: Data-Driven Insights for Retention

## 📌 Project Overview

Customer churn is one of the most critical metrics for any subscription-based business. This project analyzes a telecommunications dataset to identify the primary drivers of customer attrition. By uncovering patterns in demographics, account details, and service usage, the goal is to provide actionable recommendations that help businesses retain their customers and maximize Lifetime Value (LTV).

## 📊 Key Findings from Analysis

The analysis conducted in the Jupyter Notebook revealed several high-impact insights:

* **Contract Type:** Customers on **Month-to-month** contracts are significantly more likely to churn compared to those on one or two-year contracts.
* **Tenure:** The risk of churn is highest in the first few months. Customers who stay past the first year are much more likely to remain long-term.
* **Service Adoption:** Customers who **do not** use value-added services like *Online Security*, *Tech Support*, and *Online Backup* show much higher churn rates.
* **Payment Friction:** There is a notable correlation between **Electronic Check** payments and higher churn, suggesting potential friction in the billing process or a specific customer segment preference.
* **Demographics:** Senior citizens exhibit a higher percentage of churn relative to their population size within the dataset.

---

## 🛠️ Technical Workflow

1. **Data Cleaning:** Handled missing values in `TotalCharges` (converted from object to float) and standardized `SeniorCitizen` flags.
2. **Exploratory Data Analysis (EDA):** Leveraged `Seaborn` and `Matplotlib` for visual distribution analysis.
3. **Categorical Analysis:** Performed grouping and percentage calculations to compare churn across various service tiers.
4. **Feature Engineering:** Transformed raw data into a more readable format for business stakeholders (e.g., converting 1/0 to Yes/No).

---

## 🚀 Getting Started

### Prerequisites

* Python 3.x
* Pandas
* Numpy
* Matplotlib
* Seaborn

### Execution

1. Clone this repository.
2. Ensure `Customer Churn.csv` is in the project root.
3. Open `customer_churn_analysis.ipynb` in Jupyter Notebook or Google Colab.
4. Run all cells to see the visualizations and data processing steps.

## 📂 Project Structure

* `customer_churn_analysis.ipynb`: The main analytical engine.
* `Customer Churn.csv`: Raw dataset containing customer profiles.
* `README.md`: Project documentation and business summary.

---

**Author:** [Monayem Hossain Limon](https://github.com/Limon00001)
