# Financial-Data-Mining
**Exploring Financial Data: From Raw Data to Insightful Basetables**

## Project Overview:
This project is a group assignment that focuses on constructing a data science basetable from a provided financial dataset using Python. The primary goal is to evaluate the students' skills in data processing, feature engineering, analysis, and collaborative project management.

## Purpose:
The project assesses the following competencies:

- **Data Processing:** Ability to clean and transform raw financial data to create a coherent and accurate basetable.
- **Feature Engineering:** Creation of relevant independent and dependent variables from the dataset, focusing on key financial indicators.
- **Project Organization:** Effective management and documentation of data, scripts, and other deliverables.
- **Team Collaboration:** Working effectively as a group to achieve project objectives.

## Key Components:

### Data Cleaning:
- Addressed missing values, outliers, and inconsistencies to prepare the dataset for analysis.
- Reformatted date-related variables (e.g., `Issued_Year`, `Issued_Month`, `Issued_Date`) for better readability and analysis.

### Feature Engineering:
- **Credit Card Counts:** Variables like `junior_count`, `classic_count`, and `gold_count` were created to represent the number of different types of credit cards issued by the bank. These variables provide insight into the distribution of credit products among clients based on their financial profiles.
- **DispCount:** Indicates the popularity and adoption of Disp cards, a special type of credit card with unique benefits.
- **Financial and Economic Indicators:**
  - `average_salary`: Reflects the income levels of clients in different districts, influencing their financial behavior.
  - `unemployment_rate`: Highlights economic conditions in districts, affecting clients' creditworthiness and ability to repay loans.
- **Transaction-Related Variables:**
  - **Statement Frequency:** Coded to numeric values, representing the frequency of account statements (monthly, weekly, per transaction), after validating against outliers.
  - **Number of Permanent Orders & Total Permanent Order Amount:** Calculated by counting order IDs and summing amounts by account ID, these variables provide insights into clients' financial planning and stability.

### Dependent Variables (Target Variables):
- **DV1:** Binary indicator of whether a client was granted a loan in 1997.
- **DV2:** Binary indicator of whether a client had a credit card issued in 1997.

### Pairplot Analysis:
- **Variable Relationships:** Explored using scatter plots, highlighting correlations such as between `highest_account` and `transaction_count`.
- **Age Group Insights:** Color-coded plots reveal patterns across different age groups, particularly in variables like `average_salary` and `avg_credit`.
- **Outlier Detection:** Scatter plots helped in identifying potential outliers that could impact the analysis.

### Card Issuance Analysis:
- **Cards Issued in 1996:** A variable was created to track the number of cards issued per account in 1996, offering historical context for predicting future trends.

## Documentation & Analysis:
- **Variable Descriptions:** Detailed documentation of all variables, including their names, descriptions, data types, and derived values.
- **Data Transformation:** Outlines the methods used for data correction and transformation.
- **Analysis & Visualization:** In-depth analysis and visualization of the relationships between variables, providing actionable insights into client behavior and bank performance.

## Appendix:
Includes supplementary materials and additional documentation related to the data processing and feature engineering tasks.

---

This project serves as a comprehensive exercise in data science, emphasizing the importance of data preparation, feature engineering, and collaborative work to derive meaningful insights from financial data.
