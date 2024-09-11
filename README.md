# Credit Risk Analysis Using EDA

## Introduction
This project applies **Exploratory Data Analysis (EDA)** techniques in a real-world business scenario, focusing on risk analytics in the banking and financial services domain. The goal of this assignment is to explore and analyze consumer and loan attributes to understand patterns that may lead to loan defaults. By identifying key variables that influence default behavior, we can aid in decision-making for loan approvals and minimize financial risks.

## Problem Statement
Loan providing companies often face difficulties in assessing the creditworthiness of applicants due to insufficient or non-existent credit history. This poses two types of risks:
1. **Business Loss**: If the applicant is capable of repaying the loan, but the loan is rejected, the company loses a business opportunity.
2. **Financial Loss**: If the applicant is likely to default but the loan is approved, it results in financial loss.

By analyzing the data through EDA, we aim to identify patterns and variables that can predict loan default, ensuring that only high-risk applicants are flagged for further scrutiny while maximizing business opportunities.

### Dataset Overview
The data provided consists of three files:
1. `application_data.csv`: Contains information about clients at the time of loan application, including demographic, financial, and other variables.
2. `previous_application.csv`: Details about clients' past loan applications and their statuses (Approved, Cancelled, Refused, or Unused).
3. `columns_description.csv`: A data dictionary that explains the meaning of each variable in the datasets.

### Business Objectives
The primary objective of this project is to:
1. Identify patterns and variables that indicate whether a client will default on their loan.
2. Assist in decision-making by flagging high-risk clients for further analysis or denying the loan.
3. Optimize loan approval processes to prevent rejecting clients who are capable of repayment.

## Project Structure
The project is organized into the following sections:

### 1. Data Understanding
- **Dataset Analysis**: The `application_data.csv` and `previous_application.csv` datasets are explored to understand the variables and the relationship between them.
- **Data Dictionary**: `columns_description.csv` is used to understand the significance of each variable.

### 2. Data Cleaning and Preprocessing
- **Missing Data**: Identify and handle missing values. Appropriate techniques such as removing columns or imputing values are applied.
- **Outliers Detection**: Identify potential outliers and assess their impact on the analysis.
- **Data Imbalance**: Analyze if the data is imbalanced in terms of the target variable (clients with payment difficulties vs. others) and apply appropriate visualization techniques.

### 3. Exploratory Data Analysis (EDA)
#### Univariate Analysis
- Analyze individual variables to understand their distribution and importance.
- Visualizations include histograms, bar charts, and box plots.

#### Bivariate Analysis
- Explore relationships between pairs of variables to identify trends and correlations that are important for predicting loan default.

#### Correlation Analysis
- Segment the data into two categories: clients with payment difficulties and others.
- Identify the top correlations between continuous variables, excluding the target variable, to find the key driving factors for default.

### 4. Key Insights
- Identify the variables that are strong indicators of loan default.
- Discuss the business relevance of each identified variable and its impact on risk assessment.

### 5. Visualizations
- Use a mix of visualizations such as bar charts, scatter plots, and correlation matrices to convey the findings effectively.
- Insights are highlighted to explain why certain variables are important in differentiating between clients who are likely to default and those who are not.

### 6. Deliverables
1. **Ipython Notebook**: The notebook contains the code for the entire analysis, with comments or markdown text explaining each step.
2. **Presentation (PDF)**: A summarised presentation that includes:
   - Problem Statement
   - Approach and methodology
   - Visualizations
   - Key insights and recommendations for decision-making

## How to Use
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/namratakhb/CREDIT-EDA.git
   ```
2. Install the necessary dependencies from the `requirements.txt` file (if provided). Common libraries required include:
   - `pandas`
   - `numpy`
   - `matplotlib`
   - `seaborn`
3. Open the Jupyter notebook (`.ipynb` file) to run the EDA and visualize the findings.

## Conclusion
This project aims to provide actionable insights for a consumer finance company to minimize loan default risks. By applying EDA techniques, we can explore patterns in the data that drive loan default behavior, allowing the company to make informed decisions in the loan approval process.
