# Banking Dashboard - Risk Analysis (Ongoing)


# Banking Dashboard Project

## Proposed Solution

The purpose of this project is to develop a banking dashboard aimed at enhancing risk analytics in the banking and financial services sector. This dashboard will enable the company to make informed decisions regarding loan approvals based on applicant profiles.

### Objectives

- **Understand Risk Analytics**: Gain insights into how data can minimize the risk of financial loss while lending to customers.
- **Data-Driven Decisions**: Use the dashboard to assess if an applicant is likely to repay a loan, leading to informed approval or denial.

### Dataset Overview

The dataset contains detailed information about clients and their banking activities, structured across multiple interlinked tables. Key tables include:

- **Banking Relationship**: Links clients to their respective banking accounts.
- **Client-Banking**: Provides specific banking details for each client.
- **Gender**: Contains gender information linked by `GenderId`.
- **Investment Advisor**: Associates clients with their investment advisors.
- **Period**: Tracks the time-related aspects of client activities.

### Data Features

The dataset includes the following key columns:

- **Demographic Information**: Name, Age, Nationality, GenderId
- **Banking Information**: Banking Contact, Joined Bank, Fee Structure, Banking Relation Id
- **Financial Information**: Estimated Income, Superannuation Savings, Amount of Credit Cards, Credit Card Balance, Bank Loans, Bank Deposits, Checking Accounts, Saving Accounts, Foreign Currency Account, Business Lending, Properties Owned
- **Risk Assessment**: Loyalty Classification, Risk Weighting

### Steps to Implement

1. **Data Cleaning and Preparation**
   - Remove duplicates and handle missing values.
   - Ensure correct data types for each column.

2. **Data Modeling**
   - Identify relationships between various tables to build a cohesive dataset.

3. **Risk Analytics Framework**
   - Define risk factors and develop a scoring system to evaluate applicant risk.

4. **Visualization in Power BI**
   - Create interactive dashboards to visualize applicant profiles, loan approval probabilities, and historical performance.

5. **Insights and Decision Making**
   - Generate recommendations based on the data analysis to guide loan approvals.

6. **Implementation and Testing**
   - Test the dashboard with historical data and gather feedback for continuous improvement.

### Conclusion

This banking dashboard will serve as a vital tool for assessing loan applications, ultimately enhancing the decision-making process by leveraging data-driven insights into applicant risk profiles.

### P/S : THE DATASET USE FOR TRAINING PURPOSE 

Note on Data Quality and DTI Calculation
Data Quality Concerns: The dataset contains several anomalies and irregularities that may influence the accuracy of the Debt-to-Income (DTI) calculations. Specifically:

Outliers: Certain entries exhibit extreme values that skew the overall DTI ratios.
Missing Values: Some records have incomplete data, leading to potential miscalculations.
Inconsistent Formats: Variability in how data is recorded (e.g., different currencies or units) can complicate analysis.
Due to these issues, the DTI calculations derived from this dataset should be interpreted with caution. Further data cleansing might be necessary for more accurate financial assessments.
