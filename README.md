# Lending Club Case Study
> A detailed exploratory data analysis (EDA) on Lending Club's loan data to identify risk factors and mitigate credit losses.

## Table of Contents
* [General Information](#general-information)
* [Objectives](#objectives)
* [Dataset Overview](#dataset-overview)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information
Lending Club, a consumer finance marketplace specializing in offering a variety of loans to urban customers, faces a critical challenge in managing its loan approval process. The company needs to minimize financial losses due to loans given to applicants who are considered risky. This study focuses on understanding the driving factors behind loan default and providing actionable insights.

## Objectives
The primary objective is to assist Lending Club in mitigating credit losses by:
- Identifying the variables that are strong indicators of loan default.
- Helping the company make informed decisions to reduce financial losses.
- Providing recommendations for improving the loan approval process.

## Dataset Overview
The dataset includes various attributes of loan applicants and their loan status. Key columns include:
- **loan_amnt:** The loan amount requested by the borrower.
- **term:** The number of payments on the loan (36 or 60 months).
- **int_rate:** Interest rate on the loan.
- **annual_inc:** The annual income of the borrower.
- **grade:** The loan grade assigned by Lending Club.
- **purpose:** The purpose of the loan.
- **dti:** Debt-to-income ratio.
- **issue_year:** year when Loan was disbursed.
- **home_ownership:** information regarding ownership of borrower.
- **loan_status:** The current status of the loan (e.g., fully paid, charged off).

## Conclusions
Based on the EDA, several key insights were identified:
1. **Interest Rates:** Loans with interest rates between 13%-17% have a higher likelihood of default. Adjusting rates based on DTI ratios can better align with the borrower's ability to repay.
2. **Low Annual Income:** Applicants with annual incomes less than ₹40,000 are more likely to default. Offering financial education or setting maximum loan amounts based on income can help.
3. **Risk Assessment for Grades B, C, and D:** These grades have the highest default rates. Implementing stricter risk assessment criteria for these grades is recommended.
4. **Term Length:** Loans with a 60-month term are more prone to default. Evaluating the risk associated with longer-term loans and potentially limiting the maximum term can mitigate this risk.
5. **Debt Consolidation Risk:** This is the category with the highest number of loans and defaults. Careful evaluation and potentially adjusting interest rates or offering financial counseling for debt consolidation loans are suggested.
6. **High Loan Amounts:** Loans of ₹15,000 or higher are more likely to default. Conducting thorough assessments for larger loan requests and capping loan amounts for higher-risk applicants can reduce defaults.
7. **Small Business Loans:** Small business loans have higher default rates. Lending Club should consider adding more parameters to assess the risk associated with small business loans to improve risk management.
8. **Public Derogatory Records:** Borrowers with a higher number of public derogatory records are more likely to file for bankruptcy. Lending Club should implement measures to ensure there are no public derogatory records for borrowers before approving loans.


## Technologies Used
- Python - version 3.11.4
- Matplotlib - version 3.7.1
- Numpy - version 1.24.3
- Pandas - version 1.5.3
- Seaborn - version 0.12.2

## Acknowledgements
- This project was inspired by the upGrad Data Science course.
- References: Exploratory Data Analysis course by S Anand, CEO Gramener
- This project was based on Course 2 - Statistics Essential
- Based on the tutorial and data provided by Lending Club and upGrad.

## Contact
Created by Balamurali Ragupathi , Chandan Sharma(https://github.com/chandansharma10698) - feel free to contact me for any questions or feedback.
