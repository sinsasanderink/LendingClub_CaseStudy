# LENDING CLUB CASE STUDY
> This project aims to leverage Exploratory Data Analysis (EDA) to improve loan approval decisions by accurately predicting the likelihood of applicants defaulting on loans. This involves analyzing a dataset of past loan applications to identify patterns associated with default risks.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Data Preparation and Initial Assessment](#data-preparation-and-initial-asssessment)
* [Data Cleaning](#data-cleaning)
* [Exploratory Data Analysis (EDA)](#eda)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
This project aims to address the challenge of loan defaults in the lending industry, specifically for Lending Club, a major online loan marketplace. The focus is on improving loan approval processes by identifying patterns that predict the likelihood of applicants defaulting on their loans.

Background

This project is part of the MSc in AI & ML program, specifically within a statistics course. Lending Club faces significant financial risks from loan defaults. The objective of this project is to leverage data analysis to enhance the accuracy of loan approval decisions.

Business Problem

The primary business problem is the risk of financial loss due to loan defaults. By identifying 'risky' applicants who are likely to default, the project aims to minimize these losses. Accurate evaluation of loan applications is crucial for making informed decisions on whether to approve, reject, or adjust loan terms.

Dataset

The dataset used in this project `loan.csv` includes historical data on past loan applicants, covering their repayment history and loan outcomes. The key categories of loan outcomes are:
* Fully Paid: Loans that have been repaid in full.
* Current: Loans that are still being repaid.
* Charged-Off: Loans where the applicant has defaulted.

## Technologies Used
* NumPy: For numerical computations.
* Pandas: For data manipulation and analysis.
* Matplotlib: For creating visualizations.
* Seaborn: For statistical data visualization.
* Warnings: To suppress warning messages.
* Python: The primary programming language used for this project.

## Data preparation and initial assessment
* Load and inspect the dataset for completeness and integrity.
* Assess initial data quality and structure to identify areas requiring cleaning or transformation.

## Data cleaning
* Drop irrelevant, irreliable, or non-informative columns
* Handling Missing Values
* Standardizing data
* Handling Outliers
* Sanity checks

## Exploratory Data Analysis
* Summary statistics
* Univariate analysis
* Bivariate analysis

## Conclusions
Loans with below criteria are highly contributing to charged off.
* Loans with higher interest rate (>12%)
* Loans with grade 'F' and loan amount > 20K
* Higher amount loans (>13K) for small business, debt consolidation or credit card
* Borrower Debit to income ratio > 25% and loan amount > 15K
* Borrower revolving utilization > 60%
* Loans from states like NE,NV,FL
* Delinquency in 2 years > 2
* Borrower derogatory public records > 0
* Borrower annual income <50K and loan amount > 5K

## Recommendations
1. Implement Risk-Based Pricing: Develop a nuanced interest rate model that reflects diverse risk factors including DTI, credit utilization, and loan purpose, ensuring rates are commensurate with potential risks.
2. Geographic Risk Management: Establish tailored lending criteria for different regions, especially in states with historically higher default rates, to mitigate location-based risks.
3. Specialized Debt Consolidation Programs: Offer tailored financial products for debt consolidation with accompanying advisory services to help borrowers manage their debts more effectively.
4. Enhance Employment Length Evaluation: Balance the emphasis on employment length with comprehensive assessments of financial health to avoid over-prioritizing tenure over actual ability to repay.
5. Credit Utilization Strategy: Tighten approval criteria for borrowers with high credit utilization rates (>60%), recognizing this as a significant predictor of potential default.
6. Seasonal Lending Adjustments: Plan for seasonal fluctuations in loan demand, optimizing capital allocation and marketing strategies to match the observed end-of-year surge in borrowing.
7. Stringent Criteria for Small Business Loans: Increase scrutiny of small business loan applications, possibly requiring detailed business assessments or additional security to offset the higher observed risk.
8. Conservative Approach to Derogatory Records: Maintain stringent lending standards for applicants with derogatory public records or bankruptcies, potentially requiring additional assurances such as guarantors or collateral.
9. Stricter DTI Thresholds: Enforce more rigorous reviews for loans where the DTI exceeds 20-25%, identifying this range as a critical risk threshold.
10. Refined Credit History Assessment: Employ a detailed approach to credit history evaluation, wary of borrowers at the extremes of credit account numbers.
11. Robust Income Verification: Strengthen the income verification process, especially for larger loan amounts, to ensure that reported incomes are accurate and reliable.
12. Adjust Loan Terms Based on Amount: Tailor the terms of loans, particularly the maximum amount and duration, to better manage the risk profile of longer-term, larger loans.

## Acknowledgements
* Thanks to the instructors from UpGrad and IIITB for guidance and feedback.

**Study Group Members**
* Somasekhar Gangarapu
* Ursina Sanderink

## Contact
Created by [@SomasekharGangarapu] & [@sinsasanderink] - feel free to contact us!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->
